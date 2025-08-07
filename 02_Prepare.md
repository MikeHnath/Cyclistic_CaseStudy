## Data Sources
The dataset used for this analysis comes from [Divvy Trip Data](https://divvy-tripdata.s3.amazonaws.com/index.html), made available by Motivate International Inc. under the [Data License Agreement](https://www.divvybikes.com/data-license-agreement). Although Cyclistic is fictional, this real-world dataset closely represents the type of information a bike-share company would use.

For this case study, I used:
- **Q1 2019**: `Divvy_Trips_2019_Q1.csv`
- **Q1 2020**: `202003-divvy-tripdata.csv`

---

## Privacy Considerations
- No personally identifiable information (PII) is included in the dataset.
- Rider IDs are anonymized.
- The dataset only contains trip-level details such as start/end time, station, and bike type.

---

## Data Organization
- Each CSV file contains one quarter of trip data.
- The structure changed in 2020:
  - 2019: `trip_id` as numeric, station fields named `from_station_name`/`to_station_name`.
  - 2020: `ride_id` as text, station fields named `start_station_name`/`end_station_name`.
- Additional fields in 2020 include GPS coordinates and bike type.

---

## ROCCC Evaluation
- **Reliable:** Data comes from an established bike-share program provider.
- **Original:** Published by the data owner.
- **Comprehensive:** Includes all recorded trips for the selected quarters.
- **Current:** Data represents Q1 2019 and Q1 2020; sufficient for year-over-year comparison.
- **Cited:** Proper attribution given to Motivate International Inc.

---

## Suitability
This dataset is suitable for answering the business question because it:
- Clearly distinguishes between `member` and `casual` riders.
- Includes timestamps and station data for usage pattern analysis.
- Is complete for the selected periods, allowing direct year-over-year comparison.
