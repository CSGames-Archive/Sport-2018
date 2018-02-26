# Compétition sportive des CS Games 2018

## FR

### Déroulement de la compétition

Cinq équipes à la fois, vous serez mis face à face avec le mur d'escalade. Votre but? Vous créer un chemin vers le haut du mur. Vous y trouverez un indice qui vous aidera à résoudre un défi.

Chaque indice n'est en fait qu'une partie manquante d'un segment d'un URL qui ressemble à ceci: `https://cs-games-18-sport.herokuapp.com/i-have-a-${missingSegment}`. Ce qui est retourné par ces URLs peut vous mener à de grandes récompenses!

En attendant patiemment votre tour pour grimper, vous serez confrontés à cinq défis algorithmiques. Commencez à travailler sur vos solutions jusqu'à ce que vous ne puissiez pas aller plus loin.

Chaque défi est composé de deux parties, et est complété après avoir obtenu la bonne réponse à chacune de ces parties. Le premier est réalisable sans aucune compétence d'escalade, mais le second exige toute la force que peuvent vous donner vos avant-bras.

Au total, vous pourrez trouver jusqu'à 10 réponses. Chaque fois que vous en trouverez une, allez avertir le superviseur pour la faire valider. Toutes vos réponses doivent être validées avant la fin du temps imparti.

L'équipe avec le plus de bonnes réponses gagne. Vos performances d'escalade sont importantes, car elles sont également utilisées en cas de bris d'égalité.

LET'S GO!!!

### Défis

#### Défi 1 : WTB Formula

- Partie 1 : Voici 3 formules, dont chacune manque 5 opérateurs : `73 _ 41 _ 58 _ 83 _ 7 _ 92 _ 6 _ 56 _ 768 _ 6 = -57,954`, `125 _ 538 _ 26 _ 4 _ 35 _ 37 _ 125 _ 538 _ 26 _ 3 = -4208` and `37 _ 274 _ 36 _ 12 _ 7 _ 28 _ 37 _ 274 _ 36 * 12 = -2272`. Nous savons que tous ces opérateurs sont identiques pour chaque formule, dans le même ordre et contenus dans les suivants : `+`, `-` et ` * `. Trouvez les cinq opérateurs manquants.

- Partie 2 : Le premier problème d'escalade vous aidera à compléter l'URL `https://cs-games-18-sport.herokuapp.com/i-eat-my-${THING_TO_EAT}`. Nous avons entendu dire qu'il pourrait mener vers des chiffres très importants.

#### Défi 2 : Keine besonderen Ereignisse

- Partie 1 : Les allemands envoient des messages cryptés importants. On vous a demandé de déchiffrer celui-ci: `8$ '! !8".,$.5$1'$1$`. Le savant précédent a laissé la note suivante : _Vous devez commencer à 32_. S'il-vous-plaît, rendez une faveur à l'humanité, et sauvez tout le monde en décryptant ce message.

- Partie 2 : Quel message coquin, le Führer a été un mauvais garçon! Nos sources nous ont indiqué que le bon message pourrait être renvoyé par l'URL suivant: `https://cs-games-18-sport.herokuapp.com/i-drive-my-${THING_TO_DRIVE}`.

#### Défi 3 : Un peu de fonctionnel

- Partie 1 : Le code suivant a été trouvé :

```javascript
const list = [[12, 74], [93, 42], [72], [32, 74, 94]]

const result = mysteriousAlgorithm(list, (x) => x + 10).reduce((x1, x2) => x1 + x2 + 3);

console.log(result);

>'594'
```

Nous ne connaissons pas l'implémentation de la fonction `mysteriousAlgorithm`, mais nous savons que c'est une fonction de programmation fonctionnelle populaire. Pourriez-vous nommer cette fonction?

- Partie 2 : Il manque une petite partie à l'URL suivant : `https://cs-games-18-sport.herokuapp.com/i-play-the-${THING_TO_PLAY}`. Il semblerait qu'il mène vers une précieuse liste...

#### Défi 4 : Got Money

- Partie 1 : Un investisseur vous demande de calculer son rendement annuel, considérant qu'il a commencé à investir avec 57 936$. Il vous a donné les transactions qu'il a effectuées au cours des 3 dernières années.

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
         "price": 152.03
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
         "price": 177.57
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
         "price": 169.58
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
         "price": 204.62
      }
   }
]
```

** Les rumeurs disent que vous devriez coder un algorithme calculant le rendement au lieu de le faire à bras.

- Partie 2 : Revirement de situation. L'investisseur veut finalement que vous calculiez son rendement pendant 15 ans. Il a fait trop de transactions, elles ne peuvent pas être listées ici. Il vous a donné cet URL: `https://cs-games-18-sport.herokuapp.com/i-sit-down-on-my-${THING_TO_SIT}`. Trouvez-le, et encore une fois, calculez son rendement annuel.

#### Défi 5 : Please Obi-Wan Kenobi, you're my only hope

- Partie 1 : La princesse Leia demande à Obi-Wan Kenobi de l'aider à comprendre les _cron expressions_ suivantes:

```
1) 0 7 19 ? * WED,SAT *
2) 0 11 5 ? 9 FRI#2 *
3) 0 0 0/7 1/1 * ? *
4) 0 0/59 * 1/1 * ? *
5) 0 53 11 ? 1/1 MON#3 *
6) 0 27 3 ? * TUE,THU,FRI,SUN *
7) 0 56 11 ? * MON-FRI *
8) 0 46 10 1/1 * ? *
9) 0 54 11 ? * MON,THU,SAT,SUN *
10) 0 15 15 1/1 * ? *
```

Elle a besoin de savoir laquelle sera la première à être exécutée, car elle a appris que cette dernière lancerait un missile vers l'Alliance rebelle et qu'elle devrait préparer ses défenses. La date courante est `2273-12-08T11:27:52.538Z`.

- Partie 2 : Connaissant la _cron job_ trouvée précédemment, et sachant aussi qu'elle fonctionnera jusqu'à `2273-12-18T11:53:12.628Z`, quelle sera la valeur de la variable `attacks` sachant que la _cron job_ exécute l'algorithme suivant:

```javascript
function destroyEverything() {
   attacks += 5;
}
```

La valeur initiale de la variable `attacks` est retournée par l'URL suivant : `https://cs-games-18-sport.herokuapp.com/i-drink-a-${THING_TO_DRINK}`.


**N'OUBLIEZ PAS D'ALLER FAIRE VÉRIFIER VOS RÉPONSES PAR LES SUPERVISEURS AVANT LA FIN DE LA COMPÉTITION!!!**


## EN

### Competition flow

Five teams at a time, you will be put face to face with the climbling wall. Your goal? Manage your way to the top. You will find a clue that will help you solve a challenge.

Each clue is actually only a missing part of a segment of an URL that looks like the following : `https://cs-games-18-sport.herokuapp.com/i-have-a-${missingSegment}`. What is returned by these URLs might lead you to great rewards!

While patiently waiting your turn to climb, you will be confronted to five algorithmic challenges. Start working on your solutions until you can't go any further.

Every challenge consists of two parts, and is completed after you get the correct answer for each part. The first one is achievable without any climbing skills, but the second one requires all the strength your forearms provide you.

In total, you will be able to find up to 10 answers. Each time you find one, go tell the supervisor in charge. All your answers need to be validated before the timer finishes.

The team with the most correct answers wins. Your climbing performances are important, since it will also act in case of tie break.

Let's GO!!!

### Challenges

#### Challenge 1 : WTB Formula

- Part 1 : Here are three formulas, each one missing its operators : `73 _ 41 _ 58 _ 83 _ 7 _ 92 _ 6 _ 56 _ 768 _ 6 = -57,954`, `125 _ 538 _ 26 _ 4 _ 35 _ 37 _ 125 _ 538 _ 26 _ 3 = -4208` and `37 _ 274 _ 36 _ 12 _ 7 _ 28 _ 37 _ 274 _ 36 * 12 = -2272`. We know all these operators are the same for each formula, in the same order, and contained in the followings : `+`, `-` and `*`. Find the five missing operators.

- Part 2 : The first climbing problem will help you complete the URL `https://cs-games-18-sport.herokuapp.com/i-eat-my-${THING_TO_EAT}`. We heard it may lead it important numbers.

#### Challenge 2 : Keine besonderen Ereignisse

- Part 1 : The germans are sending important encrypted messages. You've been asked to decrypt this one : `8$ '! !8".,$.5$1'$1$`. The previous scientist left the following note : _You need to start at 32_. Make humanity a favor, and save everybody by decrypting the message.

- Part 2 : What a noughty message, the Führer has been a bad boy! Our sources told us that the good message could be returned by the following URL : `https://cs-games-18-sport.herokuapp.com/i-drive-my-${THING_TO_DRIVE}`.

#### Challenge 3 : A bit of functional

- Part 1 : The following code has been found :

```javascript
const list = [[12, 74], [93, 42], [72], [32, 74, 94]]

const result = mysteriousAlgorithm(list, (x) => x + 10).reduce((x1, x2) => x1 + x2 + 3);

console.log(result);

>'594'
```

We don't know the implementation of the function `mysteriousAlgorithm`, but we know it is a popular functional programming function. Could you name this function?

- Part 2 : The following URL is missing a little part : `https://cs-games-18-sport.herokuapp.com/i-play-the-${THING_TO_PLAY}`. We heard it might lead to a precious list...

#### Challenge 4 : Got Money

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
         "price": 152.03
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
         "price": 177.57
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
         "price": 169.58
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
         "price": 204.62
      }
   }
]
```

** Rumors say you should code an algorithm instead of calculating with a calculator.

- Part 2 : Plot twist. The investor finally wants you to calculate his yield for 15 years. He made too many transactions, they can't be listed here. He gave you this piece of URL : `https://cs-games-18-sport.herokuapp.com/i-sit-down-on-my-${THING_TO_SIT}`. Find it, and once again, calculate his annual yield.

#### Challenge 5 : Please Obi-Wan Kenobi, you're my only hope

- Part 1 : Obi-Wan Kenobi is asked by princess Leia to help her understand the following cron expressions :

```
1) 0 7 19 ? * WED,SAT *
2) 0 11 5 ? 9 FRI#2 *
3) 0 0 0/7 1/1 * ? *
4) 0 0/59 * 1/1 * ? *
5) 0 53 11 ? 1/1 MON#3 *
6) 0 27 3 ? * TUE,THU,FRI,SUN *
7) 0 56 11 ? * MON-FRI *
8) 0 46 10 1/1 * ? *
9) 0 54 11 ? * MON,THU,SAT,SUN *
10) 0 15 15 1/1 * ? *
```

She needs to know which one will be executed first, because she learned that it will throw a missile at the Rebel Alliance and they need to prepare their defenses. The current date is `2273-12-08T11:27:52.538Z`.

- Part 2 : Knowing the previously found cron job, and also knowing that it will run until `2273-12-18T11:53:12.628Z`, what will be the value of the variable `attacks` knowing that the cron job executes the following algorithm :

```javascript
function destroyEverything() {
   attacks += 5;
}
```

The initial value of the `attacks` variable is returns by the following URL : `https://cs-games-18-sport.herokuapp.com/i-drink-a-${THING_TO_DRINK}`


**DON'T FORGET TO HAVE THE SUPERVISOR VERIFY ALL YOUR ANSWERS BEFORE THE END OF THE TIME!!!**
