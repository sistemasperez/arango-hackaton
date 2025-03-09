# ArangoGraph Geo X-ray

## Overview

ArangoGraph Geo X-ray is a powerful application that leverages OpenStreetMap data and Agentic AI to provide insightful analysis of local market dynamics and community needs. By combining the strengths of AQL (ArangoDB Query Language) and NetworkX (graph analysis library), this project enables users to perform complex queries and visualize graph data, uncovering hidden patterns and opportunities.

## Features

* **Intelligent Query Routing:** Automatically routes natural language queries to the appropriate execution engine (AQL, NetworkX, or Hybrid).
* **Hybrid Query Execution:** Combines the results of AQL and NetworkX queries to answer complex questions.
* **Graph Data Analysis:** Analyzes business density, proximity, and connections to identify opportunities and service gaps.
* **Custom Dataset Integration:** Allows users to upload and analyze their own location-specific data.
* **Real-time Demos:** Provides interactive demos and visualizations of query results.
* **User-in-the-Loop Feedback:** Implements mechanisms to improve query classification and response relevance.
* **Custom Logging:** Captures user queries for system optimization and improvement.

## Technologies

* **ArangoDB:** Graph database for storing and querying data.
* **OpenStreetMap:** Source of geographic data.
* **NetworkX:** Python library for graph analysis.
* **AQL (ArangoDB Query Language):** For database queries.
* **LangChain:** Framework for developing applications powered by language models.
* **spaCy:** Natural language processing library.
* **Sentence Transformers:** Library for sentence embeddings.
* **OpenAI API:** For generating and refining prompts.
* **Gradio:** For building the user interface.
* **Python:** Programming language.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/sistemasperez/arango-hackaton.git
    ```

2.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Set up ArangoDB:**

    * Install and configure ArangoDB.
    * Create a database and collections as needed.

4.  **Configure API keys:**

    * Add your OpenAI API key to the appropriate configuration file or environment variable.

5.  **Run the application:**


## Usage

1.  **Launch the Gradio interface.**
2.  **Enter natural language queries.**
3.  **View the results and visualizations.**
4.  **Provide feedback to improve the system.**

## Dataset

This project uses a custom dataset to provide specific and in-depth analysis of local market dynamics and community needs. This allows for the exploration of complex relationships and patterns crucial for identifying underserved markets, optimizing business placement, and pinpointing communities lacking essential services.

## Future Improvements

* Enhance the query classifier's accuracy.
* Implement more advanced data visualization techniques.
* Expand the range of supported query types.
* Integrate additional data sources.
* Further refine the user-in-the-loop feedback mechanisms.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to suggest improvements or report bugs.

## License


## Contact

Anibal Perez
