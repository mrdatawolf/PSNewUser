# PSNewUser
 add a new user to a domain
Calls an advanced function to streamline New-ADUser creation by individual user or multiple users.

#Important Note:
## This is not mine.  It comes from https://www.reddit.com/r/PowerShell/comments/1hghpg7/i_recently_updated_my_user_creation_script_after/
## This CMDlet is designed to prompt for each required parameter field dictated by the Domain Admin. It is also designed to take input by csv. 
## It also adds the parameter 'Groups' and 'SourceUser' which will allow you to copy the memberships from a Source User, or add a specific Group(s). The password for the account is supplied by a random password generator and is shown in the console and copied to the clipboard.

<!-- Purpose: Calls an advanced function to streamline New-ADUser creation by individual user or multiple users. -->
<!-- INSTALL_COMMAND: curl -o PSAddNewUser.ps1 https://github.com/mrdatawolf/PSNewUser/raw/main/PSAddNewUser.ps1 -->
<!-- RUN_COMMAND: PSAddNewUser.ps1 -->