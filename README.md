# Árvores Binárias de Busca (BST) — Estruturas de Dados 2 — UNIPÊ

Trabalho em dupla da disciplina **Estruturas de Dados 2** (Prof. Edkallenn) — **Tema 4: Árvores Binárias de Busca (BST)**.

## Integrantes
- Leandro Estrela
- Luis Henrique

## Vídeo
- [Link do vídeo no YouTube/TikTok/Kwai]

## O que a implementação faz
Árvore Binária de Busca de inteiros, sem valores repetidos, com:
inserção, busca, remoção (folha, um filho, dois filhos), percursos (pré-ordem, em ordem, pós-ordem),
altura e exibição visual no terminal.

## Estrutura
```
src/
  No.java          -> nó da árvore (valor, esquerdo, direito)
  ArvoreBST.java   -> operações da BST
  Main.java        -> demonstração (valores 50, 30, 70, 20, 40, 60, 80)
```

## Como compilar e executar (Java 11 ou superior)
```bash
cd src
javac *.java
java Main
```
(No Windows, se o terminal mostrar acentos errados: `chcp 65001` antes de executar.)
