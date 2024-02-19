# Mi primera api

To run the model, follow the next instructions on the shell:

```sh
git clone
cd my-movie-api
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
PS C:\Users\diego\OneDrive\Documentos\SoftwareProjects\my-movie-api> .\venv\Scripts\activate

uvicorn main:app
uvicorn main:app --reload 
uvicorn main:app --reload --port 5000
uvicorn main:app --reload --port 5000 --host 0.0.0.0
```