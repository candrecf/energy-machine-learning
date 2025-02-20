# Sistema de Monitoramento Automático de Cargas Elétricas com Aprendizado de Máquina

## Descrição
Este projeto apresenta um sistema de baixo custo para monitoramento automático de cargas elétricas utilizando técnicas de **Aprendizado de Máquina**. O objetivo é permitir que consumidores tenham maior controle sobre o consumo de energia, possibilitando estratégias de eficiência energética.

O sistema utiliza o microcontrolador **ESP32** para coletar dados de sensores de corrente não intrusivos e aplica algoritmos de **Machine Learning**, como **KNN (K-Nearest Neighbors)** e **Árvore de Decisão**, para identificar e classificar os dispositivos em uso com base nos padrões de consumo.

## Tecnologias Utilizadas
- **Microcontrolador**: ESP32
- **Sensor de corrente**: Sensor não intrusivo (TC)
- **Conversor A/D**: ADS1115 (16 bits)
- **Linguagem de programação**: Python para análise dos dados
- **Algoritmos de Machine Learning**:
  - KNN (K-Nearest Neighbors)
  - Árvore de Decisão
- **Banco de dados**: Armazenamento local para treinamento e previsões

## Estrutura do Projeto
### Hardware
- ESP32
- Sensor de corrente não intrusivo (TC)
- Conversor A/D (ADS1115)
- Protoboard e resistores

### Software
- Coleta de dados de corrente
- Processamento de sinais
- Treinamento do modelo de Machine Learning
- Predição em tempo real do consumo elétrico

## Funcionamento
1. O ESP32 coleta dados do sensor de corrente.
2. Os dados são processados e armazenados para treinamento do modelo.
3. Algoritmos de Machine Learning identificam quais dispositivos estão ligados com base no padrão de consumo.
4. O sistema gera relatórios para otimização do consumo energético.

## Benefícios
- **Baixo custo**: Utiliza apenas um sensor de corrente para monitorar várias cargas.
- **Precisão**: Algoritmos de Machine Learning permitem alta acurácia na classificação dos dispositivos.
- **Eficiência energética**: Identifica desperdícios e possibilita economia de energia.
- **Monitoramento em tempo real**: Atualização contínua do consumo.

## Resultados
Os testes demonstraram que o sistema foi capaz de prever com **100% de precisão** os dispositivos conectados, utilizando uma matriz de confusão para validação.

## Comparativo de Custos
Comparado a sistemas tradicionais, o projeto demonstrou uma **redução de custos de até 62%**, pois elimina a necessidade de sensores individuais para cada carga elétrica.

## Conclusão
O sistema proposto é uma alternativa eficiente e acessível para monitoramento de consumo de energia, permitindo ao usuário um controle mais detalhado sobre seu uso de eletricidade e contribuindo para a sustentabilidade.

## Autores
- **Carlos A. da C. Fonseca** - [Email](mailto:c.andrecf@gmail.com)
- **David C. F. da Silva** - [Email](mailto:davidmrtkd@gmail.com)
- **Tiago M. Quirino** - [Email](mailto:tiago.quirino@estacio.br)

## Referências
- [Plano Nacional de Eficiência Energética (PNEE)](http://www.mme.gov.br/documents/36208/469534/Plano+Nacional+Eficiência+Energética+%28PDF%29.pdf)
- [Importância da medição de energia para a eficiência energética](https://docplayer.com.br/9698165-Importancia-da-medicao-de-energia-para-a-eficiencia-energetica.html)

