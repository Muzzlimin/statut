<p align="center">
  <img src=".github/banner.svg" alt="Muzzlimin : statut de l'application" width="100%">
</p>

<p align="center">
  <a href="https://status.muzzlimin.com"><b>Voir le statut en direct →</b></a>
  &nbsp;·&nbsp;
  <a href="https://status.muzzlimin.com"><b>Live status →</b></a>
</p>

---

### 🟢 À quoi sert ce dépôt

Il publie l'état de l'application **Muzzlimin** (iPhone, iPad, Android) : tout fonctionne, une maintenance est en cours ou prévue, une mise à jour est disponible, ou une annonce est à lire.

L'application le consulte d'elle-même : à l'ouverture, au retour dans l'app, et régulièrement pendant qu'on l'utilise. Si quelque chose se passe, l'élève est prévenu par une fenêtre, puis par un bandeau discret.

### 📄 Ce qu'il contient

| | Fichier | Rôle |
| :-: | --- | --- |
| 🌐 | `index.html` | La page de statut publique, en français et en anglais. |
| 🧾 | `status.json` | L'état actuel, lu par l'application et par la page. |
| 🔗 | `CNAME` | L'adresse `status.muzzlimin.com`. |

### 🧭 Les informations publiées

| Champ | Ce que ça veut dire |
| --- | --- |
| `maintenance` | Une maintenance en cours ou prévue, avec ses dates, son message et ce qui est mis en pause. |
| `min_version` | En dessous de cette version, la mise à jour est obligatoire. |
| `recommended_version` | En dessous de cette version, une mise à jour est proposée. |
| `notice` | Une annonce : un titre, un message, une date de fin. |
| `updated_at` | La date de la dernière mise à jour. |

---

<p align="center">
  <sub>Ce dépôt ne contient aucune donnée d'élève ni aucun secret. Il est public pour que l'application puisse le lire sans compte.</sub>
</p>
