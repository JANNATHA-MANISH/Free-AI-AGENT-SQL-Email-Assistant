# Free AI SQL & Email Assistant

## Description
The **Free AI SQL & Email Assistant** is a versatile, user-friendly tool powered by AI (Gemini) to simplify SQL query generation and professional email composition. This open-source solution allows users to interact with databases effortlessly, fetch meaningful insights, and generate professional emails without requiring any prior technical expertise.

With this tool, you can translate natural language inputs into accurate SQL queries, retrieve data from your database, and seamlessly create and send tailored emails, all from a single interface.

---

## Key Features

- **Natural Language Querying**: Input plain English queries, and the AI generates precise SQL queries based on your database schema.
- **Database Interaction**: Execute SQL queries and retrieve results in a clean, tabular format.
- **Professional Email Generator**: Convert query results into polished, professional emails.
- **Customizable Outputs**: Edit and personalize generated emails before sending or saving as drafts.
- **Streamlined Workflow**: Perform data querying and communication tasks without switching tools.

---

## Use Cases by Sector

### 1. Education
- Automate report generation for student performance or attendance.
- Send professional emails to students, parents, or faculty summarizing key insights.
- Query and email administrative reports to stakeholders.

### 2. Healthcare
- Retrieve patient statistics or appointment details from databases.
- Generate summary emails for patients, healthcare providers, or insurance companies.
- Automate daily or weekly reports on hospital metrics.

### 3. E-commerce
- Fetch sales data, inventory status, or customer insights.
- Email suppliers or customers with customized summaries or offers.
- Create performance reports for business managers.

### 4. Human Resources
- Extract employee attendance, performance, or payroll data.
- Send professional emails summarizing key HR updates to teams or individuals.
- Automate database reporting for audits or compliance checks.

### 5. Finance
- Query financial databases for transaction summaries or client account details.
- Generate concise emails for clients summarizing their financial activity.
- Automate report generation for audits or end-of-day summaries.

### 6. Marketing
- Fetch campaign performance metrics from databases.
- Generate emails summarizing analytics and insights for clients or stakeholders.
- Automate updates on leads, conversions, or ROI reports.

### 7. Small Businesses
- Manage inventory and sales data more efficiently.
- Automate customer communication with personalized emails.
- Simplify database queries for non-technical business owners.

---

## Why Choose Free AI SQL & Email Assistant?
- **Ease of Use**: No technical expertise is required.
- **Time-Saving**: Automates repetitive querying and email tasks.
- **Cost-Effective**: Free and open-source solution for personal and business use.
- **Cross-Domain Utility**: Works seamlessly across multiple sectors and use cases.
- **Customizable and Scalable**: Adapt to specific needs with minimal configuration.

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repo-link>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run main.py
   ```

4. Start querying and generating emails effortlessly!

---

## Repository Structure

```
SQL AGENT/
│
├── main.py                     # Main Streamlit application script
├── prompts.py                  # Contains custom prompts and instructions for AI agents    
├── DB.py                       # Defines the database schema as a string (Schema_prompt)
├── email_tool.py               # Handles email sending and draft saving   
├── .env                        # Environment variables
│
├── requirements.txt            # Python dependencies (e.g., Streamlit, SQLAlchemy)
├── README.md                   # Documentation for setting up and using the system
└── .gitignore                  # Files and directories to ignore in version control
```

---

## Contributions
We welcome contributions from developers, data analysts, and enthusiasts. Whether it's adding features, fixing bugs, or improving documentation, your input is valuable. 

Feel free to fork the repository, create a new branch, and submit a pull request with your changes.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact
For any queries or support, please open an issue on the GitHub repository or contact the repository maintainer directly.

---

Start leveraging the power of AI for SQL and email tasks today with the **Free AI SQL & Email Assistant**!
