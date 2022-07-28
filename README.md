# Aula de Typescript da Take na plataforma DIO
  

## O que é o Typescript
É um superset do typescript que trás tipagem estática para a linguagem, além de outras features, com o propósito de melhorar a qualidade do código escrito e a sua usabilidade. Como é um superset o código compilado e usado em produção ainda é javascript, porém é um JS mais resiliente e turbinado graças ao uso de TS durante o desenvolvimento.

## Do que você vai precisar
Ferramentas necessárias:  
* Do Node instalado na sua máquina  
* Instalar o typescript usando o npm (npm install -g typescript)
    * É interessante que ele seja instalado de forma global, para que o usuário possa usar a biblioteca a qualquer momento e em qualquer projeto para fazer testes rápidos com o TS.
* De uma IDE como o visual studio code  

Requisitos técnicos:  
* Lógica de programação
* Mas é melhor ainda se tiver um conhecimento básico de javascript  

## Sobre a estrutura de commits  
Os commits foram feitos de tal forma que o usuário pode ler commit a commit em ordem de publicação e acompanhar gradualmente a criação do repositório e a lógica aplicada. É recomendado que o primeiro estudo seja feito dessa forma. Pequenos erros nos comentários ou de gramática podem ser encontrados no caminho (consequências do programador que estuda de madrugada), mas eles já foram devidamente corrigidos na última versão da main.

## Estrutura do repositório 
* *src* 
    * Contém arquivos com exemplos de uso de TS e JS comentados para facilitar o entendimento da ferramenta
* *desafios*
    * Contém vários arquivos JS que podem ser refatorados para solidificar o conhecimento adquirido na aula
* *index.html*
    * É onde está a chamada para o arquivo app.js e pode ser manipulado a vontade para testarem seus scripts
* *tsconfig.json*
    * O coração do TS que configura suas funcionalidades.  
* *package.json*
    * Nesse arquivo foram colocados alguns scripts com o propósito de facilitar a vida de quem usar esse repositório
        * start
            * Inicia o *lite-server*, que vai escutar modificações no index.html e em seus arquivos importados. É útil caso queira fazer testes no browser. A porta disposta normalmente é a *localhost:3000*
        * watch  
            * Roda o *tsc --watch* com o propósito de compilar constantemente qualquer coisa que for editada nos arquivos TS para sua contraparte em JS. Esse comando evita que *tsc* tenha que ser digitado constantemente para fazer a compilação.  


