# NXP SE050 Test-Get-Cert-idf4-new

This communicates NXP SE050 secure chip from ESP32 and extract a certificate pre-provisioned by NXP.  
Integrated Plugand Trust middleware  

# Requirements

  Platformio(PIO Core:4.3.0 PLATFORM: Espressif 32 1.12.4) with VS Code environment.  
  install "Espressif 32" platform definition on Platformio  

# Environment reference
  
  Espressif ESP32-DevkitC  
  this project initialize both of I2C 0,1 port, and the device on I2C port 0 is absent.  
  pin assined as below:  


      I2C 0 SDA GPIO_NUM_18
      I2C 0 SCL GPIO_NUM_19

      I2C 1 SDA GPIO_NUM_21
      I2C 1 SCL GPIO_NUM_22
          
  NXP SE050(on I2C port 1)  

# Usage

"git clone --recursive " on your target directory. 
you need to change a serial port number which actually connected to ESP32 in platformio.ini.  
This repository references Plug and Trust middleware from github, so there is no need to download and install it from the NXP site.  

# Run this project

just execute "Upload" on Platformio.   

# License

This software is released under the MIT license unless otherwise specified in the included source code. See License. 
