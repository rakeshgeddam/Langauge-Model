# Mental Health Chatbot Language Model

## Importance of Mental Healthcare

Mental health support is essential, especially for individuals with ADHD. In the United States, around 3 million adults are diagnosed with ADHD, facing challenges with focus, organization, and emotional regulation. Research shows that targeted digital assistance can improve daily structure, reduce stress, and increase overall well-being. Tools like personal digital assistants have been shown to help people with ADHD improve focus, task completion, and emotional stability.

This project focuses on a language model designed for a mental healthcare chatbot that offers reminders, check-ins, and context-aware support to improve the day-to-day experiences of users, particularly those managing ADHD.

---

## Repository Structure

```
README.md           # Documentation and setup instructions
loss-plot.pdf       # Training loss visualization
pretraining.ipynb   # Notebook for model pretraining
supplementary.py    # Supporting Python functions and scripts
```

---

## Local Setup Instructions

### 1. Download and install Miniforge

Download Miniforge from the [official repository](https://github.com/conda-forge/miniforge).

Depending on your operating system, download the `.sh` file (macOS, Linux) or `.exe` file (Windows).

For macOS/Linux:

```bash
sh ~/Downloads/Miniforge3-MacOSX-arm64.sh
```

Replace `Downloads/` with the directory where the installer is located.

To improve Conda’s performance, run:

```bash
conda config --set solver libmamba
```

---

### 2. Create a new virtual environment

```bash
conda create -n mhchatbot python=3.10
conda activate mhchatbot
```

Using Python 3.10 ensures compatibility with most ML libraries.

---

### 3. Install required Python libraries

```bash
pip install -r requirements.txt
```

---

## Running the Model

You can run the model training and chatbot service from the Jupyter notebook or Python scripts.

Example to run a supplementary script:

```bash
python supplementary.py
```

<img width="2000" height="1200" alt="image" src="https://github.com/user-attachments/assets/8b53be0b-4bb7-41fb-998b-ce1bc8c5969d" />


---

## Privacy and Ethics

* User conversations remain local unless explicitly configured for cloud storage.
* The model includes basic safety checks to avoid harmful responses.
* Designed as a supportive tool, not a replacement for professional care.

---

Do you want me to also **add a “Training and Evaluation” section** explaining how `loss-plot.pdf` and `the-verdict.txt` fit into the model workflow? That would make the README more useful for others viewing your repo.
