# Conjunto de Dados de Predição de Ataques Cardíacos  

## Descrição Geral  
Este conjunto de dados foi projetado para prever o risco de ataques cardíacos com base em variáveis clínicas e demográficas. Ele fornece uma ampla gama de características relevantes para a saúde do coração e escolhas de estilo de vida, abrangendo detalhes específicos dos pacientes, como idade, sexo, níveis de colesterol, pressão arterial, frequência cardíaca, entre outros. O conjunto culmina em uma importante característica de classificação binária que indica a presença ou ausência de risco de ataque cardíaco, sendo um recurso abrangente para análises preditivas e pesquisas sobre saúde cardiovascular.  

- **Fonte**: [Kaggle - Heart Attack Risk Prediction Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset/data)  
- **Arquivo**: `heart_attack_prediction_dataset.csv`
- **Arquivo Limpo**: `clean_dataset.csv`  
- **Linhas**: 8763  
- **Colunas**: 26  
- **Formato**: CSV  
- **Observação**: Dados coletados de diferentes regiões do mundo.  

## Estrutura da Tabela  

| Coluna                             | Tipo   | Descrição                                                              |
|------------------------------------|--------|-------------------------------------------------------------------------|
| `Patient ID`                      | object | Identificador único para cada paciente                                 |
| `Age`                             | Int    | Idade do paciente                                                      |
| `Sex`                             | object | Gênero do paciente (Masculino/Feminino)                                |
| `Cholesterol`                     | int    | Níveis de colesterol do paciente                                       |
| `Blood Pressure`                  | object | Pressão arterial do paciente (sistólica/diastólica)                   |
| `Heart Rate`                      | int    | Frequência cardíaca do paciente                                        |
| `Diabetes`                        | int    | Indica se o paciente tem diabetes (Sim/Não)                           |
| `Family History`                  | int    | Histórico familiar de problemas cardíacos (1: Sim, 0: Não)            |
| `Smoking`                         | int    | Status de tabagismo do paciente (1: Fumante, 0: Não fumante)          |
| `Obesity`                         | int    | Status de obesidade do paciente (1: Obeso, 0: Não obeso)              |
| `Alcohol Consumption`             | int    | Nível de consumo de álcool do paciente (Nenhum/Leve/Moderado/Excessivo) |
| `Exercise Hours Per Week`         | float  | Número de horas de exercício por semana                               |
| `Diet`                            | object | Hábitos alimentares do paciente (Saudável/Regular/Não saudável)       |
| `Previous Heart Problems`         | int    | Indica se o paciente teve problemas cardíacos anteriores (1: Sim, 0: Não) |
| `Medication Use`                  | int    | Uso de medicação pelo paciente (1: Sim, 0: Não)                       |
| `Stress Level`                    | int    | Nível de estresse relatado pelo paciente (1-10)                       |
| `Sedentary Hours Per Day`         | float  | Horas de atividade sedentária por dia                                 |
| `Income`                          | int    | Nível de renda do paciente                                            |
| `BMI`                             | float  | Índice de Massa Corporal (IMC) do paciente                            |
| `Triglycerides`                   | int    | Níveis de triglicerídeos do paciente                                  |
| `Physical Activity Days Per Week` | int    | Dias de atividade física por semana                                   |
| `Sleep Hours Per Day`             | int    | Horas de sono por dia                                                 |
| `Country`                         | object | País do paciente                                                      |
| `Continent`                       | object | Continente onde o paciente reside                                     |
| `Hemisphere`                      | object | Hemisfério onde o paciente reside                                     |
| `Heart Attack Risk`               | int    | Indica a presença de risco de ataque cardíaco (1: Sim, 0: Não)        |

## Valores Ausentes  
Não há valores ausentes no conjunto de dados.  

## Conteúdo dos Dados  
- **Distribuição de risco de ataque cardíaco**:  
  - 34% dos pacientes estão em risco de ataque cardíaco.  
  - 66% dos pacientes não estão em risco de ataque cardíaco.  
