# 🧠 Guia de Navegação no Vim para Iniciantes

Este guia foi criado como resumo do curso de Vim da Udemy, com foco em estudantes iniciantes. Ele apresenta os principais comandos de **navegação no modo normal** do Vim, com explicações simples e exemplos.

---

## 📂 Abrindo um Arquivo no Vim

Para abrir um arquivo existente:

```bash
vim nome-do-arquivo.txt
```

Exemplo usando caminho relativo:
```bash
cd vimclass
vim nav.txt
```

Exemplo usando caminho absoluto:
```bash
vim /home/usuario/vimclass/nav.txt
```

---

## 🧭 Navegação Básica (Modo Normal)

| Tecla | Ação               | Dica                        |
|-------|--------------------|-----------------------------|
| `h`   | Esquerda           | Fica à esquerda no teclado |
| `j`   | Para baixo         | Parece uma seta para baixo |
| `k`   | Para cima          | Acima do `j`               |
| `l`   | Para a direita     | Fica à direita no teclado  |

---

## 📄 Navegação por Página

| Atalho     | Ação               |
|------------|--------------------|
| `Ctrl+f`   | Avança uma página  |
| `Ctrl+b`   | Volta uma página   |

---

## 🔤 Navegação por Palavras

| Comando    | Ação                                              |
|------------|---------------------------------------------------|
| `w` / `W`  | Avança para próxima palavra (W ignora pontuação)  |
| `b` / `B`  | Volta uma palavra (B ignora pontuação)            |

---

## 📌 Navegação por Linhas

| Comando | Ação                                      |
|---------|-------------------------------------------|
| `0`     | Vai para o início da linha (coluna 0)     |
| `^`     | Vai para o primeiro caractere da linha    |
| `$`     | Vai para o final da linha                 |

---

## 🔢 Ir para uma Linha Específica

| Comando    | Ação                                |
|------------|-------------------------------------|
| `gg`       | Vai para a primeira linha           |
| `G`        | Vai para a última linha             |
| `nG` / `ngg` | Vai para a linha `n`              |
| `:n`       | Vai para a linha `n` (modo comando) |
| `:$`       | Vai para a última linha             |

---

## ℹ️ Ver Informações do Arquivo

| Comando       | Ação                                                    |
|---------------|---------------------------------------------------------|
| `Ctrl+g`      | Mostra nome do arquivo, linha atual e porcentagem       |
| `g Ctrl+g`    | Mostra número de palavras, caracteres, etc.             |

---

## 📏 Ativando a Régua

| Comando           | Ação                                     |
|-------------------|------------------------------------------|
| `:set ruler`      | Ativa a régua (exibe linha e coluna)     |
| `:set noruler`    | Desativa a régua                         |
| `:set ruler!`     | Alterna entre ligado/desligado           |

---


