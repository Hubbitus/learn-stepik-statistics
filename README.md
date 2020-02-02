Основы статистики - степик курс
===============================

Conspectus of lessons and solve of the assignments of course https://stepik.org/course/76/ ("Основы статистики").


# How to run

First create [beakerx](https://beakerx.com) container:

```
docker compose up -d
```

Navigate to http://localhost:7777/

Authorize by token from container log:
```
docker logs stepik-statistics-beakerx 2>&1 | grep token
```

Choose notebook (it is sole there)
