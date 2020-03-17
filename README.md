# diferences-python-node, compilado de informações pela web

# NODEJS
Não é coincidência que empresas como LinkedIn, Netflix ou Twitter estejam migrando para o Node.js. 
Existem três fatores principais que contribuem para a escalabilidade do Node.js.: 
1) Ele pode ser facilmente dividido em microsserviços;
2) Possui um modelo baseado em eventos e uma I/O sem bloqueio que ajuda a aproveitar ao máximo a CPU e a memória do computador;
3) A escalabilidade torna o Node uma boa escolha para aplicativos que devem aumentar rapidamente seu número de usuários.

O NodeJS é baseado no mecanismo V8 do Chrome (rápido e poderoso), e é uma das soluções mais rápidas do lado do servidor. Além disso, graças à sua arquitetura orientada a eventos, os servidores NodeJS conseguem processar mais chamadas simultâneas do que outros servidores. Isso torna o NodeJS uma escolha perfeita para todos os aplicativos em tempo real, como bate-papos ou ferramentas de colaboração, e todas as ferramentas que exigem alto desempenho.

Com o uso do Node, o tempo de inicialização da Netflix foi reduzido em 70%! 

No topo da lista, provavelmente devemos colocar aplicativos em tempo real (RTAs), como chats, jogos ou ferramentas de colaboração e aplicativos de streaming. Graças à arquitetura do Node que funciona bem com o protocolo WebSocket, você pode criar mensagens em tempo real com transferência de dados mais rápida e menor latência. Em seguida, temos SPAs (aplicativos de página única) e outros aplicativos da web que precisam ser rápidos e escaláveis. O Node.js também é considerado uma boa opção para as soluções da Internet das Coisas (IoT), pois permite o processamento de várias solicitações simultâneas e um grande número de dispositivos na rede.

Quando se trata de adicionar simultaneidade em um servidor com vários núcleos, a equipe principal do Node trabalha na forma de um módulo de cluster [ref: http://nodejs.org/api/cluster.html]. 

----------------------------------------------------------------------------------------------------------------------------------------
# PYTHON
Quando escolhemos o Python, confiamos nas suas rotinas que podem suspender a execução da operação antes de atingir o retorno e nas ferramentas como Memcached ou NGINX. Equipados com eles, os aplicativos Python são capazes de lidar com migrações de dados, mesmo com a crescente quantidade de dados. 

Se a escalabilidade for uma das suas preocupações, o Python não irá decepcioná-lo. Se for suficiente para o Youtube, Pinterest, Reddit e Dropbox, há uma chance de que seja útil - pelo menos no começo.

O Python se destaca na área de desenvolvimento de IA. Existem algumas razões para isso. Em primeiro lugar, ele tem ótimas bibliotecas para isso: o scikit-learn para lidar com algoritmos básicos de ML, o Tensorflow para trabalhar com aprendizado profundo, configurando, treinando e utilizando redes neurais artificiais com conjuntos de dados maciços, ou PyBrain para redes neurais, aprendizado não supervisionado e de reforço - apenas para mencionar alguns deles. Em segundo lugar, é simples (ao contrário de toda a Inteligência Artificial, que é um campo complicado!). Os processos de Machine Learning contam com algoritmos extremamente complexos e fluxos de trabalho de vários estágios. A simplicidade do Python permite que os desenvolvedores liberem seus recursos mentais para que possam se concentrar na solução dos problemas e na consecução dos objetivos do projeto. Por último mas não menos importante, além do desenvolvimento da IA, o Python é útil quando você cria aplicativos de áudio / vídeo (novamente, graças a bibliotecas dedicadas, como Librosa ou PyAudioAnalysis), aplicativos da Web progressivos ou aplicativos de administração do sistema, aplicativos científicos, soluções de big data e projetos governamentais.

----------------------------------------------------------------------------------------------------------------------------------------
# Conclusão
O NodeJS trabalha muito bem com recursos de memória, quanto o Python trabalha muito bem com recursos de disco.
Para o Python, está envolvendo todo o campo do desenvolvimento de IA, ML, e também em alguns projetos de desenvolvimento da Web - especialmente aplicativos de áudio/vídeo, aplicativos da Web progressivos ou aplicativos de administração do sistema. Para o Node.js, são principalmente aplicativos em tempo real, aplicativos de streaming, aplicativos de página única e outros aplicativos da web.
Vai depender de qual a necessidade do projeto a ser usado.



https://dev.to/wrrnwng/nodejs-vs-python-3-performance-1ok6

https://benchmarksgame-team.pages.debian.net/benchmarksgame/fastest/node-python3.html

https://www.netguru.com/blog/node-vs-python
