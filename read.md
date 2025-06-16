
# ⚖️  Veredicto - Pré-Análise de Litígios com LLM 

---

## 🚀 Visão Geral do Projeto

Este projeto tem como objetivo desenvolver uma plataforma interna para advogados que automatize a triagem inicial de processos judiciais. Utilizando modelos de linguagem (LLM), embeddings jurídicos e técnicas de Retrieval-Augmented Generation (RAG), o sistema avalia a viabilidade de novos casos com base em jurisprudência pública atualizada.

O sistema gera:

- **Score de viabilidade:** (Baixa | Média | Alta);
- **Justificativa preliminar automática** com referências a precedentes;
- **Painel estatístico interno** com taxas de sucesso por tipo de ação.

---

## 🎯 Problema que estamos resolvendo

- Escritórios de advocacia e departamentos jurídicos gastam tempo excessivo triando processos massificados.
- Grande volume de casos com baixa probabilidade de sucesso são ajuizados por falta de ferramentas de apoio à decisão.
- Pesquisar jurisprudência manualmente é demorado e pouco escalável.

---

## 💡 Solução proposta

- Entrada de casos via texto livre ou upload de documentos.
- Processamento com embeddings de jurisprudência e consulta via RAG.
- Análise de viabilidade baseada em jurisprudência real (STF, STJ, TRFs, JusBrasil).
- Geração automática de pareceres preliminares.
- Triagem de processos massivos de forma escalável.

---

## 🧑‍⚖️ Áreas de atuação inicial

- Direito do Consumidor  
- Direito Previdenciário (ex.: benefícios INSS)
- Planos de Saúde (ex.: negativas de cobertura)
- Causas repetitivas de alta demanda

---

## 🔗 Fontes Jurídicas Utilizadas

- 📄 STJ — Jurisprudência Superior  
  https://scon.stj.jus.br/SCON/jurisprudencia/doc.jsp

- 📄 TRFs — Exemplo TRF1  
[  https://portal.trf1.jus.br/portaltrf1/jurisprudencia/
](https://www2.cjf.jus.br/jurisprudencia/trf1/)
- 📄 STF — Repercussão Geral  
  https://portal.stf.jus.br/jurisprudencia/

- 📄 JusBrasil — Base agregada de jurisprudência  
  https://www.jusbrasil.com.br

---

## ⚙️ Arquitetura Técnica (MVP inicial, terá alterações)

- **Input:** Resumo do caso ou petição inicial (texto ou PDF)
- **Pré-processamento:** Extração e segmentação de texto
- **Embeddings:** OpenAI embeddings ou SentenceTransformers (estudando)
- **Banco Vetorial:** (estudando)
- **RAG:** LangChain como pipeline orquestrador
- **LLM:** GPT-4 / Claude 3 / LLaMA 3 (estudando)
- **Frontend:** React (estudando)
- **Painel Estatístico:** Streamlit Analytics ou PowerBI (estudando)

---

## 📅 Roadmap Inicial (8 Semanas)

| Semana | Entregas |
|--------|--------------------------|
| 1-2    | Coleta de dados + protótipo de input |
| 3      | Construção de embeddings e banco vetorial |
| 4-5    | Desenvolvimento inicial do RAG |
| 6      | Integração LLM + primeiros pareceres |
| 7      | Implementação do score de viabilidade |
| 8      | Painel estatístico e entrega do MVP |

---

## 🔬 Diferenciais da Solução

- Aplicação prática real de LLM no Direito Brasileiro.
- Busca automática de jurisprudência pública atualizada.
- Ajuda na tomada de decisão interna do escritório.
- Automatiza tarefas repetitivas e reduz custos operacionais.

---

## 🛡️ Limitações e Cuidados

- Sistema não substitui análise jurídica humana.
- Parecer gerado é preliminar e deve ser validado por advogados.
- Dependência da qualidade e atualização das bases jurídicas.

---

## 📌 Possíveis Extensões Futuras

- Inclusão de teses jurídicas (precedentes vinculantes STJ/STF).
- Treinamento com dados proprietários do escritório.
- Suporte a novas áreas do Direito (ex.: trabalhista, tributário).
- Geração automática de petições preliminares.

---

## 👨‍💻 Desenvolvedor Responsável

Projeto acadêmico desenvolvido por:

** Antônio Henrique, Gabriel Aragão, Marco Andrade e Maria Clara Barretto**  
Disciplina: Transformação Digital com IA  
Curso: Sistemas de Informação

---

## ⚖️ Disclaimer

Este projeto é acadêmico e experimental, e não constitui aconselhamento jurídico.

---
