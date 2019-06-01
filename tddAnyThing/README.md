<h1 align='center'>
What Do I Mean By I Can TDD Anything ?.
</h1>

```
Stating that I can TDD anything a very big statement, 
nevertheless this is how I understand TDD.
```
TDD means Test Driven Development. It is the art of writing test to represent behaviours that an object is suppose to have, and then writing the simplest code to pass the test. It also means having a clear process, plan and how a model show be before writing code.

Assuming that I wanted to write a programme that takes a persons name and then says hello to the person.

> Here is how I would approach it via TDD.

 - First, I would write a failing test like so.

 <img width="701" alt="Screen Shot 2019-05-12 at 14 49 20" src="https://user-images.githubusercontent.com/37377831/57583633-1b322e00-74ca-11e9-9308-99665f806a4b.png">

- Then run my test using ``rspec`` (Red).

<img width="564" alt="Screen Shot 2019-05-12 at 14 48 49" src="https://user-images.githubusercontent.com/37377831/57583600-ddcda080-74c9-11e9-9bdd-677711362ef2.png">

- Then I would write the simplest code to pass the test.

<img width="703" alt="Screen Shot 2019-05-12 at 14 50 43" src="https://user-images.githubusercontent.com/37377831/57583651-62b8ba00-74ca-11e9-9051-c1e2f81c9578.png">

- Then run my test again ``rspec`` (Green).

<img width="568" alt="Screen Shot 2019-05-12 at 14 51 02" src="https://user-images.githubusercontent.com/37377831/57583671-95fb4900-74ca-11e9-804a-a46c1814b5d5.png">

- I will continue to write more test to describe the needed behaviour I want.

<img width="704" alt="Screen Shot 2019-05-12 at 15 32 33" src="https://user-images.githubusercontent.com/37377831/57583709-305b8c80-74cb-11e9-9ad4-ec628074d639.png">

- Then run my test again (Red).

<img width="572" alt="Screen Shot 2019-05-12 at 15 16 54" src="https://user-images.githubusercontent.com/37377831/57583736-73b5fb00-74cb-11e9-8235-8f062d0cd278.png">

- This would be followed by writing the code necessary to pass and move to the next failing suite.

<img width="675" alt="Screen Shot 2019-05-12 at 15 17 32" src="https://user-images.githubusercontent.com/37377831/57583764-b24bb580-74cb-11e9-88b3-e8e923a923d5.png">


<img width="568" alt="Screen Shot 2019-05-12 at 15 17 47" src="https://user-images.githubusercontent.com/37377831/57583768-c7284900-74cb-11e9-8256-4fdaa3d3ac0e.png">

- Lastly, I would Write code to pass test.

<img width="676" alt="Screen Shot 2019-05-12 at 15 18 20" src="https://user-images.githubusercontent.com/37377831/57583789-fd65c880-74cb-11e9-9290-c023be85559c.png">

- Now run test again.

<img width="570" alt="Screen Shot 2019-05-12 at 15 18 12" src="https://user-images.githubusercontent.com/37377831/57583795-11112f00-74cc-11e9-98d5-9d30a0246764.png">



Normally, TDD is implemented in theree stages.
- Red.
- Green.
- Refactor.

But obviously, this code is too simple to refactor at the current stage.

> An example of when I implemented the full TDD cycle can be found [here](https://github.com/SarpongAbasimi/ProcessWorkShopKatas/tree/master/middle_string) , [here](https://github.com/SarpongAbasimi/FizzBuzz-Python-JavaScript-More-) and [here](https://github.com/SarpongAbasimi/FizzBuzz-Python-JavaScript-More-/tree/master/fizzBuzzJs)

In short when I say, I can TDD anything thing, what I really mean is that, I can
- Write the user stories which gives me an idea of what to test.
- Create a diagram of the classes, properties and functions needed for the first feature and unit test.
- Follow the red, green, refactor cycle:
- Red phase.

```
Write a failing feature test.
Write a failing unit test, matching the feature test.
```
- Green phase.

```
Write the least amount of code to make the unit test pass.
Run the tests and check if unit test passes. If not, repeat green phase.

```

- Refactor phase.

```
Refactor code without adding new features.
Run tests again to check that the refactoring did not break the tests.
No code should be written unless if it is to make a failing unit test pass.
Unit tests should be specific and precise.
```

<h4 align='center'>
What Tools Do I Use For Testing ?.
<h4>

> Through out Makers, I have learnt to use a number of differnt testing frameworks. These are the some of the ones I normally use for my daily work.


| Language        |  Testing Frame work      |Evidence |
|:---:            | :-----:                  | :-----: | 
| Ruby            | <img src='https://user-images.githubusercontent.com/37377831/56475060-09d1a500-647b-11e9-9e30-3b091f7a6d23.png' width='30'>  <img src='https://user-images.githubusercontent.com/37377831/56475037-c0815580-647a-11e9-8493-80f33608095b.png' width='30'>  |  [Here](https://github.com/SarpongAbasimi/oystercard/blob/master/spec/oyster_spec.rb) & [Here](https://github.com/SarpongAbasimi/rps-challenge/blob/master/spec/features/rps_spec.rb) |
|JavaScript       | <img src='https://user-images.githubusercontent.com/37377831/57584362-4882da00-74d2-11e9-8d82-4439680f50b3.png' width='30'> <img src='https://user-images.githubusercontent.com/37377831/57584458-643ab000-74d3-11e9-9551-827bf77f6adb.png' width='30'>| [Here](https://github.com/SarpongAbasimi/bowling-challenge/blob/master/jasmine-standalone-3/spec/BowlingSpec.js) & [Here](https://github.com/SarpongAbasimi/REST-API-with-Express/blob/master/test/controllers/registration.test.js)|
|Python | <img src='https://user-images.githubusercontent.com/37377831/57584502-1ecab280-74d4-11e9-97cc-8eedeefe30c0.png' width='60'> | [Here](https://github.com/SarpongAbasimi/BowlingScoreCardPython) & [Here](https://github.com/SarpongAbasimi/FizzBuzz-Python-JavaScript-More-)|

<h4 align='center'>
Evidence Collect Together To Prove To MySelf That I have Achieved This Goal.
<h4>
 
- My TDD process.
  - [Asyn TDD with Makers Coach Alice.](https://github.com/SarpongAbasimi/TestingWithJest)
  - [Process Review](https://github.com/SarpongAbasimi/ProcessWorkShopKatas)
  - [FizzBuzz Python](https://github.com/SarpongAbasimi/FizzBuzz-Python-JavaScript-More-)
  - [FizzBuzz JavaScript](https://github.com/SarpongAbasimi/FizzBuzz-Python-JavaScript-More-/tree/master/fizzBuzzJs)
  - [Bowling Challenge JavaScript](https://github.com/SarpongAbasimi/bowling-challenge)
  - [Bowling Challenge Python Attempt](https://github.com/SarpongAbasimi/BowlingScoreCardPython)
  - [Thermostat App](https://github.com/SarpongAbasimi/ThermostatJs).

- Link to process.
  - [Process review Kata](https://github.com/SarpongAbasimi/ProcessWorkShopKatas)

- Screen recording of me using this process during a process review workshop.
  - [Get Middle String](https://drive.google.com/file/d/1D9L_BFuC5YJjwWv0HVcRlxIjvZZZ6w-H/view?usp=sharing)

- Commit histories that tell the test-driven process story of my applications

- Link to Bowling Scorecard
- Link to Thermostat commit history


<h4 align='center'>
Feedback On TDD.
<h4>

<h4 align='center'>
  Completed Projects Using TDD.
<h4>

- [Oystercard Challenge](https://github.com/SarpongAbasimi/oystercard).
- [Airport Challenge](https://github.com/SarpongAbasimi/airport_challenge).
- [TakeAway Challenge](https://github.com/SarpongAbasimi/takeaway-challenge).
- [Rock Paper Scissors](https://github.com/SarpongAbasimi/rps-challenge).
- [Thermostat App](https://github.com/SarpongAbasimi/ThermostatJs).
