# Capacitores e Dielétricos

![capacitores](https://user-images.githubusercontent.com/118854908/206873316-529cc20a-9dfe-4d9e-a1d4-c06fed1c1b91.jpeg)


  <p align="justify">
  Um capacitor é um dispositivo que armazena energia potencial elétrica e carga elétrica. Para fazer um capacitor, basta colocar um isolante entre dois condutores. Para armazenar energia nesse dispositivo, é necessário transferir carga de um condutor para o outro, de modo que um deles fique com uma carga negativa, e outro fique com a mesma carga, mas de sinal positivo. 
  </p>

  
  Para um capacitor em particular, a razão entre a carga acumulada em cada condutor e a diferença de potencial entre os condutores é uma constante, chamada de capacitância.
  </p>
  
  <p align="justify">
  A capacitância depende das dimensões, das formas dos condutores e do material (caso exista) existente entre eles. Em comparação ao caso no qual existe somente vácuo entre os condutores, a capacitância torna-se maior quando há um material isolante (ou dielétrico) entre eles.
  </p>
 
 ### Capacitores
 
  * Sistema constituído por dois condutores separados por um isolante.
  * É um dispositivo usado nos circuitos para armazenamento de eneriga potencial elétrica através do confinamento do campo elétrico;
  * Dois condutores com cargas iguais e opostos separados por uma distância "d" e com uma diferença de potencial V entre eles;
  * Dois condutores não podem estar em contanto um com o outro.


### Capacitância

  <p align="justify">
  Como as placas do capacitor são condutoras, elas formam superfícies equipotenciais.
  </p>
  
  Superfícies equipotenciais são superfícies de um campo elétrico, onde todos os pontos apresentam mesmo potencial elétrico, ou seja, suas linhas de força são sempre perpendiculares a sua superfície.[^1]
  
  
[^1]: ANJOS, Talita Alves dos. Superfícies Equipotenciais. **Brasil Escola**. Disponível em: https://brasilescola.uol.com.br/fisica/superficies-equipotenciais.htm. Acesso em 10 dez. 2022.

  >  As superfícies equipotenciais fazem parte de um campo elétrico, onde cada ponto possui o mesmo potencial elétrico. São usadas na descrição do campo elétrico para várias aplicações, como análise de circuitos elétricos, análise de equipamentos elétricos, análise de sistemas de aquecimento, entre outras. 
  
  <p align="justify">
  As cargas nas placas do capacitor são proporcionais à diferença de potencial entre elas, ou seja:
  </p>
  
  $$Q = CV$$
  
  <p align="justify">
  A capacitância é a razão entre a carga e a diferencia de potencial:
  </p>
  
  $$C = \frac{Q}{V}$$

  <p align="justify">
  A constânte $C$ depende apenas da geometria do capacitor.
  </p>
  
 ### Unidade de Medida
 
  <p align="justify">
  No sistema internacional (SI), a unidade de medida utilizada para a capacitância é o Farad (F). Onde:
  </p>
  
  1 farad = 1F = 1coulomb/1volt = 1C/1V
  
  ### Esquema de cálculo para a Capacitância
  
   <p align="justify">
  Conhecendo a geometria do capacitor, e supondo que exista carga nas placas, seguiremos os seguintes passos: 
  
  1. Calcular o campo elétrico entre as placas ( Lei de Gauss), usando a equação:

$$\varphi = \oint \vec{E}(\vec{r})\cdot \hat{n}dA = \frac{q_{int}}{\varepsilon _{0}}$$
  
  2. Conhecendo o campo elétrico, calcular a diferença de potencial (ddp) entre as placas usando a euqação:
  
$$V = V_{f} - V_{i} = -\int \vec{E}(\vec{r})\cdot \hat{n}dl$$
  
  3. Calcular a capacitância usando a equação:
  
$$C = \frac{Q}{V}$$
  
### Suposições para simplificar o cálculo da Capacitância
  
  1. A superfície gausseana deverá ser tal que o módulo de $\vec{E}$ seja constante e que $\vec{E}$ e $\hat{n}$ sejam paralelos. Por conveniência, traçar a gausseana de forma a envolver a placa positiva: 
  
$$EA = \frac{q}{\varepsilon _{0}}$$
  
  2. No cálculo da ddp, escolher a trajetória que acompanhe uma linha de campo elétrico que vai de + para -. Nesse caso, $E$ e $dl$ sempre irão apontar na mesma direção, então $V_{f}-V_{i} < 0$, $V_{f}-V_{i} = -V$. Em módulo, a ddp entre as placas será de:
  
$$V = \int_{+}^{-}Edl$$
  
  

