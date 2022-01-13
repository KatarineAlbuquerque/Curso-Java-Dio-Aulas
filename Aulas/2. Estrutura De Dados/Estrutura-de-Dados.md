#Estrutura de Dados
##Professor Bruno Dias

###Definição:

Um algoritmo estruturado de forma organizada e representado de várias formas.

###Estruturas Principais:

- Vetores/Matrizes (Arrays)
- Registro
- Lista
- Pilha
- Fila
- Árvore
- Tabela Hash
- Grafos

###Vetores/Matrizes (Arrays)

- variáveis do mesmo tipo

#####Vetor (Uni-dimensional)
#####Matriz (Mult-dimensional)

###Registro

- formato especializado
- mais de um tipo

Exemplo de Registro: Cliente

Tipos de Dados do Cliente, podendo ser diferente em outras empresas:

- nome
- cpf
- email
- telefone

Para acessar esses tipos, basta colocar um ponto (.), veja:

cliente.nome
cliente.cpf
cliente.email
cliente.telefone

###Listas

- ordem específica
- tamanho ajustável/flexível

Lembre-se que Arrays tem tamanhos fixos, já definidos.

####Há dois tipos de Listas:

- Ligada = Nó (índice) que conhece o próximo elemento.
- Duplamente Ligada = varia a lista ligada, fazendo navegação reversa (vice-e-versa)

###Pilhas

- acessa somente um item por vez
- restrita

####Tem dois Tipos:

- LIFO ou UEPS = O primeiro a entrar é o último a sair.
- FIFO ou PEPS = O primeiro que entra é o primeiro a sair.

#####LIFO ou UEPS:

Tem dois métodos:

- PUSH = ENTRA NA LISTA
- POP = SAI DA LISTA

#####FIFO ou PEPS:

Tem dois métodos:

- ENQUEUE = ENTRA NA LISTA
- DEQUEUE = SAI DA LISTA

###Filas

- possui regras para incluir e remover

Segue a teoria do FIFO.

#####1 , 2 , ... , n , n + 1

remover a partir do primeiro elemento (1) e insere no (n + 1)

###Árvores

- hierárquica
- facilita a busca

###Tabela Hash

- representada por chave/valor para pesquisas

###Grafos

- relaciona objetos através de arestas
- aceita qualquer tipo, devido ser relacionamentos de objetos
- Exemplo: Redes Sociais

