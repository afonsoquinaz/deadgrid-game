# DEADGRID — Privacy Policy

**Languages:** [English](#en) · [Português (Portugal)](#pt-pt) · [Português (Brasil)](#pt-br) · [Deutsch](#de) · [Español](#es) · [Français](#fr)

---

<a id="en"></a>

## English

**Last updated: 27 September 2026**

**Contents:** [Summary](#en-1) · [Stored on your device](#en-2) · [Our game server](#en-3) · [Visible to other players](#en-4) · [Purchases](#en-5) · [Ads (Google AdMob)](#en-6) · [Notifications and sharing](#en-7) · [Who receives data](#en-8) · [Retention](#en-9) · [Your rights and deleting your data](#en-10) · [Children](#en-11) · [Security](#en-12) · [Changes and contact](#en-13)

This policy explains what data the DEADGRID game (version 3 and later, for iOS and Android) uses, where it goes and why. DEADGRID is developed by **Afonso Quinaz** ("we", "us"). Contact: [support@deadgridgame.com](mailto:support@deadgridgame.com).

<a id="en-1"></a>
### 1. Summary

* To play you choose a **username**. We do **not** ask for your real name, email address, phone number, contacts, photos or precise location.
* Your progress is saved on your device **and synced to our game server** (hosted on Supabase), so it is backed up and can be recovered on a new phone.
* Your username and game results are **visible to other players** (leaderboards, profiles, friends, online matches).
* Online **Duo co-op** and **Ranked** duels send game data in real time between you and the other player through our server.
* Payments are handled by **Apple** (App Store) or **Google** (Google Play). To deliver coins, the purchase receipt is checked by our server.
* The game is free. On iOS it shows **one short ad after every 10 finished games**, served by **Google AdMob**. You decide about ad tracking and ad consent.
* We do **not sell** your personal data.

<a id="en-2"></a>
### 2. Data stored on your device

* **Save file:** your progress (coins, skins, weapons, pass, Climb level, missions, records and so on), your settings (language, sound, graphics, frame rate, vibration), purchases already delivered, and a snapshot to resume a run after a crash.
* **Identity backup:** a random device ID created by the game, your profile ID and your username. The device ID is **not** Apple's or Google's advertising identifier and not a hardware identifier.
* **Ad choices:** whether the ad-privacy question has been asked; your consent choice itself is stored on the device by Google's consent software.
* **Coming from DEADGRID 2:** on the first launch of DEADGRID 3, the game reads the save of the previous version **on the same device** to carry your progress over. This happens locally.

These files live in the app's private storage and are removed when you delete the app. Deleting the app does **not** delete your account on our server (see [section 10](#en-10)).

<a id="en-3"></a>
### 3. Data processed by our game server

Our backend runs on **Supabase**, a hosting provider that processes data on our behalf. The app sends it:

| What | Details | Why |
|---|---|---|
| **Account** | random device ID, profile ID, username, account creation date. **Optional password** (if you protect your account): the server stores only a hash of it and a hash of the one-time recovery code; failed sign-in attempts are recorded to block password guessing. | to create your account, recognise your device, let you sign in on another device |
| **Progress** | coins, game pass, skins, emotes, weapon finishes, islands, missions, specs, bonuses, season, Climb level, daily streak, revives, rank points, wins and losses, crests, referrals (who invited whom) | backup, restore and sync of your progress |
| **Scores and matches** | score, wave, kills, time survived, mode, map, result, partner's or rival's username, date | leaderboards, match history, tournaments, crests |
| **Activity and diagnostics** | last-seen time, whether you are in a menu or in a game, app version; session start and last activity; start and end of each game (mode, duration, how it ended); a network latency measurement for Ranked matchmaking; if an online match fails, one automatic connection report (connection statistics with your username and profile ID) | online status for friends, keeping the service working, fixing bugs, knowing which versions are still in use |
| **Social** | friend requests and friendships, Duo invites, matchmaking and Ranked queue entries, tournament entries and rewards | friends, invites, matchmaking, tournaments |
| **Live match data** | during Duo and Ranked: positions, actions and game events, emotes and preset quick-chat phrases, relayed to the other player | to play together in real time. There is no free-text chat and no voice chat. |
| **Messages to us** | the text you write in SETTINGS → MESSAGE THE TEAM, with your username, profile ID and app version | to read and answer your feedback |
| **Purchases** | product, transaction ID, store (App Store / Google Play), the App Store receipt or Google Play purchase token, coins granted, date | to check the purchase is real and deliver the coins exactly once |

Like any internet service, our hosting provider receives your **IP address** when the app connects; it may appear in the provider's technical logs. We do not store it in our game data and do not use it to locate you.

<a id="en-4"></a>
### 4. What other players can see

Your **username**, character skin, island and weapon rack, scores, ranks, pass tier, streak, crests and profile statistics, your online / in-game status (for friends and in player suggestions), and your username in other players' match history. Please do not use your real name or other personal information as your username.

<a id="en-5"></a>
### 5. In-app purchases

Payments are processed by **Apple** or **Google**; we never see your card or payment details. To deliver coins, the app sends the transaction ID and the receipt (iOS: App Store receipt; Android: purchase token) to a function on our server, which checks it with Apple or Google and records that the coins were delivered. If a paid purchase has not arrived, **RESTORE PURCHASES** on the GET COINS screen checks again. Apple's and Google's own privacy policies apply to the payment itself.

<a id="en-6"></a>
### 6. Advertising (Google AdMob)

* DEADGRID is free. In the **iOS** version it shows **one short full-screen ad after every 10 finished games**, at the next break (for example when you return to the menu). There are no ads during a match.
* Ads are served by **Google AdMob** (Google LLC; in the EEA and UK, Google Ireland Limited).
* Before the first ad, iOS may ask whether DEADGRID can **track** you (Apple App Tracking Transparency) and, in the EEA, the UK and other places where it is required, Google's **consent form** asks for your ad choices.
* **Data AdMob may collect:** device identifiers — including the advertising identifier (IDFA) **only if you allow tracking**; your IP address and the coarse location derived from it; device and app information (such as model, operating system, language); ad interactions (ads shown and taps); diagnostic and performance data.
* **Why:** to show ads, measure them, limit how often you see the same ad, prevent fraud and — only with your consent / permission — personalise ads. Without it, Google shows non-personalised or limited ads, which still use some data for these basic purposes.
* We do **not** send your username, account or game progress to Google, and we do not receive your advertising identifier.
* Google privacy policy: <https://policies.google.com/privacy> · How Google uses data from apps that use its services: <https://policies.google.com/technologies/partner-sites>
* **Change your choices at any time:** in the game, **SETTINGS → AD PRIVACY CHOICES** (shown when it applies to you); on iPhone, **Settings → Privacy & Security → Tracking**.

<a id="en-7"></a>
### 7. Notifications and sharing

* **Notifications** (for example "your free chest is ready") are **local**: they are scheduled on your device and only if you allow them. No push server is used and no notification token is sent anywhere. Turn them off in iOS **Settings → Notifications → DEADGRID**.
* **Sharing:** when you tap a share button, your phone's share sheet opens with an invite text (your username and a store link). It goes only where you choose to send it.

<a id="en-8"></a>
### 8. Who receives data

* **Supabase** — hosts our game server (on our behalf).
* **Apple** and **Google** — app stores and payments.
* **Google AdMob** — advertising, as described in [section 6](#en-6).
* **Other players** — the public information in [section 4](#en-4).
* **Authorities** — only if the law requires it.

These providers may process data in countries other than yours. We do not sell your personal data.

<a id="en-9"></a>
### 9. How long we keep data

* Account and progress data: as long as your account exists, so you can get your progress back.
* Matchmaking and queue entries: removed automatically after about 2 minutes; Duo invites expire after 60 seconds.
* Scores and match history: as long as the account exists (they make up the leaderboards).
* Messages to us and connection reports: as long as needed for support and bug fixing.
* Purchase records: as long as needed to prevent duplicate deliveries and to meet accounting and legal duties.

<a id="en-10"></a>
### 10. Your rights and deleting your data

Depending on where you live (for example under the GDPR in the EEA and UK, or under California law), you may have the right to access, correct, delete or receive a copy of your data, and to object to or restrict some uses.

* **Deleting your account:** the game does not have an in-app delete button yet. Email [support@deadgridgame.com](mailto:support@deadgridgame.com) with your **username** and ask for deletion. We may ask you to confirm the account is yours. We will delete or anonymise your account data within 30 days, except records we must keep by law (such as purchase records).
* **Other requests** (access, correction, a copy): the same email address.
* **Ads and tracking:** see [section 6](#en-6). **Notifications:** see [section 7](#en-7).
* **Local data:** deleting the app removes the data stored on your device.
* If you are in the EEA or UK, we rely on: performing our agreement with you (running the game and its online features), our legitimate interests (security, fraud prevention, diagnostics, usage statistics), your consent (personalised ads, tracking, notifications) and legal obligations. You can also complain to your local data protection authority.

<a id="en-11"></a>
### 11. Children

DEADGRID is **not directed to children under 13** (or the higher minimum age where you live). We do not knowingly collect personal data from children under 13. If you believe a child has given us personal data, email us and we will delete it. Personalised ads are only shown when tracking is allowed and consent is given; parents can prevent this in iOS **Settings → Privacy & Security → Tracking** (switch off "Allow Apps to Request to Track") and with Screen Time.

<a id="en-12"></a>
### 12. Security

The app talks to our server over encrypted connections (HTTPS / WSS), and passwords are stored only as hashes. No system is perfectly secure, so please use a password you do not use anywhere else.

<a id="en-13"></a>
### 13. Changes and contact

We may update this policy when the game changes. The new version will be posted here with a new date.

**Developer:** Afonso Quinaz
**Email:** [support@deadgridgame.com](mailto:support@deadgridgame.com)
**Website:** <https://github.com/afonsoquinaz/deadgrid-game>

---

<a id="pt-pt"></a>

## Português (Portugal)

**Última atualização: 27 de setembro de 2026**

**Índice:** [Resumo](#pt-pt-1) · [Guardado no teu dispositivo](#pt-pt-2) · [O nosso servidor](#pt-pt-3) · [Visível para outros jogadores](#pt-pt-4) · [Compras](#pt-pt-5) · [Anúncios (Google AdMob)](#pt-pt-6) · [Notificações e partilha](#pt-pt-7) · [Quem recebe dados](#pt-pt-8) · [Conservação](#pt-pt-9) · [Os teus direitos e apagar os teus dados](#pt-pt-10) · [Crianças](#pt-pt-11) · [Segurança](#pt-pt-12) · [Alterações e contacto](#pt-pt-13)

Esta política explica que dados o jogo DEADGRID (versão 3 e seguintes, para iOS e Android) utiliza, para onde vão e porquê. O DEADGRID é desenvolvido por **Afonso Quinaz** ("nós"). Contacto: [support@deadgridgame.com](mailto:support@deadgridgame.com).

<a id="pt-pt-1"></a>
### 1. Resumo

* Para jogar escolhes um **nome de utilizador**. **Não** pedimos o teu nome verdadeiro, email, número de telefone, contactos, fotografias nem localização precisa.
* O teu progresso é guardado no teu dispositivo **e sincronizado com o nosso servidor de jogo** (alojado na Supabase), para ficar com cópia de segurança e poder ser recuperado num telemóvel novo.
* O teu nome de utilizador e os teus resultados são **visíveis para outros jogadores** (classificações, perfis, amigos, partidas online).
* O **Duo cooperativo** e os duelos **Ranked** online enviam dados do jogo em tempo real entre ti e o outro jogador através do nosso servidor.
* Os pagamentos são tratados pela **Apple** (App Store) ou pela **Google** (Google Play). Para entregar as moedas, o recibo da compra é verificado pelo nosso servidor.
* O jogo é gratuito. No iOS mostra **um anúncio curto a cada 10 jogos terminados**, servido pelo **Google AdMob**. Tu decides sobre o rastreio e o consentimento de anúncios.
* **Não vendemos** os teus dados pessoais.

<a id="pt-pt-2"></a>
### 2. Dados guardados no teu dispositivo

* **Ficheiro de jogo:** o teu progresso (moedas, skins, armas, passe, nível da Escalada, missões, recordes, etc.), as tuas definições (idioma, som, gráficos, taxa de fotogramas, vibração), as compras já entregues e uma cópia para retomar uma partida depois de uma falha.
* **Cópia da identidade:** um ID de dispositivo aleatório criado pelo jogo, o teu ID de perfil e o teu nome de utilizador. Este ID **não** é o identificador de publicidade da Apple ou da Google nem um identificador de hardware.
* **Escolhas de anúncios:** se a pergunta sobre privacidade dos anúncios já foi feita; a tua escolha de consentimento é guardada no dispositivo pelo software de consentimento da Google.
* **Vindo do DEADGRID 2:** no primeiro arranque do DEADGRID 3, o jogo lê o ficheiro da versão anterior **no mesmo dispositivo** para trazer o teu progresso. Isto acontece localmente.

Estes ficheiros ficam no armazenamento privado da app e são removidos quando apagas a app. Apagar a app **não** apaga a tua conta no nosso servidor (ver [secção 10](#pt-pt-10)).

<a id="pt-pt-3"></a>
### 3. Dados tratados pelo nosso servidor de jogo

O nosso servidor funciona na **Supabase**, um fornecedor de alojamento que trata os dados em nosso nome. A app envia-lhe:

| O quê | Detalhes | Porquê |
|---|---|---|
| **Conta** | ID de dispositivo aleatório, ID de perfil, nome de utilizador, data de criação. **Palavra-passe opcional** (se protegeres a conta): o servidor guarda apenas um hash dela e um hash do código de recuperação de uso único; as tentativas de início de sessão falhadas são registadas para bloquear quem tente adivinhar palavras-passe. | criar a tua conta, reconhecer o teu dispositivo, permitir iniciar sessão noutro dispositivo |
| **Progresso** | moedas, passe de jogo, skins, emotes, acabamentos de armas, ilhas, missões, specs, bónus, temporada, nível da Escalada, sequência diária, revives, pontos de rank, vitórias e derrotas, brasões, convites (quem convidou quem) | cópia de segurança, recuperação e sincronização do progresso |
| **Pontuações e partidas** | pontuação, vaga, abates, tempo sobrevivido, modo, mapa, resultado, nome do parceiro ou rival, data | classificações, histórico, torneios, brasões |
| **Atividade e diagnóstico** | hora da última presença, se estás num menu ou num jogo, versão da app; início da sessão e última atividade; início e fim de cada jogo (modo, duração, como terminou); uma medição de latência para o emparelhamento Ranked; se uma partida online falhar, um relatório automático de ligação (estatísticas da ligação com o teu nome de utilizador e ID de perfil) | estado online para amigos, manter o serviço a funcionar, corrigir erros, saber que versões ainda são usadas |
| **Social** | pedidos de amizade e amizades, convites Duo, entradas nas filas de emparelhamento e Ranked, inscrições e prémios de torneios | amigos, convites, emparelhamento, torneios |
| **Dados da partida em direto** | no Duo e no Ranked: posições, ações e eventos do jogo, emotes e frases rápidas predefinidas, reencaminhados para o outro jogador | jogar em conjunto em tempo real. Não há chat de texto livre nem chat de voz. |
| **Mensagens para nós** | o texto que escreves em DEFINIÇÕES → MENSAGEM PARA A EQUIPA, com o teu nome de utilizador, ID de perfil e versão da app | ler e responder ao teu feedback |
| **Compras** | produto, ID da transação, loja (App Store / Google Play), o recibo da App Store ou o token de compra do Google Play, moedas entregues, data | confirmar que a compra é real e entregar as moedas uma única vez |

Como qualquer serviço na internet, o nosso fornecedor de alojamento recebe o teu **endereço IP** quando a app se liga; pode aparecer nos registos técnicos do fornecedor. Não o guardamos nos dados do jogo nem o usamos para te localizar.

<a id="pt-pt-4"></a>
### 4. O que os outros jogadores podem ver

O teu **nome de utilizador**, a skin da personagem, a ilha e o expositor de armas, pontuações, ranks, nível do passe, sequência, brasões e estatísticas do perfil, o teu estado online / em jogo (para amigos e nas sugestões de jogadores) e o teu nome no histórico de partidas de outros jogadores. Por favor, não uses o teu nome verdadeiro nem outros dados pessoais como nome de utilizador.

<a id="pt-pt-5"></a>
### 5. Compras na app

Os pagamentos são processados pela **Apple** ou pela **Google**; nunca vemos o teu cartão nem os teus dados de pagamento. Para entregar as moedas, a app envia o ID da transação e o recibo (iOS: recibo da App Store; Android: token de compra) para uma função no nosso servidor, que o verifica junto da Apple ou da Google e regista a entrega. Se uma compra paga não tiver chegado, **RESTAURAR COMPRAS** no ecrã OBTER MOEDAS verifica de novo. Ao pagamento em si aplicam-se as políticas de privacidade da Apple e da Google.

<a id="pt-pt-6"></a>
### 6. Publicidade (Google AdMob)

* O DEADGRID é gratuito. Na versão **iOS** mostra **um anúncio curto em ecrã inteiro a cada 10 jogos terminados**, na pausa seguinte (por exemplo, quando voltas ao menu). Não há anúncios durante uma partida.
* Os anúncios são servidos pelo **Google AdMob** (Google LLC; no EEE e no Reino Unido, Google Ireland Limited).
* Antes do primeiro anúncio, o iOS pode perguntar se o DEADGRID te pode **rastrear** (Transparência do Rastreio de Apps da Apple) e, no EEE, no Reino Unido e noutros locais onde é obrigatório, o **formulário de consentimento** da Google pede as tuas escolhas sobre anúncios.
* **Dados que o AdMob pode recolher:** identificadores do dispositivo — incluindo o identificador de publicidade (IDFA) **apenas se permitires o rastreio**; o teu endereço IP e a localização aproximada que dele resulta; informação do dispositivo e da app (como modelo, sistema operativo, idioma); interações com anúncios (anúncios mostrados e toques); dados de diagnóstico e desempenho.
* **Porquê:** mostrar anúncios, medi-los, limitar quantas vezes vês o mesmo anúncio, prevenir fraude e — só com o teu consentimento / autorização — personalizar anúncios. Sem isso, a Google mostra anúncios não personalizados ou limitados, que ainda usam alguns dados para estes fins básicos.
* **Não** enviamos à Google o teu nome de utilizador, conta ou progresso, e não recebemos o teu identificador de publicidade.
* Política de privacidade da Google: <https://policies.google.com/privacy> · Como a Google usa dados de apps que utilizam os seus serviços: <https://policies.google.com/technologies/partner-sites>
* **Muda as tuas escolhas quando quiseres:** no jogo, **DEFINIÇÕES → PRIVACIDADE DOS ANÚNCIOS** (em inglês: SETTINGS → AD PRIVACY CHOICES; aparece quando se aplica a ti); no iPhone, **Definições → Privacidade e segurança → Rastreio**.

<a id="pt-pt-7"></a>
### 7. Notificações e partilha

* As **notificações** (por exemplo "o teu baú grátis está pronto") são **locais**: são agendadas no teu dispositivo e só se as autorizares. Não é usado nenhum servidor de notificações push e nenhum token de notificação é enviado. Desliga-as em **Definições → Notificações → DEADGRID** no iOS.
* **Partilha:** quando tocas num botão de partilha, abre-se o menu de partilha do telemóvel com um texto de convite (o teu nome de utilizador e um link da loja). Só vai para onde tu escolheres.

<a id="pt-pt-8"></a>
### 8. Quem recebe dados

* **Supabase** — aloja o nosso servidor de jogo (em nosso nome).
* **Apple** e **Google** — lojas de apps e pagamentos.
* **Google AdMob** — publicidade, como descrito na [secção 6](#pt-pt-6).
* **Outros jogadores** — a informação pública da [secção 4](#pt-pt-4).
* **Autoridades** — apenas se a lei o exigir.

Estes fornecedores podem tratar dados noutros países que não o teu. Não vendemos os teus dados pessoais.

<a id="pt-pt-9"></a>
### 9. Durante quanto tempo guardamos os dados

* Dados da conta e do progresso: enquanto a tua conta existir, para poderes recuperar o progresso.
* Entradas nas filas de emparelhamento: removidas automaticamente após cerca de 2 minutos; os convites Duo expiram após 60 segundos.
* Pontuações e histórico de partidas: enquanto a conta existir (formam as classificações).
* Mensagens para nós e relatórios de ligação: o tempo necessário para o suporte e a correção de erros.
* Registos de compras: o tempo necessário para evitar entregas duplicadas e cumprir obrigações contabilísticas e legais.

<a id="pt-pt-10"></a>
### 10. Os teus direitos e apagar os teus dados

Dependendo de onde vives (por exemplo, ao abrigo do RGPD no EEE e no Reino Unido, ou da lei da Califórnia), podes ter direito a aceder, corrigir, apagar ou receber uma cópia dos teus dados, e a opor-te a alguns usos ou limitá-los.

* **Apagar a tua conta:** o jogo ainda não tem um botão para apagar a conta. Envia um email para [support@deadgridgame.com](mailto:support@deadgridgame.com) com o teu **nome de utilizador** a pedir a eliminação. Podemos pedir-te que confirmes que a conta é tua. Apagaremos ou anonimizaremos os dados da conta no prazo de 30 dias, exceto registos que a lei nos obrigue a manter (como registos de compras).
* **Outros pedidos** (acesso, correção, cópia): o mesmo endereço de email.
* **Anúncios e rastreio:** ver [secção 6](#pt-pt-6). **Notificações:** ver [secção 7](#pt-pt-7).
* **Dados locais:** apagar a app remove os dados guardados no teu dispositivo.
* Se estiveres no EEE ou no Reino Unido, baseamo-nos em: execução do nosso acordo contigo (fazer funcionar o jogo e as funções online), os nossos interesses legítimos (segurança, prevenção de fraude, diagnóstico, estatísticas de utilização), o teu consentimento (anúncios personalizados, rastreio, notificações) e obrigações legais. Podes também apresentar reclamação à autoridade de proteção de dados do teu país (em Portugal, a CNPD).

<a id="pt-pt-11"></a>
### 11. Crianças

O DEADGRID **não se destina a crianças com menos de 13 anos** (ou a idade mínima mais alta aplicável no teu país). Não recolhemos intencionalmente dados pessoais de crianças com menos de 13 anos. Se achares que uma criança nos deu dados pessoais, envia-nos um email e apagá-los-emos. Os anúncios personalizados só são mostrados quando o rastreio é permitido e o consentimento é dado; os pais podem impedi-lo em **Definições → Privacidade e segurança → Rastreio** no iOS (desligando "Permitir pedidos de rastreio das apps") e com o Tempo de ecrã.

<a id="pt-pt-12"></a>
### 12. Segurança

A app comunica com o nosso servidor através de ligações encriptadas (HTTPS / WSS) e as palavras-passe são guardadas apenas como hash. Nenhum sistema é totalmente seguro, por isso usa uma palavra-passe que não uses em mais lado nenhum.

<a id="pt-pt-13"></a>
### 13. Alterações e contacto

Podemos atualizar esta política quando o jogo mudar. A nova versão será publicada aqui com uma nova data.

**Programador:** Afonso Quinaz
**Email:** [support@deadgridgame.com](mailto:support@deadgridgame.com)
**Website:** <https://github.com/afonsoquinaz/deadgrid-game>

---

<a id="pt-br"></a>

## Português (Brasil)

**Última atualização: 27 de setembro de 2026**

**Sumário:** [Resumo](#pt-br-1) · [Salvo no seu aparelho](#pt-br-2) · [Nosso servidor](#pt-br-3) · [Visível para outros jogadores](#pt-br-4) · [Compras](#pt-br-5) · [Anúncios (Google AdMob)](#pt-br-6) · [Notificações e compartilhamento](#pt-br-7) · [Quem recebe dados](#pt-br-8) · [Retenção](#pt-br-9) · [Seus direitos e exclusão dos dados](#pt-br-10) · [Crianças](#pt-br-11) · [Segurança](#pt-br-12) · [Alterações e contato](#pt-br-13)

Esta política explica quais dados o jogo DEADGRID (versão 3 em diante, para iOS e Android) usa, para onde eles vão e por quê. O DEADGRID é desenvolvido por **Afonso Quinaz** ("nós"). Contato: [support@deadgridgame.com](mailto:support@deadgridgame.com).

<a id="pt-br-1"></a>
### 1. Resumo

* Para jogar, você escolhe um **nome de usuário**. **Não** pedimos seu nome real, e-mail, número de telefone, contatos, fotos nem localização precisa.
* Seu progresso é salvo no seu aparelho **e sincronizado com nosso servidor de jogo** (hospedado na Supabase), para ter backup e poder ser recuperado em um celular novo.
* Seu nome de usuário e seus resultados são **visíveis para outros jogadores** (rankings, perfis, amigos, partidas online).
* O **Duo cooperativo** e os duelos **Ranked** online enviam dados do jogo em tempo real entre você e o outro jogador por meio do nosso servidor.
* Os pagamentos são processados pela **Apple** (App Store) ou pelo **Google** (Google Play). Para entregar as moedas, o recibo da compra é verificado pelo nosso servidor.
* O jogo é gratuito. No iOS ele mostra **um anúncio curto a cada 10 partidas terminadas**, exibido pelo **Google AdMob**. Você decide sobre rastreamento e consentimento de anúncios.
* **Não vendemos** seus dados pessoais.

<a id="pt-br-2"></a>
### 2. Dados salvos no seu aparelho

* **Arquivo de jogo:** seu progresso (moedas, skins, armas, passe, nível da Escalada, missões, recordes etc.), suas configurações (idioma, som, gráficos, taxa de quadros, vibração), as compras já entregues e uma cópia para retomar uma partida depois de um travamento.
* **Backup da identidade:** um ID de dispositivo aleatório criado pelo jogo, seu ID de perfil e seu nome de usuário. Esse ID **não** é o identificador de publicidade da Apple ou do Google nem um identificador de hardware.
* **Escolhas de anúncios:** se a pergunta sobre privacidade de anúncios já foi feita; sua escolha de consentimento fica salva no aparelho pelo software de consentimento do Google.
* **Vindo do DEADGRID 2:** na primeira abertura do DEADGRID 3, o jogo lê o arquivo salvo da versão anterior **no mesmo aparelho** para trazer seu progresso. Isso acontece localmente.

Esses arquivos ficam no armazenamento privado do app e são removidos quando você exclui o app. Excluir o app **não** exclui sua conta no nosso servidor (veja a [seção 10](#pt-br-10)).

<a id="pt-br-3"></a>
### 3. Dados tratados pelo nosso servidor de jogo

Nosso servidor roda na **Supabase**, um provedor de hospedagem que trata os dados em nosso nome. O app envia a ela:

| O quê | Detalhes | Por quê |
|---|---|---|
| **Conta** | ID de dispositivo aleatório, ID de perfil, nome de usuário, data de criação. **Senha opcional** (se você proteger a conta): o servidor guarda apenas um hash dela e um hash do código de recuperação de uso único; tentativas de login com falha são registradas para bloquear quem tenta adivinhar senhas. | criar sua conta, reconhecer seu aparelho, permitir login em outro aparelho |
| **Progresso** | moedas, passe do jogo, skins, emotes, acabamentos de armas, ilhas, missões, specs, bônus, temporada, nível da Escalada, sequência diária, revives, pontos de rank, vitórias e derrotas, brasões, indicações (quem convidou quem) | backup, recuperação e sincronização do progresso |
| **Pontuações e partidas** | pontuação, onda, abates, tempo sobrevivido, modo, mapa, resultado, nome do parceiro ou rival, data | rankings, histórico, torneios, brasões |
| **Atividade e diagnóstico** | horário em que foi visto por último, se você está em um menu ou em uma partida, versão do app; início da sessão e última atividade; início e fim de cada partida (modo, duração, como terminou); uma medição de latência para o pareamento Ranked; se uma partida online falhar, um relatório automático de conexão (estatísticas da conexão com seu nome de usuário e ID de perfil) | status online para amigos, manter o serviço funcionando, corrigir bugs, saber quais versões ainda estão em uso |
| **Social** | pedidos de amizade e amizades, convites Duo, entradas nas filas de pareamento e Ranked, inscrições e prêmios de torneios | amigos, convites, pareamento, torneios |
| **Dados da partida ao vivo** | no Duo e no Ranked: posições, ações e eventos do jogo, emotes e frases rápidas predefinidas, repassados ao outro jogador | jogar juntos em tempo real. Não há chat de texto livre nem chat de voz. |
| **Mensagens para nós** | o texto que você escreve em DEFINIÇÕES → MENSAGEM PARA A EQUIPA, com seu nome de usuário, ID de perfil e versão do app | ler e responder seu feedback |
| **Compras** | produto, ID da transação, loja (App Store / Google Play), o recibo da App Store ou o token de compra do Google Play, moedas entregues, data | confirmar que a compra é real e entregar as moedas uma única vez |

Como qualquer serviço na internet, nosso provedor de hospedagem recebe seu **endereço IP** quando o app se conecta; ele pode aparecer nos registros técnicos do provedor. Não o guardamos nos dados do jogo nem o usamos para localizar você.

<a id="pt-br-4"></a>
### 4. O que outros jogadores podem ver

Seu **nome de usuário**, a skin do personagem, a ilha e o expositor de armas, pontuações, ranks, nível do passe, sequência, brasões e estatísticas do perfil, seu status online / em partida (para amigos e nas sugestões de jogadores) e seu nome no histórico de partidas de outros jogadores. Por favor, não use seu nome real nem outros dados pessoais como nome de usuário.

<a id="pt-br-5"></a>
### 5. Compras no app

Os pagamentos são processados pela **Apple** ou pelo **Google**; nunca vemos seu cartão nem seus dados de pagamento. Para entregar as moedas, o app envia o ID da transação e o recibo (iOS: recibo da App Store; Android: token de compra) para uma função no nosso servidor, que o verifica com a Apple ou o Google e registra a entrega. Se uma compra paga não tiver chegado, **RESTAURAR COMPRAS** na tela OBTER MOEDAS verifica de novo. Ao pagamento em si se aplicam as políticas de privacidade da Apple e do Google.

<a id="pt-br-6"></a>
### 6. Publicidade (Google AdMob)

* O DEADGRID é gratuito. Na versão **iOS** ele mostra **um anúncio curto em tela cheia a cada 10 partidas terminadas**, na pausa seguinte (por exemplo, quando você volta ao menu). Não há anúncios durante uma partida.
* Os anúncios são exibidos pelo **Google AdMob** (Google LLC; no EEE e no Reino Unido, Google Ireland Limited).
* Antes do primeiro anúncio, o iOS pode perguntar se o DEADGRID pode **rastrear** você (Transparência de Rastreamento de Apps da Apple) e, no EEE, no Reino Unido e em outros lugares onde é exigido, o **formulário de consentimento** do Google pede suas escolhas sobre anúncios.
* **Dados que o AdMob pode coletar:** identificadores do dispositivo — incluindo o identificador de publicidade (IDFA) **somente se você permitir o rastreamento**; seu endereço IP e a localização aproximada obtida a partir dele; informações do aparelho e do app (como modelo, sistema operacional, idioma); interações com anúncios (anúncios exibidos e toques); dados de diagnóstico e desempenho.
* **Por quê:** exibir anúncios, medi-los, limitar quantas vezes você vê o mesmo anúncio, prevenir fraudes e — somente com seu consentimento / permissão — personalizar anúncios. Sem isso, o Google mostra anúncios não personalizados ou limitados, que ainda usam alguns dados para essas finalidades básicas.
* **Não** enviamos ao Google seu nome de usuário, conta ou progresso, e não recebemos seu identificador de publicidade.
* Política de privacidade do Google: <https://policies.google.com/privacy> · Como o Google usa dados de apps que utilizam seus serviços: <https://policies.google.com/technologies/partner-sites>
* **Mude suas escolhas quando quiser:** no jogo, **DEFINIÇÕES → PRIVACIDADE DOS ANÚNCIOS** (em inglês: SETTINGS → AD PRIVACY CHOICES; aparece quando se aplica a você); no iPhone, **Ajustes → Privacidade e Segurança → Rastreamento**.

<a id="pt-br-7"></a>
### 7. Notificações e compartilhamento

* As **notificações** (por exemplo "seu baú grátis está pronto") são **locais**: são agendadas no seu aparelho e só se você permitir. Nenhum servidor de notificações push é usado e nenhum token de notificação é enviado. Desative-as em **Ajustes → Notificações → DEADGRID** no iOS.
* **Compartilhamento:** quando você toca em um botão de compartilhar, abre-se o menu de compartilhamento do celular com um texto de convite (seu nome de usuário e um link da loja). Ele só vai para onde você escolher.

<a id="pt-br-8"></a>
### 8. Quem recebe dados

* **Supabase** — hospeda nosso servidor de jogo (em nosso nome).
* **Apple** e **Google** — lojas de apps e pagamentos.
* **Google AdMob** — publicidade, conforme a [seção 6](#pt-br-6).
* **Outros jogadores** — as informações públicas da [seção 4](#pt-br-4).
* **Autoridades** — somente se a lei exigir.

Esses provedores podem tratar dados em países diferentes do seu. Não vendemos seus dados pessoais.

<a id="pt-br-9"></a>
### 9. Por quanto tempo guardamos os dados

* Dados da conta e do progresso: enquanto sua conta existir, para você poder recuperar o progresso.
* Entradas nas filas de pareamento: removidas automaticamente após cerca de 2 minutos; convites Duo expiram após 60 segundos.
* Pontuações e histórico de partidas: enquanto a conta existir (eles formam os rankings).
* Mensagens para nós e relatórios de conexão: pelo tempo necessário para o suporte e a correção de bugs.
* Registros de compras: pelo tempo necessário para evitar entregas duplicadas e cumprir obrigações contábeis e legais.

<a id="pt-br-10"></a>
### 10. Seus direitos e exclusão dos dados

Dependendo de onde você mora (por exemplo, pela LGPD no Brasil, pelo GDPR no EEE e no Reino Unido ou pela lei da Califórnia), você pode ter direito a acessar, corrigir, excluir ou receber uma cópia dos seus dados, e a se opor a alguns usos ou limitá-los.

* **Excluir sua conta:** o jogo ainda não tem um botão para excluir a conta. Envie um e-mail para [support@deadgridgame.com](mailto:support@deadgridgame.com) com seu **nome de usuário** pedindo a exclusão. Podemos pedir que você confirme que a conta é sua. Excluiremos ou anonimizaremos os dados da conta em até 30 dias, exceto registros que a lei nos obrigue a manter (como registros de compras).
* **Outras solicitações** (acesso, correção, cópia): o mesmo endereço de e-mail.
* **Anúncios e rastreamento:** veja a [seção 6](#pt-br-6). **Notificações:** veja a [seção 7](#pt-br-7).
* **Dados locais:** excluir o app remove os dados salvos no seu aparelho.
* Tratamos seus dados com base em: execução do nosso acordo com você (fazer o jogo e as funções online funcionarem), nossos interesses legítimos (segurança, prevenção de fraudes, diagnóstico, estatísticas de uso), seu consentimento (anúncios personalizados, rastreamento, notificações) e obrigações legais. Você também pode fazer uma reclamação à autoridade de proteção de dados do seu país (no Brasil, a ANPD).

<a id="pt-br-11"></a>
### 11. Crianças

O DEADGRID **não é direcionado a crianças menores de 13 anos** (ou à idade mínima mais alta aplicável no seu país). Não coletamos intencionalmente dados pessoais de crianças menores de 13 anos. Se você acredita que uma criança nos forneceu dados pessoais, envie-nos um e-mail e nós os excluiremos. Anúncios personalizados só são exibidos quando o rastreamento é permitido e o consentimento é dado; os pais podem impedir isso em **Ajustes → Privacidade e Segurança → Rastreamento** no iOS (desativando "Permitir Solicitações de Rastreamento") e com o Tempo de Uso.

<a id="pt-br-12"></a>
### 12. Segurança

O app se comunica com nosso servidor por conexões criptografadas (HTTPS / WSS), e as senhas são guardadas apenas como hash. Nenhum sistema é totalmente seguro, então use uma senha que você não use em nenhum outro lugar.

<a id="pt-br-13"></a>
### 13. Alterações e contato

Podemos atualizar esta política quando o jogo mudar. A nova versão será publicada aqui com uma nova data.

**Desenvolvedor:** Afonso Quinaz
**E-mail:** [support@deadgridgame.com](mailto:support@deadgridgame.com)
**Site:** <https://github.com/afonsoquinaz/deadgrid-game>

---

<a id="de"></a>

## Deutsch

**Zuletzt aktualisiert: 27. September 2026**

**Inhalt:** [Überblick](#de-1) · [Auf deinem Gerät gespeichert](#de-2) · [Unser Spielserver](#de-3) · [Für andere sichtbar](#de-4) · [Käufe](#de-5) · [Werbung (Google AdMob)](#de-6) · [Mitteilungen und Teilen](#de-7) · [Empfänger](#de-8) · [Speicherdauer](#de-9) · [Deine Rechte und Löschung](#de-10) · [Kinder](#de-11) · [Sicherheit](#de-12) · [Änderungen und Kontakt](#de-13)

Diese Datenschutzerklärung erklärt, welche Daten das Spiel DEADGRID (ab Version 3, für iOS und Android) verwendet, wohin sie gehen und warum. DEADGRID wird von **Afonso Quinaz** entwickelt („wir“, „uns“). Kontakt: [support@deadgridgame.com](mailto:support@deadgridgame.com).

<a id="de-1"></a>
### 1. Überblick

* Zum Spielen wählst du einen **Benutzernamen**. Wir fragen **nicht** nach deinem echten Namen, deiner E-Mail-Adresse, Telefonnummer, deinen Kontakten, Fotos oder deinem genauen Standort.
* Dein Fortschritt wird auf deinem Gerät gespeichert **und mit unserem Spielserver synchronisiert** (gehostet bei Supabase), damit er gesichert ist und auf einem neuen Handy wiederhergestellt werden kann.
* Dein Benutzername und deine Spielergebnisse sind **für andere Spieler sichtbar** (Bestenlisten, Profile, Freunde, Online-Matches).
* Online-**Duo-Koop** und **Ranked**-Duelle übertragen Spieldaten in Echtzeit zwischen dir und dem anderen Spieler über unseren Server.
* Zahlungen laufen über **Apple** (App Store) oder **Google** (Google Play). Damit die Münzen ankommen, prüft unser Server den Kaufbeleg.
* Das Spiel ist kostenlos. Unter iOS zeigt es **nach jeweils 10 beendeten Spielen eine kurze Werbung**, ausgeliefert von **Google AdMob**. Über Tracking und Werbe-Einwilligung entscheidest du.
* Wir **verkaufen** deine personenbezogenen Daten **nicht**.

<a id="de-2"></a>
### 2. Auf deinem Gerät gespeicherte Daten

* **Spielstand:** dein Fortschritt (Münzen, Skins, Waffen, Pass, Level im Aufstieg, Missionen, Rekorde usw.), deine Einstellungen (Sprache, Ton, Grafik, Bildrate, Vibration), bereits gutgeschriebene Käufe und ein Zwischenstand, um eine Runde nach einem Absturz fortzusetzen.
* **Identitäts-Sicherung:** eine zufällige, vom Spiel erzeugte Geräte-ID, deine Profil-ID und dein Benutzername. Diese Geräte-ID ist **nicht** die Werbe-ID von Apple oder Google und keine Hardware-Kennung.
* **Werbe-Entscheidungen:** ob die Frage zum Werbe-Datenschutz schon gestellt wurde; deine Einwilligungsentscheidung selbst speichert Googles Einwilligungssoftware auf dem Gerät.
* **Umstieg von DEADGRID 2:** Beim ersten Start von DEADGRID 3 liest das Spiel den Spielstand der vorherigen Version **auf demselben Gerät**, um deinen Fortschritt zu übernehmen. Das geschieht lokal.

Diese Dateien liegen im privaten Speicher der App und werden beim Löschen der App entfernt. Das Löschen der App löscht **nicht** dein Konto auf unserem Server (siehe [Abschnitt 10](#de-10)).

<a id="de-3"></a>
### 3. Von unserem Spielserver verarbeitete Daten

Unser Backend läuft bei **Supabase**, einem Hosting-Anbieter, der Daten in unserem Auftrag verarbeitet. Die App sendet:

| Was | Details | Warum |
|---|---|---|
| **Konto** | zufällige Geräte-ID, Profil-ID, Benutzername, Erstellungsdatum. **Optionales Passwort** (wenn du dein Konto schützt): Der Server speichert nur einen Hash davon und einen Hash des einmaligen Wiederherstellungscodes; fehlgeschlagene Anmeldeversuche werden protokolliert, um das Erraten von Passwörtern zu blockieren. | dein Konto anlegen, dein Gerät wiedererkennen, Anmeldung auf einem anderen Gerät ermöglichen |
| **Fortschritt** | Münzen, Game Pass, Skins, Emotes, Waffen-Finishes, Inseln, Missionen, Specs, Boni, Saison, Level im Aufstieg, Tagesserie, Revives, Rangpunkte, Siege und Niederlagen, Wappen, Empfehlungen (wer wen eingeladen hat) | Sicherung, Wiederherstellung und Synchronisierung deines Fortschritts |
| **Punkte und Matches** | Punktzahl, Welle, Kills, Überlebenszeit, Modus, Karte, Ergebnis, Benutzername von Partner oder Gegner, Datum | Bestenlisten, Match-Verlauf, Turniere, Wappen |
| **Aktivität und Diagnose** | Zeitpunkt der letzten Aktivität, ob du im Menü oder im Spiel bist, App-Version; Sitzungsbeginn und letzte Aktivität; Beginn und Ende jedes Spiels (Modus, Dauer, wie es endete); eine Latenzmessung für das Ranked-Matchmaking; wenn ein Online-Match scheitert, ein automatischer Verbindungsbericht (Verbindungsstatistiken mit deinem Benutzernamen und deiner Profil-ID) | Online-Status für Freunde, Betrieb des Dienstes, Fehlerbehebung, Überblick, welche Versionen noch genutzt werden |
| **Soziales** | Freundschaftsanfragen und Freundschaften, Duo-Einladungen, Einträge in Matchmaking- und Ranked-Warteschlangen, Turnier-Anmeldungen und -Preise | Freunde, Einladungen, Matchmaking, Turniere |
| **Live-Matchdaten** | bei Duo und Ranked: Positionen, Aktionen und Spielereignisse, Emotes und vorgegebene Schnellchat-Sätze, an den anderen Spieler weitergeleitet | gemeinsames Spielen in Echtzeit. Es gibt keinen Freitext-Chat und keinen Sprachchat. |
| **Nachrichten an uns** | der Text, den du unter EINSTELLUNGEN → DEM TEAM SCHREIBEN eingibst, mit Benutzername, Profil-ID und App-Version | dein Feedback lesen und beantworten |
| **Käufe** | Produkt, Transaktions-ID, Store (App Store / Google Play), der App-Store-Beleg bzw. das Google-Play-Kauftoken, gutgeschriebene Münzen, Datum | prüfen, dass der Kauf echt ist, und die Münzen genau einmal gutschreiben |

Wie bei jedem Internetdienst erhält unser Hosting-Anbieter deine **IP-Adresse**, wenn sich die App verbindet; sie kann in den technischen Protokollen des Anbieters erscheinen. Wir speichern sie nicht in unseren Spieldaten und nutzen sie nicht, um dich zu orten.

<a id="de-4"></a>
### 4. Was andere Spieler sehen können

Deinen **Benutzernamen**, deinen Charakter-Skin, deine Insel und dein Waffenregal, Punkte, Ränge, Pass-Stufe, Serie, Wappen und Profilstatistiken, deinen Online-/Im-Spiel-Status (für Freunde und in Spielervorschlägen) sowie deinen Namen im Match-Verlauf anderer Spieler. Bitte verwende nicht deinen echten Namen oder andere persönliche Angaben als Benutzernamen.

<a id="de-5"></a>
### 5. In-App-Käufe

Zahlungen werden von **Apple** oder **Google** abgewickelt; deine Karten- oder Zahlungsdaten sehen wir nie. Damit die Münzen ankommen, sendet die App die Transaktions-ID und den Beleg (iOS: App-Store-Beleg; Android: Kauftoken) an eine Funktion auf unserem Server, die ihn bei Apple bzw. Google prüft und die Gutschrift festhält. Ist ein bezahlter Kauf nicht angekommen, prüft **KÄUFE WIEDERHERSTELLEN** auf dem Bildschirm MÜNZEN HOLEN erneut. Für die Zahlung selbst gelten die Datenschutzerklärungen von Apple und Google.

<a id="de-6"></a>
### 6. Werbung (Google AdMob)

* DEADGRID ist kostenlos. In der **iOS**-Version erscheint **nach jeweils 10 beendeten Spielen eine kurze Vollbild-Werbung**, bei der nächsten Pause (zum Beispiel beim Zurückkehren ins Menü). Während eines Matches gibt es keine Werbung.
* Die Werbung liefert **Google AdMob** aus (Google LLC; im EWR und im Vereinigten Königreich Google Ireland Limited).
* Vor der ersten Werbung kann iOS fragen, ob DEADGRID dich **tracken** darf (App-Tracking-Transparenz von Apple), und im EWR, im Vereinigten Königreich und überall sonst, wo es vorgeschrieben ist, fragt Googles **Einwilligungsformular** nach deinen Werbe-Einstellungen.
* **Daten, die AdMob erheben kann:** Gerätekennungen — die Werbe-ID (IDFA) **nur, wenn du Tracking erlaubst**; deine IP-Adresse und der daraus abgeleitete ungefähre Standort; Geräte- und App-Informationen (etwa Modell, Betriebssystem, Sprache); Interaktionen mit Werbung (angezeigte Anzeigen und Tipps); Diagnose- und Leistungsdaten.
* **Wozu:** Anzeigen ausliefern und messen, begrenzen, wie oft du dieselbe Anzeige siehst, Betrug verhindern und — nur mit deiner Einwilligung / Erlaubnis — Werbung personalisieren. Ohne sie zeigt Google nicht personalisierte oder eingeschränkte Anzeigen, die für diese grundlegenden Zwecke dennoch einige Daten nutzen.
* Wir senden Google **nicht** deinen Benutzernamen, dein Konto oder deinen Spielfortschritt, und wir erhalten deine Werbe-ID nicht.
* Datenschutzerklärung von Google: <https://policies.google.com/privacy> · Wie Google Daten von Apps nutzt, die Google-Dienste verwenden: <https://policies.google.com/technologies/partner-sites>
* **Ändere deine Entscheidung jederzeit:** im Spiel unter **EINSTELLUNGEN → WERBE-DATENSCHUTZ** (englisch: SETTINGS → AD PRIVACY CHOICES; erscheint, wenn es für dich gilt); auf dem iPhone unter **Einstellungen → Datenschutz & Sicherheit → Tracking**.

<a id="de-7"></a>
### 7. Mitteilungen und Teilen

* **Mitteilungen** (zum Beispiel „Deine Gratis-Truhe ist bereit“) sind **lokal**: Sie werden auf deinem Gerät geplant, und nur, wenn du sie erlaubst. Es gibt keinen Push-Server, und kein Mitteilungs-Token wird irgendwohin gesendet. Abschalten unter iOS **Einstellungen → Mitteilungen → DEADGRID**.
* **Teilen:** Wenn du auf eine Teilen-Schaltfläche tippst, öffnet sich das Teilen-Menü deines Handys mit einem Einladungstext (dein Benutzername und ein Store-Link). Er geht nur dorthin, wohin du ihn schickst.

<a id="de-8"></a>
### 8. Wer Daten erhält

* **Supabase** — hostet unseren Spielserver (in unserem Auftrag).
* **Apple** und **Google** — App Stores und Zahlungen.
* **Google AdMob** — Werbung, wie in [Abschnitt 6](#de-6) beschrieben.
* **Andere Spieler** — die öffentlichen Angaben aus [Abschnitt 4](#de-4).
* **Behörden** — nur wenn das Gesetz es verlangt.

Diese Anbieter können Daten auch in anderen Ländern als deinem verarbeiten. Wir verkaufen deine personenbezogenen Daten nicht.

<a id="de-9"></a>
### 9. Wie lange wir Daten speichern

* Konto- und Fortschrittsdaten: solange dein Konto besteht, damit du deinen Fortschritt zurückbekommst.
* Einträge in Warteschlangen: werden nach etwa 2 Minuten automatisch entfernt; Duo-Einladungen verfallen nach 60 Sekunden.
* Punkte und Match-Verlauf: solange das Konto besteht (sie bilden die Bestenlisten).
* Nachrichten an uns und Verbindungsberichte: so lange, wie es für Support und Fehlerbehebung nötig ist.
* Kaufaufzeichnungen: so lange, wie es nötig ist, um doppelte Gutschriften zu verhindern und Buchhaltungs- und gesetzliche Pflichten zu erfüllen.

<a id="de-10"></a>
### 10. Deine Rechte und Löschung deiner Daten

Je nachdem, wo du lebst (zum Beispiel nach der DSGVO im EWR und im Vereinigten Königreich oder nach kalifornischem Recht), hast du möglicherweise das Recht auf Auskunft, Berichtigung, Löschung und eine Kopie deiner Daten sowie das Recht, bestimmten Verwendungen zu widersprechen oder sie einzuschränken.

* **Konto löschen:** Das Spiel hat noch keine Schaltfläche zum Löschen des Kontos. Schreib an [support@deadgridgame.com](mailto:support@deadgridgame.com) mit deinem **Benutzernamen** und bitte um Löschung. Wir können dich bitten zu bestätigen, dass das Konto dir gehört. Wir löschen oder anonymisieren deine Kontodaten innerhalb von 30 Tagen, außer Aufzeichnungen, die wir gesetzlich aufbewahren müssen (etwa Kaufaufzeichnungen).
* **Andere Anfragen** (Auskunft, Berichtigung, Kopie): dieselbe E-Mail-Adresse.
* **Werbung und Tracking:** siehe [Abschnitt 6](#de-6). **Mitteilungen:** siehe [Abschnitt 7](#de-7).
* **Lokale Daten:** Das Löschen der App entfernt die auf deinem Gerät gespeicherten Daten.
* Im EWR und im Vereinigten Königreich stützen wir uns auf: die Erfüllung unserer Vereinbarung mit dir (Betrieb des Spiels und seiner Online-Funktionen), unsere berechtigten Interessen (Sicherheit, Betrugsverhinderung, Diagnose, Nutzungsstatistiken), deine Einwilligung (personalisierte Werbung, Tracking, Mitteilungen) und gesetzliche Pflichten. Du kannst dich außerdem bei deiner Datenschutz-Aufsichtsbehörde beschweren.

<a id="de-11"></a>
### 11. Kinder

DEADGRID **richtet sich nicht an Kinder unter 13 Jahren** (oder das in deinem Land geltende höhere Mindestalter). Wir erheben wissentlich keine personenbezogenen Daten von Kindern unter 13 Jahren. Wenn du glaubst, dass ein Kind uns personenbezogene Daten gegeben hat, schreib uns, und wir löschen sie. Personalisierte Werbung erscheint nur, wenn Tracking erlaubt und eingewilligt wurde; Eltern können das unter iOS **Einstellungen → Datenschutz & Sicherheit → Tracking** (Schalter „Apps erlauben, Tracking anzufordern“ aus) und mit der Bildschirmzeit verhindern.

<a id="de-12"></a>
### 12. Sicherheit

Die App kommuniziert über verschlüsselte Verbindungen (HTTPS / WSS) mit unserem Server, und Passwörter werden nur als Hash gespeichert. Kein System ist vollkommen sicher, also verwende bitte ein Passwort, das du sonst nirgends benutzt.

<a id="de-13"></a>
### 13. Änderungen und Kontakt

Wir können diese Datenschutzerklärung aktualisieren, wenn sich das Spiel ändert. Die neue Fassung wird hier mit neuem Datum veröffentlicht.

**Entwickler:** Afonso Quinaz
**E-Mail:** [support@deadgridgame.com](mailto:support@deadgridgame.com)
**Website:** <https://github.com/afonsoquinaz/deadgrid-game>

---

<a id="es"></a>

## Español

**Última actualización: 27 de septiembre de 2026**

**Índice:** [Resumen](#es-1) · [Guardado en tu dispositivo](#es-2) · [Nuestro servidor](#es-3) · [Visible para otros jugadores](#es-4) · [Compras](#es-5) · [Anuncios (Google AdMob)](#es-6) · [Notificaciones y compartir](#es-7) · [Quién recibe datos](#es-8) · [Conservación](#es-9) · [Tus derechos y borrar tus datos](#es-10) · [Menores](#es-11) · [Seguridad](#es-12) · [Cambios y contacto](#es-13)

Esta política explica qué datos usa el juego DEADGRID (versión 3 y posteriores, para iOS y Android), adónde van y por qué. DEADGRID lo desarrolla **Afonso Quinaz** («nosotros»). Contacto: [support@deadgridgame.com](mailto:support@deadgridgame.com).

<a id="es-1"></a>
### 1. Resumen

* Para jugar eliges un **nombre de usuario**. **No** te pedimos tu nombre real, correo electrónico, teléfono, contactos, fotos ni ubicación precisa.
* Tu progreso se guarda en tu dispositivo **y se sincroniza con nuestro servidor de juego** (alojado en Supabase), para que tenga copia de seguridad y puedas recuperarlo en un móvil nuevo.
* Tu nombre de usuario y tus resultados son **visibles para otros jugadores** (clasificaciones, perfiles, amigos, partidas online).
* El **Dúo cooperativo** y los duelos **Ranked** online envían datos del juego en tiempo real entre tú y el otro jugador a través de nuestro servidor.
* Los pagos los gestiona **Apple** (App Store) o **Google** (Google Play). Para entregar las monedas, nuestro servidor comprueba el recibo de la compra.
* El juego es gratis. En iOS muestra **un anuncio corto cada 10 partidas terminadas**, servido por **Google AdMob**. Tú decides sobre el rastreo y el consentimiento de anuncios.
* **No vendemos** tus datos personales.

<a id="es-2"></a>
### 2. Datos guardados en tu dispositivo

* **Archivo de partida:** tu progreso (monedas, skins, armas, pase, nivel de la Escalada, misiones, récords, etc.), tus ajustes (idioma, sonido, gráficos, fotogramas por segundo, vibración), las compras ya entregadas y una copia para retomar una partida tras un cierre inesperado.
* **Copia de identidad:** un ID de dispositivo aleatorio creado por el juego, tu ID de perfil y tu nombre de usuario. Ese ID **no** es el identificador publicitario de Apple o Google ni un identificador de hardware.
* **Elecciones de anuncios:** si ya se hizo la pregunta sobre privacidad de anuncios; tu elección de consentimiento la guarda en el dispositivo el software de consentimiento de Google.
* **Si vienes de DEADGRID 2:** al abrir DEADGRID 3 por primera vez, el juego lee la partida guardada de la versión anterior **en el mismo dispositivo** para traer tu progreso. Esto ocurre localmente.

Estos archivos están en el almacenamiento privado de la app y se eliminan al borrar la app. Borrar la app **no** borra tu cuenta en nuestro servidor (ver [sección 10](#es-10)).

<a id="es-3"></a>
### 3. Datos que trata nuestro servidor de juego

Nuestro servidor funciona en **Supabase**, un proveedor de alojamiento que trata los datos por cuenta nuestra. La app le envía:

| Qué | Detalles | Para qué |
|---|---|---|
| **Cuenta** | ID de dispositivo aleatorio, ID de perfil, nombre de usuario, fecha de creación. **Contraseña opcional** (si proteges tu cuenta): el servidor guarda solo un hash de ella y un hash del código de recuperación de un solo uso; los intentos fallidos de inicio de sesión se registran para bloquear a quien intente adivinar contraseñas. | crear tu cuenta, reconocer tu dispositivo, permitirte iniciar sesión en otro dispositivo |
| **Progreso** | monedas, pase de juego, skins, emotes, acabados de armas, islas, misiones, specs, bonus, temporada, nivel de la Escalada, racha diaria, revives, puntos de rango, victorias y derrotas, emblemas, referidos (quién invitó a quién) | copia de seguridad, recuperación y sincronización de tu progreso |
| **Puntuaciones y partidas** | puntuación, oleada, bajas, tiempo sobrevivido, modo, mapa, resultado, nombre del compañero o rival, fecha | clasificaciones, historial, torneos, emblemas |
| **Actividad y diagnóstico** | hora de última conexión, si estás en un menú o en una partida, versión de la app; inicio de sesión y última actividad; inicio y fin de cada partida (modo, duración, cómo terminó); una medición de latencia para el emparejamiento Ranked; si una partida online falla, un informe automático de conexión (estadísticas de la conexión con tu nombre de usuario e ID de perfil) | estado online para amigos, mantener el servicio funcionando, corregir errores, saber qué versiones se siguen usando |
| **Social** | solicitudes de amistad y amistades, invitaciones de Dúo, entradas en las colas de emparejamiento y Ranked, inscripciones y premios de torneos | amigos, invitaciones, emparejamiento, torneos |
| **Datos de la partida en directo** | en Dúo y Ranked: posiciones, acciones y eventos del juego, emotes y frases rápidas predefinidas, reenviados al otro jugador | jugar juntos en tiempo real. No hay chat de texto libre ni chat de voz. |
| **Mensajes para nosotros** | el texto que escribes en AJUSTES → ESCRIBE AL EQUIPO, con tu nombre de usuario, ID de perfil y versión de la app | leer y responder a tus comentarios |
| **Compras** | producto, ID de transacción, tienda (App Store / Google Play), el recibo de App Store o el token de compra de Google Play, monedas entregadas, fecha | comprobar que la compra es real y entregar las monedas una sola vez |

Como cualquier servicio de internet, nuestro proveedor de alojamiento recibe tu **dirección IP** cuando la app se conecta; puede aparecer en sus registros técnicos. No la guardamos en los datos del juego ni la usamos para localizarte.

<a id="es-4"></a>
### 4. Lo que pueden ver otros jugadores

Tu **nombre de usuario**, la skin de tu personaje, tu isla y tu armero, puntuaciones, rangos, nivel del pase, racha, emblemas y estadísticas del perfil, tu estado online / en partida (para amigos y en las sugerencias de jugadores) y tu nombre en el historial de partidas de otros jugadores. Por favor, no uses tu nombre real ni otros datos personales como nombre de usuario.

<a id="es-5"></a>
### 5. Compras dentro de la app

Los pagos los procesa **Apple** o **Google**; nunca vemos tu tarjeta ni tus datos de pago. Para entregar las monedas, la app envía el ID de transacción y el recibo (iOS: recibo de App Store; Android: token de compra) a una función de nuestro servidor, que lo comprueba con Apple o Google y registra la entrega. Si una compra pagada no ha llegado, **RESTAURAR COMPRAS** en la pantalla CONSEGUIR MONEDAS lo vuelve a comprobar. Al pago en sí se aplican las políticas de privacidad de Apple y Google.

<a id="es-6"></a>
### 6. Publicidad (Google AdMob)

* DEADGRID es gratis. En la versión de **iOS** muestra **un anuncio corto a pantalla completa cada 10 partidas terminadas**, en la siguiente pausa (por ejemplo, al volver al menú). No hay anuncios durante una partida.
* Los anuncios los sirve **Google AdMob** (Google LLC; en el EEE y el Reino Unido, Google Ireland Limited).
* Antes del primer anuncio, iOS puede preguntarte si DEADGRID puede **rastrearte** (Transparencia de Rastreo de Apps de Apple) y, en el EEE, el Reino Unido y otros lugares donde sea obligatorio, el **formulario de consentimiento** de Google te pide tus preferencias de anuncios.
* **Datos que AdMob puede recopilar:** identificadores del dispositivo — incluido el identificador publicitario (IDFA) **solo si permites el rastreo**; tu dirección IP y la ubicación aproximada que se deduce de ella; información del dispositivo y de la app (como modelo, sistema operativo, idioma); interacciones con anuncios (anuncios mostrados y toques); datos de diagnóstico y rendimiento.
* **Para qué:** mostrar anuncios, medirlos, limitar cuántas veces ves el mismo anuncio, prevenir el fraude y — solo con tu consentimiento / permiso — personalizar los anuncios. Sin él, Google muestra anuncios no personalizados o limitados, que aun así usan algunos datos para estos fines básicos.
* **No** enviamos a Google tu nombre de usuario, tu cuenta ni tu progreso, y no recibimos tu identificador publicitario.
* Política de privacidad de Google: <https://policies.google.com/privacy> · Cómo usa Google los datos de las apps que utilizan sus servicios: <https://policies.google.com/technologies/partner-sites>
* **Cambia tus preferencias cuando quieras:** en el juego, **AJUSTES → PRIVACIDAD DE ANUNCIOS** (en inglés: SETTINGS → AD PRIVACY CHOICES; aparece cuando te corresponde); en el iPhone, **Ajustes → Privacidad y seguridad → Rastreo**.

<a id="es-7"></a>
### 7. Notificaciones y compartir

* Las **notificaciones** (por ejemplo «tu cofre gratis está listo») son **locales**: se programan en tu dispositivo y solo si las permites. No se usa ningún servidor de notificaciones push ni se envía ningún token de notificación. Desactívalas en iOS en **Ajustes → Notificaciones → DEADGRID**.
* **Compartir:** cuando tocas un botón de compartir, se abre el menú de compartir del móvil con un texto de invitación (tu nombre de usuario y un enlace a la tienda). Solo va adonde tú decidas enviarlo.

<a id="es-8"></a>
### 8. Quién recibe datos

* **Supabase** — aloja nuestro servidor de juego (por cuenta nuestra).
* **Apple** y **Google** — tiendas de apps y pagos.
* **Google AdMob** — publicidad, como se describe en la [sección 6](#es-6).
* **Otros jugadores** — la información pública de la [sección 4](#es-4).
* **Autoridades** — solo si la ley lo exige.

Estos proveedores pueden tratar datos en países distintos del tuyo. No vendemos tus datos personales.

<a id="es-9"></a>
### 9. Cuánto tiempo conservamos los datos

* Datos de la cuenta y del progreso: mientras exista tu cuenta, para que puedas recuperar tu progreso.
* Entradas en las colas de emparejamiento: se eliminan automáticamente tras unos 2 minutos; las invitaciones de Dúo caducan a los 60 segundos.
* Puntuaciones e historial de partidas: mientras exista la cuenta (forman las clasificaciones).
* Mensajes para nosotros e informes de conexión: el tiempo necesario para el soporte y la corrección de errores.
* Registros de compras: el tiempo necesario para evitar entregas duplicadas y cumplir obligaciones contables y legales.

<a id="es-10"></a>
### 10. Tus derechos y borrar tus datos

Según dónde vivas (por ejemplo, en virtud del RGPD en el EEE y el Reino Unido, o de la ley de California), puedes tener derecho a acceder, rectificar, suprimir o recibir una copia de tus datos, y a oponerte a algunos usos o limitarlos.

* **Borrar tu cuenta:** el juego todavía no tiene un botón para borrar la cuenta. Escribe a [support@deadgridgame.com](mailto:support@deadgridgame.com) con tu **nombre de usuario** y pide que la borremos. Podemos pedirte que confirmes que la cuenta es tuya. Borraremos o anonimizaremos los datos de tu cuenta en un plazo de 30 días, salvo los registros que la ley nos obligue a conservar (como los registros de compras).
* **Otras solicitudes** (acceso, rectificación, copia): la misma dirección de correo.
* **Anuncios y rastreo:** ver [sección 6](#es-6). **Notificaciones:** ver [sección 7](#es-7).
* **Datos locales:** borrar la app elimina los datos guardados en tu dispositivo.
* Si estás en el EEE o el Reino Unido, nos basamos en: la ejecución de nuestro acuerdo contigo (hacer funcionar el juego y sus funciones online), nuestros intereses legítimos (seguridad, prevención del fraude, diagnóstico, estadísticas de uso), tu consentimiento (anuncios personalizados, rastreo, notificaciones) y obligaciones legales. También puedes presentar una reclamación ante tu autoridad de protección de datos (en España, la AEPD).

<a id="es-11"></a>
### 11. Menores

DEADGRID **no está dirigido a menores de 13 años** (o a la edad mínima más alta que se aplique en tu país). No recopilamos a sabiendas datos personales de menores de 13 años. Si crees que un menor nos ha dado datos personales, escríbenos y los borraremos. Los anuncios personalizados solo se muestran cuando se permite el rastreo y se da el consentimiento; los padres pueden impedirlo en iOS en **Ajustes → Privacidad y seguridad → Rastreo** (desactivando «Permitir que las apps soliciten rastrear») y con Tiempo de uso.

<a id="es-12"></a>
### 12. Seguridad

La app se comunica con nuestro servidor mediante conexiones cifradas (HTTPS / WSS), y las contraseñas se guardan solo como hash. Ningún sistema es totalmente seguro, así que usa una contraseña que no uses en ningún otro sitio.

<a id="es-13"></a>
### 13. Cambios y contacto

Podemos actualizar esta política cuando cambie el juego. La nueva versión se publicará aquí con una nueva fecha.

**Desarrollador:** Afonso Quinaz
**Correo:** [support@deadgridgame.com](mailto:support@deadgridgame.com)
**Web:** <https://github.com/afonsoquinaz/deadgrid-game>

---

<a id="fr"></a>

## Français

**Dernière mise à jour : 27 septembre 2026**

**Sommaire :** [Résumé](#fr-1) · [Stocké sur ton appareil](#fr-2) · [Notre serveur](#fr-3) · [Visible par les autres joueurs](#fr-4) · [Achats](#fr-5) · [Publicités (Google AdMob)](#fr-6) · [Notifications et partage](#fr-7) · [Destinataires](#fr-8) · [Conservation](#fr-9) · [Tes droits et suppression](#fr-10) · [Enfants](#fr-11) · [Sécurité](#fr-12) · [Modifications et contact](#fr-13)

Cette politique explique quelles données le jeu DEADGRID (version 3 et suivantes, pour iOS et Android) utilise, où elles vont et pourquoi. DEADGRID est développé par **Afonso Quinaz** (« nous »). Contact : [support@deadgridgame.com](mailto:support@deadgridgame.com).

<a id="fr-1"></a>
### 1. Résumé

* Pour jouer, tu choisis un **nom d’utilisateur**. Nous ne te demandons **pas** ton vrai nom, ton e-mail, ton numéro de téléphone, tes contacts, tes photos ni ta position précise.
* Ta progression est enregistrée sur ton appareil **et synchronisée avec notre serveur de jeu** (hébergé chez Supabase), pour être sauvegardée et récupérable sur un nouveau téléphone.
* Ton nom d’utilisateur et tes résultats sont **visibles par les autres joueurs** (classements, profils, amis, parties en ligne).
* Le **Duo coopératif** et les duels **Ranked** en ligne échangent des données de jeu en temps réel entre toi et l’autre joueur via notre serveur.
* Les paiements sont gérés par **Apple** (App Store) ou **Google** (Google Play). Pour livrer les pièces, notre serveur vérifie le reçu de l’achat.
* Le jeu est gratuit. Sur iOS, il affiche **une courte publicité toutes les 10 parties terminées**, diffusée par **Google AdMob**. C’est toi qui décides du suivi et du consentement publicitaire.
* Nous ne **vendons pas** tes données personnelles.

<a id="fr-2"></a>
### 2. Données stockées sur ton appareil

* **Sauvegarde :** ta progression (pièces, skins, armes, passe, niveau de l’Ascension, missions, records, etc.), tes réglages (langue, son, graphismes, images par seconde, vibrations), les achats déjà livrés et un instantané pour reprendre une partie après un plantage.
* **Copie de l’identité :** un identifiant d’appareil aléatoire créé par le jeu, ton identifiant de profil et ton nom d’utilisateur. Cet identifiant n’est **pas** l’identifiant publicitaire d’Apple ou de Google ni un identifiant matériel.
* **Choix publicitaires :** si la question sur la confidentialité des publicités a déjà été posée ; ton choix de consentement lui-même est enregistré sur l’appareil par le logiciel de consentement de Google.
* **Si tu viens de DEADGRID 2 :** au premier lancement de DEADGRID 3, le jeu lit la sauvegarde de la version précédente **sur le même appareil** pour reprendre ta progression. Cela se fait localement.

Ces fichiers se trouvent dans le stockage privé de l’app et sont supprimés quand tu supprimes l’app. Supprimer l’app ne supprime **pas** ton compte sur notre serveur (voir la [section 10](#fr-10)).

<a id="fr-3"></a>
### 3. Données traitées par notre serveur de jeu

Notre serveur fonctionne chez **Supabase**, un hébergeur qui traite les données pour notre compte. L’app lui envoie :

| Quoi | Détails | Pourquoi |
|---|---|---|
| **Compte** | identifiant d’appareil aléatoire, identifiant de profil, nom d’utilisateur, date de création. **Mot de passe facultatif** (si tu protèges ton compte) : le serveur n’en conserve qu’un hachage, ainsi qu’un hachage du code de récupération à usage unique ; les tentatives de connexion échouées sont enregistrées pour bloquer ceux qui essaient de deviner les mots de passe. | créer ton compte, reconnaître ton appareil, te permettre de te connecter sur un autre appareil |
| **Progression** | pièces, passe de jeu, skins, emotes, finitions d’armes, îles, missions, specs, bonus, saison, niveau de l’Ascension, série quotidienne, revives, points de rang, victoires et défaites, blasons, parrainages (qui a invité qui) | sauvegarde, restauration et synchronisation de ta progression |
| **Scores et parties** | score, vague, éliminations, temps de survie, mode, carte, résultat, nom du partenaire ou de l’adversaire, date | classements, historique, tournois, blasons |
| **Activité et diagnostic** | heure de dernière connexion, si tu es dans un menu ou en partie, version de l’app ; début de session et dernière activité ; début et fin de chaque partie (mode, durée, façon dont elle s’est terminée) ; une mesure de latence pour le matchmaking Ranked ; si une partie en ligne échoue, un rapport de connexion automatique (statistiques de connexion avec ton nom d’utilisateur et ton identifiant de profil) | statut en ligne pour les amis, faire fonctionner le service, corriger les bugs, savoir quelles versions sont encore utilisées |
| **Social** | demandes d’ami et amitiés, invitations Duo, entrées dans les files de matchmaking et Ranked, inscriptions et récompenses de tournois | amis, invitations, matchmaking, tournois |
| **Données de partie en direct** | en Duo et en Ranked : positions, actions et événements de jeu, emotes et phrases rapides prédéfinies, relayés à l’autre joueur | jouer ensemble en temps réel. Il n’y a ni chat en texte libre ni chat vocal. |
| **Messages qui nous sont adressés** | le texte que tu écris dans RÉGLAGES → ÉCRIRE À L’ÉQUIPE, avec ton nom d’utilisateur, ton identifiant de profil et la version de l’app | lire et répondre à tes retours |
| **Achats** | produit, identifiant de transaction, boutique (App Store / Google Play), le reçu App Store ou le jeton d’achat Google Play, pièces créditées, date | vérifier que l’achat est authentique et livrer les pièces une seule fois |

Comme tout service en ligne, notre hébergeur reçoit ton **adresse IP** lorsque l’app se connecte ; elle peut figurer dans ses journaux techniques. Nous ne la conservons pas dans nos données de jeu et ne l’utilisons pas pour te localiser.

<a id="fr-4"></a>
### 4. Ce que les autres joueurs peuvent voir

Ton **nom d’utilisateur**, le skin de ton personnage, ton île et ton râtelier d’armes, tes scores, rangs, palier de passe, série, blasons et statistiques de profil, ton statut en ligne / en partie (pour les amis et dans les suggestions de joueurs) et ton nom dans l’historique des parties des autres joueurs. Merci de ne pas utiliser ton vrai nom ni d’autres informations personnelles comme nom d’utilisateur.

<a id="fr-5"></a>
### 5. Achats intégrés

Les paiements sont traités par **Apple** ou **Google** ; nous ne voyons jamais ta carte ni tes données de paiement. Pour livrer les pièces, l’app envoie l’identifiant de transaction et le reçu (iOS : reçu App Store ; Android : jeton d’achat) à une fonction de notre serveur, qui le vérifie auprès d’Apple ou de Google et enregistre la livraison. Si un achat payé n’est pas arrivé, **RESTAURER LES ACHATS** sur l’écran OBTENIR DES PIÈCES vérifie à nouveau. Le paiement lui-même relève des politiques de confidentialité d’Apple et de Google.

<a id="fr-6"></a>
### 6. Publicité (Google AdMob)

* DEADGRID est gratuit. Dans la version **iOS**, il affiche **une courte publicité plein écran toutes les 10 parties terminées**, à la pause suivante (par exemple au retour au menu). Il n’y a pas de publicité pendant une partie.
* Les publicités sont diffusées par **Google AdMob** (Google LLC ; dans l’EEE et au Royaume-Uni, Google Ireland Limited).
* Avant la première publicité, iOS peut te demander si DEADGRID peut te **suivre** (transparence du suivi des apps d’Apple) et, dans l’EEE, au Royaume-Uni et partout où c’est requis, le **formulaire de consentement** de Google te demande tes choix publicitaires.
* **Données qu’AdMob peut collecter :** identifiants de l’appareil — dont l’identifiant publicitaire (IDFA) **uniquement si tu autorises le suivi** ; ton adresse IP et la localisation approximative qui en découle ; des informations sur l’appareil et l’app (modèle, système d’exploitation, langue, etc.) ; les interactions avec les publicités (publicités affichées et appuis) ; des données de diagnostic et de performance.
* **Pourquoi :** afficher et mesurer les publicités, limiter le nombre de fois où tu vois la même, prévenir la fraude et — uniquement avec ton consentement / ton autorisation — personnaliser les publicités. Sans cela, Google affiche des publicités non personnalisées ou limitées, qui utilisent tout de même certaines données pour ces besoins de base.
* Nous n’envoyons **pas** à Google ton nom d’utilisateur, ton compte ni ta progression, et nous ne recevons pas ton identifiant publicitaire.
* Politique de confidentialité de Google : <https://policies.google.com/privacy> · Comment Google utilise les données des apps qui utilisent ses services : <https://policies.google.com/technologies/partner-sites>
* **Modifie tes choix à tout moment :** dans le jeu, **RÉGLAGES → CONFIDENTIALITÉ DES PUBS** (en anglais : SETTINGS → AD PRIVACY CHOICES ; affiché lorsque cela te concerne) ; sur iPhone, **Réglages → Confidentialité et sécurité → Suivi**.

<a id="fr-7"></a>
### 7. Notifications et partage

* Les **notifications** (par exemple « ton coffre gratuit est prêt ») sont **locales** : elles sont programmées sur ton appareil, et seulement si tu les autorises. Aucun serveur de notifications push n’est utilisé et aucun jeton de notification n’est envoyé. Désactive-les dans iOS via **Réglages → Notifications → DEADGRID**.
* **Partage :** quand tu touches un bouton de partage, la feuille de partage de ton téléphone s’ouvre avec un texte d’invitation (ton nom d’utilisateur et un lien vers la boutique). Il ne va que là où tu choisis de l’envoyer.

<a id="fr-8"></a>
### 8. Qui reçoit des données

* **Supabase** — héberge notre serveur de jeu (pour notre compte).
* **Apple** et **Google** — boutiques d’applications et paiements.
* **Google AdMob** — publicité, comme décrit à la [section 6](#fr-6).
* **Les autres joueurs** — les informations publiques de la [section 4](#fr-4).
* **Les autorités** — uniquement si la loi l’exige.

Ces prestataires peuvent traiter des données dans d’autres pays que le tien. Nous ne vendons pas tes données personnelles.

<a id="fr-9"></a>
### 9. Durée de conservation

* Données de compte et de progression : tant que ton compte existe, pour que tu puisses récupérer ta progression.
* Entrées dans les files de matchmaking : supprimées automatiquement au bout d’environ 2 minutes ; les invitations Duo expirent après 60 secondes.
* Scores et historique des parties : tant que le compte existe (ils constituent les classements).
* Messages qui nous sont adressés et rapports de connexion : le temps nécessaire au support et à la correction des bugs.
* Enregistrements d’achats : le temps nécessaire pour éviter les doubles livraisons et respecter nos obligations comptables et légales.

<a id="fr-10"></a>
### 10. Tes droits et suppression de tes données

Selon l’endroit où tu vis (par exemple au titre du RGPD dans l’EEE et au Royaume-Uni, ou du droit californien), tu peux avoir le droit d’accéder à tes données, de les rectifier, de les supprimer ou d’en recevoir une copie, et de t’opposer à certains usages ou de les limiter.

* **Supprimer ton compte :** le jeu n’a pas encore de bouton de suppression du compte. Écris à [support@deadgridgame.com](mailto:support@deadgridgame.com) en indiquant ton **nom d’utilisateur** et demande la suppression. Nous pourrons te demander de confirmer que le compte t’appartient. Nous supprimerons ou anonymiserons les données de ton compte sous 30 jours, sauf les enregistrements que la loi nous oblige à conserver (comme les enregistrements d’achats).
* **Autres demandes** (accès, rectification, copie) : la même adresse e-mail.
* **Publicité et suivi :** voir la [section 6](#fr-6). **Notifications :** voir la [section 7](#fr-7).
* **Données locales :** supprimer l’app efface les données stockées sur ton appareil.
* Si tu te trouves dans l’EEE ou au Royaume-Uni, nous nous appuyons sur : l’exécution de notre accord avec toi (faire fonctionner le jeu et ses fonctions en ligne), nos intérêts légitimes (sécurité, prévention de la fraude, diagnostic, statistiques d’utilisation), ton consentement (publicités personnalisées, suivi, notifications) et nos obligations légales. Tu peux aussi introduire une réclamation auprès de ton autorité de protection des données (en France, la CNIL).

<a id="fr-11"></a>
### 11. Enfants

DEADGRID **ne s’adresse pas aux enfants de moins de 13 ans** (ou à l’âge minimum plus élevé applicable dans ton pays). Nous ne collectons pas sciemment de données personnelles d’enfants de moins de 13 ans. Si tu penses qu’un enfant nous a transmis des données personnelles, écris-nous et nous les supprimerons. Les publicités personnalisées ne sont affichées que si le suivi est autorisé et le consentement donné ; les parents peuvent l’empêcher dans iOS via **Réglages → Confidentialité et sécurité → Suivi** (en désactivant « Autoriser les demandes de suivi des apps ») et avec Temps d’écran.

<a id="fr-12"></a>
### 12. Sécurité

L’app communique avec notre serveur par des connexions chiffrées (HTTPS / WSS), et les mots de passe ne sont conservés que sous forme de hachage. Aucun système n’est parfaitement sûr ; utilise donc un mot de passe que tu n’utilises nulle part ailleurs.

<a id="fr-13"></a>
### 13. Modifications et contact

Nous pouvons mettre à jour cette politique lorsque le jeu évolue. La nouvelle version sera publiée ici avec une nouvelle date.

**Développeur :** Afonso Quinaz
**E-mail :** [support@deadgridgame.com](mailto:support@deadgridgame.com)
**Site web :** <https://github.com/afonsoquinaz/deadgrid-game>

---

© 2026 Afonso Quinaz
