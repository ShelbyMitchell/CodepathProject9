# Project 9 - Pentesting Live Targets

Time spent: **3** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Database Query Fail when changing the URL within the Salesperson tab. Watch [Here](https://github.com/ShelbyMitchell/CodepathProject9/blob/master/Exploit%231BlueSQL.gif)

Vulnerability #2: N/A


## Green

Vulnerability #1: Username Enumeration when trying to log in. If a username does not exist in the system, the green website will not bold it. Watch [Here](https://github.com/ShelbyMitchell/CodepathProject9/blob/master/Exploit%231GreenUserEnumeration.gif)

Vulnerability #2: N/A


## Red

Vulnerability #1: XSS Attack when creating a new country for the staff users, Watch [Here](https://github.com/ShelbyMitchell/CodepathProject9/blob/master/Exploit%231RedXSS.gif)

Vulnerability #2: IDOR when putting in different Number IDs to try to find different Salespeople. A salesperson who is supposed to be private can now be viewed publicly. Watch [Here](https://github.com/ShelbyMitchell/CodepathProject9/blob/master/Exploit%232RedIDOR.gif)


## Notes


