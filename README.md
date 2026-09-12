## Installation Instructions

Follow these steps to set up the project on your computer or in GitHub Codespaces.

1. Open a terminal in the project folder.
2. Create and activate a virtual environment (optional but recommended):

```bash
python -m venv .venv
source .venv/bin/activate
```

3. Install the required Python packages:

```bash
pip install -r requirements.txt
```

4. Start Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook
```

5. In the browser, open one of the notebooks in the `notebooks/` folder, such as `filings.ipynb`.
6. Click the Run button on the first cell, then keep running the cells one by one until the notebook finishes.

If you are using GitHub Codespaces, the environment usually already has Python installed, so the main commands are:

```bash
git clone <your-fork-url>
cd smu-cce-starter
pip install -r requirements.txt
jupyter notebook
```

---

## Code Walkthrough

This repository is a beginner-friendly data project for financial analysis. The main work is in the `notebooks/` folder.

### Main files and folders

- `notebooks/filings.ipynb` — looks up company filing and financial data. This is often the starting point for exploring a company.
- `notebooks/news.ipynb` — gathers and reviews recent news related to a stock or company.
- `notebooks/stock_price_ratings.ipynb` — combines stock price information and rating data to help compare performance and sentiment.
- `lessons/` — course notes and step-by-step instructions that explain the learning flow.
- `requirements.txt` — lists the Python packages needed to run the project.
- `README.md` — overall project overview and course context.

### How the application works

The project begins by loading Python libraries such as `pandas` and `yfinance`. Then a notebook pulls market or company data from online sources, usually using finance APIs or stock data services. The code cleans the data, organizes it into tables, and then shows results in charts or text output.

From start to finish, the flow is simple:

1. Open a notebook.
2. Run the first code cell to import libraries.
3. Load data for a company or stock.
4. Clean and organize the data.
5. View results such as tables, summaries, or charts.
6. Repeat with another notebook for news or ratings.

This starter repo teaches the basic workflow behind data-driven analysis: get data, prepare it, analyze it, and present it clearly.

---

 # Cloud Computing for Economics: Starter Repo 

  This repository contains the starter code and lesson materials for building a Python financial-data application and deploying it to AWS.

  Students will use GitHub Codespaces, Python, Jupyter notebooks, Streamlit, Git, and AWS CloudFormation.

  ## Learning outcomes

  By the end of the course, you will be able to:

   1.  Build and deploy an analytics application with a simple Front End / back-end (using AI)
   2.  Host and share the application on a cloud platform (e.g., AWS EC2 or similar) so that others can access it securely over the web
   3.  Integrate data sources and APIs into the app to enable interactive, real-time analytics
   4.  Apply cloud architecture best practices, ensuring the app demonstrates scalability, performance efficiency, and basic security
   5.  Showcase your work on GitHub as part of a personal portfolio, demonstrating practical cloud and analytics skills through a shareable, explorable repository

  
  ## Repository structure

  ```text
  .
  ├── lessons/          # Step-by-step course instructions
  ├── notebooks/        # Starter financial-data notebooks
  ├── requirements.txt  # Python dependencies
  └── README.md         # Course overview