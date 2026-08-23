Sursand Connect Super Admin v2.3

FIXED
- Login button uses a direct event listener instead of unreliable element-id globals.
- All important DOM elements are now accessed with document.getElementById.
- Login works with click and Enter key.
- Added Show/Hide password on the Super Admin login screen.
- Existing valid Super Admin session is stored in localStorage and restored after refresh.
- Invalid/expired stored sessions return to Login cleanly.

RETAINED
- Light theme default + Dark/Light toggle.
- Multicolour 3D module cards.
- Confirmation dialogs before Add, Edit, Delete, Staff Admin create/enable/disable and password change.
- Super Admin notification bell and unseen red dot.
- Super Admin password change with Show/Hide controls.

No Apps Script change is required for v2.3.
