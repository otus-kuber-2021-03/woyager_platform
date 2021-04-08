#kubernetes-controllers

## почему обновление ReplicaSet не повлекло обновление запущенных pod

ReplicaSet не проверяет соответствие запущенных Podов шаблону

## Найдите способ модернизировать свой DaemonSet таким образом, чтобы Node Exporter был развернут как на master, так и на worker нодах

      tolerations:
      - key: node-role.kubernetes.io/master
        effect: NoSchedule
