# NodeMCU8266-SensorDeChuva
Nesse projeto, utilizamos o NODEMCU8266 e um sensor de chuva RainDrops Module. Também utilizamos para o envio de e-mails o STMP Gmail. No primeiro momento testamos que
se o sensor fosse molhado ele ligava o led da placa e caso contrário se não estivesse molhado o led ficava desligado. Após os testes codificamos para que o NodeMcu fosse
conectado ao email para poder fazer os envios de mensagens em função do código feito, o qual tem como objetivo de 5 em 5 minutos é feito uma verificação de qual o estado
do sensor se está "chovendo" ou não e com isso emite mensagens ao email colocado como destinatário.
