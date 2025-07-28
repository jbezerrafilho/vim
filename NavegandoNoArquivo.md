+-------------------------------------------------------------+
|                                                             |
|          ✨  SEUS PRIMEIROS PASSOS NO VIM!  ✨              |
|                                                             |
+-------------------------------------------------------------+

             Modo Padrão: 💡 NORMAL MODE 💡
             (Onde você digita os comandos)

---------------------------------------------------------------

🎯  MOVIMENTAÇÃO BÁSICA (Por caractere/linha)
    Não tire as mãos da posição de digitação!

    ⬅️   **h** - Esquerda
    ⬇️   **j** - Baixo
    ⬆️   **k** - Cima
    ➡️   **l** - Direita

    *Dica: Segure a tecla para repetir o movimento!*

---------------------------------------------------------------

📄  MOVIMENTAÇÃO POR PÁGINAS

    ⬇️ PÁGINA:  **Ctrl + f** (de "Forward" - para frente)
    ⬆️ PÁGINA:  **Ctrl + b** (de "Backward" - para trás)

---------------------------------------------------------------

📖  MOVIMENTAÇÃO POR PALAVRAS (e seus segredos!)

    ➡️ PRÓXIMA PALAVRA:
        ▪️ **w** (minúsculo): Para em PONTUAÇÃO.
                               (Ex: `palavra,` -> para em `,` depois `palavra`)
        ▪️ **W** (MAIÚSCULO): IGNORA PONTUAÇÃO.
                               (Ex: `palavra,` -> pula direto para a próxima palavra)

    ⬅️ PALAVRA ANTERIOR:
        ▪️ **b** (minúsculo): Volta parando em PONTUAÇÃO.
        ▪️ **B** (MAIÚSCULO): Volta IGNORANDO PONTUAÇÃO.

    *Padrão Vim: Minúscula e Maiúscula fazem coisas PARECIDAS!*

---------------------------------------------------------------

📏  MOVIMENTAÇÃO NA LINHA (Início e Fim)

    ↩️ INÍCIO DA LINHA (primeiro caractere):  **0** (zero)
    ↩️ INÍCIO REAL (primeiro texto, ignora espaços):  **^**
    ➡️ FIM DA LINHA:  **$**

---------------------------------------------------------------

🔢  SALTANDO PARA LINHAS ESPECÍFICAS

    PRIMEIRA LINHA DO ARQUIVO:  **gg**
    ÚLTIMA LINHA DO ARQUIVO:  **G** (maiúsculo)

    LINHA ESPECÍFICA:
    ▪️ Digite o NÚMERO e depois **gg** ou **G**.
      Ex: `2gg` ou `2G` (para a linha 2)

    USANDO O MODO DE LINHA (começa com `:`):
    ▪️ Para uma linha específica:  **:[número]** + Enter
      Ex: `:5` + Enter (para a linha 5)
    ▪️ Para a última linha:  **:$** + Enter

---------------------------------------------------------------

📊  INFORMAÇÕES DO ARQUIVO E CURSOR

    VER STATUS:  **Ctrl + g**
      (Mostra nome do arquivo, linha atual, total de linhas, %)

    LIGAR/DESLIGAR A "RÉGUA" (linha e coluna no canto):
    ▪️ Ligar:  **:set ruler**
    ▪️ Desligar: **:set noruler**
    ▪️ Alternar: **:set ruler!**
