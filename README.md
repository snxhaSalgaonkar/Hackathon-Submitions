# Hackathon Submission Repository

# Project Name: 
MindBridge

## Team Name: 
Golden Fleece

## Problem Statement
PS12

## Team Members
Sneha Salgaonkar
Noah Menezes
Chinmayi Parab
Erika Vaz

## GitHub Repository
https://github.com/NoahMenezes/GoldenFleece-MindBridge-12.git

## Demo Video
https://youtube.com/demo

## Project Description
MindBridge is a powerful AI-orchestration browser extension that serves as a "Neural Bridge" between various AI platforms like ChatGPT, Claude, and Gemini. It eliminates the need to re-explain project context every time you switch AI tools by capturing your conversation "DNA" and injecting it into new chats. It acts as a unified memory layer for your AI-assisted workflow.

## Features
1. Neural Sync: Automatically extracts structured data (Roles, Goals, Tasks) from active AI conversations.
2. Cross-Platform Memory Injection: Seamlessly "pastes" relevant project history and technical context into Claude, ChatGPT, or Gemini with a single click.
3. Semantic Vector Search: Uses a local ChromaDB brain to find the most relevant past memories based on the meaning of your current chat.
4. Identity Persistence: Maintains a consistent user persona (e.g., "Senior React Developer") across all platforms.
5. Hybrid Storage: Syncs raw conversation logs to Supabase for backup while keeping high-speed vector embeddings in a local database.

## Tech Stack
Frontend: Plasmo Framework (React + TypeScript), Tailwind CSS.
Backend: FastAPI (Python).
Database: Supabase (PostgreSQL) for raw logs & ChromaDB for vector semantic memory.
APIs: Firebase Google Authentication, Google Identity Services (Native Auth).
LLM Engine: Integrated via FastAPI to analyze and structure persona data.

## Installation Steps
Clone the Repo: git clone https://github.com/NoahMenezes/GoldenFleece-MindBridge-12.git
Install Frontend: pnpm install
Install Backend: cd backend && pip install -r requirements.txt
Env Setup:
Create a .env in the root with your Firebase and Google Client IDs.
Create a backend/.env with your Supabase credentials.
Run Development:
Terminal 1: pnpm dev:firefox (or pnpm dev for Chrome).
Terminal 2: cd backend && python run.py.
Usage Instructions
Sign In: Open the MindBridge extension popup and log in with Google.
Capture: In ChatGPT, click the "MindBridge Active" button and hit Connect.
Bridge: Go to Claude or Gemini. Click the "MindBridge Active" button and hit Connect again.
Interact: Watch as MindBridge automatically injects your previous project context into the input field!

## Screenshots
(Add your captured screenshots here showing the Neural Sync box and the Synced Identity dashboard)

## Demo Video
(Insert link to your screen recording showing the ChatGPT -> Claude context transfer)

## MindBridge: The Missing Memory Layer for the AI Age.