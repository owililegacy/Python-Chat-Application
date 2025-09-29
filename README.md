PYTHON-CHAT-APPLICATION

Connects Everyone, Empowers Conversations, Unites Seamlessly
last-commit repo-top-language repo-language-count

Built with the tools and technologies:
Python

Table of Contents

    Overview
    Getting Started
        Prerequisites
        Installation
        Usage
        Testing

Overview

Python-Chat-Application is a scalable, distributed chat system designed for real-time messaging across multiple nodes, ensuring high availability and consistency. The core features include:

    🧩 Multi-node synchronization: Maintains consistent chat history across peer servers using gossip protocols, supporting scalable architectures.
    🚀 Fault-tolerant clients: Clients automatically reconnect to multiple servers, providing seamless communication despite network disruptions.
    🔧 Shared utilities: Provides reliable network communication helpers for message serialization, deserialization, and socket interactions.
    🌐 Distributed architecture: Facilitates scalable and resilient chat infrastructure suitable for large-scale deployments.
    ⚙️ Real-time messaging: Supports instant message broadcasting and system notifications across all nodes.

Getting Started
Prerequisites

This project requires the following dependencies:

    Programming Language: Python
    Package Manager: Conda

Installation

Build Python-Chat-Application from the source and install dependencies:

    Clone the repository:

    ❯ git clone https://github.com/owililegacy/Python-Chat-Application

    Navigate to the project directory:

    ❯ cd Python-Chat-Application

    Install the dependencies:

Using conda:

❯ conda env create -f conda.yml

Usage

Run the project with:

Using conda:

conda activate {venv}
python {entrypoint}

Testing

Python-chat-application uses the {test_framework} test framework. Run the test suite with:

Using conda:

conda activate {venv}
pytest
