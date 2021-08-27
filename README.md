# BUILD_LORAWAN_END_NODE_using_B-L072Z-LRWAN_STM32_BOARD

<b>🔥🔥🔥 GOAL of the project</b>

BUILD LORAWAN END NODE using B-L072Z-LRWAN STM32 BOARD and Transmit data to the TTN (The Things Network)


<b>📚 Description</b>

A lorawan end node have created by setting the keys of the device in TTN server platform. Configuring the device with the parameters, upload codes to device and finally activate it in the TTN to transfer the packets (Voltage and the temperature of the MCU in the board) and be visible in the TTN online platform.

First, choose and install the best tool (tool-chain) to configure and upload the codes(FLASH) the device. Cube-IDE includes Cube-MX and Cube-programmer tools and could be the best between: 
    • IAR EWARM
    • KAIL
    • gcc-based IDE
    • Arm-mbed online platform
    
Secondly, download the Lorawan_end_node example and import it to the Cube-IDE tool.

Thirdly, flash (upload the lorawan application) to the device. 

Fourthly, choose and install a terminal tool for tracking the packets

Finally, creating an account and other entitis in TTN (e.g. add  Gateway, application and a device)


<b>👉 Hardware equipment</b>

- B-L072Z-LRWAN_STM32_BOARD

- Type-C USB cable (connect board to the PC)

<b>👉 Software equipment</b>

- Cube-IDE software

- Cutecome terminal application (or any terminal application)

    
<b>🎬 Related video</b>

https://drive.google.com/drive/folders/193a0y-XQt243AbnOHGVEFdcdlx3MfqSE?usp=sharing


<b>👋 Additional resources</b>

Frequency setting according to your zone to set in the lora device and TTN (Frequency plan):
https://www.thethingsindustries.com/docs/reference/frequency-plans/

Links for downloading STM-cube-IDE:
https://www.st.com/resource/en/user_manual/um2159-getting-started-with-ultralowpower-stm32l0-and-lora-discovery-kit-stmicroelectronics.pdf

Stm32-B-L072Z-LRWAN documentation and user manual:
https://www.st.com/resource/en/user_manual/um2159-getting-started-with-ultralowpower-stm32l0-and-lora-discovery-kit-stmicroelectronics.pdf

Stm32-B-L072Z-LRWAN pins out:
https://os.mbed.com/platforms/ST-Discovery-LRWAN1/

Video from ST company for programming B-L072Z-LRWAN and to create a lorawan end node:
https://www.youtube.com/watch?v=MgbTraRq0K8&t=0s


<b> 👉 Important paths </b>

# Path of .project file path
~/STM32CubeExpansion_LRWAN_V2.0.0/Projects/BL072Z-LRWAN1/Applications/LoRaWAN/LoRaWAN_End_Node/STM32CubeIDE/
cmwx1zzabz_0xx/
or
~/STM32CubeExpansion_LRWAN_V2.0.0/Projects/BL072Z-LRWAN1/

# Include directory path:
~/STM32CubeExpansion_LRWAN_V2.0.0/Middlewares/
Third_Party/LoRaWAN/LmHandler/Packages/
cmwx1zzabz_0xx (the heart of lorawan application) path:
~/STM32CubeExpansion_LRWAN_V2.0.0/Projects/BL072Z-LRWAN1/Applications/SubGHz_Phy/SubGHz_Phy_PingPong/STM32CubeIDE/
cmwx1zzabz_0xx/

