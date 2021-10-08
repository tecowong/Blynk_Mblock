# Blynk_Mblock
I would like to connect the uno broad with ESP8266 to blynk server. However, I can't do it.
I created an Mblock extension on my own. However, I found out that this 3 line from blynk must be placed before the library.
```
#define BLYNK_TEMPLATE_ID ""
#define BLYNK_DEVICE_NAME ""
#define BLYNK_AUTH_TOKEN "";

// Comment this out to disable prints and save space
#define BLYNK_PRINT Serial
```
I tried to change it in the extension of arduinoC code by following this
http://www.mblock.cc/doc/zh/developer-documentation/design-blocks-6-1.html
however, there is nothing change when I tried to upload the prgram. What can I do?
