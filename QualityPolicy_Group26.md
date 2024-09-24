# Quality Policy

Here are the quality policies that the team needs to be mindful about:
1. Code Clarity and Readability: Code should be easy to read and understand. This includes using meaningful variable and method names, and oranizing code logically.
2. Commenting and Documentation: Proper commenting within the code to explain the purpose and functionality of code segments. Additionally, external documentation may be required to explain the overall design of the program.
3. Adherence to coding standards: Following a specific coding style guide or standard.
4. Testing and Validation: Thorough testing of code to prevent and fix bugs early on.
5. Software Design Principles: Applying solid software design principles and patterns to ensure code is maintainable, scalable, and efficient.
6. Error Handling and Robustness: Writing code that gracefully handles unexpected situations and errors.
7. Collaboration and Teamwork: Working effectively in teams, which includes code reviews, pair programming, and effective communication.
8. Ethical and Professional Considerations: Writing code ethically and professionally, considering aspects like user privacy, data security, and accessibility.
9. Requirement reviews: Reviewing the necassary requirements before making a final submission for any piece of code or software contribution.


## Git Workflow
Our team has decided to fork the repositories that we work on from the main orgainization page on Github. This will reduce our chances of disturbing existing code before we fully understand it. 
-   The master branch, `main`, will not be pushed to until the end of each sprint.
    -   A pull request for merge into main shall require **2** reviews.
-   A development branch,`dev`, will be branched from master.
    -   The development branch will be used to merge user stories for each sprint.
    -   A pull request for merge into development shall require **1** review.
-   Each user story will be separated by branch.
    -   Branch name format: `US#-description`
    -   User stories will not be merged into Development until all that user story's tasks are complete.
-   Developers will pull the corresponding US branch to their local repo and branch for each task.
    -   Branch name format: `US#-TS#-description`
    -   Task branches will only be merged into their parent user story branch once they are complete.
-   Each commit will be prepended with `US#-TS#`, along with a short description of the purpose of the commit

## Unit tests
Unit tests are an integral part of our project as the current code base does not have any and they are highly requested by Ian Skelskey, ASU alum and current code maintainer for the Field Day project. We will include both blackbox and whitebox testing in the code.

# Unit Tests Blackbox
Each member of the team will take part in the testing process to make the testing more reliable and thorough. Blackbox testing takes place without looking at the code so in context to our project, they would assess:
- The functionality of each additional feature added to the Field day application.
- The improvement of existing charactersticks.
- The security measures that would be put in place.

Edge cases and boundary values will also be heavily tested to ensure maximum code correctness and adherence to the requirements.

The testing policies would include: 
- Testing code that already exists.
- Testing code developed by peers in the team.
- Writing a handful of test cases for each section of code. 

  
 # Unit Tests Whitebox
- Each user story should be tested before merging into dev.
- Special focus on areas that result in errors after Blackbox testing.
- At Least an 80% of code coverage or more should be reached after testing.
- Each team member will contribute in testing.

## Code Review
- No Direct Commits: No code should be directly committed to the Master or Dev branches without undergoing a detailed Code Review.
- Minimum Reviews: Each Pull Request (PR) must receive at least one code review.
- Documentation: All reviews and relevant comments must be documented in the PR review section.

Before submitting a PR to the Dev branch, developers must complete the following checklist and include it in the PR comment:

1. Code Functionality: Verify that the code accomplishes its intended functionality.
2. Code Quality: Ensure code follows best practices in readability, structure, and naming conventions.
3. Edge Cases: Ensure Edge cases and exceptional scenarios are handled.
4. Testing: Confirm that the code has been thoroughly tested (unit tests).
5. Documentation: Ensure all new code is adequately documented, including comments in code.
6. Dependency Check: Verify that new code does not introduce dependency issues.
7. Compatibility: Ensure code compatibility with existing codebase.
8. Conflict Check: Ensure that the PR does not introduce merge conflicts.

Reviewers must use the following checklist during the Code Review process and include comments as part of the PR review:

1. Code Understanding: Ensure the code's purpose and implementation are clearly understood.
2. Code Quality Assessment: Evaluate code for readability, maintainability, and adherence to best practices.
3. Testing Validation: Confirm that appropriate tests have been provided and are passing.
4. Documentation Adequacy: Check if the new code is well-documented.
5. Compatibility Check: Verify code compatibility with the current codebase.
6. Edge Case Handling: Check whether the code correctly handles all edge cases.
7. Feedback and Suggestions: Provide constructive feedback and suggestions for improvement.
8. Approvals: Confirm that all necessary approvals from other team members are obtained.
9. Final Validation: Ensure that the entire checklist has been addressed and the PR is ready for merge.
    
## Scrum
The team will utilize the scrum framework during each sprint that takes place. Sprints will typically start 10 days to two weeks before each project deliverable. The team members will be responsible for creatiing user stories, tasks and overseeing the progression of the burndown charts.
The board for Group 26's Field day project can be found [here](https://tree.taiga.io/project/qknowles-project-plan/timeline/).

## Stand Up 
Each member of the team has to post in the stand-up channel on slack multiple times a week. The following questions have to be taken into consideration
- What was done yesterday?
- What was done today/ what do you plan to do today?
- What obstacles have you faced so far?

These stand up reports will help the team maintain progress as a unit while also allowing each member to present their shares and contributions. Additionally, any obstacles encountered will be overcome in a speedy manner if multiple members try to come up with a solution as opposed to just one member.

## Communication and Resource sharing
The team has two main channels realted to the project: the communication channel and the stand up meeting channel. Both of these are on Slack. The live meetings between teammates and with the sponsor are held on Zoom. 

Google Drive wil be used to store and maintain the team's shared resources. A few of these resources are records for meeting minutes, the project plan, member avilabilty, and ASU deliverables. They are present in the following structure:

-   Group26_ASUCapstone (main directory)
-   ASU Deliverables. This folder comes under the main directory and includes the artifact review, meeting minutes, plan review, and project plan.
-   Sponsor Communication. This includes emails that have been sent to the sponsor and potential questions to present in future meetings.
-   Team coordination. This includes an availabilty chart for the team mebers as well as roles and responisibilities distributed for each sprint.
-   Issues. This file contains issues or confusions that the team has regarding the project and that need to be cleared.


## Acknowledgement

By checking the box below that corresponds with my name, I am agreeing to adhere to all policies, standards,
and practices specified in this document.

-   [ ] Evan Hagood
-   [ ] Chase Molstad
-   [ ] Quinten Knowles
-   [ ] Ayesha Arif
-   [ ] Timothy Weaver
