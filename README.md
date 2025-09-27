# Jogo-de-Adivinha-o-de-Palavras-com-Display-OLED-vers-o-simplificada-de-Wordle-termo-
📖 Descrição

Jogo de Adivinhação de Palavras com Display OLED (MicroPython)
Este projeto é uma versão simplificada de “Wordle / termo”, onde o usuário tenta adivinhar palavras ocultas, letra por letra, com um número limitado de tentativas. O sistema mostra o progresso no display OLED, revelando letras corretas nas posições certas.

🔗 Abrir no Wokwi

🧠 Funcionalidades

Exibe uma tela de introdução no OLED com instruções iniciais.

Esconde as letras das palavras selecionadas (representadas por “_ _ _ _ …”).

Solicita ao usuário que digite uma palavra da mesma extensão das palavras alvo.

Para cada tentativa, revela as letras que estão corretas na posição correta nas palavras.

Conta o número de tentativas até um máximo (ex: 6 tentativas).

Ao acertar todas as palavras antes de esgotar tentativas, exibe mensagem de vitória; caso contrário, revela as palavras completas no final.

🛠️ Tecnologias

Linguagem: MicroPython

Placa simulada: Raspberry Pi Pico

Display: SSD1306 OLED via I2C

Arquivos auxiliares:

fala.py — define palavras usadas e mensagens de introdução

ssd1306.py — driver do display OLED

▶️ Como executar

Acesse o link da simulação no Wokwi.

Inicie a simulação e aguarde a tela de introdução.

Quando for solicitado, digite uma palavra de mesma quantidade de letras que as palavras alvo.

A cada tentativa, o progresso será mostrado no display OLED.

Tente adivinhar todas as palavras antes de esgotar o número máximo de tentativas.
