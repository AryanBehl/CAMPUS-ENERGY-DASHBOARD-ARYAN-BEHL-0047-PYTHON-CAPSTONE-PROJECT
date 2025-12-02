# Campus Energy Dashboard

## Objective
Analyze campus building electricity usage to identify energy-saving opportunities through automated data processing and visualization.

## Dataset
- 3 sample buildings (Academic, Library, Dormitory)
- Hourly meter readings for 2025
- Generated using realistic consumption patterns with diurnal/seasonal variations

## Methodology
1. **Data Ingestion**: Automated CSV loading with error handling
2. **Aggregation**: Daily/weekly summaries using Pandas groupby/resample
3. **OOP Modeling**: Building/MeterReading classes for scalable architecture
4. **Visualization**: 4-panel Matplotlib dashboard (trends, comparisons, peaks)
5. **Export**: Cleaned data, summaries, and executive report

## Key Insights
- Identifies highest consuming buildings
- Reveals peak load patterns
- Provides actionable energy-saving recommendations

## Files Generated
- `output/dashboard.png` - Complete visualization
- `output/cleaned_energy_data.csv` - Processed dataset
- `output/building_summary.csv` - Building statistics
- `output/summary.txt` - Executive report
