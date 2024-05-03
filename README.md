
# CS4295_Project
Final project for CS4295 Release Engineering for Machine Learning Applications


1. download_dataset
2. preprocessing
3. model_train
4. model_predict

## Setup
To set up the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/nickdubbel/CS4295_Project.git
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv myenv
    source myenv/bin/activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Authentication

    In order to udownload the dataset, you must first authenticate using an kaggle API token. Go to the 'Account' tab of your user profile and select 'Create New Token'. This will trigger the download of kaggle.json, a file containing your API credentials.

    If you are using the Kaggle CLI tool, the tool will look for this token at ~/.kaggle/kaggle.json on Linux, OSX, and other UNIX-based operating systems, and at C:\Users\<Windows-username>\.kaggle\kaggle.json on Windows. If the token is not there, an error will be raised. Hence, once you’ve downloaded the token, you should move it from your Downloads folder to this folder.

4. Run the project:
    ```bash
    python main.py
    ```

<!-- # options for poetry
3. Install the required dependencies using Poetry:
    ```bash
    poetry install
    ```

4. Run the project:
    ```bash
    poetry run python main.py
    ``` -->
