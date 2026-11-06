# ATLAS — Um mundo para explorar

Projeto acadêmico desenvolvido pelo grupo **Longe Demais do Himalaia**, na disciplina **Desenvolvimento Front-End para Web** da **UNICID**, com orientação do professor **Paulo Henrique**.

O Atlas começou como um site informativo sobre dez países: cada integrante pesquisou um tema e desenvolveu uma página. Na segunda fase, o grupo reuniu os trabalhos em uma identidade visual comum e acrescentou recursos de navegação e uma área inicial de planejamento de viagens.

**Site publicado:** [Atlas no GitHub Pages](https://wellsdevx.github.io/Atlas_Project/). A versão publicada pode não conter as alterações mais recentes do arquivo ZIP.

## Países e temas

| País | Tema |
| --- | --- |
| México | Música e mitologia |
| Grécia | Gastronomia |
| Egito | Monumentos históricos |
| Itália | História e patrimônio |
| Canadá | Natureza e biomas |
| Alemanha | Guerras e impactos políticos |
| Suíça | Turismo e oportunidades profissionais |
| Austrália | Biodiversidade |
| Japão | Evolução das artes visuais |
| França | Museus, artistas e moda |

## Páginas e funcionalidades

A página inicial apresenta o projeto, um mapa ilustrativo e cartões para os dez países. A página Sobre inclui um banner panorâmico com referências visuais aos dez destinos. Cada página tem conteúdo e organização próprios, mas compartilha cabeçalho, menu, rodapé e o mesmo arquivo de CSS. Há ainda as páginas **Sobre**, **Créditos** e **Orçamento e Contato**.

- **Buscar no Atlas:** menu expansível de países e temas. É uma navegação interna, não uma pesquisa por palavras digitadas.
- **Créditos clicáveis:** as bandeiras e os nomes dos países levam ao conteúdo correspondente.
- **Conteúdo expansível:** a página da Austrália usa os elementos HTML `<details>` e `<summary>` para organizar seus temas.
- **Transições em vídeo:** ao escolher um país, o visitante passa por um MP4 de aproximadamente 3,6 segundos, que destaca o destino. As páginas intermediárias utilizam um redirecionamento HTML após quatro segundos. É um tempo fixo, que pode não coincidir com a reprodução em conexões lentas.
- **Planejamento de viagens:** o formulário permite selecionar destino, cidade, pessoas e noites, com validações HTML5. Ainda não calcula valores, pesquisa passagens ou efetua reservas.
- **Contato:** formulário demonstrativo com campos validados em HTML5. Não envia mensagens nem armazena as respostas.

## Tecnologias utilizadas

- **HTML5:** estrutura das páginas, links, formulários, imagens e vídeo.
- **CSS3:** identidade visual, cores de cada país, Flexbox, Grid e adaptação às larguras de tela.
- **MP4:** dez animações de transição.
- **Git e GitHub Pages:** versionamento e publicação de uma versão do site.

O projeto está organizado **sem JavaScript**, com um único arquivo de estilos em `css/style.css`. Alguns pequenos ajustes visuais específicos estão diretamente no atributo `style` do HTML.

## Organização dos arquivos

```text
Atlas_Project/
├── index.html
├── sobre.html
├── creditos.html
├── orcamento.html
├── README.md
├── paginas/                 # Dez conteúdos de países
├── transicoes/              # Dez páginas de entrada animada
├── css/
│   └── style.css             # Folha de estilos compartilhada
├── img/                     # Imagens e bandeiras
├── assets/                  # Dez vídeos MP4
├── js/                      # Pasta reservada; não há JavaScript
└── docs/
    ├── README.md
    ├── DIARIO_DE_BORDO_ATLAS.docx
    ├── DIARIO_DE_BORDO_ATLAS.pdf
    ├── ORCAMENTO_SERVIDOR_E_DOMINIO.pdf
    ├── CREDITOS_DE_IMAGENS.txt
    └── REGISTRO_DE_TESTES.md
```

Para abrir a versão local, extraia o ZIP e abra `index.html` no navegador. As imagens externas dependem de conexão com a internet; a reprodução automática dos vídeos pode variar entre navegadores.

## Participação do grupo

| Integrante | Trabalho no projeto |
| --- | --- |
| Welder | Página inicial, integração dos arquivos, navegação e padronização da identidade visual |
| Kelvin | México e colaboração nas revisões do grupo |
| Gustavo | Egito e pesquisa relacionada ao orçamento técnico |
| Matheus | Canadá e continuidade do conteúdo da Itália |
| Gabriel | Alemanha |
| Maria Eduarda Almeida da Rocha | Suíça |
| Daniel | Austrália |
| Lucas | Japão e colaboração com a revisão do CSS |
| Maria Eduarda Cabral | França |

**Colaborações da primeira fase:** André (Grécia) e Alicia (Itália). Após a saída de André e Alicia, o grupo redistribuiu as tarefas. Não houve tempo hábil para atualizar o conteúdo da Grécia; Matheus deu continuidade à Itália. Os créditos da primeira etapa foram preservados.

## Orçamento e evolução do projeto

O nome ATLAS foi mantido como identidade definitiva do projeto, mesmo após uma sugestão de mudança durante o desenvolvimento. O Atlas informativo ganhou uma proposta complementar de **exploração de destinos e planejamento de viagens**. A página `orcamento.html` é a primeira etapa dessa ideia; a futura busca de passagens, hospedagens e comparação de preços ainda não foi implementada.

O **orçamento de servidor web e domínio**, exigido pela disciplina, é um documento diferente do formulário de viagem. O relatório está em `docs/ORCAMENTO_SERVIDOR_E_DOMINIO.pdf`: compara GitHub Pages, Cloudflare Pages e Hostinger Single, além das extensões `.com.br`, `.com` e `.edu.br`, com custos, limites, condições e justificativa. Os valores apresentados no relatório são referências sujeitas a atualização e disponibilidade.

## Documentação

- **`docs/DIARIO_DE_BORDO_ATLAS.pdf` / `.docx`:** decisões, dificuldades, divisão de tarefas e evolução das duas entregas.
- **`docs/ORCAMENTO_SERVIDOR_E_DOMINIO.pdf`:** pesquisa e comparação de hospedagem web e domínios.
- **`docs/CREDITOS_DE_IMAGENS.txt`:** créditos disponíveis de imagens e observações sobre fontes pendentes.
- **`docs/REGISTRO_DE_TESTES.md`:** verificações técnicas realizadas e itens não validados oficialmente.

## Referências de estudo

Durante a integração, foram consultados exemplos e materiais de HTML e CSS, incluindo [W3Schools — HTML](https://www.w3schools.com/html/), [W3Schools — CSS](https://www.w3schools.com/css/) e [W3Schools — Formulários](https://www.w3schools.com/html/html_forms.asp). Ferramentas de IA também foram utilizadas como apoio à pesquisa técnica, à explicação de propriedades e à revisão de alternativas, junto com os testes e as decisões do grupo.

**Situação em 05/11/2026:** versão integrada do projeto. Os testes de navegação local e integridade de arquivos foram registrados; a validação oficial pelo W3C e a conferência manual em todos os navegadores ainda precisam ser documentadas. Algumas imagens da Austrália seguem pendentes, assim como a confirmação das fontes de fotografias recebidas pelo grupo.
