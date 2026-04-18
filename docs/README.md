# Documentation Overview

## Project
Онлайн-платформа для навчання — інформаційна система для організації дистанційного освітнього процесу, керування курсами, навчальними матеріалами, тестуванням та результатами студентів.

## Documentation as Code
Ця документація реалізована за підходом Documentation as Code. Усі документи зберігаються в репозиторії у форматі Markdown, мають контроль версій і можуть бути автоматично згенеровані у вигляді статичного сайту.

## Navigation

### Architecture
- [SSD — System Specification Document](architecture/SSD.md)
- [SDD — Software Design Document](architecture/SDD.md)
- [ISD — Infrastructure Specification Document](architecture/ISD.md)

### Quality
- [Test Strategy](quality/test-strategy.md)
- [Traceability Matrix](quality/traceability-matrix.md)

### Developer
- [Onboarding](developer/onboarding.md)

## Single Source of Truth
- Усі функціональні та нефункціональні вимоги зберігаються тільки в `architecture/SSD.md`.
- Усі архітектурні рішення зберігаються тільки в `architecture/SDD.md`.
- Усі інфраструктурні рішення зберігаються тільки в `architecture/ISD.md`.
- Підхід до тестування зберігається в `quality/test-strategy.md`.
- Простежуваність між вимогами та тестами зберігається в `quality/traceability-matrix.md`.

## Documentation Update Rules
1. Якщо змінюються вимоги, спочатку оновлюється `SSD.md`.
2. Якщо змінюється архітектура, оновлюється `SDD.md`.
3. Якщо змінюється інфраструктура або розгортання, оновлюється `ISD.md`.
4. Якщо змінюються тести або вимоги, оновлюється `traceability-matrix.md`.
5. Усі зміни документації мають фіксуватися в репозиторії.

## Versioning
- Версія документації `v1.0` відповідає першій стабільній версії системи.
- Незначні зміни документації позначаються як `v1.1`, `v1.2`.
- Значні зміни вимог, архітектури або API оформлюються як нова основна версія, наприклад `v2.0`.
