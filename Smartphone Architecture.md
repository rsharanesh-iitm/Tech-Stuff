## Brief on the Smartphone Architecture
Any basic smartphone comprises 5 basic components/segments in it:
- Hardware Architecture
- Communication Design
- User Application Execution
- Important peripheral devices
- Processors

Let's have a look at each of them indivually,

***Hardware Architecture***

Every modern smartphone today uses a System on a Chip (SoC) Architecture with the following 3 primary components:

- Application processor executing the user's application software with instructions from the middleware and the operating system (OS)
- A baseband (or modem) processor with its own OS components performing baseband radio transmission and reception of audio, video and data
- Various peripheral devices for the user interface

![Smartphone_Hardware_Arcitecture](https://www.evelta.com/product_images/uploaded_images/smartphone-hardware-architecture.png)

***Smartphone Communication Design***

_Receiver (RX)_

- The RX hardware (part of the baseband processor) receives incoming signals and generates interrupts for the radio interface in OS (both the radio interface and the OS software run on a baseband or modem processor)
- After the reception, a physical layer handshake takes place. Then the incoming audio, video and data are processed by the modem processor
- The radio OS components talk to the peripheral device drivers to give the incoming data to the user through the device (display, speaker etc.)

_Transmission (TX)_

- The device drivers write the data to be transmitted in the memory, from where the radio OS components collect them (For eg. audio from microphone, or image/video from camera, position from GPS)
- These data are then processed by the modem processor as per the transmission protocol
- Transmission initiated by the radio interface through transmitted hardware
- The Subscriber Identifier Module (SIM) plays an important role in reception and transmission

***User Application execution in a Smartphone***
The application processor executes the user applications and related OS programs
- Applications such as audio / video codec and players, games, image processing, speech processing, internet browser, text editor, etc
- Applications which are graphics intensive (the majority) are executed with help from the GPU
- Modern smartphone handsets have a large volatile memory (SDRAM) 1-2 GB and larger non-volatile storage, typically more than 10 GB
- Mostly a traditional OS (Linux) is used after being stripped down and optimized for smartphone

***Important Peripheral Devices in a Smartphone***
The peripherals are Input / Output (I/O) devices through which the end-user interacts with the handset. Of course, the OS needs driver software installed for each device. Typical peripheral devices are LCD, touchscreen, keyboard, camera, GPS, speaker, microphone, bluetooth, WiFi, HDTV

***Processors in Samrtphones***

The processors used in a smartphone are quite different from those used in a PC or laptop because they have different design constraints. The trick is to balance power consumption against performance. This is the primary design trade-off. Using an Intel Core i7 will drain the battery in a few minutes flat while using something like an 8-bit microprocessor will not pack enough power to run your browser and YouTube.

The market is ruled by Advances RISC Machines (ARM), a British fabless company which sells its smartphone processor designs to all major semiconductor manufacturers. ARM has won the game because its designs are optimized for battery life Vs performance and have a low area and transistor count. This is important to provide a small form factor and lower drain on the battery.

The Modem processor is a separate ARM processor or one extended by a DSP (the baseband encoding and decoding involves a lot of number crunching). Some architectures also use a modem accelerator along with the processor core.

![Basic-processor-ARM](https://www.evelta.com/product_images/uploaded_images/arm1136jf-s-chip-big.jpg)
The above depictedimage is a basic ARM mobile processor.
