# smartcar
Acionamento de funcoes no carro por comando de voz e ou texto, via linguagen natural

O codigo neste repositorio refere-se ao orquestrador. 

A IHM adotada nesta demo foi o Telegram.

O dashboard que representa o carro (nao esta neste projeto), recebe POSTs do orquestrador e representa os comandos realizados


ORQESTRADOR:

a) Apps Cloud Foundry
Nodered


Nodes adicionais (manage palette):

node-red-contrib-telegrambot

node-red-contrib-media-utils


b) Serviços Cloud Foundry:

Watson Speech to Text

Watson Assistant



Obs
A versao do dashboard foi publicada por Higor Melgaco no git -> https://github.ibm.com/Blue9er/smart-car-demo-general 

O dashboard esta ativo em -> https://smartcar-demo.mybluemix.net/


Os comandos sao dados via telegram (textou ou audio)


Exemplos de comandos no telegram:

esta frio

esta calor

ligar limpador

esta chovendo

anoiteceu

amanheceu

desliga farol

limpador rapido

desliga limpador

toca jazz

play list



TELEGRAM
![alt text](https://github.com/afgaspar2012/smartcar/blob/master/Telegram.png)





DASHBOARD
![alt text](https://github.com/afgaspar2012/smartcar/blob/master/cardash.png)
