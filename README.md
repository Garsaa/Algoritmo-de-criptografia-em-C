# Algoritmo-de-criptografia-em-C
Algoritmo de criptografia simples utilizando ASCII, baseado no algoritmo RSA, em C

Eu optei por um algoritmo simples  usando ASCII, tendo como base o sistema de chave privada e chave pública do algoritmo de criptografia RSA.

Ele pega o texto digitado e o modifica caractere por caractere e após o criptografar e gera 2 chaves aleatórias para o texto. Guardando as chaves em arquivos separados e a string criptografada em outro arquivo  assim é possível fazer um controle linear para vincular a mensagem criptografada à suas chaves e cada 
descriptografia ser realizada com referência nas linhas dos arquivos e dessa forma, só será possível descriptografar cada texto com as suas respectivas chaves geradas no momento da criptografia. 

A mensagem descriptografada é exibida em letras maiúsculas.

O algoritmo usa como base a tabela ASCII-7, que foi desenvolvida tendo como base o inglês, ou seja, o programa não foi feito para criptografar ou descriptografar utilizando acentos.
