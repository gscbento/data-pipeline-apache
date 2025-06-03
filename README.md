# Projeto: Pipeline de Dados de API para Data Lake com Apache NiFi
## Objetivo
Criar um fluxo de dados que:
- Consulta periodicamente uma API pública (ex: dados climáticos, financeiros ou de COVID).
- Faz transformações no dado (limpeza, filtragem, enriquecimento).
- Salvar os dados no formato CSV ou JSON em um Data Lake (ex: AWS S3, GCP Cloud Storage, ou localmente).

(Opcional) Envia um alerta por e-mail ou Slack quando certos critérios forem atendidos.

Ferramentas
Apache NiFi
API REST pública (por exemplo, OpenWeather, Brasil.IO, ou CoinGecko)
Destino: armazenamento local, Amazon S3, ou Google Cloud Storage
Processadores comuns: InvokeHTTP, ExtractText, ConvertRecord, PutFile, PutS3Object, RouteOnAttribute, UpdateAttribute
