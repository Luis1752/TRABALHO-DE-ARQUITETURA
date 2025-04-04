# 1. Máquina de Turing
![image](https://github.com/user-attachments/assets/7870c0a6-e1e7-4275-8e39-cbacf196ae29)

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

![image](https://github.com/user-attachments/assets/501fc221-ceae-4c52-bc12-933bf994951c)

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
---
---

## FONTE: 
#### 1. Máquina de Turing
Wikipedia (Visão geral e fundamentos teóricos):
https://pt.wikipedia.org/wiki/Máquina_de_Turing

Stanford Encyclopedia of Philosophy (Explicação técnica e conceitual):
https://plato.stanford.edu/entries/turing-machine/

MIT OpenCourseWare (Materiais acadêmicos sobre teoria da computação):
https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/

#### 2. Arquitetura de von Neumann
Wikipedia (Introdução e componentes básicos):
https://pt.wikipedia.org/wiki/Arquitetura_de_von_Neumann

Computer History Museum (Contexto histórico e evolução):
https://computerhistory.org/

TutorialsPoint (Explicação técnica simplificada):
https://www.tutorialspoint.com/computer_fundamentals/computer_von_neumann_architecture.htm

#### 3. Arquiteturas RISC e CISC
GeeksforGeeks (Comparação detalhada com exemplos):
https://www.geeksforgeeks.org/risc-and-cisc-architecture/

ARM Developer (Documentação oficial sobre arquitetura RISC):
https://developer.arm.com/

Intel Architecture Manuals (Detalhes sobre CISC/x86):
https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html

#### 4. Primeiros Computadores
Computer History Museum (Linha do tempo e fotos de máquinas antigas):
https://computerhistory.org/timeline/computers/

Wikipedia - História dos Computadores:
https://pt.wikipedia.org/wiki/História_do_computador

BBC - The Birth of the Computer (Documentário e artigos):
https://www.bbc.com/news/technology-18457719
