# Diário de Bordo — Projeto ATLAS

**Grupo:** Longe Demais do Himalaia  
**Instituição:** Universidade Cidade de São Paulo (UNICID)  
**Disciplina:** Desenvolvimento Front-End para Web  
**Professor:** Paulo Henrique  
**Período registrado:** primeira entrega de 04/10/2026 à integração final de 05/11/2026

## 1. Ideia inicial e planejamento

O ATLAS foi idealizado como um site de consulta sobre dez países. A proposta inicial era reunir diferentes assuntos em um único lugar, de forma semelhante a uma pequena enciclopédia digital. O visitante escolheria um país para acessar informações sobre cultura, história, gastronomia, natureza, arte e outros temas pesquisados pelo grupo.

A equipe escolheu o nome ATLAS e distribuiu os assuntos entre seus integrantes. Durante o desenvolvimento, chegou a ser considerada a possibilidade de adotar o nome NIMROD. Após a discussão, a decisão do grupo foi manter definitivamente **ATLAS**, pois o nome já representava a identidade e a proposta do site.

## 2. Organização da equipe e divisão dos conteúdos

Na distribuição inicial, a página principal e a integração visual ficaram sob a coordenação de **Welder**, enquanto os demais integrantes trabalharam nos conteúdos dos países. A divisão registrada pelo grupo foi:

| Integrante | Responsabilidade ou contribuição |
| --- | --- |
| Welder | Página inicial, integração, navegação, padronização visual e revisão do CSS |
| Kelvin | México; colaboração com o grupo em ajustes e revisões gerais |
| André | Grécia — participação na primeira etapa |
| Gustavo | Egito e pesquisa do orçamento de servidor e domínio |
| Alicia | Itália — participação na primeira etapa |
| Matheus | Canadá e continuidade da página da Itália |
| Gabriel | Alemanha |
| Maria Eduarda Almeida da Rocha | Suíça |
| Daniel | Austrália |
| Lucas | Japão e apoio em ajustes do CSS |
| Maria Eduarda Cabral | França |

Os créditos da primeira etapa foram preservados para reconhecer as contribuições de André e Alicia, mesmo depois da saída de ambos do grupo.

## 3. Primeira entrega — 04/10/2026

A primeira etapa concentrou-se na organização do conteúdo e na criação das páginas HTML. O grupo estruturou a página inicial com uma apresentação do tema, um mapa-múndi ilustrativo e links para os países. Também foram utilizadas tags semânticas, títulos, imagens e seções para organizar os assuntos.

A ideia inicial de um mapa interativo, com seleção direta de cada país, foi discutida e testada, mas sua implementação seria muito complexa para a fase do trabalho. Por isso, o grupo optou por manter o mapa como elemento visual e criar cartões de navegação. A decisão permitiu priorizar links funcionais e uma estrutura que pudesse ser ampliada na segunda entrega.

## 4. Mudanças no grupo e dificuldades encontradas

Após a primeira entrega, **André e Alicia se desligaram do grupo**. A mudança aconteceu quando o trabalho já estava em andamento, exigindo uma reorganização repentina das tarefas. Como o prazo era curto, não foi possível refazer completamente todos os conteúdos herdados. A página da Grécia, iniciada por André, foi mantida e integrada ao padrão visual, mas não houve tempo hábil para Kelvin realizar a atualização das informações dessa página. Kelvin continuou colaborando com o grupo em outras revisões e ajustes gerais. Matheus assumiu a continuidade da Itália, anteriormente iniciada por Alicia.

Outro desafio foi a disponibilidade de computadores. **Maria Eduarda Almeida da Rocha (Suíça)** e **Maria Eduarda Cabral (França)** não tinham computador próprio para desenvolver suas páginas em casa e precisavam utilizar os equipamentos da universidade. Isso dificultou a conciliação dos horários e o envio dos materiais.

**Daniel**, responsável pela Austrália, teve dificuldades na aplicação do CSS e na organização da estrutura da página. Welder prestou apoio para reorganizar o conteúdo e integrar os estilos sem descaracterizar o trabalho original. **Lucas**, responsável pelo Japão, também colaborou com ajustes de CSS e revisões do projeto.

## 5. Integração visual e evolução do CSS

Na segunda fase, o principal desafio foi reunir páginas feitas por diferentes pessoas sem que parecessem sites separados. **Welder coordenou a integração e a identidade visual**, mantendo a base azul-escura do ATLAS e adicionando detalhes específicos para cada país, como cores, bandeiras e imagens. As estruturas individuais foram preservadas sempre que possível, com correções pontuais de alinhamento, navegação e organização.

O grupo passou a utilizar **um único arquivo `css/style.css`**, compartilhado pelas páginas. Foram revisados os menus, cartões, títulos, rodapés, tabelas e ajustes para telas menores. No processo, Welder aprofundou o estudo de classes, caminhos relativos, Grid, Flexbox, variáveis CSS, bordas, gradientes e responsividade. A equipe utilizou documentação de HTML/CSS, testes práticos e consultas pontuais a ferramentas de IA para esclarecer dúvidas e comparar alternativas.

## 6. Atualização dos países, imagens e navegação

Os conteúdos foram sendo entregues em momentos diferentes, o que exigiu conferência de nomes de arquivos, caminhos das imagens e ligações entre as páginas. Canadá, Itália e Austrália receberam arquivos atualizados durante a integração. As fotografias dos cartões da página inicial passaram a representar os destinos, enquanto os Créditos receberam bandeiras em arquivos de imagem e links para as páginas correspondentes.

O grupo também criou o menu expansível **“Buscar no Atlas”**, que reúne os dez países e seus temas para facilitar a navegação. Na Austrália, os conteúdos de fauna, cidades, natureza e cultura foram organizados em blocos expansíveis, permitindo visualizar mais informações sem abrir uma nova página.

## 7. Identidade dos países e vídeos de transição

A partir de uma arte panorâmica com os países do projeto, a equipe desenvolveu a proposta de criar versões com destaque visual para cada destino. Foram produzidas dez animações em MP4, uma para cada país, com cenário temático, bandeira destacada e transições de entrada e saída em preto.

Na integração, o grupo testou a reprodução dos vídeos e corrigiu um problema de exibição da imagem antes do início da animação. Para manter a proposta sem JavaScript, as páginas utilizam uma transição intermediária com redirecionamento temporizado ao destino escolhido. O trabalho também recebeu um banner geral, reunindo referências visuais aos dez países, na página Sobre.

## 8. Evolução da proposta e orçamento

Além da função de consulta cultural, o ATLAS passou a apresentar uma proposta complementar de **exploração e planejamento de viagens**. A página “Orçamento e Contato” reúne um formulário inicial em que o visitante seleciona destino e informa dados de planejamento, além de uma seção de contato. Os campos utilizam validação HTML5. Essa etapa é demonstrativa e não realiza reservas, cálculos de preços ou busca automática de passagens.

Separadamente, a equipe preparou o **orçamento técnico de hospedagem web e domínio** exigido na disciplina. Gustavo ficou responsável pela pesquisa relacionada a esse orçamento. O relatório compara GitHub Pages, Cloudflare Pages e Hostinger, além de possibilidades de registro de domínio e custos associados, justificando uma solução compatível com um projeto acadêmico.

## 9. Revisão, publicação e conclusão do trabalho

Na etapa final, o grupo reuniu os materiais, revisou a consistência dos estilos, verificou os caminhos locais de links e imagens e organizou os documentos do projeto. O GitHub foi utilizado no versionamento e uma versão do site foi publicada no GitHub Pages, permitindo observar o funcionamento da navegação em ambiente web.

A versão integrada reúne a página inicial, dez páginas temáticas, as seções Sobre, Créditos e Orçamento e Contato, além dos vídeos de transição e do CSS compartilhado. O grupo manteve a diversidade dos conteúdos de cada integrante, mas construiu uma identidade visual única para o ATLAS.

O projeto foi concluído como resultado de trabalho coletivo, adaptação às mudanças da equipe, pesquisa, aprendizado técnico e revisões ao longo das duas entregas.
