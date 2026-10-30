---
layout: legal-document
title: Privacy Policy - Rua OC
lang: en
software: ruaoc
software_name: Rua OC
permalink: /ruaoc/en/privacy-policy/
---

# Privacy Policy - Rua OC

*Version: 1.0 · Updated and effective: October 30, 2026*

## 1. Introduction

This Privacy Policy explains how GuiFu Wu (吴贵福, pen name: Futu, “we,” “us,” or “our”) handles and protects information in connection with the macOS application Rua OC (布袋 OC, “the App”). Contact: [faurewu@icloud.com](mailto:faurewu@icloud.com).

Rua OC is a macOS app for organizing creative content and creating characters, with a 14-day free trial and a one-time purchase. No separate App account is required. Core creative features and image processing run on your Mac; iCloud sync is optional.

**Creative content is stored locally by default. When you enable iCloud sync, selected content and necessary linked items are transmitted to the current iCloud account’s private database. The App does not upload this content to a developer-operated server.** Purchases, purchase restoration, and update checks use Apple services; the App should not be understood as entirely offline or as never processing personal information.

This policy describes actual processing. Using the App is not treated as blanket consent to all optional processing.

## 2. Information Categories

The App handles the following categories. Some are processed only on your device; others are synced or sent only as you choose. Listing a category here does not mean we receive all of that information from your device.

- **Creative content and assets:** Text, images, and related material you provide, used to create, organize, and display your work. They remain local by default; enabling sync also places your selection and necessary linked content in iCloud.
- **Settings and interaction information:** App preferences and pointer or keyboard events, used to remember choices and respond to actions. Settings are stored locally. Interaction events serve immediate responses and are not saved or uploaded as activity logs.
- **Purchase information:** Purchase records and access status supplied by Apple, used to validate trials, purchases, and restoration.
- **Information needed for sync:** Necessary account, App, and content identifiers and sync state, used to separate accounts, synchronize changes, and retry operations. These are held locally and in necessary private iCloud records.
- **Diagnostics:** Limited error and crash records used for troubleshooting, kept locally and not uploaded automatically; see Section 7.
- **Feedback you provide:** Contact information, issue descriptions, and attachments you send, used to reply, address issues, and assist with rights requests.

Fictional creative content is not necessarily personal information, but text or photos you provide may relate to real people. Original image files are preserved, so embedded capture dates, device information, or location metadata may also be stored, synced, or exported. Remove unwanted metadata before importing.

The App does not require your real name, phone number, identity documents, Apple account password, or payment card number. Only enter or share other people’s information when you are authorized to do so.

## 3. Purposes and On-Device Processing

We process information only as needed to provide features you choose, maintain necessary operating state, verify access, respond to feedback, and comply with applicable law. Where optional processing relies on consent, you can withdraw it through feature controls, system permissions, or by contacting us; withdrawal does not invalidate earlier lawful processing. Processing necessary to perform a service or comply with legal obligations relies on the relevant legal basis. Where permitted by applicable law, necessary troubleshooting and service security may also rely on legitimate interests, taking your rights into account.

Image decoding, thumbnail creation, part cropping, and illustration depth estimation run on your device. Depth estimation uses a bundled Core ML model and does not send images to an external AI service. Character speech displays text you provide according to local rules; it does not read conversations in other apps or generate replies through cloud-based generative AI.

We do not sell personal information, use advertising tracking or third-party behavioral analytics, or use creative content to train AI models. Desktop characters may display your speech text above other windows. Consider hiding the character or disabling speech when sharing your screen or when others can see it.

## 4. Optional iCloud Sync

Sync is off by default. You can enable it during initial feature setup or in Settings → Data Management, and choose all content or a selection in Data Management. “All content” includes existing and future content. To preserve relationships, a selection may also include linked worlds, characters, archives, and images; automatically included items are shown in the selection interface.

Synced content includes relevant text, fields, original images, thumbnails, character assets, and necessary sync identifiers. CloudKit stores it in the App’s private database for the current system iCloud account, not a public database or an App feature that publishes it to other users. We do not operate an administration interface for remotely browsing this private creative content.

The App checks iCloud account availability and identifiers and responds to changes through system sync notifications and network recovery events. Apple services may also process network, device, and service information needed for connections, account security, and push delivery. We do not read your Apple account password. When a sync account change is detected, sync pauses; enabling it again uses the current account.

**Turning sync off or narrowing its scope stops subsequent corresponding sync activity but does not automatically delete existing local or cloud copies.** See Section 10 for deletion and other-device handling. Enabling sync does not authorize unrelated advertising, analytics, or public sharing.

Information about real people’s health, identity, finances, movements, or children may be sensitive personal information. Avoid entering or syncing it unnecessarily. Where needed, applicable necessity, authorization, and separate-consent requirements must be met. Sync serves the cross-device storage and recovery you choose; disclosure may affect privacy, personal safety, or financial interests. An App user cannot consent on someone else’s behalf beyond their authority.

## 5. Trials, Purchases, and Update Checks

Trials, one-time purchases, purchase restoration, and offer-code redemption use Apple StoreKit. The App verifies Apple’s transaction information on your device to calculate the trial period, establish access, and respond to refunds or revocations. Access may be checked at launch, when the App becomes active, and when transactions change. Restoring purchases requests Apple’s record synchronization and may require a connection and system account authentication; it does not charge you again.

Payment cards, billing details, account passwords, and offer codes are handled in the relevant Apple interfaces. The App does not read or save those inputs. Purchase records are not synced as creative content, included in creative export packages, or written into diagnostics. Your App Store purchase account may differ from your system iCloud account.

The App checks Apple’s `itunes.apple.com` service automatically or at your request for a released version. Requests contain the App’s store ID, storefront or system region code, and software category, not creative content or diagnostics. The receiving service obtains normal connection information such as an IP address. Results and check times are cached locally; update links open Apple’s store or website.

Apple’s account, payment, transaction, and service-security processing is governed by its [Privacy Policy](https://www.apple.com/legal/privacy/) and applicable service terms.

## 6. Files, Clipboard, and Device Permissions

- **Import and export:** In response to your file selection, drag-and-drop, or save action, the App reads images, assets, or data packages and writes to the destination you select. Importing an image does not mean requesting access to your entire system Photos library.
- **Clipboard:** Relevant text is read when you perform a paste action for editing; the App does not continuously scan the clipboard in the background.
- **Pointer interaction:** Pointer positions and events are processed locally for hovering, dragging, illustration parallax, and desktop character movements, not uploaded as a behavioral history.
- **Input Monitoring:** Desktop character keyboard following uses hardware key positions and modifier states to trigger gestures and briefly show keycap labels. It does not read input-method-composed text or save or upload keystroke logs. Keyboard following defaults to on and the in-app-only option defaults to off, but responding to keys in other apps still requires your explicit macOS Input Monitoring permission. Without that permission it responds only inside this App. It pauses when secure input is enabled, and monitoring stops when the character is hidden.
- **Launch at login:** This uses macOS login items and can be disabled in the App or system settings. Enabling it does not create an additional data upload.

You can disable keyboard following or restrict it to the App in Settings → Desktop Character. Revoke Input Monitoring in macOS System Settings → Privacy & Security → Input Monitoring. Refusing it does not prevent local creative work. File access is managed by macOS and your actions; not every kind of access has a separate system permission switch.

These features do not request contacts, precise location, camera, or microphone access. Export packages may contain selected App settings, but not purchase access, Input Monitoring authorization, sync enablement or account bindings, diagnostics, or the device’s App language preference.

## 7. Diagnostics and Feedback

The App keeps limited runtime error, exception-stack, and system-delivered crash information locally. Records exclude creative text, images, user document paths, passwords, complete raw crash reports, and original error descriptions. Normal validation and cancellations are not recorded as errors.

The cache is maintained for the latest 7 days with a maximum of 100 entries. Expired entries are filtered when records are written or read; this does not depend on a deletion task running after the App closes. Diagnostics are not automatically uploaded to us. You can save a file through Settings → About → Export Diagnostics and decide whether to send it. Exports include App and macOS versions. Logs handled by macOS under your system diagnostic settings are managed separately by the system.

If you email us, we receive your contact address, description, and attachments. General feedback emails are retained for no more than 6 months after the issue closes; original troubleshooting attachments are deleted within 30 days after closure. Unrelated or mistakenly supplied sensitive or children’s information is addressed promptly after discovery, normally deleted within 10 working days. You can request earlier deletion. If law or an unresolved dispute requires further retention, we retain only what is necessary and explain why.

Do not send identity documents, passwords, or unauthorized children’s information. If sensitive information is necessary, we will first explain the scope and purpose and obtain the consent required by law. The feedback inbox uses iCloud Mail; transmission and storage are subject to mail-service rules and may involve processing abroad.

## 8. Service Providers, Disclosure, and Storage Regions

Optional sync is provided by the service provider applicable to your current system iCloud account; purchases and updates use the relevant Apple services. We do not provide creative content to advertisers or data brokers. Export destinations, other cloud drives, email services, or recipients you choose handle files you give them under their own rules.

For iCloud operated by GCBD in China mainland, the provider is **AIPO Cloud (Guizhou) Technology Co. Ltd.** (云上艾珀（贵州）技术有限公司, Guizhou, China). Elsewhere, the applicable Apple entity may be Apple Inc. (US), Apple Canada Inc. (Canada), Apple Services LATAM LLC (US), Apple Services Pte. Ltd. (Singapore), iTunes K.K. (Japan), Apple Pty Limited (Australia), or Apple Distribution International Ltd. (Ireland). See the [iCloud Terms](https://www.apple.com/legal/internet-services/icloud/) for the regional mapping; the App does not read or verify your account’s service region.

These sync providers receive the content, images, and necessary identifiers described in Section 4 to provide storage, transmission, synchronization, and recovery. Content in iCloud operated by GCBD is stored in China, while limited Apple service information may be processed abroad. Data for other service regions may also be processed outside China mainland. A provider’s location does not identify every server location, and the App cannot identify or guarantee individual storage nodes. See [Apple’s explanation for customers in China](https://support.apple.com/zh-cn/121767).

You can contact [Apple Privacy](https://www.apple.com/legal/privacy/contact/), use [Apple Data and Privacy](https://privacy.apple.com/), or follow the contact channels in the [GCBD Privacy Policy](https://www.icloud.com.cn/gcbd-privacy-policy/) to identify the applicable provider and request assistance with data. You may also contact us. Each provider’s verification and handling scope follows its rules. Provider terms or enabling sync do not replace any cross-border notice, consent, or other obligations we must separately fulfill under applicable law.

Privacy and user-agreement pages are hosted on GitHub Pages and opened in your default browser. They do not embed advertising, analytics, third-party fonts, or scripts. GitHub and your browser may process IP addresses and access logs; opening a policy does not send your creative content. See the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Do not post private content or diagnostic attachments in the public repository.

## 9. Data Security

We use system storage and network services, CloudKit private databases, account-change checks, integrity validation, and diagnostic-field restrictions to reduce risk. Update queries use HTTPS. Apple’s security mechanisms govern its cloud-service transmission, storage, and account protection.

Local databases and export packages do not have a separate password-encryption feature provided by the App. Protection in transit does not mean an exported file is encrypted. Use trusted devices, macOS account protection, FileVault, appropriate backups, and iCloud security settings, and choose export destinations and recipients carefully.

Feedback is accessed only by people who need it to address the issue. If disclosure is legally required, we check the basis and limit the scope. No storage or transmission method guarantees absolute security. If an information-security incident requires notice under applicable law, we will take remedial action and fulfill notification duties.

## 10. Retention, Deletion, and Your Rights

Creative content remains available for your use until you delete it or clear the relevant local library. Settings and necessary sync state are retained for later launches and sync. Trial expiry does not automatically delete creative content; clearing diagnostics does not delete original images or creative work.

- **Access, correction, and export:** While creative features are available, view, edit, and delete individual items in their respective pages. Export all or selected data packages in Settings → Data Management. After trial expiry or without valid purchase access, Data & Privacy still provides free export, stopping sync, clearing diagnostics, and policy access. Assistance with data access and rights requests does not require purchasing the App.
- **Local deletion:** There is no single control to delete the entire library. Complete any confirmation or undo stage when deleting individual items. Contact us for help clearing a library without sending the entire library. Uninstalling alone does not guarantee deletion of local data or backups.
- **Stopping sync and cloud deletion:** Turning sync off does not clear the cloud. To remove all App cloud data, first disable sync on all relevant devices, then delete the App’s data through macOS System Settings → Apple Account → iCloud → Manage Storage. Menu names may vary by macOS version. Local copies, other devices, and backups must be managed separately; re-enabling sync may bring their content back.
- **Synced item deletion:** Deletion within the sync scope must successfully sync before it propagates. For recovery, unreferenced cloud files have a grace period of at least 24 hours before later maintenance reclaims them. Removing an item from the interface does not immediately erase every underlying copy; Apple’s service-retention rules also apply.
- **Diagnostics and separate copies:** Settings → General → Clear Cache, or Data & Privacy after expiry, clears current diagnostic records. New errors may produce new records. Manage exported files, email, other devices, and your own backups separately.
- **Purchase records:** Deleting content, clearing caches, or uninstalling does not cancel purchases or guarantee deletion of transactions Apple retains under applicable rules. Use Apple’s privacy and purchase-support channels for assistance.

Contact [faurewu@icloud.com](mailto:faurewu@icloud.com) to request access, correction, a copy, or deletion of feedback information we hold, withdraw applicable consent, or exercise rights such as restriction, objection, or portability where provided by law. We have no administration interface for remotely operating on your local or private iCloud content; we can provide practical assistance.

We will respond within 15 working days with an outcome or next steps, or sooner if required by law. Ordinary reasonable requests are free. We verify only information needed to handle the request. If immediate deletion or another request cannot be fulfilled, we explain the reasons and applicable basis. You may complain to the competent data-protection authority or seek a legal remedy.

<a id="children"></a>

## 11. Age and Children’s Information

Rua OC is a general-purpose creative tool, not specifically designed for children. Its App Store age rating describes content suitability; it does not replace consent, guardianship requirements, or external-service age rules. This policy does not impose a universal minimum age for using the App. Minors should use it with guardian guidance and obtain authorization where legally required.

**Specific rules for children under 14 in China mainland.** Children should read this policy with a parent or guardian, who should guide importing, exporting, permissions, and the decision to enable sync. The App does not ask for real ages, schools, identity documents, or guardian identities, and does not verify age or guardianship. Prefer fictional content and avoid unnecessary real children’s information.

Processing children’s personal information requires guardian consent and any separate consent required by applicable law. Such information is sensitive, and disclosure may affect children’s privacy and safety. Sections 2, 4, and 8 describe the scope, recipients, purposes, and locations; Sections 7 and 10 cover retention and deletion. Disabling sync does not affect local creation. Enabling the sync switch does not establish that guardian consent has been verified or authorize processing another child’s information.

We do not use children’s information for advertising, profiling, or AI training, or publish or sell it through the App. If we need to process children’s information through feedback, we will first obtain and verify the necessary guardian consent under applicable law. When unauthorized or unnecessary children’s information is discovered, we will stop the relevant processing and promptly delete it. Access is limited to people who need it to handle the issue.

Guardians can stop sync, export, and manage copies as described in Section 10, or email us to request access, correction, a copy, deletion, or withdrawal of consent concerning children’s information we have received. We verify only information necessary for the request and guardianship and respond within the Section 10 timeframe.

Local child-protection rules apply elsewhere. Where a relevant online service relies on consent, the age for a child’s own consent varies between 13 and 16 across EU Member States and is 13 in the UK; below the applicable threshold, guardian consent must be obtained and verified as required by law. See the [European Commission’s explanation](https://commission.europa.eu/law/law-topic/data-protection/information-individuals_en) and [UK legal explanation](https://www.legislation.gov.uk/ukpga/2018/12/notes/division/6/index.htm). These are not universal minimum ages for using an app. Apple accounts, iCloud, and purchases remain subject to their applicable age and family rules.

## 12. Changes to This Policy

We will update this policy to reflect actual features and processing, with a version and date. Material changes will be communicated through the App or other appropriate means as required by law. If a change to purposes, methods, or information categories requires fresh consent, we will obtain it separately; posting a webpage or continued use does not automatically replace that consent.

Simplified Chinese, English, Japanese, Korean, German, and French versions are provided and should remain consistent. We will clarify and correct translation differences without reducing your rights under applicable law.

## 13. Contact Us

- **Developer and personal information handler:** GuiFu Wu (吴贵福, pen name: Futu)
- **Privacy and children’s information contact:** GuiFu Wu
- **Email:** [faurewu@icloud.com](mailto:faurewu@icloud.com)
- **Related terms:** [User Agreement](https://faurewu.github.io/legal/ruaoc/en/user-agreement/)

---

*Rua OC Privacy Policy · Version 1.0*
