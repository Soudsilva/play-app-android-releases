# Play Desenvolvimento — Android

Canal de testes do aplicativo Android da Play, separado do sistema web atual.

Esta versão permite testar a instalação, o mecanismo de atualização, o login nas contas existentes e o menu correspondente ao perfil. A 0.1.8 troca a conexão contínua do perfil por uma leitura HTTPS única e informa a etapa do carregamento. Ainda não possui registro de atendimentos ou envio em segundo plano. Não usar para trabalho operacional.

Instalador destinado a celulares Android. As primeiras versões usam assinatura de desenvolvimento. As versões anteriores à 0.1.2 precisam receber manualmente a primeira instalação com atualizador.

As Releases contêm o APK e o arquivo `update.json` que informa a versão disponível. O aplicativo mostra um botão amarelo na parte superior ao abrir ou retornar e só inicia a atualização após o usuário tocar nele. A instalação depende da confirmação solicitada pelo Android.
