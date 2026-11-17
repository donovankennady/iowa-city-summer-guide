# A/B Test Plan: Iowa City Summer Guide for Students

## Objective

The goal of this experiment is to determine whether changing the homepage headline increases interest in exploring the Iowa City Summer Guide for Students website.

## Unit

One unit is one fresh AI conversation acting as a potential website visitor. Each conversation will be treated as a separate visitor, with no memory of previous trials.

## Assignment

Each unit will be randomly assigned to one of two versions of the website:

- Version A: 50% of units
- Version B: 50% of units

A random number generator will be used to assign visitors to each version. The assigned version will be recorded for every trial.

## Treatment

The only difference between the two versions will be the homepage headline.

- **Version A:** "Make This Summer Count"
- **Version B:** "Your Guide to the Best Iowa City Summer"

All other website content, images, descriptions, and information will remain the same.

## Outcome

Each AI visitor will be asked: "Would you be interested in exploring this website to find activities and information about summer in Iowa City?"

Responses will be recorded as:

- Yes = 1
- No = 0

The primary outcome will be the percentage of AI visitors who answer yes.

## Procedure

1. Start a new AI conversation with no memory of previous trials.
2. Randomly assign the conversation to Version A or Version B.
3. Provide the same website content and prompt, changing only the homepage headline based on the assigned version.
4. Record the AI model, assigned version, full response, and yes/no outcome.
5. Close the conversation and repeat with a new conversation.
6. Complete 100 total trials, with 50 assigned to each version.

The same AI model, model version, and settings will be used for every trial.

## Analysis

After completing the trials, I will calculate the number of yes responses and the yes rate for each version. I will compare the difference between the two versions, calculate the standard error, z-score, and p-value, and use the results to determine whether the headline change made a statistically significant difference.

I will use a significance level of 0.05 to evaluate the results. A higher yes rate for Version B with a p-value below 0.05 would support the hypothesis that the new headline increases interest in exploring the website.

## Limitations

AI-generated responses may not accurately represent the behavior or opinions of actual website visitors. The results will provide an indication of how the two headlines perform in this experiment but cannot guarantee how real students or visitors would respond.
