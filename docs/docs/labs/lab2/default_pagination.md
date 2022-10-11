#### Задание 2.2.1

Настроить пагинацию для любых списков в Вашем проекте.

### Добавим стандартную конфигурацию:

```python
'DEFAULT_PAGINATION_CLASS':
    'rest_framework.pagination.PageNumberPagination',
    'PAGE_SIZE': 5
```

![](../imgs/2022-10-09_19-23.png)