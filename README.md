# Description

This bash script creates a branch named after to the summary of a JIRA ticket.

# How to install

1. Move the `git-jira` file somewhere in your `$PATH` for example:
   `/usr/local/bin/git-jira`
2. Change permissions `chmod +x /usr/local/bin/git-jira`
3. Generate an access token here: https://id.atlassian.com/manage/api-tokens
4. Replace the `token` variable in the `git-jira` file
5. Replace the `email` variable with your email

# Usage

    git jira ASBE-300

# Example

    ➜  tutti-android git:(translation-fixes-ad-reply) ✗ git jira ASBE-387
    
    ...
    Creating branch: ASBE-387-retry-verification-with-backoff
    ...
    
    ➜  tutti-android git:(ASBE-387-retry-verification-with-backoff)
