# Dijkstra Clássico x Dijkstra com Min-Heap

## 📋 Descrição do Projeto
Este projeto implementa e compara o desempenho de diferentes algoritmos para encontrar o caminho mais curto em grafos ponderados. Os algoritmos utilizados incluem:

- **Dijkstra**: Implementação tradicional com complexidade $O(V^2 + E)$.
- **Dijkstra com Min-Heap**: Versão otimizada utilizando uma estrutura de dados Min-Heap, com complexidade $O((V + E) \cdot \log(V))$.
- **Shortest_path (NetworkX)**: Implementação de referência utilizando a biblioteca `networkx`.

Além disso, o projeto mede o tempo de execução e as emissões de CO2 geradas por cada algoritmo, utilizando a biblioteca `codecarbon`.

---

## 🏗️ Estrutura do Notebook

### 1. **Geração de Grafos Aleatórios**
- O grafo é gerado com um número de nós definido pelo usuário e uma probabilidade fixa de conexão entre os nós.
- Apenas o maior componente conectado é utilizado.
- Pesos aleatórios (entre 1 e 10) são atribuídos às arestas.

### 2. **Criação de DataFrames**
- DataFrames são criados para armazenar os tempos de execução e emissões de CO2 para cada algoritmo.

### 3. **Implementação dos Algoritmos**
- **Dijkstra**: Implementação básica com listas.
- **Dijkstra com Min-Heap**: Utiliza uma estrutura de dados Min-Heap para otimização.
- **Shortest_path**: Implementação de referência utilizando a função `shortest_path` da biblioteca `networkx`.

### 4. **Medição de Desempenho**
- Para cada algoritmo, são medidos:
  - Tempo de execução.
  - Emissões de CO2 geradas.
- Os resultados são armazenados nos DataFrames correspondentes.

### 5. **Análise Estatística**
- Cálculo da média e desvio padrão dos tempos de execução e emissões de CO2 para diferentes tamanhos de grafos.
- Resultados são exportados para arquivos `.csv`.

### 6. **Visualização dos Resultados**
- Gráficos são gerados para comparar o desempenho dos algoritmos em termos de:
  - Tempo médio de execução.
  - Emissões médias de CO2.

---

## 🔧 Tecnologias Utilizadas

- **Python 3.13+**
- **NetworkX** - Manipulação e análise de grafos
- **Pandas** - Processamento de dados
- **Matplotlib** - Visualização de grafos 2D
- **Random** - Sequência e números aleatórios
- **Times** - Trabalhar com tempo
- **Codecarbon** - Rastrear e estimar o consumo de dióxido de carbono(CO2)
- **Gemini 2.5** - Intelingência Artifical
- **CopilotPRO** - Intelingência Artifical

---

## 🚀 Como Executar
1. Certifique-se de que todas as dependências estão instaladas.
2. Execute o notebook célula por célula.
3. Insira o número de nós quando solicitado.
4. Os resultados serão exibidos no notebook e salvos em arquivos `.csv`.

---

## 📊 Resultados Esperados
- Comparação clara entre os algoritmos em termos de eficiência e impacto ambiental.
- Gráficos que ilustram o desempenho dos algoritmos para diferentes tamanhos de grafos.

---

## 🔗 Links úteis

### 📚 Documentação das Bibliotecas
- [Python (site oficial)](https://www.python.org/) - Página oficial do Python
- [NetworkX Documentation](https://networkx.org/documentation/stable/) - Documentação oficial do NetworkX
- [Pandas Documentation](https://pandas.pydata.org/docs/) - Guia completo do Pandas
- [Matplotlib Documentation](https://matplotlib.org/stable/index.html) - Documentação e exemplos do Matplotlib
- [CodeCarbon GitHub](https://github.com/mlco2/codecarbon) - Repositório oficial do CodeCarbon (rastreio de emissões)
- [Random](https://docs.python.org/3/library/random.html) - Gerador de números pseudoaleatório
- [Time](https://docs.python.org/3/library/time.html) — Funções de tempo

### 📊 Teoria dos Grafos / Tutoriais
- [Graph Theory Tutorial (TutorialsPoint)](https://www.tutorialspoint.com/graph_theory/index.htm) - Tutorial básico de teoria dos grafos
- [NetworkX Tutorial](https://networkx.org/documentation/stable/tutorial.html) - Tutorial oficial do NetworkX
- [Graph Analysis with Python (DataCamp)](https://www.datacamp.com/tutorial/networkx-python-graph-tutorial) - Análise de grafos com Python

### 🎓 Recursos Acadêmicos
- [The Atlas for the Aspiring Network Scientist v2](https://www.springer.com/gp/book/9781846289699) - Livro sobre teoria dos grafos

### 💻 Ferramentas e Ambientes
- [Jupyter Notebook](https://jupyter.org/) - Ambiente interativo de desenvolvimento
- [Google Colab](https://colab.research.google.com/) - Ambiente online gratuito para notebooks
- [Anaconda](https://www.anaconda.com/) - Distribuição Python para ciência de dados
- [Visual Studio Code](https://code.visualstudio.com/) - Editor de código recomendado

---

## �📄 Licença

Este projeto foi desenvolvido para fins acadêmicos como parte da disciplina de **Algoritmos e Estruturas de Dados 2** do curo de Engenharia da Computação da UFRN ministrada pelo professor Ivanovitc Medeiros Dantes da Silva.

---

## 👥 Autor

- Lucas Marques e Leonardo Cavalcanti.
