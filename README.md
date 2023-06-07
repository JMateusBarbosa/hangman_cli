# hangman_cli
OBJETIVO PRINCIPAL:
    - Permitir o usuário jogar "Forca" usando uma interface de texto.

REQUISITOS:
    ✅ - O usuário poderá selecionar um nível de dificuldade: 'fácil', 'normal', ou 'difícil'.

    ✅ - Selecionar uma palavra aleatoriamente a partir de um banco de palavras estático.

    ✅ - O tamanho da palavra selecionada variará com a dificuldade selecionada:
        ✅ - fácil: de 3 a 5 caracters
        ✅ - normal: 6-10 caracteres
        ✅ - dificil: mais de 10 caracteres

    ✅ - A quantidade de chances que o usuário terá para advinhar uma palavra completamente variará com
      o nível de dificuldade selecionado, sendo o valor arredondado de:
       ✅ - fácil: QUANTIDADE BÁSICA +2
       ✅ - normal: QUANTIDADE BÁSICA
       ✅ - difícil: QUANTIDADE BÁSICA -2

    ✅ - QUANTIDADE BÁSICA: 1.5 vezes a quantidade de caracteres unicos da palavra selecionada.
