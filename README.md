# Personal Finance Advisor Bot

An AI-powered financial planning assistant that helps individuals take control of their personal finances with clarity and confidence. The system enables users to record monthly income, log daily and weekly expenses by category, receive personalized budget plans, and track saving progress within a centralized digital environment.

By integrating modern backend technologies with AI-driven financial analysis, the platform ensures accurate budget generation, intelligent spending insights, and structured monthly financial reporting.

The platform is built on a scalable full-stack architecture using **Flask**, **SQLAlchemy**, and an **AI engine** to support efficient financial planning and productivity enhancement for individuals managing personal budgets. It reduces manual financial tracking complexity by automating budget generation and providing structured saving recommendations, and is designed to support future enhancements such as predictive spending analytics, investment suggestions, goal-based savings tracking, and advanced AI-driven financial health monitoring.

## Scenarios

**Scenario 1 — Salaried Professional**
A salaried professional logs monthly income and daily expenses across categories such as rent, food, transport, and entertainment. The system analyzes the spending data, identifies overspending areas, and generates a personalized budget plan with actionable saving suggestions. The user receives a monthly summary report showing income vs. expenses, savings achieved, and financial goals for the following month.

**Scenario 2 — College Student**
A college student uses the Personal Finance Advisor Bot to manage a limited monthly allowance across essential and discretionary categories. The platform helps the student set realistic budget limits, track spending habits, and receive AI-powered recommendations for reducing unnecessary expenditures — enabling better financial discipline and improved savings management within a constrained budget.

**Scenario 3 — Freelancer**
A freelancer with variable monthly income uses the platform to log earnings from multiple clients and track project-related expenses. The system adapts budget recommendations based on fluctuating income patterns, highlights months with reduced saving capacity, and suggests strategies for building an emergency fund.

**Scenario 4 — Household Manager**
A household manager uses the system to monitor shared family income and expenses across categories such as groceries, utilities, education, and healthcare. The bot generates a consolidated monthly financial report, identifies budget overruns in specific categories, and provides tailored saving strategies to meet family financial goals.

## Skills Required

- Python
- Gemini AI
- Flask (Web Framework)
- SQLite
- JavaScript

## Tech Stack

- **Backend:** Flask, SQLAlchemy
- **Database:** SQLite / PostgreSQL
- **Templating:** Jinja2
- **AI Engine:** ChatGPT / Gemini AI
- **Deployment:** Ngrok (for public accessibility during development/demo)
- **Env Management:** python-dotenv

## Features

- Secure user authentication (registration, login, session management, protected routes)
- Income and expense recording by category
- AI-powered personalized budget generation
- Spending analysis and overspending detection
- Savings tracking and emergency fund guidance
- Monthly financial summary reports
- Interactive dashboard (income overview, expense breakdown, budget performance, savings progress, category-wise analytics, AI recommendations)

## Build Plan

### 1. Environment Setup & AI Configuration
- Set up the Flask development environment and install all required project dependencies
- Configure SQLAlchemy and database connectivity using SQLite or PostgreSQL
- Configure secure API key management using environment variables (`.env`)
- Integrate ChatGPT/Gemini AI services for budget generation and financial recommendations
- Install and configure required libraries: Flask, SQLAlchemy, Flask-Login, Jinja2, python-dotenv, and AI SDK packages
- Prepare the complete development environment for full-stack financial management and AI integration

### 2. User Authentication & Financial Profile Management
Develop a secure user management system including:
- User Registration
- User Login
- Secure Session Management
- User Profile Management
- Income Management
- Expense Category Management
- Financial Data Protection
- Protected Routes
- Secure Logout Functionality

Implement authentication, authorization, session handling, and secure financial data management to ensure safe access to personal finance information.

### 3. Financial Tracking & Budget Management System
Develop the core financial management modules including:
- Income Recording System
- Expense Tracking Module
- Expense Categorization
- Budget Planning Engine
- Spending Analysis Module
- Savings Tracking
- Financial Summary Generation
- Monthly Financial Monitoring

Allow users to manage income sources, track spending habits, monitor expenses across categories, and maintain complete financial visibility.

### 4. AI-Powered Budget Generation & Financial Recommendation Engine
Implement intelligent financial advisory modules including:
- Personalized Budget Generation
- AI Spending Analysis
- Savings Recommendations
- Financial Health Evaluation
- Overspending Detection
- Cost Optimization Suggestions
- Emergency Fund Guidance
- Personalized Financial Insights

Leverage ChatGPT/Gemini AI to generate customized financial advice based on user income, expenses, spending behavior, and financial goals.

### 5. Dashboard, Financial Analytics & Reporting
Develop an interactive financial dashboard featuring:
- Income Overview
- Expense Breakdown
- Budget Performance Monitoring
- Savings Progress Tracking
- Spending Analysis Reports
- Monthly Financial Summaries
- Category-Wise Expense Analytics
- AI Recommendation Display

Enable users to visualize financial performance, monitor spending habits, evaluate savings growth, and access AI-generated financial insights through an intuitive dashboard.

### 6. Database Management & Financial Data Processing
Design and implement database structures for:
- User Accounts
- Income Records
- Expense Categories
- Expense Transactions
- Budget Plans
- Monthly Reports
- Financial Analytics
- Savings Progress Records

Ensure reliable storage, retrieval, validation, consistency, and secure management of financial information throughout the application.

### 7. Frontend-Backend Integration & API Communication
- Develop Flask route handlers and backend services
- Integrate Jinja2 frontend templates with backend processing
- Implement secure communication between financial modules and AI services
- Handle request validation, form submissions, error handling, and response processing
- Ensure seamless synchronization between frontend interfaces, database operations, and AI-powered recommendations

### 8. Public Deployment Using Ngrok
- Configure the complete local development environment
- Launch the Flask application successfully
- Configure all database connections and AI services
- Install and configure Ngrok for public access
- Generate secure public URLs for external testing and demonstrations
- Validate complete frontend-backend functionality through the Ngrok deployment environment

### 9. Testing, Validation & Performance Optimization
Perform comprehensive testing including:
- User Authentication Testing
- Income Tracking Testing
- Expense Management Testing
- Budget Generation Validation
- AI Recommendation Testing
- Dashboard Testing
- Financial Report Testing
- Database Validation
- API Integration Testing
- Frontend-Backend Communication Testing
- End-to-End Workflow Testing
- Performance & Reliability Evaluation

Continuously improve financial analysis accuracy, AI recommendation quality, application performance, and user experience through testing and optimization.

## Outcome

By completing this project, you will:

- Build an AI-powered Personal Finance Management platform using Flask, SQLAlchemy, Jinja2, SQLite/PostgreSQL, and ChatGPT/Gemini AI
- Develop secure user authentication, profile management, and session handling mechanisms for financial applications
- Implement comprehensive income tracking, budget planning, and savings monitoring systems
- Integrate Generative AI to create personalized budget plans, spending insights, financial recommendations, and savings strategies
- Design intelligent financial advisory systems capable of identifying overspending patterns and suggesting cost optimization opportunities
- Create interactive dashboards for visualizing income, expenses, budget utilization, savings growth, and financial performance
- Develop structured monthly financial reporting systems with detailed analytics and AI-powered recommendations
- Implement database management solutions for secure storage and processing of financial records and user information
- Build scalable Flask backend services and integrate them seamlessly with frontend templates and AI-powered modules
- Gain hands-on experience in Generative AI, Financial Technology (FinTech), Full-Stack Development, Database Design, Prompt Engineering, Flask Development, Financial Analytics, and AI-powered Recommendation Systems
- Validate application reliability through comprehensive testing of authentication, financial tracking, AI recommendations, reporting, and deployment workflows
- Deploy and manage AI-powered web applications using Flask and Ngrok for public accessibility and demonstrations

A high-impact, industry-ready project ideal for AI Developers, Full-Stack Developers, FinTech Engineers, Backend Developers, Software Engineers, Data Analysts, Generative AI Engineers, and students seeking hands-on experience in AI-powered personal finance and budgeting solutions.

## System Requirements

### Hardware
- **Processor:** Intel Core i5 (8th Gen or above) / AMD Ryzen 5 or equivalent
- **RAM:** Minimum 8 GB (Recommended: 16 GB for multitasking and AWS Labs usage)
- **Storage:** 256 GB SSD (or 500 GB HDD minimum)
- **Internet:** Stable high-speed connection (minimum 10 Mbps, recommended 20 Mbps for AWS Labs and deployments)

### Software
- **OS:** Windows 10/11, macOS (Monterey or later), or Linux (Ubuntu 20.04+)
- **Browser:** Latest version of Google Chrome, Mozilla Firefox, or Microsoft Edge
- **IDE:** Visual Studio Code (recommended) or any preferred IDE
- **Version Control:** Git (latest version installed and configured)
- **Additional Tools:** Python 3.8+, AWS CLI (latest version)

## Team

| Role | Name |
|---|---|
| Team Member | Mayuri Raut |
| Mentor | Not yet assigned |

## Getting Started

```bash
# Clone the repository
git clone <your-repo-url>
cd personal-finance-advisor-bot

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Configure environment variables
cp .env.example .env
# Add your GEMINI_API_KEY / OPENAI_API_KEY and other config values

# Run the application
flask run
```

## License

Add your preferred license here (e.g. MIT).
