# Android Kotlin Demo Coroutines Structured Concurrency

Kotlin coroutines provide a powerful and flexible way to write asynchronous and concurrent code. One of the key concepts in coroutines is structured concurrency, which helps to ensure that resources are properly managed and errors are handled in a predictable way.

Structured concurrency is a programming paradigm that emphasizes the use of scopes to manage the lifecycle of asynchronous tasks. In Kotlin coroutines, a scope is an instance of a coroutine builder such as GlobalScope, CoroutineScope, or SupervisorScope. When you launch a coroutine within a scope, it becomes a child of that scope, and when the scope is cancelled or completes, all of its child coroutines are cancelled as well.

This means that you can easily create hierarchies of coroutines that can be cancelled together and handle errors in a predictable way.

___

### Unstructured Concurrency

[![Vaibhav Mojidra - 1.jpeg](https://raw.githubusercontent.com/VaibhavMojidra/Android-Kotlin---Demo-Coroutines-Structured-Concurrency/master/output/1.jpeg "Vaibhav Mojidra")](https://vaibhavmojidra.github.io/site/)

___

### Structured Concurrency

[![Vaibhav Mojidra - 2.jpeg](https://raw.githubusercontent.com/VaibhavMojidra/Android-Kotlin---Demo-Coroutines-Structured-Concurrency/master/output/2.jpeg "Vaibhav Mojidra")](https://vaibhavmojidra.github.io/site/)