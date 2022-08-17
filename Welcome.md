# CORDEX FPS-SESA analyses

Some analyses on CORDEX FPS-SESA data. Select a notebook from the repository:

| Notebook | Description |
|----------|-------------|
| daily_cycle.ipynb | Daily cycle of precipitation |
| pr_tseries.ipynb | Monthly time series for the whole simulation period |

## Requirements

These data are restricted. If you are an FPS-SESA partner, you can register at http://meteo.unican.es/udg-tap and enrol in the FPS-SESA group.

In order for these notebooks to work, add to this repository folder a `.netrc` file with the following plain text lines:
```
machine data.meteo.unican.es
  login yourloginname
  password yourpassword
```

If you are on MyBinder, you can upload it using the up-arrow button on the left (top buttons).
