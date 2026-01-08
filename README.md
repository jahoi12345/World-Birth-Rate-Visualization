# World Birth Rate Visualization

An interactive data visualization dashboard displaying global birth rate trends from 1960 to 2023, using World Bank demographic data.

## Live Demo

https://jahoi12345.github.io/World-Birth-Rate-Visualization/

## Features

- **Interactive Choropleth Map**: Color-coded world map showing crude birth rates by country
- **Time Slider with Animation**: Explore historical data with smooth year-to-year transitions
- **Country Rankings Table**: Sortable and searchable table with year-over-year change indicators
- **Selection Tools**: Select countries on the map or via checkboxes to filter data
- **Dark/Light Mode**: Toggle between visual themes
- **Responsive Design**: Works across different screen sizes

## Data Source

Birth rate data is fetched in real-time from the World Bank API:
- Indicator: Crude Birth Rate (SP.DYN.CBRT.IN)
- Metric: Number of live births per 1,000 people per year
- Coverage: 1960-2023

## Technologies

- Plotly.js for interactive map visualization
- jQuery and DataTables for table functionality
- Vanilla JavaScript for application logic
- CSS with custom properties for theming

## Usage

Visit the live demo link above, or open `index.html` locally in a web browser. The application will automatically fetch data from the World Bank API.

### Controls

- **Year Slider**: Drag to select a specific year
- **Play Button**: Animate through years automatically
- **Map Selection**: Click and drag on the map to select countries
- **Table Checkboxes**: Select individual countries to highlight
- **Selected Only Button**: Filter to show only selected countries
- **Reset Button**: Clear all selections and return to default view

## Formula

The Crude Birth Rate (CBR) is calculated as:

```
CBR = (Number of Births / Total Population) x 1,000
```

## License

This project uses publicly available World Bank data under their Terms of Use.

