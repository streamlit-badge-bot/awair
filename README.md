# Awair Data to Pandas DataFrame [![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/aglove2189/awair/app.py)

```python
>>> from awair import Awair

>>> awair = Awair(api)
>>> df = awair.get_sensor_df(from_date, to_date)

                               score       temp  ...   voc       pm25
timestamp                                        ...
2019-04-11 21:45:00+00:00  88.647713  76.855246  ...  20.0  82.055262
2019-04-11 22:00:00+00:00  90.699999  76.358799  ...  20.0   7.000000
2019-04-11 22:15:00+00:00  91.000000  76.387400  ...  20.0   3.522222
2019-04-11 22:30:00+00:00  90.922223  76.561683  ...  20.0   3.354789
2019-04-11 22:45:00+00:00  89.966667  76.570000  ...  20.0   5.966667

[5 rows x 6 columns]
```
