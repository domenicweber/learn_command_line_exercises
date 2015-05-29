> What is your shell set to?

By typing `env` I see my shell is set to `SHELL=/bin/bash`


> What directory are you in (don't use pwd this time)?

By typing `env` I scroll down a bit and see `PWD=/Users/thoth/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises`


> What is your home directory set to?

By typing `env` I can see that `HOME=/Users/thoth


> Can you set your environment to have DEBUG set to true?

I'm not 100% sure of what this question is asking but I can set "DEBUG" to "True" by this:

`export DEBUG="True"`

so that `echo $DEBUG` returns "True"

and `env | grep DEBUG` returns `DEBUG=True`
