# NTEU Translation Engine Docker - Docs

User guide for NTEU translation Engines.

## Usage

### Step 1: Starts the translation server

```
sudo docker run -p 10000:10000 my-docker-tag
```

### Step 2: Translate

```
curl  -X POST -H "Content-Type: application/json" -d '{"texts": ["test"]}' http://0.0.0.0:10000/api/1.0.0/translate

```


