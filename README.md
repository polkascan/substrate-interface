# Polkascan Substrate Interface
Polkascan Substrate Interface Main Application

## Run application

* Make sure to also clone submodules within the cloned directory: 
```bash
git submodule update --init --recursive
```

* Kusama Network using a publicly hosted node:
```bash
docker-compose -p substrate-interface -f docker-compose.kusama-public.yml up --build --remove-orphans
```

* Kusama Network using a local node that is part of the docker-compose configuration:
```bash
docker-compose -p substrate-interface -f docker-compose.kusama-local.yml up --build --remove-orphans
```

* Polkadot Network using a publicly hosted node:
```bash
docker-compose -p substrate-interface -f docker-compose.polkadot-public.yml up --build --remove-orphans
```

* Network using a local node that is part of the docker-compose configuration:
```bash
docker-compose -p substrate-interface -f docker-compose.polkadot-local.yml up --build --remove-orphans
```

* Substrate Node Template Development Network using a local node. This step assumes that a Substrate node is running on your local machine. The Docker-Compose configuration points to your localhost from within the configuration:
```bash
docker-compose -p substrate-interface -f docker-compose.kusama-public.yml up --build --remove-orphans
```

## Links

* Polkascan Substrate Interface GUI: http://127.0.0.1:8001
* Polkascan Substrate Interface API: http://127.0.0.1:8000
