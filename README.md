
# Movie Graph Database with Neo4j and RAG

This project demonstrates building a graph database using Neo4j to store and query a movie dataset. With the power of Retrieval-Augmented Generation (RAG), we create an interactive Q&A system that can answer questions related to the movie data in a conversational way. The project is implemented in a Jupyter Notebook environment, leveraging the Gemma2-9b-It model for enhanced question-answering capabilities.


### Overview
This project leverages:

- Neo4j as a graph database to store and manage movie data.
GraphCypherQAChain to create a Q&A system that enables conversational interaction with the graph content.
- Gemma2-9b-It model for natural language processing tasks within the RAG framework.

### Goals
- Graph Data Storage: Load a movie dataset into a Neo4j graph database.
- Q&A Interface: Enable users to query movie information using natural language through RAG.

#### What is a Graph Database?
A graph database stores and manages data in terms of nodes (entities), edges (relationships), and properties (attributes). This structure offers a unique advantage over traditional relational databases by directly mapping and managing complex, interconnected data in a way that is intuitive and highly efficient.

#### Why Graph Databases Are Important
In today's data-driven world, many applications require not only data storage but also an understanding of relationships among data points. This is especially important in scenarios like:

Recommendation Systems: For example, Netflix and Amazon use graph databases to make personalized recommendations based on user preferences and interactions.
Social Networks: Platforms like LinkedIn and Facebook represent users and their connections, posts, and comments as nodes and relationships, making it possible to quickly find and analyze user relationships.
Knowledge Graphs: Search engines like Google use graph databases to create knowledge graphs that relate real-world entities and concepts, helping provide contextual answers to user queries.

#### Dataset
The movie dataset used in this project is sourced from the following link
- https://raw.githubusercontent.com/tomasonjo/blog-datasets/main/movies/movies_small.csv

It contains details on various movies, such as title, genre, imdbRating, and other attributes relevant to our graph database model.



## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Prerequisites
- Python 3.8+
- Jupyter Notebook/Colab



## Contributing

Contributions are always welcome!


