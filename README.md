# Решения
## Работа с историей изменений
1.  <code>git log develop-feature1 ^develop ^master  --since=3.hours --pretty=format:"%an - %s" </code><br>
2.  <code>git log develop master  --pretty=format:"%an - %s, %ad" --grep=231</code>


## Избирательное слияние

В ветке develop делаем команду

<code>git cherry-pick SHA-1</code>

SHA-1 - коммит, который нужно переместить из ветки develop-feature1

##Исправление ошибок
Сначала выполнить 
<code>git rebase -i</code>

Откроется редактор, в котором можно указать что  сделать:
<code>r reword</code> -  переименовать коммит



