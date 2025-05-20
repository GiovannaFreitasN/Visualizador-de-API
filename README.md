# Visualizador de API

Um exercício feito com o objetico de criar um visualizador de APIs públicas que permite consultar diferentes serviços online: 
- **Consulta de CEP**: Busca informações de endereço pelo CEP brasileiro
- **Consulta de IP**: Mostra informações sobre o IP público
- **Piadas Aleatórias**: Retorna uma piada aleatória em inglês

## Instalação

1. Clone este repositório:
```bash
git clone https://github.com/GiovannaFreitasN/Visualizador-de-API
cd api-viewer
```

2. Crie um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

## Executando o Projeto

1. Inicie o servidor Flask:
```bash
python app.py
```

2. Acesse o navegador e abra:
```
http://localhost:5000
```

## Como Usar

- Na página inicial, você verá cards para cada API disponível
- Para a API de CEP, digite o CEP desejado no campo de texto
- Clique no botão "Consultar" para obter os resultados
- Os resultados serão exibidos em formato JSON abaixo do botão
