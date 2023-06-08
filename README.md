# JavaScript-Challenges 
 <img height="60" src="https://img.icons8.com/color/344/javascript.png">

Welcome to the  Programming Exercises Repository! Here you will find a collection of challenges and practical exercises designed to help developers improve their JavaScript skills.

 The exercises are  selected to cover a wide range of JavaScript topics and fundamental concepts, such as string manipulation, arrays, objects, functions, control structures, algorithms, and more.

Contributions are welcome! If you have an interesting exercise to add or find errors in existing exercises, feel free to open a pull request. Together, we can expand and enhance this repository, providing a valuable resource for the JavaScript developer community.

Enjoy learning, problem-solving, and improving your JavaScript skills. Happy coding!

<img width="950" alt="js2" src="https://github.com/andreahcodes/JavaScript-Programming-Exercises/assets/112190511/dbf170b9-9f19-43c2-81c8-e65a000db72a">




Prática e Exercícios: A prática é fundamental para melhorar suas habilidades em JavaScript. Além de escrever seu próprio código, resolver exercícios de programação e desafios pode ajudar a aprimorar suas habilidades lógicas e entender melhor os conceitos da linguagem.
###### 1. What's the output?

```javascript
function printNumber() {
  console.log(number);
  let number = 42;
}

printNumber();

```

- A: 42
- B: undefined
- C: `ReferenceError`


<details><summary><b>Answer</b></summary>
<p>

#### Answer: C
 
🇺🇸Inside the function, we declare the variable number using the let keyword. Unlike the var keyword, variables declared with let are not initialized with a default value. Therefore, when we try to print number before assigning a value to it, a ReferenceError occurs, indicating that the variable has not been defined.

🇧🇷Dentro da função, declaramos a variável number usando a palavra-chave let. Diferentemente da palavra-chave var, as variáveis com let não são inicializadas com um valor padrão. Portanto, quando tentamos imprimir number antes de atribuir um valor a ele, ocorre um erro de ReferenceError, indicando que a variável não foi definida.

</p>
</details>
