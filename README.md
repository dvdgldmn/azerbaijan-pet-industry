# Azerbaijan Pet Industry — Open Market Research

Интерактивный дашборд по зоо-индустрии Азербайджана: ветклиники, зоомагазины, груминг-салоны, приюты, а также регуляторная среда.

## Live

**[Открыть дашборд →](https://dxripunov.github.io/azerbaijan-pet-industry/)**

## Данные

- **~270 POI** собрано через Google Places API (New) по 8 городам Азербайджана
- **105** ветклиник / **141** зоомагазин / **22** груминг-салона / **1** приют
- Интерактивная карта (Leaflet + CartoDB)
- Поиск по таблицам, сортировка по городу + алфавиту
- Регуляторика: Dövlət Baytarlıq Xidməti, закон "О ветеринарии" 2005, KURA

## Методология

Text Search через Google Places API с location bias по городам (Baku, Sumgait, Ganja, Mingachevir, Lankaran, Shaki, Nakhchivan, Quba) × 4 языковых варианта запроса. Дедупликация по place_id, классификация по приоритету vet > groom > shelter > pet.

## Ограничения

- ~10–15% зоомагазинов не зарегистрированы на Google Maps (районные точки, базары)
- Региональное покрытие хуже бакинского на 20–40%
- Приюты в основном работают через Instagram/Facebook — не попадают на Maps

## Обновление

Для повторного запуска нужен Google Cloud API key с enabled Places API (New).

---

_Research snapshot: 2026-04-22_
