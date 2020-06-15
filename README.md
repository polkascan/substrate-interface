# Polkascan Substrate Interface
Polkascan Substrate Interface Main Application

## Run application

* Make sure to also clone submodules within the cloned directory: 
```bash
git submodule update --init --recursive
```

* Build and run the Docker containers (using public node wss://kusama-rpc.polkadot.io)
```bash
docker-compose -f docker-compose.kusama-cc3-public.yml up --build
```

* Build and run the Docker containers (using local Kusama CC3 node)
```bash
docker-compose -f docker-compose.kusama-cc3-local.yml up --build
```

## Links

* Polkascan Substrate Interface GUI: http://127.0.0.1:8001
* Polkascan Substrate Interface API: http://127.0.0.1:8000
