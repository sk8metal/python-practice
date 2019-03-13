# python-practice
pythonの練習

## docker 実行
```
$ docker run -it --rm --name my-running-script -v "$PWD":/usr/local/src/my-test-python -w /usr/local/src/my-test-python  python:2 python sample.py
```

### 出力
```
Hello, World. 0
Hello, World. 1
Hello, World. 2
Hello, World. 3
Hello, World. 4
Hello, World. 5
Hello, World. 6
Hello, World. 7
Hello, World. 8
Hello, World. 9
```
