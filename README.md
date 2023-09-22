### Hi there 👋
I am a Japanese who enjoys Java programming.

```java
IntPredicate fizz = (int num) -> num % 3 == 0;
IntPredicate buzz = (int num) -> num % 5 == 0;
IntStream.rangeClosed(1, 100)
    .mapToObj(i -> new StringBuilder()
        .append(fizz.test(i) ? "Fizz" : "")
        .append(buzz.test(i) ? "Buzz" : "")
        .append(!fizz.or(buzz).test(i) ? i : ""))
    .forEach(System.out::println);
```
<!--
**NamiUni/NamiUni** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
