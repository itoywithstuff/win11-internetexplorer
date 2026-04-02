To bring back internet explorer in windows 11

1. Navigate to C:\Users\ %username% \AppData\Roaming\Microsoft\Windows\Start Menu\Programs\System Tools
2. Download and paste the .lnk in the location (alternatively, new > shortcut > C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -WindowStyle Hidden -Command "$iexplore=New-Object -ComObject 'InternetExplorer.Application';$iexplore.Visible=$true"
3. Press Win key, type Internet explorer, launch it (should show up to Win 11 25h1*) 


4. additionally certain windows 11 builds cannot run, if thats the case my downgrade app tool includes 3 ie versions.
