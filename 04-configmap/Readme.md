Посмотреть статус деплоймента:

```kubectl rollout status deployment sc--nginx```

Посмотреть историю деплоймента:

```kubectl rollout history deployment sc-nginx```

Откатиться на конкретную ревизию деплоймена:

```kubectl rollout undo deployment sc--nginx --to-revision=1```