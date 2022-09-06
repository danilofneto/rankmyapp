# B4 Bank APP Report

![question22](/images/folder.png)

O cliente B4 Bank é um aplicativo do setor financeiro que tem como objetivo conseguir uma maior visibilidade e retenção de usuários de forma orgânica.

 Como esse mercado tem crescido muito e é muito competitivo, ele resolveu investir em ASO com o RankMyApp, focando seus esforços não só em visualizações mas também em instalações, ou seja, não apenas os usuários visualizarão o app na loja como também irão instalá-lo e utilizá-lo por um longo período de tempo. (Retenção de 15-30 dias).

 Através do nosso sistema, recebemos informações relacionadas às instalações, concorrentes, performance das palavras-chave (keywords), notas e comentários deixados na loja.

 # Business Problem

 O B4 Bank é cliente há alguns meses e eles gostariam de saber como tem sido a performance do app. Como trabalhamos com ASO para este cliente, o que mais nos interessa são as métricas de Canal Orgânico.
 
  É a partir deste KPI que nos baseamos para verificar o impacto do nosso trabalho.

  Realize uma análise exploratória dos dados para ajudar o time de negócios tomar as melhores decisões. 

  # Os Dados

  Os Dados foram retirados da loja de aplicativos de celular e originalmente contém as seguintes features:

**Date**: Data de retenção dos dados

**Package Name**:	Nome do Aplicativo

**Acquisition Channel**:	Canal do qual foi feita a aquisição do usuário

**Store Listing Visitors**:	Número de visitas ao aplicativo na loja

**Installers**:	Número de instalações do aplicativo

**Visitor-to-Installer**: conversion rate	Taxa de visitas convertidas em instalações (Installers/Store Listing Visitors)

**Installers retained for 1 day**:	Instalações Retidas por 1 dia

**Installer-to-1 day retention rate**:	Taxa de instalações retidas por 1 dia

**Installers retained for 7 days	Instalações**: Retidas por 7 dias

**Installer-to-7 day retention rate**:	Taxa de instalações retidas por 7 dias

**Installers retained for 15 days**:	Instalações Retidas por 15 dias

**Installer-to-15 day retention rate**:	Taxa de instalações retidas por 15 dias

**Installers retained for 30 days**:	Instalações Retidas por 30 dias

**Installer-to-30 day retention rate**:	Taxa de instalações retidas por 30 dias

# Top Insights
### **- Hipótese 1: Canal de aquisição orgânico representa a maior quantidade de visualizações na loja de aplicativos.** 
![image](/images/bar_total_instalacoes.png)

Hipótese verdadeira. No período analisado o canal de aquisição Organic representou 33706 instalações, um total de 56.50% do total de instalações.
![image](/images/pie_total_visualizacoes.png)

### **- Hipótese 2: Canais de aquisição com maior número de visitas na loja possuem um maior número de instalações.**

![image](/images/bar_total_visualizacoes.png)
Hipótese verdadeira. Os 2 canais com maior número de visitas são respectivamente os canais que tiveram um maior número de instalações após visita na loja. 

Organic: 183575 visualizações e 33706. Total de 76,64% das visualizações no período analisado.

Third-Party: 107365 visualizações e 9650 instalações. Total de 21.37% das visualizações no período analisado.

![image](/images/pie_total_visualizacoes.png)

### **- Hipótese 3: Canais de aquisição com mais instalações possuem um maior número de clientes retidos por mais de 30 dias.**

Os 2 canais com maior número de visitas são respectivamente os canais que mantiveram mais clientes no período de 30 dias
![image](/images/bar_retidas_30.png)

### Hipótese 4: Clientes que permacem na mais por mais dias tendem a continuar com as instalações.

Hipótese verdadeira. A diferença no total de instalações entre os clientes retidos por 7 dias a 30 dias é menor do que de 1 a 7 dias.
![image](/images/bar_1_7_dif.png)
![image](/images/bar_7_15_dif.png)
![image](/images/bar_15_30_dif.png)

### Hipótese 8: Mais instalações são realizadas aos fins de semana.

Hipótese falsa. As instalações são maiores nos dias de semana (Terça, quarta e quinta-feira)
![image](/images/bar_instalacoes_semana.png)

# Conclusão
Com a análise dos dados foi possível identificar que o canal de aquisição Organic apresenta os maiores indicadores em todas as comparações com os demais canais, porém é possível melhor os indicadores e com o apoio da análise os times de negócio consiguirão tomar melhores decisões.

# Próximos passos de evolução:
- Criar novas features.

- Disponibilizar os dados em tabelas no BD e orquestrar sua atualização.

- Adicionar mais visualizações no Power BI.

- Treinar modelos de machine learning para estimar o total de instalações nos próximos meses.