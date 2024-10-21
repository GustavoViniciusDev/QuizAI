
# QuizAI

QuizAI is an AI-powered quiz generator that creates quizzes based on user-provided topics and the desired number of questions. With QuizAI, users can easily generate quizzes by specifying a theme and the number of questions they want, and the AI will automatically create relevant questions based on the provided input.

## Features
- Generate quizzes on any topic using AI.
- Specify the number of questions to generate.
- Receive questions tailored to the chosen theme.

## How It Works
1. The user provides a topic and the desired number of questions.
2. QuizAI uses AI to generate quiz questions based on the topic.
3. The generated quiz is displayed to the user, ready to be answered.

## Installation

To set up QuizAI locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/quizai.git
   cd quizai
   ```

2. **Install dependencies:**
   ```bash
   # If using Node.js
   npm install

   # Or with Yarn
   yarn install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory with your API keys and configurations:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

4. **Run the application:**
   ```bash
   # Development mode
   npm run dev

   # Or with Yarn
   yarn dev
   ```

5. **Access the application:**
   Open a web browser and navigate to `http://localhost:3000` (or the configured port).

## Contributing

We welcome contributions! To contribute to QuizAI, follow these steps:

1. **Fork the repository** and clone it to your local machine.
2. **Create a new branch** for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** and commit them:
   ```bash
   git commit -m "Add your meaningful commit message here"
   ```
4. **Push your changes** to your forked repository:
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Create a Pull Request** on the original repository:
   - Go to the [QuizAI repository](https://github.com/yourusername/quizai) on GitHub.
   - Click on the "New Pull Request" button.
   - Choose your branch and submit the pull request.

### Pull Request Guidelines
- Make sure your code follows the existing code style and conventions.
- Write clear, concise commit messages.
- If you are fixing a bug, provide a detailed description of the bug and how you fixed it.
- If you are adding a new feature, include a detailed explanation of the feature and why it is needed.
- Make sure to include tests if applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, feel free to reach out or open an issue on GitHub.
