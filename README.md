# Smart Distribution of Sustainable Products

## 🧭 Visão Geral

Este projeto aplica teoria dos grafos, algoritmos gulosos e programação dinâmica para otimizar a implantação de estações de recarga de veículos elétricos (EV) e rotas de entrega de kits médicos móveis em três cidades. Utilizando dados geoespaciais, densidade populacional, localização de EVs e áreas de risco, o sistema visa melhorar a infraestrutura urbana e a saúde pública de forma sustentável.

## 🚀 Funcionalidades

* **Análise Geoespacial**: Mapeamento das redes viárias urbanas e identificação de locais-chave.
* **Otimização Baseada em Grafos**: Modelagem das cidades como grafos para alocação eficiente de recursos e planejamento de rotas.
* **Algoritmos Eficientes**: Aplicação de técnicas de algoritmos gulosos e programação dinâmica para alocação de recursos e roteamento.
* **Visualizações Interativas**: Geração de mapas interativos e diagramas de grafos para análise visual.

## 🛠️ Como Começar

### Pré-requisitos

* Python 3.8 ou superior
* Jupyter Notebook
* Bibliotecas necessárias: `osmnx`, `networkx`, `folium`, `geopy`, `graphviz`, `numpy`, `pandas`, `matplotlib`

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/AliceSBulhoes/Smart-Distribution-of-Sustainable-Products.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd Smart-Distribution-of-Sustainable-Products
   ```

3. Instale as dependências:

   ```bash
   pip install osmnx networkx folium geopy graphviz numpy pandas matplotlib
   ```

## 🧠 Metodologia

* **Modelagem de Grafos**: Utiliza o OSMnx para criar grafos urbanos, onde os nós representam interseções/locais e as arestas representam ruas.
* **Algoritmos Gulosos**: Priorização de áreas de alta densidade populacional ou alto risco para a implantação de estações de recarga de EV. [Simulado]
* **Programação Dinâmica**: Otimização das rotas de entrega de kits médicos para minimizar distância e tempo.
* **Cálculos Geoespaciais**: Cálculo de distâncias com `Geopy` e visualização com `Folium`.
* **Monitoramento de Desempenho**: Acompanhamento do uso de memória com `tracemalloc`.

## 📊 Resultados Esperados

* **Estações de Recarga de EV**: Localizações otimizadas, visualizadas em mapas interativos do `Folium`.
* **Rotas de Entrega de Kits Médicos**: Caminhos de entrega eficientes, apresentados como sequências de grafos e mapas.
* **Visualizações**:  mapas interativos com `Folium` para análise.
* **Métricas**: Cobertura de área, tempo de viagem e desempenho computacional.


