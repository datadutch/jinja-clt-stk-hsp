# dv-jinja
* building a datawarehouse generator using python jinja templating

# TL;DR
i have some personal goals with this:
* learning how to set up an open source project and collaborate on this with others
* build an easy to use and understandable datawarehouse generator
* learn from contributions made by others
* learn about github ci/cd, actions, codespaces, etc.
* learn more about software development best practices, since i do not really have a background in programming

# comments
* i have some experience with Python Jinja, but for this repository, I will start at page 0 using this tutorial: https://realpython.com/primer-on-jinja-templating/
* the initial version should be working on Snowflake, generating both DDL and TASKS

# local implementation
* created the virtual environment manually, using https://docs.python.org/3/library/venv.html, feel free to do it at your own preference

# to-do
* setup github repo to prevent commits direcly on main branch (done)
** for this, i have defined a Branch Protecting Rule, which requires a pull request before merging and also 1 approval
* tutorial (in progress)
* track the number of CoPilot hacks here:
** write the output file to a separate folder (done)
* setup codespaces (done)
* setup actions/cd-cd
** https://medium.com/snowflake/snowflake-ci-cd-with-github-actions-c2168ceb33bc
** or perhaps use my own script https://bidutch.medium.com/snowflake-ci-cd-75d1c907cd0b (todo)

# licensing
from https://choosealicense.com/ i have chosen the GNU GPL v3 license: lets people do almost anything they want with your project, except distributing closed source versions.
