# Kafka Topic UI

## 適用

### サービスの適用

```bash
# Kafka Rest
kubectl.exe apply -f ./kafka-rest.yaml
# Kafka Topic UI
kubectl.exe apply -f ./kafka-topic-ui.yaml
```

### Kafka UIのアクセス

1. minikuber on Windows

    ```cmd
    start "$(minikube service --url kafkatopicui)"
    ```

2. minikuber on MacOS

    ```bash
    open "$(minikube service --url kafkatopicui)"
    ```

## 参照

1. [Kafka周りの開発・テストに便利なツールをdocker-composeにまとめました](https://qiita.com/tarosaiba/items/b3d1c49c2cc5e773babf)
