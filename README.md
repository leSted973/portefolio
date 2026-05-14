[lettre_motivation_steddy.html](https://github.com/user-attachments/files/27762377/lettre_motivation_steddy.html)

<style>
  @import url('https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400;0,500;1,400&family=DM+Sans:wght@300;400;500&display=swap');

  .lettre-wrap {
    max-width: 680px;
    margin: 0 auto;
    padding: 2rem 0;
    font-family: 'DM Sans', sans-serif;
  }

  .lettre-card {
    background: var(--color-background-primary);
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-lg);
    padding: 3rem 3.5rem;
    position: relative;
    overflow: hidden;
  }

  .lettre-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0;
    width: 4px; height: 100%;
    background: #534AB7;
  }

  .header-row {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 2.5rem;
  }

  .nom-bloc .prenom {
    font-family: 'EB Garamond', serif;
    font-size: 26px;
    font-weight: 500;
    color: var(--color-text-primary);
    margin: 0 0 2px;
  }

  .nom-bloc .nom {
    font-family: 'EB Garamond', serif;
    font-size: 26px;
    font-weight: 400;
    font-style: italic;
    color: #534AB7;
    margin: 0 0 10px;
  }

  .nom-bloc .titre {
    font-size: 12px;
    font-weight: 400;
    color: var(--color-text-secondary);
    letter-spacing: 0.08em;
    text-transform: uppercase;
    margin: 0 0 8px;
  }

  .contact-infos {
    display: flex;
    flex-direction: column;
    gap: 4px;
  }

  .contact-infos a, .contact-infos span {
    font-size: 13px;
    color: var(--color-text-secondary);
    text-decoration: none;
    display: flex;
    align-items: center;
    gap: 6px;
  }

  .contact-infos a:hover {
    color: #534AB7;
  }

  .date-lieu {
    font-size: 13px;
    color: var(--color-text-secondary);
    text-align: right;
    line-height: 1.6;
  }

  .objet-ligne {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 2rem;
    padding-bottom: 1.5rem;
    border-bottom: 0.5px solid var(--color-border-tertiary);
  }

  .objet-label {
    font-size: 11px;
    font-weight: 500;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--color-text-secondary);
    white-space: nowrap;
  }

  .objet-texte {
    font-size: 13px;
    font-weight: 500;
    color: var(--color-text-primary);
  }

  .corps {
    font-size: 15px;
    line-height: 1.9;
    color: var(--color-text-primary);
    font-weight: 300;
  }

  .corps p {
    margin: 0 0 1.2rem;
  }

  .corps p:last-child {
    margin-bottom: 0;
  }

  .highlight {
    color: #534AB7;
    font-weight: 500;
  }

  .signature-bloc {
    margin-top: 2.5rem;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    gap: 4px;
  }

  .signature-nom {
    font-family: 'EB Garamond', serif;
    font-size: 20px;
    font-style: italic;
    color: var(--color-text-primary);
  }

  .signature-sous {
    font-size: 12px;
    color: var(--color-text-secondary);
  }

  .tags-row {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    margin-top: 2rem;
    padding-top: 1.5rem;
    border-top: 0.5px solid var(--color-border-tertiary);
  }

  .tag {
    font-size: 11px;
    font-weight: 500;
    padding: 4px 12px;
    border-radius: 20px;
    background: #EEEDFE;
    color: #3C3489;
    letter-spacing: 0.04em;
  }

  .copy-btn {
    margin-top: 1.5rem;
    width: 100%;
    padding: 10px;
    font-size: 13px;
    cursor: pointer;
    border-radius: var(--border-radius-md);
    border: 0.5px solid var(--color-border-secondary);
    background: transparent;
    color: var(--color-text-secondary);
    transition: background 0.15s;
  }
  .copy-btn:hover {
    background: var(--color-background-secondary);
    color: var(--color-text-primary);
  }
</style>

<div class="lettre-wrap">
  <div class="lettre-card">
    <div class="header-row">
      <div class="nom-bloc">
        <p class="prenom">Stéddy</p>
        <p class="nom">Marie-Joseph</p>
        <p class="titre">Étudiant BTS SIO — Option SLAM · 19 ans</p>
        <div class="contact-infos">
          <span><i class="ti ti-phone" style="font-size:15px" aria-hidden="true"></i> 06 94 49 15 90</span>
          <a href="mailto:steddymj@gmail.com"><i class="ti ti-mail" style="font-size:15px" aria-hidden="true"></i> steddymj@gmail.com</a>
        </div>
      </div>
      <div class="date-lieu">
        Île-de-France<br>Mai 2026
      </div>
    </div>

    <div class="objet-ligne">
      <span class="objet-label">Objet</span>
      <span class="objet-texte">Présentation de mon profil — Développeur en formation, BTS SIO SLAM</span>
    </div>

    <div class="corps">
      <p>Madame, Monsieur,</p>

      <p>
        Je m'appelle <span class="highlight">Stéddy Marie-Joseph</span>, j'ai 19 ans et je suis actuellement en dernière année de
        <span class="highlight">BTS Services Informatiques aux Organisations, option SLAM</span>
        (Solutions Logicielles et Applications Métiers). Ce profil GitHub est le reflet de mon parcours,
        de mes apprentissages et de ma progression en tant que développeur.
      </p>

      <p>
        Tout au long de ma formation, j'ai développé des compétences solides en conception et développement
        d'applications, en gestion de bases de données ainsi qu'en analyse des besoins utilisateurs.
        Les projets présents ici illustrent concrètement ce que j'ai appris à mettre en pratique.
      </p>

      <p>
        Ce qui me définit professionnellement, c'est avant tout mon <span class="highlight">sérieux</span> et ma
        <span class="highlight">motivation</span>. Je suis quelqu'un de rigoureux, qui s'implique pleinement dans
        chaque projet, aussi bien en autonomie qu'au sein d'une équipe. J'accorde une grande importance à l'écoute —
        des besoins du client, des retours de mes collaborateurs — car je suis convaincu que la qualité d'un
        développement repose autant sur la communication que sur le code lui-même.
      </p>

      <p>
        Je suis aujourd'hui à la recherche d'opportunités pour mettre mes compétences en application,
        continuer à progresser et contribuer à des projets concrets. N'hésitez pas à parcourir mes dépôts
        et à me contacter si mon profil vous intéresse.
      </p>

      <p>Dans l'attente d'un échange, je reste disponible et vous adresse mes cordiales salutations.</p>
    </div>

    <div class="signature-bloc">
      <span class="signature-nom">Stéddy Marie-Joseph</span>
      <span class="signature-sous">BTS SIO · Option SLAM</span>
    </div>

    <div class="tags-row">
      <span class="tag">BTS SIO SLAM</span>
      <span class="tag">Développement applicatif</span>
      <span class="tag">Travail en équipe</span>
      <span class="tag">Sérieux &amp; motivation</span>
      <span class="tag">Open to opportunities</span>
    </div>
  </div>

  <button class="copy-btn" onclick="copyText()">
    <i class="ti ti-copy" aria-hidden="true"></i> Copier le texte de la lettre
  </button>
</div>

<script>
function copyText() {
  const text = `Stéddy Marie-Joseph
Étudiant BTS SIO — Option SLAM · 19 ans
📞 06 94 49 15 90 | ✉ steddymj@gmail.com
Île-de-France, Mai 2026

Objet : Présentation de mon profil — Développeur en formation, BTS SIO SLAM

Madame, Monsieur,

Je m'appelle Stéddy Marie-Joseph, j'ai 19 ans et je suis actuellement en dernière année de BTS Services Informatiques aux Organisations, option SLAM (Solutions Logicielles et Applications Métiers). Ce profil GitHub est le reflet de mon parcours, de mes apprentissages et de ma progression en tant que développeur.

Tout au long de ma formation, j'ai développé des compétences solides en conception et développement d'applications, en gestion de bases de données ainsi qu'en analyse des besoins utilisateurs. Les projets présents ici illustrent concrètement ce que j'ai appris à mettre en pratique.

Ce qui me définit professionnellement, c'est avant tout mon sérieux et ma motivation. Je suis quelqu'un de rigoureux, qui s'implique pleinement dans chaque projet, aussi bien en autonomie qu'au sein d'une équipe. J'accorde une grande importance à l'écoute — des besoins du client, des retours de mes collaborateurs — car je suis convaincu que la qualité d'un développement repose autant sur la communication que sur le code lui-même.

Je suis aujourd'hui à la recherche d'opportunités pour mettre mes compétences en application, continuer à progresser et contribuer à des projets concrets. N'hésitez pas à parcourir mes dépôts et à me contacter si mon profil vous intéresse.

Dans l'attente d'un échange, je reste disponible et vous adresse mes cordiales salutations.

Stéddy Marie-Joseph
BTS SIO · Option SLAM`;

  navigator.clipboard.writeText(text).then(() => {
    const btn = document.querySelector('.copy-btn');
    btn.innerHTML = '<i class="ti ti-check" aria-hidden="true"></i> Copié !';
    setTimeout(() => {
      btn.innerHTML = '<i class="ti ti-copy" aria-hidden="true"></i> Copier le texte de la lettre';
    }, 2000);
  });
}
</script>
