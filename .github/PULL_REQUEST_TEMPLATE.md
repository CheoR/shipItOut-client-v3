# Description

Please include a summary of the change and which issue is fixed. Please also include relevant motivation and context. List any dependencies that are required for this change.

Fixes # (issue)

## Type of change

Please delete options that are not relevant.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

# Testing Instructions

Please describe the tests required to verify your changes. Provide instructions so PR Tester can check functionality. Please also list any relevant details for your tests

On frontend repo

`git fetch --all`
`git checkout <branch-name>`
`python3 mange.py runserver`

On backend repo

`git fetch --all`
`git checkout <branch-name>`
`npm start`

In another tab, cd into `api` and run

`json-server -p 8088 -w database.json`

# Checklist:

- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] My changes generate no new warnings or errors
- [ ] I have added test instructions that prove my fix is effective or that my feature works
