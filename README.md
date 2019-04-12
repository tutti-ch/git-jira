# Description

This bash script creates a branch named after to the summary of a JIRA ticket.

# How to install

1. Clone this repository
1. Add the `git-jira` folder to your `$PATH`
1. Generate an access token here: https://id.atlassian.com/manage/api-tokens
1. Configure ~/.netrc

```
machine tutti-ch.atlassian.net
login login
password PW
```

# Usage

    git jira ASBE-300

# Example

    ➜  tutti-android git:(translation-fixes-ad-reply) ✗ git jira ASBE-387
    
    ...
    Creating branch: ASBE-387-retry-verification-with-backoff
    ...
    
    ➜  tutti-android git:(ASBE-387-retry-verification-with-backoff)
