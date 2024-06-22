# Auto-X Search

## Features
- Auto-X Search integrates seamlessly, offering built-in security measures like data compliance and firewall protections, ensuring secure AI connectivity and granular access control.

- Auto-X Search simplifies the use of Retrieval-Augmented Generation (RAG). Our platform eliminates the need for external vector databases, LangChain, or LlamaIndex, making implementing AI RAG tools directly on your data easier.

- Operate directly on local data without the hassles of ETL processes, re-indexing, or data movement. It enhances data security by allowing the data to remain in place and run securely inside your firewall.

- Enhance team efficiency and streamline workflows with Auto-X Server. It helps you find information faster and make smarter decisions, accelerating enterprise AI transformation and boosting productivity.

- Special modes to better answer specific types of questions.
    - Searches the entire web to find the best results.
    - Local search tasks with RAG that does not require searching the web.
    - Academic Search Mode: Finds articles and papers, ideal for academic research.
    - YouTube Search Mode: Finds YouTube videos based on the search query.
    - Wolfram Alpha Search Mode: Answers queries that need calculations or data analysis using Wolfram Alpha.
    - Reddit Search Mode: Searches Reddit for discussions and opinions related to the query.
- Some search tools might give you outdated info because they use data from crawling bots and convert them into embeddings and store them in a index. Unlike them, Perplexica uses SearxNG, a metasearch engine to get the results and rerank and get the most relevant source out of it, ensuring you always get the latest information without the overhead of daily data updates.

## Non-Docker Installation
1. Clone the repository and rename the sample.config.toml file to config.toml in the root directory. Ensure you complete all required fields in this file.
2. Rename the .env.example file to .env in the ui folder and fill in all necessary fields.
3. Run 'npm install sharp --ignore-scripts'
4. After populating the configuration and environment files, run 'npm i' in both the ui folder and the root directory.
5. Install the dependencies and then execute 'npm run build' in both the ui folder and the root directory.
6. Finally, start both the frontend and the backend by running 'npm run start' in both the ui folder and the root directory.

