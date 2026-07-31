

# Module 1 — Découvrir l'algorithmique

# Leçon 1.4 — Différence entre un algorithme et un programme

---

# Objectifs d'apprentissage

À la fin de cette leçon, tu seras capable de :

* Définir ce qu'est un programme.
* Expliquer la différence entre un algorithme et un programme.
* Comprendre qu'un même algorithme peut être écrit dans plusieurs langages de programmation.
* Comprendre pourquoi il est important de concevoir un algorithme avant d'écrire du code.

---

# Introduction

Après avoir découvert les algorithmes, une question revient souvent :

> **Un algorithme est-il la même chose qu'un programme ?**

La réponse est **non**.

Ces deux notions sont étroitement liées, mais elles ne désignent pas la même chose.

Avant qu'un ordinateur puisse exécuter une solution, cette solution doit être écrite dans un langage de programmation.

C'est ce que l'on appelle un **programme**.

Dans cette leçon, tu découvriras la différence entre un algorithme et un programme, et pourquoi cette distinction est importante.

---

# Algorithme ou programme ?

Un **algorithme** décrit les étapes nécessaires pour résoudre un problème.

Un **programme** est l'implémentation de cet algorithme dans un langage de programmation afin que l'ordinateur puisse l'exécuter.

Autrement dit :

* **L'algorithme décrit la solution.**
* **Le programme permet à l'ordinateur d'exécuter cette solution.**

---

## 📊 INFOGRAPHIE 1 — Algorithme vs Programme

| Algorithme                     | Programme                                   |
| ------------------------------ | ------------------------------------------- |
| Décrit une solution            | Exécute la solution                         |
| Compréhensible par un humain   | Compréhensible par l'ordinateur             |
| Indépendant d'un langage       | Écrit dans un langage de programmation      |
| Peut être écrit en pseudo-code | Est écrit en Python, JavaScript, Java, etc. |

---

# Du problème au programme

Lorsque l'on crée une application, on suit généralement les étapes suivantes.

```text
🎯 Problème

↓

📝 Algorithme

↓

💻 Programme

↓

 Résultat
```

Le programme n'est donc pas créé directement.

Il est construit à partir d'un algorithme.

---

# Pourquoi l'ordinateur ne comprend-il pas directement l'algorithme ?

Les humains comprennent facilement des phrases comme :

* Demander le nom.
* Lire le nom.
* Afficher « Bonjour ».

Mais un ordinateur ne comprend pas le français.

Il comprend uniquement des instructions écrites selon les règles d'un langage de programmation.

C'est pourquoi l'algorithme doit être écrit dans un langage comme Python ou JavaScript avant de pouvoir être exécuté.

---

## 📊 INFOGRAPHIE 2 — L'humain et l'ordinateur

```text
👤 Humain

"Afficher Bonjour"

        │

        ▼

😊 Comprend

────────────────────

💻 Ordinateur

"Afficher Bonjour"

        │

        ▼

 Ne comprend pas

↓

Python / JavaScript

↓

 Comprend
```

---

# Une comparaison simple

Imagine que tu souhaites construire une maison.

Tu commences par réaliser un plan.

Le plan explique où placer les murs, les portes et les fenêtres.

Ensuite, les ouvriers utilisent ce plan pour construire la maison.

En informatique :

* **L'algorithme est le plan.**
* **Le programme est la construction réalisée en suivant ce plan.**

Sans plan, construire correctement devient beaucoup plus difficile.

---

# Exemple

Imaginons que nous voulions saluer un utilisateur.

## L'algorithme

1. Demander le nom.
2. Lire le nom.
3. Afficher « Bonjour » suivi du nom.

Cet algorithme est facile à comprendre pour un humain.

Mais l'ordinateur ne peut pas encore l'exécuter.

Il faut maintenant l'écrire dans un langage de programmation.

---

## 📊 INFOGRAPHIE 3 — De l'algorithme au programme

```text
📝 Algorithme

↓

🐍 Python

↓

💛 JavaScript

↓

☕ Java

↓

💻 Programme exécutable
```

---

## Le programme en Python

```python
nom = input("Quel est votre nom ? ")
print("Bonjour", nom)
```

---

## Le programme en JavaScript

```javascript
const nom = prompt("Quel est votre nom ?");
console.log("Bonjour " + nom);
```

---

# Que remarques-tu ?

Les deux programmes ne sont pas écrits de la même manière.

Pourtant, ils réalisent exactement la même tâche.

Pourquoi ?

Parce qu'ils suivent **le même algorithme**.

La logique reste identique.

Seule la syntaxe change.

---

# Un algorithme, plusieurs langages

Le même algorithme peut être écrit dans de nombreux langages.

Par exemple :

* Python
* JavaScript
* Java
* C
* C++
* C#
* PHP
* Go
* Rust

Chaque langage possède sa propre syntaxe.

En revanche, la logique de l'algorithme reste la même.

C'est pourquoi apprendre l'algorithmique facilite ensuite l'apprentissage de nouveaux langages.

---

## 📊 INFOGRAPHIE 4 — Même algorithme

```text
          📝 Algorithme

                │

────────────────┼────────────────

🐍 Python

💛 JavaScript

☕ Java

⚙ C++

🦀 Rust

                │

                ▼

        Même résultat
```

---

# Pourquoi concevoir l'algorithme avant d'écrire le programme ?

Écrire directement du code sans avoir réfléchi au problème revient à construire une maison sans plan.

On risque de :

* oublier certaines étapes ;
* créer une solution incorrecte ;
* perdre du temps à corriger des erreurs ;
* devoir modifier une grande partie du programme.

Les développeurs expérimentés commencent donc par réfléchir à l'algorithme avant d'écrire du code.

---

## 📊 INFOGRAPHIE 5 — Avant ou après ?

```text
 Commencer par le code

Code

↓

Erreurs

↓

Corrections

↓

Temps perdu

────────────────────

 Commencer par l'algorithme

Algorithme

↓

Code

↓

Programme correct
```

---

# Penser comme un programmeur 🧠

Tu souhaites créer une application qui calcule la moyenne de trois notes.

Quelle est la meilleure démarche ?

A. Écrire immédiatement le code.

B. Réfléchir aux étapes nécessaires, puis écrire le programme.

La bonne réponse est **B**.

Un bon programme commence toujours par un bon algorithme.

---

# Exercice de réflexion

## Exercice 1

Associe chaque élément à la bonne réponse.

| Élément                                  | Réponse |
| ---------------------------------------- | ------- |
| Suite d'étapes pour résoudre un problème | ...     |
| Code Python                              | ...     |
| JavaScript                               | ...     |
| `print()`                                | ...     |

<details>
<summary>Réponses</summary>

* Suite d'étapes → Algorithme
* Code Python → Programme
* JavaScript → Langage de programmation
* `print()` → Instruction du langage Python

</details>

---

## Exercice 2

Vrai ou Faux ?

* Un algorithme peut être écrit en Python.
* Deux programmes différents peuvent utiliser le même algorithme.
* Un programme est directement compréhensible par l'ordinateur.
* Tous les langages utilisent exactement la même syntaxe.

<details>
<summary>Réponses</summary>

* Faux (au sens où Python est un langage de programmation ; l'algorithme est d'abord une solution indépendante du langage)
* Vrai
* Vrai
* Faux

</details>

---

## Exercice 3

Explique avec tes propres mots la différence entre un algorithme et un programme.

---

# À retenir

* Un algorithme est une méthode pour résoudre un problème.
* Un programme est l'implémentation d'un ou plusieurs algorithmes dans un langage de programmation.
* Un même algorithme peut être écrit dans différents langages.
* La logique reste identique, seule la syntaxe change.
* Concevoir un algorithme avant de programmer permet de gagner du temps et de réduire les erreurs.
* **Tous les programmes commencent par un algorithme, mais un algorithme n'est pas encore un programme.**

---

# Vocabulaire

| Mot                          | Définition                                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Programme**                | Ensemble d'instructions écrites dans un langage de programmation et pouvant être exécutées par un ordinateur. |
| **Langage de programmation** | Langage utilisé pour écrire des programmes compréhensibles par un ordinateur.                                 |
| **Syntaxe**                  | Ensemble des règles d'écriture d'un langage de programmation.                                                 |
| **Implémentation**           | Action de transformer une solution ou un algorithme en un programme exécutable.                               |



# Exercice

Pour chaque affirmation, indique si elle parle d'un **algorithme** ou d'un **programme**.

1. Une suite d'étapes pour résoudre un problème.

............................................

2. Un code écrit en Python.

............................................

3. Une solution qui peut être utilisée dans plusieurs langages.

............................................

4. Un fichier contenant du code JavaScript.

............................................

5. Le plan permettant de créer une application.

............................................

---

# Réponses

1. Algorithme.

2. Programme.

3. Algorithme.

4. Programme.

5. Algorithme.

---

# Quiz

### 1. Qu'est-ce qu'un programme ?

A. Une recette de cuisine.

B. Un algorithme écrit dans un langage de programmation.

C. Une liste de problèmes.

D. Un ordinateur.

 **Réponse : B**

---

### 2. Quelle est la principale différence entre un algorithme et un programme ?

A. Il n'y en a aucune.

B. L'algorithme est une méthode de résolution, le programme est son écriture dans un langage de programmation.

C. Le programme est toujours plus court.

D. L'algorithme est exécuté par un humain uniquement.

 **Réponse : B**

---

### 3. Un même algorithme peut-il être écrit en Python et en JavaScript ?

A. Non.

B. Oui.

C. Seulement en Python.

D. Seulement en JavaScript.

 **Réponse : B**

---

### 4. Pourquoi est-il conseillé de concevoir un algorithme avant de programmer ?

A. Pour écrire plus de lignes de code.

B. Pour mieux organiser la solution et éviter des erreurs.

C. Pour rendre l'ordinateur plus rapide.

D. Pour installer un nouveau logiciel.

 **Réponse : B**

---

### 5. Que change-t-on lorsqu'on passe d'un programme Python à un programme JavaScript ?

A. Le problème à résoudre.

B. La logique de l'algorithme.

C. La syntaxe utilisée pour écrire le programme.

D. Le résultat attendu.

 **Réponse : C**

---

## 📌 Transition vers la prochaine leçon

Tu connais maintenant la différence entre un **algorithme** et un **programme**. Dans la prochaine leçon, nous verrons **comment un ordinateur exécute un algorithme**, étape par étape. Tu découvriras pourquoi il est indispensable de donner des instructions claires, précises et dans le bon ordre pour obtenir le résultat attendu.


#############################################################################################################################################################################################################


# Modil 1 — Dekouvri algoritmik

# Leson 1.4 — Diferans ant yon algoritm ak yon pwogram

---

# Objektif aprantisaj

Lè w fini leson sa a, w ap kapab:

* Eksplike diferans ki genyen ant yon algoritm ak yon pwogram.
* Konprann poukisa yon algoritm pa ka egzekite dirèkteman pa yon òdinatè.
* Konprann kijan yon algoritm vin tounen yon pwogram.
* Konprann ke menm algoritm lan ka ekri nan plizyè langaj pwogramasyon.
* Idantifye si yon egzanp se yon algoritm oswa yon pwogram.

---

# Entwodiksyon

Nan leson anvan yo, ou te aprann kijan pou ekri yon algoritm pou rezoud yon pwoblèm.

Men, gen yon kestyon ki enpòtan anpil.

> **Èske yon algoritm ase pou òdinatè a fè travay la?**

Ann pran egzanp sa a.

```text
1. Li de nonb.
2. Fè adisyon an.
3. Afiche rezilta a.
```

Nou menm, nou konprann etap sa yo san pwoblèm.

Men, èske yon òdinatè kapab li algoritm sa a dirèkteman?

Repons lan se **Non**.

Poukisa?

Paske òdinatè a pa konprann lang nou itilize chak jou.

Li bezwen enstriksyon ki ekri nan yon lang li kapab travay avèk.

Se la **pwogram** antre an jwèt.

Nan leson sa a, ou pral dekouvri diferans ki genyen ant yon algoritm ak yon pwogram, epi ou pral konprann kijan youn vin tounen lòt la.


# Kisa yon algoritm ye?

Yon algoritm se yon seri etap ki montre kijan pou rezoud yon pwoblèm oswa reyalize yon objektif.

Li eksplike **kisa pou fè**, san li pa bezwen itilize yon langaj pwogramasyon.

Pa egzanp:

```text
1. Li de nonb.
2. Fè adisyon an.
3. Afiche rezilta a.
```

Sa se yon algoritm.

Li montre etap yo, men li pa ekri nan Python, JavaScript oswa nenpòt lòt langaj.

![Description](https://api.tizekode.com/media/algorithm/discover_algorithm/algorit.png)


# Kisa yon pwogram ye?

Yon pwogram se **yon algoritm ki ekri nan yon langaj pwogramasyon** pou yon òdinatè kapab prepare epi egzekte li.

Sa vle di algoritm lan pa chanje.

Se sèlman fason nou ekri li ki chanje.

Pa egzanp, algoritm nou te wè a ka ekri an Python.

```python
a = int(input("Premye nonb: "))
b = int(input("Dezyèm nonb: "))

print(a + b)
```

Koulye a, sa pa yon algoritm ankò.

Se yon **pwogram**.

Paske li ekri nan yon langaj pwogramasyon.

![Description](https://api.tizekode.com/media/algorithm/discover_algorithm/pwogram.png)


# Diferans ant yon algoritm ak yon pwogram

Anpil moun panse de mo sa yo vle di menm bagay.

Men se pa vre.

Yo gen yon relasyon sere, men yo pa menm.

| Algoritm                                | Pwogram                                          |
| --------------------------------------- | ------------------------------------------------ |
| Yon solisyon pou yon pwoblèm            | Yon algoritm ki ekri nan yon langaj pwogramasyon |
| Ekri ak etap ki fasil pou moun konprann | Ekri ak sentaks yon langaj                       |
| Pa depann de okenn langaj               | Depann de yon langaj pwogramasyon                |
| Ka ekri sou papye                       | Ekri pou òdinatè kapab egzekte li                |

💡 **Lide kle**

> **Yon pwogram toujou soti nan yon algoritm. Men, yon algoritm pa oblije tounen yon pwogram.**

# Yon algoritm ka ekri nan plizyè langaj

Ann reprann algoritm nou te wè a.

```text
1. Li de nonb.
2. Fè adisyon an.
3. Afiche rezilta a.
```

Sa a se algoritm lan.

Li eksplike **sa pou fè**, men li pa di **kijan pou ekri li nan yon langaj pwogramasyon**.

Ann wè kijan menm algoritm sa ka ekri nan de langaj diferan.


## Menm algoritm lan an Python

```python
a = int(input("Premye nonb: "))
b = int(input("Dezyèm nonb: "))

print(a + b)
```


## Menm algoritm lan an JavaScript

```javascript
const a = Number(prompt("Premye nonb:"));
const b = Number(prompt("Dezyèm nonb:"));

console.log(a + b);
```


Pran kèk segonn pou obsève de pwogram sa yo.

Yo pa ekri menm jan.

Gen kèk mo ki diferan.

Gen kèk senbòl ki diferan.

Men, yo fè egzakteman menm travay la.

Sa vle di:

* **Langaj la chanje.**
* **Algoritm lan pa chanje.**

Se poutèt sa menm algoritm lan ka ekri nan Python, JavaScript, Java, C++ oswa anpil lòt langaj pwogramasyon.

![Description](https://api.tizekode.com/media/algorithm/discover_algorithm/menm_lojik_langaj_diferan.png)



💡 **Lide kle**

> **Yon algoritm se lide a. Langaj pwogramasyon an se fason nou ekri lide sa a pou òdinatè a kapab egzekte li.**


# Poukisa nou ekri algoritm anvan nou ekri kòd?

Ann pran yon lòt egzanp.

Imajine ou vle konstwi yon kay.

Èske mason yo kòmanse bati kay la san okenn plan?

Non.

Anvan yo mete premye blòk la, yo bezwen yon plan ki montre kijan kay la dwe konstwi.

Plan sa a ede tout moun konprann sa pou yo fè.

Nan pwogramasyon, se menm bagay la.

Anvan yon pwogramè kòmanse ekri kòd, li reflechi sou algoritm lan.

Algoritm lan se plan an.

Pwogram nan se aplikasyon plan sa a nan yon langaj pwogramasyon.

![Description](https://api.tizekode.com/media/algorithm/discover_algorithm/plan_ak_kay.png)



Remake byen.

Plan an pa kay la.

Men, san plan an, li pi difisil pou konstwi kay la.

Se menm jan an tou:

Algoritm lan pa pwogram nan.

Men, yon bon algoritm fè li pi fasil pou ekri yon bon pwogram.


## 👨🏽‍💻 Konsèy pwogramè

Lè yon pwoblèm sanble konplike, pa prese louvri editè kòd ou.

Pran kèk minit pou ekri algoritm lan sou papye oswa sou yon tablo.

Lè lojik la klè, ekri pwogram nan ap vin pi fasil epi w ap fè mwens erè.


## ⚠ Erè debutan

Anpil moun ki kòmanse aprann pwogramasyon panse premye etap la se ekri kòd.

Se pa sa bon pwogramè yo fè.

Yo kòmanse pa konprann pwoblèm nan.

Apre sa, yo ekri algoritm lan.

Se sèlman lè algoritm lan pare yo kòmanse ekri pwogram nan.

Sa ede yo travay pi vit epi evite anpil erè.


# Soti nan pwoblèm rive nan pwogram

Koulye a, ann mete tout sa nou aprann yo ansanm.

Lè ou vle kreye yon pwogram, ou suiv chemen sa a:

```text
🎯 Pwoblèm

        │

        ▼

📝 Algoritm

        │

        ▼

💻 Pwogram

        │

        ▼

 Rezilta
```

Chak etap gen yon wòl enpòtan.

Ou pa ka sote algoritm lan si ou vle kreye yon pwogram ki byen òganize.

💡 **Lide kle**

> **Pwoblèm nan montre sa ou vle rezoud. Algoritm lan montre kijan pou rezoud li. Pwogram nan pèmèt òdinatè a egzekte solisyon an.**

# Egzèsis

Kounye a, se ou menm ki pral mete sa ou aprann yo an pratik.

Pran tan pou reflechi anvan ou gade repons yo.


## Egzèsis 1 — Algoritm oswa Pwogram?

Pou chak egzanp, ekri si se yon **algoritm** oswa yon **pwogram**.

### Egzanp A

```text
1. Li de nonb.
2. Fè adisyon an.
3. Afiche rezilta a.
```


### Egzanp B

```python
print("Bonjou")
```


### Egzanp C

```javascript
console.log("Bonjou");
```


### Egzanp D

> 1. Louvri navigatè a.
>
> 2. Antre adrès sit entènèt la.
>
> 3. Peze **Enter**.


<details>
<summary>Repons</summary>

A → Algoritm

B → Pwogram

C → Pwogram

D → Algoritm

</details>


# Egzèsis 2 — Menm algoritm lan

Gade algoritm sa a.

```text
1. Mande non itilizatè a.
2. Li non an.
3. Afiche mesaj "Bonjou".
```

### Kesyon

* Èske algoritm sa a ka ekri nan Python?
* Èske li ka ekri nan JavaScript?
* Èske algoritm lan ap chanje?

<details>
<summary>Repons</summary>

Wi.

Li ka ekri nan Python, JavaScript oswa nenpòt lòt langaj.

Se sèlman langaj la ki chanje.

Algoritm lan rete menm jan an.

</details>


# Egzèsis 3 — Chèche algoritm lan

Gade pwogram Python sa a.

```python
age = int(input("Laj ou: "))

if age >= 18:
    print("Ou granmoun.")
else:
    print("Ou poko granmoun.")
```

San ekri okenn kòd, dekri algoritm ki dèyè pwogram sa a.

💡 **Konsèy**

Pa reflechi sou sentaks Python an.

Reflechi sèlman sou etap yo.



<details>
<summary>Yon solisyon posib</summary>

1. Mande laj itilizatè a.
2. Li laj la.
3. Si laj la pi gran oswa egal ak 18, afiche **"Ou granmoun."**
4. Sinon, afiche **"Ou poko granmoun."**

</details>



# Egzèsis 4 — Ranpli chemen an

Ranpli dyagram sa a.

```text
🎯 _______

      │

      ▼

📝 _______

      │

      ▼

💻 _______

      │

      ▼

 Rezilta
```

<details>
<summary>Repons</summary>

Pwoblèm

↓

Algoritm

↓

Pwogram

</details>



#  Egzèsis 5 — Vrè oswa Fo?

Ekri **Vrè** oswa **Fo**.

1. Yon algoritm se yon pwogram.

2. Yon pwogram se yon algoritm ki ekri nan yon langaj pwogramasyon.

3. Menm algoritm lan ka ekri nan plizyè langaj.

4. Yon òdinatè ka egzekte yon algoritm ki ekri sou papye.

5. Li pi bon reflechi sou algoritm lan anvan ou ekri pwogram nan.



<details>
<summary>Repons</summary>

1.  Fo

2.  Vrè

3.  Vrè

4.  Fo

5.  Vrè

</details>


# Rezime

Nan leson sa a, ou dekouvri ke yon **algoritm** ak yon **pwogram** pa menm bagay.

Yon algoritm se yon seri etap ki montre kijan pou rezoud yon pwoblèm.

Yon pwogram se algoritm sa a ki ekri nan yon langaj pwogramasyon pou òdinatè a kapab egzekte li.

Ou aprann tou ke menm algoritm lan ka ekri nan plizyè langaj diferan.

Sa ki chanje se **langaj la**.

Sa ki pa chanje se **lojik algoritm lan**.

Anfen, ou wè poukisa bon pwogramè yo toujou reflechi sou algoritm lan anvan yo kòmanse ekri kòd.



# Sa pou sonje

 Yon algoritm se yon solisyon pou yon pwoblèm.

 Yon pwogram se yon algoritm ki ekri nan yon langaj pwogramasyon.

 Menm algoritm lan ka ekri nan plizyè langaj.

 Òdinatè a egzekte pwogram nan, pa algoritm ki ekri sou papye.

 Yon bon algoritm fè li pi fasil pou ekri yon bon pwogram.



# Vokabilè

| Mo                      | Definisyon                                                                       |
| ----------------------- | -------------------------------------------------------------------------------- |
| **Algoritm**            | Yon seri etap ki montre kijan pou rezoud yon pwoblèm.                            |
| **Pwogram**             | Yon algoritm ki ekri nan yon langaj pwogramasyon pou òdinatè a kapab egzekte li. |
| **Langaj pwogramasyon** | Yon lang ki pèmèt moun ekri pwogram pou òdinatè.                                 |
| **Kòd**                 | Enstriksyon yo ekri nan yon langaj pwogramasyon.                                 |
| **Sentaks**             | Règ pou ekri kòd nan yon langaj pwogramasyon.                                    |

