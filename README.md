# Update feed files

`latest.json` is the public pointer that installed DatasetDoctor clients read.

For each release:

```powershell
.\Publish-Update.ps1 `
  -Version "1.8.8" `
  -InstallerPath "C:\path\to\DatasetDoctor-Setup-1.8.8-beta.exe" `
  -InstallerUrl "https://downloads.example.org/DatasetDoctor-Setup-1.8.8-beta.exe" `
  -Notes "DatasetDoctor 1.8.8 fixes ..." `
  -OutputPath ".\latest.json"
```

Upload the installer first. Replace the stable public `latest.json` only after the installer is accessible.
