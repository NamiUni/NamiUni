### Hi there 👋
I am a Japanese who enjoys Java programming.

```java
IntStream.rangeClosed(1, 100)
        .mapToObj(i -> Optional.of(i)
                .filter(num -> num % 15 == 0)
                .map(num -> "FizzBuzz")
                .orElse(Optional.of(i)
                        .filter(num -> num % 3 == 0)
                        .map(num -> "Fizz")
                        .orElse(Optional.of(i)
                                .filter(num -> num % 5 == 0)
                                .map(num -> "Buzz")
                                .orElse(String.valueOf(i)))))
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
