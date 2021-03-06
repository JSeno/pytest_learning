# Aprendendo como são as funcionalidades do pytest

### Documentação do pytest:
    
&nbsp;[`pytest`](https://docs.pytest.org/en/latest/index.html) e&nbsp;[`pytest-mock`](https://docs.pytest.org/en/latest/example/simple.html).  
&nbsp;

### Antes de iniciar é necessário instalar duas bibliotecas:&nbsp;  

-----
#### Algumas bibliotecas e como instalar:

```bash

# O pytest é uma biblioteca de testes automatizados.
 pip install pytest

# O pytest-order é uma biblioteca de testes automatizados que permite ordenar os testes.
 pip install pytest-order

# O pytest-mock é uma biblioteca de testes automatizados que permite fazer mock de funções.
 pip install pytest-mock

# O pytest-cov é uma biblioteca de testes automatizados que permite cobertura de código.
 pip install pytest-cov

# O pytest-html é uma biblioteca de testes automatizados que permite gerar relatórios em HTML.
 pip install pytest-html

# O pytest-markdown é uma biblioteca de testes automatizados que permite gerar relatórios em Markdown.
 pip install pytest-markdown

```
-----
&nbsp;  

### Preparando o ambiente:&nbsp;    


Após isso deve ser instalado um diretório de testes, onde serão armazenados os testes chamado de `tests`.&nbsp;  

Quando for criar um arquivo de teste, ele deve ser criando dentro da pasta `tests` e com o nome `test_*.py`.&nbsp;  
Por exemplo:&nbsp;  
 `test_hello_world.py`&nbsp;  
 &nbsp;  


 É utilizado o pytest para testar os retornos das funções. Para isso, é necessário criar uma função com o nome de:&nbsp;  
    `def test_hello_world():`&nbsp;
    e no retorno é utilizado o assert para verificar se o retorno da função é o esperado.&nbsp;  
    Por exemplo:&nbsp;  
    &nbsp;


```python
def test_hello_world():
    assert hello_world() == 'Hello World!'
```

     














