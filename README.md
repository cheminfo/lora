# lora
Bash utilities to use RN2483 microchip LORA from raspberry pi (RPi)

Those small utilites allows to manage the Lora chip RN2483 that is connected using RX / TX to a RPi.

To install just copy the utilites from the 'bash' folder to '/usr/local/bin'


## lora

Just enter your text after the "lora" instruction and it will be sent.

`> lora send this test`

## loraInit

You need to append the address of your device that you should first register on: http://thethingsnetwork.org/wiki/AddressSpace

`> loraInit 1234ABCD`

## loraInfo

Retrieve most of the parameters from the RN2483

`> loraInfo`
