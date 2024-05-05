# Presenting the Diamonds Model

This assignment picks up where the diamond regression assignment left off. The details are in `diamond-report.rmd`. 

## Getting Started

- Clone this repository to get started with the assignment.
- The main file you will be working on is `diamond-report.rmd`. Follow along in that file for instructions.

## Resources

- `diamond-report.rmd`: Contains the assignment instructions and is a place for you to build out your presentation of the findings.
- `diamond-data.txt`: The dataset file with diamond attributes and prices.

## Submission

After completing the analysis, commit your modified `diamond-report.rmd` file to this repository, along
with the knitted HTML file. Ensure this 
final document is well-commented and clearly presents your findings. After you've knitted your report, please carefully
read the HTML. Assume that this report is going to go to your boss's boss's boss or something. Try to write clearly
and minimize weird formatting issues. It's okay to leave your code in, since some of your audience will be data scientists. 

## Feedback

One technical note: `library(arm)` has some name collisions with `dplyr`, so I typically use `arm::display` so that `select` keeps working as expected. 

In 3, a couple of examples would clarify your exposition, which is otherwise quite good. 

In 4, it'd be nice to add some visual cues (hue, shape, etc.) so that it's easier to see what's going on. 

Overall you've done a nice job. There are some aspects of the above which I feel like are on the cusp of needing a revision, but you did such a thorough job on 7 we can call this done. 
