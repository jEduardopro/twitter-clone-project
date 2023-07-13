## Clone project
```
git clone https://github.com/jEduardopro/twitter-clone-project.git
```

## Pull and Update submodules (remote repositories)
Exec the following commands:
```
cd twitter-clone-project
```
```
git submodule update --init --recursive
```

## Continue with the instructions in the following README file before running the project
<a href="https://github.com/jEduardopro/tw-main-api/blob/docker-setup/README.md">TW Main API README File</a>


<br/>

## After that run project with the following command
```
	docker-compose up --build
```

## Go to browser and open these urls

### API
```
	http://localhost:8200
```
### Client SPA
```
	http://localhost:8000
```