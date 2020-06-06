<p align="center">
  <img src="https://antenas.s3.amazonaws.com/Logo.svg" alt="Logo do Projeto Antenas" />
</p>

<h1 align="center">Projeto Antenas</h1>

<p align="center">
    <a href="#equipe">Equipe</a> •
    <a href="#o-que-é-o-antenas">O que é o Antenas?</a> •
    <a href="#vida-de-um-projeto-no-antenas">Vida de um projeto</a> •
    <a href="#entregas">Entregas</a> •
    <a href="#tecnologia">Tecnologia</a>
</p>

---

## Equipe:
- [Danielly Jardim](https://github.com/daniellygj) _Dev_
- [Fábio Romeiro](https://github.com/FabioRomeiro) _Scrum Master_
- [Giovanna Xavier](https://github.com/giovannaxavierm) _Dev_
- [Mateus Machado](https://github.com/Mateusmsouza) _Dev_
- [Thiago Dias](https://github.com/ThiagoDisk) _Dev_

## O que é o Antenas?

O Antenas é uma **plataforma online para conectar a FATEC com as empresas do mercado** que desejam realizar projetos e recrutar alunos. Neste site o empresário cadastra seu projeto, e este é enviado para o [CADI (Centro de Apoio ao Desenvolvimento e Inovação)](https://fatecsjc-prd.azurewebsites.net/cadi.php), que o analisa, pede mais informações, e finalmente depois de uma reunião com o empresário, libera o projeto para um professor responsável poder aplica-lo com os seus alunos.

Esta abordagem proporciona ao aluno uma experiência mais próxima do que ele encontrará no mercado de trabalho quando sair da faculdade, uma vez que o projeto não esta sendo aplicado apenas por razões didáticas, mas sim para servir um cliente real.

Para saber mais, acesse o tópico [O que é o Antenas?](https://github.com/antena-dream-team/AntenasClient/wiki/Conceito#o-que-%C3%A9-o-antenas) na nossa wiki.


## Vida de um projeto no Antenas

<p align="center">
  <img src="https://antenas.s3.amazonaws.com/vida-projeto.svg" alt="Diagrama do fluxo do projeto" />
</p>


## Entregas

#### Entrega 1
- Planejamento da nova arquitetura do sistema
- Configuração inicial da API utilizando Spring Boot
- Configuração inicial e desenvolvimento dos primeiros componentes Vue do Front-end

#### Entrega 2
- Rotas essenciais (CRUD) da API construídas
- Persistencia da API no banco de dados MySQL
- Views da plataforma construídas no Front-end
- Componentes de formulário e gerenciamento de projetos criados no Front-end
- Sass configurado e estilos globais (reset.css, variaveis, funções, mixins, ...) criados no Front-end
- Implementação incial do CI na API utilizando CircleCI

#### Entrega 3
- Serviços de integração desenvolvido no front-end utilizando dados mockados
- CircleCI configurado para avisar membros pelo Telegram caso algum commit com falha nos testes unitários seja subido para o repositório remoto
- Sistema de autenticação utilizando Spring Security implementado

#### Entrega 4
- [Issue#2](https://github.com/antena-dream-team/AntenasClient/issues/2) - Deploy automatizado do front-end
- [Issue#5](https://github.com/antena-dream-team/AntenasService/issues/5) - Deploy automatizado da API


## Tecnologia

Foi optado por separa o projeto em dois grandes módulos:

- **AntenasClient**: Este repositório foi exclusivamente criado para servir a parte do front-end do projeto, isto é, a parte visual e a lógica necessária para apresentar ao usuário todas as informações que ele precisa ter acesso.

- **AntenasService**: Este repositório foi criado para servir a API do antenas, isto é, o local onde os dados entrados no sistema são processados e também a fonte de onde o AntenasClient busca as informações que aparecerão para o usuário final.

Para descobrir como executar o projeto ou explorar o código fonte, visite a página inicial de cada repositório:

- [Front-end (AntenasClient)](https://github.com/antena-dream-team/AntenasClient)
- [API (AntenasService)](https://github.com/antena-dream-team/AntenasService)

Para conhecer os pré-requisitos, tecnologias utilizadas e motivação para a refatoração geral do Antenas, visite a wiki de cada um dos repositórios:
- [Wiki do AntenasClient](https://github.com/antena-dream-team/AntenasClient/wiki)
- [Wiki do AntenasService](https://github.com/antena-dream-team/AntenasService/wiki)

---

<p align="center">
  <img src="https://antenas.s3.amazonaws.com/fatec-logo.png" alt="Logo do Projeto Antenas" width="150" />
</p>