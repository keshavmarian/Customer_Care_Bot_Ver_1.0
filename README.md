# Customer_Care_Bot_Ver_1.0
Here's a fully rephrased version with entirely new wording:  "CustomerCareBot leverages Streamlit to offer automated customer support, employing advanced AI for crafting responses."
# CustomerCareBot

CustomerCareBot is a web application built with Streamlit to automate customer service interactions using AI-driven language models. It harnesses your company's data to generate precise responses. This tool relies on historical data from previous customer service interactions to craft context-aware replies.

The data utilized is sourced from the Bitext - Customer Service Tagged Training Dataset for LLM-based Virtual Assistants.

## Features

- **Automated Response Generation:** Employs OpenAI's GPT-3.5-turbo model to produce relevant and context-aware responses to customer inquiries.
- **Conversation Log:** Retains a history of user interactions and bot responses for easy reference and continuity.
- **User-Friendly Interface:** A straightforward text area for entering customer messages and a button to swiftly generate responses.
- **Adjustable Settings:** Options to modify response generation parameters like temperature and model selection.

## Installation

To set up CustomerCareBot locally, follow these instructions:

1. Clone the repository:
    ```bash
    git clone https://github.com/keshavmarian/Customer_Care_Bot_Ver_1.0.git
    cd Customer_Care_Bot_Ver_1.0
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Configure environment variables:
    Ensure you have set the necessary environment variables, such as `OPENAI_API_KEY` for OpenAI authentication.

4. Launch the Streamlit application:
    ```bash
    streamlit run app.py
    ```

5. Open your web browser and navigate to `http://localhost:8501` to access the app.

## Usage

1. Input a customer message in the text area labeled "Customer message".
2. Press "Ctrl+Enter" to activate the AI model and generate a response.
3. The response will be displayed along with the previous conversation history.
4. Use the conversation log to maintain context and ensure seamless customer interactions.

## Example

Here's an example of how to use CustomerCareBot:

- **Customer Input:**
    ```
    Hello, I need help canceling an order I made.
    ```

- **Generated Response:**
    ```
    Assistant: I understand your concern. To cancel your order, please provide your order number and contact information so we can assist you further.
    ```

## Contributions

We welcome contributions! If you have suggestions, feature requests, or find any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
