# Exercise #5

| Deadline                   | Date                   |
| -------------------------- | ---------------------- |
| Review due date (optional) | 16.12.2020 - 14:00     |
| **Final Due date**         | **06.01.2021 - 14:00** |

## Goal

In this example, you're going to learn how versatile GraphQL is when it comes to the persistency layer.

This exercise is a little different that then others: Instead of specifying a desired implementation, we're going to definean abstract objective and you have several options how to implement it.

Extend exercise [#1](../1), [#2](../2), [#3](../3) and [#4](../4) with the new [objectives](#objectives).

## Instructions

1. Choose a GraphQL [scenario](#scenarios) fitting to your needs.
2. Ensure that data is persisted even if the server gets stopped.
3. Ensure that your software tests stay atomic, ie. your tests do not interfere with each other. You can achieve this by either:
  * Cleaning the database before or after your tests
  * or by mocking the response of your database or the remote API.
4. PR Review:
  1. Review a pull request of another team.
    * Find at least 6 things (:star: from [Objectives](#objectives)) the other team did or didn't do.
    * Either "Request Changes" or "Approve" *do not just "Comment"*.
    * Suggest changes line-by-line in "Files Changed".
    * Link to your code review in the description of your own pull request.
  2. Request a review from another team

## Objectives

:star: :star: For database setup.

If you require API keys, put them into `.env` and use [git-crypt](https://github.com/AGWA/git-crypt) to encrypt this file.


:star: :star: For persisted data.

:star: :star: For your tests staying atomic.

:star: For requesting a review and reviewing another team's PR according to the instructions.

## Scenarios

Choose at least one of the scenarios below. Combinations are possible.

### Accessing a Database directly

![Apollo-Server <--> Database](../../.github/img/scenario1.png)

### Schema Delegation to a Remote GraphQL API

![Remote GraphQL API](../../.github/img/scenario2.png)

### Schema Delegation to Neo4J-GraphQL-JS

![Neo4J-GraphQL-JS](../../.github/img/scenario3.png)

