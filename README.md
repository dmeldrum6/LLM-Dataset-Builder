# LLMDatasetBuilder
LLM-Powered Dataset Creation Tool
v2!
![image](https://github.com/user-attachments/assets/c6b8cf0f-8efd-46e8-9fae-6b6212a1ca2c)
UI / UX Rework with Bootstrap to adapt to different screens better.
- Dark/Light Mode toggle
- Better Input validation
- Better error messaging and visual feedback
- Ability to save/load different configs
- API Connection test
- Visual tracking for batch processing
- Contextual Help added


![image](https://github.com/user-attachments/assets/0a6b33dd-6b41-4556-888b-6fedb02ab2d7)

I wanted to use LLMs to create some training data. I built this tool to streamline that process and thought it might be useful to other folks too. Single HTML file with embedded JavaScript will query an Open AI API compatible LLM and create question answer pairs on a topic of your choice. Fork it and make it better! :)

Key Features
- API Connection
  - Configurable endpoint URL for compatibility with different OpenAI API-compatible services
  - API key input
  - Model selection
- Dataset Configuration
  - Topic/domain specification
  - Output format selection (JSON/XML)
  - Customizable prompt template
  - Batch size and total item control
- Tag Management System
  - A dedicated section for adding, displaying, and removing topic tags
  - Pre-populated with three sample tags (Beginner, Intermediate, Advanced) to get started
  - Simple interface to add new tags by typing and pressing Enter or clicking the "+" button
- Batch Processing
  - Built-in batching to manage token usage
  - Progress tracking with visual feedback
  - Configurable delay between requests to avoid rate limiting
  - Stop/resume functionality
- Output Handling
  - Real-time display of generated data
  - Toggle between JSON and XML views
  - Download functionality for the complete dataset
- Advanced Options
  - Temperature control for output variety
  - Max tokens limitation
  - System prompt customization
 

The .json file is an example produced with this tool.
