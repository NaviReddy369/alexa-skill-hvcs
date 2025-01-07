# Alexa Skill: Hello HVCS

This repository contains the Alexa Skill: **Hello HVCS**, designed for Hudson Valley Concierge Services. This skill provides customers with essential information about the company, including contact details, operating hours, location, and services offered. It enables seamless interaction via Alexa devices to improve accessibility and convenience for customers.

## Key Features
- **Contact Information**: Provides the phone number, email address, and website details.
- **Operating Hours**: Shares the business hours of the company.
- **Location Information**: Provides the address of Hudson Valley Concierge Services.
- **Services Overview**: Highlights the core services such as transportation, medical support, deliveries, and errands.

## Project Structure
The repository is organized as follows:
├── assets/ # Contains skill icons and media assets ├── interactionModels/ # JSON files defining intents, slots, and utterances ├── lambda/ # Python code for Alexa skill backend (AWS Lambda) │ ├── lambda_function.py # Main Lambda handler │ ├── utils.py # Utility functions for skill │ ├── requirements.txt # Dependencies for the Lambda function ├── skill.json # Alexa skill configuration file └── README.md # Project documentation


## How to Use
1. **Clone the Repository**:
git clone https://github.com/YourGitHubUsername/alexa-skill-hvcs.git cd alexa-skill-hvcs


2. **Deploy Lambda Code**:
- Update `lambda_function.py` in your AWS Lambda instance.
- Ensure the required Python libraries are installed using `requirements.txt`.

3. **Configure Alexa Skill**:
- Import `interactionModel.json` into the Alexa Developer Console under the "Interaction Model" tab.
- Upload `skill.json` for skill configuration.

4. **Test the Skill**:
- Use the Alexa Simulator or an Alexa-enabled device to test.
- Example commands:
  - "Alexa, open Hello HVCS."
  - "Alexa, ask Hello HVCS for contact information."
  - "Alexa, ask Hello HVCS about operating hours."

## Technology Used
- **Python**: For Lambda backend.
- **AWS Lambda**: Backend serverless function.
- **Alexa Skills Kit (ASK)**: For interaction model creation.
- **GitHub**: For version control and collaboration.

## Contribution
Feel free to submit issues or feature requests. Contributions are welcome!


