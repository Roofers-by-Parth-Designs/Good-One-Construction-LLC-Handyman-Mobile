# Implementation Plan - Update Business Name to Good One Construction LLC

This plan outlines the changes needed to rename the business from "Good One Construction LLC / Handyman Mobile" to "Good One Construction LLC" across the workspace files.

## Checklist

- [x] Update businessName in business_info.json
- [x] Update title tag in index.html
- [x] Update navigation logo span in index.html
- [x] Update Hero heading in index.html to split 'Good One' and 'Construction LLC'
- [x] Update Review text quote in index.html
- [x] Update Footer business name in index.html
- [x] Verify there are no leftover instances of "Handyman Mobile" in business_info.json or index.html

## Proposed Changes

### Configuration

#### [MODIFY] [business_info.json](file:///Users/khandpv1/Desktop/.AntiGrav/Roofers/Good-One-Construction-LLC-Handyman-Mobile/business_info.json)
- Update `businessName` from `"Good One Construction LLC / Handyman Mobile"` to `"Good One Construction LLC"`.

### Web Site

#### [MODIFY] [index.html](file:///Users/khandpv1/Desktop/.AntiGrav/Roofers/Good-One-Construction-LLC-Handyman-Mobile/index.html)
- Line 6: Update `<title>Good One Construction LLC / Handyman Mobile | Professional Roofing</title>` to `<title>Good One Construction LLC | Professional Roofing</title>`.
- Line 502: Update `<span class="nav-logo">Good One Construction LLC / Handyman Mobile</span>` to `<span class="nav-logo">Good One Construction LLC</span>`.
- Lines 516-519:
  ```html
        Good One Construction LLC /<br>
        <em>Handyman Mobile</em>
  ```
  to:
  ```html
        Good One<br>
        <em>Construction LLC</em>
  ```
- Line 634:
  ```html
  <p class="review-text">"After the storm hit, I called four roofers. Good One Construction LLC / Handyman Mobile was the only one who walked me through the insurance process step by step. They handled everything. Couldn't have gotten through it without them."</p>
  ```
  to:
  ```html
  <p class="review-text">"After the storm hit, I called four roofers. Good One Construction LLC was the only one who walked me through the insurance process step by step. They handled everything. Couldn't have gotten through it without them."</p>
  ```
- Line 652:
  ```html
  <span class="footer-name">Good One Construction LLC / Handyman Mobile Roofing</span>
  ```
  to:
  ```html
  <span class="footer-name">Good One Construction LLC Roofing</span>
  ```

## Verification Plan

### Manual Verification
- Review changes in `index.html` to confirm correct tag closing and text structure.
- Run a case-insensitive search for "Handyman Mobile" in `index.html` and `business_info.json` to verify complete removal.
- Run a search for `[` or `]` to ensure no template placeholders are present.
