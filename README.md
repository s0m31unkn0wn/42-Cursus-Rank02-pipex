# 42-Rank02-pipex
Pipex for 125%
Utils for bonus and regular are exactly the same, regular just doesn't use the condition for appending.
found somewhere on github as well, updated to modern requirements; no malloc -> no leaks.

In minishell heredoc is supposed to work simlutaneously with multipipe, here it's one or the other (you can slightly change heredoc to accept multipipe, or no commands at all, but my main strictly checks for 6 arguments when the first is here_doc)
