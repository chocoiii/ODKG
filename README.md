Copyright 2023 by Nanjing University of Posts and Telecommunications. 

Time: 2/6/2023  Authors:  Wenbo Zhou & Weizhuo Li & Bianyu Yang 

Mail: b20090724@njupt.edu.cn & liweizhuo@amss.ac.cn & b20090721@njupt.edu.cn

Description: [ODKG](http://www.odkg.com.cn/odkg/) is an official document knowledge graph. You can use its original resources and visit the [website](http://www.odkg.com.cn/odkg/) to enjoy its services (User name: admin Password: 123456).

## 1. Introduction：
In this project, we present an official document knowledge graph, namely ODKG, which aims to collect the documents for effective management. 

We design a lightweight ontology of official documents. It can bring a well-defined schema of collected documents so that they could share more linkage with each other.
We present the algorithms of element extraction, document archiving knowledge alignment during the process of construction, and further evaluate the corresponding algorithms with our constructed datasets. Experimental results show
that several algorithms can be competent to above tasks to some extent. 
Finally, we list three use cases of ODKG that are helpful for managers and can improve
the efficiency of their document management.


## 2. Usage:
ODKG consists of five important resources, including Ontology (Knowledge Schema), Statistics of official documents, Structured document, Test data for document archiving and element extraction.

### Ontology:
We design one lightweight ontology of documents. It can bring a well-defined schema of collected documents so that these documents could share more linkage with each other.
It contains 39 basic classes, 10 relations and 30 properties. 

For the this file, it needs to install [protege](https://protege.stanford.edu/) to open it.


### Statistics of official documents:
This dataset is statistics of crawlled documents from  from the Ministry of Industry and information technology, nuclear safety administration, the Ministry of Science and Technology, and the Government official website.


### Encyclopedias:
This dataset contains the structureed triples of documents contained extracted value of elements.


### Test data:
It is corpus to test the models for the tasks of Document Archiving and Element Extraction.


## 3. Use-Cases:
We list the main use-cases of [ODKG](http://www.odkg.com.cn/odkg/) for effective management. 

- **Semantic Retrieval**: ODKG can achieve semantic retrieval. For example, if users query one document, ODKG can display its comprehensive structured information to them in the form of knowledge cards. Benefited from this case, managers can quickly understand the key contents of documents. 
- **Association Discovery**. ODKG can recommend some similar documents for managers, which is helpful for them to further analyze the reliability and substation of other news and public sentiments.
- **Auxiliary Decision-Making**. The comprehensive information of ODKG and its services can assist users to make better decisions. Nevertheless, it depends on the scale of ODKG and the quality of extracted elements.