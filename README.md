# Picora — Privacy Policy

**Last updated: November 12, 2026**

Picora ("we", "our", or "the App") is a photo collage maker developed for Android. This Privacy Policy explains what information the App accesses, how it is used, and the choices you have. By using Picora, you agree to the practices described below.

## 1. Information We Collect

**Your photos and collages never leave your device.** Picora collects only anonymous usage statistics via Google Analytics for Firebase (feature usage, screen views, crashes) — never photo content or personally identifiable data. See the full policy at https://winstonokk.github.io/Picora_Privacy/

### 1.1 Photos You Select

- The App requests read access to your device's photo library (`READ_MEDIA_IMAGES` / `READ_EXTERNAL_STORAGE`) so you can pick photos to include in a collage.
- Photos you choose are processed **entirely on your device**. They are never uploaded anywhere.
- We do not access, read, or use any photo you have not explicitly selected for a collage.

### 1.2 Photos We Create

- Collages you export are saved to your device's public Pictures directory (`Pictures/Picora`) via the system MediaStore so they appear in your gallery.
- Exported images remain on your device. We have no access to them.

### 1.3 Camera Photos

- If you use the in-app camera entry, the photo is taken through your device's default camera app and saved to local cache, then placed into your collage. It is never transmitted.

## 2. Permissions We Request

| Permission | Why |
|---|---|
| `READ_MEDIA_IMAGES` / `READ_EXTERNAL_STORAGE` | To display your photo library inside the in-app picker so you can choose photos |
| `INTERNET` | Reserved for future features (e.g., in-app update notices). The current version makes no network requests |
| `CAMERA` (optional) | To take a new photo directly from the picker, if you choose the Camera tab |

## 3. Third-Party Services

The App integrates **Google Analytics for Firebase** (Google LLC) for anonymous usage statistics: app-instance IDs, screen views, aggregated feature events, and crash reports. Photo/collage content is never collected. No advertising SDK is present. See details in the live policy page.

## 4. Children's Privacy

Picora does not knowingly collect any personal information from anyone, including children under 13. Since no data is collected at all, the App is compliant with children's privacy regulations (COPPA, GDPR-K).

## 5. Data Storage and Retention

- All data (selected photos, exported collages, preferences) lives **only on your device**.
- Uninstalling the App removes all App-specific preferences; photos you exported remain in your gallery unless you delete them yourself.

## 6. Your Rights and Choices

- **Photo access**: You can revoke photo permission at any time in Android Settings → Apps → Picora → Permissions. The App will show a permission guide and remain usable except for picking existing photos.
- **Deletion**: Delete exported collages from your gallery app at any time.
- **Contact**: If you have questions about this policy, open an issue at [https://github.com/Winstonokk/Picora_Privacy/issues](https://github.com/Winstonokk/Picora_Privacy/issues).

## 7. Changes to This Policy

We may update this Privacy Policy as the App evolves. The "Last updated" date at the top will reflect any changes. Material changes will be highlighted in the App's release notes on Google Play.

## 8. Contact

- Developer: Winstonokk
- Repository: [https://github.com/Winstonokk/Picora_Privacy](https://github.com/Winstonokk/Picora_Privacy)
- Issues: [https://github.com/Winstonokk/Picora_Privacy/issues](https://github.com/Winstonokk/Picora_Privacy/issues)
