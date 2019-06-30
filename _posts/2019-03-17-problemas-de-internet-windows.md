---
layout: page
title: "Dica para problemas de internet no Windows."
subtitle: ""
date: 2019-03-19
categories: ["instadrops"]
---

*Texto originalmente publicado no Instagram em 17 de março de 2019.*

Hoje vou dar uma dica bem simples mas que aparentemente nem todo mundo que usa Windows e tem problemas com a internet sabe. Tem horas que aquele sinalzinho amarelo com um ponto de exclamação simplesmente aparece sem razão aparente junto com o nosso sinal de internet e dá aquela vontade de gritar né... Se a gente coloca na solução de problemas do Windows raramente ele soluciona alguma coisa 🙄 Geralmente quando isso acontece comigo e eu constato que não tem problema de conexão de algum fio no roteador ou temporal na região, eu uso três comandos simples no cmd, a linha de comando / terminal / prompt / chame como quiser do Windows.

Digite ipconfig /release e logo em seguida ipconfig /renew. Com isso você força o PC a fazer uma solicitação de um novo número de IP. 
Também uso (mais do que o release e renew na verdade) o ipconfig /flushdns. Esse comando limpa o DNS Resolver cache, já que geralmente o DNS é que dá mais probleminhas.

1. Muita gente fala sobre abrir o Executar (tecla do Windows + R) e digitar CMD para abrir o terminal, e isso funciona em versões antigas, mas saiba que no Windows 10 é só digitar cmd na própria caixa de pesquisa do menu Iniciar e ele já te sugere o prompt! Outra forma que funciona no Windows 8 em diante é tecla do Windows + X para abrir um menu gráfico de ferramentas administrativas, que incluem o terminal comum, terminal de administrador e até mesmo o Executar.

2. Esses três comandos também podem ser executados diretamente no Executar! Um de cada vez, é claro. Mas eu gosto de fazer no terminal para ler com calma o que foi feito.

