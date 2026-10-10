# Marissa – AI Voice Assistant for Home Credit

## Project Overview

Marissa is an AI-powered voice assistant developed using Retell AI to handle preliminary customer eligibility checks for Home Credit Loan Against Property (LAP). The assistant interacts with customers through natural conversations, collects relevant information, evaluates preliminary eligibility based on predefined business rules, and guides customers toward the appropriate next steps.

The project demonstrates the design, configuration, publishing, and testing of an AI voice agent for a financial services use case.

## Objectives

- Automate preliminary Loan Against Property eligibility conversations.
- Provide a professional and friendly customer experience.
- Collect relevant customer and property information.
- Identify preliminary qualification and disqualification scenarios.
- Refer customers to a loan specialist when required.
- Maintain structured call summaries and post-call information.

## Features

- AI Voice Interaction: Conversational customer interaction using Retell AI.
- Customer Greeting: Introduces Marissa and explains the purpose of the call.
- Eligibility Screening: Collects information required for preliminary eligibility checks.
- Property Assessment: Handles residential, commercial, and industrial property scenarios.
- Qualification Handling: Provides appropriate responses based on predefined eligibility criteria.
- Specialist Referral: Directs relevant customer requests to a loan specialist.
- Call Analysis: Supports post-call summaries, qualification status, customer sentiment, and other configured extraction fields.
- Testing: Enables testing of multiple customer scenarios to validate conversation logic.

## Technology Stack

- Retell AI
- Large Language Model (LLM)
- AI Voice Agent
- Natural Language Processing (NLP)
- Prompt Engineering
- Conversational AI

## Conversation Workflow

1. Marissa greets the customer and introduces herself.
2. The assistant explains the purpose of the call.
3. The assistant asks relevant questions about the customer's property, loan requirements, employment, and income.
4. The responses are evaluated against the configured preliminary eligibility rules.
5. The assistant communicates the appropriate next step, such as preliminary qualification, disqualification, or referral to a specialist.
6. The conversation ends professionally.
7. Configured post-call extraction fields capture relevant information from the interaction.

## Testing Scenarios

The following scenarios are used to test the agent's conversation logic:

1. Successful Preliminary Qualification: A customer provides information that meets the configured preliminary criteria.
2. Cash-Income Disqualification: A self-employed customer reports receiving income in cash, triggering the configured disqualification response.
3. Specialist Referral: A customer requests assistance that requires a loan specialist.
4. Property Type Assessment: The assistant handles residential, commercial, and industrial property responses.
5. Conversation Completion: The assistant provides a suitable closing message and ends the call when appropriate.

## Expected Outcomes

- A professional and consistent customer conversation.
- Accurate collection of the information requested by the configured prompt.
- Appropriate handling of qualification and disqualification scenarios.
- Correct routing of specialist-related requests.
- Structured call summaries and test evidence.

## Deployment

The AI voice agent is configured and published using Retell AI. The public Retell link can be added below if it is intended for public sharing.

Published Agent: https://agent.retellai.com/orb/agent_649b9d8422801d9c60252d965e?token=2c67ea0573d4a6eedb3faea90a667a2d

## Project Limitations

- Preliminary eligibility decisions depend on the business rules configured in the agent.
- The assistant does not make final loan approval decisions.
- Final eligibility, interest rates, loan terms, and approval remain subject to review by the authorized lending team.
- Call recording, transcript availability, and post-call extraction depend on the platform configuration.

## Privacy and Security

- Use simulated customer information when demonstrating or testing the agent.
- Do not publish real customer personal information, financial details, phone numbers, private recordings, or API credentials.
- Share call recordings and transcripts only when authorized.

## Conclusion

Marissa demonstrates how conversational AI and voice automation can support preliminary customer screening in financial services. By combining structured prompting, voice interaction, predefined eligibility rules, and post-call analysis, the project provides a foundation for an AI-assisted Loan Against Property customer engagement workflow.

