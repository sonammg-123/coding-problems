# 10299. Finding Updated Records

| Field | Value |
|---|---|
| Platform | StrataScratch |
| Difficulty | Unknown |
| Category | SQL |
| Link | [Finding Updated Records](https://platform.stratascratch.com/coding/10299-finding-updated-records) |

## Problem Statement

### Finding Updated Records

Last Updated: October 2026

 Easy

ID 10299

727

We have a table with employees and their salaries; however, some of the records are old and contain outdated salary information. Since there is no timestamp, assume salary is non-decreasing over time. You can consider the current salary for an employee is the largest salary value among their records. If multiple records share the same maximum salary, return any one of them. Output their id, first name, last name, department ID, and current salary. Order your list by employee ID in ascending order.

##### Table

ms\_employee\_salary

---

---

##### ms\_employee\_salary

id:bigintfirst\_name:textlast\_name:textsalary:bigintdepartment\_id:bigint

---

##### Recommended Easy Interview Questions

- ID 2002[Submission Types](https://platform.stratascratch.com/coding/2002-submission-types)
- ID 2004[Number of Comments Per User in 30 days before 2020-02-10](https://platform.stratascratch.com/coding/2004-number-of-comments-per-user-in-past-30-days)
- ID 2006[Users Activity Per Month Day](https://platform.stratascratch.com/coding/2006-users-activity-per-month-day)

##### Recommended Questions from the Same Companies

- ID 2170[Department Workforce Analysis](https://platform.stratascratch.com/coding/2170-department-workforce-analysis)
- ID 10566[Search Click Success Rate by User Segment](https://platform.stratascratch.com/coding/10566-search-click-success-rate-by-user-segment)
- ID 9845[April Admin Employees](https://platform.stratascratch.com/coding/9845-find-the-number-of-employees-working-in-the-admin-department)

## Expected Output

| id | first_name | last_name | department_id | salary |
| --- | --- | --- | --- | --- |
| 1 | Todd | Wilson | 1006 | 110000 |
| 2 | Justin | Simon | 1005 | 130000 |
| 3 | Kelly | Rosario | 1002 | 42689 |
| 4 | Patricia | Powell | 1004 | 170000 |
| 5 | Sherry | Golden | 1002 | 44101 |
| 6 | Natasha | Swanson | 1005 | 90000 |
| 7 | Diane | Gordon | 1002 | 74591 |
| 8 | Mercedes | Rodriguez | 1005 | 61048 |
| 9 | Christy | Mitchell | 1001 | 150000 |
| 10 | Sean | Crawford | 1006 | 190000 |
| 11 | Kevin | Townsend | 1002 | 166861 |
| 12 | Joshua | Johnson | 1004 | 123082 |
| 13 | Julie | Sanchez | 1001 | 210000 |
| 14 | John | Coleman | 1001 | 152434 |
| 15 | Anthony | Valdez | 1001 | 96898 |
| 16 | Briana | Rivas | 1005 | 151668 |
| 17 | Jason | Burnett | 1006 | 42525 |
| 18 | Jeffrey | Harris | 1002 | 20000 |
| 19 | Michael | Ramsey | 1003 | 63159 |
| 20 | Cody | Gonzalez | 1004 | 112809 |

_Showing 20 of 50 rows._
