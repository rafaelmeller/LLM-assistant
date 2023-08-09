**RESUMO:**

**Aplicação em Python utilizando as bibliotecas da OpenAI e Langchain para criar um assistente como o ChatGPT capaz de analisar e extrair informações específicas de um arquivo de texto (.txt) presente no diretório "/data".


**COMO USAR:**

Primeiramente, para utilizar uma API da OpenAI, é necessário criar uma API Key se registrando no site abaixo:

https://platform.openai.com/

Depois de criar sua conta, vá em "View API keys" e crie a sua. Com esse código, é possivel criar uma API vinculada a sua conta, então tome o cuidado de salvar essa Key em um lugar seguro e não disponibilizar ela para nenhum desconhecido (ou em ambientes virtuais públicos).

Após isso, crie um arquivo ".env" no mesmo diretório em que você salvou o arquivo app.py. Nesse arquivo, digite o seguinte na primeira linha: OPENAI_API_KEY= 
Cole sua API key logo em seguida, na mesma linha.

Na pasta data, presente no mesmo diretório, insira todos os arquivos .txt que você deseja utilizar na aplicação.

- Para executar essa aplicação, é necessário dar o seguinte comando para instalar as bibliotecas no seu ambiente:

```
pip install langchain openai chromadb tiktoken unstructured python-dotenv
```

- Execute o programa no terminal com o seguinte comando:

```
python app.py 
```

ou o comando abaixo, caso esteja utilizando um Mac:

```
“python3 app.py” 
```

Ao aparecer a linha "Prompt: " você já pode escrever o que deseja que a aplicação faça com os arquivos selecionados. Quando acabar o uso, basta escrever "fim" e a aplicação finalizará.