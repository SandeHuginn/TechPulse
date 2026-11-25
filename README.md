# TechPulse — Portal de Notícias de Tecnologia

## 1. Apresentação do Projeto

O **TechPulse** é um portal de notícias desenvolvido com o objetivo de apresentar informações, novidades e tendências relacionadas ao universo da tecnologia.

A proposta é oferecer uma página inicial organizada, acessível e intuitiva, permitindo que os visitantes encontrem conteúdos sobre diferentes áreas tecnológicas.

O projeto foi desenvolvido como parte de uma atividade acadêmica de desenvolvimento Front-End, aplicando conceitos de HTML5 semântico, CSS3, acessibilidade e design responsivo.

## 2. Objetivos

- Apresentar notícias e informações sobre tecnologia.
- Organizar conteúdos por categorias.
- Proporcionar uma navegação simples e intuitiva.
- Desenvolver uma interface adaptável a computadores e dispositivos móveis.

## 3. Tecnologias Utilizadas

O desenvolvimento do TechPulse utiliza tecnologias fundamentais para a construção de páginas web:

- **HTML5:** utilizado para estruturar o conteúdo da página, empregando elementos semânticos como `header`, `nav`, `main`, `section`, `article` e `footer`.
- **CSS3:** responsável pela apresentação visual, incluindo cores, fontes, espaçamentos, bordas e adaptação da interface para diferentes tamanhos de tela.

Não foram utilizadas bibliotecas ou frameworks externos. A estrutura e a estilização foram desenvolvidas diretamente com HTML5 e CSS3.

## 4. Organização dos Arquivos

O projeto foi organizado para manter a separação entre estrutura, estilização e recursos visuais.

```text
TechPulse/
├── index.html
├── css/
│   └── style.css
├── assets/
│   └── tecnologia.jpg
└── README.md
```

Descrição dos arquivos:

- `index.html`: contém a estrutura e os conteúdos da página.
- `css/style.css`: concentra as regras de estilização.
- `assets/`: armazena as imagens utilizadas no portal.
- `README.md`: apresenta a documentação técnica do projeto.

## 5. Justificativas de Design

### 5.1. Cores utilizadas

A identidade visual utiliza uma combinação de azul-escuro, azul vibrante, branco e cinza-claro.

- **Azul-escuro (#14213d):** utilizado no cabeçalho e rodapé para transmitir confiança, profissionalismo e estabilidade.
- **Azul (#0077b6):** utilizado em elementos de destaque, como títulos e botão de ação, para direcionar a atenção dos visitantes.
- **Cinza-claro (#f4f6f8):** utilizado no fundo da página para criar contraste com as áreas de conteúdo.
- **Branco (#ffffff):** utilizado nas seções e nos textos do cabeçalho e rodapé para favorecer a leitura.

### 5.2. Tipografia

Foi utilizada a família de fontes Arial, com alternativas Helvetica e sans-serif.

Essa escolha prioriza a legibilidade, a simplicidade e a compatibilidade com diferentes navegadores e dispositivos.

Os tamanhos das fontes foram definidos de acordo com a hierarquia dos conteúdos, utilizando títulos maiores para destacar seções e textos menores para informações complementares.

### 5.3. Espaçamentos e bordas

Foram utilizadas propriedades do Box Model do CSS:

- **Margin:** define os espaços externos entre seções e elementos.
- **Padding:** cria espaços internos, evitando que os conteúdos fiquem próximos das bordas.
- **Border:** delimita visualmente algumas áreas e elementos.
- **Border-radius:** suaviza os cantos de seções, cartões e botões.

Essas escolhas contribuem para uma interface organizada, confortável e de fácil leitura.

## 6. Estrutura e Acessibilidade

A estrutura da página utiliza elementos semânticos do HTML5 para organizar os conteúdos:

- `header`: apresenta a identificação do portal.
- `nav`: disponibiliza o menu de navegação.
- `main`: agrupa o conteúdo principal.
- `section`: organiza os conteúdos por assunto.
- `article`: representa notícias individuais.
- `footer`: apresenta as informações finais da página.

Também foram aplicados recursos de acessibilidade, como o atributo `alt` na imagem, textos descritivos e uma hierarquia de títulos para facilitar a compreensão do conteúdo.

## 7. Responsividade

O projeto utiliza uma Media Query com o ponto de quebra de 600 pixels (`max-width: 600px`).

Essa configuração adapta elementos da página para telas menores, incluindo:

- Organização vertical do menu de navegação.
- Ajustes no tamanho dos títulos.
- Redução dos espaçamentos internos.
- Adaptação da imagem à largura disponível.
- Ajustes na apresentação dos textos.

O objetivo é manter a navegação e a leitura confortáveis tanto em computadores quanto em celulares.

## 8. Serviços e Categorias do Portal

O TechPulse apresenta conteúdos relacionados às seguintes áreas tecnológicas:

- **Inteligência Artificial:** informações sobre ferramentas inteligentes, automação e aprendizado de máquina.
- **Computação em Nuvem:** conteúdos sobre armazenamento, processamento e serviços digitais.
- **Cibersegurança:** notícias sobre proteção de dados, privacidade e segurança de sistemas.

Essas categorias representam os principais assuntos abordados na proposta do portal.

## 9. Sitemap Visual

O Sitemap Visual representa a organização hierárquica dos conteúdos do TechPulse, demonstrando como as categorias e subcategorias estão distribuídas.

```text
TECHPULSE
│
└── Página Inicial
    │
    ├── Início
    │   ├── Apresentação do portal
    │   └── Destaque principal
    │
    ├── Notícias
    │   ├── Inteligência Artificial
    │   │   ├── Automação
    │   │   └── Aprendizado de Máquina
    │   │
    │   ├── Computação em Nuvem
    │   │   ├── Armazenamento em Nuvem
    │   │   └── Serviços Digitais
    │   │
    │   └── Cibersegurança
    │       ├── Proteção de Dados
    │       └── Segurança Digital
    │
    ├── Tecnologias
    │   ├── Inteligência Artificial
    │   ├── Computação em Nuvem
    │   └── Cibersegurança
    │
    └── Sobre
        ├── Apresentação do TechPulse
        └── Objetivos do Portal
```

### 9.1. Hierarquia de conteúdo

A hierarquia foi organizada a partir da página inicial, que funciona como ponto central de acesso às demais áreas do portal.

As categorias principais agrupam assuntos relacionados, enquanto as subcategorias dividem os conteúdos em temas mais específicos.

### 9.2. Taxonomia

A taxonomia do TechPulse utiliza a classificação temática para organizar as informações.

As notícias são agrupadas de acordo com seus assuntos, permitindo que os visitantes identifiquem e compreendam melhor os conteúdos disponíveis.

Essa organização facilita a navegação e estabelece uma estrutura lógica para o crescimento futuro do portal.

## 10. Considerações Finais

O desenvolvimento do TechPulse permitiu aplicar conceitos fundamentais de desenvolvimento Front-End, incluindo estruturação semântica com HTML5, estilização com CSS3, organização de arquivos, acessibilidade e responsividade.

A primeira versão do portal apresenta uma estrutura organizada e preparada para receber novas funcionalidades e conteúdos relacionados ao universo da tecnologia.