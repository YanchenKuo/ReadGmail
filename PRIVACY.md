# Privacy Policy / 隱私權政策

[English](#english) | [繁體中文](#繁體中文)

_Last updated / 最後更新：2026-11-06_

---

## English

### 1. About this app

ReadGmail ("the App") is a personal automation tool developed and used only by its developer. It is not a public service. The only Google account it is intended to access is the developer's own account.

### 2. Data the App accesses

When the developer signs in with Google OAuth 2.0, the App requests read-only access to Gmail through the Gmail API. The App uses this access only to search the signed-in account's incoming emails for a specific verification code.

The App may access:

- Email content and metadata of the signed-in account, only as needed to locate the verification code.
- OAuth access and refresh tokens issued by Google, which are needed to keep the App signed in.

### 3. How the data is used

- Gmail data is used **only** to find the verification code that the developer's own automation needs.
- The data is not used for advertising, profiling, analytics, or any purpose unrelated to this function.
- No human reads the email content other than the account owner.

### 4. Sharing and transfer

The App does **not** sell, share, rent, or transfer Gmail data or Google user data to any third party. The App does not send Gmail data to any server operated by the developer.

### 5. Storage and security

- The App runs on the developer's own computer, and any data it handles is processed there.
- OAuth tokens are kept locally on the developer's own computer and are not published. They are excluded from the public source repository.
- The developer protects access to the computer and the tokens.

### 6. Retention and deletion

- Email content is not intentionally kept after the verification code has been extracted.
- The developer can delete locally stored tokens at any time.
- Access can be revoked at any time at <https://myaccount.google.com/permissions>. Revoking access immediately invalidates the App's tokens.

### 7. Google API Services User Data Policy

The App's use and transfer to any other app of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

### 8. Changes

This policy may be updated. The "Last updated" date above shows the latest version.

### 9. Contact

Please open an issue at <https://github.com/YanchenKuo/ReadGmail/issues>.

---

## 繁體中文

### 1. 關於本應用程式

ReadGmail（以下稱「本應用程式」）是僅由開發者本人開發並使用的個人自動化工具，不是公開服務。它預期存取的 Google 帳號，只有開發者本人的帳號。

### 2. 存取的資料

開發者透過 Google OAuth 2.0 登入時，本應用程式會透過 Gmail API 要求 Gmail 的唯讀權限。本應用程式只使用此權限，在已登入帳號收到的郵件中尋找特定的驗證碼。

本應用程式可能存取：

- 已登入帳號的郵件內容與中繼資料，僅限找出驗證碼所需的範圍。
- Google 核發的 OAuth access token 與 refresh token，用於維持登入狀態。

### 3. 資料的使用方式

- Gmail 資料**僅**用於找出開發者自己的自動化流程所需的驗證碼。
- 不會用於廣告、使用者剖析、分析，或任何與此功能無關的用途。
- 除了帳號擁有者本人，沒有任何人會閱讀郵件內容。

### 4. 分享與轉移

本應用程式**不會**販售、分享、出租或轉移 Gmail 資料或 Google 使用者資料給任何第三方，也不會將 Gmail 資料傳送到開發者營運的任何伺服器。

### 5. 儲存與安全

- 本應用程式在開發者自己的電腦上執行，處理的資料也在該電腦上處理。
- OAuth token 僅保存在開發者自己的電腦上，不會公開，並已從公開的原始碼 repository 中排除。
- 開發者會保護該電腦與 token 的存取安全。

### 6. 保留與刪除

- 驗證碼擷取完成後，不會刻意保留郵件內容。
- 開發者可隨時刪除本機儲存的 token。
- 可隨時至 <https://myaccount.google.com/permissions> 撤銷存取權限，撤銷後本應用程式的 token 立即失效。

### 7. Google API 服務使用者資料政策

本應用程式對從 Google API 取得之資訊的使用與轉移，皆遵守 [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy)，包括其中的 Limited Use（有限使用）規定。

### 8. 政策變更

本政策可能更新，上方「最後更新」日期即為最新版本日期。

### 9. 聯絡方式

請至 <https://github.com/YanchenKuo/ReadGmail/issues> 開立 issue。
