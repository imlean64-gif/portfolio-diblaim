# Diblaim Palmeira · Blueprint v2

Portfólio estático em **HTML, CSS e JavaScript**, com identidade visual azul inspirada no modelo **Blueprint Tech (02)**.

## Como abrir

1. Extraia o arquivo ZIP.
2. Abra `index.html` no navegador.

> O site não precisa de Node.js, npm, backend ou API para funcionar. Todos os arquivos necessários estão incluídos.

## Estrutura

```text
blueprint-diblaim-v2/
├── index.html
├── assets/
│   ├── css/style.css
│   └── js/script.js
└── README.md
```

## Principais recursos

- Layout dark mode azul, responsivo para desktop, tablet e celular.
- Apresentação, sobre, projetos, tecnologias, jornada e contato.
- Filtros entre projetos acadêmicos e estudos.
- Modais com detalhes de cada projeto, acessíveis pelo teclado.
- Menu móvel, indicador de progresso de rolagem e navegação por âncoras.
- Links para WhatsApp, Instagram, LinkedIn e GitHub.
- Sem bibliotecas externas, cookies, anúncios ou formulários que coletam dados.

## Contatos incluídos

- Instagram: https://www.instagram.com/diblx_/
- LinkedIn: https://www.linkedin.com/in/diblaim-palmeira-727576324/
- GitHub: https://github.com/imlean64-gif
- WhatsApp: `https://wa.me/5571984151227` (botões incluem mensagem inicial)

> Atenção: o número de WhatsApp fica público no HTML. Se preferir não expor o número, remova os botões ou substitua por outro canal de contato.

## Sobre os projetos

O MobFlow é apresentado como um **protótipo acadêmico**: mapas, métricas e alertas visuais desta página são **ilustrativos** e não são dados em tempo real. Os estudos de Java e lógica são descritos como trabalhos em evolução. Links para GitHub direcionam ao perfil geral, sem prometer repositórios individuais inexistentes.

## Como publicar no GitHub Pages

1. Crie um repositório público (por exemplo, `portfolio`).
2. Envie `index.html` e a pasta `assets` para a raiz do repositório.
3. Em **Settings → Pages**, selecione a publicação pela branch `main` e pasta `/ (root)`.
4. Depois que o GitHub publicar, use o endereço exibido na seção Pages.

Para publicar na Vercel, importe o repositório e configure como site estático sem comando de build.

## Personalização

- **Cores:** variáveis CSS no início de `assets/css/style.css` (`--bg`, `--blue`, `--ink` etc.).
- **Textos, projetos e links:** edite `index.html`.
- **Detalhes dos modais:** objeto `projects` em `assets/js/script.js`.
- **Número do WhatsApp:** procure `wa.me/5571984151227` em `index.html`.

O projeto foi escrito com HTML semântico, links externos com `noopener noreferrer`, suporte a movimento reduzido e elementos interativos acessíveis.
