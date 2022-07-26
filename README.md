# CatsEffectByExamples - Asynchronous runtime in functional programming style 😼

[![Generic badge](https://img.shields.io/badge/Scala-2.12.16-darkred.svg?style=plastic)](https://www.scala-lang.org/)
[![Generic badge](https://img.shields.io/badge/CatsEffect3-3.3.14-red.svg?style=plastic)](https://typelevel.org/cats-effect/)
[![Generic badge](https://img.shields.io/badge/SBT-1.6.2-blue.svg?style=plastic)](https://www.scala-sbt.org/)
[![Generic badge](https://img.shields.io/badge/OpenJDK-11-white.svg?style=plastic)](https://adoptium.net/)

![img.png](docs/front-img.jpg)

👾📚 The objective is to do an easy-to-access codes snippets collections of important Cats Effect concepts.
Cats Effect possesses [IO](https://typelevel.org/cats-effect/api/3.x/cats/effect/IO.html)
for wrapping & chaining asynchronous codes executions.
It has also the concept of [Resource](https://typelevel.org/cats-effect/api/3.x/cats/effect/kernel/Resource.html)
for an automatic resources releasing after usage.
[Semaphore](https://typelevel.org/cats-effect/api/3.x/cats/effect/std/Semaphore.html) and more well known asynchronous
programming patterns are also part of the library.


# Table of contents 📃

🔎📚 For a better understanding of each subject please take the time to run the code snippets.
They all compile & are runnable ✅.
So do not hesitate to fork this git repository and execute them on your own computer 😍.

<ins>Remark</ins>: Some code snippets have multiple possible runs.

| 🔎 Subject       | 📃 Description                                                                                                                                            | 👾 Code snippets                                                                                                                         |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| **IOs**          | *This part focuses on understanding `IOs` as data structures holding a manageable execution result.*                                                      | [Introduction](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_0_io/_A_Introduction.scala)               |
|                  |                                                                                                                                                           | [Parallel](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_0_io/_B_Parallel.scala)                       |
|                  |                                                                                                                                                           | [Traversal](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_0_io/_C_Traversal.scala)                     |
|                  |                                                                                                                                                           | [Exception](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_0_io/_D_Exception.scala)                     |
| **Concurrency**  | *This part focuses on understanding `Fibers` as easy-to-manage threads with possibility of starting & joining concurrently execution results from `IOs`.* | [Fiber](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_1_concurrency/_A_Fiber.scala)                    |
|                  |                                                                                                                                                           | [Uncancelable](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_1_concurrency/_B_Uncancelable.scala)      |
|                  |                                                                                                                                                           | [Race](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_1_concurrency/_C_Race.scala)                      |
|                  |                                                                                                                                                           | [Resource](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_1_concurrency/_D_Resource.scala)              |
| **Coordination** | *This part focuses on understanding communication patterns between `Fibers`.*                                                                             | [Ref](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_2_coordination/_A_Ref.scala)                       |
|                  |                                                                                                                                                           | [Deferred](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_2_coordination/_B_Deferred.scala)             |
|                  |                                                                                                                                                           | [Semaphore](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_2_coordination/_C_Semaphore.scala)           |
|                  |                                                                                                                                                           | [CountDownLatch](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_2_coordination/_D_CountDownLatch.scala) |
|                  |                                                                                                                                                           | [CyclicBarrier](https://github.com/iLoveDataJjia/catseffectbyexamples/blob/main/src/main/scala/_2_coordination/_E_CyclicBarrier.scala)   |


# Main references 📚

- [Official docs](https://typelevel.org/cats-effect/docs/getting-started)
- [ScalaDoc](https://typelevel.org/cats-effect/api/3.x/index.html)
- [RockTheJVM course](https://rockthejvm.com/p/cats-effect)