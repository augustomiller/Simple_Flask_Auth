<div align="center">
 <h1>Simple Flask Auth 🌶️🔐 </h1>
</div>

## Projeto focado em autenticação com persistência em um banco de dados utilizando o Frameork Flask.


![_9f043b25-17d6-4fc3-bf74-5412db9e3944](https://github.com/augustomiller/lab_flask/assets/990877/52320f53-f134-426d-be65-410700a22aeb)

### Startando o projeto 🚀

```python
pip install -r requirements.txt
```

### Gerando o Data Base com o Flask 📅

```python
flask shell
db.create_all()
db.session.commit()
exit()
```

### Criando um objeto da Classe User

```python
flask shell
user = User(username="admin", password="!@#789qwe")
user
```
Visualizando o objeto criado
```python
user
user.username
user.password
```
Utilizando o SQLalchemy para adionar o objeto(cadastar) na Base de dados
```python
db.session.add(user)
db.session.commit()
exit()
```

### Links úteis

https://flask-login.readthedocs.io/en/latest/
https://flask-sqlalchemy.palletsprojects.com/en/3.1.x/queries/#queries-records

## License

<div align="center">
  
<p>This project is licensed under the MIT License. See the
  <a href="https://mit-license.org/">
    <img src="https://img.shields.io/static/v1?label=license&message=MIT&color=5965E0&labelColor=121214" alt="License"></a> file for details.</p>
<p>Made with&nbsp;💙 &nbsp;by Augusto Miller</p>
  
<div>
