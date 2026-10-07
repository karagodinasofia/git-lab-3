## Варіант
Журнал №8, Варіант 8, Карагодіна

## 1. stash list
stash@{0}: On lab3/variant-8-Karagodina: чернетка пошти v8

## 2. cherry-pick
Хеші 0d9aa1a (feature/pick-8) та ed9d044 (lab3/variant-8-Karagodina).
Хеші різні, тому що cherry-pick створює новий об'єкт коміту з іншим батьківським комітом і часом створення.

## 3. reflog
f846503 HEAD@{0}: commit (amend): Уточнити пошту групи, варіант 8
ed9d044 HEAD@{1}: cherry-pick: Замінити пошту групи

## 4. revert
76f83b2 (tag: v0.1-Karagodina, recover/v8) Revert "Зіпсувати рядок"
87ae0b6 Зіпсувати рядок

## 5. тег
tag v0.1-Karagodina
Tagger: Sofia Karagodina <karagodinasofia6@gmail.com>
Date:   Wed Oct 7 09:40:49 2026 +0300

Перший зріз варіанта 8

## 6. rebase -i
Використано pick для першого коміту (8706835) та squash для другого (f76e7e7). Підсумкове повідомлення: Замінити пошту групи.

## 7. blame
^53becd5 (Sofia Karagodina 2026-10-07 09:07:58 +0300 1) # CONTACT

## 8. fork
origin — це мій особистий форк репозиторію, а upstream — це оригінальний репозиторій проєкту.
Для отримання оновлень виконується fetch з upstream, збереження своїх змін і push робиться в origin.
Фінальна здача роботи здійснюється шляхом створення Pull Request із моєї гілки в origin у гілку upstream/main.