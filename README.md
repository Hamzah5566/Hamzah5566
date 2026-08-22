# Hi, I'm Hamzah 👋

Junior Software Developer in Johannesburg, South Africa, currently reading for a BSc Honours in
IT (Data Science) at Eduvos after completing a BSc in IT (Software Engineering).

Day to day I build full-stack applications in C# and .NET, design REST APIs in Python and
FastAPI, and work on AI-powered features — LLM integration, MCP servers, and a WhatsApp chatbot
that takes restaurant orders end to end. The repositories here are my own projects across
mobile, web and data, each documented so you can see how it was built rather than just that it
was.

---

## What I work with

### Used in the projects here

| | |
|---|---|
| **Languages** | Java · PHP · Python · R · JavaScript · SQL |
| **Mobile** | Android SDK, Material Components, View Binding, Navigation Component |
| **Backend** | Firebase (Auth, Firestore, Storage, Cloud Messaging, Cloud Functions), MySQL, PDO |
| **Web** | HTML, CSS, vanilla JavaScript |
| **Data** | pandas, NumPy, scikit-learn, statsmodels, Matplotlib, caret, ggplot2, NetworkX |
| **Tools** | Git, Android Studio, Gradle, XAMPP, Composer, Jupyter, RStudio |

### Used professionally

Day-to-day work as a Junior Software Developer, which the repositories here do not cover.

| | |
|---|---|
| **Languages and frameworks** | C#, .NET, ASP.NET, Blazor, Razor, MVC, TypeScript |
| **APIs** | Python/FastAPI, REST, Swagger, third-party integration |
| **Architecture** | Microservices, service layers, database schema design |
| **AI** | LLM integration, MCP servers, Gemini API, WhatsApp Business API, prompt engineering |
| **Databases** | PostgreSQL, MongoDB, Oracle |
| **DevOps** | Docker, Kubernetes, CI/CD, Azure DevOps, AWS |

### Also studied

| | |
|---|---|
| **Languages** | Kotlin, Swift |
| **Frameworks** | React, React Native, Bootstrap, Tailwind |
| **Data** | Hadoop, Seaborn |

---|---|
| **Languages** | Java · PHP · Python · R · JavaScript · SQL |
| **Mobile** | Android SDK, Material Components, View Binding, Navigation Component |
| **Backend** | Firebase (Auth, Firestore, Storage, Cloud Messaging, Cloud Functions), MySQL, PDO |
| **Web** | HTML, CSS, vanilla JavaScript |
| **Data** | caret, ggplot2, statsmodels, NetworkX |
| **Tools** | Git, Android Studio, Gradle, XAMPP, Composer, Jupyter, RStudio |

### Also worked with

Studied through coursework and personal learning. No project in this repository list uses these
yet, so I have kept them separate from the above.

| | |
|---|---|
| **Languages** | C# |
| **Frameworks** | Blazor, React, React Native |
| **Containers and orchestration** | Docker, Kubernetes |

---

## Featured projects

### 🛒 [SellitZA](https://github.com/Hamzah5566/E-Commerce-Website)
`PHP` · `MySQL` · `JavaScript`

A consumer-to-consumer marketplace where anyone can list second-hand goods, message a seller
about a listing, and check out. Built without a framework.

One page serves all seven product categories, SQL is confined to repository classes, and only
the `public/` directory is reachable by the browser. My first website, originally deployed to
shared hosting.

---

### 📱 [R & S Motorsport](https://github.com/Hamzah5566/RandSMotorsport)
`Java` · `Android` · `Firebase`

A native Android app for a motorsport garage and parts retailer. Customers browse a parts
catalogue, check out with Google Places address autocomplete, and book service appointments
against real time slots. Administrators get a separate dashboard for orders, appointments,
products and users, and status changes fire Cloud Functions that push a notification to the
affected customer.

47 classes, role-based access read from Firestore, and unit-tested cart and validation logic.

---

### 📈 [Tech Role Demand Forecasting](https://github.com/Hamzah5566/Tech-Role-Demand-Forecasting)
`Python` · `Time Series` · `statsmodels`

Forecasting five years of weekly search interest for Data Analyst, Software Engineer and
Cybersecurity Specialist roles: decomposition, stationarity testing, ARIMA order selection from
ACF and PACF, and residual diagnostics.

The non-seasonal models forecast a flat line and the Ljung-Box test flagged leftover structure
in the residuals. Adding a 52-week seasonal component roughly halves the error — 9.24% MAPE down
to 4.67% for Data Analyst.

---

### 📊 [Machine Learning in R](https://github.com/Hamzah5566/Machine-Learning-in-R)
`R` · `Machine Learning` · `caret`

Three analyses on public UCI datasets: logistic regression classifying heart disease at 79.7%
accuracy and 85.7% recall, a comparison of multiple linear regression against decision tree
regression on US crime data, and k-means clustering of wine chemistry with PCA for
visualisation.

The crime model initially scored a test R² of exactly 1.0. The dataset records each violent
offence separately and violent crime is their sum, so the model was re-deriving the target from
its own parts. Removing those columns gives an honest R² of 0.74.

---

## Other work

| Project | Built with | What it does |
|---|---|---|
| [Priority Patient Queue Manager](https://github.com/Hamzah5566/Priority-Patient-Queue-Manager) | Python | Schedules emergency room patients by clinical priority |
| [Social Network Analysis](https://github.com/Hamzah5566/Social-Network-Analysis) | Python, NetworkX | Analyses and visualises connections in a social graph |
| [Grade Tracker](https://github.com/Hamzah5566/Python-grade-tracker-with-Unit-Testing) | Python, unittest | Calculates per-module grades, with a unit test suite |
| [CRUD Inventory System](https://github.com/Hamzah5566/CRUD-operations-Programs) | Python, SQLite | Product inventory with full create, read, update and delete |
| [Tax Calculator](https://github.com/Hamzah5566/Python-tax-calculator) | Python | SARS income tax calculator with a form-based interface |
| [Loan Calculator](https://github.com/Hamzah5566/Simple-Interest-Loan-Calculator) | Java, Android | Simple interest and loan repayment calculator |
| [Tablet Finance App](https://github.com/Hamzah5566/Android-Tablet-Finance-App) | Java, Android | Works out instalments and total cost on a purchase |
| [Student Grade Calculator](https://github.com/Hamzah5566/Student-Grade-Calculator-App) | Java, Android | Averages student scores and assigns a grade |
