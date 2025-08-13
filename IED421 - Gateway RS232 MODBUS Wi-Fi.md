# IED421 - Gateway RS232 MODBUS Wi-Fi

## Principais Características

### IED421

- Realiza comunicação pelo protocolo MODBUS RTU
- Registra em memória os dados coletados
- Configuração do dispositivo via Bluetooth
- Interface de LED para status do dispositivo
- Comunicação com o servidor baseada no protocolo MQTT
- Atualização de software remotamente
- Sincronização automática de data e hora

## Aplicações

### IED421

- Gateway MODBUS Wi-Fi para aplicação industrial
- Telegestão de inversores com suporte ao protocolo MODBUS
- Datalogger offline para armazenamento de informações MODBUS

## Visão Geral

O IED421 é um gateway desenvolvido para aplicações de interface com MODBUS, como cenários de comunicação com inversores de energia de mercado. A configuração do IED421 é feita de forma simples utilizando a interface Bluetooth, podendo ser realizada por um aplicativo de smartphone. A conexão com a internet é estabelecida através da interface de comunicação Wi-Fi 2.4GHz e os dados são transmitidos para o servidor do cliente utilizando o protocolo MQTT.

O IED421 possui relógio interno, portanto, mantém data e hora correta mesmo quando desligados por muito tempo e sem conexão com internet. No modelo IED421, a data e hora são sincronizados via NTP, após a conexão com a internet.

O IED421 possui a opção de funcionar em modo offline. Neste modo o IED421 irá armazenar as informações e não enviará os dados para o servidor. A coleta dos dados armazenados é feita através de um Access Point gerado pelo próprio equipamento.

## Especificações Técnicas

### Conexões

- A interface RS232 é utilizada para conectar o gateway no dispositivo
- A coleta de dados deve ser realizada por meio do protocolo de comunicação MODBUS RTU com baudrate de 9600
- A interface Bluetooth é utilizada para configuração inicial
- A interface Wi-Fi 2.4GHz é utilizada para conexão com internet

### Físico/Ambiental

- **Alimentação:** 5 a 15Vdc
- **Consumo máximo de energia:** 1 W
- **Dimensões IED4X1 (CxLxA):** 42 x 125 x 32 mm
- **Temperatura de operação:** -10 a 60 ºC
- **Temperatura de armazenamento:** -30 a 85ºC
- **Umidade de operação/armazenamento:** Até 90% não condensado

### Armazenamento de dados

- Depende da configuração e de quantos registradores irá coletar do dispositivo MODBUS
- Memória de 4 MB compartilhada com o sistema operacional
- Aproximadamente 150000 registradores MODBUS

### Garantias e certificações

- **Garantia total (legal + garantia Khomp):** 1 ano
  - Garantia legal: 90 dias
  - Garantia Khomp: 9 meses
- **Indústria certificada ISO 9001**

## Especificações Detalhadas

### Tabela 1: Características

| Parâmetros | IED421 | Unidade |
|------------|--------|---------|
| Interface de dados | RS232 | — |
| Tensão de operação | 5 a 15 | Vdc |
| Potência | 1 | W |
| Conector | RJ12 | — |
| Comprimento do cabo | 1 | m |
| Bateria para relógio interno | CR1220 | — |

### Tabela 2: Parâmetros técnicos gerais

| Parâmetros | IED421 | Unidade |
|------------|--------|---------|
| Interface com usuário | LED RGB e botão | — |
| Protocolo de comunicação inversor | Modbus RTU | — |
| Protocolo de comunicação servidor | MQTT | — |
| Ganho da antena | 3 | dBi |
| Máxima distância Wi-Fi com visada direta | 100 | m |
| Dimensões | 42 x 125 x 32 | mm x mm x mm |
| Peso | 35 | g |

### Tabela 3: Parâmetros técnicos Wi-Fi

| Parâmetros | IED421 | Unidade |
|------------|--------|---------|
| Padrão Wi-Fi | IEEE 802.11b/g/n | — |
| Modo de autenticação Wi-Fi | OPEN, WEP, WPA_PSK, WPA2_PSK, WPA_WPA2_PSK | — |
| Canais Wi-Fi | 1 a 13 | — |
| Largura de canal Wi-Fi | 20 e 40 | MHz |
| Frequência de operação Wi-Fi | 2412 a 2484 | MHz |
| Potência TX Wi-Fi | 18.5 a 21 | dBm |
| Potência RX Wi-Fi | -71.4 a -98.4 | dBm |

### Tabela 4: Parâmetros técnicos Bluetooth

| Parâmetros | IED421 | Unidade |
|------------|--------|---------|
| Bluetooth | Bluetooth 5 | — |
| Frequência de operação Bluetooth | 2402 a 2480 | MHz |
| Potência TX Bluetooth | -24 a 21 | dBm |
| Potência RX Bluetooth | -105 a -93 | dBm |

## Informações Regulamentares

Este equipamento não tem direito à proteção contra interferência prejudicial e não pode causar interferência em sistemas devidamente autorizados.

Para informações do produto homologado acesse o site: https://sistemas.anatel.gov.br/sch

## Modelo de aplicação

*[Informação sobre modelo de aplicação disponível no documento original]*

## Contato

**Khomp**  
Rua Joe Collaço, 253 - Florianópolis, SC  
+55 (48) 3722.2900  
comercial@khomp.com

---

*Documento convertido para Markdown por Manus AI*

