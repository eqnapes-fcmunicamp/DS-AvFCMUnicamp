# Arquitetura e princípios

Hoje a identidade visual existe, mas está repetida em vários pontos de produção do relatório, cada um com sua cópia de cores, tamanhos e rótulos. Foram observadas a mesma paleta definida em mais de um lugar, três ordens diferentes para os domínios e variações de raio e de tamanho entre páginas que deveriam ser iguais. Com um segundo curso, essas cópias tenderiam a se multiplicar.

O sistema deve garantir que:

1. os relatórios dos dois cursos sejam reconhecíveis como uma família (mesmo Napes, mesma FCM, mesma leitura);
2. cada curso mantenha o que lhe é próprio (estrutura do curso, programas, instrumentos, séries históricas) sem criar estilos avulsos;
3. as séries históricas continuem comparáveis, com Medicina 2026.1 reproduzível sem diferença visível;
4. o nível de divulgação seja uma escolha, e não uma versão paralela do relatório.

## Núcleo FCM e perfis de curso

```
NÚCLEO FCM (comum a todos os cursos)
  identidade institucional · tipografia · neutros · escalas de resposta
  componentes · regras de gráfico · níveis de divulgação · números e rótulos
        │
        ├── PERFIL MEDICINA        anos letivos (1º–6º) · chip «MEDICINA»
        │                          mentoria PMU/Med · série SPICES/INT · metodologias
        │
        └── PERFIL FONOAUDIOLOGIA  a definir pelos exemplos
```

| Camada | Contém | Não contém |
|---|---|---|
| Núcleo FCM | identidade Napes, FCM e Unicamp; tipografia; paleta estrutural e neutros; escalas de resposta comuns; catálogo de componentes; regras de gráfico; temas de divulgação; convenções de número, data e ciclo | nada que dependa da grade de um curso |
| Perfil de curso | nome e rótulo do curso; número e rótulos dos anos ou períodos; programas e iniciativas próprias (ex.: mentoria); séries históricas; escalas exclusivas do instrumento do curso; seções específicas | cores ou fontes que concorram com o núcleo |

**Regra de convivência.** Um perfil pode acrescentar uma seção, uma escala ou um acento de cor de programa próprio, e não pode substituir um token do núcleo. Se um curso precisar de algo que o núcleo não tem e que o outro curso também usaria, o item sobe para o núcleo.

## Princípios

1. **Fonte única de verdade.** Cada valor visual é definido uma única vez, num registro permanente, e todo o resto o referencia pelo nome.
2. **Nome pelo papel.** «Cor do cabeçalho» e «cor de Oportunidade de melhoria», e nunca «verde-escuro».
3. **Três camadas de token.**

| Camada | O que é | Exemplo |
|---|---|---|
| Base | a paleta e as medidas disponíveis | petróleo `#005A5A`; 6px |
| Semântica | o papel de cada valor no relatório | cabeçalho de página usa petróleo; «Sim» usa verde |
| Componente | as medidas próprias de cada peça | raio do cabeçalho = 6px |

4. **Componentes fechados.** Uma página é montada com componentes do catálogo; o que não existe entra primeiro no catálogo.
5. **Escalas congeladas.** As cores das escalas de resposta não mudam entre ciclos nem entre cursos. Escala nova recebe cores novas.
6. **Conteúdo separado de forma.** Curso, ciclo, instrumento e nível de divulgação mudam o que aparece; o sistema define como aparece.
7. **O guia visual é derivado do sistema** e não é escrito à parte.

## Identificação do curso no relatório

O curso precisa ser identificável em toda página de conteúdo sem depender de cor própria:

- capa, contracapas e metadados do documento trazem o nome do curso por extenso;
- chip do curso no cabeçalho das páginas de visão geral (Medicina 2026.1: «MEDICINA»);
- rodapé com o ciclo (e, se decidido, a sigla do curso, D10);
- títulos e subtítulos no formato «Relatório de Avaliação do Curso de <Curso>».
