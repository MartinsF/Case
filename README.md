# Projetos de Python

Este repositório contém projetos diversos em Python. Utilize os arquivos `requirements.txt` ou `environment.yml` para configurar o ambiente conforme sua preferência:

- `environment.yml` → para uso com **conda**
- `requirements.txt` → para uso com **pip**

---

## Projeto: Consumo de Energia

Este projeto analisa dados referentes às características e à rotina de alguns edifícios para os quais uma fornecedora de energia oferece serviços. Junto a isso, temos dados ambientais e o consumo de energia desses edifícios em diferentes horários ao longo de 1 ano.

O objetivo é desenvolver um **modelo preditivo** para estimar o consumo de energia de um edifício com base em:

- Suas características estruturais
- Condições ambientais
- Horário e dia de coleta do dado

---

###  Dados

Os dados estão no arquivo `Dados.zip`, contendo arquivos `.csv` com dados de consumo ao longo das horas de cada mês do ano.
url no git: 

# URL do CSV no GitHub
url_mar = 'https://raw.githubusercontent.com/MartinsF/Case/main/Dados/Consumo_Energia_Marc%CC%A7o.csv'


---

###  Descrição das Variáveis

O conjunto de dados contém **12 colunas**, descritas a seguir:

1. **Mês**: Mês do ano no momento da coleta do dado.
2. **Hora**: Hora do dia no momento da coleta do dado.
3. **Dia da Semana**: Dia da semana no momento da coleta do dado.
4. **Feriado**: Indica se o dia era feriado ou não.
5. **Temperatura**: Temperatura (°C) no momento da coleta.
6. **Umidade**: Percentual de umidade no momento da coleta.
7. **Metros Quadrados**: Área total do edifício.
8. **Ocupação**: Número de pessoas no edifício no momento da coleta.
9. **Uso Aquecimento/Ventilação/Ar-condicionado**: Equipamento estava ligado ou não.
10. **Uso Sistema Iluminação**: Indica se a iluminação estava ligada.
11. **% Energia Renovável**: Percentual da energia proveniente de fontes renováveis.
12. **Consumo de Energia**: Quantidade de energia fornecida pela CPFL Energia.

---


