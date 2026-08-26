
[Explique a decisão ou pergunta que esta seção ajuda o usuário a responder.]

### Dados apresentados

| Indicador | Valor | Regra, fonte ou campo de origem |
|---|---:|---|
| [Nome do indicador] | [Valor fornecido] | [Origem] |

### Estrutura visual

[Descreva a grade, a ordem de leitura, os cartões, tabelas, filtros e áreas de destaque.]

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

- [Descreva texto alternativo, contraste, legenda, filtro, ordenação ou estado necessário.]

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