# GS-DYNAMIC 

## Firewatch – Sistema Inteligente de Combate a Queimadas Florestais

**Autores:**  
- Gabriel Borba (RM 553187)  
- Enzo Teles de Moura (RM 553899)  
- Pedro Henrique Mello Silva Alves (RM 554223)  

---

## 📖 Descrição

O **Firewatch** é um sistema integrado de detecção, alerta e combate a queimadas em áreas florestais, que combina IoT, drones autônomos e análise de dados para:

- Monitorar em tempo real sensores de temperatura, umidade e fumaça.  
- Priorizar incidentes críticos usando uma estrutura de heap (min-heap).  
- Rastrear histórico de ações dos drones com pilha (stack).  
- Gerenciar dinamicamente sensores com lista ligada (linked list).  
- Organizar zonas de monitoramento em árvore binária.  
- Otimizar rotas de drones usando grafos e algoritmo de Dijkstra.  

---

## 🚀 Funcionalidades Principais

1. **Leitura contínua de sensores IoT** (Queue)  
2. **Análise de risco** e classificação de alertas (Heap)  
3. **Simulação de patrulha aérea** por drones com histórico de ações (Stack)  
4. **Inclusão/exclusão de sensores em tempo real** (Linked List)  
5. **Zonação hierárquica de áreas florestais** (Árvore Binária)  
6. **Cálculo de rota ótima para combate** (Grafo + Dijkstra)  
7. **Relatórios** de operação com logs detalhados  

---

## 📂 Estrutura do Projeto
```
├── firewatch/
│ ├── sensors.py # Modelos de sensoriamento e fila de coleta
│ ├── alerts.py # Priorização e gerenciamento de alertas (heap)
│ ├── drones.py # Lógica de voo e pilha de ações
│ ├── zones.py # Árvores de zonas de monitoramento
│ ├── routing.py # Grafos e algoritmo de rota ótima
│ └── main.py # Ponto de entrada e loop de simulação
├── tests/ # Testes unitários das estruturas de dados
├── requirements.txt # Dependências do Python
└── README.md # Este arquivo
```

## ⚙️ Requisitos e Instalação

1. **Pré-requisitos**  
   - Python 3.8+  
   - pip  

2. **Instalação**  
   ```bash
   git clone https://github.com/seu-usuario/firewatch.git
   cd firewatch
   pip install -r requirements.txt

 ##🎬 Como Executar
python main.py
