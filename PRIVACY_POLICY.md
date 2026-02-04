# Privacy Policy for Influencer Opportunity Finder

**Effective Date:** February 1, 2026  
**Last Updated:** February 1, 2026

## 1. Introduction

Welcome to Influencer Opportunity Finder ("we," "our," "us," or "the Extension"). We are committed to protecting your privacy and ensuring transparency about how we handle your data. This Privacy Policy explains what information we collect, how we use it, and your rights regarding your data.

By installing and using Influencer Opportunity Finder, you agree to the collection and use of information in accordance with this policy.

## 2. Information We Collect

### 2.1 Data Stored Locally on Your Device

The Extension stores the following data locally on your device using Chrome's storage API. This data never leaves your device except as specified in Section 2.2:

**Product Information:**
- Amazon Standard Identification Numbers (ASINs) extracted from your influencer storefront
- Product availability status (Available, Not Available, Unknown)
- Product images (cached for performance)
- Best Seller Rank (BSR) data when available
- Product category information
- Price information when available

**Opportunity Scores:**
- Calculated opportunity scores based on product metrics
- Score history and trends
- Product rankings and comparisons

**User Preferences:**
- Tier selection (Free, Pro, Unlimited)
- Feature preferences and settings
- UI customization preferences

**Usage Data:**
- Number of products checked per calendar month
- Timestamp of last extraction
- Feature usage statistics (for tier limit enforcement only)

### 2.2 Data Sent to Third Parties

The Extension sends minimal data to the following third-party services:

**A. Lemon Squeezy (Payment & License Validation)**
- **Purpose:** To validate software licenses and enforce tier limits
- **Data Sent:**
  - License key (if you purchased a paid plan)
  - Number of products checked this month
  - License tier (Free, Pro, or Unlimited)
  - Timestamp of validation request
- **Data NOT Sent:** Product ASINs, scores, or any personal browsing data
- **Privacy Policy:** https://www.lemonsqueezy.com/privacy
- **Legal Basis:** Contractual necessity for paid services

**B. Amazon.com**
- **Purpose:** To fetch product data and check availability
- **Data Sent:**
  - HTTPS requests to public Amazon product pages
  - Product ASIN numbers (to fetch product details)
  - Standard browser headers (User-Agent, etc.)
- **Data NOT Sent:** Your personal information, browsing history, or license data
- **Privacy Policy:** https://www.amazon.com/gp/help/customer/display.html?nodeId=468496
- **Legal Basis:** Legitimate interest in providing core functionality

**C. Amazon Affiliate Program**
- **Purpose:** To display information that is already visible to you within the Amazon Affiliate interface when you explicitly activate the Extension.
- **Data Sent:**
  - HTTPS requests to affiliate-program.amazon.com
  - Session cookies (if you're logged into Amazon Associates)
- **Data NOT Sent:** Your ASINs, scores, or extension data
- **Privacy Policy:** https://affiliate-program.amazon.com/help/operating/agreement
- **Legal Basis:** User consent when using this optional feature

### 2.3 Data We Do NOT Collect

We explicitly do NOT collect:
- Your name, email address, or contact information (unless you contact us for support)
- Your browsing history outside of Amazon influencer pages
- Your Amazon login credentials
- Your personal financial information
- Cookies for tracking purposes
- Analytics or behavioral data for advertising
- Any data from non-Amazon websites

## 3. How We Use Your Information

### 3.1 Core Functionality

We use your data to:
- **Extract Products:** Scan your Amazon influencer storefront and identify products
- **Check Availability:** Verify which products are currently available for purchase
- **Calculate Scores:** Compute opportunity scores based on product metrics
- **Display Results:** Show you which products have the highest earning potential
- **Export Data:** Generate CSV files with your results
- **Smart View:** Overlay scores on your storefront videos
- **Track Usage:** Enforce tier limits (50/500/unlimited products per month)

All analysis and data display actions are initiated manually by the user through explicit interaction with the Extension interface.

### 3.2 License Management

We use license data to:
- Validate your purchase through Lemon Squeezy
- Determine your tier level (Free, Pro, or Unlimited)
- Enforce monthly usage limits
- Provide appropriate features based on your plan

### 3.3 Product Improvement

We do not collect or transmit user data for analytics purposes. Any product improvements are informed solely by non-user-specific error events, extension version metrics, and voluntary user feedback provided through support communications.

## 4. Data Storage and Security

### 4.1 Local Storage

**All your product data is stored locally** on your device using Chrome's storage API (`chrome.storage.local`). This means:
- ✅ Your data stays on your computer
- ✅ We cannot access your data
- ✅ Your data is not uploaded to any server (except as described in Section 2.2)
- ✅ Uninstalling the Extension deletes all local data

### 4.2 Data Transmission Security

When data is transmitted to third parties:
- **HTTPS Encryption:** All data transmission uses HTTPS/TLS encryption
- **Minimal Data:** We send only the minimum data required for functionality
- **No Plaintext Secrets:** License keys are transmitted securely
- **Session Isolation:** Each user's data is kept separate

### 4.3 Data Retention

**Local Data:**
- Retained indefinitely on your device until you uninstall the Extension or clear Chrome's extension data
- Automatically cleared when Chrome's browsing data is cleared (if you select "Hosted app data")

**License Data:**
- Retained by Lemon Squeezy according to their privacy policy
- Used only for license validation and payment processing

**Amazon Data:**
- Product data fetched from Amazon is cached locally for 24 hours
- No data is sent back to Amazon beyond standard API requests

## 5. Your Data Rights

### 5.1 Access Rights

You may contact us with questions regarding your account or subscription data. Because Extension data is stored locally on your device, we generally do not retain personal data to provide upon request, except where required for billing or legal compliance.

You have the right to:
- **View Your Data:** All data is stored locally and can be viewed in Chrome's extension storage
- **Export Your Data:** Use the CSV export feature to download your data
- **Inspect Requests:** Use Chrome DevTools to see all network requests made by the Extension

### 5.2 Deletion Rights

You have the right to delete your data:
- **Uninstall Extension:** Removes all local data immediately
- **Clear Extension Storage:** Go to `chrome://extensions` → Extension Details → Clear Storage
- **Clear Browsing Data:** Chrome Settings → Privacy → Clear browsing data → Hosted app data

### 5.3 Rectification Rights

You have the right to correct inaccurate data:
- Re-run extraction to update product data
- Manually clear cached data and re-fetch

### 5.4 Portability Rights

You have the right to export your data:
- Use the CSV export feature to download all results
- Data is exported in standard CSV format for use in other tools

## 6. Children's Privacy

The Extension is **not intended for use by individuals under 18 years of age**. We do not knowingly collect information from minors. If we discover that a minor has provided us with personal information, we will delete it immediately.

Amazon's Influencer Program also requires users to be 18 or older.

## 7. International Data Transfers

**License Validation Data:**
- May be transferred to Lemon Squeezy's servers (located in the United States)
- Protected by HTTPS encryption
- Subject to Lemon Squeezy's privacy policy

**Amazon Data:**
- Requests are sent to amazon.com servers
- Subject to Amazon's privacy policy
- Standard e-commerce data handling

If you are located in the European Economic Area (EEA), UK, or Switzerland:
- Your data is protected under GDPR
- You have additional rights under GDPR (see Section 8)
- Data transfers comply with GDPR requirements

## 8. GDPR Compliance (European Users)

If you are located in the EEA, UK, or Switzerland, you have the following additional rights under GDPR:

### 8.1 Legal Basis for Processing

We process your data based on:
- **Legitimate Interest:** Providing core Extension functionality
- **Contractual Necessity:** Fulfilling our obligations for paid licenses
- **Consent:** For optional features (you can withdraw consent anytime)

### 8.2 GDPR Rights

You have the right to:
- **Right to Access:** Request a copy of data we hold about you
- **Right to Rectification:** Correct inaccurate data
- **Right to Erasure:** Request deletion of your data ("right to be forgotten")
- **Right to Restriction:** Request limitation of processing
- **Right to Data Portability:** Receive your data in a machine-readable format
- **Right to Object:** Object to processing based on legitimate interest
- **Right to Withdraw Consent:** Withdraw consent for optional features

### 8.3 Data Protection Officer

For GDPR inquiries, contact us at: guerrinoservices@gmail.com

### 8.4 Supervisory Authority

You have the right to lodge a complaint with your local data protection authority.

## 9. California Privacy Rights (CCPA)

If you are a California resident, you have the following rights under CCPA:

### 9.1 Right to Know

You have the right to request:
- Categories of personal information collected
- Specific pieces of personal information collected
- Purposes for collecting personal information
- Categories of third parties with whom we share data

### 9.2 Right to Delete

You have the right to request deletion of your personal information (subject to certain exceptions).

### 9.3 Right to Opt-Out

You have the right to opt out of the "sale" of personal information.

**Note:** We do NOT sell your personal information.

### 9.4 Non-Discrimination

We will not discriminate against you for exercising your CCPA rights.

### 9.5 CCPA Requests

To exercise your CCPA rights, contact us at: guerrinoservices@gmail.com

## 10. Cookies and Tracking

### 10.1 Our Use of Cookies

The Extension itself does **NOT** use cookies or tracking technologies.

### 10.2 Third-Party Cookies

When you use the Extension on amazon.com:
- Amazon may set cookies according to their privacy policy
- We do not control Amazon's cookies
- The Extension does not access or modify Amazon's cookies

## 11. Third-Party Links

The Extension may display links to:
- Amazon product pages
- Amazon affiliate program pages
- Lemon Squeezy payment pages

**We are not responsible for the privacy practices of these third-party websites.** Please review their privacy policies before providing any information.

## 12. Data Breach Notification

In the unlikely event of a data breach affecting your information:
- We will notify affected users within 72 hours
- We will notify relevant supervisory authorities as required by law
- We will provide information about the breach and remediation steps

**Note:** Because all your data is stored locally, a breach of our systems would not compromise your product data. Only license validation data could be affected.

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect:
- Changes in legal requirements
- Changes in our data practices
- New features or functionality

**How We Notify You:**
- Update "Last Updated" date at the top
- For significant changes: Display in-app notification
- Continued use of Extension after changes constitutes acceptance

**Your Options:**
- Review this policy periodically
- Uninstall the Extension if you disagree with changes

## 14. Contact Us

If you have questions about this Privacy Policy or our data practices:

**Email:** guerrinoservices@gmail.com  
**Support:** guerrinoservices@gmail.com  
**Website:** https://guerrinoservices.github.io/influencer-opportunity-finder

**For GDPR/CCPA requests, please use the privacy email address.**

**Response Time:** We aim to respond within 30 days.

## 15. Legal Disclaimer

This Privacy Policy is provided for informational purposes. It does not create any contractual or other legal rights in or on behalf of any party.

## 16. Consent

By installing and using Influencer Opportunity Finder, you acknowledge that you have read and understood this Privacy Policy and consent to the collection, use, and disclosure of your information as described herein.

---

**Document Version:** 1.0  
**Effective Date:** February 1, 2026  
**Last Updated:** February 1, 2026

© 2026 Influencer Opportunity Finder. All rights reserved.
