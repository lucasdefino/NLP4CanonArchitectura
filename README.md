# Natural Language Processing Applied to the Discovery of an Architectural Canon

This project aims to develop a methodology to "decipher" the architectural canon of the 20th century—that is, to identify data patterns that reveal how the canon has evolved over time. The architectural canon includes noteworthy works that are essential in the education of professionals and artists and in setting high standards of quality.

Framed within the field of Digital Humanities, this research applies artificial intelligence to interpret large volumes of information from various written sources. The primary goal is to identify as many architectural works as possible from a defined set of books and to build a database capable of answering key questions such as:

* Who designed each work?
* In which city and country is it located?
* When did its construction begin and end?

Additionally, the project conducts positional recognition within the text, distinguishing whether works appear in titles, paragraphs, or references—aiming to answer the question: *How influential was each work according to each author?*

The proposed methodology utilizes several Natural Language Processing (NLP) techniques:

1. **Named Entity Recognition (NER)** to identify architectural works in texts.
2. **Text Segmentation** to determine the contextual location of mentions.
3. **Retrieval-Augmented Generation (RAG)** to answer questions and populate the database.

### Model Performance:

* **Named Entity Recognition**: 69% accuracy
* **Text Classification**: 85% accuracy

**Retrieval-Augmented Generation Results:**

* Author Accuracy: 64%
* City Accuracy: 67%
* Country Accuracy: 57%
* Start Year Accuracy: 41%
* End Year Accuracy: 35%

### Key Findings:

1. While NER and Text Classification can achieve strong results, they are highly dependent on the quality and quantity of training data.
2. The RAG model performed well in extracting results but proved to be computationally intensive, with limitations in speed and cost.
