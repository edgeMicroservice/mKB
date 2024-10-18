# mKB - mimik Knowledge Base Microservice
mKB is a microservice designed to perform semantic searches on datasets. These datasets are pre-processed, chunked, and indexed by creating vector representations (embeddings) of the documents using the [mimik dataset-cli tool](https://www.npmjs.com/package/@mimik/dataset-cli).

## Features

### Dataset Management

- Create Datasets: Upload pre-processed JSON datasets to the Knowledge Base.
- List Datasets: Retrieve a list of all available datasets.
- Delete Datasets: Remove datasets by their name.
- Upload Chunks: Add specific chunks to an existing dataset using a pre-processed file.

### Search and Retrieval

- Similarity Search: Perform searches across datasets based on a prompt, returning the most relevant content.
- Chunk Retrieval: Retrieve individual chunks by their chunkId for detailed inspection.

## Installation Guide

1. Download the latest .zip file for the most recent release [HERE](https://github.com/edgeMicroservice/mKB/releases).
2. Unzip the package.
3. Locate the unzipped .tar file; this artifact is needed for the edge microservice deployment.
4. If you are deploying the edge microservice for the first time, please follow the [edge microservice deployment quick start guide](https://devdocs.mimik.com/tutorials/01-submenu).

- For additional information on ai tutorials, please visit [mimik ai quickstart tutorials](https://devdocs.mimik.com/tutorials/02-submenu)
