--------------Maior comunidade conectada--------------
A maior comunidade conectada, em um contexto de redes sociais, se refere ao grupo de pessoas dentro de uma rede social que estão todas conectadas entre si de alguma forma. Nesse contexto, a conexão geralmente é representada por amizades ou relacionamentos entre as pessoas.


->Esse código lê uma rede de amizade a partir de um arquivo e encontra a maior comunidade ou (clique)conectada dentro da rede.
->Um clique é um subgrupo de pessoas onde todas são amigas em comum.

------Arquitetura------
-> O código utiliza uma estrutura de dados chamada `Pessoa` para representar cada usuário da rede social. Cada `Pessoa` tem:
->Um identificador único.
- >Um nome.
->Uma lista dinâmica de amigos.
->O número de amigos.


------Principais funções------
1.eh_clique: Função recursiva que verifica se um conjunto de pessoas forma um clique, terando sobre todos os pares possíveis de pessoas no conjunto. Se encontrar um par que não são amigos, retorna 0. Caso contrário, continua a verificação até confirmar que todas as pessoas no conjunto são amigas entre si, retornando 1 no final.
2.maior_rede_conectada: Função que encontra o maior clique na rede de pessoas.Para cada subconjunto, ela verifica se todas as pessoas nesse subconjunto são amigas entre si. Se encontrar um clique maior que o anteriormente registrado, ela atualiza o clique máximo.Finalmente, imprime o tamanho e os nomes das pessoas no maior clique.



------Decisões de Design------
->Estrutura de dados que armazenar pessoas e suas amizades.
->Utilização de alocação dinâmica para permitir listas de amigos de tamanho variável.
->Algoritmo importante para verificar e encontrar cliques na rede.

------Como utilizar o programa------
1-Compilar o programa/código
2-Criar arquivo dados.txt
3-Rodar o programa
4-Verificar a saída, onde exibirá a lista de amigos e maior comunidade


Integrantes do grupo: André Lucas, Beni Davi, Wemerson Miranda
