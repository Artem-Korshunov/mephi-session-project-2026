# MEPHI Session Project 2026

Student number: 265875
Operating system: RED OS 8.0.3 Standard Server Minimal

## Проверки

- ping.out — проверка сетевой связности.
- dnf.out — история транзакций DNF.
- journalctl.out — журнал nginx за текущую загрузку.
- getcap.out — capabilities tcpdump.
- getenforce.out — режим SELinux.
- stat.out — права доступа, ACL и контексты SELinux.
- curl.out — ответ веб-сервера.
- mephi-screenshot.png — визуальное подтверждение результата.

## Конфигурация

- fstab — автоматическое монтирование MEPHI_WEB.
- passwd и group — учётные записи и группы.
- shadow — копия с замаскированными полями паролей.
- pwquality.conf и login.defs — политика паролей.
- login и console-deny — ограничение локального входа кураторов.
- system-auth и password-auth — настройки PAM.
- nginx.conf — конфигурация веб-сервера.

Настройки проверены после перезагрузки системы.
