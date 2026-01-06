# Shanling UA4 — PCM фильтры / PCM Filters (Guide / Руководство)
RU:
Это двуязычный README, описывающий доступные PCM‑фильтры в Shanling UA4 (чип ESS ES9069Q) — что они делают, как на это ориентироваться на слух и какие профили пробовать для разных целей.

EN: 
This bilingual README describes the PCM filters available on the Shanling UA4 (ESS ES9069Q) — what they do, how to compare them by ear, and which ones to try for different listening goals.

## Быстрая шпаргалка / Quick reference
RU:
- Linear phase fast roll-off — максимально нейтрально и аналитично. Подходит для детального прослушивания и студийной точности.
- Linear phase fast roll-off (low ripple) — чуть более «чистая» версия fast, разницу услышать сложно.
- Linear phase slow roll-off — мягче на ВЧ, комфортнее долгие сессии.
- Linear phase apodizing fast roll-off — устраняет артефакты/pre-ringing в записях; полезно для старых/обработанных треков.
- Minimum phase fast roll-off — натуральнее атака, меньше пре‑рингинга; хорош баланс между музыкой и подробностью.
- Minimum phase slow roll-off — тёплее и мягче, приятнее на ярких наушниках.
- Minimum phase slow roll-off low dispersion — максимально «комфортный», оптимизация дисперсии; для долгого прослушивания.

EN:
- Linear phase fast roll-off — most neutral and analytical; good for detailed and studio‑like listening.
- Linear phase fast roll-off (low ripple) — cleaner variant of fast; differences subtle.
- Linear phase slow roll-off — gentler highs, more comfortable for long sessions.
- Linear phase apodizing fast roll-off — reduces recording artifacts/pre‑ringing; useful for older/processed tracks.
- Minimum phase fast roll-off — more natural attack, less pre‑ring; a balanced musical choice.
- Minimum phase slow roll-off — warmer and softer; suits bright headphones.
- Minimum phase slow roll-off low dispersion — very comfortable; optimized to reduce dispersion artifacts.

## Подробно по профилям / Profiles explained

Каждый профиль влияет на:
- фазовые характеристики (linear vs minimum),
- скоростью спада вне полосы (fast vs slow roll-off),
- дополнительные параметры (apodizing, low ripple, low dispersion).

RU:
1. Linear phase — линейная фаза: нейтральность в относительном времени; сохраняет фазу на всём диапазоне. Часто даёт пред‑звон (pre‑ring).
2. Minimum phase — минимальная фаза: переносит артефакты после импульса (post‑ring), меньше пред‑звука — субъективно «натуральнее».
3. Fast roll‑off — резкий спад: чёткая граница частот, выше — быстро подавляется; может давать более «ясную» ВЧ подачу.
4. Slow roll‑off — плавный спад: мягче на ВЧ, ощущается как «более тёплый» звук.
5. Apodizing — аподизация: фильтр, уменьшающий пред‑звон и некоторые артефакты записи.
6. Low ripple — уменьшение пульсаций в полосе пропускания — теоретически повышает ровность амплитудной характеристики.
7. Low dispersion — уменьшение дисперсии (фазовых смещений по частоте) — направлено на комфорт и согласованность спектра.

EN:
1. Linear phase — keeps phase linear across the band: very neutral timing; may produce pre‑ring.
2. Minimum phase — moves ringing after the impulse (post‑ring), reduces pre‑ring — subjectively more natural.
3. Fast roll‑off — sharp cutoff: clearer high‑end but aggressive out‑of‑band attenuation.
4. Slow roll‑off — gentle cutoff: softer highs, warmer sound.
5. Apodizing — reduces pre‑ring and some recording artifacts.
6. Low ripple — reduces passband ripple for slightly cleaner response.
7. Low dispersion — reduces frequency‑dependent phase dispersion for comfort.

## Как тестировать — план прослушивания / How to test — listening plan
RU:
1. Подготовка:
   - Выберите пару треков: один с сильной атакой (ударные, бас), один с натуральным вокалом/акустикой и один с обилием ВЧ/перкуссии.
   - Используйте ваши наушники/усилитель, на которых вы обычно слушаете.
2. Метод:
   - Начните с Linear phase fast roll‑off как эталона.
   - Сравнивайте по переключениям: переключить профиль — прослушать 30–60 секунд одной фразы — обратно — переключить — слушать.
   - Обращайте внимание на: атака, «телесность» баса, разборчивость микродеталей, утомляемость ВЧ, ощущение «воздуха».
3. Что искать:
   - Pre‑ring: кажется ли, что звук «появляется» до удара?
   - Атака инструментов: более «ударная» или «смазанная»?
   - Комфорт: утомляют ли верхние частоты?
   - Пространство и слои: лучше ли разделены инструменты?

EN:
1. Preparation:
   - Choose tracks: (1) fast attack (drums/bass), (2) natural vocals/acoustic, (3) bright/percussive material.
   - Use your normal headphones/amp.
2. Method:
   - Start with Linear phase fast roll‑off as a reference.
   - A/B by switching filter: listen ~30–60s each time to the same passage.
   - Note: attack, bass weight, microdetail, treble fatigue, sense of “air”.
3. What to listen for:
   - Pre‑ring: does sound seem to appear before the transient?
   - Instrument attack: punchy or smeared?
   - Comfort: are highs fatiguing?
   - Imaging and separation: are instruments layered clearly?

## Рекомендации / Recommendations
RU:
- Для студийной проверки и максимальной нейтральности: Linear phase fast roll‑off (или low ripple).
- Для повседневного приятного прослушивания и «музыкальности»: Minimum phase fast roll‑off.
- Если на наушниках верх слишком яркий: Minimum phase slow roll‑off или Linear phase slow roll‑off.
- Для старых/обработанных записей с артефактами попробуйте Apodizing.
- Точность vs комфорт: линейная фаза = точность, минимальная фаза = комфорт/натуральность.

EN:
- For studio/neutral listening: Linear phase fast roll‑off (or low ripple).
- For everyday musical listening: Minimum phase fast roll‑off.
- If your headphones are bright: try Minimum phase slow roll‑off or Linear phase slow roll‑off.
- For older/processed recordings with artifacts: Apodizing.
- Accuracy vs comfort: linear = accuracy, minimum = musical/comfortable.
