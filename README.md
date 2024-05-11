# Projeto_Imersao_Alura_Google

# Projeto de Simplificação de Textos Técnicos

Este projeto consiste em uma aplicação desenvolvida em Python que utiliza a API do Google Generative AI para simplificar textos técnicos para uma linguagem mais acessível e compreensível para leigos no assunto.

## Funcionamento

O programa solicita ao usuário que escolha o grau de temperatura desejado para a simplificação do texto. A temperatura controla o quão criativa a geração de texto pode ser, variando de conservadora a altamente criativa. Após a escolha da temperatura, o usuário fornece o assunto e o texto técnico que deseja simplificar. O programa então utiliza o modelo de linguagem da API do Google Generative AI para gerar uma versão simplificada do texto, mantendo o significado original, mas utilizando palavras simples e evitando jargões.

## Como Executar

Antes de executar o programa, é necessário configurar uma chave de API do Google Generative AI. Esta chave deve ser inserida no arquivo de configuração `userdata`. Após configurar a chave de API, o programa pode ser executado em qualquer ambiente Python compatível.

```bash
python projeto_simplificacao_texto.py
```

## Requisitos

- Python 3.x
- Chave de API do Google Generative AI
