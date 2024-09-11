Rate My Professor Chatbot

This project is a web application that allows users to scrape information from Rate My Professor website. It includes both a frontend interface for users to submit URLs and interact with a chatbot, and a backend API that processes the scraping requests. It also includes a login process with Next.js user authentication logic. 

Features

Scraping: Submit a Rate My Professors URL and scrape professor data.
Scraped data from Rate my Professor is upsert to a Pinecone index, integrated with a RAG pipeline using LangChain and OpenAI GPT-4o for responses.
Chatbot Interaction: A chatbot assists users with queries about professors and improves its knowledge base as new professors are added.
RESTful API: Exposes endpoints for scraping data programmatically.
User Authentication: Rate my professor includes user authentication to provide a seamless login process with Google credentials.

Technology Stack

Frontend: React (with Next.js), Material-UI for styling
Backend: Node.js with Next.js API routes, Prisma, MongoDB
Deployment: Vercel
Installation
