# Aplicação First-app

Software criado para discutir os conceitos de criação de uma aplicação Web usando o Design Pattern Model-View-Controller, bem como o uso do Javascript tanto no cliente quanto no servidor.

## Requisitos da aplicação
- Para utilizar a aplicação você deve ter instalado o [NodeJs](https://nodejs.org/en/) em sua máquina.
- Tmabém será necessário possuir o git em sua máquina.

## Como fazer funcionar na sua máquina (Windows)
-  Após instalar o Node, utilizando seu terminal de preferência, clone este repositório:

>Lembre-se de estar em uma pasta que seja de fácil acesso, recomendo a sua pasta de usuário.

```bash
    git clone https://github.com/paulohgs/first-app2
```
- Entre no repositório e então instale as dependências presentes no projeto:

```bash
    cd first-app2
    npm install
```
- Com isso será possível executar a aplicação, seja para desenvolvimento ou produção:

```bash
    npm run dev # Para executar como desenvolvimento
    npm run prod # Para executar como produção
```
- Caso prefira por instalar cada dependência separadamente:

```bash
    # Para produção
    npm install -save ejs
    npm install -save express
    npm install -save express-ejs-layouts
    
    # Para desenvolvimento
    npm install -save-dev faker
    npm install -save-dev nodemon    
```

## Autor
- [Paulo Henrique Gomes da Silva](https://github.com/paulohgs)

## Colaboradores

- [Wellington Wagner F. Sarmento](https://github.com/wwagner33)
- [Mattheus Del Vianple](https://github.com/NovoVerso)
- [Mauro](https://github.com/MauroV27)

## Licença

Esta aplicação se encontra sob a licença Gnu [Public License Version 3.0](https://github.com/wwagner33/first-app2/blob/main/LICENSE). "The Software must floor".
