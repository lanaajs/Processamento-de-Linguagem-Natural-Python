# Processamento de Linguagem Natural

Códigos desenvolvidos durante as aulas de Processamento de Linguagem Natural (PLN), utilizando Python no ambiente Google Colab para aplicação prática de conceitos e técnicas da área.

---

### Aula 1 – Configuração e Pré-processamento Básico
Código demonstra uma pipeline básica de **Processamento de Linguagem Natural** utilizando as bibliotecas **NLTK** e **spaCy**.

O script realiza:
- Instalação de pacotes e download de recursos (`pt_core_news_sm`, stopwords, punkt, rslp)
- **Pré-processamento de texto** com Regex (remoção de HTML, URLs, números e pontuação)
- **Tokenização** do texto
- **Stemming** e **Lematização**
- **Classificação gramatical (POS Tagging)**
- **Análise estatística** das classes gramaticais presentes no texto

O objetivo é ilustrar etapas fundamentais de **limpeza, análise e estruturação de textos para aplicações de PLN**.

---

### Aula 2 – Limpeza Avançada e TF-IDF
- Limpeza de corpus com remoção de stopwords e normalização de palavras
- Transformação de textos em vetores numéricos utilizando **TF-IDF** (unigramas e bigramas)
- Identificação das palavras mais relevantes do corpus
- Visualização com **barplot**
- Cálculo da **similaridade cosseno** entre documentos
- Função de busca por **documentos semelhantes** a uma consulta

---

### Aula 3 – Sistema de Triagem de Bugs
- Criação de base de dados de bugs com descrição e status
- Pré-processamento das descrições (limpeza, remoção de stopwords)
- Vetorização com **TF-IDF**
- Comparação de novos bugs com bugs existentes usando **similaridade cosseno**
- Sistema interativo de **triagem de bugs** para identificar possíveis duplicidades

---

### Aula 5 – Word2Vec e Mapa Semântico
- Treinamento de modelo **Word2Vec** com pequenas frases de contexto de backend, frontend e bugs
- Obtenção de **vetores densos** de palavras
- Identificação das palavras semanticamente mais similares
- Redução de dimensionalidade usando **PCA** para visualização 2D
- Criação de **mapa semântico** das palavras do vocabulário
