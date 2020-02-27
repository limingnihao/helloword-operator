# helloword-operator
operator的helloword

```
operator-sdk new memcached-operator

operator-sdk add api --api-version=cache.limingnihao.com/v1alpha1 --kind=Memcached

operator-sdk add controller --api-version=cache.limingnihao.com/v1alpha1 --kind=Memcached

```