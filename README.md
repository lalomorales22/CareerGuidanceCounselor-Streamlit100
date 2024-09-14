# Career Guidance Counselor

Career Guidance Counselor is a Streamlit-based application that uses AI to provide personalized career advice based on users' interests, skills, education, and experience. It leverages advanced language models to offer insights, suggestions, and guidance for career development and decision-making.

## Features

- Personalized career advice based on user input
- Customizable career interests and skills selection
- Education level and work experience consideration
- Interactive chat interface for detailed career discussions
- Support for multiple AI models (OpenAI and Ollama)
- Conversation saving and loading functionality
- Token usage tracking
- Dark/Light theme options

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/lalomorales22/CareerGuidanceCounselor-Streamlit100.git
   cd career-guidance-counselor
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key: `OPENAI_API_KEY=your_api_key_here`

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and go to `http://localhost:8501`

3. Enter your name and configure your career profile in the sidebar:
   - Select your career interests
   - Choose your strongest skill categories
   - Set your education level and years of experience

4. Start asking for career advice or sharing your career goals in the chat interface

5. Interact with the AI counselor to get personalized guidance and insights

## Customization

- Modify the `CAREER_FIELDS` and `SKILL_CATEGORIES` lists in `app.py` to add or remove options
- Adjust the `custom_instructions` in the sidebar to change the AI's behavior and focus

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
