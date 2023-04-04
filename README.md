# Running the server:

```bash
npm install
# Or 
# npx nodemon myserver.ts
```

# Connecting to the server

## From a browser

http://localhost:9000/add?first=50&second=27&fmt=XXXX

where `XXXX` is one of the following

* `text` to get plain text response
* `enc` to get a urlencoded response
* `img` to get a PNG image response
* `json` to get a JSON response


# WARNING

When deploying to Heroku/Render.com you must create a separate git repository ONLY for 
this project.  Deploying from this cloned repo will fail to build.
