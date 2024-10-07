# Vaga Desenvolvedor(a) PHP/WordPress Pleno

- **Vaga**: Programador(a) PHP / WordPress 
- **Modelo Híbrido**: 3 dias Home office/ 2 dias Presenciais
- **Local**: São Paulo SP ( ao lado Shopping Morumbi)
- **Contratação**: PJ


Empresa está em busca de desenvolvedores PHP com experiência comprovada em **PHP OO**, **WordPress** e **Criação de Plugins** 
(WordPress utilizando APIs: hooks, filters e  shortcodes). O profissional também deve ter experiência sólida no uso de **Git** para versionamento de código.

## 1. Requisitos para Participar

### Envio de Documentação
Para participar da seleção, siga as instruções abaixo:

- Envie seu currículo em formato PDF para o e-mail: **selecao@tonica.ag**
- **Assunto do e-mail**: SELEÇÃO WORDPRESS ID: S2T0-O2N4-I1C0-AP
- No corpo do e-mail, inclua uma **carta de apresentação** com:
    - Pretenção Salarial em R$/Mensal; 
    - A URL do seu perfil no GitHub;
    - A URL do repositório GitHub com os plugins criados para a seleção (nome do repositório: **skills-wordpress**).
    - **Respostas para as questões abaixo** (detalhadas na seção "Teste de Lógica na Carta de Apresentação").

## 2. Instruções para Teste de Aplicação para a Vaga (Criação dos Plugins)

A pessoa deve criar um repositório GitHub público nomeado **skills-wordpress** contendo três plugins que abordam as tarefas descritas a seguir.

### Estrutura de Pastas

O repositório deve seguir o padrão de pastas do WordPress. Cada plugin deve estar na sua respectiva pasta dentro da estrutura:

wp-content/plugins/nome-do-plugin-1
wp-content/plugins/nome-do-plugin-2
wp-content/plugins/nome-do-plugin-3

### Plugin 1: Adicionar Classe CSS a Elementos de Post
- **Tarefa**: Utilize um filtro para modificar o conteúdo dos posts, adicionando uma classe CSS (`custom-class`) a cada tag `<p>` presente no conteúdo do post.
- **Funções Usadas**: `add_filter()`, `the_content`.
- **Nome do Plugin**: Escolha um nome adequado e crie uma descrição clara.

### Plugin 2: Shortcode para Exibir Links Relacionados por Categoria
- **Tarefa**: Crie um shortcode que exiba uma lista de links para outros posts da mesma categoria, precedidos por um título `<h3>` com o texto "Mais Artigos". Os links devem estar em uma lista `<ul><li>`.
- **Funções Usadas**: WP_Query, funções nativas de categorias do WordPress.
- **Nome do Plugin**: Nome e descrição claros.

### Plugin 3: Configuração de URL do GitHub no Admin
- **Tarefa**: Adicione uma página no menu "Configurações" do admin do WordPress que contenha um campo para salvar a URL do perfil GitHub. Essa URL deve ser salva nas opções do WordPress e exibida como uma meta tag no head do site, com o formato:
  ```html
  <meta name="verify-skills" content="{url do perfil}">
  ```
- **Funções Usadas**: `API de opções` do WordPress, wp_head.
- **Nome do Plugin**: Nome e descrição claros.


## 3. Estrutura e Documentação dos Plugins

Cada plugin deve seguir as seguintes diretrizes:

Nome do Autor: Informar o nome do autor no cabeçalho do plugin.

Nome do Plugin: Nome apropriado no cabeçalho.

Descrição: Descreva o que o plugin faz.

Versão: Indicar a versão do plugin.

Dependências: Listar as dependências, como versão mínima do PHP e quaisquer extensões ou requisitos do servidor.


Exemplo de Cabeçalho do Plugin:
```php
/*
Plugin Name: Example Plugin
Plugin URI: https://github.com/username/example-plugin
Description: This plugin adds a custom class to all <p> tags in posts.
Version: 1.0
Author: Seu Nome
Author URI: https://github.com/username
Requires PHP: 7.4
*/
```

### Documentação:

Cada plugin deve conter um arquivo README.md em sua pasta com:

Descrição do plugin.

Instruções de instalação e ativação.

Instruções de configuração (se aplicável).

Funções PHP utilizadas.

Dependências e requisitos do servidor.

Seção Lógica e Aplicação:

Lógica: Explique o raciocínio por trás da implementação. Por que usou determinados hooks, funções, ou métodos? Como sua solução resolve o problema proposto?

Aplicação prática: Explique onde esse plugin poderia ser aplicado em projetos reais, como em blogs, sites de notícias, ou outros tipos de sites. Como isso melhora a experiência do usuário?




## 4. Teste de Lógica na Carta de Apresentação

Além de enviar a URL do GitHub e do repositório com os plugins, a pessoa deve responder as seguintes questões no corpo do e-mail.

- Qual a importância de utilizar versionamento com Git em projetos WordPress? Explique como o uso do Git impacta o fluxo de trabalho em uma equipe de desenvolvimento.


- Explique como você aplicaria o conceito de Shortcodes em um projeto real, além do exemplo solicitado no teste. Dê ao menos um outro caso de uso prático e justifique a escolha.


- Explique o conceito de hooks (ações e filtros) no WordPress e a diferença entre eles, mencionando exemplos de casos práticos em que utilizou ou utilizaria um.



## 5. Versionamento e Git

O repositório deve seguir boas práticas de versionamento com Git:

Commits: Use mensagens de commit claras e descritivas.

Git Log: A progressão dos commits será revisada para avaliar a organização do desenvolvimento.


## 6. Critérios de Avaliação

Os critérios de avaliação incluirão:

Qualidade do Código: Código limpo e organizado, uso de boas práticas em PHP e WordPress.

Documentação: Comentários no código e explicações claras em inglês (pode ser comentado em português).

Funcionalidade: Plugins funcionando conforme a especificação.

Raciocínio e Aplicação: Explicação lógica da solução proposta e a aplicação prática do plugin.

Versionamento: Uso adequado de Git e commit messages claras.
