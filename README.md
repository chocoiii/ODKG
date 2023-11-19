Copyright 2023 by Nanjing University of Posts and Telecommunications. 

Time: 19/11/2023  Authors:  Wenbo Zhou & Weizhuo Li & Bianyu Yang 

Mail: b20090724@njupt.edu.cn & liweizhuo@amss.ac.cn & b20090721@njupt.edu.cn

Description: [ODKG](http://www.odkg.com.cn) is an official document knowledge graph. You can use its original resources and visit the [website](http://www.odkg.com.cn/odkg/) to enjoy its services (User name: admin Password: 123456).

## 1. Introduction：
In this project, we present an official document knowledge graph, namely ODKG, which aims to collect the documents for effective management. 

We present the framework of ODKG comprehensively, including designed lightweight ontology, feature extraction algorithm for few-shot samples, and knowledge alignment method for entity alignment, by which these documents could share more linkages with each other. 
Moreover, we lists three potential applications of ODKG, which are helpful for managers and can improve
the efficiency of their document management.


## 2. Usage:
ODKG consists of five important resources, including Ontology (Knowledge Schema), Statistics of official documents, Structured document, Test data for document archiving and element extraction.

### Ontology:
We design one lightweight ontology of documents. It can bring a well-defined schema of collected documents so that these documents could share more linkage with each other.
It contains 38 basic classes, 9 relations and 29 properties. 

For the this file, it needs to install [protege](https://protege.stanford.edu/) to open it.


### Statistics of official documents:
This dataset is statistics of crawlled documents from  from the Ministry of Industry and information technology, nuclear safety administration, the Ministry of Science and Technology, and the Government official website.


### Encyclopedias:
This dataset contains the structureed triples of documents contained extracted value of elements.


### Test data:
It is corpus to test the models for the tasks of Document Archiving and Element Extraction.


## 3. Use-Cases:
We list the main use-cases of [ODKG](http://www.odkg.com.cn) for effective management. 

- **Semantic Retrieval**: ODKG can achieve semantic retrieval. For example, if users query one document, ODKG can display its comprehensive structured information to them in the form of knowledge cards. Benefited from this case, managers can quickly understand the key contents of documents. 
- **Association Discovery**. ODKG can recommend some similar documents for managers, which is helpful for them to further analyze the reliability and substation of other news and public sentiments.
- **Auxiliary Question-Answering**. This service provides quick and accurate consultation for managers, which is helpful for them to make better decisions. Nevertheless, it still depends on the scale of ODKG and the quality of extracted elements.