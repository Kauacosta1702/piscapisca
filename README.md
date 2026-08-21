## Nome: Kauã Costa de Oliveira
## Nome: Bruna Rosa Bueno

# Análise de Iluminação no Unity

Documentação prática sobre o comportamento e configurações das luzes em uma cena 3D na *Unity* 

---
<img width="1600" height="764" alt="foto1" src="https://github.com/user-attachments/assets/bb07fc10-f56c-4cd2-b4b5-30e463e15a1b" />


##  Elementos da Cena
* *Plataforma Grid:* Plataforma parecida com um coliseu, dento dois lados o de dentro e o de fora.*
* *Objeto Central:* Existem 2 personagens na cena o gato que se encontra do lado de fora do coliseu e o personagem da  vaca que se encontra internamente .*
* Objeto Suspensos: * Na cena existem 2 objetos suspensos, os dois ovnis, que um esta dentro do coliseu e o outro fora.*

---

## Cena 1

### 1. Directional Light (Luz Global)
* *Tipo:* Directional Light
* *Temperatura:* 5000K (Branco neutro) | *Intensidade:* 2
* *Sombras:* Soft Shadows (Força: 1.0)
* *Efeito:* Ilumina toda a cena de forma uniforme simulando o sol, gerando sombras suaves na plataforma.

---

### 2. Point Light - Alta Intensidade
* *Tipo:* Point Light
* *Cor:* Vermelho | *Intensidade:* 500 | *Range:* 10
* *Sombras:* No Shadows
* *Efeito:* Na cena ele está projetando uma luz intensa e vermelha, a luz se encontra dentro do ovni do lado de fora, onde o brilho é tão intenso que afeta também a luz do objeto do gato*

---

### 3. Point Light - Intensidade Moderada
* *Tipo:* Point Light
* *Cor:* Vermelho | *Intensidade:* 100 | *Range:* 10
* *Sombras:* No Shadows
* *Efeito:* Redução da intensidade para 100, deixando a luz vermelha mais suave e contida no centro da cena, onde afeta parcialmente a parte interna do coliseu onde a luz se encontra tanenm dentro do ovni, mas o ovni que está dentro do coliseu

---

### 4. Spot Light - Holofote Forte
* *Tipo:* Spot Light (Luz Cônica)
* *Cor:* Verde | *Intensidade:* 500 | *Range:* 10
* *Sombras:* No Shadows
* *Efeito:* Foco de luz verde apontado para baixo, criando um círculo vibrante focado no objeto do gato que está sendo abduzido pelo ovni do lado de fora do coliseu. *

---

### 5. Spot Light - Holofote Suave
* *Tipo:* Spot Light
* *Cor:* Verde | *Intensidade:* 200 | *Range:* 10
* *Sombras:* No Shadows
* *Efeito:* Intensidade reduzida para 200, suavizando o brilho verde sobre o personagem da vaca e do chão, a luz também está vindo do ovni de dentro do coliseu.* 

---

## Cena 2

<img width="1600" height="753" alt="foto2" src="https://github.com/user-attachments/assets/35b675e8-18d9-4969-b437-0d3424e2a66f" />

### 1. Directional Light (Luz Global)
* *Tipo:* Directional Light
* *Temperatura:* 9533K (Tom frio | azulado) | *Intensidade:* 10
* *Sombras:* Soft Shadows (Força: 1.0)
* *Efeito:* Ilumina toda a cena de uma forma muito escura, deixando a cena de uma forma alaranjada e escura

---

### 2. Point Light - Alta Intensidade
* *Tipo:* Point Light
* *Cor:* Amarelo |*Intensidade:* 50 | *Range:* 10
* *Sombras:* No Shadows
* *Efeito:* Na cena ele está projetando uma luz suave e amarelada, a luz se encontra dentro do ovni do lado de fora, onde o brilho é tão intenso que afeta também a luz *

---

### 3. Point Light - Intensidade forte
* *Tipo:* Point Light
* *Cor:* Purpura/Magenta | *Intensidade:* 500 | *Range:* 100
* *Sombras:* No Shadows
* *Efeito:* Na cena a luz forte e da cor purpura deixa o ambiente totalemenet diferente, deixando os objetos, como o ovni e a vaca, deixando o interior totalmente diferente.

---

### 4. Spot Light - Holofote Amarelo
* *Tipo:* Spot Light (Luz Cônica)
* *Cor:* Verde | *Intensidade:* 1000 | *Range:* 100
* *Sombras:* No Shadows
* *Efeito:* A luz do spot dentro do coliseu apresenta uma configuração muito mais intensa, entretanto deixando o spot muito acima, deixa a luz com  um estilo de cone, fazendo o objeto da vaca parecendob que esta sendo realmenete abduzida. *

---

### 5. Spot Light - Verde Muito intenso
* *Tipo:* Spot Light
* *Cor:* Verde | *Intensidade:* 100 | *Range:* 100
* *Sombras:* No Shadows
* *Efeito:* A intensidade sendo da mesma configuração do spot anterior, todavia a luz ficou mais perto do objeto do gato, deixando o ambienete extremamente verde intenso, e afetando tambem a vizibilidade do objeto do gato.* 




