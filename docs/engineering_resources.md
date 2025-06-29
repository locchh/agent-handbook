# Engineering Resources

### LLM Frameworks

- **n8n**: [https://n8n.io/](https://n8n.io/)

- **crewAI**: [https://github.com/crewAIInc/crewAI](https://github.com/crewAIInc/crewAI)

- **langflow**: [https://github.com/langflow-ai/langflow](https://github.com/langflow-ai/langflow)

- **LangChain**: [https://www.langchain.com/](https://www.langchain.com/)

- **LangGraph**: [https://www.langchain.com/langgraph](https://www.langchain.com/langgraph)

- **AutoGen**: [https://github.com/microsoft/autogen](https://github.com/microsoft/autogen)

- **LlamaIndex**: [https://www.llamaindex.ai/](https://www.llamaindex.ai/)

- **llama.cpp**: [https://github.com/ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp)

- **Ollama**: [https://ollama.com/](https://ollama.com/)

- **vLLM**: [https://docs.vllm.ai/en/latest/](https://docs.vllm.ai/en/latest/)

### Data & Evaluation

- **Argilla**: [https://argilla.io/](https://argilla.io/)
- **Distilabel**: [https://distilabel.argilla.io/latest/](https://distilabel.argilla.io/latest/)
- **LightEval**: [https://github.com/huggingface/lighteval](https://github.com/huggingface/lighteval)

## Databases & APIs

- **PostgreSQL**: [https://www.postgresql.org/docs/](https://www.postgresql.org/docs/)

- **MySQL**: [https://www.mysql.com/](https://www.mysql.com/)

- **MongoDB**: [https://www.mongodb.com/](https://www.mongodb.com/)

- **Neo4j**: [https://neo4j.com/](https://neo4j.com/)

- **Chroma**: [https://www.trychroma.com/](https://www.trychroma.com/)

- **Qdrant**: [https://qdrant.tech/](https://qdrant.tech/)

- **Milvus**: [https://milvus.io/](https://milvus.io/)

- **GraphQL**: [https://graphql.org/](https://graphql.org/)

- **FAISS**: [https://github.com/facebookresearch/faiss](https://github.com/facebookresearch/faiss)

## Tools

### Search

Tools that execute online searches:

| Tool/Toolkit                                                                               | Free/Paid                    | Return Data                                           |
| ------------------------------------------------------------------------------------------ | ---------------------------- | ----------------------------------------------------- |
| [Bing Search](https://python.langchain.com/docs/integrations/tools/bing_search)            | Paid                         | URL, Snippet, Title                                   |
| [Brave Search](https://python.langchain.com/docs/integrations/tools/brave_search)          | Free                         | URL, Snippet, Title                                   |
| [DuckDuckgoSearch](https://python.langchain.com/docs/integrations/tools/duckduckgo_search) | Free                         | URL, Snippet, Title                                   |
| [Exa Search](https://python.langchain.com/docs/integrations/tools/exa_search)              | 1000 free searches/month     | URL, Author, Title, Published Date                    |
| [Google Search](https://python.langchain.com/docs/integrations/tools/google_search)        | Paid                         | URL, Snippet, Title                                   |
| [Google Serper](https://python.langchain.com/docs/integrations/tools/google_serper)        | Free                         | URL, Snippet, Title, Search Rank, Site Links          |
| [Jina Search](https://python.langchain.com/docs/integrations/tools/jina_search)            | 1M Response Tokens Free      | URL, Snippet, Title, Page Content                     |
| [Mojeek Search](https://python.langchain.com/docs/integrations/tools/mojeek_search)        | Paid                         | URL, Snippet, Title                                   |
| [SearchApi](https://python.langchain.com/docs/integrations/tools/search_api)               | 100 Free Searches on Sign Up | URL, Snippet, Title, Search Rank, Site Links, Authors |
| [SearxNG Search](https://python.langchain.com/docs/integrations/tools/searxng_search)      | Free                         | URL, Snippet, Title, Category                         |
| [SerpAPI](https://python.langchain.com/docs/integrations/tools/serpapi)                    | 100 Free Searches/Month      | Answer                                                |
| [Tavily Search](https://python.langchain.com/docs/integrations/tools/tavily_search)        | 1000 free searches/month     | URL, Content, Title, Images, Answer                   |
| [You.com Search](https://python.langchain.com/docs/integrations/tools/youcom_search)       | Free for 60 days             | URL, Title, Page Content                              |

### Code Interpreter

| Tool/Toolkit                                                                                                                        | Supported Languages           | Sandbox Lifetime    | Supports File Uploads | Return Types | Supports Self-Hosting |
| ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- | ------------------- | --------------------- | ------------ | --------------------- |
| [Azure Container Apps dynamic sessions](https://python.langchain.com/docs/integrations/tools/azure_container_apps_dynamic_sessions) | Python                        | 1 Hour              | ✅                     | Text, Images | ❌                     |
| [Bearly Code Interpreter](https://python.langchain.com/docs/integrations/tools/bearly_code_interpreter)                             | Python                        | Resets on Execution | ✅                     | Text         | ❌                     |
| [Riza Code Interpreter](https://python.langchain.com/docs/integrations/tools/riza_code_interpreter)                                 | Python, JavaScript, PHP, Ruby | Resets on Execution | ✅                     | Text         | ✅                     |

### Productivity

| Tool/Toolkit                                                                                | Pricing                                                 |
| ------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| [Github Toolkit](https://python.langchain.com/docs/integrations/tools/github_toolkit)       | Free                                                    |
| [Gitlab Toolkit](https://python.langchain.com/docs/integrations/tools/gitlab_toolkit)       | Free for personal project                               |
| [Gmail Toolkit](https://python.langchain.com/docs/integrations/tools/gmail_toolkit)         | Free, with limit of 250 quota units per user per second |
| [Infobip Tool](https://python.langchain.com/docs/integrations/tools/infobip_tool)           | Free trial, with variable pricing after                 |
| [Jira Toolkit](https://python.langchain.com/docs/integrations/tools/jira_toolkit)           | Free, with rate limits                                  |
| [Office365 Toolkit](https://python.langchain.com/docs/integrations/tools/office365_toolkit) | Free with Office365, includes rate limits               |
| [Slack Toolkit](https://python.langchain.com/docs/integrations/tools/slack_toolkit)         | Free                                                    |
| [Twilio Tool](https://python.langchain.com/docs/integrations/tools/twilio_tool)             | Free trial, with pay-as-you-go pricing after            |

### Web Browsing

| Tool/Toolkit                                                                                                              | Pricing                                                     | Supports Interacting with the Browser |
| ------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------- |
| [AgentQL Toolkit](https://python.langchain.com/docs/integrations/tools/agentql_toolkit)                                   | Free trial, with pay-as-you-go and flat rate plans after    | ✅                                     |
| [Hyperbrowser Browser Agent Tools](https://python.langchain.com/docs/integrations/tools/hyperbrowser_browser_agent_tools) | Free trial, with flat rate plans and pre-paid credits after | ✅                                     |
| [Hyperbrowser Web Scraping Tools](https://python.langchain.com/docs/integrations/tools/hyperbrowser_web_scraping_tools)   | Free trial, with flat rate plans and pre-paid credits after | ❌                                     |
| [MultiOn Toolkit](https://python.langchain.com/docs/integrations/tools/multion_toolkit)                                   | 40 free requests/day                                        | ✅                                     |
| [PlayWright Browser Toolkit](https://python.langchain.com/docs/integrations/tools/playwright_browser_toolkit)             | Free                                                        | ✅                                     |
| [Requests Toolkit](https://python.langchain.com/docs/integrations/tools/requests_toolkit)                                 | Free                                                        | ❌                                     |

### Database

| Tool/Toolkit                                                                                         | Allowed Operations              |
| ---------------------------------------------------------------------------------------------------- | ------------------------------- |
| [Cassandra Database Toolkit](https://python.langchain.com/docs/integrations/tools/cassandra_toolkit) | SELECT and schema introspection |
| [SQLDatabase Toolkit](https://python.langchain.com/docs/integrations/tools/sqldatabase_toolkit)      | Any SQL operation               |
| [Spark SQL Toolkit](https://python.langchain.com/docs/integrations/tools/spark_sql_toolkit)          | Any SQL operation               |


### Finance

| Tool/Toolkit                                                      | Pricing | Capabilities                                                                     |
| ----------------------------------------------------------------- | ------- | -------------------------------------------------------------------------------- |
| [GOAT](https://python.langchain.com/docs/integrations/tools/goat) | Free    | Create and receive payments, purchase physical goods, make investments, and more |


For a full list of tools, visit the [LangChain Tool Integrations Page](https://python.langchain.com/docs/integrations/tools/).

## Document Loaders

### Webpages

These loaders allow you to load webpages. See this [guide](https://docs.langchain.com/docs/modules/data_connection/document_loaders/how_to/web) to get started.

| Document Loader                                                                                 | Description                         | Type    |
| ----------------------------------------------------------------------------------------------- | ----------------------------------- | ------- |
| [`Web`](https://python.langchain.com/docs/integrations/document_loaders/web_base)               | Uses urllib and BeautifulSoup       | Package |
| [`Unstructured`](https://python.langchain.com/docs/integrations/document_loaders/unstructured)  | Parses web pages using Unstructured | Package |
| [`RecursiveURL`](https://python.langchain.com/docs/integrations/document_loaders/recursive_url) | Recursively scrapes child links     | Package |
| [`Sitemap`](https://python.langchain.com/docs/integrations/document_loaders/sitemap)            | Loads pages via sitemap             | Package |
| [`Firecrawl`](https://python.langchain.com/docs/integrations/document_loaders/firecrawl)        | API service, deployable locally     | API     |
| [`Docling`](https://ds4sd.github.io/docling/)                                                   | Uses Docling to parse web pages     | Package |
| [`Hyperbrowser`](https://python.langchain.com/docs/integrations/document_loaders/hyperbrowser)  | Scales headless browser tasks       | API     |
| [`AgentQL`](https://python.langchain.com/docs/integrations/document_loaders/agentql)            | Structured web data extraction      | API     |

### PDFs

See the [guide](https://docs.langchain.com/docs/modules/data_connection/document_loaders/how_to/pdf) to load PDF files.

| Document Loader                                                                                      | Description                  | Type    |
| ---------------------------------------------------------------------------------------------------- | ---------------------------- | ------- |
| [`PyPDF`](https://python.langchain.com/docs/integrations/document_loaders/pypdf)                     | Loads PDFs with `pypdf`      | Package |
| [`Unstructured`](https://python.langchain.com/docs/integrations/document_loaders/unstructured)       | Open source PDF loader       | Package |
| [`Amazon Textract`](https://python.langchain.com/docs/integrations/document_loaders/amazon_textract) | Loads PDFs with AWS Textract | API     |
| [`MathPix`](https://python.langchain.com/docs/integrations/document_loaders/mathpix_pdf)             | Extracts scientific PDFs     | Package |
| [`PDFPlumber`](https://python.langchain.com/docs/integrations/document_loaders/pdfplumber)           | Parses PDFs with PDFPlumber  | Package |
| [`PyPDFDirectory`](https://python.langchain.com/docs/integrations/document_loaders/pypdf_directory)  | Loads all PDFs from a folder | Package |
| [`PyPDFium2`](https://python.langchain.com/docs/integrations/document_loaders/pypdfium2)             | Loads using PyPDFium2        | Package |
| [`PyMuPDF`](https://python.langchain.com/docs/integrations/document_loaders/pymupdf)                 | Loads with PyMuPDF           | Package |
| [`PyMuPDF4LLM`](https://python.langchain.com/docs/integrations/document_loaders/pymupdf4llm)         | Converts PDF to markdown     | Package |
| [`PDFMiner`](https://python.langchain.com/docs/integrations/document_loaders/pdfminer)               | Uses PDFMiner                | Package |
| [`Upstage`](https://python.langchain.com/docs/integrations/document_loaders/upstage)                 | Loads PDFs via Upstage API   | Package |
| [`Docling`](https://ds4sd.github.io/docling/)                                                        | Loads PDFs with Docling      | Package |

### Cloud Providers

| Document Loader                | Description                     | API Reference                     |
| ------------------------------ | ------------------------------- | --------------------------------- |
| AWS S3 Directory               | Load from an S3 directory       | `S3DirectoryLoader`               |
| AWS S3 File                    | Load from an S3 file            | `S3FileLoader`                    |
| Azure AI Data                  | Load from Azure AI services     | `AzureAIDataLoader`               |
| Azure Blob Storage Container   | Load from Azure Blob container  | `AzureBlobStorageContainerLoader` |
| Azure Blob Storage File        | Load from Azure Blob file       | `AzureBlobStorageFileLoader`      |
| Dropbox                        | Load from Dropbox               | `DropboxLoader`                   |
| Google Cloud Storage Directory | Load from GCS bucket            | `GCSDirectoryLoader`              |
| Google Cloud Storage File      | Load from GCS object            | `GCSFileLoader`                   |
| Google Drive                   | Load Google Docs from Drive     | `GoogleDriveLoader`               |
| Huawei OBS Directory           | Load from Huawei OBS Directory  | `OBSDirectoryLoader`              |
| Huawei OBS File                | Load from Huawei OBS File       | `OBSFileLoader`                   |
| Microsoft OneDrive             | Load from OneDrive              | `OneDriveLoader`                  |
| Microsoft SharePoint           | Load from SharePoint            | `SharePointLoader`                |
| Tencent COS Directory          | Load from Tencent COS Directory | `TencentCOSDirectoryLoader`       |
| Tencent COS File               | Load from Tencent COS File      | `TencentCOSFileLoader`            |

### Social Platforms

| Document Loader | API Reference        |
| --------------- | -------------------- |
| Twitter         | `TwitterTweetLoader` |
| Reddit          | `RedditPostsLoader`  |

### Messaging Services

| Document Loader | API Reference            |
| --------------- | ------------------------ |
| Telegram        | `TelegramChatFileLoader` |
| WhatsApp        | `WhatsAppChatLoader`     |
| Discord         | `DiscordChatLoader`      |
| Facebook Chat   | `FacebookChatLoader`     |
| Mastodon        | `MastodonTootsLoader`    |

### Productivity Tools

| Document Loader | API Reference           |
| --------------- | ----------------------- |
| Figma           | `FigmaFileLoader`       |
| Notion          | `NotionDirectoryLoader` |
| Slack           | `SlackDirectoryLoader`  |
| Quip            | `QuipLoader`            |
| Trello          | `TrelloLoader`          |
| Roam            | `RoamLoader`            |
| GitHub          | `GithubFileLoader`      |

### Common File Types

| Document Loader                                                                                | Data Type                  |
| ---------------------------------------------------------------------------------------------- | -------------------------- |
| [`CSVLoader`](https://python.langchain.com/docs/integrations/document_loaders/csv)             | CSV files                  |
| [`DirectoryLoader`](https://python.langchain.com/docs/integrations/document_loaders/directory) | All files in directory     |
| [`Unstructured`](https://docs.unstructured.io/platform/supported-file-types)                   | Many types supported       |
| [`JSONLoader`](https://python.langchain.com/docs/integrations/document_loaders/json)           | JSON files                 |
| [`BSHTMLLoader`](https://python.langchain.com/docs/integrations/document_loaders/bshtml)       | HTML files                 |
| [`Docling`](https://ds4sd.github.io/docling/)                                                  | Multiple formats supported |
