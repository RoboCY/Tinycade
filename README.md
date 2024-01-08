# Introduction
Do you love 8-bit arcade games?

Do get excited when building electronics?

Do you enjoy soldering kits?

🤷 How about riding unicorns? 🤷

Well, if the answer is yes to any of them then Tinycade comes to the rescue 🚀 

![TinycadeHandson_P](https://user-images.githubusercontent.com/90136800/179738511-d3f68d56-4e3e-4ab1-9bc8-85a18d2713f8.png)

The Tinycade kit is designed to be a quite simple soldering kit, to serve as an introductory experience in the world of electronics while showcasing advanced possibilities that such simple hardware can handle!

It is based on the tiny, yet powerful, microcontroller Attiny85 which already comes pre-programmed with an open-source game from the maker community! Note that we do not sell the software on this kit, only the hardware😊.

As usual, you have the option to re-program your Tinycade via the programming interface on the back, using an ISP programmer. This way you can re-load other open-source games, use it as an educational gaming platform and make your own mini-game, or even hack it and find other cool usages around it 👾.

To make the kit even cooler and arcad-y, we prepared dedicated graphics for the PCB 😃   

![Tinycade_V0 3_Front_2D_1_P](https://user-images.githubusercontent.com/90136800/179738717-36f54a90-c16d-4f93-a736-e12e768658b7.png)
![Tinycade_V0 3_Back_2D_1_P](https://user-images.githubusercontent.com/90136800/179738757-9863f66d-fe09-404c-b703-194978c32dcd.png)

# Assembly instructions:

The Tinycade was designed to be quite simple and straightforward to build. The only tool that you will need from your side is just a soldering iron! You can use the following picture as an assembly reference:

![Tinycade_V0 3_Front_2_P](https://user-images.githubusercontent.com/90136800/179738860-217ec217-35d1-47de-a483-d932a49fd522.png)

All resistors have the same value by design, so there is no issue in mixing and matching them 😊. You will need to watch for the polarity of the buzzer, LED, and the Attiny85 MCU which is always marked on the board.

# Get it up and running:

Connect a CR2032 coin cell on the back, turn on the switch, and get ready to make a highscore! That's it, your cute mini 8-bit arcade machine is ready😀. You can upload a new game into your Tinycade, code your own or even hack it and use it any other way you think of 🦄

# Uploading a new game:
As we already mentioned, Tinycade runs on an ultra simple, yet beautifully powerful microcontroller named Attiny85. In order to connect the Attiny to a PC and reprogram it, an AVR (AVR is a family of microcontrollers developed since 1996 by Atmel, acquired by Microchip Technology in 2016) compatible ISP programmer has to be used. ISP stands for "In-System Programming" (ISP), or also called "In-circuit Serial Programming" (ICSP). If you do not have an ISP programmer lying around, USBtinyISP is a small cost efficient ISP programmer that can be used. The ISP interface of Tinycade can be found on the bottom:

![TinycadeISP_Interface _P](https://user-images.githubusercontent.com/90136800/179990085-54071509-4de1-40d1-8f7f-830c7c74227d.png)

Just be careful of the pinout and the polarity of the ISP programmer when connecting it with the Tinycade. After downloading the HEX file with the game of your choice from our GitHub page, you can use a HEX uploader program like XLoader (or AVRDUDE if you are familiar with) to write the new game in your Tinycade. That's it! Enjoy try making the best highscore 🕹️ 

# Shop link:
https://robo.com.cy/products/tinycade-8bit-arcade-machine

# Contributions and relevant information:
Games and sketches developed by [Ilya Titov ❤️](https://webboggles.com/)

Games and sketches developed by [Andy Jackson ❤️](https://github.com/andyhighnumber/Attiny-Arduino-Games)

Inspired by the original AttinyArcade by [Ilya Titov ❤️](https://github.com/webboggles/AttinyArcade)
