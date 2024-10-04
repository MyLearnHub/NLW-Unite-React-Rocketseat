<p align="center">
  <img width="100px" src="assets/logo.png" align="center" alt="Pass.In Logo" />
</p>

<p align="center">
  <a href="#">Português</a> · <a href="/docs/README_EN.md">English</a>
</p>

# 🔍Índice <!-- omit in toc -->
- [Tecnologias](#tecnologias)
- [Visão Geral](#visão-geral)
- [Guia de Instalação](#guia-de-instalação)
- [Como Usar o Projeto?](#como-usar-o-projeto)
- [Recursos Adicionais](#recursos-adicionais)
  - [Design](#design)
  - [Ferramentas](#ferramentas)
  - [Linguagens e Pacotes](#linguagens-e-pacotes)

# 💻Tecnologias
  <div align="center">
    <img src="https://iconsverse.vercel.app/icons?i=react,ts,nodejs,postgres,prisma">
  </div>

# 📝Visão Geral
O pass.in é uma aplicação de **gestão de participantes em eventos presenciais**,

A ferramenta permite que o organizador cadastre um evento e abra uma página pública de inscrição.

Os participantes inscritos podem emitir uma credencial para check-in no dia do evento.

O sistema fará um scan de credencial do participante para permitir a entrada no evento.

# 📖Guia de Instalação
Siga as etapas abaixo para configurar e executar o Pass.in em seu ambiente local, o processo pode ser mais fácil com uma ferramenta de edição de texto avançada como o Visual Studio Code:

1. Usando o git bash clone este repositório:
   ```
   git clone https://github.com/Paulo-Alvares/Pass.In.git
   ```
   
2. Navegue até o diretório do projeto:
   ```
   cd pass.in
   ```

3. Instale as dependências:
   ``` 
   npm i
   ```

4. Inicie o servidor de desenvolvimento:
   ``` 
   npm start
   ```

5. Acesse o Pass.in em seu navegador:
   ```
   http://localhost:3333
   ```
   
# 💡Como Usar o Projeto?
## Requisitos

### Requisitos funcionais

- [x] O organizador deve poder cadastrar um novo evento;
- [x] O organizador deve poder visualizar dados de um evento;
- [x] O organizador deve poder visualizar a lista de participantes;
- [x] O participante deve poder se inscrever em um evento;
- [x] O participante deve poder visualizar seu crachá de inscrição;
- [x] O participante deve poder realizar check-in no evento;

### Regras de negócio

- [x] O participante só pode se inscrever em um evento uma única vez;
- [x] O participante só pode se inscrever em eventos com vagas disponíveis;
- [x] O participante só pode realizar check-in em um evento uma única vez;

### Requisitos não-funcionais

- [x] O check-in no evento será realizado através de um QRCode;

## Anotações

Métodos HTTP: GET, POST, PUT, PATCH, DELETE, PATCH, HEAD, OPTIONS, ...

Corpo da requisição (Request Body)
Parâmetros de busca (Search Params / Query Params) `http://localhost:3333/users?name=Diego`
Parâmetros de rota (Route Params) -> Identificação de recursos `DELETE http://localhost:3333/users/5`
Cabeçalhos (Headers) -> Contexto

Semânticas = Significado

Driver nativo / Query Builders / ORMs

Object Relational Mapping (Hibernate / Doctrine / ActiveRecord)

JSON - JavaScript Object Notation

20x => Sucesso
30x => Redirecionamento
40x => Erro do cliente (Erro em alguma informação enviada por QUEM está fazendo a chamada p/ API)
50x => Erro do servidor (Um erro que está acontecendo INDEPENDENTE do que está sendo enviado p/ o servidor)

# 🔗Recursos Adicionais
### 🎨Design
  - <a href="https://www.figma.com/community/file/1356738933008624188/pass-in">Protótipo</a>

### 🔧Ferramentas
  - <a href="https://code.visualstudio.com/download">Visual Studio Code</a>
  - <a href="https://www.figma.com/">Figma</a>

### 📦Linguagens e Pacotes
  - <a href="https://nodejs.org/en/download/package-manager">Node</a>

# 📬Contato
<div align="center"> 
  <a href = "mailto:pauloalvares66@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/paulo-alvares/"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> 
  <a href="https://www.instagram.com/paulo_10111/"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
  <a href="https://www.facebook.com/paulogabriel.alvares"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"></a>
  <a href="https://codepen.io/Poulos-Alvares"><img src="https://img.shields.io/badge/Codepen-000000?style=for-the-badge&logo=codepen&logoColor=white"></a>
</div>