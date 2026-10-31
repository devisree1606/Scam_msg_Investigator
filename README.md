# Scam Message Investigator

## Project Overview

Scam Message Investigator is an AI-powered web application developed using Python, Streamlit and Ollama. It helps users identify potentially suspicious messages by analyzing their content using a locally running Large Language Model (LLM).

The application examines messages for common scam indicators and provides a risk assessment along with safety recommendations.

## Live Demo

Try the application here:

https://scammsginvestigator-jbysbutguc8hmbiplb8eyg.streamlit.app/

## Features

* Detects potentially suspicious messages.
* Identifies common scam warning signs.
* Classifies messages based on risk levels.
* Provides a short analysis summary.
* Highlights suspicious phrases with explanations.
* Suggests safety precautions.
* Displays limitations of the AI analysis.
* Uses a locally running Ollama model.

## Technologies Used

* Python
* Streamlit
* Ollama
* Gemma 3 (1B)
* Requests
* JSON

## Model Information

Model Name: gemma3:1b

Ollama is used to run the language model locally and generate message analysis reports.

## Project Structure

```text
Scam_Message_Investigator/
│
├── app.py
├── requirements.txt
└── README.md
```

## How to Use

1. Open the Scam Message Investigator application.
2. Enter or paste a suspicious message in the input box.
3. Click the Analyze Message button.
4. Wait for the AI model to process the message.
5. View the generated analysis report.
6. Check the risk level, warning signs and recommended safety actions.

## Risk Classification

| Risk Level     | Description                                           |
| -------------- | ----------------------------------------------------- |
| Low Concern    | No obvious suspicious indicators identified.          |
| Medium Concern | Some potentially suspicious characteristics detected. |
| High Concern   | Multiple serious scam indicators identified.          |

## Expected Output

The application generates an investigation report containing:

* Risk Level
* Message Category
* Analysis Summary
* Identified Warning Signs
* Safety Recommendations
* Analysis Limitations

## Limitations

* AI-generated results may not always be accurate.
* Message content alone cannot confirm whether a message is genuine.
* The application does not independently verify website links or sender identities.
* Ollama must be installed and running for local model analysis.

## Future Enhancements

* Add suspicious URL detection.
* Support multiple regional languages.
* Add SMS and email analysis.
* Improve scam detection accuracy.
* Include downloadable investigation reports.

## Conclusion

Scam Message Investigator provides an AI-based approach to examining suspicious messages. It helps users understand potential scam indicators and make safer digital decisions.

**Note:** This application provides AI-generated assessments and should not be considered a guarantee of message authenticity.
