# Pandas W3Schools - Tutorial Completo de Pandas

Este repositório contém um tutorial abrangente sobre a biblioteca Pandas do Python, baseado nos conteúdos do W3Schools. O projeto é organizado em módulos progressivos, cobrindo desde os conceitos básicos até tópicos avançados como limpeza de dados, correlações e visualização.

## 📋 Visão Geral do Projeto

Este projeto foi desenvolvido para fornecer uma aprendizagem prática e estruturada da biblioteca Pandas, uma das ferramentas mais poderosas para análise de dados em Python. Cada módulo contém notebooks Jupyter interativos com exemplos práticos, exercícios e explicações detalhadas.

### 🎯 Objetivos de Aprendizagem
- Compreender os conceitos fundamentais do Pandas (Series e DataFrames)
- Aprender técnicas de limpeza e pré-processamento de dados
- Analisar correlações entre variáveis em datasets
- Criar visualizações de dados com Pandas
- Praticar através de exercícios e quizzes interativos

## 📁 Estrutura do Projeto

### 1. Pandas Tutorial
**Diretório:** `1.Pandas Tutorial/`

Este módulo introdutório cobre os fundamentos da biblioteca Pandas:

- **series.ipynb**: Introdução aos objetos Series do Pandas
  - Criação de Series a partir de listas e dicionários
  - Indexação personalizada
  - Acesso a elementos por índice

- **dataFrames.ipynb**: Conceitos fundamentais dos DataFrames
  - Criação de DataFrames a partir de dicionários
  - Indexação com `loc` e `iloc`
  - Leitura e escrita de arquivos CSV
  - Visualização de dados com `head()`

- **read_csv.ipynb**: Técnicas de leitura de dados
  - Importação de arquivos CSV
  - Manipulação de índices e colunas

- **read_JASON.ipynb**: Leitura de dados JSON
  - Carregamento de dados no formato JSON
  - Conversão para estruturas Pandas

- **analyzingDF.ipynb**: Análise exploratória de DataFrames
  - Estatísticas descritivas
  - Inspeção de estrutura de dados

**Arquivos de dados:**
- `data.csv`: Dataset de exemplo para demonstrações
- `dataW3S.csv`: Dados do W3Schools para exercícios
- `dataW3S.json`: Dados JSON para prática

### 2. Data Cleaning
**Diretório:** `2.Data Cleaning/`

Módulo dedicado às técnicas de limpeza e pré-processamento de dados:

- **cleaning_data.ipynb**: Visão geral das técnicas de limpeza
  - Identificação de problemas comuns em datasets
  - Estratégias para tratamento de dados inconsistentes

- **empty_cells.ipynb**: Tratamento de células vazias
  - Detecção de valores NaN
  - Técnicas de preenchimento e remoção

- **wrong_format.ipynb**: Correção de formatos incorretos
  - Conversão de tipos de dados
  - Padronização de formatos de data

- **wrong_data.ipynb**: Identificação e correção de dados incorretos
  - Detecção de outliers
  - Validação de dados

- **removing_duplicates.ipynb**: Remoção de duplicatas
  - Identificação de registros duplicados
  - Técnicas de deduplicação

**Arquivos de dados:**
- `dataForDC.csv`: Dataset com células vazias para prática
- `dataForDC2.csv`: Dataset com múltiplos tipos de problemas

### 3. Correlations
**Diretório:** `3.Correlations/`

Análise de correlações entre variáveis:

- **pandas_correlations.ipynb**: Método `corr()` do Pandas
  - Cálculo de correlações entre colunas
  - Interpretação dos coeficientes de correlação
  - Exemplos práticos com dados de exercícios físicos

**Arquivo de dados:**
- `dataCorr.csv`: Dataset com variáveis numéricas para análise de correlação

### 4. Plotting
**Diretório:** `4.Plotting/`

Visualização de dados com Pandas:

- **pandas_plotting.ipynb**: Técnicas de plotagem
  - Gráficos básicos com Pandas
  - Integração com Matplotlib
  - Visualização de séries temporais e distribuições

### 5. Quiz & Exercises
**Diretório:** `5.Quiz&Exercises/`

Materiais para avaliação e prática:

- **quiz.ipynb**: Questionário interativo
  - Teste de conhecimentos sobre Pandas
  - Questões de múltipla escolha

- **exercises.ipynb**: Exercícios práticos
  - Problemas aplicados aos conceitos aprendidos
  - Soluções passo-a-passo

- **certificate.ipynb**: Certificação
  - Avaliação final do aprendizado
  - Geração de certificado de conclusão

- **editor.ipynb**: Ambiente de prática
  - Editor interativo para experimentação
  - Espaço para escrever e testar código

- **study plan.ipynb**: Plano de estudos
  - Roteiro recomendado de aprendizagem
  - Metas e objetivos por módulo

- **syllabus.ipynb**: Conteúdo programático
  - Estrutura completa do curso
  - Tópicos cobertos em cada módulo

## 🚀 Como Usar

### Pré-requisitos
- Python 3.7 ou superior
- Jupyter Notebook ou JupyterLab
- Bibliotecas necessárias:
  - pandas
  - numpy
  - matplotlib (para visualizações)

### Instalação das Dependências
```bash
pip install pandas numpy matplotlib jupyter
```

### Executando os Notebooks
1. Navegue até o diretório desejado
2. Inicie o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Abra o notebook desejado (.ipynb)
4. Execute as células em ordem sequencial

### Ordem Recomendada de Estudo
1. Comece com `1.Pandas Tutorial/`
2. Prossiga para `2.Data Cleaning/`
3. Estude `3.Correlations/`
4. Explore `4.Plotting/`
5. Finalize com os exercícios em `5.Quiz&Exercises/`

## 📊 Exemplos de Código

### Criando uma Series
```python
import pandas as pd

# Criando uma Series simples
dados = [1, 7, 2]
serie = pd.Series(dados)
print(serie)
```

### Criando um DataFrame
```python
# Criando um DataFrame a partir de um dicionário
dados = {
    "calorias": [420, 380, 390],
    "duracao": [50, 40, 45]
}

df = pd.DataFrame(dados)
print(df)
```

### Calculando Correlações
```python
# Carregando dados e calculando correlação
df = pd.read_csv('dados.csv')
correlacao = df.corr()
print(correlacao)
```

## 🎓 Recursos Educacionais

- **Documentação Oficial**: [pandas.pydata.org](https://pandas.pydata.org/)
- **W3Schools Pandas**: [w3schools.com/python/pandas](https://www.w3schools.com/python/pandas/)
- **Exercícios Práticos**: Cada módulo contém exemplos aplicados
- **Quizzes Interativos**: Avaliação contínua do aprendizado

## 🤝 Contribuição

Este projeto é destinado ao aprendizado pessoal. Para sugestões ou correções, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## 📄 Licença

Este material é baseado no conteúdo educacional do W3Schools e está disponível para uso educacional.

---

**Desenvolvido para facilitar o aprendizado prático do Pandas através de exemplos interativos e exercícios aplicados.**
