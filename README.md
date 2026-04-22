# VIVARA-N8N-workflow
Json formatted file of N8N workflow of VIVARA
This project contains an automated workflow built in n8n that processes incoming emails, extracts and analyzes content using AI, and routes data for storage and notifications.

The workflow is exported as a .json file, which can be directly imported into n8n to recreate the full pipeline.
##
1- Trigger
Starts from:
IMAP Email Trigger
Webhook (optional entry point)
2- Preprocessing
Merge inputs
Execute custom code transformations
Prepare structured data
3- Document Handling
Upload PDF / file to external API
Extract and process document content
4- AI Processing
Uses an AI model to:
Interpret content
Extract meaning
Generate structured outputs
5- Routing Logic
Smart switching based on:
Content type
Urgency
Tags
6- Data Storage
Stores processed results in MongoDB
Builds structured documents before insertion
7- Notifications
Sends alerts/messages via:
📩 Email (Gmail nodes)
Other messaging integrations
