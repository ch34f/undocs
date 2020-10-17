# Undocumented features

## Undocumented Program Options - Programs
Also, some standard programs that have a graphical shell have undocumented options. These programs will be described below.

### Contacts (Wab.exe)
The Wab.exe program has many options, some of which are undocumented and will be discussed below. The other part of its options was considered by us earlier.

Table 3.88. Undocumented options for wab.exe

/ Upgrade. Updates the mail client's address book.
/ SetMe. Displays the Windows Contacts dialog - profile selection
DirectX Diagnostic Tool (dxdiag.exe)
The DirectX Diagnostic Tool also supports several undocumented options, some of which are presented in the table below.

Table 3.89. Undocumented program options
-64bit. Use the version of the program for 64-bit systems.
-saveonly. Runs diagnostics, the results of which are suggested to be saved in a file.
System configuration (msconfig.exe)
This command supports the / auto option, which displays the SYSTEM CONFIGURATION dialog.

### System Information (msinfo32.exe)
The msinfo32.exe utility displays detailed information about the user's system configuration. In addition to displaying a special wizard describing this information, you can use the program's “undocumented” options to save the information provided by the program to a file.

Table 3.90. Undocumented options for msinfo32.exe

Category.
Computer "computer". Display information about a remote computer.
Report "file". Save information to a text file.
Nfo "file". Save information in XML format.
Windows Memory Diagnostic Tool (MdSched.exe)
This program allows the next time the computer is restarted to start the diagnostic process of the RAM. In addition to starting the program without parameters, which is used to display the WINDOWS MEMORY DIAGNOSTIC TOOL dialog, you can use one of its options to simplify the work with the program.

More information about memory diagnostics can be found in the section "How do I know about problems with computer memory?", Which has the CLSID number 4edd5f80-def2-4d32-965c-116d49fb9872.

Table 3.91. Undocumented options for MdSched.exe

/ rn. Reboot the computer immediately and run RAM diagnostics.
/ rd. Run RAM diagnostics on next reboot.
/ rshd. Run RAM diagnostics on next reboot.
/ winpe. Display the Windows Memory Diagnostic Tool dialog.
Volume (Sndvol.exe)
Even a little program like Sndvol.exe contains undocumented options. With their help, the type of dialogue VOLUME is determined. For example, using the –r option, the VOLUME dialog is displayed, shown in Figure 3.11 on the left. And on the right in the same figure is the view of the VOLUME dialog when the –f option is specified.

### Scissors (Snippingtool.exe)
By default, Snippingtool.exe runs in screenshot mode. If you use the / p option, then the program will run normally.

For more information on how to use the Snippingtool.exe program, see Screen Capture Recorder, d which has CLSID 1337cdba-52a2-4704-ad4d-2d7bace605b4.

### Sound Recorder (Soundrecorder.exe)
Undocumented options are also supported by Soundrecorder.exe. For example, some of them are presented below.

Soundrecorder.exe / L [OG] "file". When recording, it creates a log file containing information about the progress of the recording process.
Soundrecorder.exe / F [ILE] "filename". Specifies the file name to be used when saving recorded data.
It should be noted that this program will not work if the group policy is set to DISABLE RUNNING OF THE SOUND RECORDING APPLICATION. This policy is located in the ADMINISTRATIVE TEMPLATES / WINDOWS COMPONENTS / SOUND RECORDING of the COMPUTER CONFIGURATION and USER CONFIGURATION sections and changes the value of the Soundrec DWORD value located in the Software \ Policies \ Microsoft \ SoundRecorder registry branch.

### Windows Remote Assistance (msra.exe)
Also, the "undocumented" options are supported by the msra.exe program. In addition, the capabilities of this program can be limited by using group policies. For this, the policies of the COMPUTER CONFIGURATION / ADMINISTRATIVE TEMPLATES / SYSTEM / REMOTE ASSISTANT section are applied. These policies change the values ​​of DWORD-type parameters and are described in the table below.

Table 3.92. Undocumented options for msra.exe

/ RAConnectionString "computer". Connects to a remote computer based on knowledge of the password.
/ CreateRAConnectionString. Creates a password for accessing a remote computer.
/ SolicitedIM. Specifies the password for the remote assistance connection.
/ OfferIM. Specifies the password for the remote assistance connection.
/ history "prompt". Displays the history of the remote assistance session.
/ RecoverDesktop. Sets the Altered Desktop DWORD value in the HKCU \ Software \ Microsoft \ Remote Assistance registry branch to 0.
Table 3.93. HKLM \ SOFTWARE \ Policies \ Microsoft \ Windows NT \ Terminal Services

CreateEncryptedOnlyTickets. Allow connections only from computers running Windows Vista or newer systems
LoggingEnabled. Enable session logging
UseBandwidthOptimization, OptimizeBandwidth. Enable bandwidth optimization
* ShareControlMessage, * ViewMessage, UseCustomMessages. Configuring warning messages
MaxTicketExpiryUnits, fUseMailto, fAllowFullControl, fAllowToGetHelp, MaxTicketExpiry. Remote assistance request
fAllowUnsolicitedFullControl, fAllowUnsolicited. Offer remote assistance
* parameter is of string type.

Help and Support: msra.exe Help Topics

1906e592-9192-46e4-92fa-d16eb716ad71. What is Windows Remote Assistance?
2001f924-eed7-4e5a-88d7-79c29a5e154c. Which connection method should I use in Windows Remote Assistance?
398b5eda-aa7f-4078-94c5-1519b697bfa0. Windows Remote Assistance FAQ
613faf4a-92a5-4250-827a-034c9a3933d6. How does Windows Remote Assistance affect my computer's privacy and security?
62087979-e422-48d6-a676-4f37ef5903c5. Using Windows Remote Assistance settings
62db2db0-1665-4136-95c4-2f5088ddbccf. What's the difference between Windows Remote Assistance and Remote Desktop Connection?
6fd17a90-60f3-4bf8-8f57-673484d40774. Providing support for solving computer problems using Windows Remote Assistance

### Backup status and configuration (sdclt.exe)
In addition to displaying the STATUS AND CONFIGURING ARCHIVING wizard using the sdclt.exe program, you can use one of the program options to display a specific wizard step.

Table 3.94. Undocumented options for sdclt.exe

/ RUNONCE. Displays the Archive Files wizard.
/ BACKUPPAGE. Displays the Archive Files step of the sdclt.exe wizard
/ RESTOREPAGE. Displays the File Recovery step of the sdclt.exe wizard
/ STARTBACKUPS. Displays the Archive Files wizard.
/ CONFIGURE. Displays the Back Up Files wizard to change the settings for automatic file archiving.
/ BLBBACKUPWIZARD. Displays the CompletePC Windows Backup wizard.
/ RESTOREWIZARDADMIN. Displays the File Recovery Wizard (advanced).
/ RESTOREWIZARD. Displays File Recovery.
/ UIMODE. Displays an alert Last backup was unsuccessful.
/ ENABLEJOB. Includes the previously created archive job.
/ DISABLEJOB. Disables a previously created archive job.
/ KICKOFFJOB. Ends running system backup jobs.
/ KICKOFFNEW. Completes the newly created quest

### System Restore (rstrui.exe)
The rstrui.exe utility supports several undocumented options.

Table 3.95. Undocumented options for rstrui.exe

/ RUNONCE. Displays information about the date the system was last restored.
/ OFFLINE: "rollback point". Restores the system from the point of rollback.

### Problem Reports and Solutions (wercon.exe)
You can use one of the options in the wercon.exe program to display a specific step in the PROBLEM REPORTING AND SOLUTIONS wizard.

Table 3.96. Undocumented wercon.exe options

-solutioncheck. Search for solutions to previously encountered problems.
-signoff. Displays the Find solutions to these problems window.
-problemhistory. Displays the Problems Detected by Windows window.
-showweropts. Displays the Choose a method to check for solutions if you have a problem with your computer.
-showsqmopts. Displays a dialog Want to join the Windows Customer Experience Improvement Program?
-downloadonly. Download problem solutions.
-adminarchive. Search for solutions to problems.
Help and Support: How the Wizard Works You can get problem reports and solutions from the following Help topics.

15d43eb3-45fd-4248-8bd5-2ed92ee29896
	Choosing which information to send when a problem occurs
5569a7bb-b6c5-4985-b5ab-c3cf224eae69
	What information is sent to Microsoft when a problem report is submitted?

### Windows Calendar (WinCal.exe)
Windows Calendar (located in the% programfiles% \ Windows Calendar directory) supports the ability to remind you of a specific day. This feature works on the basis of assigned tasks. To do this, a standard REMINDERS job is created, located in the JOB SCHEDULER LIBRARY / MICROSOFT / WINDOWS / WINDOWSCALENDER. This task, using the WinCal.exe / reminder command, implements the reminder function.

You can also use the / icsfile "file" option to import the calendar file. To do this, the IMPORT wizard will be displayed.

Another option that you can use is the / webcal "calendar" option. It subscribes to the specified calendar. For this, the CALENDAR SUBSCRIPTION wizard is launched.

Both the program itself and its options discussed above will not work if the group policy is set to DISABLE WINDOWS CALENDAR located in the COMPUTER CONFIGURATION / ADMINISTRATIVE TEMPLATES / WINDOWS COMPONENTS / WINDOWS CALENDAR section. This policy modifies the value of the TurnOffWinCal DWORD value located in the HKLM \ SOFTWARE \ Microsoft \ Windows \ CurrentVersion \ Policies \ Windows registry branch.

### Windows Media Center (ehshell.exe)
The Windows Media Center Shell suite is stored in the% SystemRoot% \ ehome directory. The main one is the ehshell.exe program, which, in fact, implements the Windows Media Center shell. The rest of the programs are designed to support the operation of this shell and are, as a rule, executable files of services.

Group Policies You can prevent Windows Media Center from running by using the DO NOT RUN WINDOWS MEDIA CENTER Group Policy located in the WINDOWS / WINDOWS MEDIA CENTER TEMPLATES / COMPONENTS subsection of the COMPUTER CONFIGURATION and USER CONFIGURATION sections.

This Group Policy modifies the value of the MediaCenter DWORD value located in the Software \ Policies \ Microsoft \ WindowsMediaCenter registry branch.

### Shell options 
The ehshell.exe program does not support any additional options. But the same cannot be said about other programs located in the% SystemRoot% \ ehome directory. In particular, the "undocumented" program options in the% SystemRoot% \ ehome directory are used by scheduled jobs in the JOB SCHEDULER LIBRARY / MICROSOFT / WINDOWS / MEDIA CENTER. These tasks and the options they use are presented below.

In addition to the options described in the table, ehPrivJob.exe supports the / OCURUnregister and / Event: "command" options. The first one unregisters the digital cable device. The second one executes a specific service command.

### The repository update manager (mcupdate.exe) supports many other options in addition to the –gc option. 

Some of them are described in the table below.

Assignment: ehDRMInit

Account: Runs with system rights.
Action:% SystemRoot% \ ehome \ ehPrivJob.exe / DRMInit
Optional: no.
Description: DRM Initialization of Privileged Media Center
Assignment: mcupdate

Account: Runs with the rights of the network service.
Action:% SystemRoot% \ ehome \ mcupdate $ (Arg0) –gc
Optional: Job does not start on battery power.
Description: Check for updates to the Media Center shell.
Task: OCURActivate

Account: Runs with system rights.
Action:% SystemRoot% \ ehome \ ehPrivJob.exe / OCURActivate
Optional: no.
Description: Activate OCUR Privileged Media Center
Assignment: OCURDiscovery

Account: Runs with system rights.
Action:% SystemRoot% \ ehome \ ehPrivJob.exe / OCURDiscovery
Optional: no.
Description: Discovery of OCUR privileged Media Center.
Assignment: UpdateRecordPath

Account: Runs with system rights.
Action:% SystemRoot% \ ehome \ ehPrivJob.exe / DoUpdateRecordPath $ (Arg0)
Optional: no.
Description: Sets the recording permission of the privileged Media Center.
Table 3.97. Mcupdate.exe program options

-lp. Displays information about subscription packages stored in the store.
-ls. Displays detailed information about warehouse subscription packages.
-dp "package ID". Remove package from repository.
-o "file". Output the result of the program to a file, not to the console.
-sp "package ID". Subscribe to the specified package.
-u. Delete.

### Windows Defender (MSASCui.exe)
Windows Defender is the MSASCui.exe program located in the% programfiles% \ Windows Defender directory.

Help and Support: The basics of how Windows Defender works can be found in the following Help topics

074f84cf-d303-4f62-ad3c-a1fb6434ae49. Reporting Suspicious Software to Microsoft SpyNet
b15d099f-68f5-4512-8bd2-68dd0dc9875e. Join the Microsoft SpyNet Community
09038554-ea5f-4db7-bba3-97a67ea29367. Deleting or restoring items quarantined by Windows Defender
13f74d76-344a-4dcc-9284-7ab43d9171b2. Turn Windows Defender Real-Time Protection On or Off
31d797aa-091d-4d67-a556-dbfaf21bf0dc. Turn Windows Defender On and Off
329da9be-1e0e-40f5-b6f5-f58617ec1839. Scheduling Windows Defender scans of your computer
3394e8a6-5416-4b89-91da-db7e9d1a7e3a. View Windows Defender scan progress
4c99fa18-7f2c-49d6-ba38-cac2d1e620af. Description of Windows Defender alert levels
4ef8da25-133e-4947-99c1-5c7951d48a15. Using Windows Defender (overview)
5d42c151-d187-4eb5-a4a3-8cf163e1b78d. Adding and removing objects from the Windows Defender allowed list
7f6dcd70-ad5e-4224-962d-737abdecab5e. Regularly updating Windows Defender definitions
8b8917f4-88c7-4470-88ae-0a06987c20fd. Description of Windows Defender Real-Time Protection
Windows Defender Options
This program supports the options shown in Table 3.98.

Table 3.98. Undocumented options for MSASCui.exe

-CheckForUpdates. Open the program and start the process of checking for updates to the malware database.
-UpdateAndQuickScan. Open the program and start the process of checking for updates to the malware database, and then start a quick scan.
-Hide. Display the application icon in the notification panel.
-QuickScan. Start a quick scan.
-FullScan. Start full scan.
-ScanResults. Display scan results.
-Settings. Display program options.
-ShowSWE. Display a list of startup programs
-ShowSWE: "Program Category GUID". Display a list of programs in this category.
Windows Defender limitations
You can customize the capabilities of WINDOWS PROTECTOR using group policies. To do this, use the section WINDOWS CONFIGURATION / ADMINISTRATIVE TEMPLATES / WINDOWS COMPONENTS / WINDOWS DEFENDER. The policies in this section change the values ​​of DWORD-type parameters.

First of all, it should be noted that using the DISABLE WINDOWS PROTECTOR policy, you can prevent the WINDOWS PROTECTOR from starting. This policy modifies the value of the DisableAntiSpyware setting in the HKLM \ SOFTWARE \ Policies \ Microsoft \ Windows Defender registry branch.

Alternatively, you can use the CHECK NEW SIGNATURE BEFORE SCANNED SCAN policy, which changes the value of the CheckForSignaturesBeforeRunningScan parameter located in the HKLM \ SOFTWARE \ Policies \ Microsoft \ Windows Defender \ Scan registry branch.

And using the DISABLE REAL-TIME PROTECTION REQUEST ON DETECTION OF UNKNOWN FILES, the value of the EnableUnknownPrompts parameter in the HKLM \ SOFTWARE \ Policies \ Microsoft \ Windows Defender \ Real-Time Protection registry branch is changed.

If you need to configure work with Microsoft SpyNet, then you should use the CUSTOMIZE MICROSOFT SPYNET REPORTS policy. This policy modifies the value of the SpyNetReporting parameter located in the HKLM \ SOFTWARE \ Policies \ Microsoft \ Windows Defender \ SpyNet registry branch.

The rest of the policies that customize the operation of Windows Defender are presented in the tables below.

Table 3.99. HKLM \ SOFTWARE \ Policies \ Microsoft \ Windows Defender \ Signature Updates

CheckAlternateDownloadLocation. Enable definition updates using WSUS and Windows Update
ForceFullUpdate. Load entire set of signatures
Table 3.100. HKLM \ SOFTWARE \ Policies \ Microsoft \ Windows Defender \ Reporting

DisableLoggingForKnownGood. Enable logging for known trusted files
DisableLoggingForUnknown. Enable logging when unknown files are found
Internet Explorer (iexplore.exe)
The Internet Explorer browser supports one very useful, in some cases, function - the ability to launch the browser with all add-ons disabled and the very ability to enable them. The –extoff option is used for this.

### Windows Media Configuration Manager (setup_wm.exe)
Windows Media Customization Manager is used to customize, update, and install Windows Media Player. It is located in the% programfiles% \ Windows Media Player directory.

When you run setup_wm.exe with no options, the Windows Media Update Wizard appears and tries to search for player updates. If no new updates are found, the wizard will exit. Table 3.101 lists the options that can be used with this program.

Table 3.101. Undocumented options for the setup_wm.exe program

/ UpdateCheck. Check the player version and display the results.
/ RunOnce. Run the Windows Media Player 11 Installation Wizard.
/ FixUp. Check and install updates.
/ Quiet. Work in a "quiet" mode.
/ WUScan. Check the player version and display the results.
/ DownloadService. Start the update download service.
/ UninstallAll. Remove updates.
Scanners and Cameras (Imagingdevices.exe)
In addition to displaying the SCANNER AND CAMERA Wizard, you can display the SCANNER AND CAMERA Wizard by using Imagingdevices.exe located in the% programfiles% \ Windows Photo Gallery directory. The –InstallWiaDevice option is used for this.

### Windows Mobile Device Center (wmdc.exe)
To display the WINDOWS MOBILE DEVICE CENTER, you must use the / show option of wmdc.exe located in the% systemroot% \ WindowsMobile directory.
