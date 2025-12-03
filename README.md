# jamf-domains-block-list
Blocks all urls reletad to Jamf to break communication between the device and their servers.
Also add these three as Regex/Wildcard blacklist manually.

(^|\.)jamf\.com$

(^|\.)jamfcloud\.com$

(\.|^)jamfschool\.com$
