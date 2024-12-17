# Previsão de Receitas Futuros com Machine Learning

## 📋 Descrição do Projeto
Este projeto utiliza técnicas de **Machine Learning** para prever receitas futuras com base em dados históricos e variáveis explicativas, como investimentos em marketing. O objetivo é explorar métodos de aprendizado supervisionado para criar um modelo eficiente e confiável para tomadas de decisão financeiras.

## 🔍 Metodologia
1. **Preparação dos dados**:
   - Dados fictícios foram criados para simular receitas e investimentos ao longo dos anos.
   - Limpeza e normalização de dados.
2. **Exploração dos dados**:
   - Visualizações gráficas para entender as tendências e relações entre variáveis.
3. **Treinamento e avaliação de modelos**:
   - Comparação entre os modelos de **Regressão Linear** e **Random Forest Regressor**.
   - Avaliação de métricas como:
     - Erro Absoluto Médio (MAE).
     - Erro Quadrático Médio (MSE).
     - Coeficiente de Determinação (R²).
4. **Escolha do modelo final**:
   - O modelo **Random Forest Regressor** foi selecionado como o mais eficiente.

## 📈 Resultados
| Modelo            | MAE   | MSE     | R²    |
|------------------|--------|---------|-------|
| Linear Regression | 4.20  | 28.84   | 0.99  |
| Random Forest     | 4.02  | 21.37   | 0.99  |

O modelo Random Forest apresentou melhor desempenho nas métricas avaliadas, sendo utilizado para as projeções finais.

## 🔧 Ferramentas Utilizadas
- **Linguagem**: Python
- **Bibliotecas**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## 🚀 Possibilidades de Melhorias
1. Adicionar mais variáveis explicativas, como custos e tendências econômicas.
2. Ajustar os hiperparâmetros do modelo Random Forest para otimizar resultados.
3. Implementar validação cruzada para maior robustez do modelo.
4. Utilizar bases de dados reais para aplicações práticas.

## 📂 Estrutura do Repositório
- `modelo_projeção_receitas.ipynb`: Notebook com todo o código e explicações do projeto.
- `README.md`: Apresentação e explicação do projeto.

## 📝 Como Utilizar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu_usuario/projeto_projecao_receitas.git
