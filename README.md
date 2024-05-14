This database contains all birthday-included readings by Edgar Cayce, for quick searching and charting.
Also, all reincarnation with past life as famous person. 


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
- second: if second is 1, the date is converted to Gregorian Calendar from Juian Calendar.
- id: A unique identifier for each person in Readings, or birthday or name if id not available.
- category: similar means the birth date in the two lives, varies in less than 3 days; similar 10 means around 10 degrees apart of Sun, not list means the current lives' birth date is not available.
- birth_name: birth date records original (in Julian Calendar)
- rewrite: birth date of current lives.

#### Addition:
* In some cases, there are multiple individuals within a family who share the same name and have similar occupations (such as in political families), making it difficult to determine which individual is being referenced.
* Some birth dates lack credibility, such as the birth date of Joan of Arc.
* some birth dates are the date of bishop, thus might be few days after real birth time.

### Thoughts
* About a quarter of people from previous lives, have birth dates very close to those in their current lives, differing by no more than 3 days (before convert Julian Calendar to Gregorian calendar).
* Does this caused by numerology reasons? (which means, not the Sun's ecliptic degree, but the number in birth date, really matters)



