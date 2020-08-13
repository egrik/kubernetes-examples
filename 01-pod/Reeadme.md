Применить манифесты:

```kubectl apply -f 01/```

Получить список подов:

```kubectl get pod```

Получить список подов и расширенную информацию о них:

```kubectl get pod -o wide```

Получить информацию о поде в yaml:
```kubectl get pod sc--nginx -o yaml```

Получить описание пода:

```kubectl describe pod sc--nginx```

Посмотреть логи, которые пишутся в stdout по поду:

```kubectl logs pod sc--nginx```

Выполнить команду в поде:

```kubectl exec -it sc--nginx sh```

Редактирование манифеста пода:

```kubectl edit pods sc--nginx```

Настроить порт форвард для пода:

```kubectl port-forward sc--nginx 8282:80```

Редактирование манифеста пода:

```kubectl edit pods sc--nginx```

Удалить сущности в кластере, согласно манифестам, указанным в директории:
```kubectl delete -f 01/```
