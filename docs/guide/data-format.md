# Data Overview

OwlAPI serves data directly from MyPortal. It does not try to filter or add anything new to the format to maintain purity to the original. For now, only the most recent quarter's data is pulled from MyPortal. On [opencourse.dev](https://opencourse.dev), seat data is synced every 5 minutes with MyPortal.

::: tip
This following, including data formats, is subject to change with the latest ongoing development.
:::

### JSON data
```
CRN        | Course Number
course     | Course ID (format: [F0*][ID][Section ID][WYH]) see note
desc       | Short-form course description
campus     | Campus the section is held at
days       | Day(s) the section is held on (M, T, W, Th, F, S, U)
instructor | Professor for the section
room       | Room the section is held at
time       | Time for the section
start      | First date for the section
end        | Last date for the course
units      | Number of course units
seats      | Seats left in the course
status     | Status of the course (Online / Waitlist)
wait_cap   | Waitlist capacity
wait_seats | Waitlist slots left in the course
```
#### Course variant format
```
Online     | W (Foothill) / Z (De Anza)
Hybrid     | Y
Honors     | H
```
