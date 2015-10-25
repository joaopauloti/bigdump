# BigDump
Script PHP que permite importar grandes arquivos SQL


Para utilizar, altere os itens abaixo com as informações de seu banco de dados e rode no seu servidor.

// Database configuration
$db_server = ‘mysql02.seudominio.com.br’;

$db_name = ‘nome do banco‘;

$db_username = ‘usuário do banco‘;

$db_password = ‘senha do banco‘;

// Other settings (optional)
$filename = ‘nome do arquivo .sql‘;

Obs.: Os dois arquivos (seu.sql e bigdump.php) devem estar obrigatoriamente no mesmo diretório, após isso acesse em seu navegador http://seudominio/bigdump.php e clique em “Start Import”.


Author:       Alexey Ozerov (alexey at ozerov dot de) 

AJAX & CSV functionalities: Krzysiek Herod (kr81uni at wp dot pl) 

Copyright:    GPL (C) 2003-2009

More Infos:   http://www.ozerov.de/
