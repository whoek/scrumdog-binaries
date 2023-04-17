# Scrumdog binaries for Windows, Linux and Mac-Intel

## To Install

Scrumdog is distributed as a single executable file. No installation is required. Just copy the file somewhere suitable on your machine and run it. 

Executable file is available for [Windows](https://github.com/whoek/scrumdog-binaries/raw/main/Windows64bit/scrumdog.exe), 
[macOS](https://github.com/whoek/scrumdog-binaries/raw/main/OSX-Intel/scrumdog) or
[Linux](https://github.com/whoek/scrumdog-binaries/raw/main/Linux-Intel-64bit/scrumdog).

Another option is to build the execution file from [source](https://github.com/whoek/scrumdog).

## Support 

For more details see:

- Scrumdog website - https://scrumdog.app/  
- Blog post on [Why and How Scrumdog was created](https://whoek.com/b/jira-to-sqlite-with-scrumdog)

If you have any issues, comments or questions - either raise a [Github Issue](https://github.com/whoek/scrumdog-binaries/issues/new) or email me at willem@matimba.com

## Changelog
```
Release 0.51 - April 2, 2023
- Add 'csv' folder
- Output Excel friendy csv files for every table

Release 0.50 - March 19, 2023
- Remove dependancy on curl
- Move from curl to ocaml-tls
- Clean-up http response error reporting
- Add authentication for get-fields call
- Fix field parsing issue for Linux version

Release 0.4 - July 20, 2022
- Add database tables for Jira labels and components

Release 0.3 - July 19, 2022
- Add more error messages for curl
- Add database table for Jira comments

Release 0.2 - June 26, 2022
- Add command line options
- First public release on www.scrumdog.app

Release 0.1 - June 16, 2022
- Change tablename from zz to zz_issues


