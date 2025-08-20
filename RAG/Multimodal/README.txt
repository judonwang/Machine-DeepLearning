Multimodal RAG using langchain; 

Current checklist:

Currently testing multimodal extraction (text, images, tables from PDF) using unstructured partition.
--- partition_pdf extracts the text and images, but tables do not seem to be outputted as a table object.
--- partition does find tables 

LLM
Finding a model that can perform image to text so I can describe/summarize image contents from the PDF
--- Currently trying llava-1.5-7b-hf using huggingface, as the model is open source
------ Was able to make a summarization on a simple image of a dock; trying on images from the PDFs I am trying

Vector DB
Haven't decided on which one to use

RAG
Finish above first
