Diagrama de blocos preliminar do projeto:

![Diagrama de blocos](DiagramaDeBlocos.jpg)

legenda:

1 - o computador de bordo envia a ângulação desejada e recebe as informações de telemetria via protocolo MQTT (tensão, corrente, potência, longitude, latitude, direção, velocidade, eventos)
2 - as mesmas informações de telemetria são fornecidas via protoloca CAN utilizado em veículos
3 - a tensão de pico é medida na entrada do ponte H e enviada para o microcontrolador
4 - as informações de geolocalização são enviadas para o microcontrolador
5 - a corrente de pico é medida na entrada do ponte H e enviada para o microcontrolador
6 - o PWM é gerado conforme o ângulo recebido pelo computador de bordo
7 - o ângulo é medido sem contato no eixo do leme e enviado para o microcontrolador
8 - o ponte H aciona o motor e fornece as proteções necessárias
9 - o motor acoplado a um sistema de engrenagens e roldanas gira o leme na direção conforme o PWM

