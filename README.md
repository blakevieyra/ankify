##Anki Deck Generator from PowerPoint
The **Anki Deck Generator** is a Python-based GUI application that helps users convert PowerPoint presentations into Anki flashcards. This tool automates the process of creating flashcards by extracting content from slides and using OpenAI's GPT-3.5-turbo model to generate meaningful questions and answers.
Features
- PowerPoint Integration: Load `.pptx` files to extract slide content.
- AI-Powered Flashcards: Generate high-quality questions and answers using OpenAI's GPT.
- Customizable Deck Title: Automatically derive deck titles from the presentation or use a default.
- Progress Tracking: Visual progress bar and time estimation for deck generation.
- Save Decks Locally: Save generated Anki decks as `.apkg` files.
---
Requirements
Python Libraries
Install the following Python libraries:
- `tkinter` (standard library for GUI development)
- `transformers`
- `genanki`
- `python-pptx`
- `openai`
Install the required dependencies using `pip`:
pip install transformers genanki python-pptx openai
OpenAI API Key
To use the AI flashcard generation feature, you need an OpenAI API key. Replace `'YOUR_API_KEY'` in the script with your OpenAI API key:
openai.api_key = 'YOUR_API_KEY'
How to Use
1. Run the Script: Launch the script using Python:
```bash
python anki_deck_generator.py
```
1. Select a PowerPoint File: Click the "Drop PowerPoint File" button to choose a `.pptx` file.
1. Monitor Progress: A progress bar will indicate the deck generation process, and a time estimate will be displayed.
1. Save the Deck: Once the deck is generated, choose a location to save the `.apkg` file.
1. Import to Anki: Open Anki and import the saved `.apkg` file to access your new flashcards.
---
Screenshot
*(Add a screenshot of the application window here.)*
---
Known Limitations
- Slide Content: Relies on clear and structured text in slides for effective flashcard generation.
- AI Accuracy: The quality of generated flashcards depends on the clarity and relevance of the slide content.
- API Dependency: Requires an active OpenAI API key.
---
Troubleshooting
- No File Selected: Ensure a valid `.pptx` file is selected.
- Error Saving Deck: Verify you have write permissions to the chosen save location.
- Missing Dependencies: Ensure all required libraries are installed using the provided `pip` command.
---
License
This project is open-source and free to use. Modify or distribute as needed.
