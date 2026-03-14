# Introducao-Computacao-Hardware-Victor-Nicolle
#Investigação de hardware: Máquina Enigma

**Alunos: Victor Gabriel e Nicolle Coelho**

![Image](https://github.com/user-attachments/assets/a12210cc-079d-4d1b-ab23-62502415c46c)

## Processamento
 O sistema de criptografia da Enigma era baseado em um mecanismo eletromecânico que alterava constantemente as substituições de letras. A máquina utilizava rotores giratórios e um painel de conexões que trocava pares de letras. Cada vez que uma tecla era pressionada, um rotor girava e modificava o circuito interno, fazendo com que a mesma letra pudesse ser codificada de formas diferentes ao longo da mensagem. Esse funcionamento gerava um número extremamente elevado de combinações possíveis, tornando praticamente impossível decifrar as mensagens apenas por tentativa e erro.  
 Além disso, as configurações da máquina, como a ordem dos rotores, a posição inicial e as conexões do painel, eram alteradas regularmente pelos operadores alemães, geralmente todos os dias. Com essas variáveis combinadas, a Enigma podia alcançar números astronômicos de configurações, chegando a centenas de trilhões ou até mais possibilidades dependendo do modelo utilizado.  
Durante a Segunda Guerra Mundial, uma equipe de criptanalistas britânicos liderada por Alan Turing trabalhou no centro de inteligência de Bletchley Park para quebrar o sistema de criptografia alemão.
 Para acelerar o processo de análise, eles desenvolveram uma máquina chamada Bombe, projetada para testar automaticamente diferentes configurações da Enigma até encontrar aquelas que poderiam gerar mensagens plausíveis.Os criptanalistas utilizavam também uma técnica chamada “cribs”, que consistia em procurar trechos previsíveis dentro das mensagens criptografadas. Palavras ou expressões que apareciam com frequência, como relatórios meteorológicos, nomes de locais ou saudações militares, eram comparadas com o texto cifrado para identificar possíveis correspondências. Esse método permitia reduzir drasticamente o número de configurações que precisavam ser testadas pelas máquinas.  
 Outra observação importante feita por Turing e sua equipe foi que certos padrões se repetiam nas mensagens alemãs. Por exemplo, números muitas vezes eram escritos por extenso em alemão, como “eins” para representar o número um. A partir dessa regularidade, foi criado o chamado Catálogo Eins, um conjunto de métodos que auxiliava na identificação automática desses padrões e facilitava a busca por possíveis chaves de decodificação.
 Essas técnicas, combinadas com o uso de máquinas eletromecânicas e análise matemática, permitiram que os aliados decifrassem uma grande quantidade de comunicações militares alemãs. Muitos historiadores consideram que o trabalho realizado em Bletchley Park contribuiu significativamente para encurtar a guerra, pois forneceu informações estratégicas importantes para as forças aliadas.

## Armazenamento
 Durante a Segunda Guerra Mundial, a máquina de criptografia Enigma não possuía memória eletrônica como os computadores atuais. Seu funcionamento era baseado em componentes eletromecânicos, como rotores, refletores e um painel de conexões. Esses elementos determinavam como cada letra seria transformada em outra durante o processo de criptografia. Dessa forma, a “memória” da máquina era representada apenas pela configuração física dos seus componentes naquele momento, funcionando como um tipo de registro temporário do sistema.
Os rotores eram discos com circuitos internos responsáveis por realizar a substituição das letras do alfabeto.
 Cada rotor possuía 26 posições, correspondentes às 26 letras, e girava a cada tecla pressionada, alterando continuamente o resultado da criptografia. A combinação entre a ordem dos rotores, suas posições iniciais e as conexões do painel de cabos criava um número extremamente grande de configurações possíveis, o que tornava o sistema de criptografia muito difícil de ser quebrado sem métodos especializados.
 Além disso, as configurações da Enigma eram alteradas diariamente pelos operadores militares alemães. Essas mudanças eram registradas em livros de códigos, que indicavam qual seria a chave criptográfica utilizada em cada dia. No início de cada jornada, os operadores ajustavam a máquina de acordo com essas instruções. Esse procedimento aumentava a segurança das comunicações, pois impedia que a mesma configuração fosse usada por muito tempo, dificultando o trabalho dos criptanalistas inimigos.
 Como a máquina não possuía capacidade de armazenamento permanente, as mensagens criptografadas não eram guardadas dentro do equipamento. Em vez disso, os operadores anotavam manualmente em papel as letras que apareciam no painel luminoso, formando a mensagem codificada que posteriormente seria enviada por rádio ou arquivada. Assim, o armazenamento das informações ocorria principalmente por meio de registros físicos e documentos militares, e não por memória digital.
 Portanto, o sistema relacionado à Enigma utilizava uma forma de armazenamento limitada, baseada em configurações mecânicas temporárias e registros escritos, refletindo as tecnologias disponíveis na época.

## Interface
 A interface da máquina Enigma era composta por um teclado com 26 teclas (A a Z), um painel de lâmpadas com 26 luzes (também A a Z) e um conjunto de rotores visíveis na frente da máquina.
 Quando uma tecla era pressionada, uma corrente elétrica percorria o sistema, e a luz correspondente à letra criptografada acendia no painel. O operador digitava a mensagem original (plaintext) no teclado, e o resultado cifrado (ciphertext) era lido pelas luzes acesas.
 A interface também incluía um painel de conectores (plugboard), onde cabos conectavam pares de letras para alterar o caminho elétrico antes e depois dos rotores, aumentando a complexidade da cifra.
 A aparência era semelhante a uma máquina de escrever, com os rotores girando automaticamente após cada tecla pressionada, alterando a cifra a cada letra.
 
![Image](https://github.com/user-attachments/assets/b09f71bc-8c1d-407a-a3ff-7e1241155c44)

 ## Comparação
 A máquina Enigma, usada pela Alemanha na Segunda Guerra Mundial, era um dispositivo eletromecânico complexo, mas seu poder computacional é insignificante comparado ao hardware atual. Um processador moderno em um notebook pode realizar bilhões de operações por segundo, superando em muito o que era possível em Bletchley Park, onde as bombas de Turing máquinas pesadas e lentas eram usadas para tentar quebrar os códigos. 
 O que levou meses ou anos na década de 1940 hoje seria resolvido em segundos.  As bombas mecânicas de Turing, que ocupavam salas inteiras, podem agora ser simuladas em software em um computador pessoal, executando o mesmo trabalho milhares de vezes mais rápido. Um smartphone atual possui mais poder computacional que todos os computadores combinados de Bletchley Park na época. 
 Além disso, sistemas modernos como o ChatGPT e algoritmos de inteligência artificial podem quebrar a Enigma de forma quase instantânea, usando análise estatística avançada, computação paralela massiva e aprendizado de máquina.
 A criptografia da Enigma, com 150 quintilhões de combinações, era invencível para a época, mas hoje seria trivial para os padrões atuais de segurança digital, que usam chaves de 256 bits ou mais, resistindo até a computadores quânticos teóricos. 
 
## Análise Técnica – Tabela comparativa
Componente	Hardware Histórico 	Hardware moderno
(Computadores atualmente)

ULA	Implementada com válvulas eletrônicas ou transistores discretos, ocupando grande espaço físico e consumindo muita energia. O desempenho era limitado, realizando milhares de operações por segundo.	Integrada dentro de microprocessadores em circuitos integrados, com bilhões de transistores. Realiza bilhões de operações por segundo e faz parte de CPUs e GPUs altamente otimizadas.

Memória	Inicialmente utilizava tecnologias como linhas de atraso de mercúrio ou memória de núcleo magnético, com capacidade muito pequena (ex.: cerca de 1000 palavras de memória em computadores antigos).	Utiliza memória semicondutora (RAM, DDR4/DDR5) com capacidades de gigabytes ou terabytes, acesso extremamente rápido e baixo consumo de energia.

Armazenamento de dados	Usava fitas magnéticas, cartões perfurados ou tambores magnéticos, com acesso sequencial e baixa velocidade.	Usa SSDs e discos rígidos modernos, com acesso rápido, grande capacidade (centenas de GB a vários TB) e alta confiabilidade.

Periféricos de entrada	Cartões perfurados, fitas perfuradas e painéis de controle manual. Muitas vezes exigiam configuração física da máquina para executar programas.	Teclado, mouse, touchscreen, sensores, webcams, scanners e dispositivos de entrada avançados.

Periféricos de saída	Impressoras mecânicas e fitas impressas eram os principais meios de saída.	Monitores de alta resolução, impressoras modernas, realidade virtual, dispositivos de áudio e vídeo digitais.

Tamanho físico	Computadores ocupavam salas inteiras, pesavam toneladas e consumiam muita energia.	Computadores podem caber em notebooks, smartphones ou dispositivos embarcados, consumindo muito menos energia.
Velocidade de processamento	Realizavam poucas milhares de operações por segundo.	Realizam bilhões de operações por segundo graças aos processadores modernos e paralelismo.

![Image](https://github.com/user-attachments/assets/c222306e-c970-490e-b12f-8d71b33776c6)

 ## fontes 
 https://brasilescola.uol.com.br/historiag/maquina-enigma.htm
 https://epocanegocios.globo.com/tecnologia/noticia/2024/08/enigma-como-uma-maquina-de-guerra-ajudou-a-construir-a-computacao-moderna.ghtml
 https://revistagalileu.globo.com/Ciencia/noticia/2018/11/segredos-da-maquina-nazista-enigma-sao-quebrados-em-exame-de-raios-x.html
 https://revistagalileu.globo.com/Ciencia/noticia/2018/11/segredos-da-maquina-nazista-enigma-sao-quebrados-em-exame-de-raios-x.html
 https://www.computerhistory.org/collections/catalog/B197.81
 https://www.sciencedirect.com/topics/computer-science/enigma-machine
https://brasilescola.uol.com.br/historiag/maquina-enigma.htm
https://www.infoescola.com/segunda-guerra/enigma/
https://www.theguardian.com/technology/2014/nov/14/how-did-enigma-machine-work-imitation-game
https://www.britannica.com/technology/computer
https://www.webopedia.com/definitions/computer/
https://www.researchgate.net/publication/387964642_Optimized_Design_and_Applications_of_Arithmetic_Logic_Units_Addressing_Power_Efficiency_and_Performance_in_Diverse_Computing_Applications


 
