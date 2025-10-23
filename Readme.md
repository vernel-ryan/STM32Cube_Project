# STM32 Project 

This repository contains my STM32 Project.

## Introduction 

The goal of this STM32 project is to learn/show how embedded systems work and add multiple functionnalities using the STM32CubeIDE software.

## Hardware 

* [STM32F103RBT6 Nucleo](https://www.amazon.fr/Carte-d%C3%A9veloppement-STMicroelectronics-NUCLEO-F103RB-STM32/dp/B07CWQKVCD/ref=sr_1_2?asc_source=01H8HFYCS1MWCPQSJYRR7EWW12&crid=3Q5X4T1MG7RM&dib=eyJ2IjoiMSJ9.g7kCz60B_jyCXtXBqm_LIa_omVNqDs83lHNWjORiKiDPTcTzeOdYM4FNmhjcmbm0v4Rm5Nq3yq5qXK0ULCt_CcqR7934shs1Ruv-9Hz2icht1H7YCDJWGNozuQoCGS7gdyqS-3CEv1y1hNd1d9dgIBsIaE0ekir5zEcqc_I79ZbFukw_mdULtXIA52ZjxEmjnOVCPJZSvj2jljoN43-ugXdebtTHw5OSQpNLeqnLMZe7eXZkhCaloRQio_qDNQdR3qO-eFLYIiOjt49YiwHep8eIWgphf-0sRHdjKuimE40.B6wClihPMmxgoK8WBF268Dt9iPlqEjK-BWBCifkFGy4&dib_tag=se&keywords=stm32f103rbt6+nucleo&qid=1760967572&sprefix=stm32f103rbt6+nucleo%2Caps%2C70&sr=8-2&tag=snxfr109-21)
* [Arduino Uno](https://fr.rs-online.com/web/p/arduino/7154081?cm_mmc=FR-PLA-DS3A-_-bing-_-PLA_FR_FR_Catch+All-_-Composants+Electroniques,+Energie+et+Connecteurs-_-7154081&matchtype=e&pla-4574655592306590&cq_src=google_ads&cq_cmp=554644914&cq_term=&cq_plac=&cq_net=o&cq_plt=gp&msclkid=594d264f1d451707e4f54eb926990792&gclid=594d264f1d451707e4f54eb926990792&gclsrc=3p.ds&gad_source=7&gad_campaignid=20595363253)
* LEDs
* Resistors
* Photoresistor

## My Work 

Here is the different parts of my work on this project.
### PWM Functionnality 

I initialized the TIM2 timer in PWM mode to generate a PWM signal on a LED output pin to modifiy its intensity.

### UART Functionnality 

I integrated the UART serial communication to send messages and datas to an Arduino Uno board.

### ADC Functionnality 
#### Internal Temperature Sensor 

I used the ADC conversion to get the temperature in °C with the internal temperature sensor. The datas are sent on the Arduino Uno board with the UART communication.