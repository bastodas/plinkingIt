## For the windows you might need to enable script excution but im assuming it already is enabled

Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

## Also make sure to run get users command before so that we dont delete any needed users by the system. These usually will have a description telling us if they are actually necessary or not

Get-LocalUser
