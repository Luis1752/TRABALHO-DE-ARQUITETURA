# 1. Máquina de Turing

### Definição e Conceito
Criada por **Alan Turing** (1936) como um modelo teórico para entender os limites da computação. Representa um sistema formal capaz de simular qualquer algoritmo computacional.

### Componentes e Funcionamento
- **Fita infinita**: Dividida em células, cada uma contendo um símbolo (incluindo espaço em branco).
- **Cabeçote de leitura/escrita**: Lê e modifica símbolos na fita, movendo-se para a esquerda ou direita.
- **Tabela de estados**: Define as ações do cabeçote com base no estado atual e no símbolo lido.

### Importância
- **Tese de Church-Turing**: Qualquer problema computável pode ser resolvido por uma Máquina de Turing.
- Fundamenta a teoria da computabilidade e a ciência da computação teórica.

---

# 2. Arquitetura de von Neumann

### Origem
Proposta por **John von Neumann** (1945) no relatório "First Draft of a Report on the EDVAC".

### Principais Componentes
- **CPU (Unidade Central de Processamento)**:
  - **Unidade Lógica e Aritmética (ULA)**: Executa operações matemáticas.
  - **Unidade de Controle (UC)**: Gerencia a execução de instruções.
- **Memória Principal**: Armazena dados e instruções (conceito de programa armazenado).
- **Dispositivos de Entrada/Saída (E/S)**: Permitem interação com o usuário.
- **Barramento (Bus)**: Comunicação entre CPU, memória e periféricos.

### Características Principais
- Programas armazenados na memória (diferente da arquitetura Harvard, que separa dados e instruções).
- Execução sequencial de instruções (fetch-decode-execute).
- Base para quase todos os computadores modernos.

---

# 3. Arquiteturas RISC e CISC

## CISC (Complex Instruction Set Computer)

### Características
- Instruções complexas e variadas (uma instrução pode fazer várias operações).
- Menos instruções por programa, mas cada uma pode levar vários ciclos de clock.
- Uso de microcódigo para executar instruções.

### Vantagens
- Código mais compacto (menos linhas de assembly).
- Facilidade para programadores.

### Desvantagens
- Maior consumo de energia e complexidade de hardware.

## RISC (Reduced Instruction Set Computer)

### Características
- Instruções simples e padronizadas (executadas em um ciclo de clock).
- Maior número de registradores.
- Pipeline eficiente (execução paralela de instruções).

### Vantagens
- Maior desempenho e eficiência energética.
- Mais fácil de otimizar para compiladores.

### Desvantagens
- Códigos mais longos.

**Exemplos:** ARM (celulares), MIPS, RISC-V.

---

# 4. Primeiros Computadores

## Mark I (1944)
**Tipo:** Eletromecânico.

**Criador:** Howard Aiken (Harvard) e IBM.

### Características
- Usava relés e interruptores.
- Programação por fita perfurada.
- Lento (cálculos levavam segundos).

## ENIAC (1945)
**Tipo:** Eletrônico digital.

**Criadores:** John Mauchly e J. Presper Eckert (EUA).

### Características
- Usava válvulas termiônicas (18.000 válvulas).
- Consumia 150 kW de energia.
- Programação por recablagem física.
- Usado para cálculos balísticos na Segunda Guerra.

## Colossus (1943-1945)
**Tipo:** Eletrônico digital (britânico).

**Criador:** Alan Turing e equipe (Bletchley Park).

**Função:** Decifrar códigos dos nazistas durante a segunda guerra mundial (máquina Enigma).

### Características
- Usava válvulas (primeiro computador programável do mundo).
- Segredo militar até os anos 1970.

### Evolução
- **Década de 1950:** Transistores substituem válvulas.
- **Década de 1970:** Surgem os microprocessadores (Intel 4004, 1971).

---

# Conclusão

- **Máquina de Turing:** Conceito da computação.
- **Von Neumann:** Estrutura dos computadores modernos.
- **RISC vs CISC:** Dois modelos de processadores (simplicidade vs complexidade).
- **Primeiros computadores:** Máquinas gigantescas que evoluíram para os PCs atuais.

Esse resumo cobre os pontos essenciais com maior profundidade.
