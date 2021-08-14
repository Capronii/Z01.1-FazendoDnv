# Mundo Real

!!! warning ""
    Entregar até dia 3/12 (final da semana de AF).

| HW | SW |
|----|----|
| 15 | 15 |

Esse projeto extra optativo (individual) fornece **15 pontos** 
extras de **Hardware** e **15 pontos extras** de **Software**. 

## (10 SW/ 10 HW) Processadores

Você deverá escolher um dos processadores listados a seguir:

- [ARM Cortex M0](https://en.wikipedia.org/wiki/ARM_Cortex-M)
- [RISC V](https://en.wikipedia.org/wiki/RISC-V)
- [AVR](https://www.google.com/search?q=avr+microcontroller+wiki)
- [Microchip PIC ](https://en.wikipedia.org/wiki/PIC_microcontrollers)
- [PowerPC](https://en.wikipedia.org/wiki/PowerPC)
- [SPARC V8](https://en.wikipedia.org/wiki/SPARC)
- [ZIP CPU](https://zipcpu.com/)
- [OpenRISC](https://openrisc.io/)

!!! warning 
    Não pode repetir dentro do grupo!
    ==DPs: Não pode ser o mesmo do semestre passado==

Vocês devem entregar um vídeo que explica a CPU em questão, neste vídeo (de no mínimo 3 minutos e no máximo 5) vocês devem explicar:

- Histórico
    - [ ] História da arquitetura
    - [ ] Pessoas/ empresas responsáveis
    - [ ] Impacto histórico, impacto nos concorrentes/ comunidade/
    - [ ] Curiosidades
    
- Uso atual
    - [ ] Dispositivos e empresas que ainda fazem uso da arquitetura
    
- Arquitetura
    - [ ] Descreva a arquitetura interna da CPU
        - [ ] Quantos bits de largura? 8/16/32/..
        - [ ] Quantidade de registradores
        - [ ] Operações da ULA (se for muitas, pode pegar algumas)
        - [ ] A arquitetura é CISC ou RISC?
        - [ ] Como o Program Cunter (PC) funciona? 
        - [ ] Como é realizado o acesso a memória nessa arquitetura?
          - Pode fazer operações direto na memória? Ou temos que carregar para os registradores antes?
        - [ ] Especificidades
    - [ ] Comparação com o Z01.1
    
==Muito importante sempre que possível realizar uma comparação com a nossa CPU==
    
- Instruções
    - [ ] Descritivo das instruções e seus padrões
    - [ ] Quantidade total de instruções
    - [ ] Diferença com relação ao Z01.1 

## (**5 HW / 5 SW**) Comentar código

Você deve pegar um código de exemplo do assembly da CPU escolhida de baixa/média e comentar ele no vídeo, explicando o que está fazendo.

- Explicar o que cada instrução está fazendo
- o impacto dela no hardware
- Muitas arquitetura possuem simulador! Interessante usar, mas não é necessário