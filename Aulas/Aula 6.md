# Introducao-Computacao-Sistemas-Operacionais
Victor-Gabriel-Nicolle-Coelho-João-Pedro-Oliveira

## Desenvolvimento e arquitetura de software
para aplicativos do Android

O desenvolvimento de aplicativos Android vai além da criação de telas atraentes. É essencial organizar o código de forma clara e estruturada para que o aplicativo seja fácil de entender, corrigir e expandir ao longo do tempo. A arquitetura de software desempenha um papel fundamental, ajudando a lidar com as limitações comuns dos dispositivos móveis, como consumo de bateria, memória e telas de diferentes tamanhos.
O ambiente principal de desenvolvimento é o Android Studio, ferramenta oficial do Google. A linguagem de programação recomendada é o Kotlin, adotada como prioridade pelo Google por ser moderna, concisa e mais segura.
Todo aplicativo Android é composto por componentes básicos:
• Activity: representa uma tela completa com a qual o usuário interage;
• Service: executa tarefas em segundo plano;
• Broadcast Receiver: recebe notificações e eventos do sistema ou de outros aplicativos;
• Content Provider: permite o compartilhamento seguro de dados entre diferentes aplicativos.
Cada componente possui um ciclo de vida gerenciado pelo sistema operacional. Por isso, o desenvolvedor deve garantir que as informações não sejam perdidas quando o usuário muda de tela, gira o dispositivo ou sai do app.
A arquitetura mais recomendada atualmente combina o padrão MVVM (Model-View-ViewModel) com a Clean Architecture. No MVVM, a interface (View) fica separada do controlador de lógica (ViewModel) e da camada de dados (Model). A Clean Architecture organiza o app em camadas bem definidas: camada de apresentação (UI), camada de domínio (regras de negócio) e camada de dados. Essa separação facilita a manutenção e os testes, pois mudanças em uma camada afetam menos as outras.
Para construir as interfaces de usuário, o Google recomenda o Jetpack Compose, o toolkit moderno e declarativo que permite criar telas de forma mais rápida e eficiente.
O conjunto de bibliotecas Jetpack oferece ferramentas para navegação entre telas, gerenciamento de dados, execução de tarefas em segundo plano e injeção de dependências. Essas bibliotecas incorporam boas práticas de engenharia de software, contribuindo para melhor desempenho, segurança e experiência do usuário.
As boas práticas no desenvolvimento Android incluem a realização de testes, a divisão do projeto em módulos menores (modularização) e o cuidado constante com performance e segurança. Essas medidas garantem que o aplicativo funcione bem em diferentes dispositivos e seja fácil de atualizar no futuro.
Em resumo, o desenvolvimento de apps Android aplica os conceitos centrais da Engenharia de Software: organização, separação de responsabilidades e foco na qualidade. Usando Kotlin, Jetpack Compose, MVVM e Clean Architecture, é possível criar aplicativos organizados, confiáveis e prontos para evoluir conforme as necessidades dos usuários.

## Introdução ao Uso de Dispositivos Móveis e o Ecossistema Android. 

Os dispositivos móveis evoluíram de simples celulares para smartphones multifuncionais, e o Android domina o mercado como sistema operacional open-source baseado em Linux.   Essa introdução aborda o uso básico e o ecossistema Android para o seu trabalho escolar.

Dispositivos Móveis 
 
   Dispositivos móveis são computadores portáteis como smartphones e tablets, com telas touch, internet e apps para tarefas diárias como comunicação, entretenimento e banking. Sua história começou com notebooks e palmtops nos anos 90, evoluindo para smartphones em 2007, que integram voz, dados e apps. Hoje, permitem edição de textos, redes sociais e jogos, superando limitações antigas.

História do Android 

   Android surgiu em 2003 como startup para câmeras digitais, adquirido pelo Google em 2005 e lançado comercialmente em 2008 com o HTC Dream. Andy Rubin é considerado o "pai do Android", que usa kernel Linux e parcerias com Samsung e Motorola para dominar 70% do mercado móvel. Versões constantes evoluem com integrações Google.


Arquitetura do Android 

   A arquitetura tem camadas: kernel Linux (gerencia hardware como Wi-Fi e energia), HAL (abstrai hardware), bibliotecas nativas (C/C++, OpenGL), Android Runtime (ART para apps Java/Kotlin) e Framework (APIs para apps). Componentes chave incluem Activity (interface), Service (tarefas em background), Broadcast Receiver (mensagens) e Content Provider (compartilhamento de dados).

Ecossistema Android
 
    O ecossistema integra serviços Google como Gmail, Maps, Drive e Play Store, com sincronização entre dispositivos via Google Play Services. É personalizável com widgets e temas, open-source para customizações por fabricantes como Samsung. Vantagens incluem apps vastos (250.000+), IA para spam e compatibilidade ampla.

Mercado do Android 
 
   No Brasil, o Android detém 81,92% do mercado móvel em fevereiro de 2026, contra 17,86% do iOS. Globalmente, embarques de smartphones cairão 12,9% em 2026 devido a crise de memória RAM, com recuperação só em 2028. Samsung lidera marcas com 33,84%, seguida por Motorola e Xiaomi.

Comparação Android e iOS 

  Android oferece múltiplos fabricantes (Samsung, Xiaomi, Motorola), alta personalização (widgets, temas, launchers), ampla faixa de preços (R$500 a R$10.000+), atualizações que variam por fabricante (2-7 anos), desempenho dependente do hardware, segurança via Play Protect, integração Google e apps da Google Play + lojas alternativas.
   iOS é exclusivo Apple (iPhone), tem interface padronizada com baixa personalização, preços a partir de R$4.000+, atualizações simultâneas para todos os modelos (5-7 anos), desempenho otimizado para chips Apple, alta segurança via App Store fechada e Face ID/Touch ID, integração perfeita com Mac/iPad/Watch/AirPods e apps apenas da App Store.

  Android por flexibilidade, variedade de preços e customização ideal para uso diário e projetos escolares.
   iOS por segurança, integração Apple e atualizações confiáveis se você já possui ecossistema Apple.

## DESAFIOS, BOAS PRÁTICAS E TENDÊNCIAS NO DESENVOLVIMENTO ANDROID

O desenvolvimento de aplicativos para dispositivos móveis, especialmente no sistema Android, tem se expandido significativamente nos últimos anos. Com a popularização dos smartphones, cresceu também a demanda por aplicações eficientes, seguras e com boa experiência de uso. Neste contexto, torna-se essencial compreender os desafios enfrentados pelos desenvolvedores, bem como aplicar boas práticas e acompanhar as tendências tecnológicas da área.

2 DESAFIOS NO DESENVOLVIMENTO ANDROID
Um dos principais desafios no desenvolvimento Android é a fragmentação de dispositivos, uma vez que existem diversos fabricantes, tamanhos de tela e versões do sistema operacional. Isso exige que o aplicativo seja adaptável e funcione corretamente em diferentes ambientes.

Outro desafio relevante é o gerenciamento de permissões e segurança, já que os aplicativos lidam com dados sensíveis dos usuários. Além disso, a otimização de desempenho é essencial, pois o app deve consumir poucos recursos do dispositivo, como memória e bateria.

A compatibilidade entre versões do Android também é um fator crítico, pois novas atualizações do sistema podem impactar o funcionamento do aplicativo. Por fim, a integração com APIs e serviços externos exige estabilidade e tratamento adequado de erros.

3 BOAS PRÁTICAS NO DESENVOLVIMENTO
Para lidar com esses desafios, é fundamental adotar boas práticas de desenvolvimento. Uma das principais é o uso de arquiteturas como MVVM (Model-View-ViewModel), que promove a separação de responsabilidades e facilita a manutenção do código.

A aplicação dos princípios SOLID contribui para a criação de um código mais organizado, reutilizável e fácil de entender. Além disso, a realização de testes automatizados permite identificar falhas precocemente e aumentar a confiabilidade do sistema.

O uso de ferramentas como o Room possibilita o armazenamento eficiente de dados locais, enquanto o consumo de APIs REST permite a integração com serviços externos. O versionamento de código com Git é essencial para o trabalho em equipe e controle de alterações.

Outro aspecto importante é o uso do Material Design, que garante uma interface mais padronizada, intuitiva e agradável para o usuário.

4 TENDÊNCIAS NO DESENVOLVIMENTO ANDROID
Entre as principais tendências, destaca-se o uso da linguagem Kotlin, que se tornou a principal linguagem para desenvolvimento Android devido à sua simplicidade e segurança.

O Jetpack Compose também vem ganhando espaço como uma forma moderna de construção de interfaces, permitindo maior produtividade e menos código.

Além disso, o desenvolvimento multiplataforma, com tecnologias como Flutter e React Native, tem se tornado cada vez mais comum, permitindo a criação de aplicativos para diferentes sistemas operacionais com um único código.

Outras tendências incluem a integração com inteligência artificial, uso de computação em nuvem, e maior foco na experiência do usuário (UX), buscando aplicações mais rápidas, intuitivas e eficientes.

A segurança e a privacidade dos dados também têm ganhado destaque, exigindo maior responsabilidade por parte dos desenvolvedores.

5 CONCLUSÃO
O desenvolvimento Android apresenta diversos desafios que exigem conhecimento técnico e constante atualização. A adoção de boas práticas e o acompanhamento das tendências tecnológicas são essenciais para a criação de aplicativos de qualidade. Dessa forma, é possível desenvolver soluções eficientes, seguras e que atendam às necessidades dos usuários.

## Fontes

https://tecnoblog.net/responde/o-que-e-android-conheca-a-historia-do-sistema-operacional-movel-mais-popular-do-mundo/
https://www.mobiletime.com.br/muse
https://tecnoblog.net/responde/o-que-e-android-conheca-a-historia-do-sistema-operacional-movel-mais-popular-do-mundo/
https://didatica.tech/o-que-e-android-e-como-funciona-entenda-tudo-aqui/?amp=1
https://www.oficinadanet.com.br/smartphones/68378-market-celulares-fevereiro-2026-brasil /ultima-hora/tecnologia/ios-x-android-entenda-as-diferencas-e-saiba-qual-escolher-1.3 
https://developer.android.com/topic/architecture
https://developer.android.com/kotlin/first
https://developer.android.com/compose
https://developer.android.com/guide/components/fundamentals
https://developer.android.com/topic/architecture/recommendations
