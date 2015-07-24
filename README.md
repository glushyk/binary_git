# Решения
## Работа с историей изменений
1.  <code>git log --since="3 hours ago" --pretty=format:"%an - %s" --date-order --no-merges</code><br>
2.  <code>git log  --pretty=format:"%an - %s, %ad" --date-order -S231</code>


## Избирательное слияние

1. <code>git commit --only</code>

##Исправление ошибок
Сначала выполнить 
<code>git rebase -i</code>

Откроется редактор, в котором можно указать что  сделать:
<code>r reword</code> -  переименовать коммит
