LIMA MVP — First prototype

Included:
- Crop/planting records
- Farm tasks and mark-complete
- Harvest records
- Sales and expenses in Emalangeni
- Basic totals and estimated balance
- English / draft siSwati language toggle
- Export records as a JSON backup
- Basic service-worker caching for offline app loading when hosted over HTTPS

IMPORTANT LIMITATIONS:
- This is a prototype, not a public production app.
- Records are saved only in local browser storage on this device.
- There are no private logins, cloud database, online sync, multi-device access, or server backups yet.
- Export backups regularly. Do not rely on this prototype as the only copy of important farm records.
- The siSwati translations are a first draft and should be checked by a fluent siSwati speaker.
- To test PWA installation and offline caching, host these files over HTTPS. Opening index.html directly does not enable service-worker features.
