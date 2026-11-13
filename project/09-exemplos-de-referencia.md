# Exemplos de referência

Os exemplos entram aqui como referências aprovadas, com precedência sobre o restante deste sistema.

## Ficha de cada exemplo

| Campo | Conteúdo |
|---|---|
| Identificador | ex.: `EX-MED-01`, `EX-FONO-01`, `EX-FCM-01` |
| Curso | Medicina · Fonoaudiologia · ambos |
| Origem e ciclo | relatório, página, edição |
| O que mostra | componente(s), modelo de página, regra |
| Status | referência aprovada · referência parcial (só o item indicado) · contraexemplo |
| Decisões que resolve | ex.: D3, D11 |
| Divergências com este sistema | o que o exemplo contradiz e qual lado vale |

## Como ler um exemplo

1. **Identidade:** logos, posição, capa, contracapa.
2. **Tokens:** cores, fontes, tamanhos e espaços realmente usados.
3. **Componentes:** quais do catálogo aparecem, quais não existem ainda (candidatos a C22 em diante).
4. **Regras:** rótulos de percentual, ordem, notas, números.
5. **Camada:** núcleo (serve aos dois cursos) ou perfil (só de um).
6. **Registrar** o resultado na ficha e atualizar as seções afetadas, com data.

## Registro de exemplos

| ID | Curso | Origem | O que mostra | Status | Resolve |
|---|---|---|---|---|---|
| EX-MED-01 | Medicina | Relatório de Avaliação do Curso de Medicina, 1º semestre de 2026, versão «Simples» (64 páginas, A4) | Capa, sumário, Resumo Executivo, contracapas de seção, páginas de ano e de disciplina, série comparativa, mentoria do 1º ano, rodapé DIVULGAÇÃO | referência aprovada (versão «Simples») | D12 em parte (a página final usa `capa`); abre D15 e D16 |

## EX-MED-01 — ficha

Registrado em 2026-11-13. Páginas: 1 capa, 2 sumário, 3 Resumo Executivo (com assinaturas), 4 contracapa da seção 1, 5 a 12 resultados gerais e por ano, 13 a 15 série comparativa, 16 a 18 mentoria, 19 contracapa da seção 4, 20 a 63 disciplinas, 64 página final.

1. **Identidade:** capa em bloco `capa-fundo` (`#2F8F8F`) com texto branco em Google Sans Flex (`capa-etiqueta`, `capa-titulo`, `capa-ciclo`); página final em `capa` (`#105B5C`).
2. **Tokens:** fontes Google Sans, Spline Sans e Google Sans Flex. Rodapé a 6,5pt (`rodape`, 8,67px). Texto da prosa em `#2B2B29` (`texto-prosa`). Rodapé: ciclo (2026.1), número da página e o rótulo DIVULGAÇÃO.
3. **Componentes:** a capa e a página final ainda não têm componente (candidatos a C28 e C29). A conferência página a página contra C1 a C21 fica para a validação do passo 7 da sequência.
4. **Regras:** legenda NÃO SEI RESPONDER nas disciplinas, NÃO SEI nas outras páginas (V16). Chip «MEDICINA» nas páginas de visão geral, «1º ANO» nas de ano, «SÉRIE COMPARATIVA» na seção 2.
5. **Camada:** núcleo, exceto a mentoria (perfil Medicina, paleta `mentoria-*`).
6. **Divergências com este sistema:** V14 a V17; nestes itens o exemplo vale.
