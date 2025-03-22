# dio_nexa_aws_rekognition
AWS Rekognition - Detectando Celebridades em Imagens

# Projeto: Comparação de Faces com Amazon Rekognition

## Descrição
Este projeto utiliza o serviço Amazon Rekognition para comparar o rosto presente na imagem `neymar.jpg` com outras imagens armazenadas localmente. O objetivo é identificar similaridades entre o rosto do Neymar e as imagens alvo: `bale.jpg`, `bbc.jpg`, `cr7.jpg`, `messi.jpg` e `msn.jpg`.

## Funcionalidades
- Comparação de faces utilizando o serviço AWS Rekognition.
- Geração de resultados detalhados com as porcentagens de similaridade encontradas.
- Criação de imagens de saída com caixas delimitadoras e valores de similaridade sobrepostos.
- Salvamento automático de arquivos de resultado no formato `resultado_<nome_da_imagem>.jpg`.


## Tecnologias Utilizadas
- Python 3
- Amazon Rekognition (boto3)
- PIL (Python Imaging Library)
