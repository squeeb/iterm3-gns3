#GNS3 to iTerm3 telnet console

* check this script out somewhere (`~/bin/iTerm3GNS.scpt` will do just fine)
* Open GNS3
* Select **GNS3** > **Preferences**
* Go to **General** > **Console applications**
* Under **Console settings** > **Console application command for Telnet:**, press **Edit**
* Select **Custom** and enter:
`osascript /Users/username/bin/iTerm3GNS.scpt %h %p`
* Click **Save** and enter any name, I used `iterm3`
* Press **OK**
* Fire up a device and hit **Console**