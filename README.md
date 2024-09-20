
# Web Scraper de Vagas de Emprego

Este é um projeto de Web Scraper desenvolvido em Python que coleta dados de vagas de emprego de um site de interesse (como Indeed, por exemplo). O projeto utiliza as bibliotecas BeautifulSoup, requests, e pandas para fazer scraping dos dados e salvar as informações em um arquivo CSV para análise futura.

## Funcionalidades

- Coleta de Dados de Vagas: Extrai informações como título da vaga, empresa, localização e uma breve descrição de cada vaga.
- Armazenamento em CSV: Os dados coletados são organizados em um arquivo CSV para fácil visualização e manipulação.
- Extensível para Outros Sites: O scraper pode ser adaptado para funcionar em outros sites com vagas ou outros tipos de dados.

## Tecnologias Utilizadas

- Python 3
- BeautifulSoup4 – Biblioteca para parsing de HTML e extração de dados.
- requests – Para fazer requisições HTTP e obter o conteúdo das páginas web.
- pandas – Utilizado para manipulação e exportação dos dados para arquivos CSV.

## Instalação

### Clone o repositório:

git clone https://github.com/seu-usuario/web-scraper-vagas.git

### Acesse o diretório do projeto:

cd web-scraper-vagas

### Instale as dependências necessárias:

pip install -r requirements.txt

### Como Usar

Modifique o URL de exemplo no código para o site que deseja fazer scraping. O URL está definido na variável job_url:

job_url = 'https://br.indeed.com/jobs?q=python+developer&l=S%C3%A3o+Paulo'

### Execute o script para iniciar a coleta de dados:

python scraper.py

### O arquivo CSV com os dados coletados será gerado na pasta do projeto:

vagas_emprego.csv

## Exemplo de CSV Gerado

**csv**

Título,Empresa,Localização,Descrição
"Python Developer","Tech Company","São Paulo, SP","Desenvolvimento de software em Python, APIs, e integrações com banco de dados..."
"Junior Python Developer","Startup","São Paulo, SP","Desenvolver soluções em Python para otimização de processos..."

## Possíveis Melhorias

- Paginação: Melhorar o scraper para navegar entre várias páginas de resultados.
- Suporte a Múltiplos Sites: Generalizar o código para funcionar com diferentes fontes de vagas.
- Filtros Personalizados: Adicionar filtros para coletar apenas vagas com certos critérios, como nível de experiência ou tipo de contrato.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir pull requests ou relatar issues.

## Licença

Este projeto está licenciado sob a MIT License.
