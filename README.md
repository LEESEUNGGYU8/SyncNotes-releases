# SyncNotes Releases

[SyncNotes](https://syncnotes.local) 의 공개 릴리스 채널입니다.
모든 빌드 산출물(인스톨러 + `version.json`)은 [Releases](../../releases) 탭에서 받을 수 있습니다.

자동 업데이트가 이 저장소를 폴링하므로 **저장소를 비공개로 전환하면 업데이트가 동작하지 않습니다.**

## 무결성 검증

각 릴리스의 `version.json` 안에 인스톨러의 SHA-256 해시가 들어 있습니다. 다운받은
파일이 동일한 해시인지 확인하시려면 PowerShell에서:

```powershell
Get-FileHash -Algorithm SHA256 SyncNotes-Setup-1.0.0.exe
```