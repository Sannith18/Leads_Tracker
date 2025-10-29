Leads Tracker Chrome Extension
------------------------------
Leads Tracker is a Chrome Extension that helps users save, organize, and manage leads such as website URLs, client details, or research links directly from their browser.
It is built to simplify the process of collecting and revisiting potential business or study opportunities with just one click.

Project Overview
------------------
The Leads Tracker allows users to store important web links or data without needing to open another app.
It saves leads locally in the browser using Chrome storage or localStorage, making it fast, secure, and easy to use offline.
This project is ideal for freelancers, marketers, or students who frequently gather online resources.

Key Features
-------------
Add and save leads (URLs or text) manually or from the current tab
View, manage, and delete stored leads anytime
Data automatically saved using localStorage
Simple and clean user interface
Works offline after installation
No login or internet dependency

Tech Stack
-----------
Languages and Tools
HTML, CSS, JavaScript
Chrome Extensions API (Manifest V3)
LocalStorage / Chrome Storage

Concepts Used
-------------
DOM Manipulation
Event Handling
Storage Management
UI Design with HTML and CSS

How It Works
------------
User opens a website or link they want to save
Click the Leads Tracker icon in the Chrome toolbar
Click “Save Tab” to store the current URL or manually enter a lead
Leads are saved and displayed in the extension popup
User can delete individual leads or clear all data anytime

Project Structure
-----------------
Leads-Tracker/
│
├── manifest.json
├── popup.html
├── popup.js
├── popup.css
├── icons/
│ ├── icon16.png
│ ├── icon48.png
│ └── icon128.png
└── README.md

Installation Steps
------------------
Download or clone this repository:
git clone https://sannith18.github.io/Leads_Tracker/
Open Google Chrome and go to chrome://extensions/
Turn on Developer Mode (top-right corner)
Click Load unpacked
Select your project folder (Leads-Tracker)
The extension icon will appear in your Chrome toolbar
