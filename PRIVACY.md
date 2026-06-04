Privacy Policy
Effective Date: June 1, 2026 (v1.0) | Last Updated: June 1, 2026
Data Controller: Alina Gorfina, Georgia / Tbilisi. Privacy requests: remode.support@gmail.com (response within 30 days as required by GDPR).
1. Overview Remode is built with a “Local-First” architecture. We believe that your productivity data should belong to you, and you alone. This policy explains how we handle your information (or rather, how we don’t).
2. Data Collection & Storage Remode operates entirely within your browser.
•	Extension Storage: All settings are stored via Chrome’s extension storage API (chrome.storage.local — distinct from the browser’s DOM window.localStorage). Storage keys include: isEnabled, isLocked, lockedSites, lockedUntil, redirectUrl, sitePassUntil, pausedUntil, siteBlockPolicies, budgetExtensionMs, dailyTimeBudgetMs, dailyUsageMs, onboardingCompleted, blockedSites.
•	Zero Server Transmission: We do not own, operate, or use any external servers to collect, store, or process your browsing history or personal data.
•	Brain Dump Privacy: Any text entered during the “Brain Dump” exercise is processed in volatile memory (RAM) only. It is never saved to local storage or any external database. Note: if the browser tab crashes or is closed unexpectedly, this data is irrecoverable.
•	Locked Mode Data: The keys lockedSites and lockedUntil store your Locked Mode configuration locally. This data never leaves your device. See §2 of the Terms of Service (“Exiting Locked Mode”) for context on how the lock works and what exit options are available.
3. Permissions Remode requests only the minimum Chrome extension permissions required to function, all scoped to your local browser:
•	declarativeNetRequest: To filter and block access to sites you’ve chosen to limit.
•	storage: To save your personal preferences using chrome.storage.local.
•	tabs: To provide the “Transition Protocol” interface when a limit is reached.
•	windows: To manage extension popups and the Transition Protocol overlay.
•	alarms: To schedule time-based events such as budget resets and lock expiry.
•	host_permissions (<all_urls>): Required to apply blocking rules across all domains you configure. A content script runs on all pages and reads window.location.hostname to match the current site against your block list. No page content, text, or user input is read or transmitted outside your device.
4. Third-Party Services The current MVP version of Remode does not use third-party analytics, tracking, or advertising scripts.
•	Cookies & Tracking: Remode does not use cookies, web beacons, pixels, or browser fingerprinting.
•	Subprocessors: None. No third party processes your data on our behalf.
•	Fonts: No external font CDN is used. All fonts are loaded locally via @font-face declarations bundled with the extension.
•	Support Email: If you contact us at remode.support@gmail.com, your message is handled by Google (Gmail) under Google’s Privacy Policy.
•	Chrome Web Store: Google independently collects install and usage statistics for extensions listed on the Chrome Web Store, governed by Google’s own Privacy Policy.
•	Future Third Parties: If a payment processor (such as Stripe or Paddle) is added when a subscription tier launches, this Privacy Policy will be updated before that change takes effect.
5. Your Rights Since all data is stored locally on your device, you have full control. You can delete all your data at any time by simply uninstalling the extension from your browser.
6. Children’s Privacy Remode is not directed at children under 13 (or under 16 in the European Economic Area). We do not knowingly collect any information from children below these ages. If you believe a minor has used Remode, please contact us at Report.support@gmail.com.
7. Data Retention Your settings are retained in chrome.storage.local until you uninstall the extension. The developer has no ability to access or delete data stored on your device.
8. Security chrome.storage.local data is stored on your device by Chrome and is not encrypted by Remode at the application level. The security of your data depends on your device security and Chrome profile configuration. We recommend using a device lock and a dedicated Chrome profile.
9. Legal Basis for Processing (GDPR Art. 6) Where GDPR applies, the legal basis for processing your configuration data locally is: (a) performance of a contract — storing settings is necessary for the extension to function as you requested; and (b) our legitimate interest in providing a reliable product. No personal data is transmitted to us.
10. CCPA Disclosure We do not sell or share personal information. Remode does not engage in the sale of personal data as defined under the California Consumer Privacy Act.
11. International Data Transfers No data leaves your device. Remode does not transmit your data to any server, and therefore no international data transfers occur.
12. Changes to This Policy This Privacy Policy may be updated from time to time. The current version is always available on the About page. By continuing to use Remode after an extension update, you accept the revised Policy.
13. Contact For privacy-related requests: Report.support@gmail.com. We will respond within 30 days as required by GDPR.

