# Play Desenvolvimento — Android

Canal de testes do aplicativo Android da Play, separado do sistema web atual.

A versão 0.1.11 permite testar a instalação, o mecanismo de atualização, o login nas contas existentes e o menu correspondente ao perfil. Ela mantém a sessão por até dois dias e, dentro desse prazo, abre diretamente o menu sem mostrar o formulário de login. Nome e senha continuam cifrados pelo cofre do Android para preencher o próximo login. Ainda não possui registro de atendimentos ou envio em segundo plano. Não usar para trabalho operacional.

A 0.1.11 usa a mesma chave definitiva da 0.1.9 e pode ser instalada pelo botão de atualização do aplicativo. A reinstalação manual foi necessária somente na passagem da 0.1.8 para a 0.1.9.

O pacote está registrado no Android Developer Console gratuito. Somente os celulares autorizados nessa conta poderão instalar o aplicativo quando a verificação obrigatória do Android estiver ativa.

As Releases contêm o APK e o arquivo `update.json` que informa a versão disponível. O aplicativo mostra um botão amarelo na parte superior ao abrir ou retornar e só inicia uma atualização compatível após o usuário tocar nele. A instalação depende da confirmação solicitada pelo Android.
