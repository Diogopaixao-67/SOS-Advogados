
<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>SOS Jurídico Angola</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#f4f6fb;
    color:#222;
}

header{
    position:sticky;
    top:0;
    z-index:1000;
    height:65px;
    background:#0d47a1;
    color:#fff;
    display:flex;
    align-items:center;
    gap:15px;
    padding:0 18px;
    box-shadow:0 3px 10px rgba(0,0,0,.2);
}

header h1{
    font-size:22px;
    font-weight:600;
}

.menuBtn{
    border:none;
    background:none;
    color:#fff;
    font-size:30px;
    cursor:pointer;
}

.menu{
    position:fixed;
    left:-280px;
    top:0;
    width:270px;
    height:100%;
    background:#fff;
    transition:.35s;
    overflow:auto;
    box-shadow:3px 0 18px rgba(0,0,0,.2);
    z-index:2000;
}

.menu.ativo{
    left:0;
}

.logo{
    background:#0d47a1;
    color:#fff;
    padding:22px;
    font-size:23px;
    font-weight:bold;
    text-align:center;
}

.menu ul{
    list-style:none;
}

.menu li{
    padding:17px 20px;
    border-bottom:1px solid #eee;
    cursor:pointer;
    transition:.3s;
}

.menu li:hover{
    background:#f0f4ff;
}

.banner{
    margin:18px;
    background:linear-gradient(135deg,#0d47a1,#1976d2);
    color:#fff;
    padding:30px;
    border-radius:18px;
    text-align:center;
}

.banner h2{
    margin-bottom:12px;
    font-size:27px;
}

.banner p{
    opacity:.95;
    line-height:1.6;
}

.cadastro{
    padding:18px;
}

.novoAdvogado{
    width:100%;
    padding:15px;
    border:none;
    border-radius:12px;
    background:#00a152;
    color:#fff;
    font-size:17px;
    cursor:pointer;
    font-weight:600;
}

.pesquisa{
    padding:0 18px 20px;
}

.pesquisa input{
    width:100%;
    padding:15px;
    border-radius:12px;
    border:1px solid #ccc;
    outline:none;
    font-size:16px;
}

.lista{
    padding:18px;
    display:grid;
    gap:18px;
}

.card{
    background:#fff;
    border-radius:18px;
    padding:18px;
    box-shadow:0 4px 15px rgba(0,0,0,.08);
}

.card h3{
    color:#0d47a1;
    margin-bottom:10px;
}

.card p{
    margin:7px 0;
    font-size:15px;
}

.estrelas{
    margin-top:12px;
    font-size:28px;
    color:#ffc107;
}

.estrelas span{
    cursor:pointer;
    transition:.2s;
}

.estrelas span:hover{
    transform:scale(1.2);
}

.whatsapp{
    margin-top:18px;
    width:100%;
    padding:14px;
    border:none;
    border-radius:10px;
    background:#25D366;
    color:#fff;
    font-size:16px;
    cursor:pointer;
    font-weight:600;
}

.modal{
    position:fixed;
    inset:0;
    background:rgba(0,0,0,.55);
    display:none;
    align-items:center;
    justify-content:center;
    padding:20px;
    z-index:3000;
}

.caixa{
    width:100%;
    max-width:420px;
    background:#fff;
    border-radius:18px;
    padding:22px;
}

.caixa h2{
    margin-bottom:20px;
    text-align:center;
}

.caixa input,
.caixa select{
    width:100%;
    margin-bottom:15px;
    padding:14px;
    border:1px solid #ccc;
    border-radius:10px;
    font-size:15px;
}

.botoes{
    display:flex;
    gap:10px;
}

.botoes button{
    flex:1;
    padding:13px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    color:#fff;
    font-size:15px;
}

.botoes button:first-child{
    background:#0d47a1;
}

.botoes button:last-child{
    background:#e53935;
}

.sobre{
    position:fixed;
    inset:0;
    background:#fff;
    overflow:auto;
    display:none;
    padding:30px;
    z-index:4000;
}

.sobre h2{
    color:#0d47a1;
    margin-bottom:15px;
}

.sobre p{
    line-height:1.8;
    text-align:justify;
}

.sobre button{
    margin-top:25px;
    width:100%;
    padding:15px;
    border:none;
    border-radius:10px;
    background:#0d47a1;
    color:#fff;
    font-size:16px;
    cursor:pointer;
}

@media(max-width:600px){

header h1{
    font-size:19px;
}

.banner h2{
    font-size:22px;
}

.banner{
    padding:22px;
}

.card{
    padding:16px;
}

.estrelas{
    font-size:24px;
}

}

</style>

</head>

<body>

<!-- MENU -->

<div id="menu" class="menu">

<div class="logo">
⚖ SOS Jurídico
</div>

<ul>

<li onclick="mostrarTodos()">
🏠 Início
</li>

<li onclick="filtrarCategoria('Penal')">
⚖ Direito Penal
</li>

<li onclick="filtrarCategoria('Civil')">
📑 Direito Civil
</li>

<li onclick="filtrarCategoria('Trabalho')">
💼 Direito do Trabalho
</li>

<li onclick="filtrarCategoria('Família')">
👨‍👩‍👧 Direito da Família
</li>

<li onclick="filtrarCategoria('Comercial')">
🏢 Direito Comercial
</li>

<li onclick="filtrarCategoria('Administrativo')">
🏛 Direito Administrativo
</li>

<li onclick="filtrarCategoria('Tributário')">
💰 Direito Tributário
</li>

<li onclick="filtrarCategoria('Constitucional')">
📘 Direito Constitucional
</li>

<li onclick="sobreNos()">
ℹ Sobre Nós
</li>

</ul>

</div>

<!-- TOPO -->

<header>

<button class="menuBtn" onclick="abrirMenu()">
☰
</button>

<h1>
SOS Jurídico Angola🇦🇴
</h1>

</header>

<!-- BANNER -->

<section class="banner">

<h2>
Encontre um advogado perto de si.
</h2>

<p>
Pesquise por província ou categoria e entre em contacto rapidamente pelo WhatsApp.
</p>

</section>

<!-- CADASTRO -->

<section class="cadastro">

<button class="novoAdvogado" onclick="pedirSenha()">
➕ Cadastrar Advogado

</button>

</section>

<!-- PESQUISA -->

<section class="pesquisa">

<input
type="text"
id="pesquisaProvincia"
placeholder="Pesquisar por província..."
onkeyup="pesquisarProvincia()">

</section>

<!-- LISTA -->

<section
id="listaAdvogados"
class="lista">

</section>

<!-- SOBRE -->

<div
id="sobre"
class="sobre">

<h2>
Sobre Nós
</h2>

<p>

O SOS Jurídico Angola é uma plataforma criada para facilitar o acesso da população angolana aos profissionais do Direito.

Aqui é possível localizar advogados por província, categoria e entrar em contacto rapidamente através do WhatsApp.

</p>

<button onclick="fecharSobre()">

Fechar

</button>

</div>

<!-- MODAL CADASTRO -->

<div
id="modalCadastro"
class="modal">

<div class="caixa">

<h2>
Cadastrar Advogado
</h2>

<input
id="nome"
placeholder="Nome do advogado">

<input
id="provincia"
placeholder="Província">

<select id="categoria">

<option>Penal</option>

<option>Civil</option>

<option>Trabalho</option>

<option>Família</option>

<option>Comercial</option>

<option>Administrativo</option>

<option>Tributário</option>

<option>Constitucional</option>

</select>

<div class="botoes">

<button onclick="salvarAdvogado()">

Salvar

</button>

<button onclick="fecharCadastro()">

Cancelar

</button>

</div>

</div>

</div>

<script>

let advogados = JSON.parse(localStorage.getItem("advogados")) || [];

function salvarLocal(){
    localStorage.setItem("advogados", JSON.stringify(advogados));
}

function abrirMenu(){
    document.getElementById("menu").classList.toggle("ativo");
}

function sobreNos(){
    document.getElementById("sobre").style.display="block";
    document.getElementById("menu").classList.remove("ativo");
}

function fecharSobre(){
    document.getElementById("sobre").style.display="none";
}

function pedirSenha(){

    let senha = prompt("Digite a senha:");

    if(senha==="5"){
        document.getElementById("modalCadastro").style.display="flex";
    }else{
        alert("Senha incorreta!");
    }

}

function fecharCadastro(){
    document.getElementById("modalCadastro").style.display="none";
}

function salvarAdvogado(){

    let nome=document.getElementById("nome").value.trim();
    let provincia=document.getElementById("provincia").value.trim();
    let categoria=document.getElementById("categoria").value;

    if(nome==="" || provincia===""){
        alert("Preencha todos os campos.");
        return;
    }

    advogados.push({
        nome:nome,
        provincia:provincia,
        categoria:categoria,
        estrelas:0
    });

    salvarLocal();

    document.getElementById("nome").value="";
    document.getElementById("provincia").value="";
    document.getElementById("categoria").selectedIndex=0;

    fecharCadastro();

    renderizar(advogados);

}

function renderizar(lista){

    let html="";

    lista.forEach((a,index)=>{

        html+=`

        <div class="card">

            <h3>${a.nome}</h3>

            <p><strong>Província:</strong> ${a.provincia}</p>

            <p><strong>Categoria:</strong> ${a.categoria}</p>

            <div class="estrelas">

                <span onclick="avaliar(${index},1)">
                ${a.estrelas>=1?'★':'☆'}
                </span>

                <span onclick="avaliar(${index},2)">
                ${a.estrelas>=2?'★':'☆'}
                </span>

                <span onclick="avaliar(${index},3)">
                ${a.estrelas>=3?'★':'☆'}
                </span>

                <span onclick="avaliar(${index},4)">
                ${a.estrelas>=4?'★':'☆'}
                </span>

                <span onclick="avaliar(${index},5)">
                ${a.estrelas>=5?'★':'☆'}
                </span>

            </div>

            <button
            class="whatsapp"
            onclick="window.open('https://wa.me/244941530467','_blank')">

            Chamar no WhatsApp

            </button>

        </div>

        `;

    });

    if(lista.length===0){

        html=`
        <div class="card">
        <h3>Nenhum advogado encontrado.</h3>
        </div>
        `;

    }

    document.getElementById("listaAdvogados").innerHTML=html;

}
function pesquisarProvincia(){

    const texto = document
        .getElementById("pesquisaProvincia")
        .value
        .toLowerCase()
        .trim();

    if(texto===""){
        renderizar(advogados);
        return;
    }

    const resultado = advogados.filter(a =>
        a.provincia.toLowerCase().includes(texto)
    );

    renderizar(resultado);

}

function filtrarCategoria(categoria){

    document.getElementById("menu").classList.remove("ativo");

    const resultado = advogados.filter(a =>
        a.categoria === categoria
    );

    renderizar(resultado);

}

function mostrarTodos(){

    document.getElementById("menu").classList.remove("ativo");

    renderizar(advogados);

}

function avaliar(indice, estrelas){

    advogados[indice].estrelas = estrelas;

    salvarLocal();

    renderizar(advogados);

}

window.onclick = function(event){

    const modal = document.getElementById("modalCadastro");

    if(event.target === modal){
        fecharCadastro();
    }

}

window.onload = function(){

    if(advogados.length === 0){

        advogados = [

            {
                nome:"Dr. Manuel António",
                provincia:"Luanda",
                categoria:"Penal",
                estrelas:5
            },

            {
                nome:"Dra. Ana Paula",
                provincia:"Benguela",
                categoria:"Civil",
                estrelas:4
            },

            {
                nome:"Dr. Carlos Mateus",
                provincia:"Huambo",
                categoria:"Trabalho",
                estrelas:5
            },

            {
                nome:"Dra. Helena Domingos",
                provincia:"Huíla",
                categoria:"Família",
                estrelas:4
            }

        ];

        salvarLocal();

    }

    renderizar(advogados);

};

</script>

<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>SOS Jurídico Angola</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
background:#eceff1;
}

.header{

background:white;
box-shadow:0 2px 8px rgba(0,0,0,.2);

}

.capa{

height:230px;

background:linear-gradient(120deg,#003366,#0057b8,#0099ff);

}

.perfil{

margin-top:-70px;

text-align:center;

}

.perfil img{

width:140px;

height:140px;

border-radius:50%;

border:5px solid white;

background:white;

}

.nome{

font-size:28px;

font-weight:bold;

margin-top:10px;

}

.desc{

color:#555;

margin-top:5px;

}

.info{

display:flex;

justify-content:center;

gap:30px;

margin-top:15px;

font-size:18px;

font-weight:bold;

}

button{

border:none;

cursor:pointer;

}

#seguir{

margin:20px;

background:#1877f2;

color:white;

padding:12px 35px;

border-radius:8px;

font-size:18px;

}

#seguir:hover{

background:#0058d6;

}

.posts{

padding:15px;

}

.card{

background:white;

border-radius:12px;

padding:15px;

margin-bottom:15px;

box-shadow:0 2px 8px rgba(0,0,0,.15);

}

.advogado{

display:flex;

align-items:center;

justify-content:space-between;

}

.left{

display:flex;

align-items:center;

}

.left img{

width:70px;

height:70px;

border-radius:50%;

margin-right:12px;

}

.status{

color:green;

font-weight:bold;

margin-top:5px;

}

.titulo{

font-size:23px;

margin-bottom:15px;

font-weight:bold;

}

.footer{

padding:20px;

text-align:center;

color:#555;

}

</style>

</head>

<body>

<div class="header">

<div class="capa"></div>

<div class="perfil">

<img src="HTML/Logo jurídico SOS Angola.png">

<div class="nome">
SOS Jurídico Angola
</div>

<div class="desc">
Ajudando cidadãos angolanos a encontrar assistência jurídica rápida.
</div>

<div class="info">

<div>
<strong id="seguidores">1.500.000.00</strong><br>
Seguidores
</div>

<div>
<strong>15</strong><br>
Advogados
</div>

</div>

<button id="seguir">
Seguir
</button>

</div>

</div>

<div class="posts">

<div class="titulo">
Lista de clientes satisfeitos
</div>

<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">


<style>


.depoimentos{
  max-width:900px;
  margin:30px auto;
  padding:15px;
}

.

.nome a{
  color:;
  font-weight:bold;
  text-decoration:none;
}

.nome a:hover{
  text-decoration:underline;
}

.info{
  font-size:13px;
  color:#9aaea2;
  margin-top:4px;
}

.texto{
  margin:10px 0 14px;
  line-height:1.4;
}

.reacoes{
  display:flex;
  align-items:center;
  gap:15px;
  flex-wrap:wrap;
}

.reacoes button{
  background:#0b1a12;
  border:1px solid rgba(0,255,120,0.4);
  color:#3cff9a;
  font-size:18px;
  padding:6px 12px;
  border-radius:8px;
  cursor:pointer;
}

.reacoes button:hover{
  background:#102a1c;
}

.contador{
  font-size:14px;
  color:#cfeede;
}

/* MOBILE */
@media(max-width:600px){
  .card{
    padding:14px;
  }
  .reacoes{
    gap:10px;
  }
}
</style>
</head>

<body>

<div class="depoimentos" id="depoimentos"></div>

<script>
// ================= DADOS =================
const depoimentos = [
{
  id:1,
  nome:"Diogo Paixão",
  idade:24,
  pais:"Angola",
  link:"https://facebook.com/diogopaixao",
  texto:"Obtive resultados reais com essa plataforma. Quem quiser comprovação pode visitar meu perfil.",
  likes:600,
  hearts:180
},
{
  id:2,
  nome:"Carlos Mendes",
  idade:31,
  pais:"Brasil",
  link:"https://facebook.com/carlos",
  texto:"Resultados acima das expectativas.",
  likes:142,
  hearts:40
},
{
  id:3,
  nome:"Ana Silva",
  idade:27,
  pais:"Portugal",
  link:"https://facebook.com/ana",
  texto:"Entrega exatamente o que promete.",
  likes:198,
  hearts:55
},
{
  id:4,
  nome:"João Pedro",
  idade:35,
  pais:"Brasil",
  link:"https://facebook.com/joao",
  texto:"Funciona mesmo.",
  likes:121,
  hearts:30
},
{
  id:5,
  nome:"Marcos Lima",
  idade:29,
  pais:"Angola",
  link:"https://facebook.com/marcos",
  texto:"Muito simples de usar.",
  likes:165,
  hearts:44
},
{
  id:6,
  nome:"Sofia Martins",
  idade:28,
  pais:"Portugal",
  link:"https://facebook.com/sofia",
  texto:"Excelente experiência.",
  likes:109,
  hearts:28
},
// (pode duplicar até 20 mantendo ids diferentes)
];

// ================= STORAGE =================
function getData(id){
  return JSON.parse(localStorage.getItem("dep_"+id));
}

function saveData(dep){
  localStorage.setItem("dep_"+dep.id,JSON.stringify(dep));
}

// ================= RENDER =================
const box = document.getElementById("depoimentos");

depoimentos.forEach(dep=>{
  const saved = getData(dep.id);
  if(saved) dep = saved;

  box.innerHTML += `
    <div class="card">
      <div class="nome">
        <a href="${dep.link}" target="_blank">${dep.nome}</a>
      </div>
      <div class="info">${dep.idade} anos • ${dep.pais}</div>
      <div class="texto">${dep.texto}</div>
      <div class="reacoes">
        <button onclick="like(${dep.id})">👍</button>
        <button onclick="heart(${dep.id})">❤️</button>
        <div class="contador">
          👍 <span id="like_${dep.id}">${dep.likes}</span>
          • ❤️ <span id="heart_${dep.id}">${dep.hearts}</span>
        </div>
      </div>
    </div>
  `;

  saveData(dep);
});

// ================= AÇÕES =================
function like(id){
  let dep = getData(id);
  dep.likes++;
  saveData(dep);
  document.getElementById("like_"+id).innerText = dep.likes;
}

function heart(id){
  let dep = getData(id);
  dep.hearts++;
  saveData(dep);
  document.getElementById("heart_"+id).innerText = dep.hearts;
}
</script>

</body>
</html>

<div id="lista"></div>

</div>

<footer style="width:100%; text-align:center; padding:15px; margin-top:20px;
background:#f2f2f2; color:#333; font-size:14px; border-top:1px solid #ddd;">
  ©2026 SOS jurídico Angola• Todos os direitos reservados  
  | <a href="#" style="color:#333; text-decoration:underline;">Termos de Uso</a>
</footer>


</body>
</html>
