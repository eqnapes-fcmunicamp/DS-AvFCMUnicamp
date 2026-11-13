# DS-AvFCMUnicamp

Design system dos Relatórios de Avaliação dos Cursos da FCM-Unicamp, conduzidos pelo Napes (Medicina e Fonoaudiologia).

Comece por [`project/README.md`](project/README.md) (como aplicar) e [`project/00-sobre.md`](project/00-sobre.md) (visão geral).

| Caminho | Conteúdo |
|---|---|
| `project/tokens.json`, `project/tokens.css` | Cores (3 temas de divulgação), tipografia, espaços e raios. `tokens.css` é gerado de `tokens.json`. |
| `project/components/` | Componentes C1 a C27, cada um com `README.md` (ficha) e `preview.html`; estilos em `bundle.css`. |
| `project/00-…` a `10-…` | Seções: arquitetura, perfis, regras de visualização, níveis de divulgação, modelos de página, divergências, decisões, exemplos de referência, princípios. |
| `project/assets/Logos/` | Logos da Unicamp, FCM e Napes e as regras de uso (`README.md`). |
| `project/fonts/` | Google Sans Flex (cortes da capa), com a licença OFL. |

Estado: rascunho. As decisões abertas estão em `project/08-decisoes-pendentes.md`; todo exemplo aprovado tem precedência sobre o texto (`project/09-exemplos-de-referencia.md`).

## Origem e sincronização

Esta pasta espelha o artefato «Relatórios FCM» do Claude (Design System). O índice do artefato (`design-system.json`) não está aqui porque guarda identificadores internos de arquivos enviados.

Ainda fora do repositório: `FCM UNICAMP.png`, `NAPESalfa.png`, `UNICAMP.png` e `Unicamp60anos.png`, que estão só no artefato. O logotipo do PMU/Med não foi enviado.

## Licenças

Google Sans Flex: SIL Open Font License 1.1 (`project/fonts/GoogleSansFlex-OFL.txt`). Marcas da Unicamp, da FCM e do Napes: uso institucional, conforme as regras em `project/assets/Logos/README.md`.
