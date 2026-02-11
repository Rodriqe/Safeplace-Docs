# Privacy Policy for Safeplace

**Last Updated: February 11, 2026**

## Introduction

Safeplace ("we", "our", or "the app") is committed to protecting your privacy. This Privacy Policy explains how we handle your information when you use our mobile application.

## Information We Collect

### User-Provided Content

Safeplace allows you to store the following types of content:
- Photos and videos from your device's photo library
- Documents and files from your device
- Folder names and organizational information you create

**Important**: All content you add to Safeplace is stored encrypted on your device only. We do not collect, transmit, or store any of your files or data on external servers.

### Data We Do NOT Collect

We do not collect:
- Personal identification information (name, email, phone number)
- Device identifiers for tracking purposes
- Location data
- Usage analytics or behavioral data
- Advertising identifiers (IDFA)
- Any data from third-party services

## How We Use Your Information

All data in Safeplace is used solely for:
- **App Functionality**: Storing and organizing your files securely on your device
- **Encryption**: Protecting your files with AES-256 encryption using passwords you create
- **Local Storage**: Keeping your encrypted files in the app's secure container

Your data is NEVER:
- Sent to external servers
- Shared with third parties
- Used for advertising or marketing
- Used for tracking or analytics
- Accessible to us (the developers)

## Data Security

### Encryption

All files stored in Safeplace are encrypted using:
- **AES-256-CBC** encryption with PKCS#7 padding
- **PBKDF2-HMAC-SHA256** key derivation (10,000 iterations) for password-protected folders
- **iOS Keychain** storage with `kSecAttrAccessibleWhenUnlockedThisDeviceOnly` for device-protected folders
- Unique random initialization vectors (IV) and salts for each encryption operation

### Local Storage Only

- Files are stored in the app's secure sandbox (`Application Support` directory)
- Files are encrypted at rest and only decrypted temporarily for viewing
- Encrypted files are excluded from device backups (when applicable)
- No cloud synchronization or external storage

### Data Retention

- **Active Files**: Stored indefinitely until you choose to delete them
- **Trash**: Deleted files are retained in Trash for 30 days before permanent deletion
- **Backups**: You may export encrypted backups (`.safeplacebackup` files) which remain under your control

## Your Rights and Control

You have complete control over your data:

- **Access**: You can view and access all your files within the app at any time
- **Modification**: You can edit, rename, or organize your files and folders
- **Deletion**: You can delete files and folders at any time
- **Export**: You can export encrypted backups to share or move to another device
- **Complete Removal**: Uninstalling the app permanently deletes all local data

## Third-Party Services

Safeplace does not integrate with, transmit data to, or receive data from any third-party services, including:
- Analytics services
- Advertising networks
- Cloud storage providers
- Social media platforms

## Children's Privacy

Safeplace does not knowingly collect or store any information from children. The app is designed for general use and does not require any age verification or personal information.

## Sharing Your Data

### Normal Share

When you use the "Share" or "Share Files" function:
- Files are temporarily decrypted and shared as standard files (JPG, PDF, MP4, etc.)
- Recipients receive unencrypted files and can open them with any compatible app
- You control what files to share and with whom

### Secure Share (Encrypted Backup)

When you use "Secure Share (Backup)":
- Files are exported as an encrypted `.safeplacebackup` file
- Recipients need Safeplace and the password you set to access the files
- The encrypted backup remains under your control

## Permissions

Safeplace requests the following iOS permissions:

### Photo Library Access
- **Purpose**: To import photos and videos into secure encrypted storage
- **Usage**: Only accessed when you explicitly choose to add media files
- **Scope**: You can select specific photos; full library access is not required

### Photo Library Add Usage
- **Purpose**: To save exported photos back to your device's photo library
- **Usage**: Only when you explicitly export files from Safeplace

### Camera Access (if used)
- **Purpose**: To take photos or videos directly for encrypted storage
- **Usage**: Only when you explicitly use the camera feature within the app

All permissions are optional and only used when you initiate the corresponding action.

## Data Storage Location

All data is stored locally on your iOS device in:
- **Path**: `Application Support/Safeplace/`
- **Protection**: Files are protected by iOS file protection and app encryption
- **Isolation**: Data is sandboxed and inaccessible to other apps

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be reflected in:
- The "Last Updated" date at the top of this policy
- App updates that include the revised policy
- Notification within the app (for significant changes)

Your continued use of Safeplace after changes constitutes acceptance of the updated policy.

## International Users

Safeplace is designed for use worldwide. Since all data is stored locally on your device:
- No data crosses international borders through our app
- No data is stored on servers in any jurisdiction
- All data protection is handled by your device's iOS security

## Your Consent

By using Safeplace, you consent to this Privacy Policy.

## Contact Us

If you have questions about this Privacy Policy or how Safeplace handles data, you can contact us:

- **GitHub**: https://github.com/Rodriqe/Safeplace
- **Issues**: https://github.com/Rodriqe/Safeplace/issues
- **Email**: [Your contact email here]

## Legal Compliance

Safeplace complies with:
- Apple's App Store Review Guidelines
- iOS data protection requirements
- GDPR principles (though no personal data is collected)
- CCPA principles (though no personal data is sold or shared)

---

## Summary (TL;DR)

✅ **All your files stay on YOUR device, encrypted**  
✅ **No data collection, no tracking, no ads**  
✅ **No servers, no cloud, no third parties**  
✅ **You have complete control over your data**  
✅ **Strong encryption (AES-256) protects your files**  
✅ **We cannot access your data (even if we wanted to)**  

---

**Safeplace - Your privacy is our priority.**
