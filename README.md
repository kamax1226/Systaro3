# Task 3

## Introduction

Build a small web-app that contains an input field, where the user may only enter a valid email-address ( https://en.wikipedia.org/wiki/Email_address#Validation_and_verification ). Once it is valid, display a green check-mark from ionicons next to the input field ( http://ionicons.com/ ) and display 4 rows of output below the input. This output changes dynamically when the user makes changes in the input field.
Here are the rules for the output:
#1 the entire email address is displayed
#2 only the first part (before the @) of the email address is displayed
#3 the second part of the email address is displayed
#4 a mailto link is dynamically created and displayed, with a custom subject line saying “That was an easy Task, Systaro!"

## Setup Environment

### Node
- Ideal node version is 14.16.0
- Ideal yarn version is 1.22.5

### Ruby and ROR
- Ideal ruby version is 3.0.2
- Ideal rails version is 6.1.3.2

### Database
- Install mysql or postgresql on your computer

## Running commands

```
bundle install
rails db:create
rails server
```
