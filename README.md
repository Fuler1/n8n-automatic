Project summary
AI Email Triage & Response Agent (n8n + Gemini)

The project involves creating an automated AI agent that handles incoming customer emails, analyzes their content, and generates a concise, technical response or summary for a developer or IT team.

How the system works (workflow)

Gmail Trigger
The system automatically detects a new email sent by a customer.
Get a message
The full content of the message (body, subject, sender) is retrieved.
Edit Fields
The data is normalized and prepared for further processing
(e.g., selecting message content, removing unnecessary elements).
Message a model (Gemini AI)
The content of the email goes to an AI model, which:
analyzes the customer's intention,
identifies the type of problem (e.g., error, question, request),
generates a clear, structured technical summary.
Send a message (Gmail)
The generated response or summary is automatically forwarded
(e.g., to a developer, support team, or as a response to the customer).


The role of AI in the project
The AI model acts as the first line of analysis (AI L1):
it reduces the amount of manual email analysis,
it converts chaotic problem descriptions into clear technical information,
it speeds up the response of the IT team/developers.
AI does not make critical decisions, but only:
classifies, summarizes, formulates a response in a professional tone.

Security aspects

No production data in the code.
AI API key stored in environment variables.
Possibility of manual verification of responses (human-in-the-loop).

Technologies

n8n – workflow automation
Google Gemini (AI) – content analysis and generation
Gmail API – message reception and sending
JSON / Expressions – data processing

End result

Shorter response times to requests
Streamlined communication between the customer and the technical team
A ready-made example of the practical use of AI in IT automation
