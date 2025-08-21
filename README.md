# 🌆 Análise de Urbanização e Qualidade de Vida

Uma análise abrangente da relação entre urbanização e indicadores de qualidade de vida em diversos países, utilizando dados do Banco Mundial.

---

## 📊 Sobre o Projeto

Este projeto analisa dados de 25 países representantes de 5 regiões globais, examinando a correlação entre urbanização e indicadores-chave de qualidade de vida como saneamento, acesso à água potável, educação, PIB per capita e expectativa de vida.

---

## 🎯 Objetivos

- Analisar os níveis de urbanização por região e país
- Identificar correlações entre urbanização e qualidade de vida
- Descobrir países benchmark por região
- Detectar outliers (países com alta urbanização mas baixa qualidade de vida)
- Gerar insights estratégicos para políticas públicas

---

## 📋 Dados Utilizados

### Fontes de Dados
- **Banco Mundial**: API oficial com dados de 1990-2023
- **Indicadores**: 8 métricas-chave de desenvolvimento urbano

### Indicadores Coletados
- População Urbana (%)
- Crescimento População Urbana (%)
- Acesso a Saneamento Urbano (%)
- Acesso a Água Potável Urbana (%)
- Matrícula no Ensino Primário (%)
- Matrícula no Ensino Secundário (%)
- PIB per capita (US$)
- Expectativa de Vida (anos)

### Países Analisados
- **América Latina**: BRA, MEX, ARG, CHL, COL
- **África**: NGA, ZAF, EGY, KEN, GHA
- **Ásia**: CHN, IND, IDN, THA, VNM
- **Europa**: DEU, FRA, GBR, ESP, ITA
- **América do Norte**: USA, CAN

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas**: Manipulação e análise de dados
- **Matplotlib / Seaborn**: Visualizações gráficas
- **NumPy**: Cálculos numéricos
- **Requests**: Conexão com API do Banco Mundial

---

## 📁 Estrutura do Projeto

```
mb-urbanization-quality-life/
│
├── urbanization_analysis.py            # Script principal de análise
├── urbanization_quality_life_data.csv  # Dados completos (1990-2023)
├── urbanization_quality_life_avg.csv   # Médias por país
├── requirements.txt                    # Dependências do projeto
└── README.md                           # Documentação
```

---

## ⚙️ Instalação e Uso

1. **Clone o repositório**:
```bash
git clone https://github.com/seu-usuario/mb-urbanization-quality-life.git
cd mb-urbanization-quality-life
```

2. **Instale as dependências**:
```bash
pip install -r requirements.txt
```

3. **Execute a análise**:
```bash
python urbanization_analysis.py
```

---

## 📈 Principais Funcionalidades

### 🔍 Análise Descritiva
- Ranking de países por urbanização
- Identificação de tendências temporais
- Comparação entre regiões

### 📊 Visualizações
- Evolução temporal da urbanização por região
- Matriz de correlação entre indicadores
- Gráficos de dispersão (urbanização vs PIB)
- Comparativos regionais múltiplos

### 🎯 Insights Estratégicos
- Países benchmark por região
- Identificação de outliers
- Correlações entre urbanização e qualidade de vida
- Análise de melhoria temporal

---

## 📋 Resultados e Insights

### Principais Descobertas
- Correlação positiva entre urbanização e indicadores de qualidade de vida
- Padrões regionais distintos de desenvolvimento urbano
- Países com crescimento acelerado mas infraestrutura inadequada
- Progresso significativo em países emergentes na última década

### Países Referência por Região
- América Latina: [País benchmark]
- África: [País benchmark]
- Ásia: [País benchmark]
- Europa: [País benchmark]
- América do Norte: [País benchmark]

### 📊 Exemplos de Saída
O script gera:
- Relatórios executivos completos
- Visualizações gráficas interativas
- Arquivos CSV com dados processados
- Análises comparativas entre regiões
