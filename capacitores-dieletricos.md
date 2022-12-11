# Capacitores e Dielétricos

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
  
### Associação de Capacitores
#### Em paralelo

  * Capacitores são ligados de maneira a estarem submetidos à mesma ddp. As placas são conectadas por um fio condutor, constituindo uma superficie equipotencial;
  * Em uma ligação em paralelo, a diferença de potencial é a mesma através de todos os capacitores;
  * Todas as placas estão ligadas ao terminal da fonte.
  
  <p align="justify">
  Quando analisamos um circuito que contém capacitores em paralelo, todos os capacitores tem a mesma diferença de potencial e uma quantidade de carga, portanto, temos:
  </p>
  
$$q_{1} = C_{1}V$$

$$q_{2} = C_{2}V$$

$$q_{3} = C_{3}V$$
  
  <p align="justify">
  Dessa forma, podemos dizer que:
  </p>
  
$$q = (q_{1} + q_{2} + q_{3})V$$

  <p align="justify">
  A carga total do circuito de capacitores é igual a capacitância equivalente vezes a diferança de potencial:
  </p>
  
$$q = C_{eq})V$$
  
  <p align="justify">
  A capacitância equivalente do capacitor numa associação de capacitores em paralelo é a soma das capacitâncias:
  </p>
  
$$C_{eq} = (C_{1} + C_{2} + C_{3})$$

  <p align="justify">
  ou
  </p>

$$C_{eq} = \sum_{i}^{}C_{i}$$

  $\textcolor{red}{\text{Observação:}}$ Para os capacitores em paralelo, a capacitância do capacitor equivalente é sempre maior do que as capacitâncias individuais.

#### Em série

  * Capacitores são conectados em série por meio de fios condutores *a* e *b*.
  * A diferença de potencial não é a mesma em cada capacitor, será a soma de todos eles.

  <p align="justify">
  Num esquema, temos uma bateria com três capacitores, a placa do capacitor $C_{1}$ está ligada no terminal negativo da fonte, e placa do capacitor $C_{3}$ está ligada ao terminal positivo. O capacitor $C_{2}$ não está conectado à fonte, ele se conecta com a fonte a partir dos outros capacitores.
  </p>

  <p align="justify">
  A diferença de potencial fornecida pela bateria é distruibuída entre os capacitores, logo:
  </p>
  
 $$V = V_{1} + V_{2} + V_{3}$$

  <p align="justify">
  Sabemos que:
  </p>

$$V_{1} = \frac{q}{C_{1}}$$

$$V_{2} = \frac{q}{C_{2}}$$

$$V_{3} = \frac{q}{C_{3}}$$

  <p align="justify">
  Portanto, podemos escrever que:
  </p>

$$V = \frac{q}{C_{1}} + \frac{q}{C_{2}} + \frac{q}{C_{3}}$$

$$V = q\left ( \frac{1}{C_{1}} + \frac{1}{C_{2}} + \frac{1}{C_{3}} \right )$$

  <p align="justify">
  Onde $V$ é a diferença de potencial total. Com isso, concluímos que:
  </p>

$$V = \frac{q}{C_{eq}}$$

  <p align="justify">
  onde:
  </p>

$$\frac{1}{C_{eq}} = \frac{1}{C_{1}} + \frac{1}{C_{2}} + \frac{1}{C_{3}}$$

 <p align="justify">
  Dessa forma, vemos que o inverso da capacitância equivalente é a soma do inverso de cada uma das capacitâncias.
  </p>
  
  $\textcolor{red}{\text{Observação:}}$ A capacitância equivalente é menor do que a capacitância dos capacitores.

### Energia armazenada no Campo Elétrico

  <p align="justify">
  A energia potencial armazenada em um capacitor carregado é exatamente igual ao trabalho realiazado para carregá-lo. Um agente externo deve realizar trabalho para carregar um capacitor. Este trabalho fica armazenado sob a forma de energia potencial na região do campo elétrico entre as placas.
  </p>

  <p align="justify">
  Podemos determinar a $U$ (energia potencial) de um capacitor carregado, calculando o $W$ (trabalho) necessário para carregá-lo. Suponha que, depois do processo, a carga final seja $Q$ e a diferença de potencial $V$.
  </p>

  <p align="justify">
  Supondo que no capacitor haja $+q$ e $-q$ armazenadas nas placas de um capacitor. A bateria vai realizar um trabalho de pegar mais um $dq$ e levar para a outra carga, ou seja, a bateria (agente externo) vai realizar um trabalho infinitesimal que é igual a diferença de potencial entre as placas.
  </p>
  
  <p align="justify">
  Temos que:
  </p>
  
$$dw = Vdq = \frac{q}{c}dq$$

$$w = dw = \int \frac{q}{C}dq$$

 <p align="justify">
 Os parâmetros de integração vão desde a carga 0 (capacitor descarregado) até a carga total $Q$. Logo: 
 </p>

$$w = dw = \int_{0}^{Q} \frac{q}{C}dq$$

$$w = \frac{1}{C}\int_{0}^{Q} qdq$$

$$w = \frac{1}{C} \left [\frac{Q^2}{2} - \frac{0^2}{2} \right]$$

$$w = \frac{Q^2}{2C}$$

 <p align="justify">
 Como $Q = CV$, temos que: 
 </p>

$$U = \frac{C^2V^2}{2C}$$

$$U = \frac{1}{2}CV^2$$

  Portanto, calculamos a energia potencial elétrica armazenada no campo elétrico.

### Dielétricos

  <p align="justify">
  Quando preenchemos o espaço entre as placas de um capacitor com um dielétrico, que é um material isolante como plástico ou óleo mineral, o que acontece com a capacitância? O cientista inglês Michael Faraday foi o primeiro a investigar o assunto, em 1837. Faraday constatou que a capacitância era multiplicada por um fator numérico $K$, que chamou de constante dielétrica do material isolante. Por definição, a constante dielétrica do vácuo é igual à unidade. Como o ar é constituído principalmente de espaço vazio, sua constante
dielétrica é apenas ligeiramente maior que a do vácuo.
  </p>

  Quase todos os capacitores possuem entre suas placas condutoras um material isolante, ou dielétrico. Colocar um dielétrico sólido entre as placas de um capacitor possui três objetivos. Em primeiro lugar, resolve o problema mecânico de manter duas grandes placas metálicas separadas por uma distância muito pequena, sem que ocorra contato entre elas. Em segundo lugar, usando um dielétrico torna-se possível aumentar a diferença de potencial máxima entre as placas. Em terceiro lugar, a capacitância de um capacitor com dimensões fixas, quando existe um dielétrico entre as placas, é maior que a capacitância do mesmo capacitor quando há vácuo entre as placas. [^2]
  
[^2]:YOUNG, HUGH D.; FREEDMAN, ROGER A. Física III: Eletromagnetismo. 12ª Edição. 2003.

  > Boa parte dos capacitores apresentam um material isolante ou dielétrico entre as suas placas, e o fato desse dielétrico estar enttre as placas do capacitor possui três objetivos. O primeiro objetivo é garantir que as placas do capacitor fiquem bem separadas, evitando assim que haja curtos-circuitos entre elas. Isso é importante para garantir que o capacitor funcione corretamente e não apresente problemas de funcionamento. O segundo objetivo é aumentar a diferença de potencial máxima entre as placas. Isso é possível porque os dielétricos são materiais que têm baixa condutividade elétrica, o que significa que eles permitem que a diferença de potencial entre as placas seja muito maior do que seria possível com o vácuo entre as placas. O terceiro objetivo é aumentar a capacitância do capacitor. A capacitância de um capacitor é a medida de sua capacidade de armazenar cargas elétricas. Quando um dielétrico é colocado entre as placas de um capacitor, a capacitância do capacitor aumenta, pois o dielétrico permite que mais cargas elétricas sejam armazenadas nas placas. Isso é importante porque um capacitor com maior capacitância pode armazenar mais energia elétrica e, portanto, pode ser usado em aplicações que exigem uma grande quantidade de energia.

  <p align="justify">
  Um eletrômetro sensível é um dispositivo que permite a medida da diferença de potencial entre dois condutores, sem que haja fluxo de carga apreciável de um condutor para o outro. Se temos um eletrômetro conectado às placas de um capacitor carregado, sendo $Q$ o módulo da carga de cada placa e $V_{0}$ a diferençade potencial. Quando inserimos entre as placas um dielétrico descarregado, como vidro, parafina ou poliestireno, o experimento mostra que a diferença de potencial diminui para um valor menor $V$. Quando removemos o dielétrico, a diferença de potencial retorna a seu valor original $V_{0}$, o que mostra que as cargas originais do capacitor não se alteram.
  </p>

  <p align="justify">
  A capacitância original $C0$ é dada por: 
  </p>
  
$$C_{0} = \frac {Q}{V_{0}}$$
  
  <p align="justify">
  e a capacitância quando o dielétrico está presente é dada por:
  </p>
  
$$C = \frac {Q}{V}$$
  
  <p align="justify">
  A carga $Q$ é a mesma nos dois casos e, como $V$ é menor que $V_{0}$, concluímos que a capacitância $C$ com o dielétrico é maior que $C_{0}$. Quando o espaço entre as placas se encontra completamente preenchido com o dielétrico, a razão $C$ sobre $C_{0}$ (que é igual à razão entre $V_{0}$ e $V$) denomina-se constante dielétrica K do material:
  </p>
  
$$K = \frac {C}{C_{0}}$$

  <p align="justify">
  Quando a carga é constante, $Q = C_{0}/V_{0} = CV = C/C_{0} = V_{0}/V$. Nesse caso,
  </p>
  
$$V = \frac {V_{0}}{K}$$

  <p align="justify">
  Quando o dielétrico está presente, a diferença de potencial para uma carga fixa $Q$ é reduzida por um fator igual a $K$. A constante dielétrica $K$ é um número puro. Como $C$ é sempre maior que $C_{0}$, $K$ é sempre maior que 1.
  </p>


