# SHALA (Supportive Help Agent and Lifeline Assistant)

## Description

SHALA is a Python-based chatbot project powered by the Gemma 3 AI Agent, designed to assist individuals experiencing depression by providing ongoing emotional check-ins and real-time crisis intervention.

## Table of Contents

- [Introduction](#introduction)
- [Ethical Use Policy](#ethical-use-policy)
- [Testing Protocol](#testing-protocol)
- [Installation](#installation)
- [Fine-Tuning](#fine-tuning)
- [Steps to Run SHALA](#steps-to-run-shala)
- [Datasets](#datasets)
- [Contributions](#contributions)
- [Team](#team)
- [License](#license)

## Introduction

The system is designed to actively check-in with users, offering a supportive dialogue environment. More importantly, SHALA continuously monitors for self-harm indicators (specific words or phrases) in chat messages that may suggest the user is in a crisis. Upon detecting such language, SHALA will immediately and automatically connect the user to a HELP Provider or Suicide Prevention Hotline, ensuring timely intervention when it's most needed.

Given a user chat message T (i.e., text input), our goal is to train a model that classifies the suicide risk level. If T is flagged as suicidal (1), SHALA will alert Gemma 3 to initiate a WhatsApp call that connects the user to a Help Provider or Suicide Prevention Hotline.

⚠️ **Because these phone lines are imperative, a dummy number is used in place of any real emergency service numbers for both testing and running.**

## ⚖️ Ethical Use Policy
Mental health support systems must be developed and used with sensitivity, responsibility, and respect for the lives they aim to protect.

SHALA is not a replacement for certified therapists or mental health professionals.

This project is intended for research, prototype development, and educational purposes only.

Any misuse of this software that results in the abuse of real emergency lines is strictly prohibited.

Developers and users must ensure that real hotline numbers are never used in any version of this program outside of an officially approved deployment with proper oversight and consent.

By using or contributing to SHALA, you agree to uphold the highest ethical standards and understand the potential real-world consequences of misuse.

## Testing Protocol
To ensure safe testing and simulation, SHALA uses a **dummy phone number** to simulate the connection to a crisis support hotline.

During Development:
All outgoing call features should be pointed to a **non-functioning test number (e.g., +0000000000)**.

**No real user** should be prompted to call or message any actual suicide prevention or emergency support line.

Logs and alerts should be contained in a local or sandbox environment without external message delivery.

Safety Guidelines:
**Never** include or hardcode a real support line into the codebase.

**Do not** simulate real user crises unless ethically reviewed and permitted.

**Make sure** testing is conducted in a controlled and non-public environment.

## Installation

## Fine-Tuning

## Steps to Run SHALA

## Datasets

## Contributions

## Team

## License