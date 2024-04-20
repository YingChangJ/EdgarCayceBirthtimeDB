This database contains all readings by Edgar Cayce, integrated with birth and astrological information.

- id: A unique identifier for each reading, calculated by multiplying the reading number by 1000 and adding the reading index (e.g., the reading "500-2" becomes 500002).
- year, month, day, hour, minute, second
- zone: I treat all the time as mean local time and derive the zone from longitude, since most birthtimes are at the end of 19 centries when standard time might not be widely used.
- timestamp: The timestamp of birth, in milliseconds.
- rodden: A is birth time included, B is only birth day included, C is birth day uncertain.
- name: reading number, used for easy searching.
- ascendant to pluto: astrological degrees, in tropical ecliptic.
- zi1 to zi8: bazi (八字), Chinese most popular astrology, with starting number 0 is 甲 or 寅


Timestamp, longitude, and latitude provides the essential data needed to generate an astrological chart.

### Additional Resources:
Further details about the readings can be found in the [Edgar Cayce Readings, Archive Book](https://archive.org/embed/edgarcaycereadin0019cayc)
