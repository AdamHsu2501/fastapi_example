## FastAPI example

1. Clone repo
   ```
   git clone https://github.com/AdamHsu2501/fastapi_example.git
   ```

2. Install env
    ```
    pipenv install
    ```
3. start env
   ```
   pipenv shell
   ```
4. Run app `uvicorn [model]:[var] --reload`
   ```
   uvicorn main:app --reload
   ```
5. Open website `http://127.0.0.1:8000`
6. Review APIs
   `http://127.0.0.1:8000/docs` or
   `http://127.0.0.1:8000/redoc`