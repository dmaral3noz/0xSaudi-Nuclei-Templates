# 0xSaudi-Nuclei-Templates
Nuclei Templates for APK 

**How to use?**

 - Install apktool: 

> https://ibotpeaches.github.io/Apktool/install/

 - install nuclei: 
> go install -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei@latest

- install 0xSaudi-Templates
> git clone https://github.com/dmaral3noz/0xSaudi-Nuclei-Templates.git

--- 
Now Run this Commands: 

    apktool d file.apk
	echo FOLDER_APK | nuclei -t /0xSaudi-Templates/

example:
> echo test/  | nuclei -t 0xSaudi-Templates
![ScreenShot](https://github.com/dmaral3noz/0xSaudi-Nuclei-Templates/blob/00af0a1563a5f7153960f9788e676f144d86ec5a/img.png)
