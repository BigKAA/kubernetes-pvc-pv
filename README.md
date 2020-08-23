# Kubernetes Persistent Volumes & Volume Claims

Статическое и динамическтое создание volumes. 

Материалы для видео на канале https://www.youtube.com/channel/UCU55LZT7oRxhX4GTvb5H4HA

## Статическое создание PV

01-static-pv

## Динамическое сосздание PV

02-dynamic-pv (на примере nfs-client)

Перед использованием примеров, инциализируйте общие сущности кластера:

    kubectl apply -f 00-cluster-init.yaml