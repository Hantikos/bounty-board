# 💰 Доска заработка на GitHub

> Проверенная подборка платных задач на GitHub: реальные суммы, реальная конкуренция, реальные ловушки. Собрано через GitHub API, каждая сумма сверена по **телу issue**, а не по заголовку.

Аккаунт на момент сбора: 0 публичных репозиториев, 0 звёзд, 0 подписчиков — старт с нуля. Стратегия ниже учитывает это.

## 🎯 Главный вектор: Stellar Wave (Drips)

| Параметр | Значение |
|---|---|
| Программа | Stellar Wave Program, [drips.network/wave/stellar](https://www.drips.network/wave/stellar) |
| Текущая волна | Wave 11 |
| Окно | **18 ноя 14:00 → 25 ноя 14:00 UTC** |
| Бюджет волны | **$75 000** (нарастающим итогом $780 000 за 11 волн) |
| Механика | баллы → доля от пула волны, пропорционально баллам |
| Свободно сейчас | **216 задач / 20800 баллов**, конкуренция 0–1 комментарий |

**Почему это работает для пустого аккаунта.** Мейнтейнер назначает ровно одного исполнителя на задачу по заявке — это очередь, а не гонка PR'ов. Баллы начисляются за PR, закрытые до срока; после закрытия волны пул делится пропорционально.

> **Честно:** публичный курс «баллы → доллары» не раскрыт. Известен только бюджет волны. Любая оценка «$ за балл» — экстраполяция, а не факт.

### Протокол претензии

1. **Верифицировать личность** на [drips.network/wave](https://www.drips.network/wave) (GitHub OAuth + identity/KYC + кошелёк). Без этого баллы не начисляются — главный блокер.
2. **Выбрать задачу** с метками `drips-wave` + `N points`, приоритет `complexity: trivial`.
3. **Оставить заявку комментарием** в issue — бот `drips-wave[bot]` создаёт заявку со ссылкой на панель мейнтейнера:

   ```
   I'd like to work on this one — I can implement it and open a PR with a linked fix and green CI within the wave window.
   ```

4. **Дождаться назначения** (срок сдачи пришлёт бот). До назначения PR не открывать.
5. **PR → merge → баллы.** Ветка от `main`, Conventional Commits, `Fixes #<номер>`, CI зелёный.

## ✅ Задачи с максимальным шансом

Всего доступно **216 задач на 20800 баллов** (docs — проще всего, задача на 10–30 минут). Полный список с фильтрами — в `bounty-board.html`.

| Задача | Репозиторий | Баллы | Тип | Конкуренция |
|---|---|---|---|---|
| [docs: add an example to "Testing expectations" in ./CONTRIBUTING.md](https://github.com/soroworks/soroforge/issues/252) | `soroworks/soroforge`#252 | 100 | docs | свободна |
| [docs: add a godoc comment for Error](https://github.com/soroworks/soroforge/issues/253) | `soroworks/soroforge`#253 | 100 | docs | свободна |
| [docs: add an example to "Verifying against a changed SDK" in ./CONTRIBUTING.md](https://github.com/soroworks/soroforge/issues/254) | `soroworks/soroforge`#254 | 100 | docs | свободна |
| [docs: add a godoc comment for String](https://github.com/soroworks/soroforge/issues/255) | `soroworks/soroforge`#255 | 100 | docs | свободна |
| [docs: add an example to "Pull requests" in ./CONTRIBUTING.md](https://github.com/soroworks/soroforge/issues/256) | `soroworks/soroforge`#256 | 100 | docs | свободна |
| [test: add edge cases to the NewServer tests](https://github.com/soroworks/soroforge/issues/257) | `soroworks/soroforge`#257 | 100 | test | свободна |
| [docs: add an example to "License" in ./CONTRIBUTING.md](https://github.com/soroworks/soroforge/issues/258) | `soroworks/soroforge`#258 | 100 | docs | свободна |
| [test: add edge cases to the NewToken tests](https://github.com/soroworks/soroforge/issues/259) | `soroworks/soroforge`#259 | 100 | test | свободна |
| [docs: add an example to "Verified SDK and RPC versions" in ./README.md](https://github.com/soroworks/soroforge/issues/260) | `soroworks/soroforge`#260 | 100 | docs | свободна |
| [test: add edge cases to the ParseTokens tests](https://github.com/soroworks/soroforge/issues/261) | `soroworks/soroforge`#261 | 100 | test | свободна |
| [docs: add an example to "How deploying works" in ./README.md](https://github.com/soroworks/soroforge/issues/262) | `soroworks/soroforge`#262 | 100 | docs | свободна |
| [test: add edge cases to the NewSoroVault tests](https://github.com/soroworks/soroforge/issues/263) | `soroworks/soroforge`#263 | 100 | test | свободна |
| [docs: add an example to "Install" in ./README.md](https://github.com/soroworks/soroforge/issues/264) | `soroworks/soroforge`#264 | 100 | docs | свободна |
| [test: add edge cases to the ParseArgFlag tests](https://github.com/soroworks/soroforge/issues/265) | `soroworks/soroforge`#265 | 100 | test | свободна |
| [docs: add an example to "Release binaries" in ./README.md](https://github.com/soroworks/soroforge/issues/266) | `soroworks/soroforge`#266 | 100 | docs | свободна |
| [test: add edge cases to the ParseArgsJSON tests](https://github.com/soroworks/soroforge/issues/267) | `soroworks/soroforge`#267 | 100 | test | свободна |
| [docs: add an example to "Container image" in ./README.md](https://github.com/soroworks/soroforge/issues/268) | `soroworks/soroforge`#268 | 100 | docs | свободна |
| [test: add edge cases to the ParseArgsFile tests](https://github.com/soroworks/soroforge/issues/269) | `soroworks/soroforge`#269 | 100 | test | свободна |
| [docs: add an example to "Quickstart — deploy to testnet" in ./README.md](https://github.com/soroworks/soroforge/issues/270) | `soroworks/soroforge`#270 | 100 | docs | свободна |
| [test: add edge cases to the ParseSalt tests](https://github.com/soroworks/soroforge/issues/271) | `soroworks/soroforge`#271 | 100 | test | свободна |
| [docs: add an example to "Configuration reference" in ./README.md](https://github.com/soroworks/soroforge/issues/272) | `soroworks/soroforge`#272 | 100 | docs | свободна |
| [test: add edge cases to the ParseCLIArgs tests](https://github.com/soroworks/soroforge/issues/273) | `soroworks/soroforge`#273 | 100 | test | свободна |
| [docs: add an example to "Constructor arguments" in ./README.md](https://github.com/soroworks/soroforge/issues/274) | `soroworks/soroforge`#274 | 100 | docs | свободна |
| [test: add edge cases to the IsSAC tests](https://github.com/soroworks/soroforge/issues/275) | `soroworks/soroforge`#275 | 100 | test | свободна |
| [docs: add an example to "Initializers (contracts without constructors)" in ./README.md](https://github.com/soroworks/soroforge/issues/276) | `soroworks/soroforge`#276 | 100 | docs | свободна |
| [test: add edge cases to the UpgradeFuncOrDefault tests](https://github.com/soroworks/soroforge/issues/277) | `soroworks/soroforge`#277 | 100 | test | свободна |
| [test: add edge cases to the ParseCORSOrigins tests](https://github.com/soroworks/soroforge/issues/278) | `soroworks/soroforge`#278 | 100 | test | свободна |
| [docs: add an example to "Environment variables" in ./README.md](https://github.com/soroworks/soroforge/issues/279) | `soroworks/soroforge`#279 | 100 | docs | свободна |
| [test: add edge cases to the FormatStroops tests](https://github.com/soroworks/soroforge/issues/280) | `soroworks/soroforge`#280 | 100 | test | свободна |
| [docs: add an example to "CLI reference" in ./README.md](https://github.com/soroworks/soroforge/issues/281) | `soroworks/soroforge`#281 | 100 | docs | свободна |
| [docs: add an example to "GitHub Action" in ./README.md](https://github.com/soroworks/soroforge/issues/282) | `soroworks/soroforge`#282 | 100 | docs | свободна |
| [test: add edge cases to the DefaultClientFactory tests](https://github.com/soroworks/soroforge/issues/283) | `soroworks/soroforge`#283 | 100 | test | свободна |
| [test: add edge cases to the New tests](https://github.com/soroworks/soroforge/issues/284) | `soroworks/soroforge`#284 | 100 | test | свободна |
| [test: add edge cases to the RPCName tests](https://github.com/soroworks/soroforge/issues/285) | `soroworks/soroforge`#285 | 100 | test | свободна |
| [test: add edge cases to the Build tests](https://github.com/soroworks/soroforge/issues/286) | `soroworks/soroforge`#286 | 100 | test | свободна |
| [test: add edge cases to the NewCommandSigner tests](https://github.com/soroworks/soroforge/issues/287) | `soroworks/soroforge`#287 | 100 | test | свободна |
| [test: add edge cases to the ContractIDFromSimulation tests](https://github.com/soroworks/soroforge/issues/288) | `soroworks/soroforge`#288 | 100 | test | свободна |
| [test: add edge cases to the ContractIDFromScVal tests](https://github.com/soroworks/soroforge/issues/289) | `soroworks/soroforge`#289 | 100 | test | свободна |
| [test: add edge cases to the ContractIDFromDeployer tests](https://github.com/soroworks/soroforge/issues/290) | `soroworks/soroforge`#290 | 100 | test | свободна |
| [test: add edge cases to the InstanceLedgerKey tests](https://github.com/soroworks/soroforge/issues/291) | `soroworks/soroforge`#291 | 100 | test | свободна |

## 💵 Фиксированные суммы

| Задача | Сумма (реальная) | Конкуренция | Вердикт |
|---|---|---|---|
| [[BOUNTY] RCS Support](https://github.com/microg/GmsCore/issues/2994) | $14,999 — реальная сумма (спонсоры-люди, трек bountyhub) | 703 комментария, 21 открытый PR | тяжело |
| [[BOUNTY] WearOS Support](https://github.com/microg/GmsCore/issues/2843) | $2,340 (в заголовке) — фактически ~$700: $200 от автора + ~$500 от других | много комментариев, жёсткие условия выплаты | тяжело |
| [LLM Provider Abstraction Layer](https://github.com/Spectral-Finance/lux/issues/99) | $600 — $600 (платит мейнтейнер rparcus, COLLABORATOR) | 41 открытый PR | тяжело |
| [[BOUNTY $75] CLAUDE.md template для Next.js + SQLite](https://github.com/claude-builders-bounty/claude-builders-bounty/issues/2) | $75 — $75, выплата автоматически при merge | 282 открытых PR, 1648 комментариев | реально, но невыгодно |
| [Port Qubes to ppc64](https://github.com/QubesOS/qubes-issues/issues/4318) | 3 BTC (≈$300k+ по любому курсу) — 0,35 BTC подтверждено + 0,8 BTC обещано от @leo-lb | нет PR-гонки: работа с 2022 г., dev переехал на GitLab | реально, но не в этой жизни |
| [OpenCollective banners: redundant avatar preload](https://github.com/FreezingMoon/AncientBeast/issues/3252) | 40 XTR (собственный токен проекта) — 40 XTR — не реальные доллары | issue уже назначен на другого участника | не деньги |

## ⛔ Ловушки — не тратьте время

| Репозиторий | Сигнал | Вердикт |
|---|---|---|
| `IES-BoilerRoom/*` | В теле issue прямым текстом: «manual pull requests from human engineers are not reviewed on this mirror» | **Ферма** |
| `zhangjiayang6835-cyber/bounty-plaza` | «$10000 Recursive Bounty Architect — Five-Fold Esoteric», метки «bounty,real» | **Ферма** |
| `Scottcjn/rustchain-bounties` | Тысячи issue на 2–150 RTC (собственный токен), «First Blood — First Merged PR» | **Токен, не деньги** |
| `NSPG13/agent-bounties` | «[META · unavailable] Bounty-distribution standing-meta bounty» | **Ферма** |
| `relayhop/sn-monetization-runtime` | Авто-issues вида «[radar] SN open bounty <timestamp>» | **Ферма** |

## 🔎 Как проверять баунти (чтобы не попасть на ферму)

1. Читать **тело** issue, а не заголовок. Заголовок `$2 340` в теле может оказаться «$200».
2. Искать **реальный платёжный рельс**: algora.io, polar.sh, opire.dev, bountyhub.dev, opencollective — или подтверждённые BTC-обещания в комментариях.
3. Смотреть, **ревьюятся ли human PR**. Ферма прямо пишет «manual pull requests from human engineers are not reviewed».
4. Считать **конкурентов**: `closed_by_pull_requests` в API отдаёт число претендующих PR.
5. Отсекать «награды» в собственных токенах проекта (XTR, RTC) — это не деньги.

---

Собрано 17.11.2026 через GitHub API.
