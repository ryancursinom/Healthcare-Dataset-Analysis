
[Explique a decisão ou pergunta que esta seção ajuda o usuário a responder.]

### Dados apresentados

| Indicador | Valor | Regra, fonte ou campo de origem |
|---|---:|---|
| [Nome do indicador] | [Valor fornecido] | [Origem] |

### Estrutura visual

Segue o anexo como referência visual — o layout final deve seguir esse padrão de design.

#### Identidade e paleta
- Fundo em tom bege claro/nude (`#EDE3D8`) em todos os slides
- Paleta de destaque em 4 cores sólidas, estilo terroso/orgânico:
  - Verde escuro "Verde You" (`#5C6B4E`)
  - Verde sálvia "Verde Fit" (`#A3AD84`)
  - Marrom rosado "Marrom" (`#B3766F`)
  - Bege claro "Bege" (`#EFE4D6`)
- Preto/marrom escuro para textos de título e elementos de contraste
- Logotipo/marca no canto superior esquerdo (ícone + nome da empresa) repetido em todos os slides
- Pequenos quadrados coloridos nos cantos (superior/inferior) como marca d'água de identidade visual

#### Tipografia
- Títulos grandes em sans-serif bold
- Corpo de texto pequeno, tom marrom acinzentado, com boa entrelinha
- Números/estatísticas em destaque em fonte grande e bold

#### Elementos recorrentes
- **Cards com cantos arredondados**: blocos de cor sólida (verde escuro/verde sálvia/marrom rosado/bege) contendo ícone + título curto + descrição, com um botão circular de seta (↗) no canto inferior direito
- **Tags/pills**: pequenas etiquetas arredondadas com texto curto (categorias, prazos, etc.)
- **Ícones de linha simples** dentro de círculos ou quadrados, associados a cada item de lista
- **Fotos com máscara arredondada**: imagens recortadas em formas orgânicas/arredondadas, usadas em pares ou blocos
- **Listas numeradas em grid 2x3 ou 3x1**: cada item com número em círculo colorido, título e descrição curta
- **Botões "LEARN MORE"** com seta, estilo pill, usados sobre fotos ou fundos escuros

#### Layout geral
- Slides de introdução/índice: título grande à esquerda, lista numerada com sublinhas descritivas
- Slides de conteúdo: título + subtítulo no topo, corpo dividido em blocos/cards de largura igual (grid 3 colunas ou 2 colunas)
- Slides de resultado/estatística: painel escuro (foto ou cor sólida) de um lado + cards de métricas do outro lado
- Espaçamento generoso, hierarquia visual clara, estética orgânica e sofisticada, sem poluição visual
### Visualização recomendada

| Informação | Componente ou gráfico | Codificação visual | Justificativa |
|---|---|---|---|
| [Métrica] | [Gráfico/tabela/card] | [Cor, rótulo e escala] | [Motivo] |

### Regras de classificação

- Simples: [limite configurado ou “Dado não disponibilizado nas fontes autorizadas”].
- Moderada: [limite configurado ou “Dado não disponibilizado nas fontes autorizadas”].
- Complexa: [limite configurado ou “Dado não disponibilizado nas fontes autorizadas”].
- Cada nível deve ser mostrado por cor, texto e ícone ou rótulo; nunca somente por cor.

### Acessibilidade e interação

**Contraste e legibilidade**
- Contraste mínimo AA (4.5:1 para texto, 3:1 para elementos gráficos) entre texto e fundo, especialmente nos cards coloridos (verde-lima, roxo, laranja)
- Tamanho de fonte legível (mínimo 12-14px no corpo, hierarquia clara nos títulos)

**Não depender só de cor**
- Cada classificação (Simples/Moderada/Complexa) deve ter cor + ícone + rótulo textual junto (ex.: bolinha verde + "Simples")
- Gráficos com padrões, texturas ou rótulos numéricos além da cor, para quem tem daltonismo

**Texto alternativo**
- Todo gráfico precisa de um texto alternativo (alt text) descrevendo o que ele mostra (ex.: "Gráfico de barras mostrando 12 programas Simples, 8 Moderados e 3 Complexos")
- Tabelas com legenda explicando o conteúdo

**Estrutura e navegação**
- Hierarquia de headings correta (H1 → H2 → H3) para leitores de tela
- Tabelas com cabeçalhos associados corretamente às colunas
- Ordem de leitura lógica (tab order) se for HTML/PDF interativo

**Interação (se for relatório interativo/dashboard)**
- Filtros e ordenação da tabela acessíveis via teclado
- Estados de foco visíveis (outline) em elementos clicáveis
- Estado vazio claro quando não há dados ("Nenhum resultado encontrado para o filtro aplicado")

**Formato do documento**
- Se for PDF: usar tags de acessibilidade (PDF/UA), permitir seleção/cópia de texto (não como imagem)
- Se for Markdown/HTML: usar elementos semânticos (tabelas com cabeçalho, figuras com legenda)

### Limitações

[Registre informações ausentes, ambiguidades ou elementos que não podem ser propostos sem confirmação.]

# RESTRIÇÕES

- Utilize somente as fontes autorizadas listadas no contexto.
- Não invente dados, pesos, limites, percentuais, arquivos, programas, tendências ou classificações.
- Não altere cálculos, regras de classificação ou valores fornecidos.
- Não utilize fontes externas para preencher lacunas factuais.
- Se uma informação essencial estiver ausente, escreva: “Dado não disponibilizado nas fontes autorizadas”.
- Diferencie claramente dados fornecidos, cálculos derivados, configurações e recomendações de design.
- Não trate um programa Complexo como erro; descreva-o como maior esforço estimado ou prioridade potencial de análise.
- Use no máximo três cores de destaque: verde-lima para Simples, roxo para Moderada e laranja para Complexa, salvo se o usuário definir outro mapeamento.
- Não use a cor como único indicador de significado; use rótulos, valores, legendas e contraste adequado.
- Evite gráficos 3D, gradientes decorativos, excesso de ícones, sombras pesadas e blocos extensos de texto.
- Use títulos claros, textos curtos, espaço em branco, cartões com bordas arredondadas e alinhamento em grade.
- Não copie textos, marcas, logotipos, imagens ou conteúdos da referência visual.
- Escreva em português brasileiro, com clareza e linguagem adequada ao contexto corporativo.
- Entregue todo o conteúdo em Markdown válido.
- Não inclua comentários sobre a revisão interna nem revele rascunhos ou auditoria.

# FORMATO DE SAÍDA

Entregue uma especificação de redesign em Markdown com a seguinte estrutura:

# Especificação de Redesign — Relatório de Complexidade Heurística

## 1. Visão geral

Informe o objetivo do redesign, o público-alvo e as fontes utilizadas.

## 2. Direção visual

Defina paleta de cores com códigos hexadecimais, tipografia, espaçamentos, raio de borda, ícones, contraste e princípios visuais derivados da referência.

## 3. Resumo executivo

Descreva os cards, indicadores principais, alertas e a forma de destacar o principal achado usando apenas os dados disponíveis.

## 4. Distribuição de complexidade

Especifique o gráfico para apresentar a distribuição de programas Simples, Moderados e Complexos, incluindo legenda, rótulos e texto alternativo.

## 5. Complexidade por programa ou arquivo

Especifique o gráfico comparativo, sua ordenação, filtros e a forma de identificar os maiores valores de complexidade.

## 6. Tabela de detalhes

Defina as colunas: Programa, Arquivo, Número de instruções, Peso total, Pontuação de complexidade, Classificação e Principal fator de complexidade. Inclua regras de ordenação, busca, filtro e estado vazio.

## 7. Pesos, limites e metodologia

Apresente a fórmula, os pesos e os limites fornecidos. Se não estiverem disponíveis, registre a limitação sem criar valores.

## 8. Recomendações de UX e acessibilidade

Liste até oito recomendações objetivas de usabilidade, acessibilidade e consistência visual.

## 9. Prioridades de análise

Organize em uma tabela com as colunas “Prioridade”, “Evidência disponível”, “Área impactada”, “Ação de design sugerida” e “Limitação ou dependência”.

## 10. Dados pendentes e limitações

Registre dados ausentes, ambiguidades, gráficos indisponíveis e informações que devem ser confirmadas antes da implementação.