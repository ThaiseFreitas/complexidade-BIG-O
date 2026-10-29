# Estrutura de Dados e Algoritmos

---

## 1. Complexidade Big O

```mermaid
graph TD
    Root[Complexidade Big O] --> Conceito[Conceito: Mede tempo e memoria conforme dados crescem]
    Root --> Notacoes[Notacoes]
    Notacoes --> Omega[Omega: Melhor caso]
    Notacoes --> Theta[Theta: Caso medio]
    Notacoes --> BigO[Big O: Pior caso]
    
    Root --> Tipos[Tipos de Complexidade]
    
    Tipos --> O1[O 1: Constante]
    O1 --> O1Desc[Mesma execucao independente dos elementos]
    
    Tipos --> On[O n: Linear]
    On --> OnDesc[Cresce proporcionalmente aos dados]
    
    Tipos --> OLogN[O log n: Logaritmica]
    OLogN --> OLogDesc[Entrada reduzida por etapa ex arvore binaria]
    
    Tipos --> On2[O n2: Quadratica]
    On2 --> On2Desc[Cresce com o quadrado dos elementos]
    
    Tipos --> O1N[O n log n: Linearitmica]
    O1N --> O1NDesc[Divide em partes e junta ordenadamente]
    
    Tipos --> O2n[O 2n: Exponencial]
    O2n --> O2nDesc[O trabalho dobra a cada novo elemento]
