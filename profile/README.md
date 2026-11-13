
<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Manrope&weight=700&size=38&pause=1000&color=EB2544&background=FFFFFF00&center=true&vCenter=true&width=700&lines=React+AntiCheat;Minecraft+Cheat+Protection" alt="React AntiCheat"/></a>

<p>Бесплатный античит для Minecraft с анализом поведения игроков</p>

<p>
  <a href="https://react-ac.space"><img src="https://img.shields.io/badge/Website-EB2544?style=plastic&logo=googlechrome&logoColor=white" alt="Website"/></a>
  <a href="https://t.me/react_ac"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=plastic&logo=telegram&logoColor=white" alt="Telegram"/></a>
  <a href="https://t.me/react_ac_support"><img src="https://img.shields.io/badge/Support-555555?style=plastic&logo=telegram&logoColor=white" alt="Support"/></a>
</p>

<p>
  <a href="https://github.com/react-minecraft/plugin"><img src="https://img.shields.io/github/stars/react-minecraft/plugin?style=plastic&logo=github&logoColor=white" alt="Stars"/></a>
  <a href="https://github.com/react-minecraft/plugin/blob/master/LICENSE"><img src="https://img.shields.io/github/license/react-minecraft/plugin?style=plastic&logo=opensourceinitiative&logoColor=white" alt="License"/></a>
</p>

</div>


## О проекте

**React AntiCheat** — античит для Minecraft, который использует машинное обучение для анализа действий игроков.

Основное внимание уделяется поворотам во время боя. React собирает необходимые данные, получает результаты анализа и сохраняет историю проверок. Администрация может следить за подозрительными игроками и самостоятельно решать, как реагировать на нарушения.

Проект не ограничивается одним плагином. Отдельные компоненты отвечают за анализ, а дополнительные функции можно подключать через аддоны.


## Репозитории

### Основные компоненты

| Проект | Описание |
|:-------|:---------|
| **[plugin](https://github.com/react-minecraft/plugin)** | Основной плагин React, обработка проверок и API |
| **[rcp](https://github.com/react-minecraft/rcp)** | Компонент для работы моделей и подключения к сервису |

### Аддоны

| Проект | Описание |
|:-------|:---------|
| [menu-addon](https://github.com/react-minecraft/menu-addon) | Меню игроков с историей проверок |
| [hologram-addon](https://github.com/react-minecraft/hologram-addon) | Голограммы со статистикой игроков |
| [punish-addon](https://github.com/react-minecraft/punish-addon) | Наказания с настраиваемыми анимациями |


## Разработка

У React есть API, через который можно добавлять свои функции, обрабатывать события и подключать собственные проверки.

Для начала можно воспользоваться готовыми примерами:

- **[example-addon](https://github.com/react-minecraft/example-addon)** — шаблон аддона с обработкой событий React.
- **[example-rcp](https://github.com/react-minecraft/example-rcp)** — пример подключения собственной логики анализа.

В репозиториях есть исходный код и инструкции по сборке. Если возникнут вопросы по разработке, можно обратиться к [g4vrk](https://t.me/g4vrk).


## Установка

Актуальные сборки и требования к серверу можно найти в [основном репозитории](https://github.com/react-minecraft/plugin).

Когда доступен подписанный стабильный релиз, плагин сам загружает RCP. Для проверки ночной сборки [поставьте RCP вручную](https://github.com/react-minecraft/rcp#что-это). Для работы с сервисом React привяжите сервер к аккаунту на [react-ac.space](https://react-ac.space) командой `/react link`.


<div align="center">

<sub>React AntiCheat — open-source Minecraft anticheat.</sub>

</div>
