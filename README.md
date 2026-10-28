# 🎃 El codi maleït

> Una investigació de Halloween per descobrir els secrets amagats en un repositori Git.

## 👻 Introducció

La web de la **Casa dels Ecos** ha estat sabotejada. Al repositori hi ha canvis sospitosos, fitxers modificats i missatges amagats en diferents branques.

La teva missió és investigar l'historial del projecte, seguir les pistes i reconstruir el misteri utilitzant les eines de Git.

## 🎯 Objectius del projecte

- Clonar un repositori de GitHub.
- Consultar les branques locals i remotes.
- Canviar de branca i inspeccionar-ne els fitxers.
- Consultar l'historial de commits.
- Analitzar els canvis introduïts en un commit.
- Recuperar informació de versions anteriors.
- Crear una branca pròpia i registrar els resultats amb un commit.
- Millorar la documentació del projecte amb Markdown.

## 🛠️ Tecnologies utilitzades

- **Git:** control de versions i gestió de branques.
- **GitHub:** allotjament del repositori.
- **HTML:** estructura de la pàgina web.
- **Visual Studio Code:** editor de codi recomanat.
- **Markdown:** format utilitzat per documentar el projecte.

## 🚀 Instal·lació i execució

### Requisits previs

- Tenir Git instal·lat.
- Disposar de Visual Studio Code o un editor de text.
- Tenir accés a GitHub i una connexió a Internet per clonar el repositori.

### 1. Clonar el repositori

Obre un terminal i executa:

```bash
git clone https://github.com/jspJESS/codi-maleit.git
```

### 2. Entrar a la carpeta del projecte

```bash
cd codi-maleit
```

### 3. Obrir el projecte amb Visual Studio Code

```bash
code .
```

### 4. Obrir la pàgina web

Obre el fitxer `index.html` amb el navegador. També pots utilitzar l'extensió Live Server si ja la tens instal·lada, però no és necessària.

## 📁 Estructura del projecte

L'estructura pot variar segons la branca seleccionada.

```text
codi-maleit/
├── index.html
├── README.md
└── pistes/
    └── fitxers de pistes (segons la branca)
```

## 🌿 Branques de Git

Les diferents branques permeten investigar versions alternatives del projecte sense modificar directament la branca principal.

Durant l'activitat es treballa amb:

- `main`: versió inicial del projecte.
- Branques d'investigació: contenen informació relacionada amb el misteri.
- `solucio-final`: branca personal on es documenten els resultats i les millores.

No s'han d'eliminar branques ni fer canvis directament a `main`.

## 💻 Comandes Git principals

| Comanda | Funció |
|---|---|
| `git clone URL` | Clona un repositori. |
| `git branch -a` | Mostra les branques locals i remotes. |
| `git checkout nom-branca` | Canvia de branca. |
| `git checkout -b nom-branca` | Crea una branca i hi canvia. |
| `git log --oneline` | Mostra l'historial resumit. |
| `git show HASH` | Inspecciona un commit. |
| `git status` | Mostra l'estat del repositori. |
| `git add fitxer` | Prepara un fitxer per al commit. |
| `git commit -m "missatge"` | Desa els canvis a l'historial. |

## 📚 Aprenentatges

Aquest projecte permet practicar el control de versions amb Git, la navegació entre branques, la inspecció de commits i la recuperació d'informació de versions anteriors.

També reforça la importància de treballar en branques pròpies, documentar els canvis i mantenir una estructura de projecte clara.

## 📜 Normes del repte

- No fer commits directament a `main`.
- No eliminar cap branca del projecte.
- Llegir les instruccions del professorat abans de començar.
- No revelar les pistes ni la solució del misteri en aquesta documentació.

---

🎃 **Bona investigació!** Segueix les petjades de Git i descobreix què ha passat a la Casa dels Ecos.
