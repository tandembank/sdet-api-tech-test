# Developer in Test Coding exercise

Develop a test solution that automates some API tests composed as BDD scenarios.

The application under test is the GitHub Issues API v3: https://developer.github.com/v3/issues/

The scenarios to be covered are:

**Scenario 1: Create an Issue**

**Scenario 2: Edit an Issue title**

**Scenario 3: List issues for a repo, sorted by Update date**

Notes:
- Use of the GitHub API requires authentication:
- To simplify creation of an OAuth token, use the GitHub web UI (Developer Settings) to create a personal access token.
- Do not check in any secrets into the repo to be shared.
- Provide instructions for how to add a token locally so that your solution can be checked using another GitHub account.
- Make the name of the repo in which issues are to be created configurable, so that tests can be easily run against different repositories.

## Candidate Requirements

- Build a test project that includes automation of the 3 scenarios above.
-- Solution to be coded in any language of choice
-- Tests to be driven with a BDD framework of choice
- Share code in a public GitHub repository for review.
- Share further improvements that could be considered, where relevant.
