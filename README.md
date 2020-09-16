# NeuroStartUp

![](logo.png)

*NeuroStartUp* — динамически развивающийся стартап, специализирующийся на поиске с использованием новейших технологий искусственного интеллекта.

## Начало работы:
Для работы нам потребуется GIT, который можно скачать по ссылкам ниже:
* **Windows**: https://git-scm.com/download/win
* **Mac**: https://git-scm.com/download/mac
* **Ubuntu**: `apt-get install git`
* **Fedora**: `dnf install git`
* **Другие версии Linux**: https://git-scm.com/download/linux 

Также для написания кода рекомендуем использовать редактор кода **VS Code** – https://code.visualstudio.com/download

### Настройка:
Git хранит историю в привязке к имени пользователя и email.
Чтобы задать имя пользователя и email необходимо выполнить
следующие команды:
```bash
git config --global user.name "Vasya Pupkin"
git config --global user.email vasya@localhost
```
### Редактор:
Git использует по умолчанию редактор **Vim** (он достаточно тяжёл для
начинающих пользователей).
Мы можем задать редактор попроще (**Nano**) с помощью команды:
```bash
git config --global core.editor nano
```