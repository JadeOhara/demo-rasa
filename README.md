# demo-rasa

# 🤖 Rasa Bot + MyBinder Setup

Este repositório demonstra como executar um bot criado com o [Rasa](https://rasa.com/) diretamente no navegador usando o [MyBinder.org](https://mybinder.org/), sem necessidade de instalação local. Ideal para apresentações, testes rápidos e compartilhamento de projetos.
E salva-lo em seu GitHub para manter a memória das alterações realizadas.

---
## Requisitos do projeto

Para funcionar no [Binder](https://mybinder.org), o projeto precisa de:

1. Um repositório público no GitHub com seu projeto Rasa
2. Arquivos de configuração para ambiente:
   - `Dockerfile` **ou** `environment.yml` + `postBuild`
3. Um script que inicia o Rasa (em modo shell interativo ou HTTP)

---

## Rodando com Binder

Clique para abrir diretamente no navegador:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SEU_USUARIO/SEU_REPOSITORIO/HEAD?urlpath=lab/tree/start_rasa.ipynb)

> **Substitua `SEU_USUARIO` e `SEU_REPOSITORIO` pela URL real do seu GitHub do repositório criado para o rasa.**

> Copie o link do seu Binder para acessar posteriormente: [Esse Binder](https://mybinder.org/v2/gh/JadeOhara/demo-rasa/HEAD)

> Execute

##  Instalando o Rasa

1. Abra o terminal e use os comandos abaixo:

> pip install rasa
> rasa init
> *enter*
> Y
> N
> tar -czvf projetorasa.tar.gz *

2. *salvar o arquivo compactado que foi criado, descompactar e subir no repositório do GitHub*
