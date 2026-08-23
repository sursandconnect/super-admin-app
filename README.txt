Sursand Connect Super Admin v2.2

FIXES
- Login button works again.
- Fixed JavaScript syntax error introduced in v2.1.
- Super Admin login session is saved in localStorage.
- Refreshing/reopening the page restores the Super Admin session while the backend token is still valid.
- Logout explicitly clears the saved Super Admin token.
- Stored session is validated against the backend on page load.

CONFIRMATIONS
- Beautiful confirmation popup before Add, Edit, Delete, Staff Admin creation,
  Staff Admin enable/disable, and Super Admin password change.

NOTIFICATIONS
- Super Admin notification bell restored.
- Red dot appears only for unseen private request/admin notifications.
- Notifications are checked after login and every 60 seconds while the app is open.
- Opening the bell marks displayed notifications as seen on that device.

DESIGN
- Light theme remains default.
- Light/Dark toggle retained.
- Multicolour 3D module cards retained.

No Apps Script/backend change is required for this v2.2 frontend fix.
