# eGCA ATCO Login Helper

Unofficial Android helper for ATCOs to log into DGCA eGCA and add Air Traffic Controllers e-Log Book entries from a CSV.

**This is not a DGCA / eGCA official app.** Use your own eGCA account. Review every row before you submit the logbook on the website.

© alkyl101

## Download

- Releases: https://github.com/alkyl101/egca-atco-helper/releases
- APK file: `eGCA-ATCO-Login-Helper-v4.11.0.apk` (attach it on the Releases page if it is not listed yet)

## Install

1. On the phone allow install from this source (Chrome / Files / GitHub).
2. Open the APK and Install.
3. Uninstall any older helper first if Android blocks the update.
4. Open **eGCA ATCO Helper**.

## Permissions

Allow when asked:

- SMS (read the eGCA OTP)
- Notifications
- Display over other apps (fill while the app is in the background)
- Unrestricted battery — Settings → Apps → eGCA ATCO Helper → Battery → Unrestricted

## Login

The helper stores username and password on the phone after you type them once.

To also keep them in **Android Password Manager**:

1. Settings → Google → Autofill → Autofill with Google → on. Or Settings → Passwords, passkeys and accounts → Google → Passwords.
2. Open the helper and tap the eGCA username field, then the password field. When Android shows **Save password**, tap Save. Site is `dgca.gov.in`.
3. To add by hand: Passwords → Add password → website `https://www.dgca.gov.in` → username and password → Save.
4. Next login, tap the Autofill chip or the key icon above the keyboard. Do not autofill captcha or OTP.

Then:

1. Type the captcha on the page and tap Login.
2. OTP window appears after username + password + captcha. First time: type the SMS or let the app read it. OTP is kept for 8 hours.
3. After login the page goes to desktop view and opens Home → Services → ATCO Licensing Division → Air Traffic Controllers e-Log Book.

## Fill logbook from CSV

1. After login, tap the small **CSV** chip.
2. **Import file** → pick your duty CSV (same columns as the Chrome extension “eGCA ATC Logbook Autofill”).
3. **Run fill**. The app adds each duty and does **not** click website Submit.
4. **Pause / Resume** holds or continues the list. To kill a background run, use **Stop** on the notification.
5. **Last added** shows the last duty the app recorded.

Overnight duties: if To time is `00:00` or past midnight, To date is From date + 1.
