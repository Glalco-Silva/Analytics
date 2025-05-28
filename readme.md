## Criar, ativar e desativar ambiente virtual 

```bash 
python -m venv env
. env/Scripts/activate
deactivate
```

## Instalando biblioteca no ambiente virtual (ex: jupyter)

```bash 
pip intall jupyter
```

## Iniciando e fechando jupyter notebook

```bash 
jupyter notebook
```

Para parar o servidor jupiter notebook, apertar `ctrl+c`

## Configurando e-mail e usuário Git Hub

```bash 
git config --global user.email "email@gmail.com"
git config --global user.name "userName"
```

## Iniciando repositório

```bash 
git init
```

## Enviando o primeiro push

```bash
git add . 
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Glalco-Silva/<RepositorioName>.git
git push -u origin main
```

## Enviando alterações para o GitHub

```bash 
git add . 
git commit -m "message"
git push
```



