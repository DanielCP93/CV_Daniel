# CV Daniel - Currículo Web Profissional

Projeto de currículo em formato web, desenvolvido como página única com foco em:
- leitura rápida em tela;
- responsividade para desktop e mobile;
- impressão/exportação em A4 com alta legibilidade;
- manutenção simples, sem pipeline de build.

## Objetivo

Disponibilizar uma versão profissional do currículo de `Daniel Canal Peterle` em HTML/CSS puro, com estrutura semântica, fácil atualização de conteúdo e estilo de impressão pronto para uso.

## Stack e Decisões Técnicas

- `HTML5` semântico para organização clara das seções.
- `CSS3` com Grid, media queries e estilos dedicados para impressão.
- `Font Awesome` (CDN) para ícones de contato.
- `.hintrc` para padronização de lint HTML.

## Estrutura do Projeto

```text
CV_Daniel/
|- index.html      # Conteúdo e estrutura do currículo
|- style.css       # Estilos de tela e impressão
|- .hintrc         # Configuração de lint HTML
|- README.md       # Documentação do projeto
```

## Como Executar Localmente

Por ser um projeto estático, não há dependências obrigatórias.

1. Acesse a pasta do projeto.
2. Abra `index.html` no navegador.

Opcional (fluxo recomendado para desenvolvimento):
- usar extensão como **Live Server** no VS Code para atualização automática.

## Como Exportar para PDF (A4)

1. Abra o currículo no navegador.
2. Use `Ctrl + P` (ou menu de impressão).
3. Selecione formato `A4`, orientação retrato.
4. Salve em PDF.

Observação: o arquivo `style.css` já possui bloco `@media print` para otimizar espaçamento, legibilidade e distribuição dos blocos na folha.

## Guia de Atualização de Conteúdo

Atualize `index.html` conforme a seção:
- cabeçalho (nome e título);
- contatos;
- resumo profissional;
- stack tecnológica;
- projetos relevantes;
- experiência profissional;
- formação;
- habilidades.

## Guia de Ajustes Visuais

Atualize `style.css` conforme o contexto:
- estilos gerais de tela no bloco base;
- comportamento responsivo em `@media (max-width: 980px)`;
- impressão em `@media print`.

Ao ajustar impressão, priorize:
- `font-size` e `line-height` para legibilidade;
- espaçamentos verticais entre seções;
- controle de quebras com `break-inside`/`page-break-inside`.

## Padrões de Qualidade

- separação clara entre estrutura (`index.html`) e apresentação (`style.css`);
- marcação semântica para facilitar manutenção;
- layout otimizado para leitura humana e uso em processos seletivos;
- código enxuto e sem dependências de framework.

## Checklist Antes de Publicar/Enviar

1. Validar ortografia e atualização dos dados profissionais.
2. Conferir links de contato (LinkedIn e GitHub).
3. Verificar visual em desktop e mobile.
4. Revisar preview de impressão em A4.
5. Confirmar se a exportação em PDF mantém legibilidade.

## Licença e Uso

Este repositório contém informações pessoais e profissionais do titular do currículo.
Uso, cópia ou redistribuição devem respeitar autorização explícita do autor.