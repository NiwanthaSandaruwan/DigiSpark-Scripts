# This script does the following:
1. Starts Command prompt as Administrator
2. Runs sequence of powershell commands
    1. Stores password in a variable
    2. Creates new local user account
    3. Gives newly created account administrator priviliages
3. Exits Command prompt

# Additional information:
- Running time is around 15 seconds(depending on hw and length of user name, password, description...)
- Optionally you can add `-FullName` and `-Description` parameters to give account more believable look: 
`New-LocalUser \"accName\" -Password $pass -FullName \"User name\" -Description \"Description of new account\"`

## Use : USB Rubber Ducky
<br></br>
![image1](https://github.com/NiwanthaSandaruwan/DigiSpark-Scripts/assets/142104353/ac47aeb6-be5b-44cf-9c5b-17c8bcdf5b96)

## or ATTINY85
<br></br>
![image](https://github.com/NiwanthaSandaruwan/DigiSpark-Scripts/assets/142104353/11256277-8ea6-4853-8672-785703f4ae77)

