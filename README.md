# Backend-Flask-Docker

Construção de uma aplicação com três partes, backend (este repositiório) em Python, o front-end será feito com o Angular cli e os dados persistentes ficarão em um servidor que rodará em um docker.

### Jornada de aprendizado

Como eu sempre reclamo que os tutoriais pulam as partes que tem bug, decidi relatar neste arquivo [detalhes e bugs](https://github.com/TiagoGIM/Backend-Flask-Docker/blob/dev/detalhes_e_bugs.txt) cada erro e como eu contornei(ou tentei).

## Ambiente de desenvolvimento
libs usadas estão em [requirements.txt](https://github.com/TiagoGIM/Backend-Flask-Docker/blob/dev/requirements.txt)

O desenvolvimento foi feito no windows com subsistema linux (WSL).
```
├── Backend
|   ├──scr
|       ├──entities
|           ├──entity.py
|           ├──exam.py
|   ├──main.py
```

## Banco de dados

docker run --name online-exam-db -p 5432:5432 -e POSTGRES_DB=online-exam -e POSTGRES_PASSWORD=0NLIN3-ex4m -d postgres


## Links úteis

- [Tutorial Parte - 1](https://auth0.com/blog/using-python-flask-and-angular-to-build-modern-apps-part-1).
- [WSL  instalação](https://docs.microsoft.com/pt-br/windows/wsl/install-win10).

## Requisitos
Docker
Python 3.8
