# Ejemplo Documentación 
![Tinkercad](./img/ArduinoTinkercad.jpg)


## Integrantes 
- Nicolas Caliari
- Tobias Pasinato
- Luciano javier Lucero


## Proyecto: Contador binario.
![Tinkercad](./img/ContadorBinario.png)


## Descripción
Primera parte: Se encarga de sumar, restar y resetear un contador. Sumando de a uno al contador o restando de a uno y en el caso de resetar reinicia a cero el contador.

Segunda parte: Cumple la misma funcion que en la parte uno, ademas que mediante un switch podes cambiar de modo, a contador o muestra los numeros primos.

Tercera parte: Cumple la misma funcion que la parte dos, solo que cambiamos el swtich por un sensor de flexibilidad.


## Función principal
Esta funcion se encarga de encender y apagar los displays.

A, B, C, D, E ,F ,G son #define que utilizamos para prender los leds del displays, asociandolo a pines de la placa arduino.

(Breve explicación de la función)

~~~ C (lenguaje en el que esta escrito)
void prendeUnNumero(int digit)
{
  digitalWrite(A, LOW);
  digitalWrite(B, LOW);
  digitalWrite(C, LOW);
  digitalWrite(D, LOW);
  digitalWrite(E, LOW);
  digitalWrite(F, LOW);
  digitalWrite(G, LOW);
  switch (digit)
  {
    case 1:
    {
      digitalWrite(B, HIGH);
      digitalWrite(C, HIGH);
      break;
    }
    case 2:
    {
      digitalWrite(A, HIGH);
      digitalWrite(B, HIGH);
      digitalWrite(D, HIGH);
      digitalWrite(E, HIGH);
      digitalWrite(G, HIGH);
      break;
    }

    case 3:
    {
      digitalWrite(A, HIGH);
      digitalWrite(B, HIGH);
      digitalWrite(C, HIGH);
      digitalWrite(D, HIGH);
      digitalWrite(G, HIGH);
      break;
    }
    case 4:
    {
      digitalWrite(B, HIGH);
      digitalWrite(C, HIGH);
      digitalWrite(F, HIGH);
      digitalWrite(G, HIGH);
      break;
    }

    case 5:
    {
      digitalWrite(A, HIGH);
      digitalWrite(C, HIGH);
      digitalWrite(D, HIGH);
      digitalWrite(F, HIGH);
      digitalWrite(G, HIGH);
      break;
    }
    case 6:
    {
      digitalWrite(A, HIGH);
      digitalWrite(C, HIGH);
      digitalWrite(D, HIGH);
      digitalWrite(E, HIGH);
      digitalWrite(F, HIGH);
      digitalWrite(G, HIGH);
      break;
    }

    case 7:
    {
      digitalWrite(A, HIGH);
      digitalWrite(B, HIGH);
      digitalWrite(C, HIGH);
      break;
    }
    case 8:
    {
      digitalWrite(A, HIGH);
      digitalWrite(B, HIGH);
      digitalWrite(C, HIGH);
      digitalWrite(D, HIGH);
      digitalWrite(E, HIGH);
      digitalWrite(F, HIGH);
      digitalWrite(G, HIGH);
      break;
    } 
    case 9:
    {
      digitalWrite(A, HIGH);
      digitalWrite(B, HIGH);
      digitalWrite(C, HIGH);
      digitalWrite(D, HIGH);
      digitalWrite(F, HIGH);
      digitalWrite(G, HIGH);
      break;
    } 

    case 0:
    {
      digitalWrite(A, HIGH);
      digitalWrite(B, HIGH);
      digitalWrite(C, HIGH);
      digitalWrite(D, HIGH);
      digitalWrite(E, HIGH);
      digitalWrite(F, HIGH);
      break;
    }
  }
}

~~~

## :robot: Links del proyecto
- [proyecto parte 1](https://www.tinkercad.com/things/aOYiibnDjWu)
- [proyecto parte 2](https://www.tinkercad.com/things/4Iubwx2xzL8-tp1/editel)
- [proyecto parte 2 sensor](https://www.tinkercad.com/things/6Vz955WHeC8-copy-of-tp1/editel?tenant=circuits)





