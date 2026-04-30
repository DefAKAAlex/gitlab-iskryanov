# gitlab-iskryanov
# Задание 1
*Что нужно сделать:*

*Разверните GitLab локально, используя Vagrantfile и инструкцию, описанные в этом репозитории.
Создайте новый проект и пустой репозиторий в нём.
Зарегистрируйте gitlab-runner для этого проекта и запустите его в режиме Docker. Раннер можно регистрировать и запускать на той же виртуальной машине, на которой запущен GitLab.
В качестве ответа в репозиторий шаблона с решением добавьте скриншоты с настройками раннера в проекте.*


Работу выполнял на ВМ в Yandex Cloude
1) Создал проект

2) установил и настроил runner
![Раннер](https://github.com/DefAKAAlex/gitlab-iskryanov/blob/main/push.png)

![Раннер2](https://github.com/DefAKAAlex/gitlab-iskryanov/blob/main/runner2.png)


# Задание 2
*Что нужно сделать:*

*Запушьте репозиторий на GitLab, изменив origin. Это изучалось на занятии по Git.
Создайте .gitlab-ci.yml, описав в нём все необходимые, на ваш взгляд, этапы.
В качестве ответа в шаблон с решением добавьте:*

*файл gitlab-ci.yml для своего проекта или вставьте код в соответствующее поле в шаблоне;
скриншоты с успешно собранными сборками.*


1) склонировал приведённый в задании репазиторий, убрал привязку и добавил в gitlab
```
git clone https://github.com/netology-code/sdvps-materials.git
git remote remove origin
git push -u http://def1:gl************ib@81.26.187.92/root/project-iskryanov.git main
git push -u origin main
```
![clone](https://github.com/DefAKAAlex/gitlab-iskryanov/blob/main/git-push.png)

2) Создал .gitlab-ci.yml

![ci](https://github.com/DefAKAAlex/gitlab-iskryanov/blob/main/gitlab-ci.yml.png)

![результат](https://github.com/DefAKAAlex/gitlab-iskryanov/blob/main/pipeline.png)