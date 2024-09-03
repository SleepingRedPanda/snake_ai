# # Snake AI

This project implements an AI agent to play the classic Snake game using reinforcement learning techniques. The AI is built using PyTorch and leverages deep Q-learning to train the agent.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/snake_ai.git
   cd snake_ai
    ```
2. **Create a virtual environment:**

   ```sh
   python -m venv env
    ```

3. **Activate the virtual environment:**
On Windows:

   ```sh
   .\env\Scripts\activate
   ```
On macOS/Linux:

   ```sh
   source env/bin/activate
   ```

4. **Install dependencies:**

   ```sh
   pip install -r requirements.txt
   ```

## Usage

**Run the game:**

To run the game, run the following command:

    ```sh
    python agent.py
    ```

## Project Structure

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
|
├── model              <- Trained and serialized models, model predictions, or model summaries
│
├── models             <- Code for models
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         snake_ai and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
├── helper.py          <- Code to create visualizations
│
├── agent.py           <- AI Agent
│
├── snake_game.py      <- UI for the snake game
```

## Dependencies

The project requires the following Python packages:

```plaintext
matplotlib==3.9.2
matplotlib-inline==0.1.7
numpy==1.26.4
pygame==2.6.0
PyQt6==6.7.1
PyQt6-Qt6==6.7.2
PyQt6_sip==13.8.0
torch==2.2.2
ipython==8.14.0
```

These dependencies are listed in the **requirements.txt** file. You can install them using the following command:
```sh
pip install -r requirements.txt
```
--------

