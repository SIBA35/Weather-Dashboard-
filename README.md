# 🌦️ Weather Dashboard – Power BI Project

An interactive Power BI dashboard that visualizes weather data using cards, a line chart, a donut chart, and a 100% stacked bar chart, with slicers for filtering by location/date.

## 📁 Project Contents

| File | Description |
|------|--------------|
| `weather.pbix` | Main Power BI report file containing data model, Power Query (M) transformations, and report visuals |

## 📊 Dashboard Features

- **KPI Cards** – quick-glance metrics (e.g., temperature, humidity, wind speed)
- **Line Chart** – trend of weather metrics over time
- **Donut Chart** – categorical breakdown (e.g., weather conditions)
- **100% Stacked Bar Chart** – proportional comparison across categories
- **Slicers** – interactive filters to drill into specific locations or time periods

## 🛠️ Requirements

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (latest version recommended)
- An active internet connection (if the data source is a live weather API/web feed)
- Appropriate access/API key for the underlying data source, if applicable

## 🚀 How to Use

1. **Download** `weather.pbix` from this repository.
2. **Open** it in Power BI Desktop.
3. Refresh the data so the report reflects current, up-to-date weather information (see the important note below).
4. Explore the dashboard using the slicers and visuals.

## ⚠️ Important: Refresh the Data Before Use

> **This dashboard does not auto-refresh when opened.** To ensure you're viewing the latest weather data (and not a stale snapshot saved with the file), you must refresh it manually, **twice, in this order**:
>
> 1. Open **Power Query Editor** (`Home → Transform Data`) and click **Refresh Preview** (or **Refresh All**) to update the underlying queries.
> 2. Close and apply the Power Query Editor, then go back to the **main report/dashboard view** and click **Refresh** (`Home → Refresh`) again to push the updated data into the visuals.
>
> Skipping either step may leave you looking at outdated data cached from when the file was last saved.

## 📌 Notes

- Update the data source connection details (API endpoint/credentials) in Power Query if you're pointing this report to your own weather data feed.
- Feel free to fork and customize the visuals or add new pages for additional insights.
- It is made just to show how we can create a weather forecast dashboard for multiple days and cities.
- I have just showed for next two days for 9-10 cities, you can get more data for more cities by using any weather api key.
- I used api key from this [website](https://www.weatherapi.com/).

## 📄 License

Add your preferred license here (e.g., MIT).
