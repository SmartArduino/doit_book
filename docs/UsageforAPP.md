# Usage for APP: DoHome and HomeKit 

* We will introduce the usage of APP for DoHome and HomeKit, respectively;
* We will discuss the difference of DoHome and HomeKit;
  * DoHome is developed by Shezhen DOIT LTD., while HomeKit is developed by APP inc.;
  * DoHome can be used for Android and Iphone, while HomKit is only for Iphone;
  * By using DoHome APP, one can many voice speakers, like google assistant, Alexa, Tmall, Xiaomi, and Baidu; while using HomeKit, just     use siri. 

## DoHome APP

**Usage for DoHome APP**

**Step 1**: Please power on the plug and check that the indicator light is blinking slowly (1 time every second). Long press the button of smart plug for 5s and observe that the indicator light blinks quickly (10 times every second).

 Step 2: Use your phone to scan the following QR code and download DoHome APP.

![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image002.jpg)![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image003.png)

 **Step 3:** Open DoHome APP, register an account using your name and password, and then login the DoHome APP.

 

![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image005.jpg)

 

 

 

 

 

**Step 4:** Click the “+” in the upper right corner to add the device according to the hint.

Note: If you still have a doubt, please click the menu in the upper right corner to look for help.

 

![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image007.jpg)![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image009.jpg)![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image011.jpg)

 

**Step 5:** If you want to use the smart speaker, e.g., Alexa, google assistant, Tmall or Xiaomi, please click the “≡” in the upper right corner to look for the corresponding instructions.

**Frequent Problems**

Q1: How do Homekit users use timer, remote control and smart audio devices such as Alexa, Google Assistant, Tmall genie or XiaoMi audio. 

A1. Scan the QR code in the following and download DoHome APP.

![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image012.jpg)![IMG_256](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image014.jpg)

A2. Register and login your account information of DoHome. Pull down and refresh the interface to look for your smart device.

Note: The phone and the smart plug must be connected in <font color=red>the same 2.4G WiFi network</font>.

 

![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image007.jpg)![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image011.jpg)![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image015.jpg)

A3. Please open the menu in the upper left corner, click “Manager” and find your device. And then, choose it and click “Bind device”. 

Note: 

(1). You must login the 3rd platform to login your DoHome account before using it.

(2). If you want to use the smart audio, please click the corresponding icon to get the user manual. If you need help, please click the option of help; 

![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image016.jpg)![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image011.jpg)![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image018.jpg)![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image020.jpg)![img](file:///C:\Users\Administrator\AppData\Local\Temp\msohtmlclip1\01\clip_image022.jpg)

 

Q4: How to reset the socket to the factory mode?

A: Long press the button of the smart plug (5s) and the indicator light will blink slowly.



## Configuration  
Default values:  
```yaml
---
html:
  embed_local_images: false
  embed_svg: true
  offline: false
  toc: undefined

print_background: false
---
```

If `embed_local_images` is set to `true`, then all local images will be embedded as `base64` format.  

If `toc` is set to `false`, then the sidebar TOC will be disabled. If `toc` is set to `true`, then the sidebar TOC will be enabled and displayed. If `toc` is not specified, then the sidebar TOC will be enabled, but not displayed.

## Export on save  
Add the front-matter like below:  
```yaml
---
export_on_save:
  html: true
---
```
So the html file will be generated every time you save your markdown file.  
