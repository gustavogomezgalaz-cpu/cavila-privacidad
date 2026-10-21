# Política de Privacidade — Cavila

**Última atualização: 2026-10-21**

Cavila é um aplicativo de enigmas para crianças a partir dos 6 anos. Esta política explica o que o app guarda no telefone, que dados de uso e de falhas ele envia, para quê e por quanto tempo são guardados. Revisão de 21 de outubro de 2026: entram os planos por um tempo sem renovação automática, pagar em um celular e abrir em outro com um código, o presente de família e o que passa a ser medido (veja «Mudanças nesta política»).

---

## O resumo

Não há contas nem cadastro, não pedimos o nome da criança nem nenhum dado de contato, não há publicidade e não há chat. O progresso da criança e os perfis ficam guardados no telefone.

Para saber quantas famílias instalam o Cavila, de qual app irmão ou anúncio nosso elas vêm, que partes usam e o que compram, o app envia dados de uso ao Google Analytics para Firebase, sem nomes e sem o identificador de publicidade do telefone. E, se o app fechar por um erro, ou se uma compra com o Google Play não for concluída (por um erro, porque o tempo acabou ou porque foi cancelada), o Firebase Crashlytics envia um relatório técnico para podermos corrigi-lo. As duas coisas estão explicadas uma por uma em «Estatísticas e falhas».

O jogo funciona inteiro com o telefone em modo avião: os desafios, o progresso e a voz saem do próprio telefone. Sem conexão, os dados de uso podem esperar e ser enviados depois. Para jogar não é preciso rede; para pagar o Premium, cobrado pelo Google Play, sim. E, se um adulto paga no celular dele para abrir o app em outro aparelho, o app usa um código e um servidor nosso, só para isso (veja «Pagar em um celular e abrir em outro»).

---

## O que é guardado no telefone

O que o app guarda vive no armazenamento do próprio telefone:

- O progresso do jogo (níveis, estrelas, moedas, sequência, medalhas), para que a criança continue de onde parou.
- O apelido e o emoji de cada perfil, para distinguir irmãos que dividem o telefone.
- A faixa etária, que é opcional, para ajustar a dificuldade.
- Os ajustes: som, narração, idioma e lembrete.
- Algumas datas e marcas que só servem para decidir o que mostrar ao adulto: quando o app foi instalado, quando começou o teste de 3 dias do Farol do Critério, quais ofertas do Premium já apareceram, se há acesso Premium e, com um plano por um tempo, até quando ele dura e em que dia o app avisou que vence.
- A ficha dos planos que o Google Play entrega (o nome, os preços e as opções de compra), para poder pagar mesmo que o Google Play demore a responder (veja «A cobrança»).
- Se um adulto usou o código para pagar em um celular e abrir em outro: esse código, até quando ele vale e um número de aparelho aleatório (veja «Pagar em um celular e abrir em outro»). E se uma tentativa de pagamento não terminou e se o aviso «Melhoramos o pagamento» já apareceu, para não repeti-lo.

O apelido é escrito pela família e pode ser qualquer coisa. Não pedimos nome real, sobrenome, e-mail, telefone, endereço, foto nem data de nascimento: não há nenhuma conta para criar.

O relatório da Área dos Pais —em que a criança avança e o que custa mais para ela— é calculado no telefone a partir desse mesmo progresso. A análise de uso não copia o apelido, o emoji, a faixa etária nem o progresso: só registra os fatos soltos listados em «Estatísticas e falhas», como que um nível terminou e com quantas estrelas, o idioma do app e se há Premium.

O backup automático do Android está desativado de propósito, então o progresso não viaja para a sua conta do Google.

---

## Estatísticas e falhas (Firebase)

O Cavila usa o Google Analytics para Firebase em modo infantil. Não usa o identificador de publicidade do telefone (AdID) nem o ANDROID_ID, não registra as telas por conta própria e não permite personalizar anúncios. A análise de uso funciona com um identificador de instância do app: um número aleatório criado ao instalar o app e que muda se você o desinstalar.

O que é enviado:

- Quando o app é aberto e quanto tempo é usado, e a primeira vez que ele é aberto.
- O modelo do telefone, o idioma dele e as versões do Android e do app.
- Uma localização aproximada (o país ou a cidade), que o Google deduz do endereço IP. Não há localização precisa nem permissão de localização.
- Se a instalação veio de um link nosso —outro app da família ou um anúncio nosso—, o nome desse link (como «promo-matibu»). O app o lê do «install referrer» do Google Play, fica só com esse nome e descarta o resto, inclusive o identificador do clique. À parte, o Google Analytics lê esse mesmo dado por conta própria na primeira vez que o app é aberto, para saber de qual campanha veio a instalação.
- O idioma do app e se ele está no plano grátis ou em qual plano pago.
- Uma lista fechada de fatos de uso: que as boas-vindas terminaram ou foram puladas; que um nível terminou, de qual ilha e com quantas estrelas; que uma ilha ou o desafio do dia terminou; que o teste de 3 dias do Farol do Critério abriu ou fechou; que um limite do plano grátis foi atingido (os perfis ou o relatório); a entrada na Área dos Pais e a passagem pela porta dos adultos, que pedem apagar um perfil, restaurar uma compra e o que sai do app (se foi passada, se a digital respondeu ou se foi tocado um número errado; nunca a digital nem o número); os cadeados tocados e de qual tela; a tela de planos, o plano escolhido, como ela foi fechada e depois de quantos segundos, e se a compra começou, falhou ou foi restaurada; que uma avaliação no Google Play foi pedida; e qual outro app da família foi visto ou tocado na Área dos Pais.
- Se um adulto compra o Premium: o plano, o preço e a moeda, se o pagamento foi confirmado mais tarde (por exemplo, um pagamento em dinheiro) e se foi pago com o preço do presente de família. Nenhum dado de pagamento.
- Se uma compra não se completou: o motivo e o código que o Google Play deu (por exemplo, que foi cancelada, que o tempo acabou ou que o pagamento foi recusado por falta de saldo), em que passo da compra aconteceu, se o telefone tinha internet e, da conexão, se era por wi-fi ou por dados, se o Android restringia os dados do app (por exemplo, com a economia de dados) e se o telefone tem os serviços do Google.
- Ao carregar os planos: se foi possível trazer os preços do Google Play (e se foi ao pedi-los de novo ou com uns guardados de pouco antes), se o app foi instalado pelo Google Play ou por outra fonte, se roda em um aparelho de testes do Google (Firebase Test Lab), se havia internet, quantas tentativas o app fez e quantos segundos demorou, e o mesmo da conexão: se era por wi-fi ou por dados, se o Android restringia os dados do app e se o telefone tem os serviços do Google. Nunca o nome da rede, a operadora nem nenhum endereço. Serve para separar os testes automáticos das famílias de verdade e para saber o que acontece quando os preços não carregam.
- Se o app conseguiu guardar no telefone a ficha do Google Play dos planos (para abrir o pagamento mesmo que o Google Play demore a responder) e, se um pagamento foi aberto com ela, como terminou e se foi pago de saída com a que já estava guardada. A ficha vem do Google Play e não leva nada da criança nem do cartão.
- Do código para pagar em um celular e abrir em outro: que o código QR foi mostrado e de onde, que foi aberto no outro celular, que foi pago, que um aparelho foi aberto com ele, que foi criado um para abrir outro aparelho, que o link dele foi tocado para enviá-lo e, se algo falhou, o motivo e em que passo. Nunca o código.
- Do presente de família: que o desconto no passe dos nossos outros apps foi visto, que o link do presente foi aberto ou enviado e para qual deles, que um código de família deu o preço com desconto, de que app vinha e como chegou, ou por que não. Nunca o código.
- Que o aviso «Melhoramos o pagamento» foi visto e se foi tocado «Ver os planos» ou se foi fechado.

Se o app fechar por um erro, o Firebase Crashlytics envia um relatório técnico: o rastro do erro, o modelo do telefone, as versões do Android e do app e a hora. Sem nenhum dado da criança. Além disso, quando uma compra ou uma consulta ao Google Play falha por um erro da loja, o Crashlytics recebe um relatório mesmo que o app não feche, com o código e a mensagem que o Google Play deu, o passo da compra, o produto e o plano; ele também não leva nada da criança.

O que nunca vai nesses dados: o apelido ou o emoji de um perfil, a idade ou a faixa etária, as respostas aos desafios, nada que se escreva no app nem o identificador de publicidade. Cada evento tem uma lista fechada de valores permitidos, e o que não está nessa lista é descartado antes de sair; um teste automático do código vigia isso em cada versão.

Para quê: para saber quantas famílias instalam o app e continuam, que partes são usadas, qual app irmão ou anúncio nosso traz famílias que compram, e para encontrar e corrigir falhas. Medir de onde vêm as instalações é o que o Google Play chama de «publicidade ou marketing»; o app não mostra anúncios. Não vendemos esses dados e eles não são compartilhados com terceiros para publicidade. Os do Analytics se apagam sozinhos depois de 2 meses e os relatórios de falhas depois de 90 dias. O Google os trata como fornecedor do Firebase: firebase.google.com/support/privacy

---

## O que o app NÃO faz

- Não tem publicidade, de nenhum tipo nem de nenhuma rede, e não há perfis publicitários nem rastreamento entre aplicativos.
- Não há contas, cadastro nem login. Os dados de uso vão para o Firebase, que é do Google; o único servidor nosso é o do código para pagar em um celular e abrir em outro, e o app só fala com ele se um adulto usa esse código.
- Não há chat, nem conteúdo de outros usuários, nem forma de a criança escrever para alguém ou receber mensagens.
- Não há itens à venda dentro do jogo: as moedas se ganham resolvendo desafios e não podem ser compradas com dinheiro real. A única coisa paga é o Premium, e nenhum pagamento acontece sem a janela do Google Play, que mostra o preço e pede para confirmar.
- Não usa inteligência artificial. Houve um chat com IA durante o desenvolvimento e foi retirado antes de publicar; o diálogo do Gus é escrito à mão.
- Não vende informações a ninguém.

---

## A cobrança

O app pode ser usado sem pagar nada. O Premium, que é opcional, abre o restante do conteúdo e se paga por um tempo —um mês, três meses ou um ano, com um único pagamento e sem renovação automática— ou com um passe de pagamento único; em todos os casos quem cobra é o Google Play, na sua conta: nós não vemos nem recebemos seu cartão, seu nome ou seu endereço.

Para saber se há acesso Premium, o app pergunta ao Google Play se há uma assinatura ativa ou um passe comprado. Essa consulta não leva nenhum dado da criança nem do seu progresso, e se o telefone estiver sem conexão o jogo continua funcionando igual. Quando um adulto compra, a análise de uso registra o plano, o preço e a moeda (veja «Estatísticas e falhas»), nunca dados do cartão.

Para que pagar não falhe quando o Google Play tropeça, o app guarda no telefone a ficha dos planos que o Google Play entrega (o nome, os preços e as opções de compra; nada da criança nem seu) e paga com ela. Enquanto não a tiver, pede-a de novo ao Google Play de vez em quando —aos 15 minutos, em uma hora, em 6 horas e depois uma vez por dia—, só com internet e mesmo com o app fechado, com o agendador de tarefas do Android; quando a tem, para de pedir, e se já há acesso Premium não pede. Esse pedido não leva nada da criança nem do seu progresso.

Sem compras surpresa: a tela de planos abre sem a porta dos adultos, mas nada é cobrado sem a janela de pagamento do Google Play, que mostra o preço e pede para confirmar. Se seu filho usa o telefone sozinho, nas configurações do Google Play você pode exigir sua senha ou sua digital para cada compra, ou usar o Google Family Link.

Um plano por um tempo não é renovado sozinho: não há nada para cancelar. O app guarda no telefone até quando ele dura e, alguns dias antes de vencer (quinze no plano de um ano, três nos de um mês e de três meses), abre a tela de planos para avisar e oferecer estender; se não for estendido, o acesso se fecha sozinho ao vencer. Quem ainda tiver uma assinatura antiga, das que são renovadas, a gerencia ou cancela pelo Google Play, não por aqui; e se comprar um plano por um tempo, o Google Play a substitui por esse plano, então nunca ficam duas cobrando. Restaurar uma compra continua na Área dos Pais, atrás da porta dos adultos.

---

## Pagar em um celular e abrir em outro

Você pode pagar a versão completa pelo seu próprio celular: o aparelho da criança mostra um código QR, você o abre no seu celular, paga ali com a sua conta do Google Play e o aparelho da criança se abre sozinho. O código de 8 letras também pode ser digitado à mão, e na Área dos Pais, com “Abrir em outro aparelho”, uma mesma compra abre a versão completa em até 3 aparelhos.

Para isso, e só quando um adulto usa o código, o app fala com um servidor nosso de códigos de ativação (gusmar-activacion), que funciona no Cloud Functions e no Firestore do Google, como fornecedor. O que esse servidor guarda: o código; o produto e o comprovante da compra que o Google Play entrega, que não contém nome, e-mail nem dados de pagamento; um número de aparelho aleatório criado pelo app, que não é o identificador de publicidade, nem o ANDROID_ID, nem nenhum outro dado do celular; as datas de cada etapa (quando o código foi mostrado, aberto, pago e ativado); e, para limitar os pedidos e frear abusos, um resumo do endereço IP de cada pedido, apagado em no máximo um dia (os registros técnicos do Google Cloud guardam o endereço IP por até 30 dias). Um aparelho que só mostra o código envia o código e esse número; o que pagou envia também o comprovante do Google Play. Em cada aparelho, o app lembra o seu código e o seu número para continuar de onde parou, e um aparelho aberto com um código pergunta a esse servidor, no máximo uma vez por dia, se ele continua valendo.

Para quê: para confirmar com o Google Play que a compra é válida e continua vigente (se for reembolsada, deixa de abrir a versão completa), para abri-la em até 3 aparelhos e para evitar abusos. Esse número é um identificador usado só para o serviço funcionar: não é usado para publicidade, nem para montar perfis, nem para contatar ninguém, e não é compartilhado nem vendido.

Por quanto tempo: um código que ninguém paga é apagado depois de 2 dias; o de uma compra, enquanto a compra continuar vigente e até 90 dias depois; e um aparelho que não aparece por 60 dias libera a sua vaga. Se quiser que apaguemos antes, escreva para contacto@gusmarstudios.com com o código.

O presente de família: quem tem o passe vitalício de um dos nossos apps compra o dos outros com −70%. Para isso, esse mesmo servidor dá a essa compra um código de família, ligado ao comprovante do Google Play e sem o seu nome, o seu e-mail nem dados de pagamento, que o app mostra na Área dos Pais para enviá-lo aos outros; o app que o recebe (pelo link, pelo Google Play ao instalá-lo ou digitado à mão) o confirma com o servidor usando o seu número de aparelho, guarda-o no celular e o revisa uma vez por dia. Além disso, uma vez por dia o app pergunta ao servidor se o presente está ligado e em quais apps, sem enviar nada além desse número. O código de família é guardado enquanto o passe continuar vigente e até 90 dias depois de um reembolso.

---

## Permissões que o app pede

- Impressão digital ou reconhecimento facial (opcional, pode ser desligado): serve para um adulto confirmar o que a porta dos adultos pede —apagar um perfil, restaurar uma compra, abrir algo fora do app— sem tocar nos números. Quem verifica é o sistema operacional do telefone; o app nunca vê nem guarda sua digital, apenas recebe um "sim" ou um "não".
- Notificações (opcional, vem desligado): um único lembrete diário programado pelo próprio telefone, sem passar por nenhum servidor.

O app não pede microfone, nem câmera, nem localização, nem contatos, nem acesso aos seus arquivos. A localização aproximada de «Estatísticas e falhas» não vem de nenhuma permissão: o Google a deduz do endereço IP.

Para saber se há internet —e dizer ao adulto que se conecte, em vez de um erro do Google Play, e pedir os preços de novo quando ela volta—, o app consulta o estado da rede do telefone, com a permissão normal do Android que não pede nada ao instalar: se há conexão, se é por wi-fi ou por dados e se o Android restringe os dados do app. Não lê a qual rede você está conectado nem onde você está. E para saber se o telefone tem os serviços do Google e a Play Store (alguns, como os Amazon Fire, não os trazem, e aí o Google Play não consegue cobrar), o app pergunta ao sistema só por esses dois apps, sem ver quais outros você tem.

---

## A biblioteca de avisos e os identificadores

O lembrete diário opcional usa o componente de notificações do Android, que traz dentro uma biblioteca do Google —Firebase Cloud Messaging— que outros aplicativos usam para receber mensagens enviadas de um servidor e que, para isso, registra um identificador do aparelho.

O Cavila não usa essa função: não há mensagens de nenhum servidor, o app nunca pede esse identificador de envio, a inicialização automática da biblioteca está desligada e a permissão para receber esse tipo de mensagem está bloqueada. O aviso é montado inteiro dentro do telefone e funciona em modo avião.

O que o app usa, sim, são dois identificadores técnicos do Firebase: o de instância do Analytics e o de instalação que o Crashlytics usa para agrupar os relatórios de falhas. Os dois são números aleatórios criados pelo app, não ficam ligados a nenhum nome, não são o identificador de publicidade e são reiniciados se você desinstalar o app. Por isso declaramos «IDs de dispositivo ou outros» no formulário de segurança dos dados do Google Play.

O app usa também a biblioteca do Google Play para atualizar dentro do app: ao abrir, pergunta ao Google Play, no próprio telefone, se há uma versão nova e, se for importante, abre a tela do Google Play para instalá-la, no máximo uma vez por dia. Essa consulta o Google Play responde com a versão disponível; não leva nada da criança nem do seu progresso, e o app só guarda no telefone o dia em que pediu.

---

## Leitura em voz alta

O app pode ler os textos em voz alta usando o motor de texto para fala já instalado no telefone. A única coisa entregue a esse motor são os textos do próprio app —os desafios e os fatos do Ninho do Gus—: nunca nada que a criança tenha escrito.

Esse motor faz parte do sistema operacional e segue a política de privacidade do fabricante do telefone.

---

## Crianças

O Cavila é pensado para crianças e segue as políticas do Google Play para famílias. Não coletamos o nome da criança, nem o e-mail, nem a localização precisa, nem a idade: a análise de uso mede como o app é usado com um número de instalação aleatório, sem saber quem o usa, e o progresso dela fica no telefone. Não há publicidade, nem perfis publicitários, nem rastreamento entre aplicativos, nem conteúdo gerado por outros usuários, nem forma de uma criança entrar em contato com um desconhecido dentro do app.

A Área dos Pais abre sem porta: ver o relatório e mudar os ajustes não tem nada de delicado. O que não tem volta ou sai do app —apagar um perfil, restaurar uma compra, escrever um e-mail para nós, abrir outro dos nossos apps no Google Play, enviar o link que abre o app em outro aparelho ou abrir e enviar o link do presente de família— pede uma porta que exige tocar no maior número ou confirmar com a digital. A tela de planos não tem essa porta, mas nenhum pagamento acontece sem a janela do Google Play (veja «A cobrança»).

---

## Como apagar os dados

Na tela de perfis você pode apagar um perfil com todo o progresso dele. Para apagar tudo o que está no telefone, desinstale o app: o progresso, os perfis e os ajustes não têm cópia em outro lugar, então são apagados por completo. Desinstalar também reinicia os identificadores do Firebase: se você instalar de novo, começam outros. Se o código para pagar em um celular e abrir em outro foi usado, o que o nosso servidor guarda é apagado sozinho nos prazos dessa seção, ou antes se você nos escrever com o código.

O que já foi enviado ao Firebase não se apaga ao desinstalar, mas expira sozinho: os dados do Analytics depois de 2 meses e os relatórios de falhas depois de 90 dias. Se quiser pedir que sejam apagados antes, ou tiver qualquer dúvida, escreva para contacto@gusmarstudios.com. Como esses dados não levam nome, e-mail nem nada que diga de quem são, pode ser que não tenhamos como encontrar os de um telefone em particular; por isso eles expiram sozinhos.

---

## Mudanças nesta política

Se alguma versão futura mudar algo disto, este texto e a data acima são atualizados antes que essa versão chegue ao Google Play. A revisão de 1º de outubro de 2026 acrescentou o Google Analytics para Firebase e o Firebase Crashlytics, que o app não usava antes. A de 15 de outubro de 2026 acrescentou que pagar não passa mais pela porta dos adultos, o motivo de uma compra que não se completa, o carregamento dos preços do Google Play junto com a fonte da instalação e o aparelho de testes, os erros da loja enviados ao Crashlytics e que o Google Analytics lê por conta própria o link da instalação. O que se coleta é o mesmo: só está mais bem explicado. A revisão de 21 de outubro de 2026 acrescentou os planos por um tempo sem renovação automática (com o aviso antes de vencerem e o que o app guarda para dá-lo); a atualização dentro do app com a biblioteca do Google Play; pagar em um celular e abrir em outro com um código, e o servidor da família que torna isso possível; o presente de família; que a Área dos Pais se abre sem porta (pedem a porta o delicado e o que sai do app); que a ficha dos planos do Google Play fique guardada no telefone e, enquanto faltar, seja pedida em segundo plano com o app fechado; e, nas medições, o tipo de rede (wi-fi ou dados, e se o Android restringia os dados do app), se o telefone tem os serviços do Google, quanto demorou a carga dos preços e os fatos novos do código do QR e do aviso «Melhoramos o pagamento».

---

## Contato

Para qualquer dúvida sobre privacidade, escreva para contacto@gusmarstudios.com.
