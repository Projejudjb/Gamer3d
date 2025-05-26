<!DOCTYPE html>

<html lang="fr">

<head>

  <meta charset="UTF-8" />

  <meta name="viewport" content="width=device-width,initial-scale=1.0" />

  <title>Diamand Gabon</title>

  <style>

    :root {

      --bg-dark: #2d2d2d;

      --bg-light: #f5f5f5;

      --text-main: #ececec;

      --text-dark: #222;

      --accent: #000;

      --btn-bg: #444;

      --btn-hover: #222;

      --header-height: 60px;

    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {

      font-family: 'Segoe UI', sans-serif;

      background: var(--bg-light);

      color: var(--text-dark);

      line-height: 1.6;

    }

    header {

      position: fixed;

      top: 0; left: 0; right: 0;

      height: var(--header-height);

      background: var(--bg-dark);

      display: flex;

      align-items: center;

      padding: 0 1rem;

      z-index: 1000;

    }

    header img.logo {

      height: 40px;

    }

    nav {

      margin-left: auto;

    }

    nav a {

      color: var(--text-main);

      margin: 0 0.75rem;

      text-decoration: none;

      font-weight: 500;

    }

    nav a:hover {

      text-decoration: underline;

    }

    main {

      padding-top: calc(var(--header-height) + 1rem);

    }

    section {

      padding: 3rem 1rem;

      max-width: 1000px;

      margin: auto;

    }

    h1, h2 {

      color: var(--accent);

      margin-bottom: 1rem;

    }

    .btn {

      display: inline-block;

      background: var(--btn-bg);

      color: #fff;

      padding: 0.6rem 1.2rem;

      border-radius: 4px;

      text-decoration: none;

      transition: background .2s;

      font-weight: 500;

    }

    .btn:hover {

      background: var(--btn-hover);

    }

    .grid {

      display: grid;

      gap: 1.5rem;

    }

    .grid-3 {

      grid-template-columns: repeat(auto-fill,minmax(280px,1fr));

    }

    .card {

      background: #fff;

      border-radius: 6px;

      box-shadow: 0 2px 8px rgba(0,0,0,.1);

      padding: 1.5rem;

    }

    footer {

      background: var(--bg-dark);

      color: var(--text-main);

      text-align: center;

      padding: 1.5rem 1rem;

      font-size: 0.9rem;

      margin-top: 2rem;

    }

    footer a {

      color: var(--text-main);

      margin: 0 0.5rem;

      text-decoration: none;

    }

    footer a:hover {

      text-decoration: underline;

    }

  </style>

</head>

<body>



  <!-- HEADER -->

  <header>

    <a href="#home">

      <img src="logo-diamand-gabon.png" alt="Logo Diamand Gabon" class="logo" />

    </a>

    <nav>

      <a href="#home">Accueil</a>

      <a href="#services">Services</a>

      <a href="#tournois">Tournois</a>

      <a href="#live">Live</a>

      <a href="#blog">Blog</a>

      <a href="#chat-community">Chat</a>

      <a href="#profil">Profil</a>

      <a href="#vip">VIP</a>

      <a href="#faq">FAQ</a>

    </nav>

  </header>



  <main>



    <!-- ACCUEIL -->

    <section id="home" style="background: #ececec; text-align: center;">

      <h1>Bienvenue sur Diamand Gabon</h1>

      <p>Ton guichet unique pour Free Fire, Call of Duty, Streaming, Tournois et plus encore.</p>

      <a href="#services" class="btn" style="margin-top:1rem;">Découvrir nos services</a>

    </section>



    <!-- SERVICES -->

    <section id="services">

      <h2>Nos Services</h2>

      <div class="grid grid-3">

        <div class="card">

          <h3>Free Fire Diamants</h3>

          <p>Recharge rapide : 1500 XAF = 100 diamants (VIP : 150)</p>

          <a href="#services" class="btn">Commander</a>

        </div>

        <div class="card">

          <h3>Call of Duty Mobile (CP)</h3>

          <p>Recharge CP : 1400 XAF = 80 CP</p>

          <a href="#services" class="btn">Commander</a>

        </div>

        <div class="card">

          <h3>Streaming 30j</h3>

          <p>Netflix, Prime, Disney+, etc. – 2000 XAF</p>

          <a href="#services" class="btn">S’abonner</a>

        </div>

        <div class="card">

          <h3>EVO Free Fire</h3>

          <p>Abonnement automatique et privilèges EVO</p>

          <a href="#services" class="btn">En savoir plus</a>

        </div>

      </div>

    </section>



    <!-- TOURNOIS -->

    <section id="tournois" style="background: #ececec;">

      <h2>Tournois Mensuels</h2>

      <p>Battle of King (VIP) • Ascension Royale (Non-VIP)</p>

      <a href="#tournois" class="btn">S’inscrire</a>

    </section>



    <!-- LIVE -->

    <section id="live">

      <h2>En Direct sur YouTube</h2>

      <iframe width="100%" height="450"

        src="https://www.youtube.com/embed?listType=user_uploads&list=gabondiaman"

        frameborder="0" allowfullscreen>

      </iframe>

      <div style="margin-top:1rem; text-align:center;">

        <a href="https://youtube.com/@gabondiaman" target="_blank" class="btn">Voir sur YouTube</a>

        <a href="#live" class="btn">Regarder ici</a>

      </div>

    </section>



    <!-- BLOG -->

    <section id="blog" style="background: #ececec;">

      <h2>Actus & Informations</h2>

      <div class="grid grid-3">

        <div class="card">

          <h3>Tournoi VIP – Juin 2025</h3>

          <p>Préparez-vous pour le Battle of King du 10 au 16 juin…</p>

          <a href="#blog" class="btn">Lire plus</a>

        </div>

        <!-- autres articles… -->

      </div>

    </section>



    <!-- CHAT COMMUNAUTAIRE -->

    <section id="chat-community">

      <h2>Chat Communauté</h2>

      <div class="card" style="height:300px; overflow-y:auto;">

        <p><strong>VIP_Joueur1</strong> : Salut la team ! 😊</p>

        <p><strong>Guest123</strong> : En route pour le tournoi ! 🔥</p>

      </div>

      <div style="margin-top:0.5rem;">

        <input type="text" placeholder="Écris un message..." style="width:80%;padding:.5rem;border:1px solid #ccc;border-radius:4px;">

        <button class="btn">Envoyer</button>

      </div>

    </section>



    <!-- CHAT PRIVÉ -->

    <section id="chat-private" style="background: #ececec;">

      <h2>Chat Privé</h2>

      <p>Accède à tes conversations privées.</p>

      <a href="#chat-private" class="btn">Voir mes conversations</a>

    </section>



    <!-- PROFIL -->

    <section id="profil">

      <h2>Mon Profil</h2>

      <img src="default-profile.png" alt="Avatar" style="width:100px;border-radius:50%;border:3px solid var(--accent);">

      <p>Pseudo : <strong>Therence</strong></p>

      <p>Statut : <strong>VIP</strong></p>

      <p>Fidélité : <strong>35 / 60 points</strong></p>

    </section>



    <!-- VIP -->

    <section id="vip" style="background: #ececec;">

      <h2>Espace VIP</h2>

      <p>Profite d’avantages exclusifs, tarifs réduits et plus encore.</p>

      <a href="#vip" class="btn">Devenir VIP</a>

    </section>



    <!-- FAQ -->

    <section id="faq">

      <h2>FAQ</h2>

      <details><summary>Comment devenir VIP ?</summary><p>En souscrivant un pass VIP via la page VIP.</p></details>

      <details><summary>Moyens de paiement ?</summary><p>Moov Money & Airtel Money.</p></details>

      <details><summary>Tournoi non VIP ?</summary><p>Ascension Royale – 1 mois VIP offert.</p></details>

    </section>



    <!-- LÉGAL -->

    <section id="terms" style="background: #ececec;">

      <h2>Conditions d’Utilisation</h2>

      <p>Texte des conditions…</p>

    </section>

    <section id="privacy">

      <h2>Politique de Confidentialité</h2>

      <p>Texte de la politique…</p>

    </section>



  </main>



  <!-- FOOTER -->

  <footer>

    <a href="#terms">Conditions</a> |

    <a href="#privacy">Confidentialité</a> |

    <a href="#home">Top</a>

    <p>© 2025 Diamand Gabon</p>

  </footer>



  <!-- Tawk.to Script -->

  <script type="text/javascript">

    var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();

    (function(){

      var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];

      s1.async=true;

      s1.src='https://embed.tawk.to/6830ca5543a2a8190b59daae/1irv9co1g';

      s1.charset='UTF-8';

      s1.setAttribute('crossorigin','*');

      s0.parentNode.insertBefore(s1,s0);

    })();

  </script>

</body>

</html>
