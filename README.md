# Multi-Source-RAG-Assistant-For-Students
On this particular project i will try to make a RAG pipeline in order to extract data from different data sources (e.g pdfs, word, vectordb, NoSQL etc) and get better answers without halluscinating from an LLM. 

# Architecture
![Περιγραφή της εικόνας](image.png)

An intelligent document retrieval and question-answering system built with modern AI technologies. Students can upload multiple data sources (PDFs, CSVs, databases) and ask natural language questions to receive accurate answers with source citations.

🎯 Key Features

📚 Multi-Source Data Integration


PDF Upload: Extract text from research papers, textbooks, and documents <br>
CSV Support: Import structured data from spreadsheets <br>

🔍 Hybrid Information Retrieval


BM25 Search: Keyword-based lexical matching for precise term matching <br>
Dense Retrieval: Neural embeddings for semantic understanding <br>

🤖 Local & Cloud LLM Support <br>

OpenAI API: Optional integration for GPT-4 (paid) <br>
No Vendor Lock-in: Switch between providers seamlessly <br>

📄 Document Processing <br>


Apache Tika: Extracts text from PDFs, Office documents, images <br>
Smart Chunking: Splits documents into optimal 500-token chunks <br>
Metadata Preservation: Tracks source, page numbers, timestamps <br>


🎯 Citation & Transparency <br>


Source Attribution: Every answer includes references to source documents <br>
Relevance Scores: Shows confidence in retrieved information <br>
Transparency: Users know exactly which documents contributed to answers 