# NeoCode-Windows_Users
exports filtered, srted list of windows accounts for billing purposes

user: admin

pass: NOT SET

# Command

cmd.exe /c wmic UserAccount get Name | sort > c:\users\administrator\desktop\users.csv

# Config

1. directory path and filename
1. lists of users to filter out in the perform find
1. adjust the number of users "included"

# Requires

Windows 10 / Server 2012

FileMaker 14+

BaseElements Plugin
