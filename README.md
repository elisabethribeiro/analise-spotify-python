# 🎧 Análise de Popularidade de Músicas no Spotify

## 📌 Sobre o projeto
Este projeto tem como objetivo analisar dados de músicas do Spotify para entender quais gêneros são mais e menos populares e quais características podem influenciar essa popularidade.

A análise foi feita utilizando Python, com foco em exploração de dados, visualização e interpretação dos resultados.

---

## 🎯 Objetivo
Identificar:
- Quais gêneros são mais populares
- Quais são menos populares
- Quais características musicais diferenciam esses grupos

---

## 📊 Dataset
- Ano: 2022
- Base de dados com aproximadamente 114 mil músicas
- 114 gêneros musicais diferentes
- Variáveis como:
  - Popularidade
  - Duração
  - Danceability
  - Energy
  - Acousticness
  - Valence

---

## 🛠️ Ferramentas utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧹 Etapas da análise

### 1. Exploração dos dados
- Verificação de tipos de dados
- Identificação de valores nulos e duplicados
- Análise inicial das variáveis

### 2. Limpeza dos dados
- Remoção de valores nulos
- Remoção de duplicados
- Padronização dos gêneros
- Criação da variável `duration_min`

### 3. Análise
- Cálculo da popularidade média por gênero
- Identificação dos Top 10 e Bottom 10
- Comparação das características musicais
- Análise da distribuição da popularidade
- Identificação de outliers na duração

---

## 📈 Principais análises

- Gêneros mais populares vs menos populares
- Comparação de características como:
  - Danceability
  - Energy
  - Acousticness
- Distribuição da popularidade das músicas
- Duração média e identificação de músicas muito curtas ou muito longas

---

## 🔍 Principais insights

- Gêneros mais populares tendem a ser mais **dançantes e energéticos**
- Gêneros menos populares apresentam maior **acousticness**
- A maioria das músicas possui baixa popularidade
- A duração média das músicas é de aproximadamente **3.8 minutos**
- Existem outliers com músicas muito curtas e muito longas

---

## 💡 Conclusão

Os dados indicam que músicas mais animadas e com maior energia tendem a ser mais populares no Spotify.
Por outro lado, gêneros mais específicos e com características mais acústicas parecem atingir um público menor dentro da plataforma.

---

## ⚠️ Limitações

- Não foi analisado como o Spotify calcula a popularidade
- O dataset pode não representar todos os gêneros de forma equilibrada


## 👩🏽‍💻 Autora
Elisabeth Aparecida Ribeiro  
Estudante em transição de carreira para a área de dados
