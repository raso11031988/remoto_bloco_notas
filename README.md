# Automacao Bloco de Notas

Script Python que abre o Bloco de Notas automaticamente e digita um texto usando PyAutoGUI.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyAutoGUI](https://img.shields.io/badge/PyAutoGUI-green)
![Windows](https://img.shields.io/badge/Windows-gray)

## Sobre o projeto

Este script automatiza a abertura do Bloco de Notas via menu Iniciar do Windows e escreve um texto automaticamente, sem nenhuma interação manual.

## Pré-requisitos

- Python 3.x instalado
- Biblioteca `pyautogui`

## Instalação

```bash
pip install pyautogui
```

## Como usar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/automacao-bloco-de-notas.git
cd automacao-bloco-de-notas
```

2. Execute o script:

```bash
python automacao.py
```

> ⚠️ **Atenção:** após executar, você tem 5 segundos para tirar o cursor do caminho. O script assume controle do teclado e mouse automaticamente.

## O que o script faz

- Aguarda 5 segundos para você se preparar
- Abre o menu Iniciar e pesquisa pelo Bloco de Notas
- Abre o programa e digita o texto **"Projetinho"**

## Tecnologias

- [PyAutoGUI](https://pyautogui.readthedocs.io/) — controle de teclado e mouse

## Licença

MIT License — sinta-se à vontade para usar e modificar.
