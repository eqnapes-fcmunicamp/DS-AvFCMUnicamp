Relatórios FCM reúne o padrão visual dos Relatórios de Avaliação dos Cursos da Faculdade de Ciências Médicas da Unicamp, conduzidos pelo Napes: Medicina e Fonoaudiologia. As regras abaixo valem para os dois cursos, salvo onde a regra diz perfil Medicina. O sistema está em rascunho: as decisões abertas estão em Decisões pendentes e todo exemplo aprovado tem precedência sobre este texto.

## Como aplicar

- Referencie cada cor, tamanho e raio pelo nome do token (`petroleo`, `raio-card`, `titulo-box`). Nunca copie o valor hexadecimal para um documento ou componente.
- Monte cada página só com componentes do catálogo (C1 a C27). Peça que o catálogo não tem entra primeiro no catálogo, com ficha.
- Coloque no núcleo o que serve aos dois cursos. Um perfil de curso acrescenta seção, escala ou paleta de programa; nunca substitui um token do núcleo. Se um curso precisar de algo que o outro também usaria, o item sobe para o núcleo.
- Escolha o nível de divulgação (restrito, docente, público) uma vez para o relatório inteiro, como tema. O nível muda o rodapé, o box do Resumo Executivo e a presença dos comentários sensíveis. A estrutura das páginas não muda.
- Na ordem de precedência, vale o exemplo de referência aprovado, depois o entregável final, depois o kit, depois este sistema.

## Fundamentos de conteúdo

- Escreva o ciclo como `AAAA.S` (2026.1). Escreva milhar com ponto (1.956), decimal com vírgula (89,8%) e o sinal de percentual colado ao número.
- Use inteiros nas barras. Use uma casa decimal só em adesão.
- Identifique o curso por extenso na capa, nas contracapas e nos metadados, e em título e subtítulo no formato «Relatório de Avaliação do Curso de <Curso>». Nas páginas de visão geral, ponha o chip do curso no cabeçalho (MEDICINA). Chips de ano usam «1º ANO» a «6º ANO».
- Escreva rótulos em caixa alta com entrelinha que não corte os acentos.
- Dê a cada nota de leitura (C20) a base do percentual, o que ficou fora do gráfico e as ressalvas. Declare em nota quando duas categorias forem somadas e quando temas forem cortados.
- Apresente comparações entre cursos só com escalas e enunciados equivalentes; caso contrário, mostre lado a lado sem síntese comparativa. Não desenhe linha de tendência em intervalos desiguais e não descreva comparação entre turmas como progressão.
- Nomeie consolidados com hífen no ciclo (`-2026-2`).

## Fundamentos visuais

**Cor.** Use `petroleo` no cabeçalho de página, nas contracapas e nos títulos de box. Use `capa` em títulos centrados, no sumário, nos chips de domínio e no box de declaração ou nota, em todas as versões. Use `verde-codigo` nos chips de código, ano e curso, `verde-barra` nas barras simples e `adesao` nas barras de adesão. Use `anel` só como contorno do polo predominante.

**Neutros.** Escreva texto corrido em `texto` sobre `papel` ou `fundo-box`. Use `texto-2` e `texto-3` para níveis secundários. `nota`, `numero-pagina` e `rotulo-legenda` ficam abaixo de 4,5:1 sobre `papel`: mantenha-os onde o entregável os usa e não os aplique a texto novo.

**Escalas de resposta.** Cada escala tem cores e ordem congeladas. Não altere `escala-*` nem `polo-*` entre ciclos ou cursos; escala nova recebe cores novas. Ordene os segmentos sempre pela ordem da escala, nunca por tamanho. Mostre sempre a legenda com as palavras, porque Sim e Não têm luminosidade quase igual. A escala pode ser desenhada em barra horizontal (C4), donut (C22), pizza (C23) ou colunas empilhadas (C25); percentual de uma categoria entre categorias em colunas (C24); série por edição em C26; adesão em C6 ou no anel C27. Todos seguem a mesma ordem, as mesmas cores e as mesmas regras de rótulo.

**Rótulos nas barras.** Rotule os percentuais das maiores categorias (todas menos a menor). Se uma categoria passar de 90%, rotule só ela. Use `texto` sobre fundo claro e `sobre-escuro` sobre fundo escuro, escolhendo o que der maior contraste. O limiar mínimo de rótulo é único por tipo de gráfico (hoje há quatro valores, D8).

**Tipografia.** Ponha títulos, cabeçalhos, chips e rótulos em caixa alta em Google Sans (`titulo`, 400 e 700). Ponha corpo, enunciados, comentários, números e rodapé em Spline Sans (`corpo`, leitura em 400). Use os estilos nomeados: `titulo-pagina`, `titulo-box`, `titulo-item`, `enunciado`, `prosa`, `comentario`, `legenda`, `numero-barra`, `nota-leitura`, `rodape`. Não use Stack Sans (D6). Só a capa usa Google Sans Flex (`titulo-capa`, extraleve 200 e negrito 700), com os estilos `capa-etiqueta`, `capa-titulo` e `capa-ciclo`; os dois cortes estão em `fonts/`.

**Página.** A4 retrato, margem de conteúdo `margem-conteudo`. A capa e as contracapas são sangradas, sem margem. Raios: `raio-chip`, `raio-cabecalho`, `raio-card`, `raio-barra`, `raio-box`.

**Estados.** Turmas fora do recorte válido continuam no gráfico, esmaecidas. O comentário sensível aparece só no tema restrito, em caixa própria, e some por inteiro nos outros: sem texto, sem contagem, sem menção, inclusive em notas e totais. Na dúvida sobre o nível, o padrão é excluir.

## Identidade e iconografia

Os logos estão em `assets/Logos/`, com a regra de cada versão no README da pasta: Unicamp (quatro versões, positivo e negativo), FCM e Unicamp (colorido e branco), régua Napes, FCM e Unicamp, e Napes vertical. Use os arquivos como estão, sem redesenhar nem recolorir, e respeite a área de não interferência e a altura mínima do Portal Unicamp. O logotipo do PMU/Med não foi enviado: no perfil Medicina, escreva o nome do programa em `titulo` até ele chegar. Posição da régua, versão dos logos Napes para fundo escuro e capa final comum ou por curso estão em aberto (D12). O documento de origem não define família de ícones: não introduza nenhuma sem exemplo aprovado.

## Paletas de programa

A paleta da mentoria PMU/Med (`mentoria-*`) é a única exceção à paleta do núcleo, vale só nas páginas do programa e deriva do logo dele. Qualquer paleta de programa nova segue a mesma regra.
