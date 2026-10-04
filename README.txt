ARDAAS AGRI & MILK FARM — MILK APP  (version 1.0.0)
=====================================================

WHAT THIS FOLDER IS
These files are the app itself (the "code"). They contain NO customer data.
Every phone that opens the app keeps its own records inside that phone's browser storage.
Your phone and your uncle's phone never share or sync data.

FILES
  index.html              the whole app
  sw.js                   lets the app open without internet
  manifest.webmanifest    lets the phone install it like an app
  icon-*.png, apple-touch-icon.png   app icons
  README.txt              this note (not needed by the app)

-----------------------------------------------------
STEP 1 — PUT THE APP ONLINE ONCE (free, about 5 minutes, needs a laptop or desktop)
-----------------------------------------------------
The phone must load the app from an https:// web address one time. After that it works offline.
Any free static host works. Two easy choices:

  A) Netlify Drop
     1. Unzip this folder on a computer.
     2. Open app.netlify.com/drop in a browser.
     3. Drag the unzipped folder (the one containing index.html) onto the page.
     4. Create a free Netlify account when asked so the site is kept permanently.
     5. You get an address like https://something.netlify.app — you can rename it.

  B) GitHub Pages
     1. Create a free GitHub account and a new public repository (e.g. "ardaas-milk").
     2. Upload all files from this folder (all 7 files).
     3. Repository Settings -> Pages -> Deploy from branch "main", folder "/ (root)".
     4. Your address will be https://YOUR-NAME.github.io/ardaas-milk/

The hosting account only holds these app files. Your dairy data never goes there.

-----------------------------------------------------
STEP 2 — INSTALL ON EACH PHONE (yours and your uncle's)
-----------------------------------------------------
  1. Open the address in Chrome on the phone (internet needed this first time).
  2. Chrome menu (⋮) -> "Add to Home screen" / "Install app".
     (iPhone: Safari -> Share -> Add to Home Screen.)
  3. Open it from the home screen icon. On first open, type a name for this copy
     (for example "Uncle") and start adding customers.
  4. In the app: More -> Settings -> "Ask the phone to protect storage".

Both phones can use the SAME address. Each phone still has its own separate data.

-----------------------------------------------------
BACKUPS — please do this every week
-----------------------------------------------------
  More -> Backup & Restore -> BACKUP DATA
  The file (e.g. ardaas-milk-backup-uncle-2026-10-03.json) is saved in Downloads.
  Send it to yourself on WhatsApp or upload it to Google Drive.
  If the phone is lost, broken, reset, or Chrome's data is cleared, the backup file
  is the ONLY way to get the records back.

-----------------------------------------------------
UPDATING TO A NEW VERSION LATER
-----------------------------------------------------
  Same address (normal case): upload the new files to the same site.
    Each phone shows "A new version of the app is ready" -> tap Update.
    Data stays on the phone and is upgraded automatically. Make a backup first anyway.
  New address / new phone:
    Old app: BACKUP DATA -> open new app -> RESTORE DATA -> pick the file -> Restore Backup.
    Older backups are upgraded automatically.

DO NOT
  - clear Chrome "site data" / "storage" for this site (that deletes the records)
  - use an incognito/private window for daily work
