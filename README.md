# Comandos sobre o Bootstrap

O arquivo CSS e JS do bootstrap pode ser via CDM(colar o link derecionado para o arquivo na internet) ou baixando o arquivo.

Deve-se utiliza o bootstrap.min e javascript.min (não sei pq ainda)

Utilizar as tecnologias Jquerry e Popper

Usar comando defer em Javascript para utilizá-lo no header da aplicação

Estudar o console do navegador (F12)

Div principal sendo container ou container-fluid?

## Grid

```
<div class="container">
        <div class="row">
            <div class="col">Primeira</div>
            <div class="col">Segunda</div>
            <div class="col">Terceira</div>

            <div class="col">...</div>
            <div class="col">...</div>
            <div class="col">...</div>
        </div>
    </div>
```    
    
class="col-sm"

class="w-100"

class="col-2"(da para usar valores entre 1 e 12)

class="col-md-2"

div class="order-first"    ->order last, ||||||||||| class="order-1"  |||||||||| order-last, order-first|||||||||

justify-content|||||||justify-content-start||||||||||j-c-center|||||||j-c-end||||around|||||||||||between 

align-items-start|||||a-i-end||||a-i-center

<div class="media"><img src="#" class="mr-3 avatar"> <br> <div class="media-body"> texto...</div>

<ul class="list-unstyled"></ul>

align-self-center

div class="h1"

<small class="text-muted"></small>

<span class="mark"> </span>

class="text-right" ||||||t-center

<ul class="list-inline"> <li class="list-inline-item"></li><li class="list-inline-item"></li> </ul>

<img src="" class="img-fluid">

<img src="" class="img-thumbnail">

<img src="" class="rounded">

<img src="" class="float-right">

```
<figure class="figure">
  <img src="#" class="figure-img">
  <figcaption class="figure-caption">Guilherme</figcaption>
</figure>
```

```
<div class="table-responsive">
<table class="table /*table-dark*/ table-striped table-bordered table-hover /*table-sm*/">
  <thead /*thead=dark*/ /*thead-light*/>
  <tr>
    <th>#</th>
    <th>Nome</th>
    <th>Sobrenome</th>
    <th>idade</th>
  </tr>
  </thead>
  
  <tbody>
  <tr>
    <th>1</th>
    <th>Guilherme</th>
    <th>Vimieiro</th>
    <th>90</th>
  </tr>
  
  <tr>
    <th>1</th>
    <th>Guilherme</th>
    <th>Vimieiro</th>
    <th>90</th>
  </tr>
  
  <tr>
    <th>1</th>
    <th>Guilherme</th>
    <th>Vimieiro</th>
    <th>90</th>
  </tr>
  <tbody>
</table>
</div>
```

```
div class="alert alert-primary alert-dismissible" role="alert">Aviso de alerta para o usuário</div>
secondary
success
danger
warning
div class="alert alert-primary alert-dismissible fade show" role="alert">
Aviso de alerta para o usuário
<buttom class="close" data-dismiss="alert" arial-label="Fechar">
  <span aria-hidden="true">&times;</span>
</buttom>
</div>
```

```
<a class="btn btn-primary" href="#">Botão</a>
<buttom class="btn btn-primary">Botão</buttom>
<input class="btn btn-primary" type="submit" value="Botão">
//btn-outline-danger
//btn-lg
//btn-sm
//btn-block
//div class="btn-group>
//div class="btn-group-vertical>
```

```
<div id="SlideshowExemplo" class="slide carousel">
        <div class="carousel-inner">
                
                <ol>
                        <li data-target="#SlideshowExemplo" data-slide-to="0" class="active"></li>
                        <li data-target="#SlideshowExemplo" data-slide-to="1"></li>
                        <li data-target="#SlideshowExemplo" data-slide-to="2"></li>
                        <li data-target="#SlideshowExemplo" data-slide-to="3"></li>
                </ol>
                
                <div class="carousel-item active">
                            <img src="#" class="w-100">
                </div>
                <div class="carousel-item active">
                            <img src="#" class="w-100">
                </div>
                <div class="carousel-item active>
                            <img src="#" class="w-100">
                </div>
                <div class="carousel-item active">
                            <img src="#" class="w-100">
                </div>
                <a class="carousel-control-prev" href="#SlideshowExemplo" data-slide="prev">
                        <span class="carousel-control-prev-icon"></span>
                </a>
                <a class="carousel-control-next" href="#SlideshowExemplo" data-slide="next">
                        <span class="carousel-control-next-icon"></span>
                </a>
        </div>                
```


```
<buttom class"btn btn primary" data-toggle="collapse" data-target="area">Mostrar/Esconder></buttom>        
<div class="collapse" id="area">texto qualquer</div>
```
                                      
accordion
                                      
class="dropdown"
                
input group
                
list group
                
<span class="badge badge-primary badge-pill">12</span>

```
<div class="list-group">
            <a href="#" class="list-group-item list-group-item-action">
                    <div class="d-flex justfy-content-between">
                          <h5>Título da notícia</h5>
                          <small>2 dias atrás</small>
                     </div>
                    <p>Algume texto sobre o título acima.</p>
            </a>
</div>
```
navbar
        
tooltip

