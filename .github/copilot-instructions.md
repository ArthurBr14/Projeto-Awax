# Copilot Instructions for Projeto Awax

## Visão Geral
Este projeto é um site estático, com estrutura tradicional de HTML, CSS e recursos de mídia. Não há backend, frameworks JS ou automações de build detectadas. O foco é a apresentação visual e responsiva.

## Estrutura Principal
- `index.html`: Página principal, organiza todas as seções do site.
- `Estilo/style.css`: Folha de estilos central, define layout, responsividade e temas visuais.
- `Mídia/`: Imagens usadas em banners, seções e ícones de equipe.
- `icones/`: Ícones PNG para redes sociais e elementos visuais.

## Padrões e Convenções
- CSS utiliza variáveis customizadas (`:root`) para pesos de fonte.
- Classes seguem padrão BEM simplificado, ex: `.section-team-area`, `.section-projects--photoarea`.
- Evite conjuntos de regras CSS vazios.
- Responsividade via `max-width`, `width: 100vw`, e flexbox.
- Imagens referenciadas com caminhos relativos (`../Mídia/bg.jpg`).
- Cores e temas: tons escuros predominam, com destaques em laranja (`#b28756`).

## Fluxos de Desenvolvimento
- Não há scripts de build, testes ou automações detectados.
- Alterações em CSS/HTML são refletidas diretamente ao recarregar o navegador.
- Recomenda-se validar visualmente após cada alteração.

## Exemplos de Padrão
```css
:root {
    --ligth: 300;
    --regular: 400;
    --semi-bold: 600;
    --bold: 700;
}
.section-team-area {
    background-color: rgba(0, 0, 0, 0.7);
    padding-top: 50px;
    padding-bottom: 50px;
}
```

## Recomendações para Agentes
- Priorize clareza visual e responsividade.
- Mantenha a organização das seções conforme o HTML.
- Não adicione frameworks ou automações sem solicitação explícita.
- Documente padrões visuais e de layout ao modificar CSS.

## Pontos de Atenção
- Não há dependências externas ou integrações detectadas.
- O projeto é voltado para aprendizado e demonstração visual.

---

Seções ou padrões não identificados? Solicite exemplos ou esclarecimentos ao usuário.