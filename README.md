# Jogo Termo – C++
Projeto desenvolvido na disciplina de Algoritmos (1º período – Ciência da Computação).
Implementação em C++ de uma versão do jogo estilo Termo/Wordle, executado no terminal, utilizando leitura de arquivos e manipulação de matrizes de caracteres.

## Descrição
O programa:
Lê um arquivo contendo palavras da língua portuguesa
Filtra palavras com exatamente 6 letras
Seleciona aleatoriamente uma palavra secreta
Permite até 10 tentativas
Fornece feedback após cada jogada:
O → letra correta na posição correta  
X → letra existente na palavra, mas em posição incorreta  
_ → letra inexistente na palavra

## Conceitos Aplicados
Durante o desenvolvimento foram utilizados:
Manipulação de arquivos com ifstream
Matrizes bidimensionais de caracteres (char[][])
Estruturas de repetição (for)
Estruturas condicionais (if/else)
Geração de números aleatórios (rand)
Modularização com funções
Validação de entrada do usuário
Conversão de caracteres para minúsculo (tolower)
Uso de constantes com #define

## Importante
O arquivo palavras_da_lingua_portuguesa.txt deve estar no diretório correto conforme o caminho especificado no código.

## Funcionalidades Implementadas:
Carregamento de até 245.366 palavras
Filtro automático de palavras com 6 letras
Seleção aleatória da palavra secreta

## Validação
Apenas letras minúsculas
Palavra existente na base
Sistema de feedback por posição
Controle de tentativas

## Aprendizados
Este projeto fortaleceu principalmente:
Pensamento algorítmico
Organização modular
Manipulação de memória com arrays bidimensionais
Leitura e tratamento de arquivos
Validação e controle de fluxo
