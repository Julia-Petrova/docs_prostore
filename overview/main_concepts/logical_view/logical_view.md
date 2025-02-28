﻿---
layout: default
title: Логическое представление
nav_order: 5
parent: Основные понятия
grand_parent: Обзор понятий, компонентов и связей
has_children: false
has_toc: false
---

# Логическое представление {#logical_view}

_Логическое представление_ — сохраненный запрос к данным одной или нескольких 
[логических таблиц](../logical_table/logical_table.md), который имеет имя и 
может использоваться как источник данных в других запросах. Примером логического представления 
является список контрагентов, объединенный с информацией о благонадежности контрагентов и их 
контактами.

Работа с логическими представлениями напоминает работу с реляционными представлениями. 
Логические представления можно [создавать](../../../working_with_system/logical_schema_update/create_view/create_view.md), 
[изменять](../../../working_with_system/logical_schema_update/alter_view/alter_view.md) и 
[удалять](../../../working_with_system/logical_schema_update/drop_view/drop_view.md). 
Данные логического представления можно [запрашивать](../../../working_with_system/data_reading/data_reading.md) 
и [выгружать](../../../working_with_system/data_download/data_download.md).

Логическое представление проецирует данные связанных логических таблиц и не отражается 
в [хранилище](../data_storage/data_storage.md). [Загрузка](../../../working_with_system/data_upload/data_upload.md) 
и [обновление](../../../working_with_system/data_update/data_update.md) данных недоступны для логических представлений.