# Google Translate CLI

Google Translate CLI is a command-line interface application written in Golang that allows users to translate text between different languages using the Google Translate API.

## Features

- Translate text between various languages.
- Specify the source language, target language, and text to be translated using command-line options.
- Concurrent API calls for efficient translation requests, leveraging Golang's goroutines and wait groups.
- User-friendly interface with default values for ease of use.

## Prerequisites

Before running the application, make sure you have the following prerequisites:

- Golang installed on your machine.
- API key for Google Translate API. (Follow Google Translate API documentation to obtain an API key)

## Installation

1. Clone the repository:
git clone https://github.com/yourusername/google-translate.git

2. Change to the project directory:
cd google-translate

3. Install the dependencies:
go mod download

4. Set the Google Translate API key as an environment variable:
export GOOGLE_TRANSLATE_API_KEY=your_api_key

## Usage

To translate text using the Google Translate CLI, follow these steps:

1. Open a terminal and navigate to the project directory.

2. Run the application with the desired options:

go run main.go -s <source_language> -t <target_language> -st "<text_to_translate>"

Replace `<source_language>` with the desired source language code (default: en), `<target_language>` with the desired target language code (default: fr), and `<text_to_translate>` with the text you want to translate.

3. The translated text will be displayed in the terminal.

## Acknowledgements

- [github.com/Jeffail/gabs](https://github.com/Jeffail/gabs) - Package used for parsing JSON responses from the Google Translate API.

## Contact

For any inquiries or questions, feel free to contact me at yadavbhavy25@gmail.com.
