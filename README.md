Plataforma de Solicitações e Indicadores (PSI)

Este repositório contém os arquivos produzidos para o módulo de
Desenvolvimento Web com Frameworks e HTML/CSS, utilizando como base o
projeto corporativo da Plataforma de Solicitações e Indicadores (PSI).

A PSI faz parte do Projeto Integrador II e tem como proposta centralizar
o registro de solicitações internas relacionadas às automações, além de
consolidar indicadores operacionais e financeiros para apoio à tomada de
decisão.

## Objetivo do Projeto

Criar a interface inicial da PSI, contemplando:

-   Cabeçalho corporativo com logo, título e identificação do usuário;
-   Área de destaque com descrição do sistema e botões de ação rápida;
-   Cards com indicadores simulados (abertas, em andamento, concluídas e
    economia estimada);
-   Seções principais para acesso a registro, consulta e dashboards de
    solicitações;
-   Layout responsivo e organizado, preparado para evolução futura.

Nesta etapa, o foco está apenas no front-end (HTML + TailwindCSS), sem
integração com banco de dados.

## Tecnologias Utilizadas

-   **HTML5** -- estrutura semântica da página;
-   **CSS3** -- estilização complementar;
-   **TailwindCSS** -- framework utilitário para construção rápida da
    interface;
-   **VS Code** -- ambiente de desenvolvimento;
-   **Git e GitHub** -- versionamento e documentação do projeto.

## Estrutura do Repositório

    /
    ├── index.html    # Interface principal da plataforma
    ├── img/          # Pasta com logos e recursos visuais
    └── README.md     # Documento de apresentação do projeto

## Visão Geral da Interface

A tela inicial da PSI apresenta:

-   **Cabeçalho**: logo, nome da plataforma e identificação do usuário
    logado;
-   **Seção de destaque**: título principal, descrição do sistema e
    botões "Nova solicitação" e "Ver indicadores";
-   **Painel de indicadores**: cards com quantidades de solicitações
    abertas, em andamento e concluídas, além de barras representando a
    economia estimada pelas automações;
-   **Ações principais**: três blocos que simulam as funcionalidades de
    nova solicitação, consulta e dashboards.

## Exemplo de Código (trecho do header)

``` html
<header class="bg-slate-900 text-white py-4 shadow-md">
  <div class="max-w-6xl mx-auto px-4 flex items-center gap-4">

    <img
      src="img/logo_plataforma.png"
      alt="Logo PSI"
      class="w-16 h-16 object-contain"
    />

    <div class="flex flex-col leading-tight">
      <h1 class="text-xl md:text-2xl font-semibold">
        Plataforma de Solicitações e Indicadores
      </h1>
      <p class="text-sm text-slate-300">
        Centralização de demandas e dados de automação
      </p>
    </div>

  </div>
</header>
```

## Melhorias Futuras

-   Integração com banco de dados;
-   Autenticação de usuários;
-   Dashboard dinâmico com gráficos reais;
-   Cadastro e consulta completa de solicitações;
-   Sistema de prioridade e categorias.

## Autor

**João Victor de Souza Santos**

Discente -- UFMS Digital
Curso: Tecnologia da Informação

## Licença

Este projeto é de uso acadêmico e não possui finalidade comercial.
