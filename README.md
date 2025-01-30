# Semaforo-atividade-EmbarcaTech

1 emprego da função add_repeating_timer_ms()


Os requisitos para a realização desta atividade são:

1) O acionamento dos LEDs (sinais do semáforo) deve iniciar na
cor vermelha, conforme orientação presente na Figura 1,
alterando para amarela e, em seguida, verde.

3) O temporizador deve ser ajustado para um atraso de 3 segundos
(3.000ms).

5) A mudança de estado dos LEDs deve ser implementa na função
de call-back do temporizador, a exemplo da rotina trabalhada na
aula síncrona - repeating_timer_callback().

7) A rotina principal, presente no interior da estrutura de
repetição while, deve imprimir algum tipo de informação a cada
segundo (1.000 ms) - a mensagem enviada pela porta serial fica
a critério do discente.

9) Com o emprego da Ferramenta Educacional BitDogLab, faça
um experimento com o código deste exercício utilizando o LED
RGB – GPIOs 11, 12 e 13.


Atividade 2: emprego da função add_alarm_in_ms()

Os requisitos para a realização desta atividade são:

1) Caso o usuário clique no botão (pushbutton), os três LEDs serão
ligados (todos em nível alto). A partir da primeira rotina de
atraso, ocorrerá uma mudança de estado para dois LEDs
ligados e, em seguida, apenas um. Obs.: veja o vídeo associado
a esta prática no link presente na Figura 3.

3) O temporizador do alarme deve ser ajustado para um atraso de
3 segundos (3.000ms), entre os estados de acionamento dos
LEDs.

5) A mudança de estado dos LEDs deve ser implementa em
funções de call-back do temporizador, a exemplo da rotina
trabalhada na aula síncrona - turn_off_callback().

6) O botão só pode alterar o estado dos LEDs quando o último LED
for desligado. Deste modo, durante a execução das rotinas de
temporização, o botão não pode iniciar uma nova chamada da
função call-back.

7) Com o emprego da Ferramenta Educacional BitDogLab, faça
um experimento com o código deste exercício utilizando o LED
RGB – GPIOs 11, 12 e 13 e o Botão A, GPIO 05.

9) Opcional: Implementar uma rotina em software para atenuação
do efeito bouncing no botão (software debounce).
