# Portif-lio
Projetos Pessoais Thiago Moreira Dev
<body>
  <div class="container">
    <header class="perfil">
      <img class="perfil-foto" src="https://github.com/thgmoreira.png" />
      <div class="titulo">
        <h1>Thiago Moreira</h1>
        <h3>Desenvolvedor Júnior Front-end</h3>
      </div>

    </header>
    <main class="projetos">
      <ul class="projetos-titulo">Projetos<ul>
          <li class="projetos-item"><a href="https://codepen.io/imersao-dev/pen/zYNOZRX">Conversor de moedas</a></li>
    </main>
  </div>
</body>

@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,700;1,700&display=swap");
body {
  background: linear-gradient(236.85deg, #041832 27.26%, #3468a7 96.03%);
  font-family: "Roboto", sans-serif;
}
.container {
  background: #ecf4ff;
  color: #1c1c1c;
  margin: 64px;
  border-radius: 20px;
  box-shadow: 6px 6px 6px #0e1d2f;
  padding: 64px;
}
.perfil {
  display: flex;
  align-items: center;
}
.perfil-foto {
  border-radius: 400px;
  max-height: 155px;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.titulo {
  margin-left: 16px;
}
.titulo h1{
  font-weight 700;
  font-size: 36px;
}
.titulo h3{
  font-weight 400;
  font-size: 24px;
}
.projetos {
  display: flex;
  flex-direction: column;
  background: linear-gradient(230.65deg, #449CFE 27.49%, #9CC8FC 83.19%);
  margin-top: 32px;
  padding: 32px;
  box-shadow: 2px 2px 4px rgba(16, 16, 16, 0.42);
  border-radius: 20px;
}
.projetos-titulo{
  list-style: none;
  font-weight: 700;
  font-size: 36px;
 }
.projetos-item{
  list-style-type: none;
  font-size: 24px;
  font-weight: 400;
  live-height: 48px;
}
.projetos-item a {
  color: #1C1C1C;
  text-decoration: none;
}
