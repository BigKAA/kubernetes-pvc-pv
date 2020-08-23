#Static PV

Пример создания статического PV

##Команды cli
Список всех pv:

    kubectl get pv

Подробная информация о pv:

    kubectl describe pv pv-name

Список pvc (_необходимо явно указывать namespace_):

    kubectl -n volumes-sample get pvc

Подробная информация о pvc в yaml формате:

    kubectl -n volumes-sample get pvc pvc-name -o yaml
