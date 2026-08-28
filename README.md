# githubtest

Навчальна односторінкова сторінка **«GitHub для чайників»** — пояснює базові поняття Git/GitHub,
основні команди та процес командної роботи.

## Вміст репозиторію

| Файл | Призначення |
|------|-------------|
| [`index.html`](index.html) | Сама сторінка (HTML + CSS + JS в одному файлі) |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Як ми працюємо над проєктом удвох |

## Як переглянути

Відкрий `index.html` у браузері подвійним кліком — жодних залежностей чи збірки не потрібно.
Або через локальний сервер OpenServer: `http://githubtest`.

## Робота над проєктом

Проєкт веде команда з двох людей. Усі зміни потрапляють у `main` **лише через Pull Request**
з одним апрувом від другого учасника. Детальний порядок дій — у [CONTRIBUTING.md](CONTRIBUTING.md).

Коротко:

```bash
git clone https://github.com/0988280928v-coder/githubtest.git
cd githubtest
git switch -c feature/коротка-назва   # нова гілка під задачу
# ... правки ...
git add .
git commit -m "опис змін"
git push -u origin feature/коротка-назва
gh pr create --fill                   # або кнопка "Compare & pull request" на GitHub
```
