
# Configuring an SD card with STM32F103C8 microprocessor

In this project, you can find all the necessary files to configure and program an STM32F103C8 to read/write from/to an SD card. 

 - First, make sure to install (I'm using Windows 10 by the way) [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html) which is a graphical tool that allows a very easy configuration of STM32 microcontrollers and microprocessors. To learn and understand STM32 microprocessors further, you can refer to some chapters of this great book: [Mastering STM32-Leanpub (2016) by Carmine Noviello](https://leanpub.com/mastering-stm32). Furthermore, you can see the input/output pins of the STM32 microcontroller that we are using: 
  
  ![alt text](https://raw.githubusercontent.com/amir-ghz/Configuring-SD-card-with-STM32-Microprocessor/main/help/stm32f103c8t6pinout.gif)

 - After everything is set up, we need a MicroSD Memory Card with an SD adapter like [this](https://www.memoryc.com/12287-2gb-transcend-microsd-memory-card-with-sd-adapter.html) that you might already find useless at home! You might also need a connector module, but mine is a homemade one! by soldering some pins like below. It doesn't look beautiful but does the job.

  ![alt text](https://raw.githubusercontent.com/amir-ghz/Configuring-SD-card-with-STM32-Microprocessor/main/help/SDcard.png) 

 - Next step is to connect the STM microprocessor to the programer like this:

  ![alt text](https://raw.githubusercontent.com/amir-ghz/Configuring-SD-card-with-STM32-Microprocessor/main/help/programmerTOmicro.jpg)

 - Now, it's time to connect the microprocessor to the SD card like below; in addition, the last image shows SD card pins in order to understand how to connect the wires correspondingly.  

  ![alt text](https://raw.githubusercontent.com/amir-ghz/Configuring-SD-card-with-STM32-Microprocessor/main/help/board.JPG)
  ![alt text](https://raw.githubusercontent.com/amir-ghz/Configuring-SD-card-with-STM32-Microprocessor/main/help/SDpins.png)

  So, everything is set. All that misery just to write a simple string "Amir was HERE!!!" into memory once the current flows into our STM32 chip! STM32 microprocessors are very efficient and can serve to be exploited in a variety of applications in the IoT world.  
## Authors

- [@katherinepeterson](https://www.st.com/en/development-tools/stm32cubemx.html)

