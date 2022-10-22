# Creación de entorno de tareas en AWS con CLI

## Referencia de comandos

https://awscli.amazonaws.com/v2/documentation/api/latest/reference/ec2/index.html#cli-aws-ec2

## Configuración del entorno en el Learner Lab

![ConfigurarEntornoLearnerLab.PNG](imagenes/ConfigurarEntornoLearnerLab.PNG)

## Creación de entorno de tareas 00AWSCrearVPC_EC2Win_Ubu.sh

Con este fichero se creará el siguiente entorno de tareas:

![00AWSCrearVPC_EC2Win_Ubu.PNG](imagenes/00AWSCrearVPC_EC2Win_Ubu.PNG)

Creará:

* Una VPC
* Una subred pública
* Una puerta de enlace de internet
* La tabla de enrutamiento de la subred para permitir conectarse a internet
* Un grupo de seguridad para Ubuntu y otro para Windows
* Una instancia EC2 con Windows Server 2022 
* Una instancia EC2 con Ubuntu Server 22.04
* Direcciones IPs públicas para las instancias EC2

