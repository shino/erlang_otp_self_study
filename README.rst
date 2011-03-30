#################
Erlang/OTP 独習会
#################

:主催: @jbking, @voluntas
:日時: 未定
:場所: 未定

概要
====

- Erlang Programming (日本語もある)
- Erlang/OTP in Action 

上記二冊を元にプレゼン＋ハンズオン形式で進めていきます。

- 参加者は必ず 1 回以上プレゼンとハンズオンの講師をする必要があります
- 1 日で進めるのは 1 ~ 2 章です、隔週で開催予定です。
- イベントは 2 時間以内で終わらせるのを目標とします。
- プレゼンは 1 ポモドーロ (25 分) で、ハンズオンは 2 ポモドーロ (25 分 * 2) です。
- 流れとしては事前にいくつかの章に対して担当を割り振ります

参加方法
========

参加予定者と自己紹介欄を埋めて、pull-request ください。それが merge されたら登録完了です。

参加予定者
==========

- @jbking

  - ここに一言自己紹介を

- @voluntas

  - Erlang しか書けなくなってきてます

- @ymotongpoo

  - Learn You Some Erlang翻訳してるOTP使いたい人

- @itawasa

  - Ruby の変数がアトムに見え始めています

Erlang Programming
==================

::

  1.  Introduction
  2.  Basic Erlang
  3.  Sequential Erlang
  4.  Concurrent Programming
  5.  Process Design Patterns
  6.  Process Error Handling
  7.  Records and Macros
  8.  Software Upgrade
  9.  More Data Types and High-Level Constructs
  10. ETS and Dets Tables
  11. Distributed Programming in Erlang
  12. OTP Behaviors
  13. Introducing Mnesia
  14. GUI Programming with wxErlang
  15. Socket Programming
  16. Interfacing Erlang with Other Programming Languages
  17. Trace BIFs, the dbg Tracer, and Match Specifications
  18. Types and Documentation
  19. EUnit and Test-Driven Development
  20. Style and Efficiency

Erlang and OTP in Action
========================

::

  Part 1 Getting past pure Erlang: the OTP basics

    Chapter 1 The Erlang/OTP platform
    Chapter 2 Erlang language essentials
    Chapter 3 Writing a TCP-based RPC service
    Chapter 4 OTP applications and supervision
    Chapter 5 Using the main graphical introspection tools

  Part 2 Building a production system

    Chapter 6 Implementing a caching system
    Chapter 7 Logging and event handling the Erlang/OTP way
    Chapter 8 Introducing distributed Erlang/OTP
    Chapter 9 Adding distribution to the cache with Mnesia
    Chapter 10 Packaging, services, and deployment

  Part 3 Integrating and refining

    Chapter 11 Adding an HTTP interface to the cache
    Chapter 12 Integrating with foreign code using ports and NIFs
    Chapter 13 Communication between Erlang and Java via Jinterface
    Chapter 14 Optimization and performance
