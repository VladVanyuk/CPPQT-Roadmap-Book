# Cheatsheet: Простий алгоритм для роботи з системою контролю версій \(одна гілка, один розробник\)

1. Клонуйте ваш репозиторій \(`git clone адреса`\) чи створіть його локально \(`git inin`\).
2. Виконуйте необхідну роботу у середині теки репозиторію.
3. Перевірте статус репозиторію \(`git status`\).
4. Додайте нові файли \(`git add файл чи тека`\), видаліть непотрібні файли \(`git rm файл`\) або додайте до коміту усі файли які були вже додані, але є модифіковані \(`git add -u`\).
5. Перевірте статус репозиторію — які файли увійдуть до наступного коміту \(`git status`\).
6. Виконайте коміт. Додайте до коміта якісний коментар, який буде описувати ваші зміни. \(`git commit -m “Коментар”`\)
7. Повторіть короки 2-6 допоки усі необхідні зміни в код не будуть внесені.
8. Перед завершенням роботи обов'язково надішліть зміни до віддаленого репозиторію \(`git push`\). Якщо репозиторій було створено локально зв'яжіть його з віддаленим перед командою push \(`git remote add origin адреса`\) та виконайте push \(`git push -u origin master`\)

