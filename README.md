This database contains all birthday-included readings by Edgar Cayce, for quick searching and charting.
Also, all reincarnation with past life as famous person. 

About a quarter of people from previous lives have birth dates very close to those in their current lives, differing by no more than 3 days. This could suggest that they share the same souls or have similar lessons to learn.

### Table: Person (1555 in total, readings with birthdate)
- id: A unique identifier for each person in Readings.
- year, month, day, hour, minute, second
- zone: I treat all the time as mean local time and derive the zone from longitude, since most birthtimes are at the end of 19 centries when standard time might not be widely used.
- timestamp: The timestamp of birth, in milliseconds.
- rodden: A is birth time included, B is only birth day included, C is birth day uncertain.
- name: A unique identifier for reading (one person could have several reading).
- ascendant to pluto: astrological degrees, in tropical ecliptic.
- zi1 to zi8: bazi (八字), Chinese most popular astrology, with starting number 0 is 甲 or 寅


Timestamp, longitude, and latitude provides the essential data needed to generate an astrological chart.

#### Additional Resources:
Further details about the readings can be found in the [Edgar Cayce Readings, Archive Book](https://archive.org/embed/edgarcaycereadin0019cayc)


### Table: Reincarnation (104 in total, readings with past lives of famous persons)
(similar structure as Table Person)

- name: name of past life.
- year, month, day, hour, minute, second: birth data of past life.
- id: A unique identifier for each person in Readings, or birthday or name if id not available.
- second: if second is 1, I convert the calendar to Gregorian Calendar, otherwise, the calendar follows local rule)
- category: similar means the birth date in the two lives varies less than 3 days; similar 10 means around 10 degrees apart of Sun.

#### Addition:
* In some cases, there are multiple individuals within a family who share the same name and have similar occupations (such as in political families), making it difficult to determine which individual is being referenced.
* Some birth dates lack credibility, such as the birth date of Joan of Arc.


