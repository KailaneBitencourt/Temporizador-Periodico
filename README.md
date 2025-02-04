# Semáforo com LED RGB - Raspberry Pi

Este projeto simula o funcionamento de um semáforo utilizando um LED RGB e temporizadores, programado em C para o Raspberry Pi. A mudança de cores segue a sequência padrão de um semáforo: vermelho, amarelo e verde, com a transição ocorrendo a cada 3 segundos. A implementação utiliza a biblioteca do Raspberry Pi e a Ferramenta Educacional BitDogLab.

## Requisitos

- **Placa**: Raspberry Pi
- **Linguagem**: C
- **Hardware**: LED RGB (conectado aos GPIOs 11, 12 e 13)
- **Ferramenta**: BitDogLab (para simulação ou Wokwi)

## Funcionalidade

1. **Sequência de Cores do Semáforo**: 
   - O LED inicia na cor **vermelha**.
   - Após 3 segundos, muda para **amarelo**.
   - Depois, muda para **verde**.
   
2. **Temporização**: A mudança de estado do LED ocorre a cada 3 segundos (3000ms).

3. **Callback do Temporizador**: 
   - A mudança de estado dos LEDs é controlada dentro de uma função de callback `repeating_timer_callback()`.


## Como Rodar

1. Clone este repositório para o seu Raspberry Pi:
2. Compile o código
3. Coloque a placa em modo BOOTSEL, ou coloque para simular no WOKWI
4. Rode o código
