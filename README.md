# Kuet_BitFest_Tahmid
To create a virtual environment named `env`, use the following command:

Create a venv

```bash
python -m venv env
```

Now activate it

On Windows:

```bash
.\env\Scripts\activate
```

On macOS and Linux:

```bash
source env/bin/activate
```

To install the required packages, use the following command:

```bash
pip install -r requirements.txt
```

Download Ollama from [here](https://ollama.com/) and install it. To pull the required models, use the following commands in the terminal:

To pull the Qwen 2.5 Coder model:

```bash
ollama run qwen2.5-coder
```

To pull the Llama 3.2 model:

```bash
ollama run llama3.2
```

Create a `.env` file with the following content:

```
GOOGLE_API_KEY='your_api_key_here'
```

To run the code in `practice.ipynb`, follow these steps:

1. Open `practice.ipynb`.
2. Select the kernel associated with the created virtual environment (`env`).
3. Execute the cells to run the code.

Connect with me on [LinkedIn](https://www.linkedin.com/in/trahmanrifat/)
