## Installation :point_left:
```
git clone https://github.com/TSC-ID/GMAILBRUTERV2
cd GmailBruterV2
```
## CLI Commands :point_left:
```
help -- To Show Help Message 
set target -- To Set The Victim Email Address
set time -- To Set Time Between Every 10 Faild Passwords
set list -- To Set PassList Name
show target -- To Show You Current Target
show time -- To Show You Current Time
show list -- The Show You Current List
start -- To Start Brute Force Attack
load -- Load Local Config For Settings

exit -- Close The Shell

s-{CMD} -- Executing Shell Command
```

## How To Create a Config? :confused:
- It's Pretty Easy Here. You Just Need To Create a Local File Looks Like This:

```
email:{TARGET}
list:{LIST-PATH}
time:{TIME}
```

- Here's a Simple Example Of The Config

```
email:example@gmail.com
list:PassList.txt
time:10
```
