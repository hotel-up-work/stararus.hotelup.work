# Гостьовий будинок «Стара Русь»

Live site: https://stararus.hotelup.work

## About
«Стара Русь» — гостьовий будинок (`guest_house`) у Кам’янці-Подільському, вул. Івана Франка, 6А. Сторінка продає SMALL STAY + RESTAURANT + MEETING SPACE за формулою STAY · DINE · MEET; сценарії PARK → STAY → DINE → REST і MEET → DINE → STAY. Назва надихає лише стиль (Alegreya, пергамент, подвійна рамка, ✦) — жодних тверджень про історичну будівлю, садибу чи Старе місто.

## Amenities (verified, list.json)
- Кондиціонування, безкоштовний Wi-Fi, безкоштовна приватна парковка, цілодобова рецепція
- Ресторан і бар (без кухні, меню, годин, коктейлів)
- Тераса (без видів і призначення)
- Конференц-зал (без місткості, обладнання, пакетів)
- Заїзд 14:00–23:30, виїзд 07:30–11:30; пізніше 23:30 — погодити телефоном

## Room count
10 номерів — Trip.com, `size_confidence: medium`. На сторінці лише «близько 10 номерів» (факти й Stay) з приміткою; не в hero і не в schema (`numberOfRooms` не додано). Підтвердити з власником.

## Not published
Приватна ванна, TV, кухня, сніданок, кухня ресторану, сімейні номери, тварини, SPA, басейн, трансфер, email, Instagram, рейтинг і відгуки (у list.json немає).

## Contact
- Phone: +380 96 364 40 92 — з муніципального переліку; Trip.com показував інший номер. Перед запуском зробити тестовий дзвінок.
- Website `https://stararus.business.site` не опубліковано: Google закрив Business Profile websites (*.business.site) у 2024 році, посилання, найімовірніше, не працює.
- Google Maps: `https://maps.google.com/?cid=6104310521932301133`

## Forms
Live HotelOS forms (`kp-stararus`, script before `</body>`): `stay-request` (section before the final CTA, also holds `#contacts`) and `conference-request` (right after `#meet`). They replace the earlier Telegram-endpoint forms.

## Photos
`photos_source: stock (Pexels, free license)` — ілюстративні фото (не самого закладу), додані до карток Stay/Dine/Meet у hero, секцій Stay, Dine (ресторан і бар), Outside (тераса) і Meet. Кожне зображення має alt з позначкою «ілюстративне фото». Файли — в `img/`. Hero лишається типографічним у подвійній рамці.
