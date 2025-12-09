# Projeto 1 – Eduardo | Plataforma NexFut

Plataforma de Recrutamento e Inclusão no Futebol

---
## Definição do Problema

Existe uma grande quantidade de jovens talentos no futebol que não têm acesso a oportunidades para mostrar seu potencial, especialmente em comunidades de baixa renda. Ao mesmo tempo, olheiros enfrentam dificuldades para localizar e avaliar esses atletas com precisão e agilidade.

A NexFut surge como uma solução digital que conecta esses dois mundos, permitindo que atletas se cadastrem, compartilhem seus dados e vídeos, e recebam análises automatizadas de desempenho. Assim, olheiros poderão filtrar, acompanhar e selecionar jogadores com base em informações relevantes e objetivas.

---

## Público-Alvo

- Jovens atletas de baixa renda, com interesse em ingressar no futebol profissional  
- Escolas de futebol e projetos sociais  
- Olheiros, agentes e clubes em busca de novos talentos  
- Técnicos e profissionais da área esportiva

---

## Objetivos de Negócio

- Promover a inclusão social através do esporte  
- Reduzir a distância entre talentos emergentes e oportunidades profissionais  
- Criar um ecossistema digital eficiente para captação de atletas  
- Oferecer uma base de dados rica e acessível para análise técnica de desempenho  
- Gerar valor para os clubes e olheiros por meio de decisões mais assertivas

---

## Funcionalidades da Plataforma NexFut

1. **Cadastro e Perfil do Atleta**  
   - Dados pessoais e posição em campo  
   - Upload de vídeos de jogos ou treinos  
   - Histórico esportivo e estatísticas  

2. **Avaliação Técnica Automatizada**  
   - Análise de vídeos com uso de IA (movimentação, passes, finalizações etc.)  
   - Feedbacks personalizados com sugestões de melhorias  

3. **Painel para Olheiros**  
   - Filtros por idade, posição, região, desempenho técnico  
   - Visualização de vídeos e gráficos de desempenho  
   - Contato direto com o atleta ou seu responsável  

4. **Área de Projetos Sociais**  
   - Espaço para instituições cadastrarem atletas  
   - Rankings locais por comunidade ou escola  

5. **Gamificação e Incentivos**  
   - Pontuação por participação em desafios  
   - Selos de destaque (ex: “melhor jogador do mês”)  
   - Ranking nacional e regional  

6. **Notificações e Oportunidades**  
   - Alertas sobre peneiras, seletivas e campeonatos abertos  
   - Mensagens de interesse enviadas por olheiros ou clubes  

---

## Tecnologias Sugeridas

- Backend: Node.js ou Python (Django/Flask)  
- Banco de dados: MongoDB ou PostgreSQL  
- Frontend: React ou Next.js  
- Armazenamento de vídeos: AWS S3 ou Firebase Storage  
- Análise de vídeo: OpenCV + TensorFlow / MediaPipe  
- Autenticação: OAuth ou Firebase Auth  
- Hospedagem: Vercel, Heroku ou AWS

---

## Fluxo Básico de Uso

1. O atleta se cadastra e envia seus dados e vídeos  
2. A NexFut processa e analisa os dados  
3. Os olheiros visualizam os perfis e avaliam os atletas  
4. Em caso de interesse, o olheiro entra em contato para uma seletiva  
5. A plataforma registra a evolução do atleta ao longo do tempo

---

## Indicadores de Sucesso

- Número de atletas cadastrados  
- Número de olheiros ativos  
- Conexões bem-sucedidas (ex: convocações, testes)  
- Crescimento em regiões periféricas  
- Aumento de visibilidade para projetos sociais parceiros


## Simulação e Análises de Dados

Utilizamos dados fictícios (em formato `.csv`) contendo informações simuladas de jogadores, clubes, torneios e ligas. Esses dados foram usados para produzir análises como:

- Evolução de cadastros mensais de atletas
- Distribuição percentual de jogadores por país (gráfico em pizza)

As análises estão documentadas no relatório final entregue em `.Rmd` e `.html`.

---

## Papéis na Equipe

- **Matheus Lira** – Criação do relatório em RMarkdown, geração de gráficos.
- **Eduardo Hirle** – Desenvolvimento da estrutura do repositório, descrição funcional da plataforma, documentação.
- **Camila Niederauer** - Documentação da base de dados.
- **Pedro Aragão Dorneles** - Incremento na documentação do projeto.
- **Manuela Raupp** - Apoio na documentação.
- **Arthur Rocha** - Conclusão.
- **Gabriel Poppi** - Tecnologia e ferramentas.


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
disputas_vencidas	Indicador de combatividade e duelos individuais
recuperacoes	Relação com a eficiência defensiva e pressão/coleta
dribles_certos	Métrica de desequilíbrio ofensivo 1x1
...	Demais atributos complementares analisáveis
