Here is an updated `README.md` formatted specifically for your repo based on the `uv` setup workflow:

```markdown
# CPSC 330: Applied Machine Learning (UBC)

This repository contains homework assignments, local Jupyter notebook environments, and code for **CPSC 330: Applied Machine Learning** at the University of British Columbia (UBC).

---

## 🛠️ Local Setup & Environment

Assignments can be completed either directly within the PrairieLearn workspace or locally on your machine for faster compute performance.

### Prerequisites

* [Python](https://www.python.org/)
* [`uv`](https://github.com/astral-sh/uv) (Fast Python package and project manager)

---

## 🚀 Running Homework Locally

Follow these steps to set up and run an assignment locally (e.g., `hw5_airbnb`):

1. **Download the Assignment Package:**
   * In the PrairieLearn workspace, open the left sidebar.
   * Right-click the assignment archive (e.g., `hw5_airbnb_local.zip`) and download it to your local machine.
   * Unzip the downloaded file.

2. **Navigate to the Homework Directory:**
   Open a terminal and navigate to the extracted folder:
   ```bash
   cd path/to/hw5_airbnb

```

3. **Install Dependencies:**
Run `uv sync` to set up the environment and lock dependencies:
```bash
uv sync --locked

```


4. **Launch Jupyter Lab:**
Once setup is complete, launch Jupyter Lab with:
```bash
uv run --locked jupyter lab

```


5. **Submitting Your Work:**
* Complete your work in the local Jupyter Notebook (`.ipynb`).
* When finished, drag and drop **only** the modified `.ipynb` file back into PrairieLearn.
* Ensure the filename remains unchanged before clicking **Save and Grade**.



---

## 💻 Tech Stack

* **Language:** Python 3.x
* **Package / Environment Management:** `uv`
* **Interface:** JupyterLab
* **Core Libraries:** `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`

---

## ⚠️ Academic Integrity

This repository is maintained for personal reference and portfolio purposes. If you are currently taking CPSC 330 at UBC, please adhere to UBC's Academic Integrity guidelines and refrain from directly copying any code or solution files.

```

```