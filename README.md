# 👨🏻‍💻 João Guilherme - GhostDev 

**`Estudante FullStack`**

Me chamo João Guilherme da Silva, Tenho 17 anos e sou estudante de Desenvolvimento de Sistemas em uma escola técnica. Atualmente estou no 2º ano do ensino médio e, desde pequeno, sempre fui fascinado por tecnologia. Hoje, estou aprendendo a programar de verdade e explorando o mundo da tecnologia de forma mais prática. Tenho interesse em desenvolvimento web e software - front-end. Tenho meu Instagram pessoal, onde pretendo criar conteúdo técnico por lá futuramente: [@itsjoaoguilherme_](https://www.instagram.com/itsjoaoguilherme_/profilecard/?igsh=cDl1NmFhZzE3aGc4).

---

### 🤖 Linguagens e Tecnologias

<img 
    align="left" 
    alt="HTML"
    title="HTML" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" 
/>
<img 
    align="left" 
    alt="CSS" 
    title="CSS"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" 
/>
<img 
    align="left" 
    alt="JavaScript" 
    title="JavaScript"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" 
/>
<img 
    align="left" 
    alt="Git" 
    title="Git"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" 
/>
<img 
    align="left" 
    alt="Python" 
    title="Python"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" 
/>
<img 
    align="left" 
    alt="Java" 
    title="Java"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" 
/>

<br/>
<br/>

---

### 📊 Estatísticas

<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Card Tecnologias</title>
<style>
  body {
    background: #000000; /* preto */
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #ffffff; /* branco */
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  .card {
    background: #1a0a3a; /* roxo escuro */
    border: 1px solid #7e57c2; /* roxo */
    border-radius: 5px;
    padding: 25px 30px;
    width: 320px;
    box-shadow: 0 0 15px #7e57c2cc;
  }
  .card h2 {
    color: #b39ddb; /* lilás claro */
    font-weight: 600;
    font-size: 18px;
    margin-bottom: 20px;
    animation: fadeIn 0.8s ease forwards;
  }
  .progress-bar {
    position: relative;
    background: #3e276a; /* roxo médio */
    border-radius: 5px;
    height: 10px;
    margin-bottom: 18px;
    overflow: hidden;
  }
  .progress-fill {
    height: 100%;
    border-radius: 5px;
    animation: growWidth 0.6s ease forwards;
  }
  .lang-info {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 8px;
    opacity: 0;
    animation: fadeIn 0.3s ease forwards;
    color: #d1c4e9; /* lilás suave */
  }
  .circle {
    width: 12px;
    height: 12px;
    border-radius: 50%;
    flex-shrink: 0;
  }
  .html { background: #7c4dff; }    /* roxo vibrante */
  .css { background: #9575cd; }     /* lilás médio */
  .js { background: #d1c4e9; color: #000; } /* lilás claro */
  .hack { background: #b39ddb; }    /* lilás suave */
  .python { background: #b39ddb; }
  .java { background: #7c4dff; }
  .lang-name {
    font-weight: 400;
    font-size: 13px;
  }
  .lang-percent {
    margin-left: auto;
    font-weight: 600;
    font-size: 14px;
  }
  @keyframes growWidth {
    from { width: 0; }
    to { width: var(--progress-width); }
  }
  @keyframes fadeIn {
    to { opacity: 1; }
  }
  .lang-info:nth-child(1) { animation-delay: 0.45s; }
  .lang-info:nth-child(2) { animation-delay: 0.6s; }
  .lang-info:nth-child(3) { animation-delay: 0.75s; }
  .lang-info:nth-child(4) { animation-delay: 0.9s; }
  .lang-info:nth-child(5) { animation-delay: 1.05s; }
  .lang-info:nth-child(6) { animation-delay: 1.2s; }
  .lang-info:nth-child(7) { animation-delay: 1.35s; }
</style>
</head>
<body>
<div class="card" role="img" aria-labelledby="cardTitle" aria-describedby="cardDesc">
  <h2 id="cardTitle">Tecnologias</h2>
  <div id="cardDesc" hidden>
    Distribuição das linguagens e frameworks usadas.
  </div>

  <div class="lang-info">
    <div class="circle html"></div>
    <div class="lang-name">HTML</div>
    <div class="lang-percent">30.00%</div>
  </div>
  <div class="progress-bar" style="--progress-width: 30%;">
    <div class="progress-fill html" style="width: 0%; animation-delay: 0.45s; animation-fill-mode: forwards;"></div>
  </div>

  <div class="lang-info">
    <div class="circle css"></div>
    <div class="lang-name">CSS</div>
    <div class="lang-percent">15.00%</div>
  </div>
  <div class="progress-bar" style="--progress-width: 15%;">
    <div class="progress-fill css" style="width: 0%; animation-delay: 0.6s; animation-fill-mode: forwards;"></div>
  </div>

  <div class="lang-info">
    <div class="circle js"></div>
    <div class="lang-name">JavaScript</div>
    <div class="lang-percent">10.00%</div>
  </div>
  <div class="progress-bar" style="--progress-width: 10%;">
    <div class="progress-fill js" style="width: 0%; animation-delay: 0.9s; animation-fill-mode: forwards;"></div>
  </div>

  <div class="lang-info">
    <div class="circle python"></div>
    <div class="lang-name">Python</div>
    <div class="lang-percent">10.00%</div>
  </div>
  <div class="progress-bar" style="--progress-width: 10%;">
    <div class="progress-fill python" style="width: 0%; animation-delay: 1.05s; animation-fill-mode: forwards;"></div>
  </div>

  <div class="lang-info">
    <div class="circle java"></div>
    <div class="lang-name">Java</div>
    <div class="lang-percent">30.00%</div>
  </div>
  <div class="progress-bar" style="--progress-width: 30%;">
    <div class="progress-fill java" style="width: 0%; animation-delay: 1.2s; animation-fill-mode: forwards;"></div>
  </div>

  <div class="lang-info">
    <div class="circle hack"></div>
    <div class="lang-name">Hack</div>
    <div class="lang-percent">5.00%</div>
  </div>
  <div class="progress-bar" style="--progress-width: 5%;">
    <div class="progress-fill hack" style="width: 0%; animation-delay: 1.35s; animation-fill-mode: forwards;"></div>
  </div>
</div>

<script>
  document.querySelectorAll('.progress-fill').forEach(el => {
    const width = getComputedStyle(el.parentElement).getPropertyValue('--progress-width');
    el.style.width = width;
  });
</script>

</body
