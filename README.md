# gitflow-examples

1. Создать репозиторий на Github и клонировать его на локальный сервер (ПК).
2. Сделать ветку разработки develope от главной ветки master(main) и запушить ветку develope на Github
3. Создаём модули (ветки внутри develope) для разработки ex.: feature/main-page. После завершения ветка модуля мёрджится с develope и удаляется.
4. Создание ветки release/0.1.0 от develope.
5. Когда ветка release закончена, она мерджится в main и develope.
6. Если в ветке main обнаруживается ошибка, то создаётся ветка hotfix.
7. Когда ветка hotfix зарервшается, она добавляется в main и develope. А затем удаляется. ex.: hotfix/about-page-title
