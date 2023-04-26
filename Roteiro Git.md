

# Roteiro básico para iniciantes em Git/GitHub

<img height="300vh" src="assets/git-vs-github.png">

[Mapa Mental de apoio ](https://gitmind.com/app/docs/md33l02d)



- [x] Obtendo o git
  - Baixando git
    - Acesse osite oficial em [git-scm]( https://git-scm.com/) e baixe a última versão do instalador de acordo com seu sistema operacional.


- [x] Instalando
  - Em ambiente Windows, siga o processo padrão de instalção, clicando no arquivo executavel e siga sempre com Next , Next ....Finish.


- [x] Iniciando um projeto git
  - git init ( Este comando irá inicar o repositório )
    - git add ( Este comando adiciona o conteudo para o próximo estágio, o commit)
    - git commit ( Este comando salva um snapshot do estado do repositório naquele momento )


- [ ] Fazendo commit
  - flags -a -m ( A flag -m indica que você irá inserir uma mensagem de informação para aquele commit. A flag -a indica que esta mensagem será adicionada para todos os arquivos)


- [ ] Alguns Comandos git

	- git checkout
	- git branch
	- git log
	- git diff
	- git status

- [ ] Criando conta no GitHub

- [ ] Apontando para o GitHub

  -  Comandos de Configuração Global

  -  Comandos de Configuração Local


- [ ] Fazendo Pull

- [ ] Clonando Projeto Existente

- [ ] Subindo Alterações em um Projeto Existente
  - git push


- [ ] Comandos Linux para usar com o gitbash

  - **touch:** Cria arquivos em branco

    > O comando **touch** permite criar novos arquivos em branco através de uma linha de comando. Como exemplo, digite **touch /home/username/Documentos/index.html** para criar um arquivo **HTML** chamado **index** dentro do diretório **Documentos**.

    


  - **ls**: Lista todos os arquivos do diretório

    >  Para listar os arquivos existentes em algum diretório, basta usar o comando *ls*. Se executado sem parâmetros, ele listará o conteúdo do diretório em que você se encontra. Mas você pode indicar um caminho para ele, como *ls /usr/bin*, por exemplo.
    >
    > Existem variações que você pode usar com o comando **Is**:
    >
    > - **ls -R** vai listar todos os arquivos nos subdiretórios
    > - **ls -a** vai mostrar todos os arquivos ocultos
    > - **ls -l** vai listar todos os arquivos e diretórios com informações detalhadas como permissões, tamanho, proprietário, etc.
    > - **ls -al** vai listar todos os arquivos e diretórios, incluindo ocultos com informações detalhadas como permissões, tamanho, proprietário, etc.
    >
    > Também é possível usar o *ls* para conferir o tamanho e a data de criação de cada arquivo ou pasta. Para isso, use o parâmetro *-lh*, como no exemplo a seguir: *ls -lh*. E se você também quiser listar os arquivos ocultos, que começam com um ponto, use a opção *-a* (*ls -lha*).

    


- **df**: Mostra a quantidade de espaço usada no disco rígido

  > Use o comando **df** para obter uma resposta da quantidade de espaço de disco usado no seu sistema. Esse valor será mostrado em KBs. Se você quiser ver os resultados em MBs, digite **df -m**.
  >
  > Use o comando **df -h**. A opção *-h*, quer dizer *human-readable*, ou seja, legível para humanos. Se você executar o comando sem ela, as informações serão exibidas em kilobytes.



- **cd**: Acessa uma determinada pasta (diretório)

  >Para navegar pelo filesystem do Linux, use o comando **cd**. Ele requer ou um caminho completo ou o nome de um diretório, dependendo do diretório atual em que você estiver.
  >
  >Vamos dizer que você esteja em **/home/username/Documents** e quer ir para **Photos**, um subdiretório de **Documents**. Para fazer isso, simplesmente digite **cd Photos**.
  >
  >Outro cenário em que você quer mudar completamente de diretório, digamos, para **/home/username/Movies**. Nesse caso, você tem que digitar **cd** seguido pelo caminho absoluto do diretório.  
  >
  >Existem alguns atalhos que você pode usar para navegar mais rapidamente.:
  >
  >- Use **cd..** (com dois pontos seguidos) para mover um diretório acima
  >- Use cd para ir diretamente para a pasta home
  >- Use **cd\**–\**** (com um hífen) para mover para os diretórios anteriores.
  >
  >Uma nota de aviso: o shell do Linux é sensível a tipos de caracteres. Por isso, você precisa digitar o nome do diretório exatamente como ele é escrito (usando letras minúsculas ou maiúsculas).

  

- **mkdir**: Cria um diretório

  > - Use o comando mkdir para criar um novo diretório – como mkdir Ferias, que vai criar um novo diretório chamado Ferias.
  >
  >   Também existem comandos mkdir extras:
  >
  >   Para gerar um novo diretório dentro de outro diretório, use este comando básico do Linux mkdir Ferias/Newimage
  >
  >   use a opção p (parents) para criar um diretório entre dois diretórios existentes. Por exemplo, mkdir -p Ferias/2022/Newimage vai criar o arquivo Newimage no novo diretório “2022”.

  

- **rmdir:** Deleta diretórios (Apenas se estiver vazio)

  >Se você precisa apagar (deletar) um diretório, use o comando **rmdir**. Porém, o rdmir só permite que você apague diretórios vazios (sem conteúdos).

  

- **rm**: Remove um arquivo/diretório

  >O comando **rm** é usado para apagar um diretório e todos os conteúdos que estiverem lá dentro. Se você só quer deletar o diretório  como uma alternativa ao **rdmir** – use **rm -r** ou **rm -rf** , o f aqui força a ação e por padrão **não pede confirmação**. (Tome muito cuidado ao usar) .
  >
  >**Nota:** Tenha muito cuidado com este comando e sempre verifique duas vezes em qual diretório você está. Isso irá deletar tudo e não há opção para desfazer.

  

- **cat**: Abre um arquivo

  >O **cat** (abreviação para concatenar) é um dos comandos Linux mais usados. Ele é usado para visualizar o conteúdo de um arquivo na saída padrão (sdout). Para executar esse comando, digite **cat** seguido pelo nome do arquivo e sua extensão. Por exemplo: **cat file.text**.
  >
  >Aqui estão outras maneiras de usar o comando **cat**:
  >
  >- **cat > filename** cria um novo arquivo
  >- **cat filename1 filename2>filename3** junta dois arquivos (1 e 2) e armazena a saída deles num novo arquivo (3)
  >- para converter um arquivo para usos de maiúscula ou minúscula, use **cat filename | tr a-z A-Z >output.txt**

  

  - **cp:** Copia arquivos

    > Use o comando *cp* seguindo do arquivo de **origem** e o **destino** para ele, que pode ser tanto uma nova pasta quando um novo arquivo, com nome diferente. Exemplo: *cp arquivo1.txt arquivo2.txt*  aqui foi feita uma copia do ***arquivo1.txt*** pro mesmo diretório mas com o nome ***arquivo2.txt***  ou, então,  *cp arquivo1.txt pastanova/*  aqui, o ***arquivo1.txt*** esta sendo copiado com o mesmo nome para o diretório ***pastanova/***. 
    >
    > Para copiar um diretório completo, inserira o parâmetro *-r* de **Recursivo**. 
    >
    > ex: Se quiser clonar uma pasta, use *cp -r pasta1 pasta2*, aqui o diretório ***pasta1*** esta sendo totalmente copiado para o diretório ***pasta2***.

  

- **vi**: Abre o editor vi (lê-se **viai**) para editar/criar arquivos



- **mv:** Mover ou Renomear arquivos e Diretórios

  >O usuário habitual do comando **mv** é mover arquivos, ainda que ele possa também ser usado para renomear arquivos.
  >
  >Os argumentos neste comando é similar ao comando **cp**. Você precisa digitar **mv**, o nome do arquivo e o diretório de destino. Por exemplo:Movendo arquivo file.txt para o diretório Documents -  **mv file.txt /home/username/Documents**.  
  >
  >Já para renomear arquivos, a sintaxe é **mv nomeantigo.ext nomenovo.ext**. 

  

- **history:** Lista o histórico de comandos digitados

  > Após diveros comando digitados no terminal, você vai perceber que você pode executar centenas de comandos e os mesmos comandos todos os dias. O comando **history** (histórico) é o ajuda a rever quais comandos já foram digitados antes.

  

- **clear:** Limpar o Buffer  e a tela do terminal

  > Após diversas linhas de comandos digitadas e consequentemente as informações de saída mostradas, a tela do terminal ficará "suja" com muitas informações na tela, para limpar use o comando ***clear*** ou ***ctrl+l*** (Control+ a letra L em minusculo)

  

- **pwd:** Verificar em que diretório estamos

  > **acrônimo para print working directory (ou, imprimir diretório de trabalho)**. O comando pwd é considerado como um dos comandos mais usados no sistema operacional Linux, Unix, e vários outros. Sua principal funcionalidade é: Encontrar o caminho completo do diretório atual.
  >
  > Exemplos do comando pwd
  >
  > Para imprimir o diretório de trabalho atual, digite:
  >
  > ```
  > pwd
  > ```
  >
  > Uma saída para o comando acima seria: 
  >
  > ```
  > /home/documentos 
  > ```
  >
  > Neste caso, */home/documento*s é o seu diretório atual. 



- **vi:** Editor de Texto em linha de comandos

  > O vi ou vim é um editor de texto poderoso e muito usado em sistemas Unix/Linux e também Mac. O vim ( vi Improved) é uma edição melhorada e com muito mais recursos em relação ao vi.
  >
  > Seu uso não é muito intuitivo à primeira vista, mas a edição simples de textos pode ser feita usando poucos comandos. 
  >
  > Ele pode ser muito útil para pequenas correções pontuais, principalmente em ambiente de produção. Então não é má ideia saber lidar com esse editor de textos universalmente disponível nas distribuições Linux.
  >
  > Basicamente ele tem tres modos de trabalho: o modo de ***operação*** e o modo de ***inserção*** e o modo **visual**(*Não falaremos do modo visual neste treinamento*) No modo de ***operação*** o vi espera comandos que vão realizar alguma ação. Neste modo, tudo que for digitado é considerado texto. 
  >
  > Para acessar o modo de ***operação*** aperte a tecla ESC. OBS: O vi sempre inicia nesse modo.
  >
  > Para entrar no modo de ***inserção***, basta a pressionar a tecla INSERT ou a tecla “i”. 
  >
  >  
  >
  > Para fazer uma edição simples de arquivos no vi digite:
  >
  > ```
  > $ vim nomedoarquivo
  > ```
  >
  > Para altere o modo para inserção pressione a tecla INSERT ou pressionando a tecla “**i**“. O cursor pode ser movido neste modo com as setas de posição. Ao terminar a digitação aperte a tecla ESC para retornar ao modo padrão (**modo de operação**)e digite shift+:
  >
  > > :w para salvar as modificações; 
  > > :wq para salvar e sair do vi; ou :x também para salvar e sair, mas neste caso só foi preciso uma tecla de comando ao invés de duas.
  > > :q! para sair sem salvar;
  > >
  > >  ***Lembre-se, os comandos acima para salvar e sair devem ser digitados pressionando primeiro a tecla ESC depois a tecla shift+:  seguido da letra de comando.***
