# Инструкция по публикации в каталог Lumafly

Lumafly берёт моды из **GitHub-репозиториев**. Готовую папку с файлами можно найти здесь:
`Publish-ImprovedHollowKnight/ImprovedHollowKnight/`

## Что уже готово (лежит в папке)
- `ImprovedHollowKnight.dll` — собранный мод (в подпапке `ImprovedHollowKnight/`)
- `ImprovedHollowKnight.cs` + `.csproj` — исходники
- `README.md` — описание
- `LICENSE` — MIT
- `Lumafly.json` — метаданные для каталога

## Что нужно сделать тебе (мне нельзя — нужен твой GitHub-аккаунт)

1. **Создай GitHub-репозиторий** (публичный), например с именем `ImprovedHollowKnight`.
2. **Залей в него содержимое папки** `Publish-ImprovedHollowKnight/ImprovedHollowKnight/` (DLL в этой структуре — под `ImprovedHollowKnight/ImprovedHollowKnight.dll`).

   > ВАЖНО: чтобы Lumafly нашёл DLL, в корне репо должна быть ДОЛЖНА быть папка `ImprovedHollowKnight/ImprovedHollowKnight.dll`, рядом с `Lumafly.json`.

3. **Выпусти релиз** (Release) с тегом `1.0.0`, прикрепив к нему `ImprovedHollowKnight.dll`.
4. **Поправь `Lumafly.json`**: впиши свой ник в `"author"` и URL репозитория в `"repo"` вместо заглушек.

## Правила каталога (кратко)
- Репозиторий публичный.
- Есть `Lumafly.json` и `README.md`.
- DLL лежит в папке с именем мода.
- Зависимость `Modding API` указана.

После этого мод появится в поиске Lumafly у всех пользователей.
