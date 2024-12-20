# Trabalho de Aprendizado Profundo - PPGCC Unesp

Este repositório contém um trabalho realizado para a disciplina de **Aprendizado Profundo** do **Programa de Pós-Graduação em Ciência da Computação (PPGCC)** da **Unesp**, ministrada pelo **Prof. Dr. Denis Henrique Pinheiro Salvadeo**.

A disciplina aborda conceitos e técnicas avançadas de aprendizado de máquina, com ênfase em redes neurais profundas e suas diversas aplicações.

## Modelos Utilizados

Durante o desenvolvimento deste trabalho, foram utilizados os seguintes modelos de linguagem:

- **PolyCoder-160M**
- **Salesforce/codegen-350M-mono**
- **Llama 3.1**
- **GPT-2**
- **google-t5/t5-base**
- **gpt-neo-1.3B**

Estes modelos foram empregados em diferentes tarefas relacionadas ao processamento de linguagem natural, como geração de texto, tradução e análise semântica.

## Link para o Programa de Pós-Graduação em Ciência da Computação (PPGCC)

[Programa de Pós-Graduação em Ciência da Computação (PPGCC) da Unesp](https://www.unesp.br/ppgcc)


## Como Executar

Para rodar o projeto, siga os passos abaixo:

1. **Instale as dependências**:

    Execute o seguinte comando para instalar as bibliotecas necessárias:

    ```bash
    pip install torch transformers langchain rich bitsandbytes
    ```

2. **Faça login no Hugging Face**:

    Para acessar alguns dos modelos utilizados, é necessário estar logado no Hugging Face. Execute o seguinte comando e insira suas credenciais:

    ```bash
    huggingface-cli login
    ```

3. **Execute o chatbot**:

    Para rodar o chatbot, execute o seguinte comando:

    ```bash
    python chatbot.py
    ```


## Licença

Este repositório está licenciado sob a [Licença MIT](LICENSE).
