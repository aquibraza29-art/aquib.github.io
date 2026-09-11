# CNG Dispenser Monitoring System — Working Prototype

## Run
Open `index.html` in a modern browser. Internet access is required on first load for the SheetJS CDN used by Excel export.

## Login
Username: admin
Password: admin123

## Included
- Login screen
- Station database
- Dispenser database
- Live status dashboard
- Status changes
- Breakdown ticket creation
- Restore/close ticket
- Automatic ticket downtime calculation
- MTTR and availability KPI cards
- Excel export for Stations, Dispensers and Tickets
- Browser localStorage persistence

## Important
This is a browser prototype. It does not yet connect to real station PLC/SCADA/IoT data or provide multi-user server-side authentication. For production deployment, add a backend database, role-based access, API/IoT gateway, audit trail, HTTPS and server-side authentication.
