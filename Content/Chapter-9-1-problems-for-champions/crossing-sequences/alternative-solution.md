#### Alternative Solution

Предходното решение на задачата използва масиви за запазване на стойностите. Масивите не са необходими за решаването на задачата. Съществува **алтернативно решение**, което генерира числата и работи директно с тях, вместо да ги записва в масив. Можем на **всяка стъпка** да проверяваме дали **числата от двете редици съвпадат**. Ако това е така, ще принтираме на конзолата числото и ще прекратим изпълнението на нашата програма. В противен случай, ще видим текущото число на **коя редица е по-малко и ще генерираме следващото, там където "изоставаме"**. Идеята е, че **ще генерираме числа от редицата, която е "по-назад"**, докато не прескочим текущото число на другата редица и след това обратното, а ако междувременно намерим съвпадение, ще прекратим изпълнението.

![](/assets/chapter-9-images/01.Crossing-sequences-07.png)

### Testing in the Judge System

Тествайте решението си тук: [https://judge.softuni.bg/Contests/Practice/Index/518#0](https://judge.softuni.bg/Contests/Practice/Index/518#0).