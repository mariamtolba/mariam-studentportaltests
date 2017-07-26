# mariam-studentportaltests
gherkin scripts for Student Portal
_____________________
**should log in with offline availability off**
```cucumber
Feature: Log Functionality

Scenario: log in attempt
Given I am logged out and at the student portal login page
When I enter my correct login credentials (username and password)
And I click the login button
Then I should be directed to a page with the games displayed
```
_____________________
**should log in with offline availability on**
```cucumber
Feature: Log Functionality

Scenario: log in attempt
Given I am logged out and at the student portal login page
When I enter my correct login credentials (username and password)
And I click the login button
Then I should be directed to a page titled 'installing' with each game being installed
```
_____________________
**should log in with offline availability on**
```cucumber
Feature: Log Functionality

Scenario: log in attempt
Given I am logged out and at the student portal login page
When I enter my correct login credentials (username and password)
And I click the login button
Then I should be directed to a page titled 'installing' with each game being installed
```
_____________________
**should log out automatically**
```cucumber
Feature: Log Functionality

Scenario: log out attempt
Given I am logged in and at the game selection page
When I my computer is idle for____seconds
Then I should be automatically logged out
```
