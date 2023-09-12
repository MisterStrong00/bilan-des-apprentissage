# HTML
```
<h1>Bilan des apprentissages</h1>
<div style="margin-bottom: 40px">
	<button class="backBut" onclick="changePage('ICON', ext='.jpg')">JPG</button>
	<button class="backBut" onclick="changePage('project1')" data-project="Projet1">Projet 1</button>
	<button class="backBut" onclick="changePage('project2')" data-project="Projet2">Projet 2</button>
	<button class="backBut" onclick="changePage('project3')" data-project="Projet3">Projet 3</button>
	<button class="backBut" onclick="changePage('project4')" data-project="Projet4">Projet 4</button>
	<button class="backBut" onclick="changePage('project5')" data-project="Projet5">Projet 5</button>
	<button class="backBut" onclick="changePage('project6')" data-project="Projet6">Projet 6</button>
	<button class="backBut" onclick="changePage('project7')" data-project="Projet7">Projet 7</button> 
</div>
```

# CSS
```
.backBut {
  background-color: rgb(0, 75, 135);
  color: white;
  border-color: hidden;
  border-style: hidden;
  float: left;
  border: 1px solid;
  display: block;
  text-decoration: none;
  padding: 10px;
  margin-right: 10px;
  cursor: pointer;
}

.backBut:hover {
  background-color: white;
  color: rgb(0, 75, 135);
}
```

# Javascript
```
function changePage(project, ext = ".html") {
  window.location.pathname = "/" + project + ext;
}
```
# Redirection
```
  <a class="nav-link" href="/project1.html">Projet 1</a>
  ````