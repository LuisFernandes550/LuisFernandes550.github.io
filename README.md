# Lagoa de Óbidos - Website Promocional

Template front-office do website promocional dedicado à Lagoa de Óbidos, desenvolvido com HTML, CSS e Bootstrap 5.

## Estrutura do Projeto

```
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos customizados
├── pages/
│   ├── alojamento.html           # Hotéis, alojamento local, campismo
│   ├── paisagens-naturais.html   # Paisagens Naturais
│   ├── trilhos-percursos.html    # Trilhos e Percursos
│   ├── zonas-observacao.html     # Zonas de Observação
│   ├── patrimonio-historico.html # Património Histórico
│   ├── locais-emblematicos.html  # Locais Emblemáticos
│   └── natureza.html             # Contacto com a Natureza
└── README.md
```

## Secções e Menu

| Menu | ID/Secção | Descrição |
|------|-----------|-----------|
| História | `#historia` | Enquadramento histórico e cultural |
| Visitar | `#visitar` | Links para páginas: Paisagens, Trilhos, Zonas de Observação, Património, Locais Emblemáticos, Natureza |
| Experiências | `#experiencias` | Atividades culturais, educativas e desportivas |
| Gastronomia | `#gastronomia` | Restaurantes, cafés, bares e experiências gastronómicas |
| Alojamento | `#alojamento` | Links para página com Hotéis, Alojamento local, Campismo |
| Galeria | `#galeria` | Lightbox para percorrer imagens |

## Tecnologias

- **HTML5** - Estrutura semântica
- **Bootstrap 5.3** - Grid responsivo, componentes e utilitários
- **Bootstrap Icons** - Ícones
- **CSS3** - Variáveis, flexbox, animações
- **Google Fonts** - Playfair Display, Source Sans 3

## Design

- Paleta inspirada na Lagoa: tons de água (verde-azulado), areia e natureza
- Design responsivo para mobile, tablet e desktop
- Navegação fixa com efeito de scroll
- Hero full-height com call-to-action
- Cards com efeitos hover e placeholders para imagens

## Próximos Passos (Laravel)

Este template está preparado para integração com Laravel:

1. **Imagens**: Os placeholders (`placeholder-image`, `placeholder-card`, `placeholder-gallery`) devem ser substituídos por imagens reais via Blade ou componentes dinâmicos
2. **Conteúdos**: O texto estático pode ser movido para base de dados ou ficheiros de configuração
3. **Links**: Os botões "Ver opções" em Onde Ficar e os links de navegação podem apontar para rotas Laravel
4. **Galeria**: A grelha de imagens pode ser alimentada dinamicamente por uma coleção

## Como Visualizar

Abra o ficheiro `index.html` no browser ou utilize um servidor local:

```bash
# Com Python
python -m http.server 8000

# Com Node.js (npx)
npx serve
```

Aceda a `http://localhost:8000` no browser.
