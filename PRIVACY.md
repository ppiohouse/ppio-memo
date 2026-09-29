# PPIO MEMO 개인정보처리방침 / Privacy Policy

시행일 / Effective date: 2026-09-29

## 한국어

PPIO MEMO는 메모 동기화를 위해 사용자가 선택적으로 연결한 Google 계정의 다음 정보와 권한을 사용합니다.

- Google 계정 이메일 주소: 앱 설정 화면에 연결된 계정을 표시하는 용도
- Google Drive 앱 데이터 권한(`drive.appdata`): PPIO MEMO가 만든 메모 동기화 파일을 사용자의 앱 전용 숨김 공간에서 읽고 쓰는 용도

로그인 과정에서 `openid` 권한을 요청하지만, 앱은 OpenID 식별자(`sub`)를 별도로 저장하거나 이용하지 않습니다. PPIO MEMO는 사용자의 일반 Google Drive 파일이나 다른 앱의 데이터에는 접근하지 않습니다.

메모 내용은 사용자의 기기와 Google Drive 앱 전용 공간 사이에서 직접 동기화되며 PPIO.HOUSE 서버로 전송되지 않습니다. 광고, 분석, 사용자 추적을 위해 Google 사용자 데이터를 사용하거나 제3자에게 판매·공유하지 않습니다. PPIO MEMO의 Google API 정보 이용 및 전송은 제한적 사용 요건을 포함한 [Google API 서비스 사용자 데이터 정책](https://developers.google.com/terms/api-services-user-data-policy)을 준수합니다.

OAuth 로그인 토큰은 Windows가 제공하는 암호화 저장소를 통해 로컬 기기에 보관합니다. 앱에서 Google 연결을 해제하면 로컬 토큰을 삭제하고 Google에 권한 취소를 요청합니다. 연결 해제나 앱 삭제가 Google Drive에 이미 저장된 메모 동기화 파일을 자동 삭제하지는 않습니다.

개인정보 관련 문의: ppio.house@gmail.com

## English

PPIO MEMO uses the following Google account data and permission only when a user chooses to connect Google sync:

- Google account email address: to show which account is connected in the app settings
- Google Drive app-data permission (`drive.appdata`): to read and write the memo sync file created by PPIO MEMO in the user's hidden, app-specific storage

The app requests the `openid` scope during sign-in but does not separately store or use the OpenID identifier (`sub`). PPIO MEMO cannot access the user's regular Google Drive files or data belonging to other apps.

Memo content synchronizes directly between the user's devices and the user's Google Drive app-data space. It is not sent to a PPIO.HOUSE server. Google user data is not used for advertising, analytics, or tracking, and is not sold or shared with third parties. PPIO MEMO's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

OAuth tokens are stored locally using encrypted storage provided by Windows. Disconnecting Google in the app removes the local token and requests revocation from Google. Disconnecting or uninstalling the app does not automatically delete memo sync data already stored in Google Drive.

Privacy contact: ppio.house@gmail.com
