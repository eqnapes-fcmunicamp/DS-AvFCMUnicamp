# Divergências entre kit e entregável

Fontes atuais: o relatório de Medicina 2026.1 «Simples» (EX-MED-01, 64 páginas), os entregáveis finais de Medicina 2026.1, o kit de design (`guia-de-estilo.md`, `tokens.json`, `base.css`, `guia-visual.html`), a auditoria de 2026-10-17 e o esqueleto do relatório de Medicina 2026.2.

**Precedência:** exemplo de referência aprovado > entregável final > kit atual > este documento. Os tokens deste sistema já trazem o valor do entregável onde ele diverge do kit (decisão D1 ainda por confirmar).

| # | Item | Kit | Entregável | Orientação |
|---|---|---|---|---|
| V1 | Cor da faixa de tema | `#E4E4E1` | `#EDEDE9` | adotar o entregável |
| V2 | Fonte da faixa de tema e dos sensíveis | Stack Sans | Google Sans | adotar o entregável |
| V3 | Box da declaração de uso restrito | `#062D41` | `#105B5C` | adotar o entregável ou decidir mudar |
| V4 | Peso do rótulo do rodapé no interno | 600 | 400 (defeito) | uniformizar em 600 |
| V5 | Raio do box | 8px | 4 a 8px conforme a página | D2 |
| V6 | Cabeçalho da série comparativa | igual ao padrão | menor | registrar como variante |
| V7 | Cor do texto | `#1F1F1D` | `#1A1A1A` | adotar o entregável |
| V8 | Largura dos rótulos das barras simples | uma | três | registrar por uso |
| V9 | Ordem dos domínios | uma | três | D4 |
| V10 | Cor das siglas no sumário | n/d | duas | unificar em `#105B5C` |
| V11 | Sensível moderado | ativo | desativado | registrar como desativado |
| V12 | Esmaecimento na mentoria | previsto | não aplicado | D5 |
| V13 | Nome dos consolidados de 2026.2 | com ponto no ciclo | regra de nomes pede hífen | `-2026-2` |
| V14 | Cor do texto corrido | `#1A1A1A` (V7) | `#2B2B29` na prosa, `#1F1F1D` nas assinaturas, `#555555` nos valores, `#444444` nos rótulos de lista | `texto-prosa`, `texto-assinatura`, `texto-valor`, `texto-lista`; o EX-MED-01 vale |
| V15 | Rótulo do nível no rodapé | USO RESTRITO, CORPO DOCENTE, PÚBLICO | DIVULGAÇÃO | decidir se é um quarto nível ou o nome do público (D15) |
| V16 | Legenda da escala Sim, Parcialmente, Não | NÃO SEI | NÃO SEI RESPONDER nas disciplinas (páginas 20 a 63), NÃO SEI nas demais | decidir texto único (D16); a escala e as cores não mudam |
| V17 | Capa e página final | `capa` `#105B5C` em tudo | capa em `#2F8F8F` (`capa-fundo`), título em Google Sans Flex; página final em `#105B5C` | adotar o EX-MED-01 |
