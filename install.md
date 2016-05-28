Work station:

* Install choco
https://chocolatey.org/install

```
@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin

```
## .NET
`choco install dotnet4.5.2 visualstudio2015community resharper -y`

## Cmd and dev utils
`choco install git far cmder nuget.commandline fiddler4 visualstudiocode linqpad windbg -y `

## Misc
`choco install slack skype googlechrome foxitreader paint.net -y`

## Needs registration

`choco install gitkraken -y`

 
