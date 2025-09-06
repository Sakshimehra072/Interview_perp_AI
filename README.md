An AI-Powered Platformed for preparing for interview

# 1. VAPI

A developer-focused voice AI platform for building scalable and secure voice agents.

## Voice AI Platform Overview

| Section             | Details                                                                                                                                                                                                                                              |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **What is it?**      | A voice AI platform to build, test, and deploy AI voice agents                                                                                                                                                                                       |
| **Key Features**     | - Modular: choose STT, LLM, TTS (OpenAI, Anthropic, ElevenLabs, etc.) <br> - APIs + SDKs (TypeScript, Python, React, cURL) <br> - Visual workflow builder (no-code flows) <br> - Tool calling & 40+ integrations (Twilio, Salesforce, Zendesk, etc.) |
| **Performance & Scale** | - Ultra-low latency (<500ms) <br> - Can handle millions of calls/minute <br> - Supports 100+ languages + global telephony                                                                                                                            |
| **Security**         | - SOC 2, HIPAA, PCI compliant <br> - AI guardrails to avoid hallucinations <br> - A/B testing for optimization                                                                                                                                       |
| **Use Cases**        | - Inbound/outbound customer calls <br> - Appointment booking & healthcare follow-ups <br> - Sales/BPO multilingual support <br> - Legal firm call screening & lead qualification                                                                     |
| **Pros**             | Developer-friendly (modular + APIs) <br>  Highly scalable + multilingual <br> Strong security & compliance                                                                                                                                           |
| **Cons (from users)**| Lag/robotic voice after ~20s <br>  Struggles with very high call volumes <br>  Memory tools sometimes unreliable                                                                                                                                     |


Login to VAPI using account : 07

1.	Create Assistant (Interview Prepration Platform)
2.	More… Go to Workflows.
3.	Create Workflow (interview_prep)


# 2. WebStorm (IDE)
WebStorm is an Integrated Development Environment (IDE) by JetBrains, tailored for JavaScript, TypeScript, and related technologies. It provides powerful tools out-of-the-box for modern web development
1.	Open Folder in webstorm
2.	In Terminal type: npx create-next-app@latest ./

PS D:\interview_prep_platform> npx create-next-app@latest ./ <br>
√ Would you like to use TypeScript? ... No / `Yes`   <br>
√ Which linter would you like to use? » ESLint       <br>
√ Would you like to use Tailwind CSS? ... No / `Yes`  <br>
√ Would you like your code inside a `src/` directory? ... `No` / Yes       <br>
√ Would you like to use App Router? (recommended) ... No / `Yes`           <br>
√ Would you like to use Turbopack? (recommended) ... No / `Yes`             <br>
? Would you like to customize the import alias (`@/*` by default)? » `No` / Yes      <br>



### Authentication

Create a directory in app named as "(auth)" , inside() to turn it to route group means to preventing mapping of folder to URL paths