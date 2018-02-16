# CS Games 2018's sport competition
## Competition description
### FR
```
{
"name": "Grimpez pour sauver les pingouins",
"description": "En tant que pingouin, nos mouvements sont limités. Nous allons avoir besoin de votre aide. Prouvez que vous avez un esprit sain dans un corps sain! Soyez prêt à suer dans ce challenge, et préparez vos avant-bras à des heures de souffrance!",
"participants": 2,
"languages": "Désodorisant, des vêtements sportifs, apportez votre laptop et choisissez le language de votre choix!",
"weighting": "7%"
}
```
### EN
```
{
"name": "Climb to save the penguins",
"description": "As penguins, some of our movements are limited. We are going to need your help. Prove that you have an healthy mind and body! Get ready to sweat in this challenge, and prepare your forearms for hours of suffering!",
"participants": 2,
"languages": "Deodorant, indoor sportswear, bring your laptop and choose the language of your choice!",
"weighting": "7%"
}
```
## Competition flow

### FR

Cinq équipes à la fois, vous serez mis face à face avec le mur d'escalade. Votre but? Vous créer un chemin vers le haut du mur. Vous y trouverez un indice qui vous aidera à résoudre un défi.

Chaque indice n'est en fait qu'une partie manquante d'un segment d'un URL qui ressemble à ceci: `https://cs-games-18-sport.herokuapp.com/i-have-a-${missingSegment}`. Ce qui est retourné par ces URLs peut vous mener à de grandes récompenses!

En attendant patiemment votre tour pour grimper, vous serez confrontés à cinq défis algorithmiques. Commencez à travailler sur vos solutions jusqu'à ce que vous ne puissiez pas aller plus loin.

Chaque défi est composé de deux parties, et est complété après avoir obtenu la bonne réponse à chacune de ces parties. Le premier est réalisable sans aucune compétence d'escalade, mais le second exige toute la force que vous peuvent vous procurer vos avant-bras.

Au total, vous pourrez trouver jusqu'à 10 réponses. Chaque fois que vous en trouverez une, allez avertir le superviseur pour la faire valider. Toutes vos réponses doivent être validées avant la fin du temps imparti.

L'équipe avec le plus de réponses correctes gagne. Vos performances d'escalade sont importantes, car elles agissent également en cas de bris d'égalité.

LET'S GO!!!

### EN

Five teams at a time, you will be put face to face with the climbling wall. Your goal? Manage your way to the top. You will find a clue that will help you solve a challenge.

Each clue is actually only a missing part of a segment of an URL that looks like the following : `https://cs-games-18-sport.herokuapp.com/i-have-a-${missingSegment}`. What is returned by these URLs might lead you to great rewards!

While patiently waiting your turn to climb, you will be confronted to five algorithmic challenges. Start working on your solutions until you can't go any further.

Every challenge consists of two parts, and is completed after you get the correct answer for each part. The first one is achievable without any climbing skills, but the second one requires all the strength your forearms provide you.

In total, you will be able to find up to 10 answers. Each time you find one, go tell the supervisor in charge. All your answers need to be validated before the timer finishes.

The team with the most correct answers wins. Your climbing performances are important, since it will also act in case of tie break.

Let's GO!!!

## Challenges

### Challenge 1 : WTB Formula

- Part 1 : Here are three formulas, each one missing its operators : `84 _ 27 _ 42 _ 82 _ 62 _ 9 = 1674`, `8 _ 63 _ 38 _ 2 _ 41 _ 29 = -232` and `49 _ 20 _ 9 _ 22 _ 86 _ 2 = -990`. We know all these operators are the same for each formula, in the same order, and contained in the followings : `+`, `-`, `*`, `/`, `mod`, `//`, `(` and `)`. Find the five missing operators.

- Part 2 : The first climbing problem will help you complete the URL `https://cs-games-18-sport.herokuapp.com/i-eat-my-${THING_TO_EAT}`. We heard it may lead it important numbers.

### Challenge 2 : Keine besonderen Ereignisse

- Part 1 : The germans are sending important encrypted messages. You've been asked to decrypt this one : `8$ '! !8".,$.5$1'$1$`. The previous scientist left the following note : _You need to start at 32_. Make humanity a favor, and save everybody by decrypting the message.

- Part 2 : What a noughty message, the Führer has been a bad boy! Our sources told us that the good message could be returned by the following URL : `https://cs-games-18-sport.herokuapp.com/i-drive-my-${THING_TO_DRIVE}`.

### Challenge 3 :

- Part 1 : The following code has been found :

```
const list = [[12, 74], [93, 42], [72], [32, 74, 94]]

const result = mysteriousAlgorithm(list, (x) => x + 10).reduce((x1, x2) => x1 + x2 + 3);

console.log(result);

>'594'
```

We don't know the implementation of the function `mysteriousAlgorithm`, but we know it is a popular functional programming function. Could you name this function?

- Part 2 : The following URL is missing a little part : `https://cs-games-18-sport.herokuapp.com/i-play-the-${THING_TO_PLAY}`. We heard it might lead to a precious list...

### Challenge 4 : Pussy Money Weed

- Part 1 : An investor asks you to calculate his annual yield, considering he started investing with 57 936$. He gave you the transactions he made in the last 3 years.

```json
[
   {
      "buy": {
         "datetime": "2002-01-11T00:00:00.000Z",
         "price": 114.94
      },
      "number-of-actions": 86.0,
      "sell": {
         "datetime": "2002-03-19T00:00:00.000Z",
         "price": 117.45
      }
   },
   {
      "buy": {
         "datetime": "2002-03-25T00:00:00.000Z",
         "price": 113.61
      },
      "number-of-actions": 89.0,
      "sell": {
         "datetime": "2003-04-29T00:00:00.000Z",
         "price": 92.03
      }
   },
   {
      "buy": {
         "datetime": "2003-05-20T00:00:00.000Z",
         "price": 92.46
      },
      "number-of-actions": 89.0,
      "sell": {
         "datetime": "2003-06-02T00:00:00.000Z",
         "price": 97.35
      }
   },
   {
      "buy": {
         "datetime": "2003-06-24T00:00:00.000Z",
         "price": 98.52
      },
      "number-of-actions": 88.0,
      "sell": {
         "datetime": "2003-09-03T00:00:00.000Z",
         "price": 103.36
      }
   },
   {
      "buy": {
         "datetime": "2003-09-23T00:00:00.000Z",
         "price": 102.94
      },
      "number-of-actions": 88.0,
      "sell": {
         "datetime": "2003-10-15T00:00:00.000Z",
         "price": 104.99
      }
   },
   {
      "buy": {
         "datetime": "2003-10-24T00:00:00.000Z",
         "price": 103.58
      },
      "number-of-actions": 89.0,
      "sell": {
         "datetime": "2003-11-03T00:00:00.000Z",
         "price": 105.99
      }
   },
   {
      "buy": {
         "datetime": "2003-11-18T00:00:00.000Z",
         "price": 103.82
      },
      "number-of-actions": 91.0,
      "sell": {
         "datetime": "2003-12-08T00:00:00.000Z",
         "price": 107.57
      }
   },
   {
      "buy": {
         "datetime": "2004-02-04T00:00:00.000Z",
         "price": 112.84
      },
      "number-of-actions": 87.0,
      "sell": {
         "datetime": "2004-02-17T00:00:00.000Z",
         "price": 116.17
      }
   },
   {
      "buy": {
         "datetime": "2004-03-09T00:00:00.000Z",
         "price": 114.5
      },
      "number-of-actions": 88.0,
      "sell": {
         "datetime": "2004-09-02T00:00:00.000Z",
         "price": 112.58
      }
   },
   {
      "buy": {
         "datetime": "2004-09-23T00:00:00.000Z",
         "price": 110.95
      },
      "number-of-actions": 89.0,
      "sell": {
         "datetime": "2004-10-06T00:00:00.000Z",
         "price": 114.62
      }
   }
]
```

** Rumors say you should code an algorithm instead of calculating with a calculator.

- Part 2 : Plot twist. The investor finally wants you to calculate his yield for 15 years. He made too many transactions, they can't be listed here. He gave you this piece of URL : `https://cs-games-18-sport.herokuapp.com/i-sit-down-on-my-${THING_TO_SIT}`. Find it, and once again, calculate his annual yield.

### Challenge 5 : Please Obi-Wan Kenobi, you're my only hope

- Part 1 : Obi-Wan Kenobi is asked by princess Leia to help her understand the following cron expressions :

```
1) 0 7 19 ? * WED,SAT *
2) 0 11 5 ? 9 FRI#2 *
3) 0 0 0/7 1/1 * ? *
4) 0 0/426 * 1/1 * ? *
5) 0 53 11 ? 1/1 MON#3 *
6) 0 27 3 ? * TUE,THU,FRI,SUN *
7) 0 56 11 ? * MON-FRI *
8) 0 46 10 1/1 * ? *
9) 0 54 11 ? * MON,THU,SAT,SUN *
10) 0 15 15 1/1 * ? *
```

She needs to know which one will be executed first, because she learned that it will throw a missile at the Rebel Alliance and they need to prepare their defenses. The current date is `2273-12-08T11:27:52.538Z`.

- Part 2 : Knowing the previous cron job, and also knowing that it will run until `2273-12-18T11:53:12.628Z`, what will be the value of the variable `attacks` knowing that the cron job executes the following algorithm :

```
function destroyEverything() {
   attacks += 5;
}
```

The initial value of the `attacks` variable is returns by the following URL : `https://cs-games-18-sport.herokuapp.com/i-drink-a-${THING_TO_DRINK}`


**DON'T FORGET TO HAVE THE SUPERVISOR VERIFY ALL YOUR ANSWERS BEFORE THE END OF THE TIME!!!**
