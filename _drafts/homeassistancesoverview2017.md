---
date: 2019-01-29 22:14:21 +0000

---
  
**Home assistances overview 2017**

I found a funny article in Twitter [https://thebolditalic.com/you-are-now-fully-optimized-716f4](https://thebolditalic.com/you-are-now-fully-optimized-716f4 "https://thebolditalic.com/you-are-now-fully-optimized-716f4")[…](https://thebolditalic.com/you-are-now-fully-optimized-716f482b17f5?fbclid=IwAR0CUrLYt_9wErlJerN5Qa1dBSy_-qb_bpi6-a37t2VrXknfxNKsSEO9SnQ) about IOT, Software engineers life and automation. Btw, see @lyashenkogs. So I was interested how it’s going with home assistances now.

Time to time I use Google assistance on my Xiomi Mi Max to translate something to Russian, check the weather, convert currency, look at nearest events in a calendar, build a direction on a map or just google for some technical or not very term.   
The biggest cons - this doesn’t work from a locked screen on a smartphone, except you are Google Pixel owner ($649 for a basic version).

So for me, it will be good to have a home assistance like GA but on a MacBook.

**Why I don’t consider Google Home as an option.**  
No screen -> no visual output or possibility to open a wiki article for example  
1\. No keyboard in case if need to input a request manually  
2\. A highly proprietary system with no clean way to integrate with  
3\. There is no SDK for Google Home as a device.   
4\. When developing custom action you are locked with google infrastructure and firebase. [https://developers.google.com/actions/get-started/](https://developers.google.com/actions/get-started/ "https://developers.google.com/actions/get-started/")

**Amazon Echo**  
I didn’t use Echo but seems like it doesn’t work well with Google services out of the box. Developing Alexa skills involves AWS Lambda so I can get a vendor lock eventually. I’m sure there are workarounds, but I don’t see some very popular ones.  
A website when you can try Alexa online [https://echosim.io/](https://echosim.io/ "https://echosim.io/") didn’t work for mine. I wasn’t able even to trigger some basic functionality!

Siri  
Very limited. [https://9to5mac.com/](https://9to5mac.com/ "https://9to5mac.com/")[…/how-siri-works-in-ios-10-for-third-p…/](https://9to5mac.com/2016/06/14/how-siri-works-in-ios-10-for-third-party-apps-rich-integration-with-six-kinds-of-application/?fbclid=IwAR2owf457Q7QB3ZCZ0GHtl_Lpd8oQOfGbckP5DuVbWVc4NfqTS19kDqwZrQ)

  
**Ok Google on MacBook**  
Hopefully, I found a video with detailed instructions how to use OK Google from a MacBook using voice, and it worked for me. [https://www.youtube.com/watch?v=N7dYKFukPfo](https://www.youtube.com/watch?v=N7dYKFukPfo "https://www.youtube.com/watch?v=N7dYKFukPfo")

What it does and doesn’t   
It does everything except triggering actions like playing music, adding events to a calendar or reminders. In this case, you need GA which doesn't have an official desktop version. Only an API or an SDK[https://developers.google.com/assistant/sdk/overview](https://developers.google.com/assistant/sdk/overview "https://developers.google.com/assistant/sdk/overview") which will eventually look like a console app [https://www.youtube.com/watch?v=UINBWxs6SeI](https://www.youtube.com/watch?v=UINBWxs6SeI "https://www.youtube.com/watch?v=UINBWxs6SeI")

**MacAssistant**  
Technically, it's a Swift based wrapper, suspiciously similar to Siri, with very limited functions and bugs. Also, it requires macOS Sierra. I think the idea is great, but implementation has a lot of work to do yet.   
[https://github.com/vanshg/MacAssistant](https://github.com/vanshg/MacAssistant "https://github.com/vanshg/MacAssistant")

**Open source solutions**  
I didn’t test it yet. And it’s written in javascript. [https://www.youtube.com/watch?v=XEnu-aotG2s](https://www.youtube.com/watch?v=XEnu-aotG2s "https://www.youtube.com/watch?v=XEnu-aotG2s"). [https://github.com/TheAdrianProject/AdrianSmartAssistant](https://github.com/TheAdrianProject/AdrianSmartAssistant "https://github.com/TheAdrianProject/AdrianSmartAssistant")

Even Mark Zuckerberg build own home assistance. Yeh yeh, without any other engineers) and surprisingly there is no open source code) [https://www.youtube.com/watch?v=vvimBPJ3XGQ](https://www.youtube.com/watch?v=vvimBPJ3XGQ "https://www.youtube.com/watch?v=vvimBPJ3XGQ")

  
**Summary**  
I think there is no proper desktop home assistant for mere mortals yet. All market solutions seem beta versions and are very vendor specific. Personally, I will wait till something proper appeared at market and use GA as it is now from a smartphone and a MacBook.

p.s I will appreciate any kind of constructive critics about the article or yours ideas about home assistances in practice.