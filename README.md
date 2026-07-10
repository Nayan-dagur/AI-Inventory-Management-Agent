# AI-Inventory-Management-Agent
Overview

AI Inventory Management Agent is an intelligent inventory automation system built using n8n, OpenAI, and Excel-based inventory storage. The agent automates inventory monitoring, updates stock records, provides natural language inventory insights, and helps reduce manual inventory management efforts.

The system allows users to interact with inventory data through a conversational interface, enabling non-technical staff to check stock levels, update inventory records, and receive inventory information using plain English.

⸻

Features

* Automated inventory tracking and management
* Natural language inventory queries using an LLM
* Conversational inventory assistant
* Inventory updates through chat-based commands
* OpenAI-powered response generation
* Simple memory for maintaining conversation context
* Excel sheet integration for inventory storage
* Low-stock monitoring workflow
* No-code/low-code implementation using n8n

⸻

Workflow Architecture<br>
User Message<br>
      │
      ▼
Chat Trigger<br>
      │
      ▼
OpenAI Chat Model<br>
      │
      ▼
Simple Memory<br>
      │
      ▼
Inventory Agent Logic<br>
      │
      ▼
Excel Inventory Database<br>
      │
      ▼
Inventory Response / Update<br>
⸻

Example Queries

Users can interact with the inventory using natural language:

* “How many laptops are currently in stock?”
* “Show all products with low inventory.”
* “Update monitor stock to 45 units.”
* “Which item has the highest stock?”
* “List all available products.”

⸻

Tech Stack

* n8n
* OpenAI API
* AI Agent Node
* OpenAI Chat Model
* Simple Memory
* Excel Spreadsheet
* Workflow Automation

⸻

How It Works

1. A user sends a message to the AI Inventory Agent.
2. The OpenAI Chat Model interprets the request.
3. Simple Memory maintains conversational context.
4. The workflow accesses inventory data stored in an Excel sheet.
5. The agent retrieves or updates inventory records.
6. The response is returned in natural language.

⸻

Project Components

Chat Message Node

Receives user inventory queries.

OpenAI Chat Model

Processes user requests and generates intelligent responses.

Simple Memory

Stores conversation history and context.

Excel Inventory Database

Acts as the inventory management backend.

Inventory Update Logic

Handles stock additions, modifications, and inventory checks.

⸻

Business Impact

* Reduces manual inventory tracking efforts
* Improves accessibility for non-technical users
* Enables faster inventory lookups
* Simplifies stock management through conversational AI
* Demonstrates practical use of AI agents in business operations

⸻

Future Improvements

* Automated reorder generation
* Email and WhatsApp low-stock alerts
* Multi-user support
* Dashboard visualization
* Database integration (MySQL/PostgreSQL)
* Predictive inventory forecasting
* Supplier management automation

⸻

## Demo Video

Watch the project demonstration here:https://www.youtube.com/watch?v=JyP1NQdziiw



⸻

Author

Nayan Dagur

AI & Machine Learning Enthusiast | Building AI Agents and Automation Solutions with n8n and LLMs
