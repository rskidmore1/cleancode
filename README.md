# cleancode
A check list for making a pull request.


--------------------
### Frontend and backend 
- Did I accomplish the objective of the ticket?
- Tag and stages
  - Link issue to PR on right bar
  - Link PR to issue on right bar 
  - Set issue to In Review (if not a draft)
  - Assign PR to myself
  - Assign reviewer
- Review code in commits
   - run `composer run lint` for symfony repos 
   - Are variables names descriptive?
   - Are there any debug statements?
   - Anything that needs an `if` and exception or error log?
   - Are there any extra loops?
   - Is there any extra pushing to an array?
- Creating testing instructions
- Rebase commits 
  - TODO look up how to do this
- Put Documentation on ticket or wiki
  - Explain what the feature does
  - Explain what the code is doing 
- Check for linting or console errors
- Is code formatted properly?
- Assess order of CSS elements according to company standarda
- Run accessibility and light house score 

--------------------
### Answer comments
- Answer all comments
  - Put Clarification
  - Mark "Resolved"
- Tag review with @ in comment (They will get an email that they have been mentioned.)
