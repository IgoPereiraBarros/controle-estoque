# Controle de Estoque

## Como rodar o projeto ?

* Clone o repositório.
* Crie uma virtualenv com python 3.
* Ative a virtualenv.
* Instale as dependências.
* Rode as migrações.

```
git clone https://github.com/IgoPereiraBarros/controle-estoque.git
cd controle-estoque
python3 -m venv .venv
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```

# Teste dev

## Requisitos da solução
* Deve permitir o cadastro de novas mercadoria
* Deve ser registrado entrada e saída de mercadoria
* Preciso consultar o estoque de uma mercadoria e ver toda movimentação

## Observações: 
* A solução deve usar uma API em Django Rest Framework
Extra:
* Docker com um contêiner para cada aplicação
* Uso de NGINX 

## Avaliação:
Você deve publicar e enviar a URL da solução e acesso ao repositório GIT até dia 30/09/2019 - 08:00h.
* Analise da solução;
* Analise de código;
* Documentação e comentários de código; 
* Uso de ferramentas extra;
