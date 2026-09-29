# ESP32 – Sistemas Ciberfísicos

Códigos feitos com ESP32 DevKit (30 pinos) na disciplina de Sistemas Ciberfísicos.

## Projetos

| Pasta | O que faz |
|---|---|
| [`hello_world_web`](hello_world_web/) | O ESP32 cria a rede Wi-Fi `ESP32-Hello` (senha `12345678`) e serve uma página "Hello World" em `http://192.168.4.1`. |
| [`teste_teclado_3x4`](teste_teclado_3x4/) | Lê um teclado matricial 3x4 e mostra a tecla pressionada no Monitor Serial (115200). |

## Como usar

1. Abra o `.ino` da pasta na Arduino IDE (placa: **ESP32 Dev Module**).
2. Para o teclado, instale a biblioteca **Keypad** (Mark Stanley / Alexander Brevig) pelo Gerenciador de Bibliotecas.
3. Faça o upload e abra o Monitor Serial em 115200.

### Ligação do teclado 3x4

| Fio do teclado | Pino do ESP32 |
|---|---|
| 1 (linha 1) | GPIO 14 |
| 2 (linha 2) | GPIO 27 |
| 3 (linha 3) | GPIO 26 |
| 4 (linha 4) | GPIO 25 |
| 5 (coluna 1) | GPIO 33 |
| 6 (coluna 2) | GPIO 32 |
| 7 (coluna 3) | GPIO 13 |
