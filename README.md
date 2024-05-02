# jewlex-stack

This stack is used to build your infrastructure in your local and production server

# Pre-requisites 
# Install docker and docker-compose in your local machine
- Install docker for [Windows](https://docs.docker.com/desktop/install/windows-install)
- Install docker for [Linux or Ubuntu](https://docs.sevenbridges.com/docs/install-docker-on-linux)
- Install docker for [Mac](https://docs.sevenbridges.com/docs/install-docker-on-linux) 

# Install docker-compose in your local machine
- Install docker-compose for [Windows](https://docs.docker.com/compose/install/)
- Install docker-compose for [Linux or Ubuntu](https://docs.docker.com/compose/install/)
- Install docker-compose for [Mac](https://docs.docker.com/compose/install/)

# Launch Stack(Nodejs+Redis+Postgresql):
- Code Checkout
```sh
git clone https://github.com/suraj143/jewlex-stack.git
cd jewlex-stack
```
- Copy code in app directory
```sh
mkdir app
cp -r <source_code_path> app
```
- Build and Launch Infra
```sh
docker-compose up -d
docker-compose ps
```
- Open Browser to access Nodejs/NextJS App [http://127.0.0.1:3000] or [http://localhost:3000]

- update docker-compose.yaml file as per your business requirements 
