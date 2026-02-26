# ED_Lista_Ordenacao
# Inventário Free Fire - Estrutura de Dados em C++

## 📖 Sobre o projeto
Este projeto foi desenvolvido como trabalho da disciplina **Estrutura de Dados em C++**.  
Ele simula um sistema de inventário inspirado no jogo Free Fire, permitindo inserir, remover, listar e buscar itens em duas estruturas diferentes:

- **Vetor (lista sequencial estática)**
- **Lista encadeada (dinâmica)**

## 🛠️ Funcionalidades
- Inserir itens na mochila
- Remover itens
- Listar todos os itens
- Ordenar (apenas no vetor, usando Bubble Sort)
- Buscar itens (binária no vetor, sequencial na lista)

## 🚀 Como compilar
Se estiver usando VS Code com os arquivos `tasks.json` e `launch.json`:
1. Pressione `Ctrl+Shift+B` para compilar.
2. O executável `main.exe` será gerado na pasta do projeto.

Ou manualmente no terminal:
```bash
g++ -g main.cpp -o main.exe