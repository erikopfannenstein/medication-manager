MEDICATION MANAGER PWA

GitHub Pages setup
1. Create a new GitHub repository, for example: medication-manager
2. Upload every file and folder from this package to the repository root.
3. In GitHub, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the main branch and /root, then Save.
6. Open the GitHub Pages URL in Safari on iPhone.
7. Tap Share > Add to Home Screen.

Important storage notes
- Patient and medication data are stored in the browser on each device.
- Data do not sync automatically between iPhone and computer.
- Clearing website data can erase local records.
- Use Export Backup regularly and store backups only in an approved secure location.
- The GitHub repository contains only the app code. Do not place patient data or exported backups in the repository.

Updating the app
- Replace index.html, manifest.json, service-worker.js, and icons as needed.
- If an old version remains cached, change CACHE_NAME in service-worker.js (for example v1 to v2).
