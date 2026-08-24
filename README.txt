SURSAND CONNECT SUPER ADMIN v4

HOME
- Home is fixed and does not scroll.
- 3-column module grid fills the available screen below the saffron header.
- Clicking a module opens module.html as a separate page. Module contents never open below Home cards.

FORMS
- Explicit professional forms are defined for every editable module.
- Fixed values are dropdowns instead of free text wherever practical.
- ID is never shown or requested in Add/Edit forms.
- Backend generates IDs automatically using the existing prescribed sheet prefixes and 4-digit sequence.
- Image fields use image upload / device camera, not URL entry.

TRANSPORT
- Service Category dropdown: Passenger / Goods.
- Vehicle Type dropdown.
- Starting Point defaults to Sursand and is read-only.
- End Point is separate.
- Route Name is generated as Sursand - End Point.
- Add any number of stoppages.
- Each stoppage has Stop Name, Arrival Time and Fare.
- Stoppages are saved into Stop Names / Arrival Times / Fare Details for the existing Sursand Connect transport page.

HEALTHCARE
- Complete healthcare facility form: Facility Name, Facility Type, Services, Contact, WhatsApp, Ward, Address, Map, Image, Status.
- Doctor form includes Healthcare Facility dropdown, Degree, Medical System, Speciality, Availability, Days, Times and Contact.

SMOOTH ACTIONS
- Confirmation appears above forms.
- Successful Save/Edit/Approve/Reject/Delete closes the active form and shows a success toast.
- Module data refreshes after the action.

BACKEND
1. Replace Code.gs with Code_v10_2.gs.txt.
2. Add V4_Setup.gs using V4_Setup.gs.txt.
3. Run runSuperAdminV4Setup() once.
4. Redeploy Apps Script as a new version.
5. Upload the Super Admin v4 files to the separate Super Admin GitHub repository.
