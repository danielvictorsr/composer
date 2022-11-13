# Meu Pacote

Exemplo de um curso


## Exemplo de utilização

```

use DanielVictor\EstudoComposer\Hello;

$log = new Logger('name');
$log->pushHandler(new StreamHandler('app.log', Logger::WARNING));

$log->warning((new Hello)->say('Daniel Victor'));

```
