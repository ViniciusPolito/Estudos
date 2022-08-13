# Java

## Caracteristicas

As principais características de Java são as seguintes:

**Concisa e simples:**
Não contém redundâncias e é fácil de entender, implementar e usar. Parecida com C++ para facilitar compreensão por grande parte de programadores. É uma evolução de C++: não suporta aritmética de ponteiros, registros, coercions, etc.

**Orientada a objetos:**
Suporta os principais conceitos de orientação a objetos. Favorece reusabilidade.

**Provê acesso a Internet/WWW*:*
Contém bibliotecas especiais que possibilitam o trabalho com protocolos TCP/IP como HTTP e FTP. Permite acesso a URLs.

**Robusta:**
Strongly typed. Programas são confiáveis. Reduz imprevistos em tempo de execução: variáveis são automaticamente inicializadas, uso disciplinado de ponteiros, rotinas devem ser chamadas corretamente, etc.

**Portável:**
Completamente especificada. Não contém aspectos dependentes da implementação: o tamanho dos tipos é fixo para qualquer implementação, etc.

**Segura:**
Restrições de acesso a arquivos, manipulação de ponteiros, etc. Implica que não é útil para desenvolver certas aplicaçoes como `device drivers'.

**Concorrente:**
Suporta aplicações concorrentes: multithreads, monitores, execução atômica.
Por outro lado as principais características da implementação atual de Java são as seguintes:

**Independente de plataforma:**
Geração de bytecode que pode ser interpretado para qualquer arquitetura e sistema operacional tendo o sistema Java. Facilita distribuição de software.

**Interpretada:**
Facilita desenvolvimento exploratório. Perde em eficiência.

**Compilada:**
Utilizando compiladores, bytecodes podem ser traduzidos em tempo de execução para código de máquina.

## Significados

### JVM (Java Virtual Machine)

![JavaVirtualMachine2](https://user-images.githubusercontent.com/41132563/184510037-2a72cfcb-1016-439c-9203-57e9e61c340b.jpg)

A JVM vai receber o Byte Code (.class) para traduzir as instruções do código, em algo que o sistema operacional entenda. <br>

Código Java (.java) -> Byte Code (.class) -> Linguagem que o SO entende. <br>
