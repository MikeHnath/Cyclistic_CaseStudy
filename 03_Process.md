# 03 – Process

## Tools Used
- **R (Posit Cloud)** for data import, cleaning, transformation, and analysis.
- Libraries: `tidyverse`, `lubridate`, `janitor`, `ggplot2`.

---

## Cleaning Steps
1. **Imported CSV files** for Q1 2019 and Q1 2020.
2. **Standardized column names** with `janitor::clean_names()`.
3. **Renamed fields** in 2019 data to match 2020 schema:
   - `trip_id` → `ride_id`
   - `start_time`/`end_time` → `started_at`/`ended_at`
   - `from_station_*` / `to_station_*` → `start_station_*` / `end_station_*`
   - `usertype` values converted from `"Subscriber"/"Customer"` to `"member"/"casual"`.
4. **Created new columns**:
   - `ride_length` = `ended_at - started_at` (in minutes)
   - `day_of_week` = extracted from `started_at` (Sunday = 1 through Saturday = 7).
5. **Matched column types**:
   - Converted 2019 `ride_id` from numeric to character to match 2020.
6. **Filtered out bad data**:
   - Removed rides with `ride_length <= 0` or `ride_length >= 1440` minutes (24 hours).
7. **Merged datasets** into one dataframe for analysis.
8. **Exported cleaned data** to `/outputs/cleaned_combined.csv`.

---

## Data Integrity Checks
- Verified no missing values in key fields (`ride_id`, `started_at`, `ended_at`, `member_casual`).
- Spot-checked random rows to ensure `ride_length` values were positive and reasonable.
- Ensured consistent day-of-week mapping.

---

## Output
A clean, combined dataset ready for analysis:
- **Rows:** 791,956 rides (Q1 2019 + Q1 2020 after cleaning)
- **Columns:** 10 fields, including `ride_length` and `day_of_week`.
- **File:** `/outputs/cleaned_combined.csv`
