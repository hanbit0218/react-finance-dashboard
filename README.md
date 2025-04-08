# REACT-FINANCE-DASHBOARD

A comprehensive personal finance dashboard built with React and Node.js that connects to Bank of America accounts via Plaid API. Features include transaction categorization, spending analytics, budget tracking, expense predictions, and personalized financial insights - all with responsive design and secure data handling. Deployed on Vercel.

## Project Timeline

<svg viewBox="0 0 1000 700" xmlns="http://www.w3.org/2000/svg">
  <!-- Background -->
  <rect width="1000" height="700" fill="#f8f9fa" rx="10" ry="10"/>
  
  <!-- Title -->
  <text x="500" y="40" font-family="Arial" font-size="24" font-weight="bold" text-anchor="middle" fill="#333">Finance-Lens Architecture</text>
  
  <!-- Client Section -->
  <rect x="50" y="80" width="400" height="340" fill="#e9f5ff" stroke="#4285f4" stroke-width="2" rx="10" ry="10"/>
  <text x="250" y="110" font-family="Arial" font-size="20" font-weight="bold" text-anchor="middle" fill="#4285f4">Frontend (React)</text>
  
  <!-- Client Components -->
  <rect x="80" y="130" width="340" height="270" fill="#ffffff" stroke="#aaa" stroke-width="1" rx="5" ry="5"/>
  
  <!-- UI Components -->
  <rect x="100" y="150" width="140" height="230" fill="#e3f2fd" stroke="#90caf9" stroke-width="1" rx="5" ry="5"/>
  <text x="170" y="170" font-family="Arial" font-size="14" font-weight="bold" text-anchor="middle">UI Components</text>
  <rect x="110" y="180" width="120" height="30" fill="#ffffff" stroke="#90caf9" stroke-width="1" rx="3" ry="3"/>
  <text x="170" y="200" font-family="Arial" font-size="12" text-anchor="middle">Dashboard</text>
  <rect x="110" y="220" width="120" height="30" fill="#ffffff" stroke="#90caf9" stroke-width="1" rx="3" ry="3"/>
  <text x="170" y="240" font-family="Arial" font-size="12" text-anchor="middle">Transactions</text>
  <rect x="110" y="260" width="120" height="30" fill="#ffffff" stroke="#90caf9" stroke-width="1" rx="3" ry="3"/>
  <text x="170" y="280" font-family="Arial" font-size="12" text-anchor="middle">Budget</text>
  <rect x="110" y="300" width="120" height="30" fill="#ffffff" stroke="#90caf9" stroke-width="1" rx="3" ry="3"/>
  <text x="170" y="320" font-family="Arial" font-size="12" text-anchor="middle">Reports</text>
  <rect x="110" y="340" width="120" height="30" fill="#ffffff" stroke="#90caf9" stroke-width="1" rx="3" ry="3"/>
  <text x="170" y="360" font-family="Arial" font-size="12" text-anchor="middle">Settings</text>
  
  <!-- Core Features -->
  <rect x="260" y="150" width="140" height="230" fill="#e8f5e9" stroke="#a5d6a7" stroke-width="1" rx="5" ry="5"/>
  <text x="330" y="170" font-family="Arial" font-size="14" font-weight="bold" text-anchor="middle">Core Features</text>
  <rect x="270" y="180" width="120" height="30" fill="#ffffff" stroke="#a5d6a7" stroke-width="1" rx="3" ry="3"/>
  <text x="330" y="200" font-family="Arial" font-size="12" text-anchor="middle">Authentication</text>
  <rect x="270" y="220" width="120" height="30" fill="#ffffff" stroke="#a5d6a7" stroke-width="1" rx="3" ry="3"/>
  <text x="330" y="240" font-family="Arial" font-size="12" text-anchor="middle">Data Visualization</text>
  <rect x="270" y="260" width="120" height="30" fill="#ffffff" stroke="#a5d6a7" stroke-width="1" rx="3" ry="3"/>
  <text x="330" y="280" font-family="Arial" font-size="12" text-anchor="middle">Plaid Integration</text>
  <rect x="270" y="300" width="120" height="30" fill="#ffffff" stroke="#a5d6a7" stroke-width="1" rx="3" ry="3"/>
  <text x="330" y="320" font-family="Arial" font-size="12" text-anchor="middle">Theme/Styling</text>
  <rect x="270" y="340" width="120" height="30" fill="#ffffff" stroke="#a5d6a7" stroke-width="1" rx="3" ry="3"/>
  <text x="330" y="360" font-family="Arial" font-size="12" text-anchor="middle">API Client</text>
  
  <!-- Server Section -->
  <rect x="550" y="80" width="400" height="340" fill="#fff5e6" stroke="#f4b400" stroke-width="2" rx="10" ry="10"/>
  <text x="750" y="110" font-family="Arial" font-size="20" font-weight="bold" text-anchor="middle" fill="#f4b400">Backend (Node.js/Express)</text>
  
  <!-- Server Components -->
  <rect x="580" y="130" width="340" height="270" fill="#ffffff" stroke="#aaa" stroke-width="1" rx="5" ry="5"/>
  
  <!-- API Routes -->
  <rect x="600" y="150" width="140" height="230" fill="#fff8e1" stroke="#ffecb3" stroke-width="1" rx="5" ry="5"/>
  <text x="670" y="170" font-family="Arial" font-size="14" font-weight="bold" text-anchor="middle">API Routes</text>
  <rect x="610" y="180" width="120" height="30" fill="#ffffff" stroke="#ffecb3" stroke-width="1" rx="3" ry="3"/>
  <text x="670" y="200" font-family="Arial" font-size="12" text-anchor="middle">Auth Routes</text>
  <rect x="610" y="220" width="120" height="30" fill="#ffffff" stroke="#ffecb3" stroke-width="1" rx="3" ry="3"/>
  <text x="670" y="240" font-family="Arial" font-size="12" text-anchor="middle">Plaid Routes</text>
  <rect x="610" y="260" width="120" height="30" fill="#ffffff" stroke="#ffecb3" stroke-width="1" rx="3" ry="3"/>
  <text x="670" y="280" font-family="Arial" font-size="12" text-anchor="middle">Transaction Routes</text>
  <rect x="610" y="300" width="120" height="30" fill="#ffffff" stroke="#ffecb3" stroke-width="1" rx="3" ry="3"/>
  <text x="670" y="320" font-family="Arial" font-size="12" text-anchor="middle">Budget Routes</text>
  <rect x="610" y="340" width="120" height="30" fill="#ffffff" stroke="#ffecb3" stroke-width="1" rx="3" ry="3"/>
  <text x="670" y="360" font-family="Arial" font-size="12" text-anchor="middle">Analytics Routes</text>
  
  <!-- Services -->
  <rect x="760" y="150" width="140" height="230" fill="#f3e5f5" stroke="#ce93d8" stroke-width="1" rx="5" ry="5"/>
  <text x="830" y="170" font-family="Arial" font-size="14" font-weight="bold" text-anchor="middle">Services</text>
  <rect x="770" y="180" width="120" height="30" fill="#ffffff" stroke="#ce93d8" stroke-width="1" rx="3" ry="3"/>
  <text x="830" y="200" font-family="Arial" font-size="12" text-anchor="middle">Auth Service</text>
  <rect x="770" y="220" width="120" height="30" fill="#ffffff" stroke="#ce93d8" stroke-width="1" rx="3" ry="3"/>
  <text x="830" y="240" font-family="Arial" font-size="12" text-anchor="middle">Plaid Service</text>
  <rect x="770" y="260" width="120" height="30" fill="#ffffff" stroke="#ce93d8" stroke-width="1" rx="3" ry="3"/>
  <text x="830" y="280" font-family="Arial" font-size="12" text-anchor="middle">Transaction Service</text>
  <rect x="770" y="300" width="120" height="30" fill="#ffffff" stroke="#ce93d8" stroke-width="1" rx="3" ry="3"/>
  <text x="830" y="320" font-family="Arial" font-size="12" text-anchor="middle">ML Service</text>
  <rect x="770" y="340" width="120" height="30" fill="#ffffff" stroke="#ce93d8" stroke-width="1" rx="3" ry="3"/>
  <text x="830" y="360" font-family="Arial" font-size="12" text-anchor="middle">Export Service</text>
  
  <!-- Database Section -->
  <rect x="300" y="460" width="400" height="180" fill="#e8f4f8" stroke="#0097a7" stroke-width="2" rx="10" ry="10"/>
  <text x="500" y="490" font-family="Arial" font-size="20" font-weight="bold" text-anchor="middle" fill="#0097a7">Database (MongoDB)</text>
  
  <!-- Collections -->
  <rect x="330" y="510" width="340" height="110" fill="#ffffff" stroke="#aaa" stroke-width="1" rx="5" ry="5"/>
  <text x="500" y="535" font-family="Arial" font-size="14" font-weight="bold" text-anchor="middle">Collections</text>
  
  <rect x="350" y="550" width="140" height="50" fill="#e0f7fa" stroke="#80deea" stroke-width="1" rx="3" ry="3"/>
  <text x="420" y="580" font-family="Arial" font-size="12" text-anchor="middle">Users</text>
  
  <rect x="510" y="550" width="140" height="50" fill="#e0f7fa" stroke="#80deea" stroke-width="1" rx="3" ry="3"/>
  <text x="580" y="580" font-family="Arial" font-size="12" text-anchor="middle">Transactions</text>
  
  <!-- External Services -->
  <rect x="825" y="460" width="150" height="180" fill="#fce4ec" stroke="#ec407a" stroke-width="2" rx="10" ry="10"/>
  <text x="900" y="490" font-family="Arial" font-size="16" font-weight="bold" text-anchor="middle" fill="#ec407a">External Services</text>
  
  <rect x="845" y="510" width="110" height="40" fill="#ffffff" stroke="#f48fb1" stroke-width="1" rx="3" ry="3"/>
  <text x="900" y="535" font-family="Arial" font-size="12" text-anchor="middle">Plaid API</text>
  
  <rect x="845" y="560" width="110" height="40" fill="#ffffff" stroke="#f48fb1" stroke-width="1" rx="3" ry="3"/>
  <text x="900" y="585" font-family="Arial" font-size="12" text-anchor="middle">Bank of America</text>
  
  <rect x="845" y="610" width="110" height="40" fill="#ffffff" stroke="#f48fb1" stroke-width="1" rx="3" ry="3"/>
  <text x="900" y="635" font-family="Arial" font-size="12" text-anchor="middle">Vercel</text>
  
  <!-- Client-Server Connection -->
  <path d="M450 250 L550 250" stroke="#666" stroke-width="2" fill="none" marker-end="url(#arrow)"/>
  <text x="500" y="240" font-family="Arial" font-size="12" text-anchor="middle" fill="#666">REST API</text>
  
  <!-- Server-Database Connection -->
  <path d="M750 400 L650 460" stroke="#666" stroke-width="2" fill="none" marker-end="url(#arrow)"/>
  <text x="720" y="440" font-family="Arial" font-size="12" text-anchor="middle" fill="#666">Mongoose ODM</text>
  
  <!-- Server-External Connection -->
  <path d="M850 400 L870 460" stroke="#666" stroke-width="2" fill="none" marker-end="url(#arrow)"/>
  <text x="880" y="440" font-family="Arial" font-size="12" text-anchor="middle" fill="#666">API Calls</text>
  
  <!-- Arrow Marker Definition -->
  <defs>
    <marker id="arrow" viewBox="0 0 10 10" refX="9" refY="5" 
            markerWidth="6" markerHeight="6" orient="auto">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#666"/>
    </marker>
  </defs>
</svg>

### Week 1: Project Setup & Authentication

| Day | Date     | Task                               | Description                                                                       |
| --- | -------- | ---------------------------------- | --------------------------------------------------------------------------------- |
| 1   | April 9  | Project initialization             | Set up GitHub repository, initialize React project, create basic folder structure |
| 2   | April 10 | Express backend setup              | Initialize Node.js/Express project, create basic API routes structure             |
| 3   | April 11 | MongoDB connection setup           | Set up database connection, create basic schema models                            |
| 4   | April 12 | Authentication system foundation   | Set up JWT authentication structure, create login/register API endpoints          |
| 5   | April 13 | Frontend authentication components | Create login and registration forms, implement JWT storage on client              |
| 6   | April 14 | Basic navigation and layout        | Create responsive navbar, sidebar, and main layout components                     |
| 7   | April 15 | Finalize authentication flow       | Connect frontend auth forms to backend, implement protected routes                |

### Week 2: Financial Integration

| Day | Date     | Task                             | Description                                                                   |
| --- | -------- | -------------------------------- | ----------------------------------------------------------------------------- |
| 8   | April 16 | Plaid API integration setup      | Initialize Plaid client, create environment variables, implement sandbox mode |
| 9   | April 17 | Plaid Link component             | Add Plaid Link button to connect Bank of America account                      |
| 10  | April 18 | Transaction fetching API         | Create API endpoint to fetch transactions from Plaid                          |
| 11  | April 19 | Transaction data models          | Create database models for storing and categorizing transaction data          |
| 12  | April 20 | Transaction sync functionality   | Implement functionality to sync transactions from Plaid to database           |
| 13  | April 21 | Transaction listing component    | Create component to display transactions in a paginated list                  |
| 14  | April 22 | Transaction search and filtering | Add search and filtering functionality to transaction list                    |

### Week 3: Dashboard Core

| Day | Date     | Task                          | Description                                             |
| --- | -------- | ----------------------------- | ------------------------------------------------------- |
| 15  | April 23 | Dashboard layout              | Create main dashboard layout with placeholder widgets   |
| 16  | April 24 | Account summary component     | Create component to display accounts and balances       |
| 17  | April 25 | Spending breakdown chart      | Implement pie chart for spending categories             |
| 18  | April 26 | Monthly spending trend chart  | Implement line chart for spending over time             |
| 19  | April 27 | Income vs. expenses component | Create bar chart comparing income and expenses          |
| 20  | April 28 | Recent transactions widget    | Add quick view of most recent transactions to dashboard |
| 21  | April 29 | Dashboard responsive design   | Ensure dashboard is fully responsive on mobile devices  |

### Week 4: Budgeting Features

| Day | Date     | Task                                  | Description                                            |
| --- | -------- | ------------------------------------- | ------------------------------------------------------ |
| 22  | April 30 | Budget model and API                  | Create budget data model and API endpoints             |
| 23  | May 1    | Budget creation form                  | Implement form for creating and editing budgets        |
| 24  | May 2    | Budget category management            | Create functionality to manage budget categories       |
| 25  | May 3    | Budget progress visualization         | Add progress bars for budget category spending         |
| 26  | May 4    | Budget alert system                   | Implement alerts for approaching budget limits         |
| 27  | May 5    | Monthly budget summary                | Create monthly overview of budget performance          |
| 28  | May 6    | Budget vs. actual spending comparison | Implement chart comparing budgeted vs. actual spending |

### Week 5: Analytics & Insights

| Day | Date   | Task                                 | Description                                       |
| --- | ------ | ------------------------------------ | ------------------------------------------------- |
| 29  | May 7  | Spending patterns analysis backend   | Create API for analyzing spending patterns        |
| 30  | May 8  | Spending patterns visualization      | Implement visualizations for spending patterns    |
| 31  | May 9  | Expense categorization improvements  | Enhance automatic categorization of expenses      |
| 32  | May 10 | Recurring expenses detection         | Implement algorithm to detect recurring expenses  |
| 33  | May 11 | Savings opportunities identification | Create feature to identify potential savings      |
| 34  | May 12 | Financial insights component         | Create component to display personalized insights |
| 35  | May 13 | Insights notification system         | Implement notifications for new insights          |

### Week 6: Predictions & Machine Learning

| Day | Date   | Task                              | Description                                               |
| --- | ------ | --------------------------------- | --------------------------------------------------------- |
| 36  | May 14 | Prediction models setup           | Set up simple ML models for expense prediction            |
| 37  | May 15 | Monthly expense predictions       | Implement functionality to predict next month's expenses  |
| 38  | May 16 | Cash flow forecast                | Create cash flow projection for upcoming months           |
| 39  | May 17 | Savings goal predictions          | Implement feature to predict savings goal achievement     |
| 40  | May 18 | Unusual activity detection        | Create algorithm to detect unusual spending patterns      |
| 41  | May 19 | Smart recommendations engine      | Implement system for generating financial recommendations |
| 42  | May 20 | Recommendations display component | Create UI for displaying personalized recommendations     |

### Week 7: Final Features & Polish

| Day | Date   | Task                              | Description                                        |
| --- | ------ | --------------------------------- | -------------------------------------------------- |
| 43  | May 21 | Monthly financial report          | Create monthly financial summary report            |
| 44  | May 22 | PDF & CSV export functionality    | Add ability to export reports and transaction data |
| 45  | May 23 | User profile & settings           | Create user profile settings UI and functionality  |
| 46  | May 24 | Theme switching & personalization | Add light/dark mode and dashboard customization    |
| 47  | May 25 | Unit & integration tests          | Implement key tests for core functionality         |
| 48  | May 26 | Performance optimization          | Optimize frontend and backend performance          |
| 49  | May 27 | Documentation & README            | Create comprehensive documentation                 |

### Week 8 (Half Week): Deployment

| Day | Date   | Task                            | Description                                    |
| --- | ------ | ------------------------------- | ---------------------------------------------- |
| 50  | May 28 | Vercel deployment configuration | Set up Vercel configuration files              |
| 51  | May 29 | Environment variables setup     | Configure environment variables for production |
| 52  | May 30 | Final bug fixes                 | Address any remaining issues                   |
| 53  | May 31 | Production launch               | Final optimizations and project launch         |
