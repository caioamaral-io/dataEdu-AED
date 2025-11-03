# dataEdu

Projeto desenvolvido para a disciplina de **Projetos** da **CESAR School**, com foco na **Análise Exploratória de Dados (AED)**.

---

## Sobre o projeto

O **dataEdu** tem como objetivo explorar dados reais do **ENEM (2020–2023)**, aplicando estruturas de dados e técnicas de análise para **extrair, integrar, processar e visualizar informações**, auxiliando na tomada de decisões baseadas em dados.

---

## Principais Datasets

### Microdados do ENEM
Conjunto detalhado de informações sobre os participantes e suas provas, composto por:

- **Itens da prova:** questões aplicadas, área de conhecimento e gabarito.  
- **Cadastro dos participantes:** idade, sexo, escolaridade, código INEP da escola e município.  
- **Resultados:** notas obtidas nas diferentes áreas por cada participante.

### Catálogo de Escolas do INEP
Informações institucionais sobre mais de **226 mil escolas de educação básica no Brasil**, incluindo:

- Endereço e localização  
- Modalidade e etapa de ensino  
- Porte e categoria administrativa (**pública/privada**)  
- Dependência administrativa (federal, estadual, municipal ou privada)  
- Situação de funcionamento  

---

## Etapas do Processamento de Dados

1. **Remoção:** exclusão de valores nulos e colunas irrelevantes.  
2. **Padronização:** ajustes de variáveis e formatos.  
3. **Integração:** consolidação dos quatro anos em um único dataset.  
4. **Redução:** redução de **16 milhões** para **124 mil registros (0,8%)**.

---

## Resultados da Análise Exploratória

- **Crescimento de Participação:** aumento de **26%** nos inscritos (2020–2023), indicando maior acesso e conscientização.  
- **Distribuição por Tipo de Escola:** **76%** dos participantes são da rede pública, reforçando o papel do ENEM na democratização do ensino superior.  
- **Nível Socioeconômico x Tipo de Escola:** correlação direta entre renda e tipo de escola; maior renda → escolas privadas.  
- **Desempenho x Renda Familiar:** maior renda familiar → notas mais altas, especialmente em Matemática e Redação.  
- **Distribuição por Faixa de Renda:** 37,9% com até 1,5 salário mínimo; mais de 60% com até 3 salários mínimos.  
- **Desempenho por Área – Escola Pública x Privada:** estudantes de escolas privadas apresentam médias superiores em todas as áreas, principalmente Matemática, Redação, Ciências Humanas e Linguagens.  
- **Desempenho Médio por Cor/Raça:** disparidade significativa, maior diferença entre brancos (562) e indígenas (491).  
- **Acesso a Tecnologias:** desigualdade digital impacta a aprendizagem; diferença de 20% na posse de computadores entre grupos.
