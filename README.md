# Linguagem-Java
Tutoriais e informações sobre Java

ÍNDICE
[Maven](https://github.com/carloshumberto28/Linguagem-Java/blob/main/README.md#maven)

[Instalando o Eclipse](https://youtu.be/sBVBuN-ZfG8),

[Introdução a Java](https://www.youtube.com/watch?v=gsy5GqwWqjw&t=182s)

[Curso Java](https://www.youtube.com/watch?v=6cgdclqm768&t=609s)

[Curso java Web](https://www.youtube.com/channel/UCfZokasaM2WVd7OM07pnktQ)

[Curso da Loiane. Introdução ao Java](https://www.youtube.com/watch?v=mu2ti43cgwc&list=PLGxZ4Rq3BOBq0KXHsp5J3PxyFaBIXVs3r&index=6)

>Aplicação
>>Módulos
>>>Pacotes
>>>>Classes
>>>>>Atributos e Metodos


# Curosos Java Web

[Fundamentos Java Web (Old)2013](https://www.youtube.com/watch?v=oWqryJpvFeg&list=PLKvsMn7xWutZ4P8U5KvF0kxpaCCbcW02A)

[Fundamentos Java Web 2015](https://www.youtube.com/watch?v=A9WRuhzVD80&list=PLKvsMn7xWutZ_kx6CRoVNxV2Bwt4xHQ6o)

[Cursou:Java Web](https://www.cursou.com.br/informatica/programacao/programacao-java-web/#player)

[PDF Java Web](https://www.caelum.com.br/apostila/apostila-java-web.pdf)

# Criando e publicando aplicações web com Eclipse

[Devmedia](https://www.devmedia.com.br/criando-e-publicando-aplicacoes-web-com-eclipse/28024)

# Maven
[Configurando o Maven. Variaveis de ambiente](https://www.youtube.com/watch?v=-ucX5w8Zm8s)

# Gladle
TUTORIAL GLADLE

Para o Wrapper funcionar com o gladle, tem que instalar o Buildship.
Configurar o eclipse para o Gladle instalando o BuildShip atraves do MarketPlace do Eclipse que está no menu help do mesmo.
https://marketplace.eclipse.org/content/buildship-gradle-integration
[]()

# OFBIZ
Bem-vindo ao Apache OFBiz! Um poderoso projeto de software Apache de nível superior. OFBiz
é um sistema de planejamento de recursos empresariais (ERP) escrito em Java e abriga um
grande conjunto de bibliotecas, entidades, serviços e recursos para executar todos os aspectos do
seu negócio.

== Requisitos do sistema

O único requisito para executar o OFBiz é ter o Java Development Kit (JDK)
versão 8 instalada em seu sistema (não apenas o JRE, mas o JDK completo) que
você pode baixar no link abaixo. Certifique-se de definir o $ JAVA_HOME
variável de ambiente.

https://adoptopenjdk.net/[JDK download]


== Início rápido

Para instalar e iniciar o OFBiz rapidamente, siga as instruções abaixo de
a linha de comando no diretório de nível superior OFBiz (pasta).

=== Baixe o wrapper Gradle:

MS Windows: init-gradle-wrapper
SO tipo Unix: ./gradle/init-gradle-wrapper


=== Prepare OFBiz:

==== Limpe o sistema e carregue os dados OFBiz completos
_______________________________________________________________________________
Nota: Dependendo da velocidade da sua conexão com a Internet, pode demorar muito
para que esta etapa seja concluída se você estiver usando OFBiz pela primeira vez, pois é necessário
para baixar todas as dependências. Então, por favor, seja paciente!
_______________________________________________________________________________

MS Windows: gradlew cleanAll loadAll
SO tipo Unix: ./gradlew cleanAll loadAll

===== Nota:
Como etapa posterior, para instalar sem os dados de demonstração, siga estas etapas:
(cuidado, isso é para desenvolvimento ou produção, não para tentar)

Windows: gradlew cleanAll "ofbiz --load-data Readers = seed, seed-initial" loadAdminUserLogin -PuserLoginId = admin
SO tipo Unix: ./gradlew cleanAll "ofbiz --load-data Readers = seed, seed-initial" loadAdminUserLogin -PuserLoginId = admin

A instalação do OFBiz ficará vazia, não haverá plano de contas, nem transações, nem produtos, nem clientes, nem fornecedores.
Você não pode fazer login na Loja de comércio eletrônico. Você obterá: "Uma Loja de Produtos não foi definida para este site de comércio eletrônico. Uma Loja de Produtos pode ser criada usando o assistente ofbizsetup."

=== Iniciar OFBiz:

MS Windows: gradlew ofbiz
Sistema operacional semelhante ao Unix: ./gradlew ofbiz

_______________________________________________________________________________
Nota: Ignore o indicador de% de progresso porque esta tarefa não termina tão longa
enquanto OFBiz está em execução.
_______________________________________________________________________________

=== Visite o OFBiz através do seu navegador:

https: // localhost: 8443 / webtools

== Indo mais longe
Para completar a instalação e usar o OFBiz, leia README.adoc
Você pode preferir ler este arquivo AsciiDoc no formato HTML.
Para isso, basta seguir:
https://asciidoctor.org/docs/convert-documents/#converting-a-document-to-html 
Mais sobre o texto originalÉ necessário fornecer o texto original para ver mais informações sobre a tradução
Enviar feedback
Painéis laterais


[Tutorial em espanhol](https://www.youtube.com/watch?v=7aiNzvn6TvQ)


[Tutorial Ofbiz](https://cwiki.apache.org/confluence/display/OFBIZ/OFBiz+Tutorial+-+A+Beginners+Development+Guide+for+16.11#OFBizTutorialABeginnersDevelopmentGuidefor16.11-CreateYourFirstApplication(HelloWorld...))

## ofbiz-plugins


## OfBiz-Framework












