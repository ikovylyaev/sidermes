---
layout: page
title: Каталог
permalink: /catalog2/
---

<div class="catalog-nav row">
	<div class="card col-3">
	  
	  <div class="card-body">
	    <h5 class="card-title">Линия для стали</h5>
	    <a href="cat1/pod1" class="card-link">Датчики</a><br>
	    <a href="cat1/pod2" class="card-link">Приборы</a><br>
	    <a href="cat1/pod3" class="card-link">Дополнительные приспособления</a><br>
	    <a href="cat1" class="btn btn-primary">Просмотреть все товарыы</a>
	  </div>
	</div>
	<div class="card col-3">
	  
	  <div class="card-body">
	    <h5 class="card-title">Линия для черных металлов</h5>
	    <a href="cat2/pod1" class="card-link">Датчики</a><br>
	    <a href="cat2/pod2" class="card-link">Приборы</a><br>
	    <a href="cat2/pod3" class="card-link">Дополнительные приспособления</a><br>
	    <a href="cat2" class="btn btn-primary">Просмотреть все товарыы</a>
	  </div>
	</div>
	<div class="card col-3">
	  
	  <div class="card-body">
	    <h5 class="card-title">Линия для цветных металлов</h5>
	    <a href="cat3/pod1" class="card-link">Датчики</a><br>
	    <a href="cat3/pod2" class="card-link">Приборы</a><br>
	    <a href="cat3/pod3" class="card-link">Дополнительные приспособления</a><br>
	    <a href="cat3" class="btn btn-primary">Просмотреть все товарыы</a>
	  </div>
	</div>
	<div class="card col-3">
	  
	  <div class="card-body">
	    <h5 class="card-title">Линия специальных изделий</h5><br>
	    <a href="cat4" class="btn btn-primary">Просмотреть все товарыы</a>
	  </div>
	</div>
</div>
<style type="text/css">
	.header-page{background: url({{ site.url }}/img/bg-catalog.jpeg); background-size: cover;}
	.col-3{padding: 0px; margin: 0px;}
	.row{padding: 0px; margin: 0px;}
	.card-body{border-radius: 0px; border-width: 0px; padding: 20px;}
	.card{border-radius: 0px; border-width: 0px; height: 50vh;}
	.card-img-top{border-radius: 0px; border-width: 0px; z-index: 0}
	.page-section{padding: 0px; margin: 0px;}
.card-body:after {
  display: inline-block;
  position: absolute;
  width: 0;
  height: 3px;
  background: #222;
}
.card-body:hover:after {
  animation: run 2s 1 linear;
}

@keyframes run {
  0% {
    width: 0px;
  }
  25% {
    width: 25%;
  }
  50% {
    width: 50%;
  }
  75% {
    width: 75%;
  }
  100%{
  	width: 100%;
  }
}
</style>