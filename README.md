mindmap
  root((Algoritmos de Busca))
    Busca Linear
      Conceito
        Varredura sequencial item a item do inicio ao fim
      Complexidade
        Pior caso On e Melhor caso O1
    Busca Linear Otimizada
      Conceito
        Interrompe a busca ao ultrapassar o valor em listas ordenadas
      Complexidade
        Pior caso On e Melhor caso O1
    Busca Binaria
      Requisito
        Exige estrutura de dados previamente ordenada
      Funcionamento
        Divisao e conquista reduzindo a busca pela metade
      Complexidade
        O log n - Altamente eficiente
      Limitacao
        Incompativel com listas encadeadas sem acesso direto
    Busca por Interpolacao
      Conceito
        Estima a posicao provavel com base na distribuicao
    Grafos - Dijkstra
      Objetivo
        Encontra o caminho de menor custo em grafos
      Restricao
        Suporta apenas pesos nao negativos
    Grafos - Bellman Ford
      Objetivo
        Caminho minimo em grafos
      Diferencial
        Suporta arestas com pesos negativos
    Hash - Tabela de Espalhamento
      Funcionamento
        Mapeia uma chave K diretamente para um indice de memoria
      Colisao
        Ocorre quando chaves diferentes geram o mesmo indice
      Area de Overflow
        Zona reservada para armazenar colisoes de forma sequencial
