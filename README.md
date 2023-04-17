# selenium_docker_test

```
docker-compose up -d tests
```

### Check logs 

```
docker logs -f selenium_docker_test-tests-1
```

### Check results

```
docker cp selenium_docker_test-tests-1:/tmp/a.png /tmp
firefox /tmp/a.png
```


https://rokpoto.com/selenium-tests-in-docker/#demo-wordpress-in-docker-site