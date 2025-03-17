# Домашнее задание к занятию «Git»

### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` [репозитория c шаблоном решения](https://github.com/netology-code/sys-pattern-homework) к себе в GitHub и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/gitlab-hw или https://github.com/имя-вашего-репозитория/8-03-hw.
   2. Выполните клонирование этого репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите сверху название занятия, ваши фамилию и имя;
      - в каждом задании добавьте решение в требуемом виде — текст, код, скриншоты, ссылка;
      - для корректного добавления скриншотов используйте [инструкцию «Как вставить скриншот в шаблон с решением»](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md);
      - при оформлении используйте возможности языка разметки md. Коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md).
   4. После завершения работы над домашним заданием сделайте коммит `git commit -m "comment"` и отправьте его на GitHub `git push origin`.
   5. Для проверки домашнего задания в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем GitHub.
   6. Любые вопросы по выполнению заданий задавайте в чате учебной группы или в разделе «Вопросы по заданию» в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!

---

### [Здесь](https://github.com/Ivashka80/git-hw-) находится `fork` [репозитория c шаблоном решения](https://github.com/netology-code/sys-pattern-homework) из инструкции выше. Далее идут шаги выполнения домашнего задания.


### Задание 1

**Что нужно сделать:**

1. Зарегистрируйте аккаунт на [GitHub](https://github.com/).

<details>

![01](https://github.com/user-attachments/assets/5c4097a7-bfb9-464d-b6ce-76690767548f)

</details>

2. Создайте публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».

<details>

 ![image](https://github.com/user-attachments/assets/11815802-7604-41aa-854a-efe4ab9acebc)

</details>

3. Склонируйте репозиторий, используя https протокол `git clone ...`.

<details>

Клонирование сделано с помощью SSH-ключа
 
![image](https://github.com/user-attachments/assets/fdfd82f2-0e82-4936-91dd-d45e40a7d1b6)

</details>

4. Перейдите в каталог с клоном репозитория.

<details>

![image](https://github.com/user-attachments/assets/3d86799c-9ba7-4b9a-911e-5cf5d896e0c0)

</details>

5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email johndoe@example.com`.

<details>

![image](https://github.com/Ivashka80/Netology/assets/121082757/ab309d1d-7d31-4405-b61a-5c9906b62d87)

</details>

6. Выполните команду `git status` и запомните результат.

<details>

![image](https://github.com/user-attachments/assets/be282099-8d17-4d6e-817b-c12ed5d31673)

</details>

7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.

<details>

![image](https://github.com/user-attachments/assets/e317f207-00f7-4c3b-ab88-5f76a56b95ab)

</details>

8. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.

<details>

![image](https://github.com/user-attachments/assets/640298a3-ee08-4271-938a-246dd2bb00e3)

</details>

9. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.

<details>

![image](https://github.com/user-attachments/assets/8563b6f4-eeb7-4d0e-ade1-3c506b52d420)
![image](https://github.com/user-attachments/assets/9b9ab299-0f63-4342-8a72-4923dbd1396a)


</details>

10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.

<details>

![image](https://github.com/user-attachments/assets/aca3f4d5-abb9-420f-a7be-7d1244673777)

</details>

11. Ещё раз выполните команды `git diff` и `git diff --staged`.

<details>

![image](https://github.com/user-attachments/assets/3c14c51f-4aca-40ac-9e15-62df58121cf3)

</details>

12. Теперь можно сделать коммит `git commit -m 'First commit'`.

<details>

![image](https://github.com/user-attachments/assets/ae62ae6f-0334-4840-a775-d262f2aeaaa9)
![image](https://github.com/user-attachments/assets/1f7a3a56-4cb3-4063-9a2c-24685bef470f)

</details>

13. Сделайте `git push origin master`.

<details>

![image](https://github.com/user-attachments/assets/88b9a506-34eb-47cd-8ad8-4e452860e1ee)

![image](https://github.com/user-attachments/assets/6dfd8775-5b2d-4e9b-8b1d-c188ce683246)

![image](https://github.com/user-attachments/assets/941a0035-8eaf-4f0a-a6fe-34474bdcd30d)

</details>

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

[Ссылка](https://github.com/Ivashka80/my-first-github/commit/5ce0e2f7275f9a42263a9c92cde3f904df31ae27)

---

### Задание 2

**Что нужно сделать:**

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.

<details>

![image](https://github.com/Ivashka80/Netology/assets/121082757/83bd9228-2edb-4625-9718-e14f5ed5ffbc)

</details>

2. Добавьте файл .gitignore в следующий коммит `git add...`.

<details>

![image](https://github.com/Ivashka80/Netology/assets/121082757/406041e7-086c-4c81-9feb-9e7f191b4e77)

</details>

3. Напишите правила в этом файле, чтобы игнорировать любые файлы `.pyc`, а также все файлы в директории `cache`.

<details>

![image](https://github.com/Ivashka80/Netology/assets/121082757/517da4e6-9a7b-4624-a93d-4ada559e150f)

</details>


4. Сделайте коммит и пуш.

<details>

![image](https://github.com/Ivashka80/Netology/assets/121082757/f9f575fb-5ed8-43a7-9ecd-ac11819f5626)

![image](https://github.com/Ivashka80/Netology/assets/121082757/5cb012d4-1f49-41aa-9af2-7ca8586d3c43)

</details>

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

[Ссылка](https://github.com/Ivashka80/my-first-github/commit/7703cbdf2134f749aafc788123ce743a552e1282)

---

### Задание 3

**Что нужно сделать:**

1. Создайте новую ветку dev и переключитесь на неё.

<details>

![image](https://github.com/Ivashka80/Netology/assets/121082757/36115cdd-09a7-4793-a375-c94b79a4e016)

</details>

2. Создайте файл test.sh с произвольным содержимым.

<details>

![image](https://github.com/Ivashka80/Netology/assets/121082757/59357a94-a61d-4c50-8114-bf7861aef850)

![image](https://github.com/Ivashka80/Netology/assets/121082757/4ff300ef-81e4-4e4f-8f96-60929639d13b)

</details>

3. Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.

<details>

![image](https://github.com/Ivashka80/Netology/assets/121082757/ce9cd8de-648e-4bd1-8d8c-418364c593c6)

</details>

   4. Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать `git merge`.

<details>

![image](https://github.com/Ivashka80/Netology/assets/121082757/1bde333c-b494-4348-a85e-95f4c1f91bb6)

</details>

5. Сделайте коммит и пуш.

<details>

![image](https://github.com/Ivashka80/Netology/assets/121082757/13a41cd6-1b5d-4bfc-9dd6-42e688c2ca95)

![image](https://github.com/Ivashka80/Netology/assets/121082757/06f8c461-5a4f-4287-a317-fbf7efa9755b)

![image](https://github.com/Ivashka80/Netology/assets/121082757/dac733c1-1d78-483c-b5db-576b0b32ca0d)

</details>

В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

### [Ссылка](https://github.com/Ivashka80/my-first-github/network) на граф.


---

<details>

## Дополнительные задания* (со звёздочкой)

Их выполнение необязательное и не влияет на получение зачёта по домашнему заданию. Можете их решить, если хотите лучше разобраться в материале.

---

### Задание 4*

Сэмулируем конфликт. Перед выполнением изучите с [документацию](https://git-scm.com/book/ru/v2/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B-Git-%D0%9F%D1%80%D0%BE%D0%B4%D0%B2%D0%B8%D0%BD%D1%83%D1%82%D0%BE%D0%B5-%D1%81%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D0%B5).

**Что нужно сделать:**

1. Создайте ветку conflict и переключитесь на неё.
2. Внесите изменения в файл test.sh. 
3. Сделайте коммит и пуш.
4. Переключитесь на основную ветку.
5. Измените ту же самую строчку в файле test.sh.
6. Сделайте коммит и пуш.
7. Сделайте мердж ветки conflict в основную ветку и решите конфликт так, чтобы в результате в файле оказался код из ветки conflict.

В качестве ответа на задание прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

 </details>
