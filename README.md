"# Spellcheck Identifiers Project"

\#  Spellcheck Identifiers



A tool to detect and correct spelling mistakes in source code identifiers using an English dictionary.



\---



\##  Overview

This project aims to improve code quality by identifying misspelled identifiers (such as variable names, method names, and class names) and suggesting accurate corrections.



It is designed to integrate with tools like \*\*Checkstyle\*\* to provide automated linting and feedback during development.



\---



\##  Features

\-  Detect spelling errors in identifiers

\-  Suggest possible corrections

\-  Integrates with Checkstyle

\-  Uses dictionary-based validation (Hunspell)

\-  Reduces false positives using heuristics



\---



\##  Tech Stack

\- \*\*Java\*\*

\- \*\*Hunspell\*\*

\- \*\*Regex\*\*

\- \*\*Checkstyle\*\*



\---



\##  Project Structure

spellcheck-identifiers/

│── src/                # Source code

│── resources/          # Dictionaries \& configs

│── README.md           # Project documentation

│── pom.xml             # Maven configuration



\---



\##  How It Works

1\. Extract identifiers from source code

2\. Split identifiers using naming conventions (camelCase, snake\_case)

3\. Validate each word using an English dictionary (Hunspell)

4\. Apply heuristics to reduce false positives

5\. Suggest corrections for misspelled words



\---



\##  How to Run



\### 1. Clone the repository

git clone https://github.com/your-username/spellcheck-identifiers.git

cd spellcheck-identifiers



\### 2. Build the project

mvn clean install



\### 3. Run the tool

java -jar target/spellcheck.jar



\---



\##  Example



\*\*Input:\*\*

int usrNmae = 10;



\*\*Output:\*\*

Possible spelling mistake: usrNmae → userName



\---



\##  Future Improvements

\- Add support for multiple languages

\- Improve suggestion accuracy

\- Integrate with IDEs (VS Code, IntelliJ)

\- Optimize performance for large codebases



\---



\##  Author

Shivansh Chauhan

