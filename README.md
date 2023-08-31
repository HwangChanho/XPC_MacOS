# XPC_MacOS
XPC_Test

path : /Library/LaunchAgents

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
    <key>KeepAlive</key>
    <false/>
    <key>Label</key>
    <string>(any process name you want)</string>
    <key>MachServices</key>
    <dict>
        <key>(your mach value)</key>
        <true/>
    </dict>
    <key>ProgramArguments</key>
    <array>
        <string>(your server binary file path)</string>
    </array>
    <key>RunAtLoad</key>
    <true/>
    <key>StandardErrorPath</key>
    <string>/dev/null</string>
    <key>StandardOutPath</key>
    <string>/dev/null</string>
</dict>
</plist>
