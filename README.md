
# Arduino OLED Menu
Simple menu using Arduino UNO, 128x64px SSD1306 OLED Display and u8g library.

**YOUTUBE VIDEO: https://youtu.be/HVHVkKt-ldc**

**YOUTUBE VIDEO u8g vs. u8g2: https://youtu.be/K5e0lFRvZ2E**

**WOKWI PROJECT: https://wokwi.com/projects/353105561979929601**

**WOKWI PROJECT u8g2: https://wokwi.com/projects/358725862609555457**

![THUMB_flipper_zero_arduino_oled_menu](https://user-images.githubusercontent.com/117754156/211013886-2e71dfe1-d69c-4260-87b8-94f2f2390a59.jpg)

Small Animation:

![arduino_oled_menu_animation_short](https://user-images.githubusercontent.com/117754156/211044356-90bd9574-dbc5-432d-ab39-daa108b57817.gif)


A simple menu using a 128x64 SSD1306 OLED Display connected using the IIC (I2C) interface to Arduino UNO together with three push buttons. The menu is inspired by the menu from Flipper Zero - https://docs.flipperzero.one/basics/control#M5BZO 

**Links from the video:**
- Flipper Zero menu - https://docs.flipperzero.one/basics/control#M5BZO
- WOKWI start project progress bar - https://wokwi.com/projects/300867986768527882
- image2cpp - https://javl.github.io/image2cpp/
- 128x64 SSD1306 OLED Display: https://s.click.aliexpress.com/e/_DCKdvnh
- Transparent OLED display: https://s.click.aliexpress.com/e/_Dns6eLz
- Arduino UNO: https://s.click.aliexpress.com/e/_AXDw1h
- Arduino UNO MINI: https://store.arduino.cc/products/uno-mini-le
- Big OLED Display: https://s.click.aliexpress.com/e/_ADL0T9
- Arduino breadboard prototyping shield: https://s.click.aliexpress.com/e/_ApbCwx
- u8g fonts (fonts available for u8g library): https://nodemcu-build.com/u8g-fonts.php
- u8g documentation: https://github.com/olikraus/u8glib/wiki/userreference
- Photopea (online Photoshop-like tool): https://www.photopea.com/
- image2cpp (convert images into C code): https://javl.github.io/image2cpp/
- Push buttons - https://s.click.aliexpress.com/e/_DmXS8B9
- LCD displays: https://s.click.aliexpress.com/e/_DBgR45P
- u8g2 documentation: https://github.com/olikraus/u8g2/wiki/u8gvsu8g2
- Image Magick: https://imagemagick.org/index.php
- LCD Image converter: https://lcd-image-converter.riuson.com/en/about/

**Related videos:**
- Arduino Parking Sensor - https://youtu.be/sEWw087KOj0
- Turbo pressure gauge with Arduino and OLED display - https://youtu.be/JXmw1xOlBdk
- Arduino Car Cluster with OLED Display - https://youtu.be/El5SJelwV_0
- Knob over OLED Display - https://youtu.be/SmbcNx7tbX8
- Arduino + OLED = 3D ? - https://youtu.be/kBAcaA7NAlA
- Arduino OLED Gauge - https://youtu.be/xI6dXTA02UQ
- Smaller & Faster Arduino - https://youtu.be/4GfPQoIRqW8



Few screenshots from the video:

![THUMB_flipper_zero_arduino_oled_menu_nolabels](https://user-images.githubusercontent.com/117754156/211014417-e82aa035-b2f0-4a4b-b714-6afa4b76a5c0.jpg)
![CAMTASIA_flipper_zero_oled_menu (Time 0_00_00;00)](https://user-images.githubusercontent.com/117754156/211014431-365214aa-fd2d-415e-b1a7-42c0531d36c2.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_00_18;02)](https://user-images.githubusercontent.com/117754156/211014461-b9f0f969-bd4d-4982-b2ad-dad3fd539f9a.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_00_51;23)](https://user-images.githubusercontent.com/117754156/211014477-58950704-ad14-4b65-a108-19dc7b484e64.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_01_24;00)](https://user-images.githubusercontent.com/117754156/211014486-8aa4c522-bdcd-4d31-b958-2842475da961.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_08_01;19)](https://user-images.githubusercontent.com/117754156/211014496-309ab00c-2731-4cc9-b0f4-ad1d8171ffa1.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_10_13;01)](https://user-images.githubusercontent.com/117754156/211014499-65439b47-7399-43cb-81e0-0d8d308ead3a.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_10_53;17)](https://user-images.githubusercontent.com/117754156/211014504-9a56d99f-df38-4ec7-952d-09889ecdbe54.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_11_05;09)](https://user-images.githubusercontent.com/117754156/211014515-def45646-680a-4169-832c-07cfc594db3e.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_11_29;22)](https://user-images.githubusercontent.com/117754156/211014530-28624ff4-afea-4c47-b113-934b604f7932.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_18_28;25)](https://user-images.githubusercontent.com/117754156/211014539-1cd3e06c-a5d7-4b96-a745-b23e155ff2e4.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_24_45;14)](https://user-images.githubusercontent.com/117754156/211014541-2d300562-2c49-47d1-a2d1-fb4c1d46944e.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_25_40;05)](https://user-images.githubusercontent.com/117754156/211014544-49f778af-5a19-4774-9d8c-9f28628b043a.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_27_17;11)](https://user-images.githubusercontent.com/117754156/211014555-bea2fcbe-5d4f-4f3c-9281-c0b370d91305.png)
![CAMTASIA_flipper_zero_oled_menu (Time 0_27_49;19)](https://user-images.githubusercontent.com/117754156/211014581-5e4b257e-9a0e-4340-8c54-e8129a1aae96.png)


![3dcube_screenshot](https://user-images.githubusercontent.com/117754156/211015869-4d426a91-f170-4635-993c-43c345ffedac.png)
![3dcube_xqr](https://user-images.githubusercontent.com/117754156/211015873-d7cbb04e-b1a4-494b-bded-4a90499bdf6b.png)


![battery_screenshot](https://user-images.githubusercontent.com/117754156/211015875-91aea248-67cc-40f0-b5f1-1b96eba09b1a.png)
![battery_xqr](https://user-images.githubusercontent.com/117754156/211015878-72858171-5fb7-48ca-973f-779e3d01213d.png)


![fireworks_screenshot](https://user-images.githubusercontent.com/117754156/211015881-7e362776-e03b-4097-ab8b-4046cdb93864.png)
![fireworks_xqr](https://user-images.githubusercontent.com/117754156/211015884-61ea6a65-d2ce-4873-a602-2661f45e5b24.png)


![gauges_screenshot](https://user-images.githubusercontent.com/117754156/211015886-1bb19eb4-8efd-4610-a6f4-4519bc34f057.png)
![gauges_xqr](https://user-images.githubusercontent.com/117754156/211015889-92084819-b09b-4c4e-9b97-59349a9b97e1.png)


![gps_speed_screenshot](https://user-images.githubusercontent.com/117754156/211015890-67c4695b-6f30-4520-9409-dc3f5e0a6a74.png)
![gps_speed_xqr](https://user-images.githubusercontent.com/117754156/211015891-9ccb5e2e-b32f-442f-b208-c0912bc447e5.png)


![knob_over_oled_screenshot](https://user-images.githubusercontent.com/117754156/211015892-1ce673c3-7198-4e13-a7a1-20152f22545f.png)
![knob_over_oled_xqr](https://user-images.githubusercontent.com/117754156/211015894-08258518-e148-4f5f-a9ca-a4b85b2c60b0.png)


![parksensor_screenshot](https://user-images.githubusercontent.com/117754156/211015895-07fddf32-b905-4c5d-b9cd-ede5d282abb1.png)
![parksensor_xqr](https://user-images.githubusercontent.com/117754156/211015896-13693a2b-6228-4127-a956-8f40b1701d11.png)


![turbo_screenshot](https://user-images.githubusercontent.com/117754156/211015897-2b304968-2b6a-47f0-8442-49d082e0a1e7.png)
![turbo_xqr](https://user-images.githubusercontent.com/117754156/211015898-079075e4-89bd-414e-aedb-b8f0481d140c.png)



Screenshots from the video using the u8g2 library:

![CAMTASIA_u8g_vs_u8g2 (Time 0_00_01;23)](https://user-images.githubusercontent.com/117754156/224031248-3d2d474c-a038-44ef-ad2b-a743a710e819.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_00_10;21)](https://user-images.githubusercontent.com/117754156/224031252-fd56c354-3740-4be0-8f59-a4a1d75e0430.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_00_12;21)](https://user-images.githubusercontent.com/117754156/224031262-058ac657-d461-4021-83fd-68d7da84d7ff.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_00_14;22)](https://user-images.githubusercontent.com/117754156/224031265-827aa29e-a77b-4ea6-8bc1-cdfe65431ae4.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_00_23;22)](https://user-images.githubusercontent.com/117754156/224031270-561b80eb-e5ae-4052-ae05-5b6b3d904b16.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_05_20;14)](https://user-images.githubusercontent.com/117754156/224031278-abfad8c4-27d0-4b58-a3f8-63f86a5da78f.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_05_48;03)](https://user-images.githubusercontent.com/117754156/224031284-dcc3c44f-ff88-43b3-947f-7e9d3b4f6d38.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_05_54;09)](https://user-images.githubusercontent.com/117754156/224031286-5f0a89a7-ac68-4f89-8117-244eb9e956d9.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_06_23;11)](https://user-images.githubusercontent.com/117754156/224031289-4565b37a-bbce-44df-bca6-ca96c05f3ccf.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_06_46;00)](https://user-images.githubusercontent.com/117754156/224031294-46132175-66ad-473e-a7d1-b49fe3d37822.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_07_43;12)](https://user-images.githubusercontent.com/117754156/224031298-9141e650-f411-4d1e-aa86-c60cb0ed4290.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_08_05;12)](https://user-images.githubusercontent.com/117754156/224031299-c7091d64-e303-4e98-8402-e06ac951f9b6.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_09_42;23)](https://user-images.githubusercontent.com/117754156/224031303-fdacea2c-ab01-4fe1-a51d-09306e3295f3.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_10_09;18)](https://user-images.githubusercontent.com/117754156/224031305-f684c23f-7b8e-4796-ae07-c2feec04166d.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_10_15;20)](https://user-images.githubusercontent.com/117754156/224031307-30bcef00-3ac3-4ab2-a5a1-611b5f9d97a8.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_10_20;25)](https://user-images.githubusercontent.com/117754156/224031311-182175bf-6b99-4ba0-94d5-b2978f0ed1f6.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_10_32;02)](https://user-images.githubusercontent.com/117754156/224031317-0a8deaac-b0f9-4762-93f5-be858b160bd7.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_10_55;26)](https://user-images.githubusercontent.com/117754156/224031319-19b20b4a-ef08-4148-8008-79aa65068371.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_11_15;20)](https://user-images.githubusercontent.com/117754156/224031320-d996468c-06b4-49f7-a746-4ee37c5e075c.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_14_51;16)](https://user-images.githubusercontent.com/117754156/224031325-0223e5d1-536f-4971-bea4-cddc3f4117ff.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_15_17;22)](https://user-images.githubusercontent.com/117754156/224031329-354b5f1a-5be2-4ae5-a824-7af513e41fd1.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_15_20;04)](https://user-images.githubusercontent.com/117754156/224031334-20068b67-11d1-4d98-846d-28a1653f03fe.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_15_26;15)](https://user-images.githubusercontent.com/117754156/224031339-4cda0ede-15f8-4108-bfdc-74e3dc556dbd.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_15_31;06)](https://user-images.githubusercontent.com/117754156/224031340-9e33b0a4-d511-4f68-8233-cefdedb7dcea.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_15_37;08)](https://user-images.githubusercontent.com/117754156/224031343-f74e0aef-bad6-4dbf-a6cb-be47564d0b00.jpg)
![CAMTASIA_u8g_vs_u8g2 (Time 0_15_42;13)](https://user-images.githubusercontent.com/117754156/224031347-b6eaa8ac-179a-48f7-a98a-8e9cc3294f70.jpg)

