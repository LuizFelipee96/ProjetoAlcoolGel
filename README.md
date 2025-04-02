# **Dispensador Automático de Álcool em Gel**  

## **Descrição do Projeto**  
O presente projeto consiste no desenvolvimento de um sistema automatizado para a dispensação de álcool em gel, visando promover a higienização eficiente das mãos de forma segura e sem contato. O dispositivo utiliza sensores para detectar a aproximação do usuário e acionar automaticamente a liberação do álcool em gel, reduzindo a necessidade de toque e minimizando o risco de contaminação cruzada.  

A aplicação desse sistema é voltada para ambientes públicos, hospitais, empresas e demais locais que necessitam de medidas eficazes de higiene. Além disso, o projeto busca integrar tecnologias que aumentem a autonomia e a usabilidade do dispositivo.  

## **Componentes Utilizados**  

| **Componente**              | **Função no Sistema**                                                         |
|----------------------------|-------------------------------------------------------------------------------|
| Sensor Ultrassônico HC-SR04 | Detecta a presença do usuário e aciona o sistema de dispensação.             |
| Arduino Uno R3             | Microcontrolador responsável pelo controle do sistema.                       |
| Servo Motor SG90           | Aciona o mecanismo de liberação do álcool em gel.                            |
| Display LCD 16x2           | Exibe informações sobre o status do sistema e nível do reservatório.         |
| Sensor de Nível de Líquido | Monitora a quantidade de álcool disponível no reservatório.                  |
| Módulo Bluetooth HC-05     | Permite a integração do sistema com dispositivos móveis para monitoramento.  |
| Fonte de Alimentação 5V    | Alimentação do sistema.                                                      |

## **Funcionamento**  

O sistema de dispensação de álcool em gel opera de forma automática, garantindo a higienização eficiente das mãos sem a necessidade de contato físico. O funcionamento do dispositivo baseia-se nas seguintes etapas:  

1. **Detecção da Presença do Usuário**  
   - O sensor ultrassônico detecta a aproximação das mãos e envia um sinal ao microcontrolador.  

2. **Acionamento do Dispensador**  
   - O **Arduino Uno R3** processa o sinal recebido e ativa o **servo motor SG90**, que movimenta a válvula do reservatório para liberar uma quantidade controlada de álcool em gel.  

3. **Monitoramento do Nível de Álcool**  
   - Um **sensor de nível de líquido** verifica a quantidade de álcool no reservatório, permitindo alertas quando o nível estiver baixo.  

4. **Exibição de Informações**  
   - O status do sistema e o nível do reservatório são exibidos em um **display LCD 16x2**.  

5. **Integração com Dispositivos Móveis (IoT)**  
   - O módulo **Bluetooth HC-05** possibilita o envio de dados para um dispositivo móvel, permitindo o monitoramento remoto do nível de álcool e do status operacional do dispensador.  

O projeto pode ser aprimorado com a implementação de uma bateria recarregável para tornar o dispositivo portátil, além da incorporação de sensores mais precisos para melhorar a detecção da presença do usuário.  

## **Instalação**  
_x_  

## **Video Google Drive**  
A apresentação deste projeto foi gravada e publicada no YouTube. Para assistir, acesse o link: [aqui](https://drive.google.com/file/d/1Z5Y4WT4Inxv3UNY7E61F3dmGt30_tQ0w/view?usp=sharing).  

## **Contribuições**  
Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias, corrigir problemas ou adicionar novos recursos ao projeto.  
