# Assembly

> Estudos de Assembly com foco em compreender como os computadores funcionam em baixo nível, explorando a relação entre código, CPU, memória, sistema operacional e hardware.

---

##  Por que estou aprendendo Assembly?

Comecei a estudar Assembly por uma razão simples: **quero entender melhor o que realmente acontece dentro de um computador quando um programa é executado.**

Já estudei e estudo linguagens de alto nível como Python, TypeScript, Java, Go e Rust. Elas permitem construir aplicações sem precisar lidar diretamente com registradores, memória e instruções da CPU.

Mas isso também cria uma abstração.

Quero ir além dessa abstração.

Quero compreender:

* Como a CPU executa instruções;
* O que são e como funcionam os registradores;
* Como a memória é utilizada;
* Como funciona a Stack;
* Como dados são representados;
* Como uma função de uma linguagem de alto nível pode chegar até Assembly;
* Como o Assembly se transforma em código de máquina;
* Como programas interagem com o sistema operacional;
* Como funcionam as chamadas de sistema (*syscalls*);
* Como o software conversa com o hardware.

Por isso, Assembly faz parte da minha tentativa de entender **o computador de baixo para cima**.

```text
Código de alto nível
       ↓
Compilador / Interpretador
       ↓
Assembly
       ↓
Código de máquina
       ↓
CPU
       ↓
Hardware
```

---

##  Arquitetura de computadores

Um dos principais motivos para estudar Assembly é compreender **Arquitetura de Computadores**.

Quero deixar de enxergar o computador apenas como uma máquina que executa programas e começar a entender os componentes que tornam essa execução possível.

O objetivo é estudar a relação entre:

```text
CPU
 │
 ├── Registradores
 ├── ALU
 ├── Control Unit
 └── Instruction Set
       │
       ↓
    Memória
       │
       ↓
Sistema Operacional
       │
       ↓
    Aplicações
```

Assembly é uma das ferramentas que me permite observar essa camada com muito mais proximidade.

---

## 🐧 Linux From Scratch

Outro motivo importante para este estudo é o meu interesse em entender profundamente o **Linux**.

Estou pensando em, no futuro, criar minha própria distribuição Linux, seguindo os conceitos apresentados no projeto:

**Linux From Scratch (LFS)**

https://www.linuxfromscratch.org/

A ideia não é apenas instalar uma distribuição Linux pronta, mas entender gradualmente os componentes que formam um sistema Linux.

Para isso, considero importante conhecer:

* Assembly;
* C;
* Linux;
* Sistemas Operacionais;
* Arquitetura de Computadores;
* Compiladores;
* Linkers;
* ELF;
* Syscalls;
* Boot process;
* Filesystems;
* Toolchains.

Este repositório começa pelo Assembly como uma das portas de entrada para esse mundo.

---

# 📚 Índice

## 00 — Instalação e ambiente

Configuração do ambiente necessário para escrever, montar, executar e depurar Assembly.

* [Instalação do Assembly](./00/installation/README.md)

---

## 01 — Primeiro programa

Começando pelo programa clássico:

```text
Hello, World!
```

* [Primeiro script — Hello World](./01/hello-world/README.md)


---

# Objetivo final

O objetivo deste repositório não é simplesmente aprender a escrever Assembly.

Quero utilizar Assembly como uma ferramenta para compreender melhor a máquina que estou programando.

**Do código → à máquina → ao sistema operacional.**


© 2026 Cust Coding
