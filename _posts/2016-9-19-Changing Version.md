<html>
<head>
<title>ChangingVersion</title>
</head>
<body>
<p>Helloo there this only applies to jailbroken devices.</p>
<h1>-Tools Need-</h1>
#Jailbroken Device
#ifile/file explorer
<p>Now you need to got to these "dir" in ifile
(System/Library/CoreServices/SystemVersion)
When you click on SystemVersion you will see 
a code that looks like the below one.
All you need to do is edit the ProductVersion key strings
to any number you want just keep in mind that this might break or make your phone stuck in bootlogo</p>

<div align="center">
 <h1>Code</h1>
</div>

<p><?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>ProductBuildVersion</key>
	<string>13G34</string>
	<key>ProductCopyright</key>
	<string>1983-2016 Apple Inc.</string>
	<key>ProductName</key>
	<string>iPhone OS</string>
	<key>ProductVersion</key>
	<string>9.3.3</string>
</dict>
</plist></p>
</body>
</html>
