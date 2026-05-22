Airtable Setup Guide — Prestige Realty CRM
Step 1: Create the Base
Log in to airtable.com
Click + Add a base → Start from scratch
Name it: `Prestige Realty CRM`
Step 2: Configure the Leads Table
Rename "Table 1" to Leads, then add these fields exactly:
#	Field Name	Type	Options
1	Name	Single line text	—
2	Phone	Phone number	—
3	Email	Email	—
4	Enquiry Type	Single select	Buy a Property, Sell a Property, Rent / Lease, NRI Investment, Commercial Space, General Enquiry
5	Preferred Location	Single select	Adyar, Besant Nagar, OMR / Sholinganallur, Anna Nagar, Velachery, T. Nagar, Porur, Other, Not specified
6	Message	Long text	—
7	Source	Single line text	—
8	Status	Single select	New, Contacted, Qualified, Closed
9	Submitted At	Single line text	—
Step 3: Connect Airtable in Claude.ai
Go to claude.ai → Settings → Connectors
Find Airtable and click Connect
Authorize with your Airtable account
The MCP URL `https://mcp.airtable.com/mcp` is pre-configured in the website code
Step 4: Test the Form
Open `index.html` in a browser (or deploy it)
Fill in the contact form and click Submit Enquiry
Check your Airtable Leads table — a new record should appear within ~3 seconds
Step 5: Set Up Airtable Automations (Optional)
Go to Automations in your base and create:
Trigger: When record created in Leads
Action: Send email notification to sales@prestigerealty.in
Action: Send WhatsApp via Twilio (optional)
---
