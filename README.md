# Desafio--3

# Memorial de Robótica de Joinville

Protótipo acadêmico de um site para organizar e tornar acessível o histórico do Campeonato Joinvilense de Robótica.

> **Aviso:** este projeto foi desenvolvido como protótipo para o **Desafio 03 — Histórico Público do Evento**, no Hackathon ADS. Os nomes de equipes, escolas, estudantes, resultados, notícias e demais registros exibidos na demonstração são fictícios e não representam dados oficiais do campeonato.

## Sobre o projeto

Atualmente, informações históricas de eventos podem ficar distribuídas entre planilhas, pastas, arquivos digitais e documentos em papel. Essa dispersão dificulta a consulta pública, a atualização dos registros e a preservação da memória das competições.

O Memorial propõe um ponto único de consulta, organizado por edição, para reunir informações como ano do evento, equipes e escolas participantes, resultados e projetos de destaque. A proposta também considera um fluxo contínuo: pesquisar e conferir documentos de edições passadas e cadastrar as informações das próximas edições em um local centralizado.

## Funcionalidades demonstradas

- Página inicial com apresentação do memorial e destaques do campeonato.
- Navegação por edições e consulta de informações por ano.
- Demonstração de equipes, escolas, estudantes identificados por código e classificação.
- Busca por termos relacionados às edições e aos destaques.
- Filtros para localizar escolas, equipes e registros de participantes.
- Área de acessibilidade com controles de tamanho do texto, modo escuro, alto contraste e navegação por teclado.
- Integração prevista com o VLibras para tradução automática de conteúdo para Libras.
- Exemplo de apresentação de dados abertos em formato JSON.
- Registro visível de correções de informação no conteúdo de demonstração.

## Tecnologias

O protótipo é composto por uma página HTML com estilos CSS e JavaScript no próprio arquivo. A navegação entre seções é feita no navegador, por meio de rotas com fragmentos de URL. Não há backend, banco de dados ou sistema de autenticação implementado nesta versão.

O VLibras é carregado por meio de um script externo e, por isso, sua disponibilidade depende do acesso ao serviço e das condições de hospedagem e rede.

## Como executar

Não é necessário instalar dependências para visualizar a demonstração:

1. Clone ou baixe este repositório.
2. Abra o arquivo HTML principal diretamente no navegador.

Se preferir executar um servidor local na pasta do projeto, use, por exemplo:

```bash
python3 -m http.server 8000
```

Em seguida, acesse `http://localhost:8000` no navegador e abra o arquivo HTML principal, se ele não se chamar `index.html`.

## Estrutura de dados da demonstração

Os dados atualmente exibidos são gerados por estruturas JavaScript no próprio arquivo e são apenas ilustrativos. O protótipo também apresenta um exemplo de resposta JSON, mas isso não significa que exista uma API ou um arquivo de dados oficial conectado ao site.

Uma implementação futura pode separar os dados do código da interface e definir um processo de validação, armazenamento, publicação e atualização por edição. Os formatos JSON e CSV são possibilidades para facilitar consulta e reutilização dos dados.

## Fontes e atualização dos registros

Para reconstruir o histórico de edições anteriores, a proposta é consultar os materiais mantidos pela Prefeitura, incluindo planilhas, documentos, arquivos e registros em papel. Os dados deverão ser organizados e conferidos com as fontes responsáveis antes de sua publicação.

Para edições futuras, deverá haver uma pessoa responsável por enviar e cadastrar os dados de cada competição, como equipes, escolas, vencedores e projetos de destaque. A adoção de um fluxo definido de atualização ajuda a manter o memorial completo e confiável ao longo do tempo.

## Privacidade, imagens e autorizações

Como os participantes podem ser menores de idade, a publicação de informações deve respeitar a legislação aplicável, as orientações da Prefeitura e as autorizações necessárias das instituições e responsáveis.

Antes de publicar uma versão com dados reais:

- obtenha as permissões legais necessárias junto à Prefeitura e às escolas;
- publique apenas informações autorizadas e estritamente necessárias;
- não divulgue nomes, imagens ou outros dados pessoais de estudantes sem autorização adequada;
- confirme as autorizações para uso e compartilhamento de fotografias e vídeos;
- valide a precisão dos resultados e atribua fontes aos registros sempre que possível.

A demonstração usa códigos para representar estudantes e nomes fictícios para equipes e escolas. Esses exemplos não devem ser substituídos por dados reais sem o processo de autorização e validação apropriado.

## Acessibilidade

A proposta contempla controles de leitura e navegação, além da integração com o VLibras. A tradução automática pode apresentar erros e não substitui intérpretes humanos. Conteúdos importantes e atividades presenciais devem considerar, conforme o contexto, interpretação em Libras, legendas e avisos visuais.

Antes de uma publicação oficial, recomenda-se testar o site com pessoas com deficiência e revisar semântica, contraste, uso pelo teclado, textos alternativos e comportamento em dispositivos móveis.

## Limitações conhecidas

- O projeto é um protótipo acadêmico e não possui vínculo oficial com o Campeonato Joinvilense de Robótica ou com a Prefeitura.
- Os dados da interface são fictícios e simulados.
- A demonstração não está conectada a uma base de dados, API ou painel de administração.
- A busca e os filtros atuam somente sobre o conteúdo simulado disponível no navegador.
- A integração externa com o VLibras pode não carregar em ambientes que bloqueiem scripts externos.

## Próximos passos possíveis

1. Levantar e conferir os registros históricos com as fontes oficiais.
2. Definir responsáveis e um processo de aprovação para inclusão e correção de dados.
3. Estabelecer as autorizações necessárias para informações e imagens.
4. Planejar uma fonte de dados persistente e mecanismos de cópia de segurança.
5. Separar os dados da interface e implementar a atualização de novas edições.
6. Realizar testes de acessibilidade, usabilidade e segurança antes da publicação.
7. Publicar o site em ambiente autorizado, com informações atualizadas e revisadas.

## Contexto acadêmico

Projeto desenvolvido como proposta para o **Hackathon ADS — Desafio 03: Histórico Público do Evento**.

---

**Memorial de Robótica de Joinville** — uma proposta para organizar, consultar e preservar a história do campeonato.
