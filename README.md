# 📊 Inteligência de Negócios e Análise Estratégica: Case E-commerce Olist

Este repositório contém a solução do **Tech Challenge - Fase 1** da pós-graduação. O objetivo do projeto é transformar dados transacionais brutos da plataforma **Olist** (período de 2016 a 2018) em um ecossistema de Business Intelligence voltado a tomadas de decisões críticas por parte de **diretores, acionistas e potenciais investidores**.

A solução foi desenvolvida utilizando o **Power BI**, aplicando modelagem tridimensional (*Star Schema*), boas práticas de governança com centralização de métricas em DAX e foco profundo em *Storytelling* de negócios.

---

## 📺 Apresentação Executiva (Vídeo de 5 Minutos)

Conforme os requisitos de comunicação executiva estabelecidos para o desafio, gravamos um vídeo de defesa técnica direcionado ao corpo diretivo (C-Level). O vídeo aborda as dores identificadas, os dados coletados, os insights extraídos e as recomendações financeiras acionáveis.

▶️ [**Assistir à Apresentação Executiva no YouTube**](https://www.youtube.com) *(Substitua este link pelo link real do seu vídeo)*

---

## 👥 Autores do Projeto

O trabalho foi idealizado, higienizado e desenvolvido de forma colaborativa pelos integrantes:
* **Jailson da Rosa Barduino**
* **David da Silva Batista**
* **Leonardo José da Silva**
* **Yara Maria Santos Morais**
* **Raíssa Vaz Viriato**

---

## 📁 Estrutura de Pastas do Repositório

A arquitetura deste repositório foi planejada seguindo critérios rigorosos de **Governança de Dados**, separando o ciclo de vida do projeto em diretórios específicos:

```text
Pos_Tech_DTAT/
    ├── 📁 Dados/                                                # Base de dados transacionais completa (Arquivos Olist .csv)
    ├── 📁 Proposta/                                             # Documentação oficial e diretrizes do desafio (PDF do TC1)
    ├── 📁 Relatórios/                                           # Entregáveis de comunicação executiva
    │   ├── Relatório Estratégico Olist.pdf                      # Slides de suporte utilizados no vídeo de defesa
    │   └── Tech Challenge - Relatório Olist.pdf                 # Relatório analítico aprofundado para acionistas
    ├── fase_1_1_tech_challenge_base_relatorio_executivo.ipynb   # Script de ETL/Análise exploratória inicial (fora das pastas)
    └── README.md                                                # Visão geral e guia de navegação do projeto
