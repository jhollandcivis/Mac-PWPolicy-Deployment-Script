# pwpolicy_config_yosemite_10.10
A pwpolicy.plist XML config for OS X Yosemite 10.10 that actually works. Tested on 10.10.4.

- Keeps a history of passwords 5 deep
- Locks the account for 5 minutes after 5 unsuccessful login attempts, then it actually auto unlocks
- Password expirtation in 121 days
- Password complexity: 8 chars min, one upper case, one lower case, one special char (non alpha-numeric)

Usage: 

To apply:  sudo pwpolicy -u <username> -setaccountpolicies pwpolicy.plist
To clear:  sudo pwpolicy -u <username> -clearaccountpolicies

See pwpolicy man page for other details, but it's spare and has some typos. Come on Apple....

See this reposity for a great script to alert users to when they need to change their password (nicely done, Taylor):
https://github.com/viverae/pwpolicy/blob/master/PasswordAgeCheck.sh 
