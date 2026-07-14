### Write a short summary/report describing 3 key insights discovered from the analysis above.

### **Task 2 – Missing Values**

A detailed investigation of the missing values in `results.csv` revealed two main causes. First, many missing values are associated with **DNF (Did Not Finish)** records, where race completion statistics are unavailable. Second, before the 2000s, race timing systems were less developed, resulting in almost all values for `milliseconds`, `fastestLapTime`, and `fastestLapSpeed` being unrecorded and therefore stored as missing values. Consequently, analyses involving these variables should consider separating data from the pre-2000 and post-2000 periods to avoid biased interpretations.

---

### **Task 7 – Number of Races by Season**

The number of races per season generally increased from 1995 to 2019, reflecting the expansion of the Formula 1 calendar. However, the 2020 season shows an exceptional decline, with the number of races falling to a level similar to that of 2007 and 2009. This decrease was most likely caused by the global COVID-19 pandemic, which led to race cancellations and schedule changes.

---

### **Task 9 – Starting Grid Position**

Starting grid position is positively associated with final race position, indicating that drivers who start closer to the front are more likely to finish in higher positions. However, because the starting grid is determined by qualifying performance rather than assigned randomly, this relationship should be interpreted as an association rather than evidence of a causal effect. Driver skill, car performance, and team competitiveness are likely to influence both qualifying and race results.