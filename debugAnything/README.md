<h1 align='center'>
  I Can Debug Anything
</h1>

> What is Debugging?

- ``Debugging`` is the process of following a pattern to quickly and effectively resolve a bug in a system.
- ``A bug`` is like a **virus**, its sole purpose is to attack and stop a programme from functioning properly.

Being able to ``debug`` and thing, therefore means having the right processes to find the **source** of a bug in a code base and correcting the bug to allow a programme to function effectively in any language.

> Debugging is a **great** skill to have and in fact, I was once told that ``all great programmers are great debuggers``, which I didn't quite understand till I joined Makers.

During my time at Makers, I have realised that being able to debug an application is a skill on its own and it comes from the ability to

- Understand what is going on in a code base.
- Know the debugging tools for a particular language.
- Follow good programming principles and processes when crafting an application.

Thanks to The Lovely Coaches At Makers I came to understand that there are ``two`` main processes that one can following when debugging and they are
- **Getting visibility**
  - This means finding ways to see what exactly is happening within the application at various points.
  When something is not working as expected, it’s easy to assume that everything is broken. Taking the time to get visibility will ensure that base on the ``stack trace`` will ensure that the right place where the error occurred is found. This helps to gain a clear understanding of the problem and create a clear picture of its edges.

  > Tools I use to get visibility when working on an application includes ``chrome console``, ``IRB``, ``postman`` and ``ipython``.

- **Tighten the loop**
  - This is the ability to narrow down a problem after gaining visibility on it to find out the exact moment an unexpected behaviour occurred. In the process of doing this, it because clear the list of elements that were causing the bug. Even though it might seem like these first steps are pointless because the problem is “obvious,” often jumping into solving the problem too soon can lead to wasted time and effort, and to a partial or non-optimal solution.

  > Examples of when I used these debugging techniques to solve a bug in my code base [RPS](https://github.com/SarpongAbasimi/rps-challenge), [Thermostat](https://github.com/SarpongAbasimi/ThermostatJs), [MathsKata](https://medium.com/@1550707241489/javascript-math-sign-445cbf0127aa).


- My Evidence For Debugging.
  - In Week 3 at Makers we were given the task to create a ``Rock``, ``Paper``, ``Scissors`` for the weekend challenge. Whiles working on this project, I realised that my application was not working as wanted because of this issue.

  <img width="462" alt="Screen Shot 2019-04-21 at 14 17 21" src="https://user-images.githubusercontent.com/37377831/56472971-07605280-645d-11e9-8feb-01e1959ce248.png">

  <img width="415" alt="Screen Shot 2019-04-21 at 14 16 36" src="https://user-images.githubusercontent.com/37377831/56472961-ea2b8400-645c-11e9-8874-2043bc1f44f3.png">

  <img width="645" alt="Screen Shot 2019-04-21 at 14 16 50" src="https://user-images.githubusercontent.com/37377831/56472981-26f77b00-645d-11e9-9deb-5c0542b484a0.png">

  <img width="616" alt="Screen Shot 2019-04-21 at 14 17 01" src="https://user-images.githubusercontent.com/37377831/56472984-3c6ca500-645d-11e9-85d3-f9e67e53dbd8.png">

The method ``random_choice`` returned a random object from the array anytime it is called. This meant the object being returned by ``random_choice`` in the ``choice method`` was different from the object being returned by ``random_choice`` in the ``results method``. The returned value of these two methods was being used in the view to show the shape that the computer and the user had chosen and the winner of the game, but since they all were a different random choice the real winner of the game was sometimes wrong as illustrated the image below. 

<img width="404" alt="Screen Shot 2019-04-21 at 13 30 34" src="https://user-images.githubusercontent.com/37377831/56473077-21e6fb80-645e-11e9-8e0a-aac308a368ef.png">

- In order to solve this problem, I had to gain visibility by ``p`` out the results of the ``random_choice `` method. This allowed me to gather enough evidence on what was happening in the application later gave me the resources to solve this bug.

By ``p``ing the function, I was able to find the solution to the problem by adding the method shown below.
<img width="606" alt="Screen Shot 2019-04-21 at 17 17 35" src="https://user-images.githubusercontent.com/37377831/56473178-37105a00-645f-11e9-8c42-722adcbbd171.png">

=====================================

#### Summary

In several instances during my coding journey at ``Makers``, I have written lots of code and not always did I get the expected behaviours I wanted because of a bug.

> Note that I was able to track down these error thanks to TDD. ``Red``, ``Green``, ``Refactor``.

In order to resolve these bugs, I had to follow the ``stack trace`` given by the application and find ways of getting a clear view of what was going on in it by ``gaining visibility `` and ``tightening the loop`` on my methods. An example to a recent problem I faced while trying to connect ``Express.js`` with a ``React Application`` [Evidence](https://github.com/SarpongAbasimi/ConnectExpressBackEndToReactFrontEnd).

As time went by at ``Makers`` debugging an application has become normal and natural to me and it has become part of my processes. So the statement, I can debug anything means that I am able to understand what is the expected behaviour of a program or application and notice when this behaviour is not fulfiled. Then, I am able to make a clear assumption about why this unexpected error occurred and then find ways to mitigate these assumptions. 

<h4 align='center'>
Projects That Illustrates My Debugging Skills.
</h4>

- [ReactExpressApplication](https://github.com/SarpongAbasimi/ConnectExpressBackEndToReactFrontEnd).
- [NewsSummary](https://github.com/SarpongAbasimi/NewsSummaryApp).
- [ThermostartApp](https://github.com/SarpongAbasimi/ThermostatJs)

> A diagram from an [article](https://hackernoon.com/how-to-debug-any-problem-ac6f8a867fae) by ``Duncan Riach`` that also helped me understand what debugging is and how to debug anything.

![1*zr0dAx65hHcfirrmq5zEDg](https://user-images.githubusercontent.com/37377831/58765536-eadf2c00-856b-11e9-9f80-27ea6a0f9b34.png)