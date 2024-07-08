## Аббревиатуры:
Будет дополняться со временем

программы:
* JR - join request
* BC - broadcast
* PA - parser
* SC - script

типы каналов:
* FR - free
* VP - vip
* SV - super vip

площадки:
* PO - pocketoption
* IQ - iq option
* OL - olymptrade
* BI - binomo
* QX - quotex

специальные:
* UNION - объединение нескольких
* master - отдельный мастер канал (вместо цвета)
* base - канал без цвета


## Название репозиториев модулей:
шаблон:
* **название**
* **примерНазвания**

примеры:
* logger
* sdb
* keitaroConversion


## Название репозиториев шаблонов/программ:
в эту группу входят репозитории:
* Программы по типу chat_join_request ботов, которые имеют базовый функционал подходходящий для каждого бота, котрый автоматически принимает в канал.

шаблон:
* **название_тип**
* **примерНазвания_тип**

примеры:
* joinRequest_tbot
* broadcast_tbot
* getUserId_tbot
* telegramChat_parser
* platform_parser
* databaseDump_script
* restartComputer_script


## Название репозиториев конкретных решений:
Будет дополнятся со временем

описание:
К этой категории относятся программы для конкретного:
* тг канала
* сайта
* и тп

общий шаблон:
* **шаблонКода_название**

шаблон для автоприемщиков:
* **шаблонКода_актер_цветканалаПлощадка_тип(free/vip/supervip)**

примеры автоприемщиков:
* joinRequest_BZPO_green
* joinRequest_BZ_UNION (одинаковый для всех BZ)

примеры других программ:
* databaseDump_Postgres
* databaseDump_Redis
* restartComputer_Windows


## Название docker image:
Совпадают с шаблонами/программами и конкретными решениями

пример: 

| Название репозитория       | Название docker image      |
| -------------------------- | -------------------------- |
| joinRequest_BZPO_green     | joinRequest_BZPO_green     |


## Название docker container:
Будет дополняться со временем

**Название шаблона заменяетя на аббревиатуру**
пример:

| Название docker image      | Название docker container       |
| -------------------------- | ------------------------------- |
| joinRequest_BZPO_green     | JR_BZPO_green                   |
| broadcast_tbot             | BC_BZOL_yellow_VIP              |
| broadcast_tbot             | BC_UNION (для ВСЕХ)             |
| broadcast_tbot             | BC_DT_FR_UNION (для всех DT FR) |
