# Play Desenvolvimento — Android

Canal de testes do aplicativo Android da Play, separado do sistema web atual.

Esta versão permite testar a instalação, o mecanismo de atualização, o login nas contas existentes e o menu correspondente ao perfil. A 0.1.9 é a primeira versão assinada com a chave definitiva de distribuição. Ainda não possui registro de atendimentos ou envio em segundo plano. Não usar para trabalho operacional.

## Instalação obrigatória da 0.1.9

A 0.1.8 e as versões anteriores foram assinadas com uma chave de desenvolvimento. Por isso, o Android não permite atualizar diretamente para a 0.1.9. Desinstale a versão antiga e instale manualmente o APK 0.1.9 uma única vez. As próximas versões usarão a mesma chave definitiva e poderão voltar a ser atualizadas pelo próprio aplicativo.

O pacote está registrado no Android Developer Console gratuito. Somente os celulares autorizados nessa conta poderão instalar o aplicativo quando a verificação obrigatória do Android estiver ativa.

As Releases contêm o APK e o arquivo `update.json` que informa a versão disponível. O aplicativo mostra um botão amarelo na parte superior ao abrir ou retornar e só inicia uma atualização compatível após o usuário tocar nele. A instalação depende da confirmação solicitada pelo Android.
