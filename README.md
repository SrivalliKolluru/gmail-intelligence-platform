# Gmail Intelligence Platform

An AI-powered Gmail Intelligence Platform built using n8n, Supabase, Gmail API, Google Gemini, and NVIDIA NIM.

---

# Features

## Gmail Integration

- OAuth 2.0 Gmail API integration
- Sync messages, threads, labels and metadata
- Pagination support
- Incremental sync using historyId
- Supabase storage

## Email Summarization

- Individual email summaries
- Thread-level summaries
- Context-aware summarization

## Email Categorization

Supported categories:

- Newsletter
- Job / Recruitment
- Finance
- Notifications
- Personal
- Work / Professional

## AI Chat Agent (RAG)

Ask questions like:

- Which companies rejected my applications?
- Summarize all emails from Acme Corp.
- What has been discussed about Kubernetes?
- List important tech news from the last 4 days.

The agent answers only from the user's email knowledge base.

## Compose Email

Generate professional emails from short prompts.

## Thread-aware Reply

Generate replies using complete thread context while preserving Gmail threading.

## Embeddings

Generate vector embeddings using NVIDIA NIM and store them in pgvector.

---

# Tech Stack

| Layer | Technology |
|---------|------------|
| Workflow Automation | n8n |
| Database | Supabase |
| Email API | Gmail API |
| LLM | Google Gemini |
| Embeddings | NVIDIA NIM |
| Vector Search | pgvector |
| Frontend | React |
| Backend | Node.js |

---

# Workflows

### Workflow 1
Initial Gmail Sync

### Workflow 2
Email Summarization

### Workflow 3
Email Categorization

### Workflow 4
Thread Summary

### Workflow 5
Embeddings Generation

### Workflow 6
AI Chat Agent (RAG)

### Workflow 7
Compose Email

### Workflow 8
Thread-aware Reply

---

# Folder Structure

```
gmail-intelligence-platform
│
├── README.md
├── Architecture.md
├── .env.example
├── workflows
├── screenshots
├── frontend
└── backend
```

---

# Setup

Clone repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
npm install
```

Run application:

```bash
npm run dev
```

---

# Environment Variables

See .env.example

---

# Import Workflows

Import all JSON files from:

```
workflows/
```

into n8n.

---

# Author

Built for Repeatless Technical Assessment.
