<div align="center">

# ADSET AI PRIMAVIA API 🚀

API de conversão de dados xlsx em jsonl, desenvolvida para facilitar o processamento e análise de dados veiculares.

</div>

## 📝 Descrição

A ADSET AI PRIMAVIA API permite a conversão de dados veiculares de formatos tabulares para o formato JSONL, otimizando o processamento e análise desses dados em sistemas de Machine Learning e bancos de dados.

## 🚀 Deploy com Docker

Para realizar o deploy da API usando Docker, siga os passos abaixo:

1. Clone o repositório:

```bash
git clone https://github.com/seuUsuario/adset-aiprimavia-api.git
cd adset-aiprimavia-api
Crie uma imagem Docker:
bash
Copy code
docker build -t adset-aiprimavia-api .
Execute o container:
bash
Copy code
docker run -dp 5000:5000 adset-aiprimavia-api
A API estará disponível em http://localhost:5000.

📦 Exemplo de Uso
Para enviar dados para a API, você pode usar o seguinte comando curl:

bash
Copy code
curl -X POST http://localhost:5000/upload \
-H "Content-Type: application/json" \
-d '{
    "data": [...],
    "assistant_id": "seu_assistant_id",
    "api_key": "sua_api_key"
}'
🛠 Tecnologias Utilizadas
Node.js
Express
Docker
OpenAI API
🤝 Contribuições
Contribuições são sempre bem-vindas! Para contribuir, por favor, faça um fork do repositório, crie uma branch para sua feature, faça commit das suas mudanças, e abra um Pull Request.

📝 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

<div align="center">
Feito com ❤️ por Guilherme Jansen

</div>
