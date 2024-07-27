# CMPG-323-Overview-35760338
This repository will store all the information about the planned schedule of CMPG 323 module, the projects due dates and the time it took to complete all projects.

## List of repositories that will be created for each project
+ CMPG 323 Overview 35760338: Project 1 - Agile and Scrum Semester plan
+ CMPG 323 Project 2 - 35760338: API Development
+ CMPG 323 Project 3 - 35760338: Patterns and Standards
+ CMPG 323 Project 4 - 35760338: Testing abd RPA
+ CMPG 323 Project 5 - 35760338: Reporting and Monitoring

## Branching Strategy

Our project follows a modified Git Flow branching strategy:

1. `main`: The primary branch containing production-ready code.
2. `develop`: The integration branch for features in progress.
3. `feature/*`: Individual feature branches (e.g. `feature/new-login-page`).
4. `hotfix/*`: For urgent fixes to the production code.
5. `release/*`: Preparation branches for new production releases.

### Workflow:

1. Create feature branches from `develop`.
2. When a feature is complete, merge it into `develop`.
3. When `develop` is stable and ready for release, create a `release` branch.
4. After testing, merge the `release` branch into both `main` and `develop`.
5. If issues are found in `main`, create a `hotfix` branch, then merge it into both `main` and `develop`.

Please ensure all commits are made to feature branches and integrated via pull requests.
