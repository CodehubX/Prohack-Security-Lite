<h1 align="center">
	<br>
	<img src="https://raw.githubusercontent.com/ProHackTech/Prohack-Security-Lite/master/logo.png" alt="ProHack-Security-Lite Logo">
	<br>
	Prohack Security Lite
</h1>

<h3 align="center">Under Development</h3>

This is a small anti-malware application made in VB.NET. All the hashes are collected from <a href="https://virusshare.com/">Virus Share Website</a>. Currently under development.

## Features

### Planned (high level general features)
- Basic signature based scanning
- Simple web protection: using host file modifying. Blocking IP's
- Task blocker and active task blocker: add tasks to block list and allow force blocking
- Create Quick, Deep & Custom scan options
- Plan WebUtils, Tools
- Create logging
- Add python scripts support
- Add CLI version for non-gui scanning (python)
- Create scalable settings menu, replace current
- Create small GUI python package manager (package list from pypi)

Or abandon the project

### Completed Features
The following features have been completed. They may need further improvements.

#### Quick Scan
- [+] Gather files based on 100+ common file extensions
- [+] Queriy *Windows Search Indexer* for file list
- [+] Gather MD5 file signature for each file in query results
- [+] Compare with malware signatures

#### Deep Scan
- [+] Gather system file list using Python
- [+] Scan against malware signatures

#### Scheduled Indexer Query
- [+] Automatic background *Windows Search Indexer* querying every minute
- [+] Added error management incase a scan is currently taking place

#### Error Reporting & Message
Default messagebox was lacking needed features, so a quick custom form was made for displaying message and errors.

- [+] Generate small report for emailing: To minimize data collection scope, automatic reporting may not planned..
- [+] Refresh application: Starts the updater to download the application again (to be used incase critical application error or files missing/deleted by mistake).

### To-Do
- Custom Scan
- Webutils, Tools
- Malware Signatures updater
- Replace 'Easy Install' with better app installer
- Create powershell support scripts (later)
- Create gui python package installer

### FIFO Order
Items in this section are to be made/fixed before doing anything else, hence *<b>F</b>irst<b>I</b>n<b>F</b>irst<b>O</b>ut* order of development:

- Custom Scan (time: 2 days)
- Add force delete malware file (time: 1 day)

Once the current to-do items are completed, the project will begin release cycles with version controls starting from v1.0.0.0 for both application and updater. Different branches will be created for each sub-project development.

## License
**DWTFFYWTDWIADBMFATHWI GENERAL PUBLIC LICENSE**
<Br>
**Version 1, April 2018**
<Br>

'Do Whatever The Frecking Fuck You Want To Do With It And Don't Blame Me For Anything That Happens With It' License allows the users to do exactly what the name expands to.


You can take any part of the code to do whatever you want with it. I didn't create any programming language. I didn't learn programming from air. Most of the code I write is the result of other people dumping their work online for free.


Take it... And go... And don't blame me if anything happens using any logic under this license. Any unlawful activity is the commiters crime. You can choose to not agree with it.

## Contribution
Contributions will be allowed once the planned features are completed.
