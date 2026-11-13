# Princípios de design

Proposta de trabalho, ainda não validada pelo Napes. Reúne princípios gerais de design de interface e diz onde cada um já aparece neste sistema ou o que passaria a valer. Onde um princípio contradiz uma regra dos outros documentos, vale a regra dos outros documentos.

Fonte lida: os princípios de design das Human Interface Guidelines da Apple, texto enviado em 2026-11-13, resumido aqui em palavras próprias. Fontes ainda não lidas: dois arquivos da comunidade do Figma indicados na mesma data.

| # | Princípio | Onde já aparece | O que passa a valer |
|---|---|---|---|
| 1 | **Propósito.** Cada elemento serve a uma pergunta do leitor. | Resumo Executivo, nota de leitura (C20), seções com contracapa. | Um gráfico só entra se responde a uma pergunta declarada na página; sem pergunta, vira tabela (C21) ou sai. |
| 2 | **Autonomia.** O leitor se orienta sozinho e vai direto ao que procura. | Sumário com páginas, contracapas de seção, chips de contexto (curso, ano, código) no cabeçalho. | Toda página diz onde está (chip e título) sem depender da página anterior. |
| 3 | **Responsabilidade.** Transparência sobre o que os dados mostram e proteção de quem os forneceu. | Níveis de divulgação, ausência total dos sensíveis nos temas não restritos, nota de base, soma de categorias e cortes declarados. | Nenhuma exceção ao padrão «na dúvida, excluir»; todo corte ou soma entra em nota. |
| 4 | **Familiaridade e consistência.** O que tem a mesma forma significa a mesma coisa. | Escalas congeladas, ordem fixa dos segmentos, tokens por nome. | Mesma cor e mesma ordem em qualquer forma de gráfico (C4, C22, C23, C25); forma nova só entra por decisão (D17). |
| 5 | **Flexibilidade e acessibilidade.** O relatório serve a quem lê em tela, imprime ou tem visão diferente. | Contraste calculado por token, legenda com as palavras, temas por nível. | Cor nunca é o único sinal: toda cor de escala tem rótulo em palavra; texto novo passa de 4,5:1 (3:1 a partir de 24px). |
| 6 | **Simplicidade.** Só o necessário, com hierarquia clara. | Estilos nomeados de título, box e item; limite de rótulos nas barras. | No máximo 5 segmentos em gráfico circular; sem 3D, sombra ou ornamento; eixos de 0% a 100%. |
| 7 | **Esmero.** A qualidade se verifica, não se presume. | Passo 7 da sequência (validar contra Medicina 2026.1), contraste calculado, exemplos aprovados com precedência. | Todo componente novo traz ficha, preview e exemplo; ficha sem exemplo fica marcada como pendente. |
| 8 | **Encanto sem decoração.** A identidade vem do uso consistente de cor, tipo e logo, não de enfeite. | Capa em `capa-fundo`, família `titulo-capa` só na capa, logos em `assets/Logos`. | Nenhum ícone, ilustração ou gradiente sem exemplo aprovado. |

## Como usar

Ao propor um componente ou uma página, passe pelos oito princípios e registre na ficha qual deles justifica a escolha. Se dois se opõem (por exemplo, simplicidade e transparência numa nota longa), vale o 3, depois o 5, depois os demais.
