# Epics

---

# Why?
To make it simple to track who / the frequency of deploys to production

# User Story
> As a user, when I want to track deploys to production, I get a notification and can check a specific channel to see information about the deployment

## Acceptance Criteria
- information should include but is not limited to:
  - the name of the application
  - who merged it
  - the time it was merged

# Technical Components
Serverless Framework created lambda
Slack integration url ( for POSTing updates to )

---

# Enhancements 

--- 

> As a user, when wishing to track test client app deployments, I should be able to receive a notification and be able to visit the channel #test-deploys. There I should be able to see a list of all of the previous deploys that have occurred through the channel history.

## Requirements for Completion
- [ ] should be tested
- [ ] should only send messages when the base app (not review) has deployed
- [ ] should have the name, time, git_commit, and url of the application that has deployed, as well as who deployed it
- [ ] each Lambda should have all required environment variables

---

# Documentation

## Changes
- this was changed
- other things were also added

## Purpose for changes
- Because things should change