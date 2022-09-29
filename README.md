<h1 id="top" align="center">Robot Framework Exemplo</h1>

<p align="center">
  <img alt="Tamanho do repositório" src="https://img.shields.io/github/repo-size/cauachagas/robot-framework-exemplo?color=56BEB8">
  <img alt="Licença" src="https://img.shields.io/github/license/cauachagas/robot-framework-exemplo?color=56BEB8">
  <img alt="Github issues" src="https://img.shields.io/github/issues/cauachagas/robot-framework-exemplo?color=56BEB8" />
  <img alt="Github forks" src="https://img.shields.io/github/forks/cauachagas/robot-framework-exemplo?color=56BEB8" />
  <img alt="Github stars" src="https://img.shields.io/github/stars/cauachagas/robot-framework-exemplo?color=56BEB8" />
</p>


<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-pré-requisitos">Pré requisitos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Começando</a> &#xa0; | &#xa0;
  <a href="#memo-licença">Licença</a> &#xa0; | &#xa0;
  <a href="https://github.com/cauachagas" target="_blank">Autor</a>
</p>

<br>

## :dart: Sobre ##

Repositório para rodar um exemplo básico com o Robot Framework.


## :rocket: Tecnologias ##

As seguintes ferramentas foram usadas na construção do projeto:

- [Python](https://www.python.org/)
- [Robot Framework](https://robotframework.org/)
- [ChromeDriver](https://chromedriver.chromium.org/)


## :white_check_mark: Pré requisitos ##

Antes de começar :checkered_flag:, você precisa ter o [Git](https://git-scm.com) e o [Python](https://www.python.org/) instalados em sua maquina. Para utilização de automação web com Selenium no navegador Chrome, será preciso do [ChromeDriver](https://chromedriver.chromium.org/downloads) no [PATH](https://www.linkedin.com/pulse/como-instalar-o-chromedriver-windows-10-jo%C3%A3o-gross/?originalSubdomain=pt) 


## :checkered_flag: Começando ##

```bash
# Clone este repositório
$ git clone https://github.com/cauachagas/robot-framework-exemplo

# Entre na pasta
$ cd robot-framework-exemplo

# Crie uma ambiente virtual
$ python -m venv venv

# Ative o ambiente virtual
$ ./venv/Scripts/activate (Para Linux ./venv/bin/activate)

# Instale as dependências
$ pip install -r requirements.txt

# Para iniciar o projeto
$ robot .

# O app irá gerar alguns arquivos, como report.html
```

## :memo: Licença ##

Este projeto está sob licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


Feito com :heart: por <a href="https://github.com/cauachagas" target="_blank">Cauã Chagas</a>

&#xa0;

<a href="#top">Voltar para o topo</a>
