Link para documento com normas ABNT: 

# Projeto de Monitoramento de Temperatura com Raspberry Pi Pico

## Descrição
- Este projeto utiliza o Raspberry Pi Pico para ler a temperatura de um ambiente usando o sensor de temperatura DS18B20. Os dados de temperatura são coletados e podem ser visualizados em tempo real.

- ## Componentes:
  - Raspberry Pi Pico
  - Sensor de temperatura DS18B20
  - Resistor de 4.7kΩ
  - Cabos de conexão
    
## Configuração do Hardware:
  - Conecte o sensor DS18B20 ao Raspberry Pi Pico:
    - VCC do sensor ao 3.3V do Pico
    - GND do sensor ao GND do Pico
    - DQ do sensor ao pino GPIO15 do Pico
    - Coloque um resistor de 4.7kΩ entre VCC e DQ para atuar como pull-up
      
## Instalação de Software:
  - Certifique-se de que o MicroPython está instalado no seu Raspberry Pi Pico. O código para ler os dados do sensor DS18B20 está escrito em Python.

## Como Usar:
  - Para usar este projeto, carregue o código Python no Raspberry Pi Pico usando uma IDE como Thonny ou outra compatível com MicroPython.
