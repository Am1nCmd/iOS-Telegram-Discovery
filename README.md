# iOS Telegram Discovery
 
As part of this paper, aims to identify all artifacts generated from Telegram on iOS devices

![Image of Detail](https://raw.githubusercontent.com/Am1nCmd/iOS-Telegram-Discovery/master/Detail.PNG)

All Data can be [downloaded here]( https://github.com/Am1nCmd/iOS-Telegram-Discovery/releases/download/1.0/root.of.iPhone.zip)
- Bundle.zip
- Data.zip
- App Groups

All directories are as detailed as possible based on the directory on the iPhone
- Bundle : /var/containers/Bundle/Application/31A34478-958C-4A89-99CA-1AB32A1BFD25
- Data : /var/mobile/Containers/Data/Application/D07B0E94-0D93-4FB2-81DC-0F9C70677416
- App Groups : /var/mobile/Containers/Shared/AppGroup/03AF7D9A-08C0-45F4-AB3F-BE0B152DD363

Based on that Detail, there are 3 main part. So, we decide to make the structure as a telegram representation installed on iOS devices 
![Image of Structure](https://raw.githubusercontent.com/Am1nCmd/iOS-Telegram-Discovery/master/Structure.PNG)

We have found telegram chat IDs as well as media sent / received directories is available on 
/ (root of iPhone)/var/mobile/Containers/Shared/AppGroup/03AF7D9A-08C0-45F4-AB3F-BE0B152DD363/AppGroups/telegram-data/account-2885063770612599369/postbox/ <here>

But every chat data and media is encrypted.
