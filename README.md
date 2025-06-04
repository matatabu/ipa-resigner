# MLBB iOS IPA Signer (for @matatabu)

This GitHub Actions workflow will re-sign your patched MLBB IPA for sideloading on iOS.

---

### 🚀 How to Use

1. Go to **Settings → Secrets and variables → Actions**
   - Add two secrets:

     | Name           | Value                      |
     |----------------|----------------------------|
     | `APPLE_ID`     | Your Apple ID email        |
     | `APPLE_PASSWORD` | App-specific password from https://appleid.apple.com |

2. Upload your IPA:
   - Click **"Add file" → "Upload files"**
   - Upload your `MLBB_unsigned.ipa` file

3. Go to the **Actions** tab
   - Click **"Run workflow"**

4. After 2–3 minutes:
   - Download your re-signed `MLBB_signed.ipa` from the **Artifacts** section

5. Install it using **Sideloadly**, **AltStore**, or **Apple Configurator 2**

---

✅ Done. You now have a re-signed IPA ready to install!
