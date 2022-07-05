---
marp: true
draft: true
inlineSVG: true

---
<!-- backgroundColor: #D9D9D9 -->
<!-- color: black -->




<style>

*{
    font-size: 35px;
}

</style>




<h1> A Esfera Pública na Era da Informação: </br> Estudando a Câmara dos Deputados a partir da Atuação Parlamentar e do Uso Político do Twitter </h1>

Defesa de dissertação - 22 de março de 2022

Lorenzo Leuck

---

Esta dissertação compara a atividade parlamentar de deputados federais à maneira que estes se posiconam e interagem no Twitter. Isto é feito por dois caminhos: um técnico e um teórico.
<br>

**Palavras-chave: Comunicação, política, mídias sociais, análise de dados**

---

<!-- _backgroundColor: #71818F -->

No âmbito teórico, é estudada a integração da democracia brasileira com a novas tecnologias digitais. Métodos de revisão bibliográfica e análise documental serão utilizados para abordar: política, tecnologia, internet e mídias sociais. Estes temas são contemplados a partir de sua conexão com o conceito de esfera pública, como proposto pelo filósofo Jürgen Habermas.



---
A Esfera Pública normalmente se refere à espaços de discussões, formais ou informais, que fazem intermédio entre a sociedade civil e o estado. 

Habermas (1989) faz uma análise sociológica e histórica do conceito, apontando sua origem, consolidação e decadência ao longo de séculos.  

Esta dissertação trabalha com a ideia de que as mídias sociais levaram este conceito a uma nova categoria histórica. 

---

<!-- _backgroundColor: #71818F -->

De acordo com o relatório mundial do We are Social (2021), 4.20 bilhões de pessoas usam mídias sociais atualmente. Araújo (2017) põe esta situação em termos práticos: é inimaginável ler notícias, interagir com os outros ou tomar decisões sem estar conectado a estas redes.

---
A influência deste processo na política fica cada vez mais evidente. Em 2018, Jair Bolsonaro foi eleito presidente a partir de uma campanha voltada a estas plataformas. Centenas de deputados federais fizeram o mesmo.

Saber quem são estes políticos, e se há relação entre o trabalho da Câmara com suas declarações nas mídias sociais foi a motivação principal deste trabalho.

---
<!-- _backgroundColor: #71818F -->

Por um viés técnico, esta obra representa a multidimensionalidade da atuação parlamentar a partir de técnicas de coleta, análise e visualizações de dados, desenvolvidas e documentaradas majoritariamente na linguagem de programação python. 

Faz parte do corpus do pesquisa: dados públicos da Câmara dos Deputados, Tribunal Superior de Contas e Twitter, relativos à parlamentares que submeteram proposições e publicaram tweets no ano de 2020. 

---

<h2 style="text-align:center">Conexões entre as bases de dados</h2>

<div>
    <img src="dbs.png" width="1500"/>        
</div>


---

<h2 style="text-align:center">Perfis Parlamentares</h2>

Características predominantes da 56ª legislatura trazem o seguinte perfil: homem (84,80%), branco (75,63%), entre 40 e 55 anos (40,54%), casado (69,98%), com ensino superior completo (55,36%) e ocupação anterior de deputado (44,25%). 

Dos 33 partidos registrados atualmente, 24 possuem deputados eleitos. O PT e o PSL estão empatados no topo com 53 deputados (10,33% cada). A distribuição do espectro ideológico é menos uniforme, visto que 273 deputados (53,22%) são de direita, 142 (27,68%) de esquerda e 98 (19,10%) de centro.

---

<h2 style="text-align:center">Perfil por Estado</h2>

|            | Bancada Gaúcha         |
|------------------------|---------------------------|
| Gênero              | Homem   (90.32%)         |   |
| Cor/Raça               | Branca   (100.0%)         |
| Faixa etária           | Entre 55 e 70   (41.94%)  |
| Estado Civil           | Casado   (58.06%)         |
| Escolaridade           | Superior   (45.16%)       |
| Ocupação anterior      | Deputado   (54.84%)       |
| Partido                | PT   (16.13%)             |
| Ideologia              | Direita   (45.16%)        |
| Tem Twitter            | Sim   (93.55%)            |
| Reeleição              | Sim   (58.06%)            |
| Declaração de bens     | Até R$407 mil  (G4)       |
| Votos                  | Até 115 mil  (G2)         |
| Seguidores no Twitter  | Até 4 mil e 200  (G3)     |
| Número de Tweets       | Até 114 mil e 966  (G1)   |


---






<h2 style="text-align:center">Consistência Temática</h2>

<!-- _backgroundColor: #76ABA7 -->





|          Deputado Acácio Favacho           |                                                                                                                                                                                                                                                                |
|--------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| 12 Proposições parlamentares, 161 palavras | lei federal enfrentamento emergencia saude publica internacional espii autorizacao estado ente federado distrito municipio aplicacao recursos leilao petroleo regime cessao onerosa combate pandemia coronavirus social fundo fiscalizacao telecomunicacoes... |
| 24 Tweets, 171 palavras                    | desafios luta assegurar melhorias amapa juntos povo amapaense viva democracia parabenizo especial macapaenses exerceram domingo desejo gestao conjunta bancada federal virtude apagao mincomunicacoes anatel determinaram lider pros camara deputados...       |
| Interseção: 13 palavras                    | plano publica recuperacao combate suspensao pandemia especial federal saude auxilio emergencial lei rescisao                                                                                                                                                   |


---
<i>
Quão consistentes são os discursos dos deputados federais no Twitter, se comparados às suas proposições parlamentares?</i>
<br>
<p style="text-align: center"> Número de palavras-chave presentes nos dois campos
<br>/ Número de palavras-chave nas proposições</p>
<b style="text-align: center">Exemplo anterior</b>
<p style="text-align: center"> (13/161) * 100 = 8.07% </p>


---

<h1 style="text-align: center"> No quadro geral, o nível de consistência temática chegou a 31,97%. Já na bancada do <br> Rio Grande do Sul, 31,07%. </h1>


---
<!-- _backgroundColor: #D6E8D5 -->

<h2 style="text-align:center">Estados por índice de Consistência Temática</h2>

<div style="overflow:scroll;">
    <img src="ct2.jpg" width="1500"/>        
</div>


---

<!-- _backgroundColor: #D6E8D5 -->

<h2 style="text-align:center">Panorama das Proposições Parlamentares</h2>

<div style="overflow:scroll;">
    <img src="pls.jpg" width="1500"/>        
</div>


---


<!-- _backgroundColor: #D6E8D5 -->

<h2 style="text-align:center">Panorma do discurso no Twitter - Geral</h2>

<div style="overflow:scroll;">
    <img src="tag-twitter.jpg" width="1500"/>
</div>

---



<!-- _backgroundColor: #D6E8D5 -->

<h2 style="text-align:center"> Tagclouds de Consistência Temática - Quadro geral x RS </h2>

<div style="overflow:scroll;">
    <img src="ct3.jpg" width="1500"/>        
</div>


---

<h2 style="text-align:center">Formação de Redes</h2>


A divulgação de proposições parlamentares no twitter representou cerca de 1% da base de dados. Para apontar a relação entre as redes de trabalhos legislativos e as formadas a partir de tweets, este trabalho se valeu de técnicas e conceitos da Análise de Redes Sociais (ARS).

---


<h2 style="text-align:center">Rede de coautoria de proposições parlamentares - RS</h2>

<div style="overflow:scroll;">
    <img src="rede-pls.png" width="1000"/>        
</div>

---

<h2 style="text-align:center">Rede de interações no Twitter - Geral</h2>
<div style="overflow:scroll;">
    <img src="rede-tw.png" width="1500"/>        
</div>

---




<b>Considerações finais</b>

A partir dos resultados encontrados, constatamos que a maneira como os os deputados federais agem no Twitter não difere muito a de influenciadores digitais. Isso é um problema, se levarmos em consideração uma contribuição da ARS: nós centrais de uma rede tendem a concentrar o número de arestas, devido a um fenômeno chamado de “conexão preferencial". 

Neste caso, quando um deputado obtém um público expressivo, e consegue antecipar razoavelmente suas reações a conteúdos amplamente difundidos na rede, a tendência é que continue crescendo independente se segue ou não as atribuições de transparência do cargo.

---

<!-- _backgroundColor: #71818F -->

É importante destacar ainda que a Esfera pública não deve ser resumida ao twitter, ou qualquer outra plataforma. A aplicação deste conceito perpassa tanto as mídias sociais com outros sistemas sociotécnicos latentes, à medida que cultura, economia e política são digitalizadas.

Portanto, a busca por transparência e maior participação política deve ser transversal a academia, imprensa e a sociedade civil, para desenvolver não só inteligência, mas sensibilidade e autoconhecimento coletivo que fortaleçam o laço social e o garantam funcionamento das instituições.


---

Esta dissertação é uma fração mínima deste campo de pesquisa. O esforço à documentação das técnicas utilizadas esteve presente da conceitualização a conclusão do trabalho. Acredita-se que a reprodutibilidade dos resultados encontrados facilitará a validação, refutação ou apropriação destes em outros contextos, fomentando a análise científica de fenômenos comunicacionais. 



---
<!-- _backgroundColor: #71818F -->

<p style="font-size:150px; text-align:center">Obrigado!<p>