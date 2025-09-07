# ⛵ Desafio Batalha Naval ⛵

Este repositório contém o **Desafio Batalha Naval**, desenvolvido em linguagem C, com implementação dos três níveis: **Novato**, **Aventureiro** e **Mestre**.

---

## 🥉 Nível Novato 🥉

### 🕹️ Descrição

- Tabuleiro 5x5 com matriz bidimensional.
- Posicionamento de dois navios:
  - Um navio **horizontal** (3 posições).
  - Um navio **vertical** (2 posições).
- Impressão no console das **coordenadas ocupadas**.

### ▶️ Como executar

```bash
gcc batalha_naval_novato.c -o novato
./novato
```

## 🥈 Nível Aventureiro 🥈

### 🕹️ Descrição

- Tabuleiro representado por uma matriz 10x10.
- Posicionamento automático de **4 navios**:
  - 1 horizontal
  - 1 vertical
  - 1 diagonal principal
  - 1 diagonal secundária
- Exibição completa do tabuleiro com:
  - `0` = posição vazia
  - `3` = parte de navio

### ▶️ Como Executar

```bash
gcc batalha_naval_aventureiro.c -o aventureiro
./aventureiro
```

## 🥇 Nível Mestre 🥇

### 🕹️ Descrição

- Representação de **habilidades especiais** com matrizes 5x5.
- Três padrões:
  - 🔺 Cone
  - ➕ Cruz
  - ♦️ Octaedro
- `1` = área afetada, `0` = não afetada

### ▶️ Como Executar

```bash
gcc batalha_naval_mestre.c -o mestre
./mestre
```
