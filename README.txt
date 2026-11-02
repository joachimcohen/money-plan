MONEY PLAN APP: how to put it online with GitHub Pages

1. On github.com, create a new public repository (for example "money-plan").
2. Click "Add file", then "Upload files". Drag in ALL the files from this folder:
   index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png, apple-touch-icon.png.
   Click "Commit changes".
3. Go to Settings, then Pages. Under "Build and deployment" choose "Deploy from a branch",
   pick the "main" branch and the "/ (root)" folder, then Save.
4. After a minute or two your link appears at the top of that page, usually
   https://YOURNAME.github.io/money-plan/ . Open it on a phone to test.
   Turn that link into a QR code to share.

BEFORE YOU SHARE IT
- Open index.html in a text editor and find CONFIG near the top of the script.
  Paste your spreadsheet link between the quotes of SPREADSHEET_URL.
  The "spreadsheet version" button only shows once a link is there.
- The two help links in CONFIG can be changed or removed.

MOVING IT TO DUSA LATER
- Upload the same six files to any web host, in one folder. Nothing else needs changing.
- People who used the GitHub link keep their data on that link. A new web address is a
  new, empty copy for them, so they would need to use Save a backup and Restore to move over.

UPDATING
- Upload a changed index.html over the old one. Phones pick up the new version the next
  time the app is opened with internet. To force it, change CACHE = 'moneyplan-v1' in sw.js to v2.
