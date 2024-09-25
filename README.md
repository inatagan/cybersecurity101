# cybersecurity101

Este projeto é dedicado a ensinar boas práticas de cybersecurity, baseado no [GithubPages](https://pages.github.com/) utilizando o tema [The Minimal theme](https://github.com/pages-themes/minimal)

### Usando o projeto localmente
Se você deseja excutar o projeto de forma local você deve:

1. Clonar este repositório:
```
    git clone https://github.com/inatagan/cybersecurity101.git
```
2. Adicione a seguinte configuração ao seu site `_config.yml`
```
    remote_theme: pages-themes/minimal@v0.2.0
    plugins:
    - jekyll-remote-theme # add this line to the plugins list if you already have one
```
3. Adicion a seguinte linha em seu arquivo `Gemgfile`
```
gem "github-pages", group: :jekyll_plugins
```
4. Na raíz do projeto execute o seguinte comando para instalar as dependências necessárias
```
script/bootstrap
```
5. Excute o comando a seguir para iniciar o servidor local:
```
bundle exec jekyll serve
```
6. Acesse em seu navegador o endereco `localhost:4000` para ver o site de forma local.

### Para mais configurações do tema por favor leia a documentação:
https://github.com/pages-themes/minimal

