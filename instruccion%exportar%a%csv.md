Get-ChildItem -Path "C:\Ruta\Principal" -Directory -Recurse | Select-Object FullName
 | Export-Csv -Path "C:\estructura_carpetas.csv" -NoTypeInformation -Encoding UTF8