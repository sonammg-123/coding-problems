# 10353. Workers With The Highest Salaries

| Field | Value |
|---|---|
| Platform | StrataScratch |
| Difficulty | Unknown |
| Category | SQL |
| Link | [Workers With The Highest Salaries](https://platform.stratascratch.com/coding/10353-workers-with-the-highest-salaries) |

## Problem Statement

### Workers With The Highest Salaries

Last Updated: October 2026

 Easy

ID 10353

789

A company wants to review compensation only for workers who have an official job title on record, since pay can't be properly benchmarked against a role that isn't documented. Find the job titles of the workers with the highest salary among those who have a matching record in the `title` table. If multiple workers share the highest salary, include all of their job titles.

Output the job title(s), sorted alphabetically.

##### Tables

worker

title

##### This question is part of an interview loop

See the full interview round by round, with questions for each stage.

[Amazon · Data Engineer](https://platform.stratascratch.com/interview-loops/amazon/data-engineer)[Big Tech platforms · Analytics Engineer](https://platform.stratascratch.com/interview-loops/big-tech-platforms/analytics-engineer)[Marketplaces, gig & delivery · Data Engineer](https://platform.stratascratch.com/interview-loops/marketplaces-gig-and-delivery/data-engineer)

---

---

##### worker

worker\_id:bigintfirst\_name:textlast\_name:textsalary:bigintjoining\_date:datedepartment:text

##### title

worker\_ref\_id:bigintworker\_title:textaffected\_from:date

---

##### Recommended Easy Interview Questions

- ID 2002[Submission Types](https://platform.stratascratch.com/coding/2002-submission-types)
- ID 2004[Number of Comments Per User in 30 days before 2020-02-10](https://platform.stratascratch.com/coding/2004-number-of-comments-per-user-in-past-30-days)
- ID 2006[Users Activity Per Month Day](https://platform.stratascratch.com/coding/2006-users-activity-per-month-day)

##### Recommended Questions from the Same Companies

- ID 2172[Customers with Large Orders](https://platform.stratascratch.com/coding/2172-customers-with-large-orders)
- ID 2153[Average On-Time Order Value](https://platform.stratascratch.com/coding/2153-average-on-time-order-value)
- ID 10176[Bikes Last Used](https://platform.stratascratch.com/coding/10176-bikes-last-used)

## Expected Output

| best_paid_title |
| --- |
| Asst. Manager |
| Manager |
