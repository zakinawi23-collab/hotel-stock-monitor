# Hotel Stock Monitor

An offline-first Progressive Web App for managing hotel housekeeping supplies.

## Included categories
- Amenity
- Minibar
- Guest supplies
- Linen
- Toiletries
- Cleaning supplies

## Features
- Add, edit and delete inventory items
- Stock in / stock out with quantity and notes
- Low-stock and out-of-stock alerts
- Search and category filters
- Movement history
- CSV inventory report
- JSON backup export and restore
- Local browser storage and offline caching

## Publish with GitHub Pages
1. Open this repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then press **Save**.
5. Wait for GitHub Pages to publish. Your app URL will be:
   https://zakinawi23-collab.github.io/hotel-stock-monitor/
6. On Android Chrome, open the URL menu and choose **Install app** or **Add to Home screen**.

## Use
- Add each supply with its category, current quantity, unit and minimum stock threshold.
- Use **Stock in / out** to record every delivery or issue.
- Use **Backup** to download a JSON copy. Use **Restore** to restore it later.
- Use **Export CSV** in Reports to open the stock list in a spreadsheet.

## Data and privacy
This version is designed for one device. Stock and history are stored locally in that device's browser; they are not synchronized to a server. Export backups regularly. Clearing browser/site data may erase locally stored stock records.

## Notes
This is an inventory helper, not an official hotel procurement or accounting system. Check counts physically and keep backups.
