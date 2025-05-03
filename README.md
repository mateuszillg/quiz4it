# 📚 quiz4it – Interaktywna platforma quizów IT

🎯 **quiz4it** to edukacyjna platforma z interaktywnymi quizami opartymi na kursach certyfikacyjnych Google (IT Support, Cybersecurity i inne). Pomaga szybciej przyswajać wiedzę i skuteczniej się uczyć – quiz po quizie.

👉 [quiz4it.pl](https://quiz4it.pl)

---

## ✨ Co oferuje platforma?

- ✅ Quizy do najważniejszych modułów z kursów IT
- 📬 Newsletter (Sendy + AWS SES) z nowościami i materiałami
- 🧭 Roadmapa rozwoju projektu (kolejne quizy, ranking, punkty)
- 🌐 Lekki landing page oparty o Carrd (mobilny i szybki)
- 🚀 Otwarte repozytorium – #buildinpublic

---

## 🧪 Technologia (stack MVP)

| Obszar            | Narzędzie                             |
|-------------------|----------------------------------------|
| Landing Page      | [Carrd](https://carrd.co)             |
| Quizy             | HTML + CSS + JS (Vanilla)             |
| Hosting quizów    | Netlify                               |
| Formularze        | Carrd + Sendy                         |
| Email backend     | AWS SES                               |
| Repo + publikacja | GitHub Pages / Netlify                |

---

## 📌 Roadmapa (maj 2025)

- ✅ CLI quiz (Windows & Linux) – gotowe
- 🚧 Networking, Security – w przygotowaniu
- 🔜 Ranking, punkty, logowanie
- 🔜 Baza quizów z innych kursów Google (Cybersecurity, Data Analytics)
- 🔜 Wersja angielska
- 🔜 API do integracji

---

## 🎮 Moduł: CLI Quiz (MVP)

Quiz z podstawowych komend terminalowych dla systemów:
- 🖥 Windows CMD
- 🐧 Linux Bash

Quiz składa się z:
- 🔄 5 losowych pytań z bazy
- ✅ natychmiastowej informacji zwrotnej
- 📈 lokalnego zapisu wyniku (best score)

---

## 🔧 Uruchomienie lokalne

```bash
git clone https://github.com/mateuszillg/quiz4it.git
cd quiz4it_repo_for_git
python3 -m http.server
