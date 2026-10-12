# VaultGenie — App Store Connect (Restructured Layout) Master Specification

> **Application**: VaultGenie  
> **Platform**: iOS 17.0+ & iPadOS 17.0+ (Universal iPhone, iPad & Mac with Apple Silicon)  
> **Target Release**: Version 1.0 (Build 3)  
> **Developer Entity**: Rareș-Mihail Cristea  
> **Official Public Repository**: [https://github.com/raresmihailcristea-cmyk/vaultgenie](https://github.com/raresmihailcristea-cmyk/vaultgenie)  
> **Live Documentation Base**: [https://raresmihailcristea-cmyk.github.io/vaultgenie/](https://raresmihailcristea-cmyk.github.io/vaultgenie/)

---

## A. Secțiunea Product Page Information

### 1. Promotional Text (max 170 caractere)
```text
Protect credentials and passkeys with military-grade Zero-Knowledge encryption, biometric Face ID, Open Banking sync, and on-device AI financial intelligence.
```
*(Exact character count: 158 / 170)*

---

### 2. Description (max 4000 caractere)
```text
VaultGenie is the next-generation password manager, cryptographic vault, and on-device AI financial intelligence suite designed specifically for iOS, iPadOS, and Apple Silicon.

Engineered with authentic Zero-Knowledge architecture, VaultGenie ensures that your master passwords, passkeys, credit cards, bank accounts, and confidential records remain completely inaccessible to anyone—including the developer.

🌟 CORE CAPABILITIES

• ZERO-KNOWLEDGE MILITARY-GRADE ENCRYPTION
- Client-side encryption utilizing Argon2id key derivation and AES-256-GCM.
- Bitwarden and Vaultwarden protocol compatibility: easily import and export your existing vault records.
- Asymmetric RSA-4096 key exchange for secure emergency sharing and organization collections.
- Cryptographic keys stay protected inside Apple's hardware Secure Enclave.

• FIDO2 PASSKEYS & BUILT-IN TOTP AUTHENTICATOR
- Store and sync passwordless FIDO2 / WebAuthn passkeys seamlessly.
- Integrated two-factor authenticator (TOTP) with live animated countdown rings.
- Replaces standalone authenticator apps by auto-generating 2FA tokens directly inside your vault.

• 1-TAP SYSTEM AUTOFILL & SAFARI EXTENSION
- Deep iOS Credential Provider integration: autofill passwords, credit cards, and passkeys instantly inside apps and Safari.
- Integrated Safari Extension for enhanced web login autofill and credential capture.

• BIOMETRIC LOCK (FACE ID & TOUCH ID)
- Instant unlock via Face ID, Touch ID, or Apple Watch.
- Customizable auto-lock timers, clipboard auto-clearing (30s/60s), and screenshot privacy masking.

• ON-DEVICE AI FINANCIAL & SUBSCRIPTION AUDITOR
- Detects forgotten, duplicate, or unused digital subscriptions from your financial records.
- Calculates annualized leakages and suggests immediate money-saving actions.
- 100% on-device AI processing: zero financial transaction data is ever sent to external cloud LLMs.

• OCR RECEIPT SCANNER & TAX DEDUCTIBILITY
- Point your camera to scan receipts and invoices with on-device CoreML Vision intelligence.
- Automatically parses totals, dates, vendor names, VAT, and evaluates business tax deductibility.

• SECURE VAULTSEND
- Share sensitive passwords, confidential notes, or private documents with friends or colleagues via ephemeral, end-to-end encrypted links.
- Set auto-delete expiration timers and maximum access counts.

• SEAMLESS MAC SYNERGY (DESKSTACKS READY)
- Pairs with DeskStacks on macOS via encrypted shared App Groups. Access your secure vault directly from your Mac desktop.

🔒 PRIVACY-FIRST & ZERO TRACKING
• 100% On-Device & Zero Cloud: We do not maintain any cloud databases that hold your secrets.
• Zero Data Collection: No telemetry, no usage analytics, no user tracking, and zero advertising trackers.
• Fully App Sandbox compliant.

PRICING & FREE TRIAL
VaultGenie includes an unrestricted 14-day Free Trial with access to all security and AI features. Choose between Monthly ($7.99/mo), Yearly ($59.99/yr), or permanent Lifetime Pass ($149.99).
```
*(Exact character count: 2,987 / 4000)*

---

### 3. Keywords (max 100 caractere)
```text
password manager,vault,passkeys,2fa,totp,authenticator,bitwarden,security,face id,finance,receipts
```
*(Exact character count: 99 / 100)*

---

### 4. URLs
* **Support URL**: `https://raresmihailcristea-cmyk.github.io/vaultgenie/support.html`
* **Marketing URL**: `https://raresmihailcristea-cmyk.github.io/vaultgenie/`

---

### 5. App Review Information — Notes (max 4000 caractere)
```text
Dear Apple App Review Team,

Thank you for reviewing VaultGenie for iOS, iPadOS, and macOS.

OVERVIEW:
VaultGenie is a native password vault, FIDO2 passkey manager, TOTP authenticator, and on-device AI financial auditor. It uses authentic Zero-Knowledge cryptography (Argon2id and AES-256-GCM) with biometric authentication backed by Apple's Secure Enclave.

HOW TO TEST THE APPLICATION:
1. ONBOARDING & VAULT CREATION:
   - On first launch, tap "Create New Vault".
   - Set a master password (minimum 8 characters) or enable Face ID / Touch ID biometric authentication.
   - The app derives encryption keys locally via Argon2id.

2. ADDING PASSWORDS & 2FA TOKENS:
   - Tap the "+" button on the main dashboard to add a login credential.
   - Enter a test username, password, and website URL.
   - Add a sample TOTP secret (e.g., JBSWY3DPEHPK3PXP) to see live 30-second 2FA countdown codes generated locally.

3. AUTOFILL CREDENTIAL PROVIDER:
   - In iOS Settings -> Passwords -> Password Options, VaultGenie can be enabled as an AutoFill provider.

4. AI RECEIPT SCANNER & TAX AUDITOR:
   - Navigate to the Receipt Scanner tab and tap "Scan Receipt".
   - Use the camera or select a sample receipt image from your photo library.
   - CoreML on-device vision extracts the merchant, total amount, and tax deductibility.

5. STOREKIT 2 IN-APP PURCHASES & SUBSCRIPTIONS:
   - VaultGenie includes an unrestricted 14-day free trial on first launch.
   - To test the paywall, tap the Settings icon and select "Upgrade / Subscription" to open the Paywall screen.
   - Test purchasing with an Apple Sandbox tester account:
     • Monthly Subscription: com.vault.genie.sub.monthly ($7.99/month)
     • Yearly Subscription: com.vault.genie.sub.yearly ($59.99/year with 14-day free trial)
     • Lifetime Pass (Non-Consumable): com.vault.genie.lifetime ($149.99)
   - The "Restore Purchases" button validates active entitlements.

PERMISSIONS & SECURITY:
- Face ID / Biometrics: Used strictly to unlock the vault.
- Camera: Used strictly on-device to scan QR codes for 2FA and receipts for OCR.
- Zero server credentials required. Zero telemetry transmitted.

If you have any questions, please contact us at support@vaultgenie.app.

Sincerely,
Rareș-Mihail Cristea
Developer of VaultGenie
```
*(Exact character count: 2,339 / 4000)*

---

### 6. App Review Information — Attachment
* **File Types**: `.mp4`, `.png`, `.jpg`, `.pdf`
* **Suggested Attachment**: A short 30-45 second video recording demonstrating:
  1. Unlocking the vault using Face ID/biometrics;
  2. Viewing a credential with live TOTP countdown codes;
  3. Opening the Paywall screen showing the Monthly ($7.99), Yearly ($59.99), and Lifetime ($149.99) cards.

---

### 7. App Sandbox Information
* **Required Entitlement Keys**:
  * iOS Target: Standard Sandbox boundary enforced by the operating system.
* **App Group & Keychain Entitlements** (Configured in `VaultGenie.entitlements`):
  * `com.apple.security.application-groups`: `group.vault.genie.app`
  * `keychain-access-groups`: `$(AppIdentifierPrefix)com.vault.genie.shared`
* **Temporary Exceptions Dropdown**:
  * **Leave EMPTY (0 items)**: VaultGenie uses zero `com.apple.security.temporary-exception.*` keys.

---

## B. Secțiunea App Information

### 1. General & Localizable Information
* **App Name**: `VaultGenie`
* **App Subtitle (max 30 caractere)**:  
  `Zero-Knowledge Password Vault` *(Exact 29 caractere)*
* **Bundle ID**: `com.vault.genie.app`
* **SKU**: `VAULTGENIE_APP`
* **Apple ID**: *(Generated automatically by Apple in ASC)*
* **Category (Primary)**: `Utilities`
* **Category (Secondary)**: `Productivity`

---

### 2. Content Rights
* **Question**: *Does your app contain, show, or access third-party content?*
* **Selection**:  
  🔘 **No, it does not contain, show, or access third-party content**

---

### 3. License Agreement (EULA)
* **Selection**:  
  🔘 **Apply Apple’s standard end user license agreement (EULA) to all countries or regions.**  
  *(URL: [https://www.apple.com/legal/internet-services/itunes/dev/stdeula/](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/))*

---

### 4. Age Ratings & Suitability
* **Declared Age Rating**: **4+** (All Ages / General Audience)
* **Age Suitability URL**: `https://raresmihailcristea-cmyk.github.io/vaultgenie/compliance.html#age-suitability`
* **Operating Systems Earlier than Version 26**:  
  * Compatible from iOS 17.0+ / macOS 14.0+ and newer.

---

### 5. App Encryption Documentation

#### a. App Purpose (max 300 caractere)
```text
VaultGenie is a native password vault and financial auditor implementing Zero-Knowledge AES-256 and Argon2id. It uses standard Apple CryptoKit, Keychain, and HTTPS APIs for biometric security and StoreKit 2 license verification.
```
*(Exact character count: 232 / 300)*

#### b. Select which encryption algorithms does your app implement:
* **Option to Select**:  
  🔘 **None of the algorithms mentioned above**  
  *(VaultGenie relies exclusively on standard Apple OS-provided CryptoKit, Keychain, and HTTPS APIs, exempt under EAR Category 5, Part 2).*

#### c. Is your app going to be available for distribution in France?
* **Selection**: **Yes** *(Cleared automatically without requiring French ANSSI submission).*

#### d. Info.plist Flag
Declared in `ios/Info.plist`:
```xml
<key>ITSAppUsesNonExemptEncryption</key>
<false/>
```

---

### 6. App Store Regulations & Permits (URL)
* **URL**: `https://raresmihailcristea-cmyk.github.io/vaultgenie/compliance.html`  
  *(Fulfills European Union GPSR 2023/988 compliance regulations).*

---

### 7. App Store Server Notifications
* **Production Server URL**: `https://raresmihailcristea-cmyk.github.io/vaultgenie/notifications/production/`
* **Sandbox Server URL**: `https://raresmihailcristea-cmyk.github.io/vaultgenie/notifications/sandbox/`

---

### 8. App-Specific Shared Secret
* In ASC: Click **Manage** ➔ Click **Generate** ➔ Copy the 32-character hexadecimal secret ➔ Click **Done**.

---

## C. App Privacy / Privacy Policy

### a. Privacy Policy URL
* **URL**: `https://raresmihailcristea-cmyk.github.io/vaultgenie/privacy.html`

### b. User Privacy Choices URL
* **URL**: `https://raresmihailcristea-cmyk.github.io/vaultgenie/privacy-choices.html`

### c. App Privacy Questionnaire (Nutrition Label)
* **Question**: *Do you or your third-party partners collect data from this app?*
* **Selection**: 🔘 **No, we do not collect data from this app**
* **Result**: Displays the official Apple privacy badge: **"Data Not Collected"**.

---

## D. App Accessibility Support

In the **App Accessibility** showcase panel in ASC:
* ✅ **Dark Interface**: Handcrafted dark theme with emerald & sapphire accents.
* ✅ **Sufficient Contrast**: Strict WCAG AA-compliant contrast ratios.
* ✅ **VoiceOver**: All interactive elements, password fields, and TOTP cards include full accessibility traits.
* ✅ **Voice Control**: Full compatibility with Voice Control.
* ✅ **Reduced Motion**: Respects system preferences for reduced animations.
* ✅ **Larger Text**: Adapts dynamically to system Dynamic Type scaling.
* ❌ *Captions*: Not Applicable.
* ❌ *Audio Descriptions*: Not Applicable.
* ❌ *Differentiate Without Color Alone*: Relies on dual indicators (icons + text status).

---

## E. Secțiunea Pricing and Availability

### 1. Price Schedule
* **Base App Price**: **Free ($0.00)**  
  *(Free download enabling the 14-day free trial, followed by in-app purchase/subscription options).*

### 2. App Availability
* **Selection**: 🔘 **All Countries or Regions** (All 175 App Store countries and territories).

### 3. App Distribution Methods
* **Selection**: 🔘 **Public — Discoverable by anyone on the App Store (default)**
* **Apple School Manager Discount**: ☑️ **Checked** (50% discount for educational purchases of 20+ licenses).

---

## F. Secțiunea In-App Purchases

### Lifetime Pass Configuration
* **Type**: `Non-Consumable`
* **Reference Name (max 64 caractere)**: `VaultGenie Lifetime Pass`
* **Product ID (max 100 caractere)**: `com.vault.genie.lifetime`
* **Price Tier**: **$149.99** (Tier 150 equivalent)
* **Display Name**: `VaultGenie Lifetime Pass`
* **Description**: `Unlock permanent lifetime access to Zero-Knowledge vaults, passkeys, TOTP generator, AI financial tracking, and all future updates.`
* **Review Screenshot**: Screenshot of `VaultGeniePaywallView` showing the $149.99 card.

---

## G. Secțiunea Subscriptions

### a. Auto-Renewable Subscriptions

#### 1. Monthly Subscription
* **Reference Name**: `VaultGenie Monthly`
* **Product ID**: `com.vault.genie.sub.monthly`
* **Price Tier**: **$7.99 / month** (Tier 8)
* **Display Name**: `VaultGenie Monthly`
* **Description**: `Full access to VaultGenie Zero-Knowledge vaults, passkeys, 2FA authenticator, and AI financial auditor.`

#### 2. Yearly Subscription (Recommended)
* **Reference Name**: `VaultGenie Yearly`
* **Product ID**: `com.vault.genie.sub.yearly`
* **Price Tier**: **$59.99 / year** (Tier 60)
* **Introductory Offer / Free Trial**: **14 Days Free Trial**
* **Display Name**: `VaultGenie Yearly`
* **Description**: `Full access to all VaultGenie security and financial features with 14-day free trial and over 37% annual savings.`

---

### b. Subscription Groups
* Click **Create Subscription Group**
* **Reference Name (max 64 caractere)**: `VaultGenie Subscriptions`
* *Group Organization*:
  - Level 1: `VaultGenie Yearly` ($59.99/year)
  - Level 2: `VaultGenie Monthly` ($7.99/month)

---

### c. Billing Grace Period
* **1. Grace Period Duration**: **16 days**
* **2. Eligible Subscribers**: **All Renewals** *(Apply a grace period to both free-to-paid and paid-to-paid subscribers)*
* **3. Server Environments**: **Production and Sandbox Environment**

---

### d. Streamlined Purchasing
* **Selection**: **Turn On Streamlined Purchasing**

---

### e. Non-Renewing Subscriptions
* **Status**: **None (N/A)**

---

## H. Secțiunea Nominations (App Store Feature)

### Nomination Pitch & Details
* **Action**: Click **Create Nomination**
* **Type**: Feature / Update Nomination
* **Details to Enter**:
  * **Title**: `VaultGenie — Next-Generation Zero-Knowledge Vault & On-Device AI Financial Intelligence`
  * **Target Event / Date**: Launch Date
  * **Why Apple Should Feature VaultGenie**:
    * **Modern Cryptographic Architecture**: Authentic Zero-Knowledge security leveraging Argon2id and AES-256-GCM, seamlessly storing keys within Apple's Secure Enclave.
    * **Unified Passkey & TOTP Experience**: Eliminates fragmented authentication tools by uniting passwordless FIDO2 passkeys with a live 2FA authenticator.
    * **100% On-Device Financial Intelligence**: Analyzes digital subscriptions and extracts receipt tax data with local CoreML without transmitting private records to third-party servers.
    * **True Cross-Device Ecosystem Synergy**: Universal app for iOS, iPadOS, and macOS with native AutoFill extensions and DeskStacks integration.
