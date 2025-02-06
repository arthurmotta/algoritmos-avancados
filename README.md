<h1 style="border-bottom:none;" align="center">Estruturas de Dados e Algoritmos Avançados</h1>

<h3>📚 Sobre:</h3> 
Durante a disciplina, me aprofundei em estruturas de dados complexas, como Heaps e Tries, e explorei a manipulação de grafos para resolver problemas robustos. Além disso, desenvolvi algoritmos avançados, incluindo técnicas de otimização como algoritmos gulosos ("greedy"), que me permitiram abordar questões de otimização com eficiência e criatividade.  
  
<h3> 📂 O repositório está organizado em três TP's (Testes de Performance) e um Assessment Final. Aqui você encontrará:</h3> 

- **Códigos-fonte** dos algoritmos e estruturas de dados implementados.
- **Explicações detalhadas** sobre cada conceito abordado.
- **Exercícios práticos** resolvidos durante a disciplina como avaliação.

<div align="center"> <h1>Introdução a Heaps - TP1</h1> </div>

### **1. Introdução às Árvores**
- Na disciplina anterior, estudamos árvores binárias de busca, usadas para manter os dados ordenados.
- Agora, vamos estudar **heaps**, que são úteis para **priorizar elementos**, sem a necessidade de ordenação total.

### **2. Filas de Prioridade**
- Uma **fila de prioridade** processa elementos conforme sua **importância** (não necessariamente por ordem de chegada).
- Exemplo: **triagem médica** – pacientes são atendidos conforme a gravidade.
- Implementações possíveis:
  - **Array ordenado**: remoções rápidas (**O(1)**), mas inserções lentas (**O(N)**).
  - **Heap**: melhor eficiência geral para inserir e remover elementos.

### **3. O Que é um Heap?**
- **Heap binário**: tipo específico de árvore binária.
- Dois tipos:
  - **Heap máximo**: maior valor na raiz.
  - **Heap mínimo**: menor valor na raiz.
- Vamos focar no **heap máximo**.

### **4. Propriedades de um Heap**
- **Propriedade de Heap**: cada nó é maior (ou igual) que seus filhos.
- **Árvore Completa**: todos os níveis da árvore devem estar preenchidos, exceto o último, onde os nós devem estar o mais à esquerda possível.

### **5. Importância e Limitações dos Heaps**
- **Vantagem**: permite acessar rapidamente o maior valor (**na raiz**).
- **Limitação**: **não é eficiente para buscas** – heaps são apenas **parcialmente ordenados**.

## **Operações em Heaps**

### **1. Inserção em um Heap**
- **Passos do algoritmo**:
  1. Adicionar o novo valor na **próxima posição disponível** (como "último nó").
  2. Comparar o novo nó com seu **pai**.
  3. Se o valor for maior, **trocar com o pai** e repetir até restaurar a propriedade de heap.
- **Complexidade:** **O(log N)** (porque o novo nó pode subir no máximo até a raiz).

### **2. Remoção em um Heap**
- **Regra:** **Sempre removemos a raiz**.
- **Passos do algoritmo**:
  1. Substituir a raiz pelo **último nó**.
  2. Mover esse nó para baixo, trocando com o **filho de maior valor** até restaurar a propriedade de heap.
- **Complexidade:** **O(log N)** (porque o nó pode descer até a última camada).

### **3. O Problema do Último Nó**
- Para inserir ou remover elementos, precisamos **localizar o último nó**.
- O problema é que a raiz **não tem acesso direto** ao último nó.

### **4. Solução: Implementação com Arrays**
- Podemos armazenar o heap como um **array**, associando cada nó a um índice.
- **Vantagens**:
  - **Último nó** sempre será o **último índice do array** → acesso em **O(1)**.
  - Inserção e remoção ficam mais fáceis e eficientes.

### **5. Comparação Heap vs. Array Ordenado**
- **Array Ordenado**: inserção lenta (**O(N)**), remoção rápida (**O(1)**).
- **Heap**: ambas as operações são **O(log N)**, tornando-o a melhor escolha para filas de prioridade.

## **Conclusão**
- **Heaps** são fundamentais para **filas de prioridade**.
- **Inserção e remoção são eficientes**, pois utilizam **árvores completas**.
- **Implementar heaps com arrays** resolve o problema do último nó de forma eficiente.
- São **ótimos para priorização**, mas **não são eficientes para buscas**.

## **Estudo de Casos**
### **O código fonte das questões está disponível na pasta correspondente.**

1. **Definição de Heap como Árvore Binária Completa**  
2. **Ordenação Parcial em Heaps**  
3. **Operação de Inserção em um Heap**  
4. **Implementação da Função `eh_heap` para Verificação de Heap**  
5. **Complexidade da Função `eh_heap` (Big O Notation)**  
6. **Modificação da Classe Heap para Inicialização com um Array**  
7. **Criação de um Heap a Partir de um Array Específico**  
8. **Inserção de um Elemento no Heap**  
9. **Remoção do Nó Raiz do Heap**  
10. **Ordem de Remoção dos Elementos de um Heap**  
11. **Descrição de um Algoritmo de Ordenação Baseado em Heap**  
12. **Análise de Complexidade do Algoritmo de Ordenação HeapSort**  
13. **Implementação do Método `niveis` para Contar os Níveis do Heap**  
14. **Fila de Prioridade com Heap para Atendimento Hospitalar**  
15. **Fila de Prioridade com Array Ordenado**  
16. **Comparação de Complexidade entre Heap e Array Ordenado na Fila de Prioridade**  


#### **TP2**
- **

#### **TP3**
- **

#### **Assessment Final**
- **

<h3>🛠️ Ao longo dessa disciplina, as seguintes competências foram demonstradas:</h3>
  
- **Utilização de estruturas de dados como Heaps e Tries.**
- **Manipulação e aplicação de grafos (graphs) em problemas reais.**
- **Desenvolvimento de algoritmos avançados com grafos.**
- **Resolução de problemas utilizando algoritmos gulosos e outras técnicas de otimização.**

<div align="center">
  <br>
  <img src="./competencias-comprovadas.png" alt="Competências Comprovadas" width="850">
</div>


