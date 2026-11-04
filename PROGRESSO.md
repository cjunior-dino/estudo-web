# Progresso dos estudos

Este arquivo é atualizado automaticamente pelo assistente ao final de cada
sessão de estudo e sincronizado entre os computadores por meio do GitHub. O
assistente não deve alterar os arquivos de código do estudante.

## Estado atual

- Módulo: fundamentos de HTML e funcionamento da web
- Capítulo da apostila: Capítulo 2 — HTML semântico
- Exercício atual: exercícios graduais 1 e 3 — completar a segunda seção e
  nomear/inspecionar a navegação
- Status: em andamento

## Conteúdos concluídos

- Responsabilidades básicas de HTML, CSS e JavaScript.
- Importância da `label` em campos de formulário.
- Noções iniciais de GET e POST.
- Unicidade do endereço de e-mail completo no banco de dados.
- Proteção de senhas por hash.
- Diferença entre autenticação e autorização.
- Finalidade básica do Handlebars na renderização de páginas.
- Diferença entre o título da aba (`title`) e o título visível (`h1`).
- Uso de `p` para parágrafos e de `ul`, `ol` e `li` para listas.
- Inspeção do arquivo `index.html` na guia Network do navegador.
- Estrutura semântica básica com `header`, `nav`, `main`, `section` e `footer`.
- Criação de links entre `index.html`, `cadastro.html` e `login.html`.

## Dificuldades e dúvidas

- Diferenciar corretamente as responsabilidades dos métodos GET e POST.
- Entender que a unicidade considera o endereço de e-mail completo.
- Separar proteção da senha durante o transporte e durante o armazenamento.
- Escolher a tag de lista adequada e estruturar seus itens.
- Diferenciar um arquivo aberto por `file://` de uma página servida por HTTP.
- Identificar a árvore de acessibilidade na guia Elements, em vez da guia
  Network.
- Dar um nome acessível ao elemento `nav` e evitar navegações aninhadas.

## Próximo passo

- Adicionar uma segunda `section` dentro de `main` no `index.html`.
- Manter somente um `nav` no cabeçalho e adicionar a ele
  `aria-label="Navegação principal"` nas três páginas.
- Abrir Elements > Accessibility, selecionar o `nav` e confirmar o papel
  `navigation` e o nome `Navegação principal`.
- Testar com Tab, Shift+Tab e Enter a navegação entre as três páginas.
- Material de apoio disponível: a apostila agora contém referências práticas
  ampliadas de HTML e CSS para consulta durante os exercícios.

## Histórico de sessões

### 2026-10-20 — Questionário diagnóstico inicial

- Conteúdo estudado: responsabilidades de HTML, CSS e JavaScript, labels,
  métodos HTTP, unicidade de e-mail, senhas, autenticação, autorização e
  Handlebars.
- Exercício realizado: respostas às sete perguntas do diagnóstico inicial.
- O que aprendi: GET solicita a leitura de recursos; POST envia dados para
  criação ou processamento; a unicidade considera o e-mail completo; senhas
  devem ser armazenadas como hash; autenticação identifica o usuário e
  autorização determina suas permissões.
- Dificuldades: conceitos de GET e POST, unicidade de e-mail e diferença entre
  transmissão segura e armazenamento seguro da senha.
- Próximo passo: reescrever as respostas 3, 4 e 5 e iniciar o Capítulo 1.

### 2026-10-22 — Capítulo 1 e inspeção no navegador

- Conteúdo estudado: diferença entre `head` e `body`, função de `title` e
  `h1`, parágrafos, listas e inspeção de recursos na guia Network.
- Exercício realizado: alteração dos títulos e inclusão de dois parágrafos;
  localização do `index.html` no Network com método GET e status 200.
- O que aprendi: `title` identifica a página na interface do navegador,
  enquanto `h1` apresenta o assunto principal no documento; `p` cria
  parágrafos, `ul` cria uma lista sem ordem e cada item usa `li`.
- Dificuldades: identificar a tag correta para a lista e compreender a
  diferença entre carregamento local por `file://` e uma requisição HTTP.
- Próximo passo: criar a lista de três metas, corrigir a meta viewport e
  inspecionar a estrutura resultante na guia Elements.
- Verificação posterior: o arquivo versionado da apostila não contém as
  referências práticas ampliadas de HTML e CSS. O registro anterior de que
  essas seções haviam sido adicionadas não correspondia ao documento atual.

### 2026-10-22 — Revisão de integridade da apostila

- Conteúdo revisado: estrutura, capítulos, exemplos, exercícios, paginação,
  acessibilidade e renderização completa da apostila.
- Verificação realizada: inspeção visual das 43 páginas e auditorias de
  títulos, seções e limites do conteúdo.
- Resultado: não foram encontrados cortes, sobreposições, comentários ou
  alterações rastreadas; a auditoria de acessibilidade não apontou problemas.
- Pendência encontrada: faltam as seções ampliadas de referência de HTML e
  CSS solicitadas anteriormente. O Capítulo 1 ainda não ensina listas antes do
  exercício que pede `ul` e `li`.
- Observação de diagramação: várias páginas têm grande área vazia devido às
  quebras entre capítulos e à continuação de exercícios.
- Arquivos preservados: nenhum código nem a apostila foram alterados nesta
  revisão; somente este registro de progresso foi atualizado.
- Próximo passo: continuar o exercício da lista e, mediante solicitação
  explícita, inserir e revisar as referências ampliadas na apostila.

### 2026-10-22 — Ampliação das referências de HTML e CSS

- Conteúdo adicionado: diferença entre tag, elemento e atributo; elementos HTML
  organizados por finalidade; atributos essenciais; seletores, cascata,
  especificidade, unidades, box model, tipografia, Flexbox, Grid,
  responsividade, estados, animações e variáveis CSS.
- Exemplos adicionados: lista de metas com `ul` e `li` e estilização completa de
  um formulário com CSS.
- Exercícios adicionados: consultas graduais para praticar HTML e CSS antes de
  prosseguir aos capítulos seguintes.
- Verificação realizada: revisão visual das 57 páginas e auditorias de
  acessibilidade, títulos, seções, limites, comentários e alterações
  rastreadas.
- Resultado: nenhuma sobreposição ou conteúdo fora da página; nenhuma falha de
  acessibilidade, comentário ou alteração rastreada foi encontrada.
- Arquivos preservados: nenhum arquivo de código foi alterado; somente a
  apostila e este registro de progresso foram atualizados.
- Dificuldades atuais: escolher a estrutura correta de lista e consolidar a
  diferença entre recursos locais abertos por `file://` e páginas servidas por
  HTTP.
- Próximo passo: concluir o exercício 2 do Capítulo 1 criando, por conta
  própria, uma lista não ordenada com três metas de estudo.

### 2026-11-03 — Revisão dos exercícios de HTML semântico

- Conteúdo estudado: regiões semânticas da página, links, nome acessível de uma
  navegação e árvore de acessibilidade do navegador.
- Exercício realizado: revisão somente por leitura de `index.html`,
  `cadastro.html` e `login.html`.
- O que aprendi: os links permitem circular entre as três páginas; o elemento
  `nav` cria uma região de navegação, mas precisa de um nome acessível claro
  quando inspecionado; a árvore de acessibilidade fica no painel Elements, não
  no Network.
- Resultado da revisão: exercício 1 parcialmente concluído, pois a página
  inicial possui apenas uma `section`; exercício 2 concluído; exercício 3
  pendente, pois os elementos `nav` ainda não têm `aria-label`.
- Dificuldades: localizar o painel Accessibility, distinguir a árvore DOM da
  árvore de acessibilidade e compreender a finalidade de `aria-label`.
- Arquivos preservados: nenhum HTML foi alterado pelo assistente.
- Próximo passo: o estudante deve remover o `nav` aninhado, adicionar uma
  segunda `section`, nomear a navegação nas três páginas e testar os links com
  Tab, Shift+Tab e Enter.

## Modelo para novas sessões

### AAAA-MM-DD — Título da sessão

- Conteúdo estudado:
- Exercício realizado:
- O que aprendi:
- Dificuldades:
- Próximo passo:

