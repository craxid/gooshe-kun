# akebi-gsc-vps
Google Shell VPS Lifetime


## How to get VPS from google Shell?

Login to Google Shell
[Google Shell](https://shell.cloud.google.com)

Typing
```sudo apt-get install -y git```

Then clone this repository 
```git clone https://github.com/craxid/akebi-gsc-vps```

Move to repo directory
```cd akebi-gsc-vps```

Then 
```chmod +x craxid.sh```

Now run
```./craxid.sh```

Login to Google Remote Desktop
[Google Remote Desktop](https://remotedesktop.google.com/headless)

Copy the text you got from google remote desktop to Google Shell Terminal 

Example: DISPLAY= /opt/google/chrome-remote-desktop/start-host --code="4/XXXXXXXX" --redirect-url="https://remotedesktop.google.com/_/oauthredirect" --name=$(hostname)

input 6 digit pin you want

Back to Chrome Remote Desktop
[Google Remote Desktop](https://remotedesktop.google.com/access)

login and enter the pin that you created earlier

