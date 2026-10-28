# VOLT landing

Vite + vanilla HTML/CSS/JS. GSAP и Lenis установлены, подключим на этапе анимаций.

    npm install
    npm run dev

## Масштаб
Весь макет считается в `--u = 100vw / 1440`, то есть 1u = 1px фрейма Figma. Размеры пишем как `calc(130 * var(--u))`.

## Плейсхолдеры (заменить экспортом из Figma под теми же именами)
public/icons/logo.svg, nav-about.svg, nav-speakers.svg, nav-agenda.svg, nav-workshops.svg, mode.svg, ticket-star.svg

## Временное
`.page { min-height: 9193u }` в base.css: чтобы был виден весь фон. Убрать, когда будут все блоки.
