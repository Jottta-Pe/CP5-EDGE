# 🍇 Vinheria Agnello – Monitoramento IoT da Adega com ESP32

Projeto: Vinheria Agnello – Monitoramento de Luminosidade, Temperatura e Umidade com Arduino
Este repositório contém o projeto desenvolvido para o Checkpoint 02 da disciplina Edge Computing & Computer Systems (FIAP - 2025). Trata-se de um sistema físico e funcional montado com Arduino, focado no monitoramento da luminosidade, Temperatura e Umidadedo ambiente de armazenamento da Vinheria Agnello, com o objetivo de preservar a qualidade dos vinhos.


## 🧩 Descrição do Desafio
A Vinheria Agnello tem a intenção de ampliar suas atividades para o meio digital, mantendo a excelência no atendimento e no zelo pelos produtos. O nosso objetivo foi sugerir um sistema integrado que pudesse identificar condições ambientais inapropriadas da estufa dos vinhos— no caso, excesso de luz, temperaturas muito elevadas ou muito baixas, e umidade inadequada. Porém, fazendo o circuito percebemos que o simulador wokwi não possui o sensor DHT 11 que iremos usar no projeto físico... então usamos um sensor do próprio simulador.



## 📘 Descrição do Projeto
Este projeto tem como objetivo o monitoramento em tempo real das condições ambientais da adega da Vinheria Agnello, utilizando o ESP32 para capturar dados de temperatura, umidade e luminosidade e enviá-los a um servidor MQTT.
A interface de visualização e controle é feita via o aplicativo MyMQTT.

## 🔧 Componentes Utilizados
- 1 × Arduino Uno R3 (U1)
- 1 × Fotorresistor (LDR) (Rluz)
- 4 × Resistor de 220 Ω (R4) (conectados nos LEDs e no LDR)
- 3 × LEDs:
- 1 × Vermelho
- 1 × Verde
- 1 × Amarelo
- Cabos Jumpers
- 1 × Protoboard

## 🧠 Componentes Utilizados
- ESP32 -	Microcontrolador com Wi-Fi e Bluetooth
- DHT11 -	Sensor de temperatura e umidade
- LDR -	Sensor de luminosidade
- Módulo de Interface de Sensores	Placa de conexão dos sensores
- Servidor MQTT -	Publicação e subscrição de dados IoT
- Aplicativo MyMQTT -	Cliente MQTT para IoS e Android

## ⚙️ Conexões do Circuito

- ESP32	Sensor Board	Função
- 3V3	VCC	Alimentação 3.3V
- GND	GND	Terra
- D4 (GPIO4)	DHT11 Data	Leitura do DHT11
- D34 (GPIO34)	LDR	Leitura do LDR

 <img width="845" height="415" alt="imagem" src="https://github.com/user-attachments/assets/cbd07c55-04cf-4013-8031-b75a1269483c" />
 
📸 A figura acima ilustra o esquema de ligação entre o ESP32 e o módulo de sensores.
--


## Componentes do Grupo
- Caio Caminha - 564789
- Giovana Parreira - 562275 
- Jean Pierre - 566534
- Julia Pompeu - 561955
- Kaio Galvão - 566536
