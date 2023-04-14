:zap: :mouse: Introdução :zap: :mouse:

Oiie, eaí pessoas. tudo certo???
Bem vindos à primeira fase do PS da comp! Aqui vamos explicar um pouco da teoria e dos conceitos de Git e posteriormente direcionar vocês nas tarefinhas.
:white_check_mark: Pré-requisitos

Antes de fazer a tarefa, vocês precisam ter criado uma conta no GitHub e passado o username de vocês para a gente (comentem no post do @Erick_das ). Isso é muito importante e vai ser necessário durante todo o PS. Então quem ainda não respondeu o post, respondam lá!

Além disso, só será necessário ter instalado o git (que explicaremos como logo mais neste post), um terminal e um editor de texto. Para o editor de texto, recomendamos fortemente o uso do VSCode , por ser o padrão usado pela equipe mas você pode usar até o notepad se preferir.
:open_file_folder: Instalando Git :

A instalação de Git varia conforme o seu sistema operacional, então vamos explicar aqui como realizar a instalação no Windows, no Ubuntu e no Mac.
Além disso, todas as vezes que estiver escrito:

$ aqui_eh_um_comando

O sinal de $ serve para indicar que o próximo texto é na verdade um comando que você deve inserir no terminal sem incluir o cifrão.
:window: Windows

Para o Windows, recomendamos instalar Git através do site oficial, clicando aqui.
Após isso, siga as instruções do instalador e aceite as opções default que ele colocar.
Para saber se a instalação foi feita corretamente, basta abrir o programa e inserir os seguintes comandos:

	$ git --version

Algo parecido com isso deve aparecer no terminal:

	$ git version 2.37.2

:penguin: Linux (Ubuntu)

Basta apenas abrir o terminal e digitar os seguintes comandos:

	$ sudo apt update
	$ sudo apt install git 

:apple: MacOS

Para o macOS, utilizaremos uma forma indireta de se instalar o git. Para isso será necessário instalar o Xcode Command Line Tools, que pode ser feita diretamente pela App Store ou abrindo o terminal e inserindo o seguinte comando:

$ xcode-select --install

Após isso, insira sua senha e confirme a instalação.

Para saber se a instalação foi feita corretamente, insira o seguinte comando no terminal:

$ git --version

Algo parecido com isso deve aparecer no terminal:

$ git version 2.37.2

Caso vocês utilizem algum outro sistema operacional, podem nos mandar mensagem que vamos te ajudar a realizar a instalação adequada.
:gear: Configurando O Git

Uma das primeiras coisas a se configurar é sua conta do GitHub. Isso é importante para seus commits serem mais facilmente identificados. Para isso, é preciso executar 2 comandos:

git config --global user.name "Seu Nome"
git config --global user.email seuemail@exemplo.com

Além disso, é exigido um token de acesso temporário para realizar a clonagem por https (para ver como gerar um token clique aqui).
Por conta disso, recomendamos usar SSH para clonar e dar push em repositórios privados no GitHub, que não exigem nenhum token, mas uma chave gerado uma única vez. Logo, é interessante gerar uma chave ssh seguindo o guia de ssh direto do GitHub. Assim, poderá mexer nos repositórios sem problemas.

Uma explicação maior sobre as possíveis configurações estarão descritas nos repositórios das tarefinhas de vocês (especialmente sobre extensões do VSCode).
:card_index_dividers: Repositório

Abrindo o seu repositório, você vai se deparar com 3 folders principais:

Guias de instalação: Onde você encontrará tutoriais pra instalar Git, C, e algumas ferramentas para trabalhar com embarcados.

Teoria: Onde você vai poder ver todo o conteúdo abordado nas aulinhas de Git e C (e até um pouco mais, como o conteúdo de embarcados).

Tarefas: ondes vão ir sendo disponibilizados os enunciados e os espaços para as tarefinhas que vocês deveram entregar durante a primeira fase.
:pencil2: Aulas

Para quem não conseguiu comparecer na aulinha do dia 14 (minha e da @Nathy), ou quiser revisar o conteúdo dado, vamos deixar aqui embaixo as aulinhas que foram gravadas pelo @guedes e pelo @Vanderson .

Aulinha Git GitHub - Parte 1 - Teoria

Aulinha Git GitHub - Parte 2 - Prática

Comentários do autor do vídeo (@Vanderson):
“No minuto 2:50, aproximadamente, eu comento sobre como criar uma chave SSH no Windows para usar no GitHub, mas se você estiver em outro sistema operacional, como Ubuntu, não é valido o mesmo procedimento. Caso esteja usando outro sistema operacional, clique aqui para ver o guia oficial do GitHub para gerar essa chave SSH”
:alarm_clock: Orientações

É muito importante que para essa tarefa vocês apliquem os conceitos explicados na aulinha. Vocês devem seguir o workflow ensinado: clonar o repositório para a sua máquina, fazer as modificações e adições necessárias, e subir as modificações para GitHub. Lembrem-se também de abrir uma PR (Pull Request) da branch que vocês criaram, evitando dar merge antes de receber a aprovação do seu veterano.

A tarefa deve ser entregue até dia 17/04 as 23:59 e 59 segundos

Para muitos o tema é novidade, e é normal que surjam dúvidas. Sintam-se a vontade para perguntar e tirar suas dúvidas com a gente, seja aqui no fórum, no whatsapp ou até presencialmente.
:zap: Desejamos a vocês um ótimo PS :zap: 