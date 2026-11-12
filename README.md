# Horoscope Tracker

A mobile-friendly birth chart and daily, monthly and yearly horoscope tracker.

**Open it:** https://saleembek.github.io/horoscope/

- Enter your birth date, time and place once. They are saved only in your own browser, never uploaded.
- **Day:** Work / Money / Love / Health scores, best hours, next 30 days.
- **Month / Year:** forecasts, best days, major transits, eclipses, retrogrades. Browse past and future years.
- Everything is calculated on your device (Meeus formulas + NASA JPL orbital elements). No server, no tracking.
- **Birth city search:** 171,000+ cities worldwide. Type a name, pick it, and latitude, longitude and the UTC offset for your birth date (daylight saving included) fill in automatically. City files in `cities/` load one letter at a time.

### Credits
- City data © [GeoNames](https://www.geonames.org), licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), via the [cities.json](https://www.npmjs.com/package/cities.json) package. Converted to per-letter files with time zones added.
- Time zones matched to the nearest city from [city-timezones](https://www.npmjs.com/package/city-timezones) (MIT).
