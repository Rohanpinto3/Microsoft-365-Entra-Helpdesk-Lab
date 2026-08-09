# Microsoft 365 + Zoom Practice Lab (Hands-on Project)

### Overview
In this lab, I practiced core Microsoft 365 apps (Outlook, Word, Excel, Teams, OneDrive) by simulating real help desk requests, then hosted and troubleshot Zoom meetings to resolve common audio/video issues. The goal was to build practical user-support experience I can explain clearly to recruiters.

### Lab Environment
  Device: Windows 11 PC (or VM)
### Tools used:
  * Microsoft 365: Outlook, Word, Excel, Teams, OneDrive
  * Zoom Desktop Client
  * Optional: Web browser (Edge/Chrome) for admin portals and test links

### Objectives
  * Handle typical end-user requests across Outlook, Word, Excel, Teams, and OneDrive.
  * Host a Zoom meeting and fix common meeting issues (no audio, bad mic, camera not working, screen share problems).
  * Document steps and capture proof screenshots for a GitHub portfolio.


# Part A: Microsoft 365 Simulated User Requests
### 1. Outlook: Email + Calendar Support Tasks
#### Task A1: Create email signature and apply it to new messages and replies
What I did
  * Opened Outlook.
  * Went to File → Options → Mail → Signatures.
  * Created a signature with my name, role, and phone format.
  * Set it as default for New messages and Replies/forwards.
  * Sent myself a test email to confirm it works.
    <img width="1917" height="924" alt="image" src="https://github.com/user-attachments/assets/11577a0a-3aff-4d7e-9fd7-246af5eebcf1" />


#### Task A2: Fix “Outlook search not returning results”
What I did
  * Confirmed the user issue: searched a known email subject and got no results.
  * Checked indexing status:
    * Search bar → Search Tools → Indexing Status
  * If indexing was incomplete, I waited briefly and re-tested.
  * If still broken, I repaired Office:
    * Control Panel → Programs → Microsoft 365 → Change → Quick Repair
  Reopened Outlook and tested search again.



#### Task A3: Create a meeting invite and share availability
What I did
  * Opened Outlook Calendar.
  * Clicked New Meeting.
  * Added attendees and checked Scheduling Assistant.
  * Set time and sent invite.
  * Verified the invite appeared on calendar.
    <img width="1920" height="912" alt="image" src="https://github.com/user-attachments/assets/e43f6d73-c7d8-4b91-b302-837588cc0abe" />



### 2. OneDrive: File Sync + Sharing Troubleshooting
#### Task B1: Confirm OneDrive is syncing correctly
What I did
  * Clicked the OneDrive cloud icon in the system tray.
  * Opened Help & Settings → Settings.
  * Confirmed the correct account is signed in.
  * Tested sync:
    * Created a folder OneDrive-Lab
    * Added a small file
    * Confirmed green check marks (synced)
      <img width="1913" height="919" alt="image" src="https://github.com/user-attachments/assets/894b09b2-734e-487b-9aac-ed71fd06fe0a" />


#### Task B2: Fix “Files not syncing”
What I did
  * Checked common causes:
    * Internet connection stable
    * OneDrive not paused
    * Enough disk space
  * Restarted OneDrive:
    * Help & Settings → Close OneDrive
    * Relaunched OneDrive from Start menu
  * If still failing, I reset OneDrive:
    * Ran: onedrive.exe /reset
  * Re-tested sync by uploading a file again.



#### Task B3: Share a file with view-only permissions
What I did
  * Right-clicked a file in OneDrive folder.
  * Selected Share.
  * Set permission to Can view.
  * Copied the link and tested it in an incognito browser window.
      <img width="1920" height="920" alt="image" src="https://github.com/user-attachments/assets/4b21a08e-0561-4537-a1f9-e20e90b9cc50" />



### 3. Word: Formatting + Recovery Scenario
#### Task C1: Fix document formatting (headings + consistent style)
What I did
  * Opened a messy document.
  * Applied Heading 1, Heading 2 styles consistently.
  * Used Format Painter to standardize text.
  * Inserted page numbers and updated margins.


#### Task C2: Recover an unsaved Word document
What I did
  * Opened Word.
  * Went to File → Info → Manage Document → Recover Unsaved Documents.
  * Restored the latest version and saved it properly.


### 4. Excel: Basic Help Desk Requests
#### Task D1: Fix #VALUE! and incorrect formulas
What I did
  * Opened an Excel sheet with calculated totals.
  * Identified #VALUE! caused by text values in numeric cells.
  * Cleaned data:
    * Removed spaces
    * Converted number-stored-as-text
  * Re-tested formulas and confirmed correct totals.


#### Task D2: Create a simple table + filter
What I did
  * Selected a dataset.
  * Pressed Ctrl + T to convert it into a table.
  * Enabled filters and tested sorting by a column.


### 5. Teams: Meeting and Chat Support
#### ask E1: Create a Teams meeting and share the link
What I did
  * Opened Teams.
  * Went to Calendar → New meeting.
  * Set title/time and copied the meeting link.
  * Joined from another device/browser to test.
    <img width="1912" height="915" alt="image" src="https://github.com/user-attachments/assets/b426fc89-b180-44af-bebd-5b9fe126f2a0" />


#### Task E2: Fix Teams mic not working
What I did

  * Checked Teams device settings:
    * Settings → Devices
  * Confirmed correct microphone selected.
  * Verified Windows privacy:
    * Settings → Privacy → Microphone access
  * Tested with a Teams test call (if available) or joined a meeting and checked mic meter.
    <img width="1920" height="906" alt="image" src="https://github.com/user-attachments/assets/a7cdb1c0-3a51-4ef0-8435-cdd6b99ccebb" />


# Part B: Zoom Hosting + Troubleshooting
### 1. Hosted a Zoom meeting (as the organizer)
What I did
  * Opened Zoom desktop app.
  * Clicked New Meeting.
  * Enabled Waiting Room and confirmed host controls.
  * Practiced:
    * Admit/remove participants
    * Mute all
    * Lock meeting
    * Share screen

      <img width="1919" height="927" alt="image" src="https://github.com/user-attachments/assets/91be49a3-613c-4d65-bbeb-d5e0b7d57f06" />



### 2. Troubleshot common Zoom issues
#### Issue 1: “I can’t hear anyone”
Fix steps I used
  * Checked Zoom audio output:
    * Click ^ next to speaker icon → Select Speaker
  * Tested speaker audio.
  * Confirmed Windows volume mixer isn’t muted.
    <img width="1920" height="1028" alt="image" src="https://github.com/user-attachments/assets/ac1700fe-dca8-4b1a-b7d6-9ad84866737d" />


#### Issue 2: “My microphone isn’t working”
Fix steps I used
  * Clicked ^ next to mic → Select Microphone.
  * Tested mic input meter.
  * Checked Windows microphone privacy settings.
  * Closed apps that might be using the mic (Teams, browser tabs, etc.).


#### Issue 3: “Camera not working / black screen”
Fix steps I used
  * Zoom ^ next to camera → selected correct camera.
  * Checked if another app is using the camera (Teams, camera app).
  * Confirmed Windows camera privacy access is enabled.
  * Restarted Zoom and re-tested.


#### Issue 4: “I can’t share my screen”
Fix steps I used
  * Verified host permissions:
  * Host controls → Security → Allow participants to share (if needed)
  * Tested sharing the entire screen vs a single window.
  * Confirmed no restricted policy or conflicting app overlay.



### Results
By completing these tasks, I demonstrated practical end-user support skills across Microsoft 365 and Zoom, including configuring apps, troubleshooting common user issues, validating fixes, and documenting the process in a recruiter-friendly format.
