Privacy Policy — MedAlert

**Last updated: July 27, 2026**

1. Overview
MedAlert is a personal medicine reminder app developed under ES brand. This privacy policy explains what data the app collects, how it is stored, and how it is used. We are committed to protecting your privacy and handling your health data responsibly.

2. Data We Collect
MedAlert collects and stores the following information solely for the purpose of managing your medicine reminders:

- **Patient name** — to identify the person taking the medicines
- **Doctor name and hospital name** — to organize prescriptions
- **Visit date and follow-up date** — to track prescription history
- **Medicine names, organ names to which medicins have to be applied, and dose timings** — to schedule reminders
- **Prescription photo** — optionally uploaded or captured to keep a digital copy
- **Family contact phone number** — optionally provided to send SMS dose notifications

3. How Data Is Stored
- All data is stored exclusively on your device in encrypted form
- A secondary encrypted backup is written to your device's local Documents folder (`MedicineReminder/prescriptions_backup.bin`) for recovery purposes
- No data is transmitted to any server, cloud service, or third party by the app itself
- The prescription photo is stored as a URI reference pointing to your device's local media storage
- Only one patient's prescriptions can be used with this App
- Use this app to store and schedule alarms for adults

4. Permissions We Request

| Permission.              | Why It Is Needed |
| `POST_NOTIFICATIONS`     | To show medicine reminder notifications |
| `SCHEDULE_EXACT_ALARM`   | To fire reminders at the precise scheduled time |
| `SYSTEM_ALERT_WINDOW`    | To show the alarm screen even when the phone is locked |
| `SEND_SMS`.              | To notify a family contact when a dose is applied or missed |
| `CAMERA`.                | To photograph the doctor's prescription |
| `READ_EXTERNAL_STORAGE`  | To upload an existing prescription photo from your gallery |
| `WRITE_EXTERNAL_STORAGE` | To save the encrypted prescription backup to Documents |

All permissions are requested only when needed and explained in context. SMS and camera permissions are optional — the app functions fully without them.

5. SMS Usage
If you provide a family contact number, MedAlert will send an SMS when:

- A dose is marked as **applied**
- A dose is marked as **skipped**
- A dose alarm fires and **no action is taken within 5 minutes**

SMS messages are sent directly from your device using your SIM. MedAlert does not route messages through any server. Standard carrier charges may apply.

6. Biometric Authentication
MedAlert uses your device's biometric or PIN authentication (via Android BiometricPrompt) to protect access to your prescription data. Biometric data is never accessed or stored by the app — authentication is handled entirely by the Android operating system.

7. Data Sharing
MedAlert does **not**:

- Share your data with any third party
- Upload your data to any server or cloud
- Use your data for advertising or analytics
- Track your location or behaviour

8. Data Deletion
You can delete your data at any time by:

- Deleting individual prescriptions from within the app — this removes all associated alarms and data
- Deleting all prescriptions — this also wipes the local encrypted backup file
- Uninstalling the app — this removes all SharedPreferences data from the device

The backup file in Documents (`MedicineReminder/prescriptions_backup.bin`) can be manually deleted from your device's file manager if needed.

9. Changes to This Policy
If this privacy policy is updated, the revised version will be made available with an updated date at the top. Continued use of the app after changes constitutes acceptance of the updated policy.

10. Contact
If you have any questions or concerns about this privacy policy or how your data is handled, please contact:

**Developer:** MedAlertApp2026
**App:** MedAlert — Medicine Reminder
**Email:** medalertapp2026@gmail.com

*MedAlert is built with your health and privacy in mind. All your prescription data stays on your device — always.*
