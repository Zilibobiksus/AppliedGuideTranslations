---
navigation:
  title: MEGA Авто-крафт
  icon: 256m_crafting_storage
  parent: index.md
  position: 020
categories:
  - megacells
item_ids:
  - mega_crafting_unit
  - 1m_crafting_storage
  - 4m_crafting_storage
  - 16m_crafting_storage
  - 64m_crafting_storage
  - 256m_crafting_storage
  - mega_crafting_accelerator
  - mega_crafting_monitor
  - mega_pattern_provider
  - cable_mega_pattern_provider
---

# MEGA Cells: Авто-крафт

<GameScene zoom="6" background="transparent">
  <ImportStructure src="assets/assemblies/crafting_cpu.snbt" />
  <IsometricCamera yaw="195" pitch="10" />
</GameScene>

## MEGA [Процессоры создания](ae2:items-blocks-machines/crafting_cpu_multiblock.md)

<Row>
  <BlockImage id="mega_crafting_unit" scale="4" />
  <BlockImage id="1m_crafting_storage" scale="4" />
  <BlockImage id="4m_crafting_storage" scale="4" />
  <BlockImage id="16m_crafting_storage" scale="4" />
  <BlockImage id="64m_crafting_storage" scale="4" />
  <BlockImage id="256m_crafting_storage" scale="4" />
</Row>

Как и в случае с ячейками хранения, MEGA также предоставляет увеличенные уровни хранилищ для процессоров создания. Хотя они тоже требуют собственной версии <ItemLink id="ae2:crafting_unit" /> для соответствия возросшей мощности, они легко справятся даже с самыми масштабными задачами благодаря большему объёму памяти, при этом выглядя *чертовски круто* в чёрном цвете.

<RecipeFor id="mega_crafting_unit" />
<RecipeFor id="1m_crafting_storage" />
<RecipeFor id="4m_crafting_storage" />
<RecipeFor id="16m_crafting_storage" />
<RecipeFor id="64m_crafting_storage" />
<RecipeFor id="256m_crafting_storage" />

В качестве дополнительного бонуса MEGA также предоставляет свой эквивалент <ItemLink id="ae2:crafting_accelerator" />, но с преимуществом: один такой блок обеспечивает не один, а сразу *ЧЕТЫРЕ* потока совместной обработки.

<BlockImage id="mega_crafting_accelerator" scale="4" />
<RecipeFor id="mega_crafting_accelerator" />

И для полного комплекта существует MEGA-эквивалент <ItemLink id="ae2:crafting_monitor" />. Он ничем не отличается от обычного монитора по функционалу, но служит отличным дополнением к вышеупомянутым блокам для тех, кто хочет сохранить эстетическую целостность и стильный тёмный вид всего мультиблока процессора.

<BlockImage id="mega_crafting_monitor" scale="4" />
<RecipeFor id="mega_crafting_monitor" />

## MEGA-поставщик шаблонов

<Row>
  <BlockImage id="mega_pattern_provider" scale="4" />
  <GameScene zoom="4" background="transparent">
    <ImportStructure src="assets/assemblies/cable_mega_pattern_provider.snbt" />
  </GameScene>
</Row>

Являясь напарником <ItemLink id="ae2:pattern_provider" />, **MEGA-поставщик шаблонов** продолжает традицию создания увеличенных вариантов устройств AE2, удваивая ёмкость шаблонов — теперь их может быть до 18 штук. Однако за это приходится платить тем, что он может содержать только [**шаблоны обработки**](ae2:items-blocks-machines/patterns.md), поэтому он не будет работать с <ItemLink id="ae2:molecular_assembler" />.

<Row>
  <RecipeFor id="mega_pattern_provider" />
  <RecipeFor id="cable_mega_pattern_provider" />
</Row>
