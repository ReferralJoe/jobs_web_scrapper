
----

# Jobs Web Scrapper

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/svt/open-source-project-template)
[![REUSE status](https://api.reuse.software/badge/github.com/svt/open-source-project-template)](https://api.reuse.software/info/github.com/svt/open-source-project-template)


**Description**:  
Jobs Web Scrapper is an open source web scrapper which gets all the open positions from the career pages of numerous companies. In simple words, it aggregates all open positions in one website, job seekers are able to find their next position easier and faster.

Firstly, this project is created to help referraljoe.com to solve the data scattering issue of open positions. 
Have you ever searched for the job in IT industry? 
Aren`t you tired of opening lots of tabs with the "careers" pages of different companies? 
The project is aiming to ease your life by providing the list of new job offers from a number of diverse reliable sites. With the help of this program you get access to the needed information in a much shorter time, than usual.

Moreover, in the nearest future this project will support any ATS that are used by the tech industry!

Feel free to check our website referraljoe.com to see how Jobs Web Scrapper is used in practice.

**Technology stack**: 
The program is written with the use of Python programming language. It could be used both as an individual program and as a part of the other project. 
The entrypoint to the program gets an input of a company's website URL and the program returns all open positions.
The program identifies the ATS and runs the specific ATS adapter, the output has the same format for any ATS.

**Status**:  1.0.0
The program is ready for use, however, it needs further testing and addition of new ATS adapters.[CHANGELOG](CHANGELOG.md).

## Requirements

The programming language Python should be installed in order to execute the project. Additionally, library bs4 for BeautifulSoup should be installed for all parts of the program to work correctly.

## Known issues

Nothing yet.

## Getting help

If you have questions, concerns, bug reports, etc, please file an issue in this repository's Issue Tracker.

## Installation

Before the start download needed software: [Python](https://www.python.org/downloads/) and [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/bs4/download/).

In order to install the project you have to follow such steps:
1. Open main page of the project (you are already here).
2. Copy the “HTTPS clone URL” link using the clipboard icon at the bottom right of the page’s side-bar.
3. Open Git, and from the home directory, use the command git clone, then paste the link from your clipboard, or copy the command and link from below:
```
git clone https://github.com/ReferralJoe/jobs_web_scrapper.git
```
4. Change directory for the newly created ~/jobs_web_scrapper:
```
cd ~/jobs_web_scrapper/
```
5. Use the pull command to ensure that your main branch is up-to-date:
```
git pull https://github.com/ReferralJoe/jobs_web_scrapper.git main
```
6. Now you are ready to start exploring the project!

## Getting involved

If you want to help the project grow, you may contribute to it, see the details in [CONTRIBUTING](docs/CONTRIBUTING.adoc).

Open task list:
- [ ] Add new adapters for other sites (companies` job offer pages);
- [ ] Test the program by hand;
- [ ] Write additional program for testing;
- [ ] Report any found mistakes;


## Development

General instructions on how to Develop for the project should be stated with a link to [DEVELOPMENT](docs/DEVELOPMENT.md), or could be merged in [CONTRIBUTING](docs/CONTRIBUTING.adoc).

----

## License

This project is licensed under the Creative Commons Zero v1.0 Universal License - see the [LICENSE](LICENSE) file for details

Most assets released under Creative Commons CC0-1.0 except for

SECURITY.md template:  

Copyright: 2020 [IEEE Open Source Maintainers Manual](https://opensource.ieee.org/community/manual/-/wikis/SECURITY.md)
License: Apache-2.0

CODE_OF_CONDUCT.md template:  

Copyright: [Contributor Covenant](https://www.contributor-covenant.org/)  
License: [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)

----

## Primary Maintainers

Primary maintainers:

[Yonatan](https://github.com/yonatanholdings)  

Thanks to:
* [CFPB Open Source Project Template](https://github.com/cfpb/open-source-project-template)
* [Keep A Changelog](https://keepachangelog.com/)
* [Contributor Covenant](https://www.contributor-covenant.org/)
* [IEEE Open Source Maintainers Manual](https://opensource.ieee.org/community/manual/)
* [VelDia](https://github.com/VelDia)

