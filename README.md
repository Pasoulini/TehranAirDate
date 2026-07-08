# TehranAirDate

A beautiful Rainmeter widget showing real-time **Air Quality Index (AQI)** for Tehran alongside the **Jalali (Persian/Solar Hijri) calendar date**.

![Rainmeter](https://img.shields.io/badge/Rainmeter-Skin-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Author](https://img.shields.io/badge/Author-Parsa%20Rasouli-orange)

## Features

- Real-time Tehran AQI with color-coded status
- Jalali (Persian) date display
- Click-to-refresh functionality
- Hover effects with smooth transitions
- Auto-refresh every hour
- Clean, modern dark UI with blur effect
- Tooltips with health recommendations

## AQI Status Colors

| AQI Range | Status | Color |
|-----------|--------|-------|
| 0 - 50 | Good | Green |
| 51 - 100 | Moderate | Yellow |
| 101 - 150 | Unhealthy (Sensitive) | Orange |
| 151 - 200 | Unhealthy | Red |
| 201+ | Very Unhealthy | Purple |

## Screenshot

```
┌─────────────────────────────┐
│  AIR QUALITY    Moderate    │
│  83              ●          │
│  AQI (US EPA Standard)      │
│─────────────────────────────│
│  1405/04/18                 │
└─────────────────────────────┘
```

## Installation

1. Download or clone this repository
2. Copy the `TehranAirDate` folder to your Rainmeter skins directory:
   ```
   %USERPROFILE%\Documents\Rainmeter\Skins\
   ```
3. Right-click the Rainmeter tray icon → **Refresh all**
4. Right-click Rainmeter tray → **Skins** → **TehranAirDate** → **TehranAirDate.ini`

## Data Source

- **Air Quality**: [time.now](https://time.now/tehran/aqi/)
- **Date Conversion**: Built-in Lua script (Gregorian → Jalali)

## Requirements

- [Rainmeter](https://www.rainmeter.net/) 4.0+
- Windows 10/11
- Internet connection

## Configuration

Edit `TehranAirDate.ini` to customize:

| Variable | Description | Default |
|----------|-------------|---------|
| `FontMain` | Main font family | Segoe UI |
| `FontBold` | Bold font family | Segoe UI Semibold |
| `UpdateRate` | Data refresh interval (seconds) | 3600 |

## License

MIT License - feel free to use and modify.

## Author

Made by **Parsa Rasouli** with [Rainmeter](https://www.rainmeter.net/) and caffeine.
