<!--
---
name: Pioreactor HAT
class: board
type: adc,led,photodiode,motor
formfactor: HAT
manufacturer: Pioreactor
description: A bioreactor built on the Raspberry Pi
url: https://pioreactor.com
github: https://github.com/pioreactor/hardware
schematic: https://github.com/pioreactor/hardware
buy: http://pioreactor.com
image: 'image.png'
pincount: 40
eeprom: yes
power:
  '1':
  '2':
  '4':
  '17':
ground:
  '6':
  '9':
  '14':
  '20':
  '25':
  '30':
  '34':
  '39':
pin:
  '3':
    mode: i2c
  '5':
    mode: i2c
  '11':
    name: PWM AMP 1
    mode: output
    active: low
  '33':
    name: PWM AMP 2
    mode: output
    active: low
  '36':
    name: PWM AMP 3
    mode: output
    active: low
  '32':
    name: PWM AMP 4
    mode: output
    active: low
  '12':
    name: PWM AMP 5 (heating)
    mode: output
    active: low
  '12':
    name: PWM AMP 5 (heating)
    mode: output
    active: low
  '22':
    name: Hall sensor
    mode: input
  '38':
    name: RaspAP On
    mode: input
  '37':
    name: RaspAP Off
    mode: input
i2c:
  '0x48':
    name: ADC
    device: ADS1015
  '0x49':
    name: DAC
    device: DAC43608
  '0x4F':
    name: Temperature
    device: TMP1075
-->
#Pioreactor HAT

