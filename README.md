### Hi there 👋
<p align="left">
  <a href="https://github.com/NamiUni/NamiUni/">
    <img src="https://komarev.com/ghpvc/?username=NamiUni" alt="NamiUni" />
  </a>
  <a href="http://twitter.com/namiu_unitarou">
    <img height="20" src="https://img.shields.io/twitter/follow/NamiUni?label=Twitter&logo=twitter&style=flat" />
  </a>
</p>
I am a Japanese who enjoys programming.

```java
IntPredicate fizz = (int num) -> num % 3 == 0;
        IntPredicate buzz = (int num) -> num % 5 == 0;
        IntStream.of(99)
                .forEach(i -> {
                    if (fizz.test(i)) {
                        System.out.print("Fizz");
                    }

                    if (buzz.test(i)) {
                        System.out.print("Buzz");
                    }

                    if (!fizz.and(buzz).test(i)) {
                        System.out.print(i);
                    }

                    System.out.println();
                });
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
