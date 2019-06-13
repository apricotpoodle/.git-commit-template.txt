# .git-commit-template.txt
This commit message template helps you write great commit messages and enforce it across teams.
# type(<scope>) (If applied, this commit will...) <subject> (Max 50 char)
# |<----  Using a Maximum Of 50 Characters  ---->|

# Explain why this change is being made
# |<----   Try To Limit Each Line to a Maximum Of 72 Characters   ---->|

# Provide links or keys to any relevant tickets, articles or other resources
# Example: Github issue #23

# --- COMMIT END ---
# Type can be 
#    feat     (new feature)
#    fix      (bug fix)
#    refactor (refactoring production code)
#    style    (formatting, missing semi colons, etc; no code change)
#    docs     (changes to documentation)
#    test     (adding or refactoring tests; no production code change)
#    chore    (updating grunt tasks etc; no production code change)
# --------------------
# Example <scope> values: init, runner, watcher, config, web-server, proxy, etc.
# The <scope> can be empty 
# (e.g. if the change is a global or difficult to assign to a single component), 
# in which case the parentheses are omitted. 
# In smaller projects such as Karma plugins, the <scope> is empty.
# --------------------
# Remember to
#    Avoid accents
#    Capitalize the subject line
#    Use the imperative mood in the subject line
#    Do not end the subject line with a period
#    Separate subject from body with a blank line
#    Use the body to explain what and why vs. how
#    Can use multiple lines with "-" for bullet points in body
# --------------------

# For a full example of how to write a good commit message, check out
# https://github.com/sparkbox/how_to/tree/master/style/git
