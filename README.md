# Development-of-a-Multi-Agent-Chatbot-for-Crime-Reporting
This project presents a multimodal, multi-agent AI crime reporting assistant designed to improve the accuracy, accessibility, and completeness of digital crime reporting. Unlike traditional chatbot-based reporting systems that primarily rely on text input, this assistant integrates Large Language Models (LLMs), computer vision, Retrieval-Augmented Generation (RAG), conversational memory, and speech technologies to produce structured, legally informed crime reports.

The system enables users to report incidents using text, images, and voice while automatically extracting critical information, classifying offences, and generating comprehensive reports for law enforcement.

Motivation

Many existing crime reporting platforms suffer from several limitations:

Depend primarily on text-based interactions.
Have limited ability to interpret images and contextual evidence.
Provide little or no legal guidance.
Often produce incomplete or ambiguous reports.
Struggle to extract structured information from free-text narratives.

These limitations can lead to inconsistent assessments, delayed incident triage, and under-reporting of crimes.

This project addresses these challenges by combining multimodal AI techniques with legal knowledge retrieval and structured information extraction.

Key Features
Multimodal crime reporting
Text-based incident reporting
Image analysis using Vision Transformers and GPT-4o Vision
Speech-to-Text for voice reporting
Text-to-Speech for improved accessibility
LLM-powered reasoning
GPT-4o-mini for crime classification
GPT-4o for contextual scene understanding
Multi-agent workflow for intelligent decision-making
Legal Retrieval-Augmented Generation (RAG)
Retrieves relevant provisions from the Theft Act 1968
Grounds responses using verifiable legal references
Reduces hallucinations during legal reasoning
Conversational Memory
Maintains context across multiple interactions
Supports follow-up questions and incident clarification
Structured Information Extraction
Automatically extracts:
Incident date and time
Location
Suspect descriptions
Victim information
Weapons
Injuries
Evidence
Stores structured records in CSV format
Automated Report Generation
Generates professional PDF crime reports
Includes annotated images
Conversation transcript
Unique incident identifiers
Structured case summaries
System Architecture

The assistant combines multiple AI components within a late-fusion architecture, including:

GPT-4o-mini
GPT-4o Vision
Vision Transformer (ViT)
Retrieval-Augmented Generation (RAG)
Conversational Memory
Speech-to-Text
Text-to-Speech
Schema-based Entity Extraction

These components work together to produce accurate, context-aware, and legally grounded crime reports.

Evaluation

The system was evaluated using multiple public datasets.

* Baton Rouge Crime Incident Dataset
* GPT-4o-mini demonstrated strong performance for crime classification.
* Roboflow Crime Dataset
* Vision Transformer achieved high classification performance.
* GPT-4o-mini produced comparable results.
* GPT-4o Vision improved contextual interpretation of crime scene images.

The combined multimodal pipeline produced accurate offence classification, coherent multimodal reasoning, and high-quality structured reports.

Applications

This framework can support:

* Digital crime reporting
* Law enforcement triage
* Public safety applications
* Incident documentation
* AI-assisted legal information retrieval
* Research into multimodal AI systems

Project Contributions

This project was developed as a supervised research project.

Project Supervisor: Dr Funmilola Fagbola

* Conceived the project and defined the research objectives.
* Designed the overall system architecture.
* Designed and implemented the Retrieval-Augmented Generation (RAG) and conversational memory components.
* Guided implementation, debugged the codebase, reviewed technical decisions, and supervised project completion.

Student Developer: Samuel Sunny Eke

* Implemented other system modules under supervision.
* Implemented several system components under supervision and integrated the modules into the final application following the agreed system design.

The repository is hosted under my GitHub account because the student does not currently maintain a GitHub account.
