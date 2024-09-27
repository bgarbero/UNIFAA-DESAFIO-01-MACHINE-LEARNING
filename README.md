# UNIFAA Desafio 01: Machine Learning

## Descrição do Projeto
Este projeto faz parte do Desafio 01 da disciplina de **Machine Learning** do curso da UNIFAA. O objetivo é prever se um indivíduo é fumante ou não (coluna `smoker`) com base em variáveis demográficas e de saúde.

## Contexto
O dataset utilizado contém as seguintes variáveis:
- **Sexo** (`sex`)
- **Idade** (`age`)
- **Índice de Massa Corporal (IMC)** (`bmi`)
- **Número de filhos** (`children`)
- **Região de residência** (`region`)
- **Custos com seguro de saúde** (`charges`)
- **Status de fumante** (`smoker` - variável alvo)

O modelo de machine learning tenta prever se um indivíduo é **fumante** ou **não fumante** com base nessas variáveis.

## Algoritmos Utilizados
### k-Nearest Neighbors (kNN)
O **kNN** classifica os dados com base nos vizinhos mais próximos.

### Naive Bayes
O algoritmo **Naive Bayes** faz suposições independentes entre as características, sendo particularmente eficaz em conjuntos de dados de alta dimensionalidade.

### Suporte a Vetores de Máquinas (SVM)
O **SVM** é utilizado para encontrar o hiperplano ótimo que separa as classes de forma mais eficiente, sendo útil em problemas de classificação como este.

### Comparação de Resultados
Ambos os algoritmos foram comparados com base em:
- Acurácia
- Precisão

## Objetivos do Desafio
1. Prever se um indivíduo é fumante ou não utilizando algoritmos supervisionados.
2. Avaliar a performance dos algoritmos.
3. Melhorar a acurácia dos modelos utilizando técnicas de pré-processamento como normalização.

## Estrutura do Projeto
1. **Preprocessamento dos dados**: Inclui limpeza dos dados e normalização das variáveis.
2. **Treinamento**: Modelos treinados com 80% dos dados.
3. **Teste e Avaliação**: Avaliação dos modelos com 20% dos dados restantes.
4. **Ajuste dos Modelos**: Ajuste de hiperparâmetros e comparação de resultados.

## Tecnologias Utilizadas
- [Orange Data Mining](https://orangedatamining.com/): Ferramenta usada para a construção dos modelos de machine learning.

## Como Utilizar
1. Clone o repositório:
   ```bash
   git clone https://github.com/bgarbero/UNIFAA-DESAFIO-01-MACHINE-LEARNING.git
2. Abra o Orange e carregue o projeto.
3. Execute a análise e compare os resultados entre os algoritmos.
4. Teste outros algoritmos e técnicas conforme necessário.

## Contribuições
Contribuições são bem-vindas! Se encontrar melhorias ou quiser adicionar funcionalidades, sinta-se à vontade para abrir um pull request.
