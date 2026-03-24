# 🕹️ MIPS Assembly - Exercícios Avançados (PUC-SP)

Este repositório contém a segunda parte dos exercícios práticos de arquitetura de computadores desenvolvidos na PUC-SP. O foco destes scripts é a manipulação direta da memória e a implementação de algoritmos de processamento de dados em baixo nível.

### 🚀 Funcionalidades dos Exercícios

* **`ex1.asm` (Armazenamento em Memória):** Demonstra como realizar o armazenamento de dados utilizando um endereço base e deslocamento (*offset*).
* **`ex2.asm` (Processamento de Array):** Um algoritmo completo que percorre uma lista de 10 notas na memória para identificar:
    * A **maior** nota do conjunto.
    * A **menor** nota do conjunto.
    * A quantidade de **notas vermelhas** (abaixo de 5).

### 🛠️ Conceitos Técnicos Aplicados
* Gerenciamento de registradores e ponteiros de memória.
* Implementação de laços de repetição (`beq`, `j`).
* Lógica de comparação e desvios condicionais (`slt`).

### 🏁 Como Executar

Para rodar os arquivos `.asm`, você precisará do simulador **MARS**:

1.  **Download:** Baixe o simulador oficial aqui: [MARS v4.5](https://github.com/dpetersanderson/MARS/releases/tag/v.4.5).
2.  **Abrir Arquivo:** No MARS, vá em `File > Open` e selecione `ex1.asm` ou `ex2.asm`.
3.  **Montar (Assemble):** Clique no ícone da **Engrenagem** (ou pressione F3).
4.  **Executar:** Clique no ícone de **Play** verde. 
    * *Dica:* No `ex2.asm`, acompanhe a atualização dos registradores `$t5`, `$t6` e `$t7` para ver os resultados do processamento em tempo real.
