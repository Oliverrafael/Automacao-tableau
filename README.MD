# Descrição do projeto
### Contexto
Você trabalha como analista de anúncios em vídeo na agência de publicidade Sterling & Draper. Você dedica muito tempo analisando vídeos de tendências no YouTube para determinar qual conteúdo merece atenção de marketing.

# Objetivo do projeto
Você precisa discutir o conteúdo do dashboard, seu layout e os dados que precisam ser exibidos com Melanie e Ashok. Em seguida, converse com os administradores de banco de dados e engenheiros de dados e descubra onde e como os dados necessários são coletados e como podem ser transformados. Por fim, desenvolva o pipeline e o dashboard.

## Datasets
- trending_by_time.csv

# Descrição dos dados
- record_id — chave primária
- region — país / região geográfica
- trending_date — data e hora
- category_title — a categoria de vídeo
- videos_count — o número de vídeos na seção de tendências

## Etapas para conclusão do projeto

# Etapa 1:  Elaboração de Requisitos Técnicos
Cada vídeo tem uma categoria específica (entretenimento, música, notícias e política etc.), região e data de tendência. 
Um vídeo pode estar na seção de tendências por vários dias seguidos.
Toda semana, os novos funcionários Melanie e Ashok fazem as mesmas perguntas:
- Quais categorias de vídeo foram tendências na semana passada?
- Como foram distribuídos entre as várias regiões?
- Quais categorias foram especialmente populares nos Estados Unidos?

# Contexto:
Em sua sexta semana de trabalho, você decide que está na hora de automatizar o processo. Você vai fazer um dashboard para Melanie e Ashok.

Depois de conversar com os gerentes e administradores de banco de dados, você elaborou breves requisitos técnicos:

- Objetivo dos negócios: analisar o histórico de vídeos de tendências no YouTube
- Com que frequência o dashboard será usado: pelo menos uma vez por dia
- Usuário do dashboard de destino: gerentes de planejamento de anúncios em vídeo
- Conteúdo de dados do dashboard:
- Vídeos de tendências do passado, divididos por dia e categoria
- Vídeos de tendências, divididos por países
- Uma tabela de correspondência entre categorias e países
- Parâmetros segundo os quais os dados devem ser agrupados:
- Data e hora da tendência
- Categoria de vídeo
- País
- Os dados:
- Histórico de tendências — valores absolutos com divisão por dia (dois gráficos: - números absolutos e proporção percentual)
- Eventos, discriminados por países — valores relativos (% de eventos)
- A correspondência entre as categorias e os países — valores absolutos (uma tabela)
- Importância: todos os gráficos são igualmente importantes

# Etapa 2: Construindo o dashboard
* O filtro de data e hora e o filtro de país devem modificar todos os gráficos do dashboard. Observe que os gráficos de histórico de interação "Histórico de tendências" e "Histórico de tendências, %" devem ter data e hora ao longo do eixo X. "Histórico de tendências" deve ter o número de vídeos na seção de tendências (o campo videos_count ) ao longo do eixo Y, e o outro gráfico deve ter a porcentagem lá.

Para construir o dashboard, conclua as etapas seguintes:

* No Tableau Public, use trending_by_time.csv (consulte a parte inferior desta página para fazer download) para criar um dashboard modelado no rascunho.

* Publique o dashboard no servidor do Tableau Public. Certifique-se de que seja acessível para todos: tente abri-lo em vários navegadores. Se não estiver acessível, o revisor não poderá verificá-lo.

* Use seu dashboard para responder às perguntas que os gerentes fizeram:

* Quais categorias de vídeo estão em alta com mais frequência?
* Como foram distribuídos entre as regiões?
* Quais categorias foram especialmente populares nos Estados Unidos? Houve alguma diferença entre as categorias populares nos EUA e as populares em outros lugares?
* Prepare uma breve apresentação contendo um relatório (respostas a estas questões e gráficos).


## 🛠 Habilidade
Tableau
Power point

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Oliverrafael
)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafael-oliveira-528400335/
)