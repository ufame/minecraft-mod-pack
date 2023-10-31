# Minecraft сборка
## Для сильных пухом

- Версия minecraft: `1.20.1`
- Загрузчик модов: `Forge`
- Всего модов (включая библиотеки): `66`

## Путеводитель

- [API и билиотеки](#api-и-библиотеки)
  - *Количество модов*: `15`
- [Визуал](#визуал)
  - *Количество модов*: `1`
- [Индустриальные моды](#индустриальные-моды)
  - *Количество модов*: `5`
- [RPG](#rpg)
  - *Количество модов*: `9`
- [Биомы](#биомы)
  - *Количество модов*: `5`
- [Моды](#мобы)
  - *Количество модов*: `9`
- [Инструменты](#инструменты)
  - *Количество модов*: `3`
- [Вспомогательные моды](#вспомогательные-моды)
  - *Количество модов*: `14`

#### API и библиотеки

1. [Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config)
    - *Файл в директории*: `cloth-config-12.0.109-forge-1.20.1.jar`
    - *Описание*: Библиотека, позволяющая другим майнкрафт модам использовать API для работы с интерфейсом настроек.
    - *Нужен для*:
      - [YUNG's Better Strongholds](#yungs-better-strongholds)
      - [YUNG's Better Mineshafts](#yungs-better-mineshafts)
      - [YUNG's Better Ocean Monuments](yungs-better-ocean-monuments)

2. [YUNG's API](https://www.curseforge.com/minecraft/mc-mods/yungs-api)
    - *Файл в директории*: `YungsApi-1.20-Forge-4.0.2.jar`
    - *Описание*: Данная модификация — это библиотека, нужная для работы модов от авторы YUNG. Сама по себе она ничего не добавляет, но без неё связанные  модификации работать не будут.
    - *Нужен для*:
      - [YUNG's Better Strongholds](#yungs-better-strongholds)
      - [YUNG's Better Mineshafts](#yungs-better-mineshafts)
      - [YUNG's Better Ocean Monuments](yungs-better-ocean-monuments)

3. [Sophisticated Core](https://www.curseforge.com/minecraft/mc-mods/sophisticated-core)
    - *Файл в директории*: `sophisticatedcore-1.20.1-0.5.100.457.jar`
    - *Описание*: Техническая модификация от автора P3pp3rF1y, он использует этот мод для упрощения и ускорения разработки собственных модов.
    - *Нужен для*:
      - [Sophisticated Backpacks](#sophisticated-backpacks)

4. [TerraBlender](https://www.curseforge.com/minecraft/mc-mods/terrablender)
    - *Файл в директории*: `TerraBlender-forge-1.20.1-3.0.0.169.jar`
    - *Описание*: Библиотечный мод для простого и совместимого добавления биомов с новой системой биомов/террейнов Minecraft.
    - *Нужен для*: 
      - [Biomes O' Plenty](#biomes-o-plenty)

5. [GeckoLib](https://www.curseforge.com/minecraft/mc-mods/geckolib)
    - *Файл в директории*: `geckolib-forge-1.20.1-4.2.4.jar`
    - *Описание*: Движок прямой кинематики для Minecraft, он позволяет переносить анимации в игру и использовать их в автоматическом режиме. С помощью GeckoLib можно экспортировать анимации из Blockbench и применять их к объектам в игровом мире
    - *Нужен для*:
      - [Creeper Overhaul](#creeper-overhaul)

6. [Resourceful Config](https://www.curseforge.com/minecraft/mc-mods/resourceful-config)
    - *Файл в директории*: `resourcefulconfig-forge-1.20.1-2.1.0.jar`
    - *Описание*: Технический мод созданный ThatGravyBoat, разработчики модов могут использовать его для ускорения и упрощения работы с настройками своих модов, за счет удобного меню с настройками.
    - *Нужен для*: 
      - [Creeper Overhaul](#creeper-overhaul)
      - [Enderman Overhaul](#enderman-overhaul)
    - *Связанные*:
      - [Resourceful Lib](#resourceful-lib)

7. [Resourceful Lib](https://www.curseforge.com/minecraft/mc-mods/resourceful-config)
    - *Файл в директории*: `resourcefullib-forge-1.20.1-2.1.11.jar`
    - *Описание*: Библиотека для моддинга, содержащая ценные утилиты и API, разработанные Team Resourceful.
    - *Нужен для*: 
      - [Creeper Overhaul](#creeper-overhaul)
      - [Enderman Overhaul](#enderman-overhaul)
    - *Связанные*:
      - [Resourceful Lib](#resourceful-lib)

8. [Kotlin for Forge](https://www.curseforge.com/minecraft/mc-mods/kotlin-for-forge)
    - *Файл в директории*: `kotlinforforge-4.5.0-all.jar`
    - *Описание*: Используется для создания модов на языке программирования Kotlin.
    - *Нужен для*:
      - [Inventory Profiles Next](#inventory-profiles-next)

9. [libIPN](https://www.curseforge.com/minecraft/mc-mods/libipn)
    - *Файл в директории*: `libIPN-forge-1.20.2-4.0.0.jar`
    - *Описание*: Он содержит обработку графического интерфейса и конфигурации.
    - *Нужен для*: 
      - [Inventory Profiles Next](#inventory-profiles-next)

10. [Library Ferret](https://www.curseforge.com/minecraft/mc-mods/library-ferret-forge)
    - *Файл в директории*: `libraryferret-forge-1.20.1-4.0.0.jar`
    - *Описание*: Этот мод является библиотечным модом и содержит общий код для некоторых модов.
    - *Нужен для*: 
      - [Better Villages](#better-villages)

11. [BlockUI](https://www.curseforge.com/minecraft/mc-mods/blockui)
    - *Файл в директории*: `blockui-1.20.1-0.0.98-ALPHA.jar`
    - *Описание*: Система управления пользовательским интерфейсом Minecraft на основе XML.
    - *Нужен для*: 
      - [Multi-Piston](#multi-piston)
      - [Structurize](#structurize)
      - [MineColonies](#minecolonies)

12. [Citadel](https://www.curseforge.com/minecraft/mc-mods/citadel)
    - *Файл в директории*: `citadel-2.4.7-1.20.1.jar`
    - *Описание*: Мод библиотеки, необходимый для расширенной анимации и свойств объектов в версии 1.14 и более поздних версиях.
    - *Нужен для*: 
      - [L_Ender 's Cataclysm](#l_ender-s-cataclysm)
      - [Alex's Mobs](#alexs-mobs)

13. [Bookshelf](https://www.curseforge.com/minecraft/mc-mods/bookshelf)
    - *Файл в директории*: `citadel-2.4.7-1.20.1.jar`
    - *Описание*: Набор кода, фреймворков, утилит и других ресурсов.
    - *Нужен для*:
      - [Enchantment Descriptions](#enchantment-descriptions)

14. [Cristel Lib](https://www.curseforge.com/minecraft/mc-mods/cristel-lib)
    - *Файл в директории*: `cristellib-1.1.3-forge-1.20.1.jar`
    - *Описание*: Позволяет создавать конфиги для структур с кодом или данными.
    - *Нужен для*:
      - [Towns and Towers](#towns-and-towers)

15. [Structure Gel API](https://www.curseforge.com/minecraft/mc-mods/structure-gel-api)
    - *Файл в директории*: `structure_gel-1.20.1-2.15.0.jar`
    - *Описание*: API, призванный упростить разработчикам создание структур, особенно тех, которые используют систему головоломки.
    - *Нужен для*:
      - [Towns and Towers](#towns-and-towers)

#### Визуал

1. [Domum Ornamentum](https://www.curseforge.com/minecraft/mc-mods/domum-ornamentum)
    - *Файл в директории*:
    - *Описание*: Предоставляет блоки со скинами, которые можно использовать в зданиях внутри игры Minecraft.
    - *Нужен для*: 
      - [MineColonies](#minecolonies)

#### Индустриальные моды

1. [Create](https://www.curseforge.com/minecraft/mc-mods/create)
    - *Файл в директории*: `create-1.20.1-0.5.1.e-forge.jar`
    - *Описание*: Предлагает множество инструментов и блоков для создания и декорации построек, а так же автоматизации. Новые элементы дадут игроку на выбор больше вариантов дизайна, обработка предметов будет происходить не в одном блоке, для этого потребуется много "акторов", работающих вместе.
    - *Связанные моды*:
      - [Create Stuff & Additions](#create-stuff-additions)
      - [Create: Steam 'n' Rails](#create-steam-n-rails)

2. [Create Stuff & Additions](https://www.curseforge.com/minecraft/mc-mods/create-stuff-additions)
    - *Файл в директории*: `create-stuff-additions1.20.1_v2.0.4a.jar`
    - *Описание*: Аддон к моду Create, который предлагает набор инструментов, экипировки и различных гаджетов! С новой бронёй вы сможете увеличить свои физические способности, получите новые способы передвижения, даже полёт, а особые гаджеты позволят вам перемещать блоки или быстро перемещаться на крюке.
    - *Нужно для работы*:
      - [Create](#create)

3. [Create: Steam 'n' Rails](https://www.curseforge.com/minecraft/mc-mods/create-steam-n-rails)
    - *Файл в директории*: `Steam_Rails-1.5.2+forge-mc1.20.1.jar`
    - *Описание*: Все за мод, посвященный расширению возможностей железнодорожной системы Create. Мы превращаем базовую логистическую систему в обширную и эстетичную интеграцию железных дорог.
    - *Нужно для работы*:
      - [Create](#create)

4. [Create Crafts & Additions](https://www.curseforge.com/minecraft/mc-mods/createaddition) 
    - *Файл в директории*: `createaddition-1.20.1-1.1.1.jar`
    - *Описание*: Расширяет Create и действует как мост между электричеством и кинетической энергией Create, добавляя электродвигатель, который генерирует кинетическую энергию из энергии кузницы, и генератор переменного тока, который делает противоположное с КПД 75%. Для изготовления этих предметов вам нужно сделать прокатный стан — кинетическую машину, используемую для изготовления стержней и проволоки. 
    - *Нужно для работы*:
      - [Create](#create)

5. [Create Jetpack](https://www.curseforge.com/minecraft/mc-mods/create-jetpack)
    - *Файл в директории*: `create_jetpack-forge-4.1.1.jar`
    - *Описание*: Используя латунь, вы можете превратить свой медный бак в реактивный ранец, используя сжатый воздух внутри, чтобы двигаться по воздуху.
    - *Нужно для работы*:
      - [Create](#create)
      - [Kotlin for Forge](#kotlin-for-forge)

#### RPG

1. [The Twilight Forest](https://www.curseforge.com/minecraft/mc-mods/the-twilight-forest)
    - *Файл в директории*: `twilightforest-1.20.1-4.3.1860-universal.jar`
    - *Описание*: «Представьте, что вы проходите через портал в сумеречное царство, наполненное деревьями, насколько хватает глаз. За каждым углом вас ждут захватывающие дух виды и удивительные открытия. Но будьте осторожны! Не все обитатели леса реагируют на ваше вторжение легкомысленно». Это мод исследования измерений, ориентированный на приключения, который отправит вас в путешествие, где вы встретите странных существ, исследуете подземелья и многое другое.

2. [Better Villages](https://www.curseforge.com/minecraft/mc-mods/better-village-forge)
    - *Файл в директории*: `bettervillage-forge-1.20.1-3.2.0.jar`
    - *Описание*: Этот мод улучшает деревни в Minecraft, улучшая существующую структуру, делая их более живыми и привлекательными для исследования.
    - *Нужно для работы*:
      - [Library Ferret](#library-ferret)

3. [MineColonies](https://www.curseforge.com/minecraft/mc-mods/minecolonies)
    - *Файл в директории*: `minecolonies-1.20.1-1.1.240-RELEASE.jar`
    - *Описание*: Интерактивный строительный мод, который позволяет вам создать свой собственный процветающий город в Minecraft. Он позволит вам развить свои лидерские качества, предоставив вам все необходимое для построения своего королевства. MineColonies дает вам возможность создать колонию, столь же уникальную, как и каждый игрок. Имея так много возможностей, вы каждый раз будете создавать новую колонию, адаптироваться к любому биому, строить внутри горы, на ее вершине, под океаном или в небе.
    - *Нужно для работы*:
      - [BlockUI](#blockui)
      - [Domum Ornamentum](#domum-ornamentum)
      - [Multi-Piston](#multi-piston)
      - [Structurize](#structurize)

4. [L_Ender 's Cataclysm](https://www.curseforge.com/minecraft/mc-mods/l_ender-s-cataclysm)
    - *Файл в директории*: `L_Enders_Cataclysm-1.39+-1.20.1.jar`
    - *Описание*: Добавляет сложные подземелья, сложные бои с боссами и мощные предметы.
    - *Нужно для работы*: 
      - [Citadel](#citadel)

5. [Towns and Towers](https://www.curseforge.com/minecraft/mc-mods/towns-and-towers)
    - *Файл в директории*: `Towns-and-Towers-1.11.1-Fabric+Forge.jar`
    - *Описание*: Добавление новых деревень, аванпостов грабителей и даже совершенно новых кораблей. Сами структуры немного более детализированы, чем их ванильные аналоги, но они по-прежнему органично вписываются в мир.

6. [Stalwart Dungeons](https://www.curseforge.com/minecraft/mc-mods/stalwart-dungeons)
    - *Файл в директории*: `stalwart-dungeons-1.20.1-1.2.8.jar`
    - *Описание*: Добавляет в нижнюю часть два новых подземелья: «Ужасное подземелье» (появляется в биомах «Долина песка душ» и «Искаженный лес») и «Хранительский замок» (появляется в биомах «Пустоши Пустоты» и «Багровый лес»). Он также добавляет подземелье в Крае (появляется в биомах Пустоты и Мидлендса).

7. [Towers of the Wild Modded](https://www.curseforge.com/minecraft/mc-mods/towers-of-the-wild-modded)
    - *Файл в директории*: `totw_modded-1.0.2-1.20.1.jar`
    - *Описание*: Этот мод добавляет особый тип конструкции — высокие башни, вдохновленные Towers of the Wild.
      Наверху этих башен есть путевой камень и сундук. Вы всегда найдете параплан в сундуке поверх другой добычи. Путевые камни используются в качестве маяка для перемещения между землями для модпаков, которые могут захотеть отключить полет надкрылий или что-то еще.

8. [Blue Skies](https://www.curseforge.com/minecraft/mc-mods/blue-skies)
    - *Файл в директории*: `blue_skies-1.20.1-1.3.29.jar`
    - *Описание*: Мод на выживание, который добавляет такие аспекты, как измерения, подземелья и многое другое в светлом и темном сценарии.
    - *Нужно для работы*:
      - [Structure Gel API](#structure-gel-api)

9. [Useless Sword](https://www.curseforge.com/minecraft/mc-mods/useless-sword)
    - *Файл в директории*: `less-sword-furtos-edition-1.20.1-1.0.1.jar`
    - *Описание*: Добавляет 76 новых мечей

#### Биомы

1. [YUNG's Better Strongholds](https://www.curseforge.com/minecraft/mc-mods/yungs-better-strongholds)
    - *Файл в директории*: `YungsBetterStrongholds-1.20-Forge-4.0.3.jar`
    - *Описание*: Полностью переработает ванильные крепости в майнкрафт, теперь в их генерацию будут включены пятнадцать уникальных комнат, различные типы туннелей и коридоров, лестницы, ловушки и даже особые скрытые области.
    - *Нужно для работы*:
      - [Cloth Config API](#cloth-config-api)
      - [YUNG's API](#yungs-api)

2. [YUNG's Better Mineshafts](https://www.curseforge.com/minecraft/mc-mods/yungs-better-mineshafts-forge)
    - *Файл в директории*: `YungsBetterMineshafts-1.20-Forge-4.0.4.jar`
    - *Описание*: Мод полностью переосмыслит генерацию ванильных шахт, превращая их из скучных линейных построек в динамичные сети туннелей со спрятанным лутом. У шахт появится девять биомов и начнут генерироваться дополнительные структуры.
    - *Нужно для работы*:
      - [Cloth Config API](#cloth-config-api)
      - [YUNG's API](#yungs-api)

3. [YUNG's Better Ocean Monuments](https://www.curseforge.com/minecraft/mc-mods/yungs-better-ocean-monuments)
    - *Файл в директории*: `YungsBetterOceanMonuments-1.20-Forge-3.0.3.jar`
    - *Описание*: Коренным образом меняет дизайн океанских памятников, делая их более привлекательными и полезными. Лучшие памятники намного больше, чем их ванильные аналоги, и имеют полностью рандомизированное расположение. За свои неприятности вы найдете гораздо лучшую добычу, включая трезубцы и сердце моря!
    - *Нужно для работы*:
      - [Cloth Config API](#cloth-config-api)
      - [YUNG's API](#yungs-api)

4. [Biomes O' Plenty](https://www.curseforge.com/minecraft/mc-mods/biomes-o-plenty)
    - *Файл в директории*: `BiomesOPlenty-1.20.1-18.0.0.598.jar`
    - *Описание*: Обширный мод биомов для Minecraft, который добавляет множество новых, уникальных биомов в Верхний мир и Пустоту! Вместе с новыми биомами в него добавляются новые растения, цветы, деревья, строительные блоки и многое другое!
    - *Нужно для работы*:
      - [TerraBlender](#terrablender)

5. [Tectonic](https://www.curseforge.com/minecraft/mc-mods/tectonic)
    - *Файл в директории*: `tectonic-mod-mc1.20-v2.0.1.jar`
    - *Описание*: Крупная модификация, которая значительно перерабатывает генерацию верхнего мира игры. Здесь вы увидите высокие горные хребты, подземные реки, тянущиеся вперёд на тысячи блоков и интересные ландшафты, делающие исследование мира в разы интереснее, без добавления каких-либо новых блоков.

#### Мобы

1. [Creeper Overhaul](https://www.curseforge.com/minecraft/mc-mods/creeper-overhaul)
    - *Файл в директории*: `creeperoverhaul-3.0.1-forge-1.20.1.jar`
    - *Описание*: Вводит в игровой мир разнообразные варианты криперов с красивыми текстурами и моделями. Теперь кроме стандартного, в игре появятся криперы из разных биомов, пещерные и даже дружелюбные криперы, которые не будут взрывать вас, если конечно вы не нападете сами. 
    - *Нужно для работы*: 
      - [GeckoLib](#geckolib)
      - [Resourceful Config](#resourceful-config)
      - [Resourceful Lib](#resourceful-lib)

2. [Enderman Overhaul](https://legacy.curseforge.com/minecraft/mc-mods/enderman-overhaul)
    - *Файл в директории*: `endermanoverhaul-forge-1.20.1-1.0.0.jar`
    - *Описание*: Вводит более двадцати вариантов странников Края, каждого со своими звуками, моделями и анимациями. Помимо самих странников Края, в игре также появятся различные жемчужины Края, у каждой из которых будут свои уникальные особенности, такие как заморозка ближайших врагов при попадании или увеличение силы атаки после перемещения.
    - *Нужно для работы*:
      - [GeckoLib](#geckolib)
      - [Resourceful Config](#resourceful-config)
      - [Resourceful Lib](#resourceful-lib)

3. [Alex's Mobs](https://www.curseforge.com/minecraft/mc-mods/alexs-mobs)
    - *Файл в директории*: `alexsmobs-1.22.6.jar`
    - *Описание*: Добавляет в Minecraft 89 новых мобов. Все эти мобы делятся на две категории: большинство из них — существа из реального мира, такие как медведи гризли, дорожные бегуны, косатки и т. д.; но некоторые из них являются чисто вымышленными, например, Эндергейд и Костяной Змей. Все эти существа выполняют необходимую цель и имеют уникальные предметы, механику или функции, поскольку чисто эстетических существ не существует. Тем не менее, они также помогают сделать некоторые среды в игре более живыми. Модели, текстуры, анимация и искусственный интеллект стилистически совместимы с последними дополнениями ванильной игры.
    - *Нужно для работы*:
      - [Citadel](#citadel)

4. [Dragon Mounts: Legacy](https://www.curseforge.com/minecraft/mc-mods/dragon-mounts-legacy)
    - *Файл в директории*: `dragonmounts-1.20.1-1.1.5.b3.jar`
    - *Описание*: позволяет вам разводить яйца драконов и превращать их в драконов, на которых можно ездить.

5. [Capybara](https://www.curseforge.com/minecraft/mc-mods/capybara-forge)
    - *Файл в директории*: `capybaramod-1.0.0.jar`
    - *Описание*: Существо из джунглей - «Капибара»! Вы можете приручить их с помощью сахарного тростника и разводить с помощью яблок! Однако они появляются только в джунглях и встречаются крайне редко.

6. [More Dragon Eggs](https://www.curseforge.com/minecraft/mc-mods/more-dragon-eggs)
    - *Файл в директории*: `moredragoneggs-4.0.jar`
    - *Описание*: Порождает новое яйцо дракона каждый раз, когда дракона убивают, а не только в первый раз.

7. [AttributeFix](https://www.curseforge.com/minecraft/mc-mods/attributefix)
    - *Файл в директории*: `AttributeFix-Forge-1.20.1-21.0.2.jar`
    - *Описание*: Minecraft использует систему атрибутов для выполнения важных вычислений. Он охватывает все: от значений брони до урона от атаки и максимального здоровья моба. В этой системе также введены ограничения атрибутов, которые ограничивают максимальное значение любого значения. Хотя обычно это остается незамеченным, на многие моды это влияет неосознанно. Этот мод значительно увеличивает эти ограничения, чтобы эти моды могли работать так, как они были задуманы.

8. [AI Improvements](https://www.curseforge.com/minecraft/mc-mods/ai-improvements)
    - *Файл в директории*: `AI-Improvements-1.20-0.5.2.jar`
    - *Описание*: Упрощенный мод модификации ИИ, ориентированный на производительность и низкоуровневые модификации ИИ в игре. Устранение недостатков базовой игры и улучшение ее для модифицированной экосистемы. Решение распространенных проблем, таких как слишком большое количество животных, снижение производительности из-за скоплений зомби и простые задачи по удалению, которые пропускаются более крупными модами улучшения ИИ.

9. [Aquaculture 2](https://www.curseforge.com/minecraft/mc-mods/aquaculture)
    - *Файл в директории*: `Aquaculture-1.20.1-2.5.0.jar`
    - *Описание*: Hасширяет систему рыбной ловли в Minecraft, добавляя более 30 новых рыб, которых можно ловить либо удочкой (подойдет любая модифицированная или ванильная удочка!), либо найденной плавающей в дикой природе. Также добавлена ​​серия новых удилищ, которые позволяют оснастить крючками и наживкой дополнительную функциональность. Также доступны индивидуальные лески и поплавки, которые сделают вашу удочку по-настоящему уникальной. Модификаторы и элементы настройки можно использовать в ящике для снастей, который также позволяет хранить дополнительные крючки, наживку, леску и поплавки. В каждом типе биома, даже в модифицированных биомах, есть новые виды рыб, которые украсят ваш опыт рыбалки и ваш мир рыбными мобами, плавающими в реках, прудах и океане! Пойманную рыбу можно превратить в рыбное филе, количество рыбного филе будет зависеть от рыбы (или веса, если опция в конфигурации включена). Кроме того, во время рыбалки вы можете получить новую блестящую добычу! 

#### Инструменты

1. [Nature's Compass](https://www.curseforge.com/minecraft/mc-mods/natures-compass)
    - *Файл в директории*: `NaturesCompass-1.20.1-1.11.2-forge.jar`
    - *Описание*: Это служебный предмет, позволяющий искать местоположение биома в любой точке мира и просматривать информацию о нем.

2. [Multi-Piston](https://www.curseforge.com/minecraft/mc-mods/multi-piston)
    - *Файл в директории*: `multipiston-1.20-1.2.31-ALPHA.jar`
    - *Описание*: Добавляет в игру многопоршневой блок, который позволяет вам втягивать любой блок в определенном направлении и выплевывать его в любом направлении с определяемой скоростью и дальностью, а также настраиваемым максимальным диапазоном в файле конфигурации.
    - *Нужно для работы*: 
      - [BlockUI](#blockui)
      - [Structurize](#structurize)
    - *Нужен для*: 
      - [MineColonies](#minecolonies)

3. [Structurize](https://www.curseforge.com/minecraft/mc-mods/structurize)
    - *Файл в директории*: `structurize-1.20.1-1.0.659-BETA.jar`
    - *Описание*: Его цель — предоставить новый способ редактирования больших частей мира Minecraft.
    - *Нужно для работы*: 
      - [BlockUI](#blockui)
      - [Domum Ornamentum](#domum-ornamentum)
    - *Нужен для*: 
      - [MineColonies](#minecolonies)

#### Вспомогательные моды

1. [Just Enough Items (JEI)](https://www.curseforge.com/minecraft/mc-mods/jei)
    - *Файл в директории*: `jei-1.20.1-forge-15.2.0.27.jar`
    - *Описание*: С его помощью вы сможете получить игровые предметы и посмотреть рецепты предметов и блоков из майнкрафт.

2. [Xaero's Minimap](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap)
    - *Файл в директории*: `Xaeros_Minimap_23.8.4_Forge_1.20.jar`
    - *Описание*: Миникарта с множеством настроек

3. [Xaero's World Map](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map)
    - *Файл в директории*: `XaerosWorldMap_1.36.0_Forge_1.20.jar`
    - *Описание*: Полноэкранная карта на клавишу `M`

4. [Mouse Tweaks](https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks)
    - *Файл в директории*: `MouseTweaks-forge-mc1.20-2.25.jar`
    - *Описание*: Теперь зажав правую кнопку мыши на стеке в инвентаре, можно быстро разобрать его на блоки, а зажав левую кнопку быстро собрать блоки в стек.

5. [AppleSkin](https://www.curseforge.com/minecraft/mc-mods/appleskin)
    - *Файл в директории*: `appleskin-forge-mc1.20.1-2.5.1.jar`
    - *Описание*: Модификация добавит твики, которые покажут насколько насытит вас та или иная еда и визуализируют насыщение в интерфейсе голода.

6. [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps)
    - *Файл в директории*: `Clumps-forge-1.20.1-12.0.0.3.jar`
    - *Описание*: Неплохая модификация, с которой сферы опыта будут собираться в одну большую единицу. Это позволит уменьшить лаги и сократить время сбора элементов.

7. [Enchantment Descriptions](https://www.curseforge.com/minecraft/mc-mods/enchantment-descriptions)
    - *Файл в директории*: `EnchantmentDescriptions-Forge-1.20.1-17.0.8.jar`
    - *Описание*: Описания чар — это легкий клиентский мод, который добавляет описания чар во всплывающую подсказку зачарованных книг. Этот мод поддерживает все ванильные чары на более чем 13 языках! Также поддерживается большинство модифицированных чар.

8. [Jade](https://www.curseforge.com/minecraft/mc-mods/jade)
    - *Файл в директории*: `Jade-1.20.1-forge-11.6.3.jar`
    - *Описание*: Зажав shift вы сможете увидеть в подсказке дополнительную информацию о предмете/мобе. Он покажет предметы, которые хранятся в блоках с инвентарем, количество топлива и время приготовления в варочной стойке, скорость, силу, высотку прыжка и эффекты мобов.

9. [Jade Addons](https://www.curseforge.com/minecraft/mc-mods/jade)
    - *Файл в директории*: `JadeAddons-1.20.1-forge-5.2.0.jar`
    - *Описание*: Поддержка модов для Jade.
    - *Нужен для*:
      - [Create](#create)

10. [Sophisticated Backpacks](https://www.curseforge.com/minecraft/mc-mods/sophisticated-backpacks)
    - *Файл в директории*: `sophisticatedbackpacks-1.20.1-3.18.65.935.jar`
    - *Описание*: В майнкрафт появятся рюкзаки, которые вы сможете размещать в мире, раскрашивать в разные цветовые комбинации, а также дополнять различными улучшениями.
    - *Нужно для работы*: 
      - [Sophisticated Core](#sophisticated-core)

11. [Inventory Profiles Next](https://www.curseforge.com/minecraft/mc-mods/inventory-profiles-next)
    - *Файл в директории*: `InventoryProfilesNext-forge-1.20-1.10.7.jar`
    - *Описание*: Позволит вам быстро навести порядок в инвентаре и в сундуках, с помощью новых кнопок для сортировки предметов. 
    - *Нужно для работы*: 
      - [Kotlin for Forge](#kotlin-for-forge)
      - [libIPN](#libipn)

12. [FallingTree](https://www.curseforge.com/minecraft/mc-mods/falling-tree)
    - *Файл в директории*: `FallingTree-1.20.1-4.3.1.jar`
    - *Описание*: Добавляет быстрый способ ломать деревья, быстро падают листья.
    - *Связанные*: 
      - [Cloth Config API](#cloth-config-api)

13. [Durability Tooltip](https://www.curseforge.com/minecraft/mc-mods/durability-tooltip)
    - *Файл в директории*: `durabilitytooltip-1.1.5-forge-mc1.20.jar`
    - *Описание*: Подсказка о долговечности показывает долговечность предмета.

14. [Dynamic Lights](https://www.curseforge.com/minecraft/mc-mods/dynamic-lights)
    - *Файл в директории*: `dynamiclights-1.20.1.1.jar`
    - *Описание*: Динамическое освещение, факел светится в руках.