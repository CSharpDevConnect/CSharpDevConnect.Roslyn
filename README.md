####Why Roslyn is a Big Deal™

Tools discussed

- [Omnisharp](http://www.omnisharp.net/)
- [ScriptCS](http://scriptcs.net)
- [Alive](http://comealive.io) (Site unavailable until April 27)

Other Roslyn based tools
- [Code Connect](http://codeconnect.io)
- [C# Pad](http://csharppad.com/)
- [Duo Code](http://duoco.de/)
- [Oz Code] (http://o.oz-code.com/ozcode-v2-announcement)
- [Scrawl] (https://fluentco.de/)

####Omnisharp Installation for SublimeText 3

1. Install KVM (Mac/Linux users see: https://github.com/aspnet/home#os-x)
 - Open a command window (with Administrator privileges)
 - Run the following:
 - `@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://raw.githubusercontent.com/aspnet/Home/master/kvminstall.ps1'))"`
2. Install Kulture to SublimeText 
 - Press Ctr-Shift-P (Command-Shift-P on Mac)
 - Type "Kulture"
 - Select "Kulture" package
3. Install Omnisharp to SublimeText
 - Press Ctr-Shift-P
 - Type "Omnisharp"
 - Select "Omnisharp" package
 - Restart SublimeText
4. Open a C# Solution
 - Choose `File > Open Folder`
 - Choose the folder containing your `.sln` file.

####ScriptCS Installation Instructions (Windows)

1. Install the [Chocolatey]()  package manager.
 - Open a command window (with Administrator privileges)
 - Run the following:
 - `@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin`
2. Install the latest version of ScriptCS
 - Open a command window (with Administrator privileges)
 - Run the following:
 - `cinst scriptcs`
 - Restarted your command window
3. Use the REPL
 - Open a command window
 - Type the following:
 - `scriptcs`
 - Enter any C# statements. (eg. `var x = 5;`)
4. Create a C# script
 - Open a text editor
 - Write any C# statements
 - Save as `app.csx`
5. Run your C# script
 - Open a command window (in the same folder as your script)
 - Type the following:
 - `scriptcs app.csx`
