# PowerShell Attack Simulation

## Objective
Simulate suspicious PowerShell execution for threat hunting detection.

## Simulated Attack Command

```powershell
powershell.exe -Command "Get-Process"
```

## Detection Logic

The Sigma rule detects:
- powershell.exe execution
- usage of `-Command`
- suspicious PowerShell activity

## Expected Detection

Elastic Stack should identify:
- process creation
- suspicious command-line activity
- PowerShell execution event

## Result

Attack simulation workflow documented successfully.
