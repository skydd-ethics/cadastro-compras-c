# Sistema de Cadastro de Compras em C

Trabalho da disciplina **Programação de Software Básico em C (ARA0363)**.

Aplicação com interface gráfica (API do Windows, `windows.h`) para cadastrar compras com produto, quantidade e preço unitário. O programa calcula o total de cada compra, grava os registros no arquivo `aval1234.txt` e mostra todas as compras cadastradas com o total geral.

## Funcionalidades
- **Salvar compra**: valida os dados, calcula `total = quantidade * preco` e grava no arquivo, no formato `produto;quantidade;preco;total`.
- **Mostrar compras**: lê o arquivo linha a linha e lista os registros. No final, mostra o total acumulado e a quantidade de compras.
- **Limpar**: limpa os campos e a lista.

## Como executar
1. Abra o `cadastro_compras.c` no Embarcadero Dev-C++.
2. Compile e execute com **F11**.
