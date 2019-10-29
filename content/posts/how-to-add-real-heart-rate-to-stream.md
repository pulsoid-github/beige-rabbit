---
title: How To Add Real Heart Rate To Stream
date: 2019-10-25T13:01:06.948Z
thumb_img_path: /images/1_47bchcejgbsobedmp6qogg.png
content_img_path: /images/1_2bdwbopf5-gfmfjry81mhg.png
layout: post
---
Nowadays social video platforms become a very popular way to communicate with people and share your interests. There are millions of broadcasters who want to be unique and to attract more people to watch their LIVE videos. In our opinion, there are two great ways to do your stream better for viewers: create quality content and make your broadcast more interactive. Of course, if you want to become popular you need to develop in both ways. And to help streamers add some interactions to their LIVE videos we created Pulsoid.

![](/images/1_2bdwbopf5-gfmfjry81mhg.png)

[Pulsoid](http://pulsoid.net/?from=newblog) is a service, which allows you to add a heart rate widget to live video on Twitch, YouTube, Facebook Live, Mixer or any other video platform. Pulsoid is totally free and easy to use. You have an ability to change widget appearance so it will fit your stream better. Font, color, transparency and ECG animation can be changed in a Configuration section.

## What do I need to start using Pulsoid?

Our service works with Bluetooth LE heart rate monitors so you will need a phone with Bluetooth Low Energy support. (You can check it using additional mobile app: [iOS](https://itunes.apple.com/us/app/bluetooth-smart-scanner/id509978131?mt=8) or [Android](https://play.google.com/store/apps/details?id=com.magicalboy.btd&hl=en)).

Also, You will need a heart rate monitor with Bluetooth Low Energy to measure your heart rate.To receive uninterrupted and accurate pulse data heart rate monitor must be with a chest strap. Since there is a wide range of heart rate monitors, we can suggest two monitors, which we tried with our service.

\- [CooSpo H6](https://amzn.to/2Z07IBv) is one of the cheapest options(about 25$). This monitor works well, is stable enough and has satisfactory quality. Recommended for beginners! Other similar options: Wahoo TICKR

\- [Polar H10](https://amzn.to/2YYg78F) costs more(about 65-80$). This one is more stable, accurate and has excellent quality. A great choice if you are going to use it a lot!

\- Watches are NOT supported!

More recommendations you will find in that article.

To make things work you will also need an account on pulsoid.net(to configure a widget and get widget’s URL) and Pulsoid application(for [Android](https://play.google.com/store/apps/details?id=com.pulsoid.swung&hl=en) or [iOS](https://itunes.apple.com/us/app/pulsoid/id1194772720?mt=8)).

_NOTES:_

_If you experience a problem, when Pulsoid application can’t find your monitor, try to find the monitor with BLE scanner app( for_ [_Android_](https://play.google.com/store/apps/details?id=ble.blescanner&hl=en)_)._

_Be aware that low battery level of heart rate monitor can cause unstable connection and measurement errors._

_You do not have to pair the monitor before using the app_

_Electrocardiogram monitor might not work well when it and the skin is too dry, that is usually said in monitor instruction._

## Let’s start!

Create an account on pulsoid.net

![](/images/0_rpedjxy365mqhqbr.png)

2. Download the mobile application for [Android](https://play.google.com/store/apps/details?id=com.pulsoid.swung&hl=en) or [iOS](https://itunes.apple.com/us/app/pulsoid/id1194772720?mt=8) and log in.

![](/images/1_cfopc4ksvzw6yi3pfmuqcw.png)

3. Put your heart rate monitor on and choose it in the application

**NOTE**: Your Bluetooth must be turned on to find devices and measure heart rate, BUT you do not have to pair before using the app.

Follow “Pulsoid does not work? Troubleshooting” if you can’t see your monitor.

![](/images/1_xef8btzuhxrdlfatmras_w.png)

4. Open Configuration page on pulsoid.net

There are two parts: ‘My widgets’ and ‘Marketplace’. Configure any of widgets you have added by default or add more from Marketplace.

![](/images/1_jrvmkrszvo63akutby3ecg.png)

![](/images/1__cf0vvp_nbzpkilib0xa_w.png)

5.1 Click ‘Configure’ next to some widget and change available settings. Note, each widget has the unique name, so you can have two or more settings of the same widget(for different games or layouts).

![](/images/1_apjmslqlyou6subx4dmnbg.png)

5.2. Copy the first widget’s URL and paste into the Browser Source in streaming software such as OBS Studio, Streamlabs OBS, Bebo, XSplit, etc.

![](/images/1_b2sspg4kna40qrq71ywskq.png)

5.3. You can also use window capture option, use the Launch button to open the window with the widget

![](/images/1_rkoav1va7wylklzobfqylw.png)

**NOTE**: Background color should be used as chroma key for software that does not support browser source plugin, in a case of browser source plugin the background color is ignored and background becomes transparent.

6. The BPM widget has ranges(1&2) for colors and transparency settings based on data. You can also change the Font of your numbers(3), all [Google Fonts](https://fonts.google.com/) are supported. Do not forget to Save(4) your changes

![](/images/1_qd9yz88sttkx0isd-pj2-g.png)

7. You can also use the ECG animation, that has the color and thickness settings.

![](/images/1_g7coglb0hjd-dut-ftacaa.png)

8. Explore the Marketplace to find all widgets that are available (updating)

![](/images/1_b0_1ptcdklln-edgcmtwoa.gif)

9. Check your stream with heart rate if everything works well. Contact us if not. Follow “Pulsoid does not work? Troubleshooting” if you have any issues.

## **Future plans:**

Since we have more and more users we are trying to become better service and offer more features for streamers. There are some planned things:

\- More widgets depended on your heart rate.

\- Analytics for more platforms.

\- Your suggestions. If you have a great idea contact us!

## **DONE:**

\- Images widget with ranges as a part of BRO plan

\- Calories widget.

\- Export to CSV as a part of BRO plan

\- Text allignment.

\- Analytics for users (Twitch and YouTube). Find best clips based on heart rate.

\- Pusloid app in Streamlabs OBS. More

\- Sound widget for BRO plan

[BRO plan](https://pulsoid.net/pricing?from=blog) for more features❤️

Twitter: https://twitter.com/plsoid

Discord: https://goo.gl/TTBw58 

App for Android: https://goo.gl/z11qA7     

App for iOS: https://goo.gl/iwL7Tk     

Help: support@pulsoid.net
