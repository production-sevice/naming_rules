## Аббревиатуры:
Будет дополняться со временем

программы:
* JR - join request
* BC - broadcast
* PA - parser
* SC - script

цвета:
* WH - white
* BL - black
* RD - red
* GR - green
* BU - blue
* YE - yellow

типы каналов:
* FR - free
* VP - vip
* SV - super vip

команды:
* YT - youtube
* FB - facebook
* SO - soprano
* KZ - kz

площадки:
* PO - pocketoption
* IQ - 
* OL - olymptrade
* BI - binomo
* QX - quotex

специальные:
* UNION - объединение нескольких


## Название репозиториев модулей:
шаблон:
* ***название**
* ***примерНазвания**

примеры:
* logger
* sdb
* keitaroConversion


## Название репозиториев шаблонов/программ:
в эту группу входят репозитории:
* Программы по типу chat_join_request ботов, которые имеют базовый функционал подходходящий для каждого бота, котрый автоматически принимает в канал.

шаблон:
* ***название_тип**
* ***примерНазвания_тип**

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
* **шаблонКода_актер_цветканала_площадка_команда_тип(free/vip/supervip)**

примеры автоприемщиков:
* joinRequest_BZ_GR_PO_YT_FR
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
| joinRequest_BZ_GR_PO_YT_FR | joinRequest_BZ_GR_PO_YT_FR |


## Название docker container:
Будет дополняться со временем

**Название шаблона заменяетя на аббревиатуру**
пример:

| Название docker image      | Название docker container       |
| -------------------------- | ------------------------------- |
| joinRequest_BZ_GR_PO_YT_FR | JR_BZ_GR_PO_YT_FR               |
| broadcast_tbot             | BC_BZ_YE_OL_FB_VIP              |
| broadcast_tbot             | BC_UNION (для ВСЕХ)             |
| broadcast_tbot             | BC_DT_FR_UNION (для всех DT FR) |
