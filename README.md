<h1 align="center" id="title">Calculator</h1>

<p align="center"><img src="https://socialify.git.ci/BrigidAn/Calculator/image?font=Source+Code+Pro&amp;language=1&amp;name=1&amp;pattern=Transparent&amp;stargazers=1&amp;theme=Light" alt="project-image"></p>

<p id="description">This is a simple calculator application that was created using Android Studio Kotlin. It’s one of the basic projects I built and it wasn’t too difficult at all—it works perfectly! This application is ideal for students who want to start with something straightforward and engaging.</p>

<p align="center"><img src="https://img.shields.io/badge/Android_Studio_-Kotlin" alt="shields"><img src="https://img.shields.io/badge/Kotlin_%20--%20AndroidStudio" alt="shields"></p>

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Simplicity

<h2>🛠️ Installation Steps:</h2>

<p>1. GitHub</p>

```
# Check for git installation if ! command -v git &> /dev/null then     echo "Git is not installed. Please install Git and rerun this script."     exit 1 fi  # Variables - replace these with your desired GitHub username and repository GITHUB_USERNAME="USERNAME" REPOSITORY_NAME="REPOSITORY"  # Clone the repository echo "Cloning the repository https://github.com/$GITHUB_USERNAME/$REPOSITORY_NAME.git ..." git clone https://github.com/$GITHUB_USERNAME/$REPOSITORY_NAME.git  # Check if clone was successful if [ $? -ne 0 ]; then     echo "Failed to clone repository. Please check the username and repository name."     exit 1 fi  # Navigate into the project directory cd $REPOSITORY_NAME || { echo "Failed to enter directory $REPOSITORY_NAME"; exit 1; }  # Detect the package manager and install dependencies  if [ -f package.json ]; then     # Node.js project detected     if command -v npm &> /dev/null; then         echo "Installing npm dependencies..."         npm install     else         echo "npm is not installed. Please install Node.js and npm to continue."         exit 1     fi elif [ -f requirements.txt ]; then     # Python project detected     if command -v pip &> /dev/null; then         echo "Installing Python dependencies..."         pip install -r requirements.txt     else         echo "pip is not installed. Please install Python and pip to continue."         exit 1     fi else     echo "No recognized dependency file found (package.json or requirements.txt)."     echo "Please follow the project's README for installation instructions." fi  echo "Installation complete." echo "Please refer to the project's README for instructions on running the project."
```

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Android Studio
*   Kotlin
