# Privacy Policy for Warranto

**Last Updated:** February 27, 2026

This Privacy Policy describes how Warranto ("we", "our", or "the app") collects, uses, and protects your information when you use our mobile application.

---

## 1. Information Collection and Use

### Data Collected Locally

Warranto stores the following information **locally on your device only**:

- **Receipt Details:** Product names, store names, purchase dates, warranty expiration dates, purchase amounts, and personal notes you add
- **Product Photos:** Images of receipts and products captured via camera or imported from your device's gallery
- **Categories:** Your organization of receipts into categories (Electronics, Household, Clothing, Furniture, Sports, Other)
- **Reminder Preferences:** Your custom reminder notification settings for warranty expiration alerts

### How Data is Stored

All data is stored in a **local SQLite database** on your device. This includes:

- Receipt information
- Product photos (stored in app's private directory)
- Category assignments
- User preferences

**Important:** We do **NOT** transmit your receipt data, photos, or any personal information to our servers or any third-party servers. Your data stays entirely on your device.

---

## 2. Third-Party Services

### Sentry Crash Reporting

Warranto uses **Sentry** (sentry.io) for crash reporting and error tracking in production builds only. This helps us identify and fix bugs to improve app stability.

**Information Sent to Sentry:**

- Crash logs and stack traces
- Device information (manufacturer, model, OS version)
- App version and build number
- Anonymized error context

**Information NOT Sent to Sentry:**

- Your receipt data
- Product photos
- Store names or product names
- Purchase amounts
- Any personally identifiable information

Sentry's data collection is limited to technical diagnostic information only. For more details, please review [Sentry's Privacy Policy](https://sentry.io/privacy/).

---

## 3. Data Security

### Local Storage Security

Your data is protected through:

- **Device-level security:** Your receipts are only accessible while the app is unlocked on your device
- **No cloud sync:** Data is never transmitted over the internet
- **App sandboxing:** Receipt photos and database are stored in the app's private directory, inaccessible to other apps

### Your Control Over Data

You have complete control over your data:

- **Delete receipts:** Remove individual receipts and their associated photos at any time
- **Clear all data:** Uninstalling the app will permanently delete all stored data from your device
- **No account required:** The app doesn't require registration or create an account, ensuring no data linkage to your identity

---

## 4. Permissions

### Camera Permission

**Why we request it:** To allow you to take photos of receipts directly within the app

**How we use it:** Photos are stored locally in the app's private directory and are never uploaded or shared

**Your control:** You can deny camera permission and still use the app by importing photos from your gallery

### Photo Library/Storage Permission

**Why we request it:** To allow you to select existing receipt photos from your device's gallery

**How we use it:** Selected photos are copied to the app's private directory for local storage only

**Your control:** You can deny this permission and still use the app by taking photos with the camera

### Notification Permission

**Why we request it:** To send you reminders before warranty expiration dates

**How we use it:** Notifications are scheduled locally on your device based on your reminder preferences

**Your control:** You can disable notifications in your device settings or within the app

---

## 5. Children's Privacy

Warranto is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe a child under 13 has provided information through the app (though unlikely given its purpose), please contact us immediately.

---

## 6. Data Sharing and Disclosure

We do **NOT**:

- Share your receipt data with third parties
- Sell your information
- Use your data for advertising
- Track your behavior
- Create user profiles

The only data shared with a third party is anonymized crash data sent to Sentry for diagnostic purposes, as described in Section 2.

---

## 7. International Users

Warranto is available worldwide and supports multiple languages (English, German, Spanish, French). All data is stored locally on your device regardless of your location. No data is transmitted internationally.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we make changes, we will:

- Update the "Last Updated" date at the top of this policy
- Notify users of significant changes through an in-app notification or update notes
- Continue to protect your data according to these principles

The latest version of this Privacy Policy will always be available at [INSERT YOUR HOSTED PRIVACY POLICY URL HERE].

---

## 9. Your Rights

Depending on your jurisdiction, you may have rights regarding your data, including:

- **Right to access:** You can view all your data directly within the app
- **Right to deletion:** You can delete individual receipts or all data by uninstalling the app
- **Right to portability:** While the app doesn't have an export feature in version 1.0.0, your data is stored in standard SQLite format
- **Right to object:** You can disable crash reporting by using debug builds instead of production builds (advanced users)

---

## 10. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or your data, please contact us:

**Email:** [INSERT YOUR CONTACT EMAIL HERE]

**Response Time:** We aim to respond to all privacy inquiries within 7 business days.

---

## Summary

**Your Privacy Matters:**

- ✅ All receipt data stays on your device
- ✅ No cloud sync or data transmission
- ✅ No user accounts or registration
- ✅ Complete control over your data
- ✅ Only anonymized crash data sent to Sentry
- ✅ No advertising or tracking
- ✅ Open source database format (SQLite)

---

## Hosting Instructions

### Before Play Store Submission

Google Play requires your privacy policy to be hosted at a **publicly accessible URL**. Here are your hosting options:

#### Option 1: GitHub Pages (Recommended - Free)

1. Create a new repository on GitHub (e.g., `warranto-privacy`)
2. Upload this `PRIVACY_POLICY.md` file
3. Enable GitHub Pages in repository settings
4. Your privacy policy will be available at: `https://yourusername.github.io/warranto-privacy/`
5. Use this URL in Google Play Console

#### Option 2: Personal Website

1. Convert this markdown to HTML
2. Upload to your personal website or domain
3. Ensure it's accessible at a permanent URL (e.g., `https://yourwebsite.com/warranto/privacy`)
4. Use this URL in Google Play Console

#### Option 3: Free Hosting Services

- **GitLab Pages:** Similar to GitHub Pages
- **Netlify:** Free tier with custom domain support
- **Vercel:** Free tier with automatic markdown rendering

#### Option 4: WordPress or Blog

1. Create a new page on your WordPress site
2. Copy the content of this privacy policy
3. Publish at a permanent URL
4. Use this URL in Google Play Console

### Important Notes

- **Do not use temporary hosting** like Pastebin or Google Docs - Google Play requires a stable, permanent URL
- **Keep it updated:** When you update the app's privacy practices, update the hosted policy too
- **Replace placeholders:** Before hosting, replace `[INSERT YOUR CONTACT EMAIL HERE]` and `[INSERT YOUR HOSTED PRIVACY POLICY URL HERE]` with actual values
- **Add to Play Store:** Once hosted, add the URL in Google Play Console → Store presence → Store settings → Privacy policy

---

**This privacy policy template is ready to use. Remember to:**

1. Replace `[INSERT YOUR CONTACT EMAIL HERE]` with your actual contact email
2. Host this policy at a public URL
3. Update `[INSERT YOUR HOSTED PRIVACY POLICY URL HERE]` with the actual hosted URL
4. Add the hosted URL to Google Play Console before submitting your app
