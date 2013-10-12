Sublime Text BH-autocomplete
===

Автодополнение для шаблонов BH

Cниппеты автодополнения
----------------------------------

    module.exports = function(bh) { ... }
    bh.match('expression', function(ctx){ ... })
    ctx.tag(value)
    ctx.tag(value, force)
    ctx.mod(key)
    ctx.mod(key, value)
    ctx.mod(key, value, force)
    ctx.mods(values)
    ctx.mods(values, force)
    ctx.attr(key)
    ctx.attr(key, value)
    ctx.attr(key, value, force)
    ctx.mix([{ block: blockName }])
    ctx.mix([{ block: blockName }], force)
    ctx.bem(value)
    ctx.bem(value, force)
    ctx.js(value)
    ctx.js(value, force)
    ctx.content({ block: blockName })
    ctx.content({ block: blockName }, force)
    ctx.content([{ block: blockName }], force)
    ctx.json()
    ctx.position()
    ctx.isFirst()
    ctx.isLast()
    ctx.extend()
    ctx.applyCtx()
    ctx.applyBase()
    ctx.stop()
    ctx.generateId()
    ctx.param(key)
    ctx.param(key, value)
    ctx.param(key, value, force)
    ctx.tParam(key)
    ctx.tParam(key, value)
    ctx.cls(class)
    ctx.cls(class, force)
    
Установка
----------------------------------

1. Ctrl+Shift+P → Package Control: Add Repository → https://github.com/i-akhmadullin/BH-autocomplete

2. Ctrl+Shift+P → Package Control: Install Package → BH-autocomplete

3. В .bh.js файлах будет срабатывать автодополнение, а sublime должен определять синтаксис как BH (если этого не произошло: View → Syntax → Open all with current extension as... → BH )
