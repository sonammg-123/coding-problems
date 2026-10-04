# 10597. Thumbs-Up Rate by Model Version

| Field | Value |
|---|---|
| Platform | StrataScratch |
| Difficulty | Unknown |
| Category | SQL |
| Link | [Thumbs-Up Rate by Model Version](https://platform.stratascratch.com/coding/10597-thumbs-up-rate-by-model-version) |

## Problem Statement

### Thumbs-Up Rate by Model Version

Last Updated: October 2026

 Easy

ID 10597

1

The Applied Product team wants to compare how well users receive each model version. Calculate, for each model version, the percentage of rated responses that received a thumbs-up. Responses that were never rated are not counted, and model versions with no rated responses should not appear.

Feedback can be sent more than once for the same response, so count each response only once.

Output the model version and its thumbs-up percentage.

##### Table

ai\_response\_feedback

---

---

##### ai\_response\_feedback

response\_id:textmodel\_version:textfeedback:text

---

##### Recommended Easy Interview Questions

- ID 2002[Submission Types](https://platform.stratascratch.com/coding/2002-submission-types)
- ID 2004[Number of Comments Per User in 30 days before 2020-02-10](https://platform.stratascratch.com/coding/2004-number-of-comments-per-user-in-past-30-days)
- ID 2006[Users Activity Per Month Day](https://platform.stratascratch.com/coding/2006-users-activity-per-month-day)

##### Recommended Questions from the Same Companies

- ID 10606[New Users Who Never Sent a Message](https://platform.stratascratch.com/coding/10606-new-users-who-never-sent-a-message)
- ID 10605[Average Output Tokens by Model](https://platform.stratascratch.com/coding/10605-average-output-tokens-by-model)
- ID 10599[Users on Both Chat and API](https://platform.stratascratch.com/coding/10599-users-on-both-chat-and-api)

## Expected Output

| model_version | thumbs_up_pct |
| --- | --- |
| gpt-4o | 75 |
| gpt-4o-mini | 40 |
| gpt-4 | 100 |
| o1 | 0 |
