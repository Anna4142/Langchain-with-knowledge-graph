# Langchain-with-knowledge-graph
LLMs are great at understanding and interpreting unstructured data. This capability extends even to structured data when unstructured information is embedded within it. For instance, if the structured data includes a column labeled ‘abstracts’ containing unstructured text, the LLM can leverage that data to generate insightful results.


In the notebook I have-
1)Downloaded some metadata on World Bank documents using the World Bank API
2)Built an ontology using the metadata for the documents
3)Populated the ontology with instances of documents
4)Pulled in additional entities and relationships into the graph using Wikidata
5)Queried the KG directly using SPARQL
6)Used LlamaIndex to query the KG
