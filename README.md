# Ongbook - Front End

Este repositório equivale aos trabalhos da ongbook respectivos ao front end.

## Sumário

- [Instalação](#instalação)
- [Como utilizar](#utilizando)
- [Suporte](#suporte)
- [Contribuição](#contribuição)

## Instalação

Faça o download do projeto ou faça um fork:

```
git clone https://github.com/Ongbook/front-oficial.git
cd front-oficial
```

## Utilizando

Baixe as dependências através do npm e bower:

```
npm install
bower install
```
Para subir o projeto utilize o http-server um servidor de sua preferência:

```
http-server
```

## Style Guide

Para manter-mos um padrão de código adequado entre os colaboradores, utilizamos
o style guide feito pelo John Papa para o Angular 1.x:

Tire uns 15 minutos para ler [Angular 1.x - John Papa](https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md#modules)

## Editor Config

Utilizamos o [EditorConfig](http://editorconfig.org) por padrão, mas sinta-se a vontade
para utilizar outra configuração.

## Sugestao das configuraçes para equipes

EditorConfig is awesome: http://EditorConfig.org

top-most EditorConfig file

root = true

Quebra de linhas
[*]
end_of_line = lf
insert_final_newline = true

Definindo charset
[*.{js,pug,html}]
charset = utf-8

Indentação via TAB, para pug e html
[*.{pug,html}]
indent_style = tab
indent_size = 4

Arquivos JS e CSS
[*.{js,css,styl}]
indent_style = tab
indent_size = 2

Demais arquivos importantes
[*.json]
indent_style = tab
indent_size = 2


## Suporte

[Abra uma issue](https://github.com/ongbook/front-oficial/issues) para bugs e novas features.
[Gitter](https://gitter.im/Ongbook) caso queira trocar uma idéia sobre o projeto ou dúvidas,
estão também disponíveis no Gitter.

## Contribuição

Para contribuir com o projeto utilize o fluxo [Github Flow](https://guides.github.com/introduction/flow/).
Existe um artigo na Medium explicando de forma simples e em portugês [Git Flow - Medium](https://medium.com/trainingcenter/git-da-necessidade-a-automa%C3%A7%C3%A3o-de-sua-release-parte-1-a9d697e8f9ee)
