---
layout: media
title: Technology
share: false
permalink: /technology/
image:
  feature: binary-code-2-1241809.jpg
---

At QBayLogic we have developed [CλaSH](http://clash-lang.org/)
(pronounced ‘clash’), which is a functional hardware description language that
borrows both its syntax and semantics from the functional programming language
Haskell. It provides a familiar structural design approach to both combinational
and synchronous sequential circuits. The CλaSH compiler transforms these
high-level descriptions to low-level synthesizable VHDL, Verilog, or
SystemVerilog.

Features of CλaSH:

  * Strongly typed (like VHDL), yet with a very high degree of type inference,
    enabling both safe and fast prototying using concise descriptions (like
    Verilog).
  * Interactive REPL: load your designs in an interpreter and easily test all
    your component without needing to setup a test bench.
  * Compile your designs for fast simulation.
  * Higher-order functions, in combination with type inference, result in
    designs that are fully parametric by default.
  * Synchronous sequential circuit design based on streams of values, called
    `Signal`s, lead to natural descriptions of feedback loops.
  * Multiple clock domains, with type safe clock domain crossing.
  * Template language for introducing new VHDL/(System)Verilog primitives.
