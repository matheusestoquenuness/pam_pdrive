<h2>Fatec - Faculdade de Tecnologia de Americana</h2>

Sistemas Operacionais II<br>
Professor: Rossano Pablo Pinto<br>
Alunos: 
        <li>Gustavo Messias Guimarães da Silva - 0040481821039</li>
        <li>Flávio Junior - 0040481821004</li>
        <li>Douglas Ortiz - 0040481821037</li>
        <li>Matheus Estoque Nunes - 0040481821040</li>
        <li>Agner Gomes - 0040481821045</li>
<hr>

Esse projeto é uma das soluções para quem precisa de um modulo de autenticação via pendrive, qualquer pendrive pode ser usado para a instalação do módulo.
<br>
<br>
<b>Versão 1.0 - 26/10/19</b><br>
<b>Versão 1.1 - 28/10/19</b><br>
<hr>

<h4> >> Instalação</h4>

  Para instalar inicie o terminal no diretório dos arquivos do módulo:<br>
  Como usuário root digite:<br>
    
    $ make
    $ make install
    
  
  Pronto, o seu módulo está instalado.<br>
  Abaixo segue a descrição do funcionamento do programa de instalação.
<hr>
<h4> >> Programa de Instalação</h4>

  O instalador cria duas pastas e dois arquivos necessários<br>
  para o funcionamento do móulo:<br>
    <br><li>/etc/pam.d/pam.pdrive</li>
      <b>login</b> : Aqui ficam localizados os seriais dos pendrives  instalados, apenas com o usuário root se tem acesso.<br>
    <br><li>/etc/pam.d/pam.pdrive/log</li>
      <b>log</b> : Aqui fica localizado o arquivo de log, onde registra data e hora de todos os logins efetuados, e o serial que foi utilizada.<br>
<hr>
<h4> >> Demais funcionalidades</h4>
    <li>Desinstalar 
        
       $ make uninstall
        
        
        
        
        
        
        
        
    
    
    
    
    
 Remove todos os diretórios e arquivos e desativa o módulo.</li>
    <li>Adcionar Pendrive 
       
       $ make addpendrive 
        
        
        
        
        
        
 Plugue um novo pendrive na máquina e digite o comando e será liberado o acesso a esse novo pendrive.</li>
<hr>
<h4> >> Limitações </h4>
    <li> <b>26/10/19 - Versão 1.0</b> : Grava apenas 1 serial.</li>
    
 <hr>
 <h4> >> Atualizações</h4>
    <li> <b/>28/10/19 - Versão 1.1</b> : Permitido o cadastro ilimitado de pendrives.


