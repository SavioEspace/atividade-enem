# 📊 Análise de Dados Educacionais — ENEM (Simulado)

Este projeto apresenta uma análise exploratória de dados educacionais com base em um dataset simulado inspirado no ENEM, utilizando **Python e Pandas**.

O objetivo é identificar padrões de desempenho, desigualdades educacionais e possíveis fatores que impactam as notas dos estudantes.

---

# 🎯 Objetivos

- Explorar um dataset educacional com Pandas  
- Identificar padrões de desempenho entre estudantes  
- Comparar resultados entre escolas públicas e privadas  
- Avaliar diferenças regionais  
- Analisar a relação entre renda e desempenho acadêmico  
- Gerar interpretações com visão de negócio/educação  

---

# 📁 Estrutura do Dataset

O dataset contém as seguintes variáveis:

- `id_estudante` — identificador do estudante  
- `estado` — unidade federativa  
- `cidade` — cidade  
- `tipo_escola` — pública ou privada  
- `renda_familiar` — renda mensal  
- `nota_matematica`  
- `nota_linguagens`  
- `nota_ciencias`  
- `nota_humanas`  
- `nota_redacao`  
- `media_final` — média geral  

---

# 🔍 Análises Realizadas

## 📌 1. Exploração inicial
- Verificação de estrutura (`shape`, `columns`)
- Tipos de dados (`info`)
- Estatísticas descritivas (`describe`)
- Identificação de valores ausentes

---

## 🏫 2. Análise por tipo de escola
- Comparação entre escolas públicas e privadas
- Cálculo de médias por disciplina
- Avaliação de desempenho geral

---

## 🌎 3. Análise por estado
- Ranking dos estados com maior média
- Identificação de desigualdades regionais

---

## 🏆 4. Ranking dos estudantes
- Top 10 melhores alunos com base na média final

---

## 📚 5. Desempenho por disciplina
- Identificação das matérias com maior e menor desempenho médio

---

## 💰 6. Relação renda x desempenho
- Análise de correlação entre renda familiar e média final

---

# 🧠 Principais Insights

- Estudantes de escolas privadas tendem a apresentar médias mais altas  
- Existem diferenças significativas de desempenho entre estados  
- Algumas disciplinas apresentam maior dificuldade média  
- Há uma correlação positiva entre renda familiar e desempenho acadêmico  

---

# 📊 Conclusão

A análise evidencia desigualdades educacionais importantes, tanto por região quanto por tipo de escola e renda.

Esses resultados sugerem a necessidade de políticas públicas focadas em:
- redução da desigualdade educacional  
- investimento em escolas públicas  
- apoio a estudantes de baixa renda  

---

# 🛠️ Tecnologias Utilizadas

- Python  
- Pandas  
