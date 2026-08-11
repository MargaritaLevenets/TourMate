# research/screens/

Скриншоти чужих застосунків — матеріал для аналізу конкурентів.

## Як називати файли

`продукт-екран.png` — латиницею, малими літерами, через дефіс:

```
tripit-app-screen-2.png
google-calendar-app-screens.png
bokun-login-dostup-obmezheno.png
```

Якщо екран заблокований логіном і всередину ми не потрапили — суфікс
`-dostup-obmezheno`. Так одразу видно, що це двері, а не сам продукт.

## Правило

Кожен скриншот має бути згаданий у таблиці конкурентів
у [`../research.md`](../research.md) — інакше через місяць ніхто не згадає,
навіщо він тут.

---

## Що вже зняте (7 серпня 2026)

Знято під телефон, ширина 390 px. Екрани самих застосунків узяті зі сторінок
App Store — це офіційні кадри продукту від самих компаній, доступні без акаунта.

### Peek Pro

| Файл | Що на ньому |
|---|---|
| `peekpro-home.png` | Головна сайту: «More Bookings, Happier Customers», позиціювання як «AI operating system» |
| `peekpro-staff-app.png` | Сторінка «Empower Staff» — що обіцяють персоналу й гідам |
| `peekpro-focus-guide-app.png` | Сторінка App Store застосунку **PeekPro Focus** — окремого продукту саме для гідів |
| `peekpro-focus-screens.png` | **Найважливіший кадр.** Екран гіда: «Hi Guide 👋 / Today is Wednesday, Aug 30», далі — наступний тур, скільки турів сьогодні й за 7 днів, погода, рейтинг |

Ціни Peek Pro зняти не вдалося: **публічної сторінки з цінами немає**, сайт веде
тільки на форму «замовити демо», де питають річний оборот. Це саме по собі факт —
див. вісь «Монетизація» в [`../research.md`](../research.md).

### Bókun

| Файл | Що на ньому |
|---|---|
| `bokun-pricing.png` | Сторінка цін: Free $0 / Start $49 / Plus $149 / Premium $499 на місяць |
| `bokun-app-screens.png` | Екрани застосунку: «Departure Details», «Pick ups» зі станами Arrived / No-show, «Scan». Нижня навігація: Schedule · Pick-ups · Scan · Settings |
| `bokun-app-reviews.png` | Один відгук на 2★: «App Calendar is useless», 14.04.2024. **Увага:** загальної оцінки 2.3★ і решти цитат на цьому кадрі **не видно** — вони взяті зі [сторінки відгуків App Store](https://apps.apple.com/us/app/bokun/id1500788456?see-all=reviews&platform=iphone), перевірено 11.08.2026 |
| `bokun-login-dostup-obmezheno.png` | **Доступ обмежений.** Вхід у продукт: «Welcome back!», вхід через Google або через Viator |

### Google Calendar

| Файл | Що на ньому |
|---|---|
| `google-calendar-marketing.png` | Сторінка-вітрина (без акаунта продукт не відкривається взагалі) |
| `google-calendar-app-screens.png` | Екрани застосунку: місяць кольоровими блоками, створення події, бічне меню |
| `google-calendar-login-dostup-obmezheno.png` | **Доступ обмежений.** Екран входу Google |

### Wanderlog

| Файл | Що на ньому |
|---|---|
| `wanderlog-app-screen-1.png` … `-4.png` | Екрани застосунку. Головне: `-2` — вкладки Overview · Itinerary · Explore · $ з розділами «Notes» і «Places to visit»; `-4` — **карта з пронумерованими пінами + чипи днів (Sat 3/21, Sun 3/22…) + власна нотатка на точці («Get photo of bridge!») + «Optimize route»** |

Веб-версію Wanderlog зняти не вдалося: сторінка безперервно перемальовується
(карта + відео), інструмент знімка не встигає зробити стабільний кадр.
Екрани застосунку це компенсують.

### TripIt

| Файл | Що на ньому |
|---|---|
| `tripit-app-screen-2.png` | **Найважливіший кадр.** День поїздки як вертикальна лінія з іконками: рейс, пересадка, авто, готель, вечеря. Статус-чипи «On Time», ключові факти жирним (Seat 19B, Arrive 9:15 AM) |
| `tripit-app-screen-3.png` | Список поїздок із відліком «Starts in 121 days» + смуга довіри: NYT, Forbes, Travel+Leisure, 4.8★, 200k+ оцінок |
| `tripit-app-screen-1.png`, `-4.png` | Загальний вигляд і сповіщення |

Екран входу TripIt зняти не вдалося з тієї ж технічної причини, що й Wanderlog
(сторінка не зупиняє перемальовування). Сам факт перевірено: `tripit.com/account/login`
віддає форму «Sign in to TripIt» — **продукт за логіном, доступ обмежений**.
