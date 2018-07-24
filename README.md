# leiaute

Conteúdo em pt-BR sobre layout em HTML e CSS.

## Como atualizar este site

Este site foi construído usando [pelican](http://docs.getpelican.com/en/3.7.1/install.html)
e utiliza [virtualenv](https://virtualenv.pypa.io/en/stable/userguide/). Para setar o ambiente, basta iniciar o ambiente e instalar as dependências:

```
virtualenv ENV
source bin/activate

pip install -r requirements.txt
```

As páginas são geradas no diretório __output__ usando o pelican:

```
pelican
```


### Publicar via githubpages
