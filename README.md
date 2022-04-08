# Tendable Coding Assessment

## Usage

```sh
yarn
yarn dev
```

## Goal

Complete the provided React program to ask a series of Yes/No questions. After each run, a rating is calculated to let them know how they did. A second rating is also calculated to provide an overall score for all runs.

## Requirements

The user should be able to select "Yes" or "No" to each question.

The answers will need to be **persisted** so they can be used in calculations for subsequent runs. You may wish to use any persistent storage you seem fit

After _each_ run the program should calculate and print a rating. The calculation for the rating is: `100 * number of yes answers / number of questions`.

The program should also print an average rating for all runs.

The questions can be found in src/questions.ts

Ensure we can run your exercise

## Bonus Points

Updated readme with an explanation of your approach

Unit Tests

Code Comments

Dockerfile / Bash script if needed for us to run the exercise
