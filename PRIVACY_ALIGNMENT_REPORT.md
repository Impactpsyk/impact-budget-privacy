# IMPACT BUDGET — BASE PRIVACY ALIGNMENT REPORT

**Date:** 2026-09-19  
**Privacy Repository:** C:\Users\scuba\Documents\Apps\impact-budget-privacy  
**Public URL:** https://impactpsyk.github.io/impact-budget-privacy/  
**Impact Budget App Repository:** C:\Users\scuba\Documents\Apps\Impact Budget

---

## A. Starting Repository Identity

**Repository:** impact-budget-privacy  
**Branch:** main  
**Starting HEAD:** `95979014c15198a4012076e5d12e989dd9b9f2e0`  
**Status:** Clean working tree ✅

---

## B. Files Changed

**Modified:** `index.html` (1 file)  
**Changes:** 11 insertions(+), 3 deletions(-)

**Section updated:** OCR and Auto Add → OCR and Receipt Scanning

---

## C. OCR Wording Result

### Before:
```
OCR and Auto Add

Impact Budget may use on-device optical character recognition (OCR) and Auto Add 
functionality to extract information from supported images or documents.

The app's OCR processing is designed to operate locally on the device rather than 
sending receipt or financial-document contents to an Impact Group OCR server.
```

### After:
```
OCR and Receipt Scanning

Impact Budget provides user-initiated, on-device optical character recognition (OCR) 
functionality that can process supported receipt or bank-slip images selected by the user.

OCR processing is designed to occur locally on the device rather than sending the 
contents of selected financial documents to an Impact Group OCR server.

Impact Budget's base release does not continuously scan the user's photo library or 
automatically monitor image folders for new receipts.

Additional automated transaction-import features may be introduced in a future version. 
If those features materially change how user information is accessed or processed, this 
Privacy Policy will be updated accordingly.
```

**Result:** ✅ ALIGNED

**Key improvements:**
- ✅ Changed heading from "OCR and Auto Add" to "OCR and Receipt Scanning"
- ✅ Clarified OCR is "user-initiated"
- ✅ Specified images are "selected by the user"
- ✅ Explicitly stated base release "does not continuously scan" photo library
- ✅ Explicitly stated no "automatically monitor image folders"
- ✅ Added forward-looking statement about future features
- ✅ Committed to policy update if future features materially change access

---

## D. Auto Add Wording Result

**Before:** Section title included "Auto Add" as active functionality  
**After:** Section title is now "OCR and Receipt Scanning" (manual functionality)

**Active Auto Add claims:** ❌ NONE (correctly removed)

**Verification:**
- ✅ No mention of automatic folder scanning
- ✅ No mention of background Auto Add
- ✅ No mention of continuous photo monitoring
- ✅ No mention of MediaStore enumeration
- ✅ No mention of Find My Folders

**Future features:** ✅ Appropriately disclosed as potential future additions

---

## E. SMS Wording Result

**SMS Auto Add mentions:** ❌ NONE (correctly absent)  
**READ_SMS disclosure:** ❌ NONE (correctly absent)  
**RECEIVE_SMS disclosure:** ❌ NONE (correctly absent)

**Status:** ✅ NO CHANGES NEEDED (SMS was never mentioned in policy)

---

## F. AdMob/UMP/Billing Preservation

### AdMob Disclosure: ✅ PRESERVED

**Section intact:** "Advertising"

**Disclosed information:**
- ✅ Free version displays Google AdMob ads
- ✅ Google Mobile Ads SDK may automatically collect:
  - IP address (approximate location)
  - App and user interactions
  - Diagnostic information
  - Device and advertising identifiers
- ✅ Google uses data for advertising, analytics, fraud prevention, security, compliance
- ✅ Impact Budget does not sell personal budgeting records
- ✅ Premium upgrade removes ads
- ✅ Reference to Google's privacy policies

### UMP Disclosure: ✅ PRESERVED

**Section intact:** "Advertising Consent and Privacy Choices"

**Disclosed information:**
- ✅ Uses Google User Messaging Platform (UMP)
- ✅ Manages advertising consent and privacy choices where required
- ✅ Google may display consent/privacy message before advertising
- ✅ Access to Google's privacy-options interface

### Google Play Billing Disclosure: ✅ PRESERVED

**Section intact:** "Google Play Billing"

**Disclosed information:**
- ✅ One-time purchase: "Impact Budget Premium"
- ✅ Permanently removes advertisements
- ✅ Processed by Google Play Billing
- ✅ Google Play handles payment information
- ✅ Impact Budget does not receive/store credit card or bank details
- ✅ Impact Budget receives purchase/ownership info to determine entitlement
- ✅ Does not persist Google Play tokens, order IDs, or account identifiers
- ✅ Google Play's privacy/payment policies apply

**Product model confirmed:**
- Free: Full app + ads
- Premium: Full app + ads removed (one-time purchase)
- Product ID: remove_ads_lifetime
- No subscription ✅

---

## G. LAN-Sync Disclosure Preservation

**Section intact:** "Local Network Sync" ✅

**Disclosed information:**
- ✅ Local-network synchronization transfers data between devices on same private network
- ✅ Impact Budget does not route through cloud server
- ✅ **May use unencrypted HTTP communication on private local network**
- ✅ Users should only use on networks/devices they trust

**Critical disclosure maintained:** Unencrypted HTTP on local network ✅

---

## H. Git Commit

**Commit hash:** `70fa004`  
**Commit message:** `docs(privacy): align policy with base release`  
**Files changed:** 1 (index.html)  
**Insertions:** +11  
**Deletions:** -3

**Commit content:**
- Updated OCR section heading
- Clarified manual/user-initiated functionality
- Added explicit statement about no automatic scanning
- Added forward-looking future features disclosure
- Preserved all other sections unchanged

---

## I. Push Result

**Push status:** ✅ SUCCESS  
**Remote:** `https://github.com/Impactpsyk/impact-budget-privacy.git`  
**Branch:** main  
**Pushed:** `9597901..70fa004`

**Note:** GitHub indicated repository moved to case-corrected URL (Impactpsyk), but push completed successfully.

---

## J. Live URL Verification

**URL:** https://impactpsyk.github.io/impact-budget-privacy/  
**Status:** ✅ LIVE AND UPDATED

**Verified on live site:**

### ✅ Manual OCR Described:
- "user-initiated, on-device optical character recognition (OCR)"
- "receipt or bank-slip images selected by the user"
- "OCR processing is designed to occur locally on the device"

### ✅ Active Auto Add NOT Claimed:
- Section renamed to "OCR and Receipt Scanning"
- No mention of active Auto Add
- No mention of automatic functionality

### ✅ No Broad Photo-Library Scanning Claimed:
- "Impact Budget's base release does not continuously scan the user's photo library"
- "does not automatically monitor image folders for new receipts"

### ✅ SMS Auto Add NOT Claimed:
- No SMS mentions anywhere in policy

### ✅ AdMob Retained:
- Full AdMob disclosure present in "Advertising" section
- SDK collection practices disclosed
- Purpose of use disclosed

### ✅ UMP Retained:
- Full UMP disclosure present in "Advertising Consent and Privacy Choices" section
- Consent management described
- Privacy options interface mentioned

### ✅ Billing Retained:
- Full Google Play Billing disclosure present
- One-time purchase model described
- Payment handling clarified
- No subscription model

### ✅ LAN-Sync Retained:
- Full local network synchronization disclosure present
- **Unencrypted HTTP on private network explicitly disclosed**
- User trust warning included

### ✅ Last Updated Date:
- "Last updated: September 19, 2026" ✅

### ✅ All Required Sections Present:
- Information You Enter ✅
- Local Data Storage ✅
- Local Network Sync ✅
- Location ✅
- Advertising ✅
- Advertising Consent and Privacy Choices ✅
- Google Play Billing ✅
- OCR and Receipt Scanning ✅
- Third-Party Services ✅
- Data Sharing ✅
- Data Security ✅
- Data Deletion ✅
- Children's Privacy (18+) ✅
- Contact ✅
- Changes to This Policy ✅

---

## K. Impact Budget Application Repository Modified?

**Repository:** C:\Users\scuba\Documents\Apps\Impact Budget  
**Git status:** Clean (no uncommitted changes)  
**Result:** ❌ **NO** (as required)

**Verification:**
- ✅ No files modified in application repository
- ✅ No source code changes
- ✅ No configuration changes
- ✅ Application untouched throughout privacy policy update

---

## L. Final Result

### ✅ **PASS — PRIVACY POLICY ALIGNED WITH BASE RELEASE**

**Summary:**

The live privacy policy at https://impactpsyk.github.io/impact-budget-privacy/ now accurately reflects Impact Budget's base release functionality:

1. **OCR functionality** is described as user-initiated and manual
2. **Auto Add** is not claimed as active functionality
3. **Photo library access** is clarified as user-selected images only
4. **No automatic scanning** is explicitly stated
5. **SMS Auto Add** is not mentioned (correctly)
6. **AdMob, UMP, and Billing** disclosures are fully preserved
7. **Local network sync** disclosure is preserved (including unencrypted HTTP)
8. **Future features** are appropriately disclosed as potential additions
9. **Last updated date** is correct (September 19, 2026)

**Alignment status:**

✅ Privacy policy matches base release product functionality  
✅ No false claims about Auto Add or automatic scanning  
✅ Manual OCR appropriately disclosed  
✅ Third-party service disclosures complete  
✅ Application repository untouched  
✅ Changes live and publicly accessible

---

**Report Date:** 2026-09-19  
**Author:** Claude Sonnet 4.5 (Cursor Agent)  
**Privacy Repository:** https://github.com/Impactpsyk/impact-budget-privacy  
**Live Policy:** https://impactpsyk.github.io/impact-budget-privacy/

---

**Status:** ✅ COMPLETE — Privacy policy successfully aligned with base release.
