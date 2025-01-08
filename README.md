# dbchat

## Text-to-SQL Model Integration

This project demonstrates the integration of OpenAI's GPT-4 model to generate SQL queries based on user instructions. The model interprets instructions and generates SQL code to modify databases and tables. The project includes:

- **System Prompt**: Defines the role of the model and the type of tasks it performs.
- **Task Type**: Specifies the nature of the SQL tasks (e.g., defining data).
- **Context Handling**: Uses context from previous commands to infer database details.
- **SQL Code Generation**: Generates SQL queries for creating, altering, and managing database objects.
- **MySQL Integration**: Executes the generated SQL queries using MySQL Connector.

### Features

- **Dynamic SQL Generation**: Automatically generates SQL code based on user input.
- **Context Awareness**: Utilizes context from previous commands to enhance SQL generation.
- **Database Management**: Supports creating, altering, and managing database tables and objects.
- **MySQL Execution**: Integrates with MySQL to execute the generated SQL queries.

### Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/vamsi-karnam/dbchat.git
   ```
2. **Install Dependencies**:
   ```bash
   pip install openai mysql-connector-python
   ```
3. **Set Up MySQL**:
   - Ensure MySQL is installed and running locally.
   - If using a network-based MySQL server, set up appropriate network forwarding and connections so that the PC running the code can access the MySQL server through the SQL terminal.
   - Update the MySQL connection details in the script.

4. **Create an OpenAI API Key**:
   - Sign up for an OpenAI account at OpenAI.
   - Add credits to your account.
   - Generate an API key from the OpenAI dashboard.
   - Add your API key to the code.

5. **Convert the Jupyter Notebook to a Python Script**:
   - Install JupyterLab or use JupyterLab online.
   - Download the Jupyter Notebook (.ipynb file).
   - Export the notebook as a Python script using JupyterLab.

6. **Run the Script**:
   ```bash
   python script-name.py
   ```

### Usage

- Provide SQL instructions to the model.
- The model generates and executes the corresponding SQL queries.
- Manage your database efficiently with minimal manual SQL coding.

### Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
