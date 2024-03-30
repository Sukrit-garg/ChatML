# Chatml: Your AI Study Buddy 🤖

Unlock the power of advanced language models with Chatml, your AI-powered study companion tailored for machine learning enthusiasts. Leveraging the cutting-edge llama-2-7b-chat.ggmlv3.q8_0 model, Chatml is a conversational chatbot designed to assist you in your machine learning journey, providing insightful responses to your queries and fostering an engaging learning experience.

## Features 🚀

- **Customized Knowledge Base:** Chatml is trained on a specific dataset specially for machine learning topics, ensuring its expertise in machine learning concepts, algorithms, and best practices.
  
- **Interactive Chatbot Interface:** Engage in natural language conversations with Chatml, asking questions, seeking explanations, and exploring complex machine learning topics with ease.
  
- **Streamlined Deployment:** Powered by Chainlit and Langchain, Chatml offers a seamless and user-friendly deployment experience, accessible from various platforms.


## Installation 🛠️

To run Chatml locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sukrit-garg/ChatML/
   ```
   
2. **Navigate to the project directory:**
   ```bash
   cd chatml
   ```

3. **Create a virtual environment and activate it:**
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

4. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Set up the necessary environment variables and configurations.**

6. **Download the Llama model from: [link](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin)**

7. **Run the ingest.py file to create the embeddings.**

8. **Run the Chainlit application:**
   ```bash
   chainlit run model.py -w
   ```

   This will start the Chatml chatbot interface, and you can begin interacting with your AI study buddy.

## Usage 🧠

Once the Chainlit application is running, you can access the Chatml chatbot interface through your web browser. Type in your machine learning-related questions, and Chatml will provide insightful responses, explanations, and guidance.

Feel free to explore various topics, from introductory concepts to advanced algorithms and techniques. Chatml is designed to foster an engaging and interactive learning experience, making it an invaluable resource for students, researchers, and professionals alike.

### Sample Outputs:
<img width="850" alt="image" src="https://github.com/Sukrit-garg/ChatML/assets/101797008/c7d0b12b-8625-4235-ad34-c66c362f66e5">

<img width="850" alt="image" src="https://github.com/Sukrit-garg/ChatML/assets/101797008/7ca28e52-8228-491c-a42f-a18284d70413">




## Contributing 🤝

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request. Together, we can enhance Chatml and make it an even more powerful AI study buddy.

## License 📝

This project is licensed under the MIT License.

## Acknowledgments 🙌

We would like to express our gratitude to the open-source community for their contributions, particularly the developers of Chainlit, Langchain, and the llama-2-7b-chat.ggmlv3.q8_0 model. Their efforts have made projects like Chatml possible.
