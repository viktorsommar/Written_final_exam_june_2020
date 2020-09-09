## Written submission
Please explain the steps you think are necessary to perform to get a feature done, from an idea to an implemented solution that is running in production. Be as detailed as possible. 

Makee a PR with your submission to this repository.

## Written answer

In order to get a feature done from an idea to an implemented solution there are several steps involved:

* Assuming the idea for the feature has been approved, is relevant to the application and is in the pipeline according to the Product Owner, it will be necessary to define the scope of the feature and that everyone that will work on it understand what needs to be done. A user story will be created to catch this.

* The feature will then be included in a design sprint, where the team will add what tasks need to be done and vote on the perceived difficulty of the task, guided by the scrum master.

* One the feature is picked up for the sprint backlog, if working in a TDD way, tests will be written and guiding the team to what to do to make it work.

* Implementation code is added while testing, and once all tests pass, a pull request is made to the appropriate branch on the main repo.

* In order to make sure everything passes even in developement and production, we can make use of Continuous Integration and Continous Development. That way the PR will be tested on submit and nothing will be pushed into production if it is not passing the tests and developement.

* The team will want to test front end and back end together if the feature involves both of these. Testing might pass but manual testing in the actual development environment might fail. 

* Lastly, testing is required event in production to make sure everything works as intended. Of course, bugs might still occur and if that is the case, a bug report / bug fix story will pop up in the next sprint.

