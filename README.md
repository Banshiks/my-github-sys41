# Домашнее задание к занятию «Git»

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

![image](https://github.com/user-attachments/assets/90e36c29-a365-492f-8abd-d10b73f8f320)


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

![image](https://github.com/user-attachments/assets/4f599d65-1dc9-46eb-8a79-36e52294523c)

![image](https://github.com/user-attachments/assets/9b9ab299-0f63-4342-8a72-4923dbd1396a)


</details>

10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.

<details>

![image](https://github.com/user-attachments/assets/aca3f4d5-abb9-420f-a7be-7d1244673777)

</details>

11. Ещё раз выполните команды `git diff` и `git diff --staged`.

<details>

![image](https://github.com/user-attachments/assets/0bf160cd-b395-47b9-861b-ef30e96cee8d)

</details>

12. Теперь можно сделать коммит `git commit -m 'First commit'`.

<details>

![image](https://github.com/user-attachments/assets/ae62ae6f-0334-4840-a775-d262f2aeaaa9)
![image](https://github.com/user-attachments/assets/1f7a3a56-4cb3-4063-9a2c-24685bef470f)

</details>

13. Сделайте `git push origin master`.

<details>

![image](https://github.com/user-attachments/assets/88b9a506-34eb-47cd-8ad8-4e452860e1ee)

![image](https://github.com/user-attachments/assets/fa258445-c56b-4f80-a84f-15604d4a915f)

![image](https://github.com/user-attachments/assets/941a0035-8eaf-4f0a-a6fe-34474bdcd30d)

</details>

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

[Ссылка](https://github.com/Ivashka80/my-first-github/commit/5ce0e2f7275f9a42263a9c92cde3f904df31ae27)

---

### Задание 2

**Что нужно сделать:**

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.

<details>

![image](https://github.com/user-attachments/assets/789b15b3-7c37-491a-bd22-fcc6cd21e8f8)

</details>

2. Добавьте файл .gitignore в следующий коммит `git add...`.

<details>
 
![image](https://github.com/user-attachments/assets/d5539c9c-78f1-411a-9b84-6256bfb083bf)

</details>

3. Напишите правила в этом файле, чтобы игнорировать любые файлы `.pyc`, а также все файлы в директории `cache`.

<details>

![image](https://github.com/user-attachments/assets/4851264c-85e2-47dc-be56-7395c7f5082b)

</details>


4. Сделайте коммит и пуш.

<details>

![image](https://github.com/user-attachments/assets/22a03a1d-8854-4be4-8e2e-a8b5e37d05c5)

![image](https://github.com/user-attachments/assets/f6de1701-aeb9-4cc4-8b35-ed80e9383496)

![image](https://github.com/user-attachments/assets/89bc81c8-4c6b-424b-92a7-8d9eec10b0b6)

</details>

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

[Ссылка](https://github.com/Ivashka80/my-first-github/commit/7703cbdf2134f749aafc788123ce743a552e1282)

---

### Задание 3

**Что нужно сделать:**

1. Создайте новую ветку dev и переключитесь на неё.

<details>

![image](https://github.com/user-attachments/assets/5bcb2b14-8a66-4295-9ee4-71407ddb5058)

</details>

2. Создайте файл test.sh с произвольным содержимым.

<details>

![image](https://github.com/user-attachments/assets/0d3a3b02-e6f7-4209-870c-6dd5962016b8)

![image](https://github.com/user-attachments/assets/06a416a8-4ff5-4f3f-98a5-54a1e409e8a0)

![image](https://github.com/user-attachments/assets/8d9c82b5-1f54-4ef4-bc77-5255dd037ebf)

</details>

3. Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.

<details>
 
![image](https://github.com/user-attachments/assets/530e26e2-d29c-4e99-b0f0-24f87ce1fcdc)

![image](https://github.com/user-attachments/assets/05d18bce-618d-4bca-bcf0-eb9ea414ce5c)

![image](https://github.com/user-attachments/assets/abd93f95-11ef-4cc0-a5e1-9a69076bd9fb)

</details>

   4. Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать `git merge`.

<details>

![image](https://github.com/user-attachments/assets/4c91d374-0012-4c85-af3f-df28414b54f3)


![image](https://github.com/user-attachments/assets/81950430-beba-474e-bf1c-2de34c7ddff7)

</details>

5. Сделайте коммит и пуш.

<details>

![image](https://github.com/user-attachments/assets/8e4a1b97-65d2-4742-a1e5-cc53b58944a8)


![image](https://github.com/user-attachments/assets/3993e0c4-85bc-4ac8-bbb9-9e44b7b4c7d9)

</details>
