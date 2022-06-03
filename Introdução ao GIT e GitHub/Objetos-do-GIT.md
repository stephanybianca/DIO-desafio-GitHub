# Objetos internos do GIT

O GIT armazena diferentes tipos de objetos em *.git/objects* .

### Blob (bolhas)

abreviação de “binary large object”.

- onde os arquivos ficam armazenados

- contém meta dados

- mostra o<u> tipo</u>, <u>tamanho</u> e <u>conteúdo</u>

### Tree (árvore)

-  contém uma ou mais entradas, sendo cada uma contendo uma referência **SHA-1**  para um  blob ou subtree 

- mostra o <u>modo</u>, <u>tipo</u> (geralmente é "blob" para um arquivo ou "tree" para um subdiretório) e <u> nome de arquivos associados</u>

### Commit (parente)

- objeto vai juntar tudo e dar sentindo as alterções realizadas

- aponta para uma arvore (tree) ou commit 

- mostra autor, mensagem, hora e data 

- também possui sha1



*SHA1* (Secure Hash Algorithm) - é um conjunto de funções hash criptografadas projetadas pela NSA. Gera um conjunto de caracteres de 40 digitos. Através dela podemos saber se o arquivo sofreu ou não alguma alteração. É uma formacurta de representar um arquivo.
