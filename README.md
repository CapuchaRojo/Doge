# Vision-Driven-Workflow-Automator
# Vision-Driven Workflow Automator (VDWA)

## Project Overview
Vision-Driven Workflow Automator is designed to transform human behavioral knowledge into executable automation by creating an abstraction layer between human-described workflows and their technical implementation.

## Setup and Development

### 1. Grok API Integration
- **Status:** API keys obtained
- **Details:** 
  - We've secured API keys for Grok, which will be used for advanced AI processing of visual inputs to generate workflow steps.
  - *Note:* API keys are stored securely and not committed to the repository.

### 2. GitHub Repository Setup
- **Status:** Repository created and linked
- **Details:**
  - Repository: [CapuchaRojo/Vision-Driven-Workflow-Automator](https://github.com/CapuchaRojo/Vision-Driven-Workflow-Automator)
  - Branches:
    - `main`: Main branch for stable releases.
    - *Note:* Additional branches for feature development or hotfixes can be created as needed.

### 3. Streamlit Deployment
- **Status:** Streamlit app is up and running
- **Details:**
  - **Local Development:**
    - Installed Streamlit and set up a basic app (`app.py`).
    - The app currently offers:
      - Navigation between showing instructions and uploading workflows.
  - **Deployment:**
    - Deployed on Streamlit Community Cloud for public access.
    - Deployment URL: [Insert Deployment URL Here]
  - **Environment:**
    - Python virtual environment created and activated.
    - Dependencies managed via `requirements.txt`.

### Other Achievements
- **Team Coordination:** 
  - Established communication channels with team members across different time zones.
- **Security:** 
  - Utilized SSH keys for secure Git operations after resolving initial setup issues.

## How to Run the Application

### Local Setup
1. **Clone the repository:**
   ```bash
   git clone git@github.com:CapuchaRojo/Vision-Driven-Workflow-Automator.git

2. Navigate to the project directory:
   ```bash
   cd Vision-Driven-Workflow-Automator

3. Set up a virtual environment:
   ```bash
   python -m venv venv.\venv\Scripts\Activate.ps1  # On Windows

4. Install dependancies:
   ```bash
    pip install -r requirements.txt

5. Run the Streamlit app:
   ```bash
   streamlit run app.py


Future Work
Blockchain Integration: 
Conceptualized how blockchain could ensure data integrity and transparency for workflow steps.
Drafted a basic Solidity smart contract for proof-of-concept.
Full Workflow Implementation: 
Plan to integrate vision API with workflow generation, leveraging Grok capabilities.
User Interface Enhancements: 
Improve UI/UX based on feedback from the deployed version.

Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

License
[Undecided]

Authors
Adam - Initial work - [CapuchaRojo]

Acknowledgments
Thanks to the Grok team for API access.
Thanks to the Streamlit community for hosting solutions.


### **Additional Notes:**

- **Version Control:** Make sure all these steps and documentation are committed to your GitHub repository.
- **Privacy:** Avoid including sensitive information like actual API keys in your public documentation. Mention that they are managed securely.
- **Links:** Use Markdown to link to external resources or internal sections of your documentation for better navigation.
- **Images:** If you have screenshots or diagrams, include them with Markdown image syntax for visual documentation.

This documentation format not only outlines what you've done but also provides a clear path for others to understand, replicate, or contribute to your project. Committing this to your GitHub repo will showcase your progress and planning to judges or team members.
      
