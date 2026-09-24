# Isadmin

NRMA Information Services VB6 IsAdmin demo (`wTokenInfo.exe`) by Elvio Serrao. `IsAdmin()` opens the thread or process token, reads `TokenGroups` via `GetTokenInformation`, and tests for the local Administrators SID with `EqualSid`. UI caption "IsAdmin" with an "Are You Admin?" button that MsgBoxes admin vs not.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`WTOKENINFO.VBP`) | VB6 | WinForms exe | IsAdmin token-group Administrators check |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `WTOKENINFO.VBP`

## Requirements

- Visual Basic 6.0 IDE
- Advapi32 / Kernel32 token APIs (`OpenProcessToken`, `GetTokenInformation`, `EqualSid`)

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Isadmin`.
Company names in project files: NRMA - Information Services Pty. Limited. Module by Elvio Serrao (`Elvio.Serrao@nrma.com.au`).

## License

MIT (c) 2026 VaderConsulting for my working copy where applicable. See `LICENSE`. Third-party sample portions remain under their original terms.
