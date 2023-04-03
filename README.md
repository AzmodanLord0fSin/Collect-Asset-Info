# Collect-Asset-Info
Collects asset information: Win-Key, BIOS, Network

.SYNOPSIS
    Sammelt Asset Informationen und schreibt sie in eine Textdatei

.DESCRIPTION
    Diese Script muss auf dem Zielsystem ausgeführt werden.
    Es schreibt eine Textdatei mit dem Hostname-AssetManagement-Info.txt nach C:\Temp\

    Wenn es wegen Berechtigungen zu einer Fehlermeldung kommt.
    Dann bitte folgendes in der Powershell ausführen:
    Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted
    
.NOTES 
    Author AzmodanLord0fSin 
    
.EXAMPLE
    .\fetch-asset-informations.ps1
