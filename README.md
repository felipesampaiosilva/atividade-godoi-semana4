# Código utilizado para realização da atividade da Semana 4 para medição da temperatura com sensor

```
import machine
import time
import dht

sensor = dht.DHT11(machine.Pin(4))

while True:
    try:
        sensor.measure()
        temp = sensor.temperature() 
        print("Temperatura em graus Celsius: {:.1f} °C".format(temp))

    except OSError as e:
        print("Falha ao ler o sensor.")

    time.sleep(2)
```
