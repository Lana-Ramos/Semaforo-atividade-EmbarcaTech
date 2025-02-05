# _Temporizador Periódico - Atividade EmbarcaTech 29-02-25_

Este repositório, feito para fins educativos, utiliza um microcontrolador Raspberry Pi Pico W e simula um semáforo utilizando leds RGB. O principal objetivo é controlar o tempo de cada ação. A mudança das cores é feita aplicando um tempo de 3 segundos para cada sinal.

# Componentes utilizados 

- Raspberry Pi pico W(ou extensão Wokwi para simular os componentes)
- 3 Leds RGB
- 3 resistores de 330 Ohms

# Como utilizar?

- Você pode baixar este repositório no GitHub ou clonar o link na sua IDE(VsCode) utilizando o Git/Github Desktop. 
- Instalar um compilador para C/C++ e as extensões: C/C++, Cmake, Raspberry Pi Pico e Wokwi.
- Compilar o código pelo ícone da Raspberry Pi do VSCode e enviar para sua placa, ou utilizar a extensão do Wokwi para testar o funcionamento do programa.


# Funcionamento 

Ao iniciar o programa pelo simulador ou pela sua placa, o led vermelho irá acender e esperar 3 segundos até desligar, então o led amarelo será aceso e após 3 segundos o led verde. Assim se mantém um ciclo como de um semáforo enquanto o sistema imprime uma mensagem a cada segundo pela porta serial, até o programa ser interrompido. 

# Linguaguem Utilizada

**C**

# Autor 

Lana Ramos Gomes

# Licença

Repositório criado para fins educacionais
