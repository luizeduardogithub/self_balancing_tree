# Árvore AVL em C

Este é um exemplo de implementação de uma Árvore AVL (Árvore Binária de Busca Balanceada) em linguagem C. A Árvore AVL é uma estrutura de dados de árvore binária que mantém o balanceamento automático para otimizar as operações de busca, inserção e exclusão.

## Compilação e Execução

Certifique-se de ter um compilador C instalado em seu sistema, como o GCC.

1. **Compilação:**

    Abra um terminal e navegue até o diretório contendo o código-fonte (arquivo .c). Use o seguinte comando para compilar:

    ```bash
    gcc arvore_avl.c main.c -o arvore_avl

    ```

2. **Execução:**

    Execute o programa usando o seguinte comando:

    ```bash
    ./arvore_avl

    ```

    O programa solicitará que você insira valores inteiros até que um valor negativo seja inserido, encerrando assim a entrada.

## Funcionalidades

O código possui as seguintes funcionalidades implementadas:

- Inserção de valores na Árvore AVL.
- Rotações para manter o balanceamento durante a inserção.
- Travessia pré-ordem para imprimir os valores após cada inserção.

## Estrutura do Código

O código é organizado da seguinte forma:

- `avl_tree.c`: Contém a implementação da Árvore AVL, incluindo funções de rotação, inserção e impressão.

- `struct node`: Definição da estrutura de um nó na árvore AVL, contendo valor, ponteiros para os filhos e altura.

- Funções auxiliares: `max`, `height`, `getBalance` são funções auxiliares usadas nas operações principais.

- `main`: Função principal que interage com o usuário, realiza a inserção e imprime a travessia pré-ordem.

## Contribuições

Contribuições são bem-vindas! Se encontrar bugs ou melhorias possíveis, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## Licença

Este projeto é distribuído sob a [Licença MIT](LICENSE).

