# 26_1-Joao-Victor-Machado-Rangel
**Título do TCC: DETECÇÃO DE MISOGINIA EM MENSAGENS TEXTUAIS**
**Alunos: João Victor Machado Rangel** <!-- substitua pelos nomes dos alunos -->
**Semestre de Defesa: 2026-1** <!-- ano-semestre, exemplo: 2025-2 -->

[PDF do TCC](Detecção_de_Misoginia_em_Mensagens_Textuais_CEFET_RJ_TCC2.pdf)


# TL;DR

Para executar todos os códigos precisa do apenas executar os ambientes através do Google Colab e os códigos dos notebooks anexados, sendo necessário dar upload nos CSVs nos respectivos ambientes.

Para rodar:
Rodar os notebooks em sequência.

[Notebook 1](Notebook 1 - Primeira_extração_do_forms.ipynb)

[Notebook 2](Notebook 2 - Criação da base de dados.ipynb)

[Notebook 3](Notebook 3 - Tratamento_da_tabela_classificação_Final.ipynb)

[Notebook 4](Notebook 4 - Treinamento_do_modelo.ipynb)

# Descrição Geral
Este estudo investiga a disseminação da misoginia nas redes sociais brasileiras e propõe
uma abordagem fundamentada em recuperação lexical e validação humana para apoiar a
sua detecção automatizada. O trabalho apresenta o desenvolvimento do LexMis-BR, um
léxico expandido construído de forma colaborativa para superar a escassez de recursos
linguísticos específicos para o português do Brasil. A metodologia, aprovada pelo Comitê
de Ética em Pesquisa , integrou a coleta de mensagens no X com a rotulação realizada por
voluntários, buscando produzir recursos alinhados ao contexto sociolinguístico nacional.
A etapa de rotulação evidenciou que, embora a recuperação lexical seja útil para orientar a
construção do corpus, ela se mostra insuficiente como critério de decisão final devido à ambiguidade
inerente aos enunciados, o que reforça a necessidade do julgamento contextual
humano na consolidação de dados confiáveis. Foram avaliados modelos supervisionados
de classificação, e os resultados indicam que os recursos produzidos são relevantes para
o avanço do estudo computacional da misoginia, oferecendo uma base empírica para o
aprimoramento de sistemas de moderação de conteúdo no cenário brasileiro.


# Funcionalidades
<!-- Descreva as principais funcionalidades do seu código. Exemplo: -->
* Primeira extração das respostas do Forms 1
* Criação da base de dados 2
* Tratamento da tabela classificação 3
* Treinamento do modelo supervisionado de classificação 4


# Arquitetura

A metodologia é estruturada em quatro grandes etapas: criação
do léxico de termos misóginos, coleta de mensagens em redes sociais, método
de rotulagem dos textos misóginos e avaliação inicial de modelos supervisionados de
classificação. As etapas são ilustradas pela figura a seguir:

<img width="878" height="241" alt="metodologia" src="https://github.com/user-attachments/assets/30ec0ed9-fedb-4703-a425-819d7ce0cff2" />


# Dependências


<!-- Apresente a lista de dependências do seu código. Quando necessário, incluia links. Exemplo: -->
* Google Colab
* Todas as dependências são automaticamente instaladas na máquina virtual do Google Colab


# Execução

<!-- Descreva como instalar/executar seu código. Exemplo: -->
Abra os notebooks no google colab e execute-os em sequência.

 
