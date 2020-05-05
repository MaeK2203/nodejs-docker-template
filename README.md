# nodejs-docker-template

## Usage
```bash
git clone https://github.com/MaeK2203/nodejs-docker-template.git
cd nodejs-docker-template
docker-compose up -d --build
```



### Using as repository template
```bash
git clone --bare https://github.com/MaeK2203/nodejs-docker-template.git
cd nodejs-docker-template.git
git push --mirror https://github.com/xxxx/new-repository.git
cd ..
rm -rf nodejs-docker-template.git
```

