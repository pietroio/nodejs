# Instalar, verificar, testar (Install, Check, Test)

Esta pauta visa atender o propósito de instalar, e testar o interpretador de JavaScript Node.js no O.S. Ubuntu (Xenial 16.04).

Para maiores detalhes visite sua página oficial (https://nodejs.org/).

Instalação:

Para versões posteriores verificar a página oficial.

Node.js v8.x no Ubuntu:

Abra o terminal e execute:

`$ curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -`

`$ sudo apt-get install -y nodejs`

A partir de agora o Nodejs já está instalado.

Verificando caminho de instalação e versão instalada:

`$ which nodejs`

`$ node -v`

Se todas as etapas anteriores correrem sem nenhuma falha, então podemos testar um simples código em JavaScript.

Navegue até um diretório apropriado. Por exemplo:

`$ cd ~/test-temp`

Gere um arquivo de texto com a extenção ".js" (iremos usar "test.js"),

`$ nano test.js`

e inscreva no corpo do mesmo o seguinte código:

`var x, y, w, z;`

`x = 1;`

`y = 2;`

`w = x*y;`

`z = w+w;`

`console.log(w);`

`console.log(z);`

No terminal, ainda, execute o seguinte comando:

`$ node test.js`

Se você tiver um retorno no console (terminal) equivalente a equação inscrita, então você concluiu o tutorial sem falhas.

Bom trabalho, e se divirta criando todos os tipos de códigos!
