+++
date = "2012-11-21"
title = "Fixing for missing iPhone in iTunes with Windows 8"
description = "A fix for missing iPhone 4S on windows version of iTunes"
tags = [ "windows", "itunes", "iphone" ]
categories = [
  "troubleshooting"
]
+++
{{% image class="left" src="/images/Fake_Windows_8_Start.png" width="300" alt="Windows 8 Desktop" %}}
After I installed Windows 8 on my laptop (I upgraded from Windows 7), the only annoyance I found was iTunes would not recognize my iPhone 4S anymore -- even when plugged in via USB. As you can imagine, this makes syncing the phone a little bit of a problem (Wifi was not working either).

I finally found a fix for it after doing a little 'digging' via Google.

The main fix (for me) can be found [here](http://support.apple.com/kb/TS1538).

{{% image class="right" src="/images/itunes_logo.jpg" width="150" alt="iTunes Logo" %}}

I ended up following section #5 in the link -- which is "Verify that the Apple Mobile Device USB Driver is installed". 
I found Apple iPhone under the Device manager's photo devices and updated the driver using the directions in the knowledge base article. 

Now: POOF! It works...Christmas came early.