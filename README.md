# Study Buddy

## Description

The Study Buddy is an integrated chatbot within Canvas, designed to streamline the assessment of Key Performance Indicators (KPIs) from the HBO-I framework. It provides quick answers to basic queries and handles more complex inquiries using user-specific data. This enables students to verify if they've submitted enough evidence for a specific KPI. The Study Buddy also assists in work submissions, validating the chosen KPI and suggesting alternatives if needed. When faced with uncertain HBO-I related questions, it transparently defers to the coach for resolution, using their response to improve its capabilities. In essence, the Study Buddy enhances the evaluation process, benefiting both students and coaches.

[comment]: <> (## Installation)
[comment]: <> (## Usage)
[comment]: <> (## Contributing)
[comment]: <> (## License)


## General project conventions

* [Pip-8](https://peps.python.org/pep-0008/) convention.
* Up-to-date documentation.
* Testing: [Pytest](https://docs.pytest.org/en/7.2.x/getting-started.html)

## Git workflow

1. Clone the project in your own IDE.
2. Git checkout to Develop. Already on Develop? Always git pull first to ensure you are up-to-date with the latest
   changes in Develop.
3. Generate a feature-branch from Develop with a linked task from Jira.
4. After pushing the branch, create a merge-request from feature-branch to Develop. When ready, select a reviewer.
5. Merge-request:
    * If approved, merge to Develop.
    * If request changes, make necessary changes or assign to someone else.
6. Merge to master on Tuesday evening or at another agreed upon time.

## Gitmoji

To make commit messages as clear and powerful as possible using as few words as possible, emojis can be used.
Via [Gitmoji](https://gitmoji.dev/), you can categorize different commits into useful categories to see at a glance
which task has been completed.
