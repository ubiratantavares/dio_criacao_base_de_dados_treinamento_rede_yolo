# DIO - Desafio de Projeto - Criação de uma base de dados e treinamento da rede Yolo

Neste desafio de projeto foi desenvolvido o Notebook app.ipynb usado para treinar a rede YOLO usando transfer learning com a base de dados COCO. 

O Notebook app.ipynb foca em treinar duas novas classes e utiliza o YOLOv5 como base, que é popular por sua facilidade de uso e desempenho.

## Passo a passo do Notebook:

1. **Configurar o ambiente**: Instalar as dependências e clonar o repositório YOLOv5.

2. **Pré-processar os dados**: Fazer o download da base COCO, rotular as classes e criar datasets customizados.

3. **Configurar o treinamento**: Especificar os hiperparâmetros e classes no arquivo de configuração.

4. **Realizar o treinamento**: Usar transfer learning para treinar as novas classes.

5. **Avaliar o modelo**: Gerar métricas e fazer previsões para verificar o desempenho.

## Detalhes Importantes:

1. **Base de dados**: O script usa a base de dados COCO. Você pode rotular as classes adicionais com ferramentas como [Label Studio](https://labelstud.io/) ou [Roboflow](https://roboflow.com/).

2. **Transfer learning**: Os pesos pré-treinados do YOLOv5s são usados para acelerar o treinamento das novas classes.

3. **Avaliação**: A métrica mAP é usada para avaliar o desempenho do modelo.
