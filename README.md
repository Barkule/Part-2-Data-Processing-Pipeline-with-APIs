# Part-2-Data-Processing-Pipeline-with-APIs
This project focuses on creating a custom data processing pipeline that integrates with OpenAI or Gemini API to transform raw, unstructured text data into structured JSON format. The pipeline aims to enhance data processing capabilities by leveraging both external and local language models.

Objective
The primary goal is to build a robust data processing pipeline that can efficiently handle text data, ensuring accurate and structured outputs.

Requirements
Setup the Pipeline:

Utilize the OpenAI or Gemini API to process raw text data, converting it into a structured JSON format with specified fields.
Prompt Engineering:

Design effective prompts for the API to ensure the generation of accurate and relevant outputs.
Implement Pydantic models to validate the structure of the API responses, ensuring data integrity and consistency.
Local Model Integration:

Set up a locally hosted language model (e.g., LLaMA) to process the same data pipeline, allowing for a comparison of results between the external API and the local model.
Error Handling:

Implement robust error handling mechanisms to gracefully manage API failures, rate limits, and invalid responses without relying on built-in batch-processing commands.
Deliverable
The final deliverable will include:

The complete pipeline code, including prompt engineering and validation scripts.
A comprehensive comparison report detailing the outputs from both the external API and the locally hosted model, highlighting differences and performance metrics.
