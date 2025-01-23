This example comes from https://github.com/FPGAOL-CE/osstoolchain-docker-things
and has been ported to the QMTech board. It features minimal code to work on
the board using clock input and one led output.




```
docker run --rm -v .:/work regymm/openxc7  make -C /work/demo
```

