# Tap Dragons — config

Игра при запуске (если есть интернет) читает `version.json` и сравнивает со своим кодом версии.
Если код версии игры меньше числа — показывает окно «Обновите игру».

- `gp_min_version_code` — для Google Play (`com.tap.rpg.dragon.fantasy`)
- `rustore_min_version_code` — для RuStore (`com.DefaultCompany.TapDragons`)

Поднимать число только после того, как новая версия **уже вышла** в этом магазине.
Без интернета игра запускается как обычно.
