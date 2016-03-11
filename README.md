# dockerfile-cuda-keras-jupyter

Dockerized [Jupyter] with [Keras] on top of [Theano] and [CUDA].

## Get Started

With port forwarding:

```
docker run -d -p 8888:8888 lukovkin/dockerfile-cuda-keras-jupyter
```

For persistent storage:

```
docker run -d -p 8888:8888 -v /notebook:/notebook lukovkin/dockerfile-cuda-keras-jupyter
```

Just browse localhost:8888 and write code with [Keras]!

[Keras]: http://keras.io/
[Jupyter]: https://jupyter.org/
