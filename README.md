[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tro2Z-6l)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23171278&assignment_repo_type=AssignmentRepo)
# Lab 01: Lógica de Programação com Blockly 🐢

Bem-vindo(a) à sua atividade prática de Lógica Computacional! Siga os passos abaixo para completar o desafio.

**Nome do Aluno:**   Pedro Alencar Gonçalves
**Matrícula:** 20261100058
---

## 🎯 Objetivo
Demonstrar capacidade de resolução de problemas algorítmicos completando o **Nível 10** do jogo da Tartaruga (Turtle). 

## 📝 Instruções

**Passo 1: Jogue e Resolva**

Acesse o jogo da Tartaruga no [Blockly Games](https://blockly.games/turtle) e complete as etapas até vencer o **nível 10**.

**Passo 2: Registre sua Solução**

Tire um screenshot (captura de tela) da sua solução final (mostrando os blocos que você usou para passar do nível 10). Faça o upload (envio) dessa imagem **dentro da pasta /imagens** que já existe neste repositório.

**Passo 3: Explique sua Estratégia**

Escreva um pequeno texto explicando qual foi a sua linha de raciocínio e a estratégia que você usou para resolver o nível 10.
*(Exemplo: "Criei uma função para desenhar uma estrela, depois usei um loop para repetir essa função 3 vezes girando 120 graus.")*

**Passo 4: Pergunta Desafio**

Olhando para os blocos que você usou para resolver o jogo no nível 10, imagine que o problema mudou. A sua nova missão agora é desenhar um **hexágono regular** (uma figura geométrica de 6 lados iguais) e repetir esse hexágono **4 vezes**, formando um padrão circular (como as pétalas de uma flor).

**Sem precisar montar os blocos** no jogo, responda por escrito:
* **A)** Quantas repetições o seu loop principal (que desenha o hexágono) precisaria ter e qual seria o ângulo (em graus) que a tartaruga deve virar a cada linha desenhada?
* **B)** Depois de desenhar um hexágono completo, qual deve ser o ângulo de giro (em graus) antes de começar a desenhar o próximo hexágono, para que os 4 fiquem distribuídos igualmente em um círculo completo?
* **C)** Explique brevemente qual foi a lógica (ou o cálculo) que você usou para descobrir os ângulos das questões A e B.

---

## ✍️ Suas Respostas

*(Edite este arquivo e escreva suas respostas dos Passos 3 e 4 aqui embaixo. Lembre-se de colocar a imagem do Passo 2 dentro da pasta **/imagens** deste repositório)*


## 2. Evidência Visual (Screenshot)
*Suba o screenshot da sua solução final (onde aparece "Você resolveu este nível!") para a pasta **/imagens** deste repositório.*

## 3. Estratégia Utilizada
*Explique com suas palavras como você resolveu o problema. Qual foi a lógica?*
Para resolver o nível 9 ( último) eu utilizei a mesma função em que havia utilizado no nível 8 para desenhar as estrelas, que consiste em um loop que se move para frente e para direita, a fim de desenhar uma estrela e, dentro desse loop, possui um segundo loop que move a caneta para o começo das outras estrelas e as completa com o primeiro loop.
Depois, para preencher a "lua", inicialmente precisei completar o círculo todo de branco repetindo o processo de se  movimentar para frente e para trás com uma inclinação de 1º, com um loop de 360 repetições. Por fim, setei a cor para o preto, virando a "tartaruga" para uma inclinação de 120º a direita e avançando-a em 20 unidades, a fim de realizar outro loop de frente e trás, preenchendo um círculo que cobre a parte necessária para transformar-se em uma "lua".

## 4. Desafio:
**A)** São 6 loops para desenhar um hexágono e o ângulo em que a tartaruga deve virar é de 60º.
  
**B)** O ângulo de giro deve ser de 90º
  
**C)** Para o ângulo da questão A, eu me recordei do ângulo utilizado para montar um pentágono (72º) e então percebi que para qualquer polígono, seu ângulo externo é igual a 360º. Como o objetivo era um hexágono, bastava dividir esse valor por 6 (números de lados), resultando em 60º.
Para o ângulo da questão C, seguindo a lógica de um círculo completo possuir 360º e termos 4 figuras, dividi 360 por 4, resultando em 90º.

---
