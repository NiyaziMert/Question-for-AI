

#  Question for AI (QfAI)

Question for AI (QfAI) is a user-friendly AI application built using Python and PyQt5. This application generates responses to text-based queries on videos and provides voice responses. Additionally, it offers features such as character creation and management, including personalized voices and media handling.
This app was created by Arda Demirkıran and Niyazi Mert Işıksal.
![WhatsApp Image 2024-11-28 at 20 30 14](https://github.com/user-attachments/assets/fff8890d-5236-42ed-83d3-7d79c312b8c7)

#  Features

Character Management:
Add user-defined characters.
Link photos and voice files to characters.
Edit or delete characters.
API Integration:
Integration with the Google Gemini API.
Users can input project-specific API keys to receive AI-generated answers to their queries.
TTS (Text-to-Speech):
Responses can be voiced with user-defined character-specific voices.
Video Management:
Play videos and generate custom outputs with character lip movements.
Requirements

#  This project requires the following software and libraries:

Once you install the environment_uc.yaml and environment_stant_son.yaml packages via Conda, no additional installation is required.
All dependencies are included in the .yaml sources, and no extra installation is needed.
Installation

#Install Dependencies:
Run the following command to install the necessary libraries:
conda env create -f environment_uc.yaml
conda env create -f environment-stant_son.yaml
Ensure that you run QfAI.py in the stant_son environment.
The uc environment is exclusively for running .bat files. Simply installing it is sufficient, and no further action is required.
API Key Configuration:
Configure your API keys within the application.
Character Database:
The application stores character information in the characters.json file. If the file is missing, it will be created automatically upon the first run.
Usage

#    Run the Application
python QfAI.py
Add a Character:
Use the Add Character button in the right menu to create a new character.
Run a Query:
Select a character, type your query in the text box at the bottom, and click Run.
Play a Video:
The application clones the uploaded audio file and synchronizes it with the Gemini-generated response to produce a video with cloned voiceovers and lip synchronization. The video is then automatically played.
File Structure

#QfAI.py: Main application file.
config.json: Configuration file containing API settings.
characters.json: Stores character information.
outputs/: Directory where the application saves generated output files.
License

This project is licensed under the MIT License. For more details, see the LICENSE file.

#    Contributing

To contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-name).
Make your changes and commit them (git commit -m 'Add new feature').
Push your branch (git push origin feature-name).
Open a Pull Request.
Contact
If you have any questions or suggestions, feel free to reach out to me.
