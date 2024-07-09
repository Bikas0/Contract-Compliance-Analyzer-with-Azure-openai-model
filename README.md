<h1>🧠Compliance Contract Analyzer🧠</h1>
This project is a Compliance Contract Analyzer that uses Azure OpenAI to extract key terms and conditions from contract texts and verify task descriptions for compliance with these conditions. It provides a user interface for uploading documents and task tables, analyzing them, and displaying the results.
<h2>Deployed in 🤗Huggingface</h2>
<a href="https://huggingface.co/spaces/Bikas0/Contract-Conditions-Extraction-and-Verification" target="_blank">🌐Contract Conditions Extraction & Verification</a>
<br>
<h2>Features</h2>
<ul>
  <li>Conditions Extraction: Extracts key terms and conditions from contract texts and structures them in JSON format.</li>
  <li>Compliance Verification: Analyzes task descriptions for compliance with the extracted contract conditions and specifies reasons for any violations.</li>
  <li>User Interface: Allows users to upload contract documents and task tables, and displays the analysis results.</li>
  <li>JSON Output: Generates a JSON file with extracted and structured contract conditions.</li>
</ul>
<h2>Technical Requirements</h2>
<ul>
  <li>Azure API</li>
  <li>Streamlit</li>
  <li>Other LLMOps tools</li>
</ul>

<h2>Installation</h2>
<h3>Prerequisites</h3>
<ul>
  <li>Python 3.10 or higher</li>
  <li>Pip (Python package installer)</li>
</ul>

<h3>Dependencies</h3>
Install the required dependencies using pip:
<br>

```bash
pip install -r requirements.txt
```

<h3>Requirements File</h3>
The requirements.txt includes the following packages:
<br>

```bash
openai==1.1.2
python-dotenv
flask
python-docx
pandas
streamlit
openpyxl
retrying
```

<h3>Usage</h3>

Clone the Repository:
<br>

```bash
git clone https://github.com/Bikas0/Contract-Compliance-Analyzer-with-Azure-openai-model.git
cd Contract-Compliance-Analyzer-with-Azure-openai-model
```

Set Up Environment Variables:

<ul>
  <li>Create a .env file in the root directory of the project.</li>
  <li>Add your Azure OpenAI API key to the .env file:</li>
</ul>
<br>

```bash
 AZURE_OPENAI_API_KEY=your_azure_openai_api_key
```
Run the Application:
<ul>
  <li>Streamlit:</li>
</ul>

```bash
streamlit run app.py
```


<h2>Functionality</h2>
<h3>Conditions Extraction</h3>
<ul>
  <li>The application extracts key terms and conditions from the provided contract text.</li>
  <li>The extracted terms are structured in a JSON format reflecting different sections and subsections of the contract.</li>
</ul>

<h2>Task Descriptions Analysis</h2>
<ul>
  <li>Users can upload a CSV file containing task descriptions and cost estimates.</li>
  <li>The system analyzes each task description for compliance with the contract conditions.</li>
  <li>If a task violates one or more conditions, the system specifies the reason for the violation.</li>
</ul>

<h2>User Interface</h2>
<ul>
  <li>The interface allows users to upload contract documents and task tables.</li>
  <li>Analysis results are displayed on the interface, including any detected violations and their reasons.</li>
</ul>


<h2>Expected Outcomes</h2>
<ul>
  <li>JSON Output: A JSON file containing extracted and structured contract conditions.</li>
  <li>User Interface: An interface for uploading documents, analyzing tasks, and displaying verification results.</li>
  <li>Documentation: Comprehensive documentation on the system operation and each component of the task.</li>
</ul>

<h2>Contributing</h2>
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.


<h2>License</h2>

This project is licensed under the MIT License. See the LICENSE file for details.






