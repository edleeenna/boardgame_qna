# boardgame_qna
Gen AI RAG Project

## Prerequisites
- VS Code
- Python
- AWS CLI
- IAM Role for VSCode
- Ananconda Navigator
  - VSCode is run via Anaconda navigator
  - aws commands may not work within anaconda environment. Solution is to make a batch file in the following path "C:\Users\user\anaconda3\etc\conda\activate.d"
    ```
    @echo off
    set PATH=C:\Path\To\AWSCLI\;%PATH%
    ```
- Boto3
- Langchain
- Streamlit
- flask-sqlalchemy
- pydpdf
- faiss-cpu
