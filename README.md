# RAG-Assignment

## Overview
RAG-Assignment is a project designed to illustrate the usage of Retrieval-Augmented Generation (RAG) in conversational AI applications. The project showcases how to effectively leverage external knowledge sources to improve the quality and relevance of generated responses.

## Architecture
The architecture of the RAG-Assignment project is built upon three main components:
1. **Retriever**: This component fetches relevant documents or data from a knowledge base based on the user's query.
2. **Generator**: This utilizes a language model to generate responses based on the retrieved data.
3. **Interface**: The user interface allows users to interact with the system and view results in real-time.

## Installation
To install the RAG-Assignment project, please follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/theAbheekMukherjee/RAG-Assignment.git
   cd RAG-Assignment
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the project, execute the following command:
```bash
python main.py
```

## Examples
1. **Query**: "What is the capital of France?"
   **Response**: "The capital of France is Paris."

2. **Query**: "Explain the concept of RAG."
   **Response**: "Retrieval-Augmented Generation combines the strengths of retrieval-based systems and generative models to enhance conversational capabilities."

## Hyperparameters
The following hyperparameters can be adjusted for model training and inference:
- **learning_rate**: The step size at each iteration while moving toward a minimum of a loss function.
- **batch_size**: The number of training examples utilized in one iteration.
- **num_epochs**: The number of times the learning algorithm will work through the entire training dataset.
- **max_input_length**: The maximum length of input sequences.

Feel free to experiment with these hyperparameters to optimize performance.

## Contributing
Contributions are welcome! Please fork the repository and submit your pull requests for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.