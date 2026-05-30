# How We Work ?
This repository serves as the single source of truth for how our team and community operate. It contains : 
  - [Code of conduct](#code-of-conduct),
  - [Contributing guideline](#contributing-guideline)

and other informations that help us collaborate effectively and transparently.

Feel free to [Star the repo !](https://github.com/evolvesmartercommunity/how-we-work)

---
## Code of Conduct

### 🌍 Our Commitment

We are committed to creating a welcoming, safe, and inclusive environment for everyone, regardless of gender, age, ability, ethnicity, religion, identity, background, or level of experience.

ES_ is a community built around learning, collaboration, and mutual support. Whether you are a beginner, a student, a professional, or simply curious, you deserve to be treated with respect and dignity.

All members are expected to uphold the values of respect, kindness, integrity, and constructive collaboration.

### 🤝 Expected Behavior

All community members should:

* Be respectful and inclusive in all interactions
* Use welcoming and constructive language
* Respect differing viewpoints and experiences
* Accept and provide feedback gracefully
* Support learning and knowledge sharing
* Assume good intent and act with empathy
* Help maintain a positive and collaborative environment

### 🚫 Unacceptable Behavior

Examples of unacceptable behavior include:

* Discrimination, harassment, or bullying of any kind
* Offensive, hateful, or derogatory comments
* Personal attacks, intimidation, or threats
* Trolling, baiting, or deliberately provoking conflicts
* Publishing private information without consent
* Disruptive, aggressive, or hostile behavior in discussions, events, repositories, or community spaces

### 🛡 Reporting Issues

If you experience or witness behavior that violates this Code of Conduct, please report it by contacting: `hello.evolvesmarter@gmail.com` with subject `CODE OF CONCUCT`.

Reports will be handled respectfully, confidentially, and as promptly as possible.

### 📜 Enforcement & Consequences

The Core Team is responsible for enforcing this Code of Conduct and may take appropriate action when necessary, including:

* A private warning
* Temporary restrictions from community spaces
* Removal of content or messages
* Temporary or permanent removal from the community

### 🤲 Our Pledge

Together, we aim to build a community where everyone feels welcome, respected, and empowered to learn, contribute, and grow.

A strong community is not defined by the number of its members, but by the way its members treat one another.

> Adapted from the [Contributor Covenant](https://www.contributor-covenant.org/) v2.1

---
## Contributing guideline

- **Tasks are created as issues** (by [Cypher1305](https://github.com/Cypher1305) or the project's team lead)
- Each Contributor **assigns or receives** an issue
- A branch is **created from `dev`** for each issue (Always from dev branch)
- Commit messages must reference the issue ID
- A **pull request** (PR) is made to `dev`
- 1 branch = 1 fonctionnality/feature = 1 PR
- Once the PR has been accepted, **the branch is deleted**

### 🗂️ Main branches

| Branche | Usage |
|---------|-------|
| `main` | Stable version, ready for production |
| `dev` | Development base (all functionalities converge here) |

### 🌱 Branch nomenclature

```bash
Type/XX/#num-title-in-kebab-case
```
| Prefix     | When to use it                   |
| ----------- | ----------------------------------- |
| `Feature/`  | New feature             |
| `Hotfix/`   | Bug fix                   |
| `Refactor/` | Code cleanup or reorganization |
| `doc/`      | For upload a document |

- XX = contributor's initials
- #num = GitHub issue number

Examples :

    Feature/BY/#12-addition-form-orientation

    Hotfix/KY/#16-fix-bug-scroll

    Doc/CZ/#20-search-results

#### 🛠 Contribution steps

1. Fork the project

- Click on **"Fork"** at the top right of the repository's GitHub page.
- This creates a **copy of the project on your own GitHub account**.

2. Clone your fork
```bash
git clone https://github.com/Cypher1305/JIREH..git
cd JIREH.
```
3. Add remote origin to official repository
```bash
git remote add upstream https://github.com/Cypher1305/JIREH..git
git remote -v # to verify
git fetch upstream # to fetch remote branches
```
3. Create a branch from issue
```bash
git checkout dev
git pull upstream dev
git checkout -b Feature/BY/#12-add-orientation-form
```
_Bring your contribution on your branch_
4. Commit your work
```bash
git add .
git commit -m "#12 Add-orientation-form"
```
5. Push the branch
```bash
git push -u origin Feature/BY/#12-add-orientation-form
```
_Proceed to a pull request (Add a clear description and link the issue with #12)_

6. Delete branch locally
```bash
git branch -d Feature/BY/#12-add-orientation-form
git push origin --delete Feature/BY/#12-add-orientation-form
```

---
<3 _Happy learning!_
