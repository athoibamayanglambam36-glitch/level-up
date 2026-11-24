LEVEL UP — YOUR PERSONAL DASHBOARD

This is a local-first web app, not an App Store app. It contains no analytics,
external libraries, payment features, or server-side account. The encrypted
vault is stored in your browser. The app itself can be hosted as static files;
public hosting exposes the app code, not your saved personal entries.

WINDOWS — QUICK START
1. Extract the ZIP. Keep all files in one folder.
2. Double-click index.html to try in Chrome or Edge. If local file storage or
   Web Crypto is blocked, use HTTPS hosting below. If Python is installed,
   you can also open a terminal in the folder and run python -m http.server
   8000 --bind 127.0.0.1 then open http://127.0.0.1:8000 in your browser.
3. Create a strong unique passphrase, preferably several random words. Do not
   share it. A forgotten passphrase cannot be reset.

IPHONE — HOME SCREEN INSTALLATION
1. Host the five app files (index.html, manifest.webmanifest, sw.js and the two
   icon PNG files) together on an HTTPS static website you control. For example,
   GitHub Pages can host public static code for free if you are eligible to use
   it. Never upload vault backups or personal data to the repository.
2. Open the resulting HTTPS URL in Safari on your iPhone.
3. Tap Share > Add to Home Screen > Add (and enable Open as Web App if shown).
4. Launch Level Up from the Home Screen. Create your vault in that app. Its
   browser storage may be separate from Safari's regular tab storage.
5. Once the app shell is successfully cached, it is designed to open offline.

PRIVACY AND BACKUP
- The passphrase derives an AES-GCM encryption key using PBKDF2/SHA-256.
- Use the Lock button when you finish. The app also attempts to lock after
  15 minutes of inactivity, excluding an active focus timer.
- No personal data is uploaded by the app. A host may see normal page requests.
- A public app URL means others can open their own empty copy; they cannot
  automatically see your entries. The app is not an account access-control
  system for the hosted source code. Use a trusted host and device lock.
- No cross-device sync. Use Progress > Export encrypted backup. Save it to a
  safe local folder. To move devices, use Restore backup and the old passphrase.
- Clearing browser/site data, uninstalling the app, or browser storage eviction
  can erase the vault. Back up regularly. Do not enter passwords for other sites,
  or other highly sensitive information.
- This app is a personal planning aid, not medical advice or official exam prep.
