# Description

This bash script creates a branch named after to the summary of a JIRA ticket.

# How to install

1. Clone this repository
2. Add the `git-jira` folder to your `$PATH`
3. Change permissions `chmod +x /path/to/my/repo/git-jira`
4. Generate an access token here: https://id.atlassian.com/manage/api-tokens
5. Define a variable GIT_JIRA_TOKEN (e.g. `export GIT_JIRA_TOKEN=asd232r29fdsf9ew8`)
6. Define a variable GIT_JIRA_EMAIL (e.g. `export GIT_JIRA_EMAIL=ctpm@tutti.ch`)

# Usage

    git jira ASBE-300

# Example

    ➜  tutti-android git:(translation-fixes-ad-reply) ✗ git jira ASBE-387
    
    ...
    Creating branch: ASBE-387-retry-verification-with-backoff
    ...
    
    ➜  tutti-android git:(ASBE-387-retry-verification-with-backoff)
