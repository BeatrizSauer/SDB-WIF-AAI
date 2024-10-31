# Task 3.3: Satellite time

A satellite transmits time periods to Earth as a "number of seconds".

Write a Java class SatelliteTime, which converts a number of seconds into a time specification in the format `d h m s`
and then outputs the calculated result to the console. The following applies:

- d = number of days,
- h = number of hours in the range from 0 to 23,
- m = number of minutes in the range from 0 to 59,
- s = number of seconds in the range from 0 to 59.

Implementation notes:

- Create a new class SatelliteTime.
- At the beginning of the programme, define a variable which the number of seconds to be converted is assigned to. After
  a single assignment, the value should no longer be able to be changed.
- Use the division and modulo (remainder) operators to calculate the individual values.
- Test your programme using 8000 as the number of seconds. As a result, the following sequence of numbers should be
  output to the console:

```java
Please enter a satellite time in seconds: 8000
0d 2h 13m 20s
```

8000 seconds equals 0 days, 2 hours, 13 minutes and 20 seconds.
