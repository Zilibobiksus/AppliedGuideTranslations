---
navigation:
  parent: appflux/appflux-index.md
  title: Флюсовый приёмник
  icon: appflux:flux_accessor
categories:
- flux accessor
item_ids:
- appflux:flux_accessor
- appflux:part_flux_accessor
---

# Флюсовый приёмник

<Row>
<BlockImage id="appflux:flux_accessor" scale="8"></BlockImage>
<GameScene zoom="8" background="transparent">
  <ImportStructure src="../structure/flux_accessor.snbt"></ImportStructure>
</GameScene>
</Row>

Флюсовый приёмник может вводить/выводить энергию, хранящуюся в вашей ME-сети. По умолчанию они не имеют ограничений ввода/вывода, что можно изменить в конфигурации Appflux.

У них есть быстрый и обычный режим. В быстром режиме он выдаёт энергию каждый такт, что может вызвать лаги при интенсивном использовании.
В обычном режиме он выдаёт энергию в зависимости от запаса энергии цели, что не вызывает проблем с лагами.

* Внимание: Под «энергией» здесь подразумевается FE, хранящаяся в ваших [ячейках хранения FE](./flux_cells.md), а не энергия в [ячейках энергии](ae2:items-blocks-machines/energy_cells.md).

