# bliphook
A python script that posts your new bleeps onto Discord via a webhook (Warning this kinda sucks lol)
# How to set up
1. Get Python 3.x
2. Run the script. Make sure to pass -u and -w arguments. (to run the script you can do `python3 main.py -u [USERNAME] -w [WEBHOOK_URL]`)
  - You can also do 'python3 main.py -h' to get help.
# To-do
1. Make the script better to read :(
# Known issues
1. The issue if where you bleep 2 times during it's cooldown, and you post after it had cool down, that the post before you post after the cool down will also get sent with it (I can't fix this. This has been bugging me since it's creation and I've been desperately trying to fix it. I'm going insane. Please someone just make a pull request that fixes this issue so I don't have to be tormented by this dumb programming language anymore.)
