# Short setup guide

App: eGCA ATCO Login Helper v4.11.0  
Repo: https://github.com/alkyl101/egca-atco-helper  
© alkyl101

This is not a DGCA app.

## 1. Install

1. Download `eGCA-ATCO-Login-Helper-v4.11.0.apk` from Releases.
2. Allow install from that source.
3. Uninstall any older helper, then install and open **eGCA ATCO Helper**.

## 2. Permissions

SMS, Notifications, Display over other apps, and Battery → Unrestricted.

## 3. Login

Type username and password once. The helper stores them on the phone.

**Android Password Manager:** Settings → Google → Autofill → Autofill with Google → on. Tap the eGCA username and password boxes and tap Save when Android offers it. Or Passwords → Add password → website https://www.dgca.gov.in. Next time use the Autofill chip. Do not autofill captcha or OTP.

Type captcha → Login → OTP (SMS or type it; kept 8 hours) → desktop view opens ATCO e-Log Book.

## 4. CSV fill

CSV chip → Import file → Run fill. Pause/Resume holds the list. Notification Stop ends the background job. The app never taps website Submit.

If To time is 00:00 or past midnight, To date is From date + 1.
