# 🎮 Dota 2 Match Analysis (Freelance, pro bono)



Exploratory data analysis (EDA) of **Dota 2 match statistics** using data from the OpenDota API(https://docs.opendota.com/), with final insights visualized in Tableau.



**Goal:** показать игровые тенденции (win rate Radiant/Dire, эффективность героев, динамика метрик) и подготовить интерактивные визуализации для медиа-публикации.



## 📈 Tableau Dashboard

➡️ **Ссылка на дашборд:** https://public.tableau.com/app/profile/alexandra.popova/viz/shared/BSTQMZB9W



## 📁 Structure

notebooks/

└─ dota2\_match\_analysis.ipynb

dashboards/

└─ tableau\_link.txt



## 🧰 Stack

Python (pandas, numpy, matplotlib, seaborn, scipy) · Jupyter  

Tableau · OpenDota API



## ✨ Highlights

- ~19K матчей, ~199K записей игроков (≈10 игроков на матч — валидная структура)

- Win rate Radiant/Dire ≈ 50/50 с небольшим перекосом

- Связь GPM ↔ Win Rate для героев (scatter + топы)

- Статистическая проверка гипотез (t-test): личный win rate игрока ↔ победа команды

- Интерактивные дашборды (Overview / Heroes / Players)



## 🔒 Data & Secrets

- Датасеты не публикуются в репозитории (см. `.gitignore`)

- Ключи и пароли храним в `.env` (и не коммитим)



## 📜 License

MIT. Data: OpenDota API.

