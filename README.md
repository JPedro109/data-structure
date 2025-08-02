# Data Structure

### Array

- Complexidade de Inserção: O(n)
  Inserções no final de um array têm complexidade O(1) amortizada, mas inserções no início ou no meio exigem o deslocamento dos elementos, o que leva a uma complexidade O(n).

- Complexidade de Remoção: O(n)
  Remover um elemento no início ou no meio de um array exige o deslocamento dos elementos subsequentes, resultando em uma complexidade O(n).

- Complexidade de Leitura: O(1)
  Arrays permitem acesso direto a qualquer posição por índice, o que garante leitura em tempo constante.

- Alocação na Memória:
  Cada item do array é armazenado em posições consecutivas na memória. Isso permite acesso eficiente por índice, mas também significa que o array precisa de um bloco contíguo de memória, o que pode ser uma limitação em certos contextos. Em arrays dinâmicos, quando a capacidade é excedida, um novo array maior é alocado, e os elementos são copiados — essa operação tem complexidade O(n), mas ocorre esporadicamente
