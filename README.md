[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vZ6sAE2k)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19764307)

# Projeto Integrador III - Template Quarto

Este repositório é um modelo de documentação para o Projeto Integrador III dos cursos de Ciência de Dados e Machine Learning do CEUB. Ele está formatado segundo as normas da ABNT e estruturado com o sistema Quarto.

## 📄 Estrutura

- `index.qmd`: introdução geral
- `01-introducao.qmd`: contexto e objetivos
- `02-metodologia.qmd`: tecnologias, ferramentas e processos
- `03-desenvolvimento.qmd`: arquitetura, código e decisões
- `04-resultados.qmd`: imagens, gráficos, resultados
- `05-conclusao.qmd`: aprendizados e próximos passos
- `referencias.qmd`: lista de referências (com suporte `.bib`)
- `refs.bib`: arquivo BibTeX para citações
- `contracapa.tex`: contracapa em LaTeX para ABNT
- `imagens/`: coloque aqui capturas de tela e diagramas
- `_quarto.yml`: configurações do projeto

## 🚀 Como Usar

### Localmente (RStudio ou terminal)

1. Instale o Quarto: https://quarto.org/docs/get-started/
2. Certifique-se de que você possui LaTeX instalado (ex: [TinyTeX](https://yihui.org/tinytex/))
3. No terminal, rode:

```bash
quarto render
```

### Alternativa com GitHub Actions (renderização automática - opcional)

Será adicionado um arquivo `.github/workflows/render.yml` para gerar o PDF automaticamente a cada commit.

## 📌 Regras

- Documentação é obrigatória e será avaliada com base na completude e clareza.
- O código deve estar hospedado em repositório GitHub e ser referenciado neste relatório.

## 👨‍🏫 Suporte

Em caso de dúvidas, consulte os materiais no Moodle ou entre em contato com o professor responsável.

# Conteúdo Técnico Adicionado — Relatório de Captação

A nova etapa do projeto incorpora uma análise completa dos jogadores captados no DF, com os seguintes indicadores técnicos: 
relatorio_captacao_df

## 📊 Distribuição dos atletas

Idade predominante entre 12 e 14 anos, o que representa a fase mais fértil de evolução técnica e cognitiva.

Altura entre 138–170 cm, média aproximada de 155 cm — diversidade física preservada.

Posição com maior volume: meias e atacantes; goleiros minoria.

## 🌍 Distribuição geográfica

Regiões com maior captação:

Gama, Ceilândia, Samambaia, Taguatinga, Plano Piloto

Regiões pouco representadas → oportunidades de expansão futura.

## ⚽ Indicadores de performance avaliados
Métrica	Descrição
Passes decisivos por idade	13–14 anos apresentam maior criação ofensiva
Recuperações x disputas vencidas	Correlação positiva forte (perfil defensivo completo)
Ranking de dribles certos	Identifica jogadores com maior poder de desequilíbrio
Radares por posição	Perﬁs e estilos distintos entre atacantes, meias e defensores

## 📂 Base de Dados Utilizada — Captação nas Escolas (CSV)

Esta base contém os dados originais utilizados para gerar os gráficos e análises estatísticas apresentadas no Relatório de Captação, incluindo informações físicas, regionais e de desempenho tático-técnico.

Variável	Descrição
idade	Faixa etária dos atletas avaliados
altura	Estatura em cm — variando entre 138–170 cm
posicao	Função exercida em campo (defensor, meia, atacante, goleiro)
pe_dom	Pé dominante do atleta (destro/canhoto)
regiao	Cidade/área de origem no DF
passes_decisivos	Média de criação ofensiva por idade
disputas_vencidas	Indicador de combatividade e duelos individuais
recuperacoes	Relação com a eficiência defensiva e pressão/coleta
dribles_certos	Métrica de desequilíbrio ofensivo 1x1
...	Demais atributos complementares analisáveis
