# LLVMGenerateGraphCMD

- sudo apt-get install -y graphviz-doc libgraphviz-dev graphviz
- clang -S -emit-llvm main.cpp -o main.ll
- opt -dot-dom main.ll or opt -dot-callgraph main.ll
- dot dom.main.dot -Tpng -o dom.main.png
