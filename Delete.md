# ✂️ Deletando Texto no Vim: Guia para Iniciantes

Este guia resume a aula sobre como deletar texto no Vim, de forma clara e prática para quem está começando.

---

## 📁 Abrindo o Arquivo de Treino

```bash
cd Downloads/vimclass
vim deleting-lesson.txt
```

---

## 🧹 Comandos Básicos de Deleção

| Comando | Ação                                  |
|---------|---------------------------------------|
| `x`     | Apaga o caractere **sob o cursor**     |
| `X`     | Apaga o caractere **antes do cursor**  |
| `dd`    | Apaga a **linha inteira**              |
| `3dd`   | Apaga **3 linhas**                     |
| `D`     | Apaga do cursor até o **fim da linha** |
| `d$`    | Mesma função do `D`                    |
| `d0`    | Apaga até o **início da linha**        |
| `dj`    | Apaga linha atual + próxima            |
| `dk`    | Apaga linha atual + anterior           |

---

## 🧠 Padrão: Operador + Movimento

| Comando   | Ação                          |
|-----------|-------------------------------|
| `dw`      | Apaga até o fim da palavra     |
| `d2w`     | Apaga duas palavras            |
| `dG`      | Apaga até o final do arquivo   |
| `dgg`     | Apaga até o início do arquivo  |
| `d/^fim`  | Apaga até encontrar "fim"      |

---

## 🔁 Repetindo Comandos

- `.` → repete o **último comando** de deleção

---

## 🔢 Repetição com Números

| Comando   | Ação                        |
|-----------|-----------------------------|
| `3dw`     | Apaga 3 palavras            |
| `2d3w`    | Executa `d3w` duas vezes → apaga 6 palavras |

---

## 💾 Salvando e Saindo

| Comando    | Ação                         |
|------------|------------------------------|
| `:w`       | Salva                        |
| `:q`       | Sai (se não houver alterações) |
| `:wq`      | Salva e sai                  |
| `:q!`      | Sai **sem salvar**           |

---

## ❗ Sobre o Exclamação `!` no Vim

- `:q!` → força saída sem salvar
- `:set ruler!` → alterna configuração
- `:!comando` → roda comando externo

---

Feito por Zezinho com 💙 para seus estudos em Vim.
