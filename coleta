import requests

# URL da API e parâmetros
url = 'https://comicvine.gamespot.com/api/characters'
params = {
    'api_key': 'SUA_CHAVE_API',
    'filter': 'name:Batman,publisher:DC Comics',
    'sort': 'count_of_issue_appearances:desc',
    'format': 'json'
}

# Faz a solicitação GET
response = requests.get(url, params=params)

# Imprime o conteúdo da resposta
print(response.content)
