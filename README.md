// a viagem de chihiro
// guardiões da galáxia
// as aventuras de pi
// paddington
// ladrões de bicicleta

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}// a viagem de chihiro, LIVRE
// guardiões da galáxia, 12
// as aventuras de pi, 10
// paddington, LIVRE
// ladrões de bicicleta, 12// fantasia, aventura, drama

// a viagem de chihiro, LIVRE, fantasia, aventura
// paddington, LIVRE, fantasia, aventura
// as aventuras de pi, 10, drama, fantasia, aventura
// depois da chuva, 10, drama
// guardiões da galáxia, 12, fantasia, aventura
// ladrões de bicicleta, 12, drama
// o menino que descobriu o vento, 14, dramaidade >= 10idade >= 14fantasia?idade >= 10idade >= 14let n = 1;
function draw() {
  background(220);
  if (n >=9){
    print(n);
  } else{
    print(n);
    n = n+2;
  }
}function draw() {
    background (220);
    let recomendacao = "A viagem de chihiro";
}function draw() {
    background (220);
    let recomendacao = "A viagem de chihiro";
    text(recomendacao, width/2, height/2);
}function draw() {
    background (220);
    let recomendacao = geraRecomendacao();
    text(recomendacao, width/2, height/2);
}function geraRecomendacao() {
  return "A viagem de Chihiro";
}function geraRecomendacao() {
    if (idade >= 10) {
        return "As aventuras de Pi";
    } else {
        return "A viagem de Chihiro";
    }
}function geraRecomendacao(idade) {
    if(idade >= 10) {
        return "As aventuras de Pi";
    } else {
        return "A viagem de Chihiro";
    }
}function draw() {
    background (220);
    let idade = 15;
    let recomendacao = geraRecomendacao(idade);
    text(recomendacao, width/2, height/2);
}function setup() {
    createCanvas(400, 400);
    createInput();
}function setup() {
    createCanvas(400, 400);
    createInput("15");
}function draw() {
    background (220);
    let idade = campoIdade;
    let recomendacao = geraRecomendacao(idade);
    text(recomendacao, width/2, height/2);
}function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
}let campoIdade;

function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
}

// Código omitidofunction draw() {
    background (220);
    let idade = campoIdade.value();
    let recomendacao = geraRecomendacao(idade);
    text(recomendacao, width/2, height/2);
}function geraRecomendacao(idade) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            return "As aventuras de Pi";
        }
    } else {
        return "A viagem de Chihiro";
    }
}function draw() {
    background(220);
    let recomendacao = "A viagem de Chihiro";
    text(recomendacao, width/2, height/2);
}function draw() {
    background(220);
    let recomendacao = geraRecomendacao();
    text(recomendacao, width/2, height/2);
}

function geraRecomendacao() {
  return "A viagem de Chihiro";
}function geraRecomendacao(idade) {
    if (idade >= 10) {
        return "As aventuras de Pi";
    } else {
        return "A viagem de Chihiro";
    }
}function draw() {
    background(220);
    let idade = 15; // exemplo de idade
    let recomendacao = geraRecomendacao(idade);
    text(recomendacao, width/2, height/2);
}let campoIdade;

function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
}function draw() {
    background(220);
    let idade = campoIdade.value();
    let recomendacao = geraRecomendacao(idade);
    text(recomendacao, width/2, height/2);
}function geraRecomendacao(idade) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            return "As aventuras de Pi";
        }
    } else {
        return "A viagem de Chihiro";
    }
}let campoIdade;

function setup() {
  createCanvas(400, 400);
  campoIdade = createInput("15");
}

function draw() {
  background(220);
  let idade = 15; // exemplo de idade
  let recomendacao = geraRecomendacao(idade);
  text(recomendacao, width / 2, height / 2);
}

function geraRecomendacao(idade) {
  if (idade >= 10) {
    if (idade >= 14) {
      return "O menino que descobriu o vento";
    } else {
      return "As aventuras de Pi";
    }
  } else {
    return "A viagem de Chihiro";
  }
}function verificarNumeroDaSorte(______) {
_____(numero === 2 || numero === 11 || numero === 25) {
      ______"Você tirou o número da sorte!";
} _______ {
     return "Não foi dessa vez, tente novamente!";
       }
}let variavelGlobal = "Eu sou global";

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
  text(variavelGlobal, 10, 30);
  exemploLocal();
}

function exemploLocal() {
  let variavelLocal = "Eu sou local";
  text(variavelLocal, 10, 50);
}let variavelGlobal = "Eu sou global";

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
  text(variavelGlobal, 10, 30);
  exemploLocal();
}

function exemploLocal() {
  let variavelLocal = "Eu sou local";
  text(variavelLocal, 10, 50);
}function draw() {
  background(220);
  text(variavelGlobal, 10, 30);
  text(variavelLocal, 10, 50);// As Aventuras de Pi, 10, drama, fantasia, aventura.

// Ladrões de bicicleta, 12, drama.function geraRecomendacao(idade) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if(gostaDeFantasia){
                return "As aventuras de Pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        return "A viagem de Chihiro";
    }
}function geraRecomendacao(idade, gostaDeFantasia) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if(gostaDeFantasia){
                return "As aventuras de Pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        return "A viagem de Chihiro";
    }
}function draw() {
    background (220);
    let idade = campoIdade.value();
    let gostaDeFantasia = false;
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);
    text(recomendacao, width/2, height/2);
}function draw() {
    background (220);
    let idade = campoIdade.value();
    let gostaDeFantasia = true;
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);
    text(recomendacao, width/2, height/2);
}function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
    createCheckbox("Gosta de Fantasia ?");
}let campoIdade;
let campoFantasia;

function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
    campoFantasia = createCheckbox("Gosta de Fantasia ?");
}function draw() {
    background (220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);
    text(recomendacao, width/2, height/2);
}function geraRecomendacao(idade, gostaDeFantasia) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if(gostaDeFantasia){
                return "As aventuras de Pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if(gostaDeFantasia) {
            return "A viagem de Chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}function geraRecomendacao(idade, gostaDeFantasia) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if(gostaDeFantasia){
                return "As aventuras de Pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        return "A viagem de Chihiro";
    }
}
}function draw() {
    background (220);
    let idade = campoIdade.value();
    let gostaDeFantasia = true;
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);
    text(recomendacao, width/2, height/2);
}let campoIdade;
let campoFantasia;

function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
    campoFantasia = createCheckbox("Gosta de Fantasia ?");
}function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);
    text(recomendacao, width / 2, height / 2);
}function geraRecomendacao(idade, gostaDeFantasia) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if(gostaDeFantasia){
                return "As aventuras de Pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if(gostaDeFantasia) {
            return "A viagem de Chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}function avaliarDesempenho(pontuacao, ______) {
    if (nivel === 'iniciante') {
        if (pontuacao >= 50) {
            return "Parabéns! Você passou para o próximo nível.";
        } else {
            return "Infelizmente, você não atingiu a pontuação necessária.";
        }
    } else if ___________ {
        if (pontuacao_____) {
            return "Bom trabalho! Você está se saindo bem.";
        } else {
            return ________________;
        }
    }
}function geraRecomendacao(idade, gostaDeFantasia) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if(gostaDeFantasia) {
                return "As aventuras de pi";
            } else {
              return "Depois da chuva";
            }
        }
    } else {
        if(gostaDeFantasia) {
            return "A viagem de chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }// código omitido

function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade,
gostaDeFantasia);
    textAlign(CENTER, CENTER)
    text(recomendacao, width / 2, height / 2);
}

// código omitido// código omitido

function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade,
gostaDeFantasia);
    textAlign(CENTER, CENTER)
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

// código omitido// código omitido

function setup() {
    createCanvas(800, 400);
    campoIdade createInput("5");
    campoFantasia = createCheckbox("Gosta de fantasia?");
}

// código omitido// código omitido

function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade,
gostaDeFantasia);
    fill(color(255,0 , 255))
    textAlign(CENTER, CENTER)
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

// código omitido// código omitido

function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade,
gostaDeFantasia);
    fill(color(200, 100, 0))
    textAlign(CENTER, CENTER)
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

// código omitido// código omitido

function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade,
gostaDeFantasia);
    fill(color(76, 0, 115))
    textAlign(CENTER, CENTER)
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

// código omitido// código omitido

function draw() {
    background("white");
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade,
gostaDeFantasia);

    fill(color(76, 0, 115))
    textAlign(CENTER, CENTER)
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

// código omitido// código omitido

function setup() {
    createCanvas (800, 400);
    createSpan("Sua idade:");
    campoIdade = createInput("5");
    campoFantasia = createCheckbox("Gosta de fantasia?");
}

// código omitidofunction geraRecomendacao(idade, gostaDeFantasia) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if (gostaDeFantasia) {
                return "As aventuras de pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if (gostaDeFantasia) {
            return "A viagem de chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}function setup() {
    createCanvas(800, 400);
    campoIdade = createInput("5");
    campoFantasia = createCheckbox("Gosta de fantasia?");
}

function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    fill(color(76, 0, 115)); // Um tom de roxo escuro
    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}function draw() {
    background("white");
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    fill(color(76, 0, 115));
    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}function setup() {
    createCanvas(800, 400);
    createSpan("Sua idade:");
    campoIdade = createInput("5");
    campoFantasia = createCheckbox(" Gosta de fantasia?");
}function setup() {
    createCanvas(800, 400);
    createSpan("Sua idade:");
    campoIdade = createInput("5");
    campoFantasia = createCheckbox(" Gosta de fantasia?");
}

function draw() {
    background("white");
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    fill(color(76, 0, 115));
    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

function geraRecomendacao(idade, gostaDeFantasia) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if (gostaDeFantasia) {
                return "As aventuras de pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if (gostaDeFantasia) {
            return "A viagem de chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}html, body {
  margin: 30px;
  padding: 0;
}
canvas {
  display: block;
}html, body {
  margin: 30px;
  padding: 0;
  background-color: rgb(221,233,251);
}
canvas {
  display: block;
}function setup() {
  createCanvas(800, 400);
  createElement("h2", "Recomendador de filmes");
  createSpan("Sua idade:");
  campoIdade = createInput("5");
  campoFantasia = createCheckbox("Gosta de fantasia?");
}html, body {
  margin: 30px;
  padding: 0;
}

canvas {
  display: block;
}html, body {
  margin: 30px;
  padding: 0;
  background-color: rgb(221,233,251);
}

canvas {
  display: block;
}function setup() {
  createCanvas(800, 400);
  createElement("h2", "Recomendador de filmes");
  createSpan("Sua idade:");
  campoIdade = createInput("5");
  campoFantasia = createCheckbox("Gosta de fantasia?");
}html,
body {
  margin: 20px;
  padding: 0px;
  background-color: rgb(0, 188, 212);
}function geraRecomendacao(idade, gostaDeFantasia, gostaDeAventura) {
  if(idade >= 10) {
    if(idade >= 14) {
      return "O menino que descobriu o vento";
    } else {
      if(idade >= 12) {
          return "Ladrões de bicicleta";
        }
      } else {
        if(gostaDeFantasia) {
          return "As aventuras de pi";
        } else {
          return "Depois da chuva";
        }
      }
    }function geraRecomendacao(idade, gostaDeFantasia) {
  if(idade >= 10) {
    if(idade >= 14) {
      return "O menino que descobriu o vento";
    } else {
      if(idade >= 12) {
        if(gostaDeFantasia) {
          return "Homem-aranha: no aranhaverso";
        } else {
          return "Ladrões de bicicleta";
        }function setup() {
  createCanvas(800, 400);
  createElement("h2", "Recomendador de filmes");
  createSpan("Sua idade:");
  campoIdade = createInput("5");
  campoFantasia = createCheckbox("Gosta de fantasia?");
  campoAventura = createCheckbox("Gosta de aventura?");
}function draw() {
  background("white");
  let idade = campoIdade.value();
  let gostaDeFantasia = campoFantasia.checked();
  let gostaDeAventura = campoAventura.checked();
  
  let recomendacao = geraRecomendacao(idade, gostaDeFantasia, gostaDeAventura);function geraRecomendacao(idade, gostaDeFantasia, gostaDeAventura) {

// Trecho de código suprimidofunction geraRecomendacao(idade, gostaDeFantasia, gostaDeAventura) {
  if(idade >= 10) {
    if(idade >= 14) {
      return "O menino que descobriu o vento";
    } else {
      if(idade >= 12) {
        if(gostaDeFantasia || gostaDeAventura) {
          return "Homem-aranha: no aranhaverso";
        } else {
          return "Ladrões de bicicleta";
        }function geraRecomendacao(idade, gostaDeFantasia) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if (gostaDeFantasia) {
                return "As aventuras de pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if (gostaDeFantasia) {
            return "A viagem de chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}function geraRecomendacao(idade, gostaDeFantasia) {
  if (idade >= 10) {
    if (idade >= 14) {
      return "O menino que descobriu o vento";
    } else {
      if (idade >= 12) {
        return "Ladrões de bicicleta";
      } else {
        if (gostaDeFantasia) {
          return "As aventuras de pi";
        } else {
          return "Depois da chuva";
        }
      }
    }
  } else {
    if (gostaDeFantasia) {
      return "A viagem de chihiro";
    } else {
      return "O feitiço do tempo";
    }
  }
}function geraRecomendacao(idade, gostaDeFantasia) {
  if(idade >= 10) {
    if(idade >= 14) {
      return "O menino que descobriu o vento";
    } else {
      if(idade >= 12) {
        if(gostaDeFantasia) {
          return "Homem-aranha: no aranhaverso";
        } else {
          return "Ladrões de bicicleta";
        }
      }
    }
  }
}let campoIdade;
let campoFantasia;
let campoAventura;

function setup() {
  createCanvas(800, 400);
  createElement("h2", "Recomendador de filmes");
  createSpan("Sua idade:");
  campoIdade = createInput("5");
  campoFantasia = createCheckbox("Gosta de fantasia?");
  campoAventura = createCheckbox("Gosta de aventura?");
}function draw() {
  background("white");
  let idade = campoIdade.value();
  let gostaDeFantasia = campoFantasia.checked();
  let gostaDeAventura = campoAventura.checked();
  let recomendacao = geraRecomendacao(idade, gostaDeFantasia, gostaDeAventura);

  fill(color(76, 0, 115));
  textAlign(CENTER, CENTER);
  textSize(38);
  text(recomendacao, width / 2, height / 2);
}function geraRecomendacao(idade, gostaDeFantasia) {
  if (idade >= 10) {
    if (idade >= 14) {
      return "O menino que descobriu o vento";
    } else {
      if (idade >= 12) {
        if(gostaDeFantasia) {
          return "Homem aranha: no aranhaverso";          
        } else{
         return "Ladrões de bicicleta";
        }
      } else {
        if (gostaDeFantasia) {
          return "As aventuras de pi";
        } else {
          return "Depois da chuva";
        }
      }
    }
  } else {
    if (gostaDeFantasia) {
      return "A viagem de chihiro";
    } else {
      return "O feitiço do tempo";
    }
  }
}function geraRecomendacao(idade, gostaDeFantasia, gostaDeAventura) {
  if (idade >= 10) {
    if (idade >= 14) {
      return "O menino que descobriu o vento";
    } else {
      if (idade >= 12) {
        if(gostaDeFantasia || gostaDeAventura) {
          return "Homem aranha: no aranhaverso";          
        } else{
         return "Ladrões de bicicleta";
        }
      } else {
        if (gostaDeFantasia) {
          return "As aventuras de pi";
        } else {
          return "Depois da chuva";
        }
      }
    }
  } else {
    if (gostaDeFantasia) {
      return "A viagem de chihiro";
    } else {
      return "O feitiço do tempo";
    }
  }
}let idade = 15;
let possuiPermissao = true;

function verificaIdade(idade, possuiPermissao) {
  if (idade >= 18 || possuiPermissao) {
    return "Você pode dirigir!";
  } else {
    return "Você não pode dirigir.";
  }
}function verificaAcesso() {
  ___ (usuario === "prof" ___ usuario === "professor(a)") {
    return "Bem-vindo(a), professor(a)!";
  } ___ {
    ____ "Bem vindo(a) estudante.";
  }
}let campoOrcamento;
let campoPraia;
let campoCidadeGrande;

function setup() {
  createCanvas(800, 400);
  createElement("h2", "Recomendador de lugares para conhecer");
  createSpan("Quanto você pode gastar R$");
  campoOrcamento = createInput("1000");
  campoPraia = createCheckbox("Gosta de Praia?");
  campoCidadeGrande = createCheckbox("Gosta de cidades grandes?");
}

function draw() {
  background("white");
  let orcamento = parseFloat(campoOrcamento.value());
  let gostaDePraia = campoPraia.checked();
  let gostaDeCidadesGrandes = campoCidadeGrande.checked();
  let recomendacao = geraRecomendacao(orcamento, gostaDePraia, gostaDeCidadesGrandes);

  fill(color(76, 0, 115));
  textAlign(CENTER, CENTER);
  textSize(38);
  text(recomendacao, width / 2, height / 2);
}

function geraRecomendacao(orcamento, gostaDePraia, gostaDeCidadesGrandes) {
  if (orcamento >= 1000) {
    if (gostaDePraia) {
      return "Rio de Janeiro - ótimo para quem gosta de praias e cidade grande.";
    } else if (gostaDeCidadesGrandes) {
      return "São Paulo - ideal para quem gosta do agito das grandes cidades.";
    } else {
      return "Gramado - perfeito para quem busca um lugar tranquilo e charmoso.";
    }
  } else if (orcamento >= 500) {
    if (gostaDePraia) {
      return "Búzios - excelente para quem quer praias lindas com orçamento moderado.";
    } else if (gostaDeCidadesGrandes) {
      return "Curitiba - uma grande cidade com muitos parques e um custo de vida razoável.";
    } else {
      return "Ouro Preto - cidade histórica com muita cultura e beleza.";
    }
  } else {
    if (gostaDePraia) {
      return "Maragogi - conhecida como o Caribe brasileiro, com preços mais acessíveis.";
    } else if (gostaDeCidadesGrandes) {
      return "Belo Horizonte - cidade grande com muita cultura e opções de lazer econômicas.";
    } else {
      return "Petrópolis - cidade com clima de montanha e muita história.";
    }
  }
}
