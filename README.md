# Personalized Cold Emails

Send personalized cold emails.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.7 or above
- Pip (usually comes with Python)

### Installing

Follow these steps to set up your development environment:

1. **Clone the project**

    ```bash
    git clone https://github.com/karatugo/cold-email.git
    cd cold-email
    ```

2. **Create a virtual environment**

   The virtual environment is a way to keep the project's dependencies isolated from your global Python environment. Here we create a virtual environment called `env-cold-email`. We're assuming you're using `venv` which comes preinstalled with Python 3.3+.

    ```bash
    python3 -m venv env-cold-email
    ```

3. **Activate the virtual environment**

   On MacOS and Linux:

    ```bash
    source env-cold-email/bin/activate
    ```

   On Windows:

    ```cmd
    .\env-cold-email\Scripts\activate
    ```

4. **Install dependencies**

   After activating the virtual environment, we can use pip to install the required dependencies. This project's dependencies are listed in the `requirements.txt` file.

    ```bash
    pip install -r requirements.txt
    ```

## Usage

After installing, you can start the Jupyter notebook:

```bash
jupyter notebook
```

This will start the Jupyter server and open your default web browser to the Jupyter interface.

From here, you can navigate to your project notebooks and start running your code!
