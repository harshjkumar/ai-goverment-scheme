# ai-goverment-scheme
This AI Government Scheme Advisor is a bilingual (English/Hindi) assistant helping Indian citizens understand public welfare schemes. It uses a hybrid system, first checking an internal database before using Google for live results. With voice input and conversational chat, it makes complex government data accessible and bridges the information gap
 
AI-Powered Government Scheme Advisor
A bilingual, conversational AI assistant designed to help Indian citizens discover and understand relevant public welfare schemes.

In the current era of Digital India, while access to information has broadened, the complexity and fragmentation of government scheme details remain a significant barrier for many citizens. This project directly confronts this challenge by creating a centralized, user-friendly platform that demystifies public welfare information. Many beneficial schemes are often underutilized due to a lack of awareness or confusion surrounding eligibility criteria. This AI advisor serves as an empathetic and accessible bridge, empowering individuals by translating complex government jargon into clear, actionable advice.

Key Features:
Bilingual Interface: As a core design principle for inclusivity, the entire application seamlessly switches between English and Hindi. This ensures the tool is accessible to a much wider demographic across the nation.

Conversational AI Chat: Moving beyond static forms, the advisor allows users to describe their situation in natural, everyday language. This intuitive approach makes it easy for anyone to get the help they need without prior knowledge of specific scheme names.

Voice Recognition: To further lower the barrier to access, particularly for users with limited literacy or those on mobile devices, the application incorporates a robust voice-to-text feature.

Hybrid Search Technology: The advisor's intelligence is powered by a sophisticated two-stage system.

Curated Knowledge Base: It first searches a fast and reliable internal database of key schemes, ensuring accuracy for common queries.

Live Web Search: If a query cannot be answered locally, it automatically leverages the Gemini API's grounding with Google Search to fetch the most up-to-date information, making its knowledge base virtually limitless.

Sourced & Trustworthy Answers: To build user trust, a critical component of any civic tech tool, all answers generated from web searches are accompanied by clickable links to the source articles.

Technology Stack:
Frontend: A clean, professional, and fully responsive user interface built with HTML and styled using Tailwind CSS for a modern, mobile-first experience.

Core Logic: All application interactivity, state management, voice recognition, and API handling are managed with modern JavaScript.

AI & NLP: The application is powered by the Google Gemini API, implementing a Retrieval-Augmented Generation (RAG) system for its internal knowledge and utilizing advanced grounding features for live web searches.

This project is a powerful demonstration of applying modern AI for significant social impact, transforming how citizens interact with and benefit from government services.
