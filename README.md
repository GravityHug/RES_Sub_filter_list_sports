# Importing instructions

1. Export your RES subreddit filter options:

	1.1. Press period on any Reddit page to open the RES command line.

	1.2. Write `RESStorage get RESoptions.filteReddit` in the console pop-up. 

	1.3. Copy the output of your settings and save them in .txt (the file will double as your backup).

2. Amend the blacklist to your setting string:

	2.1. Ctrl+F for `subreddits":{"value":[` in the .txt file

	2.2. Ctrl+C the blacklist from [here](https://raw.githubusercontent.com/GravityHug/RES_Sub_filter_list_sports/master/SportSubBlacklist.txt)

	2.3. Ctrl+V the entire blacklist after `subreddits":{"value":[` in a manner to match the pattern of already blacklisted subreddits.

3. Import the modified settings:

	3.1. Press period on any Reddit page to open the RES command line.

	3.2. Write `RESStorage update RESoptions.filteReddit` in the console pop-up 

	3.3. Ctrl+V the entire updated settings file, press confirm.
