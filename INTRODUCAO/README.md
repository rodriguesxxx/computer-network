# INTRODUÇÃO A REDES

<img src="https://tribunademinas.com.br/wp-content/webp-express/webp-images/uploads/2020/02/post-3.jpg.webp" />

Conjunto de `computadores` e outros `dispositivos` conectados entre si capazes de `trocar informações`.

Esses `computadores`ou `dispositvos` são conectados a um `Ponto de Acesso`, a partir dele toda a `informação`é trafegada.

## TOPOLOGIA DE REDES

- ### Barramento (Bus)

<img src="http://1.bp.blogspot.com/-7gMidEvGPzY/UJPebu0KJpI/AAAAAAAAAEc/2Kai4qunjzo/s400/barramento1.png" />


É uma `topologia` antiga, onde havia um único caminho para o tráfego de dados, no formato de  cabo `coaxial`. Todos os `nós`(pontos de redes) são conectados a esse mesmo `cabo` para `troca de informação` pela rede.

- #### Vantagens
	As redes de barramento tem como `vantagem` a rápida `implementação`e `expansão`.

- #### Desvantagens
	- Se um cabo `romper` - bye bye rede. 
	- Dificuldade em  achar `defeitos` - É muito difícil determinar o defeito, caso o cabo de `rompa`.
	- Número de `estações limitadas` - Quanto mais `nós`, maior probabilidade de ocorrer instabilidade no tráfego de `dados`.


- ### Anel (Ring)

<img src="https://www.fibracem.com/wp-content/uploads/2023/09/anel.jpg" />

Nesse formato de rede o usuário `1` se conecta ao usuário `2`, o `2`se conecta ao `3`e assim por diante, fomando um `anel`. Isso significa que se a `conexão`do usuário `2`ao `3` cair, a conexão do `1`ao `2` permanecera `intacta`, e do `4` ao `3`também, pois apenas o tráfego do `2` ao `3` caiu.

- #### Vantagens
	 - Mais eficiente na `transmissão de dados`.
	 - O número de pessoas `não` impacta o desempenho da rede.

- #### Desvantagens
	- Mais `vulnerabilidade` com a falta de um dispositivo.
	- Para funcionar, TODOS os dispositivos precisam estar ativos.


- ### Estrela (Star)

<img src="https://www.gerenciatec.com.br/wp-content/uploads/2022/07/2-2.jpg" />


Nesse formato cada `usúario`se conecta a um `nó`central: `roteador`, `switch`, `hub`. Que se conecta através de uma cabo individual. É a `principal` topologia utilizada atualmente.

- #### Vantagens
	 - Rápida `instalação`.
	 - Cabeamento de `baixo custo`.
	 - Expansão `rápida` e `simples`.
- #### Desvantagens
	 - Limitação de `distância` entre o `nó`e o `Ponto de Acesso`.

Acho que todo `programador`deve ter esse conhecimento `básico em redes`.
