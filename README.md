# The Equidistant Project

## Introduction
The Equidistant Project stands as a beacon against the tide of misinformation and bias prevalent in the news sphere. By scrapping a diverse range of news articles, extracting the factual essence, and crafting new, unbiased articles, we aspire to create a platform where users can access and interpret factual news. This endeavor is geared towards nurturing a more enlightened public discourse.

## Features
- **Article Scrapping**: Our robust in-house scrapping system meticulously extracts articles from a myriad of news sources.
- **Fact Extraction**: Harnessing the power of advanced Natural Language Processing (NLP) techniques to sift through the scraped articles and extract factual information.
- **Article Generation**: Generates fresh articles based solely on the extracted facts, promoting a narrative free of bias.
- **User-Friendly Interface**: A sleek, intuitive interface enabling users to effortlessly search for and read generated news articles.
- **Interpretation Tools**: Incorporates tools to aid users in interpreting the factual information presented.

## Tech Stack Description

### Backend
- **Web Scraping**: A robust scrapping mechanism to harvest news articles from various sources.
- **Fact Extraction and Analysis**: Leverages NLP libraries like GPT and BERT for precise fact extraction and analysis.
- **Database Management**: Utilizes Weaviate, a vector database, for efficient storage and management of scraped and generated articles.

### Middle End
- **Bun Runtime**: The Bun runtime in the middle end orchestrates a seamless interaction between the backend and frontend, ensuring smooth data processing and transfer.

### Frontend
- **Web Framework**: Crafted with Next.js, a React-based framework, to provide a user-centric and efficient interface.

### Infrastructure
- **In-house Server**: Hosted on an in-house server nestled in our garage in California, embodying the true spirit of a garage startup.
- **Containerization**: Every component is dockerized to ensure a harmonized environment across different development and production settings.

### Continuous Integration/Continuous Deployment (CI/CD)
- **GitHub Actions**: Harnesses the power of GitHub Actions for implementing CI/CD pipelines, ensuring automated testing and seamless deployment.

## Technology Used

- **Programming Languages**: Python, JavaScript
- **Frameworks**: Next.js
- **Database**: Weaviate
- **Runtime**: Bun
- **NLP Libraries**: GPT, BERT
- **Containerization**: Docker
- **CI/CD Tools**: GitHub Actions

## Getting Started

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/equidistant-project.git
    cd equidistant-project
    ```

2. **Set Up Environment**
    - Install the necessary dependencies as listed in `requirements.txt`.
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Application**
    - Follow the instructions detailed in the `RUNNING.md` file to kickstart the application locally.

## Contributing

We warmly welcome contributions from the community. To contribute, please fork the repository, make your amendments, and open a pull request. For more details, refer to the `CONTRIBUTING.md` file.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

---

For additional information, feel free to visit the [project website](https://your-website.com) or reach out to the [project maintainers](mailto:project-maintainers@example.com).
