

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

✅ Résultat
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

❌ Ne comprend pas

↓

Python / JavaScript

↓

✅ Comprend
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
❌ Commencer par le code

Code

↓

Erreurs

↓

Corrections

↓

Temps perdu

────────────────────

✅ Commencer par l'algorithme

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

✅ **Réponse : B**

---

### 2. Quelle est la principale différence entre un algorithme et un programme ?

A. Il n'y en a aucune.

B. L'algorithme est une méthode de résolution, le programme est son écriture dans un langage de programmation.

C. Le programme est toujours plus court.

D. L'algorithme est exécuté par un humain uniquement.

✅ **Réponse : B**

---

### 3. Un même algorithme peut-il être écrit en Python et en JavaScript ?

A. Non.

B. Oui.

C. Seulement en Python.

D. Seulement en JavaScript.

✅ **Réponse : B**

---

### 4. Pourquoi est-il conseillé de concevoir un algorithme avant de programmer ?

A. Pour écrire plus de lignes de code.

B. Pour mieux organiser la solution et éviter des erreurs.

C. Pour rendre l'ordinateur plus rapide.

D. Pour installer un nouveau logiciel.

✅ **Réponse : B**

---

### 5. Que change-t-on lorsqu'on passe d'un programme Python à un programme JavaScript ?

A. Le problème à résoudre.

B. La logique de l'algorithme.

C. La syntaxe utilisée pour écrire le programme.

D. Le résultat attendu.

✅ **Réponse : C**

---

## 📌 Transition vers la prochaine leçon

Tu connais maintenant la différence entre un **algorithme** et un **programme**. Dans la prochaine leçon, nous verrons **comment un ordinateur exécute un algorithme**, étape par étape. Tu découvriras pourquoi il est indispensable de donner des instructions claires, précises et dans le bon ordre pour obtenir le résultat attendu.


#############################################################################################################################################################################################################


# Modil 1 — Dekouvri algoritmik

# Leson 1.4 — Diferans ant yon algoritm ak yon pwogram

---

# Objektif aprantisaj

Lè w fini leson sa a, ou ap kapab:

- Defini kisa yon pwogram ye.
- Eksplike diferans ki genyen ant yon algoritm ak yon pwogram.
- Konprann ke menm algoritm lan ka ekri nan plizyè langaj pwogramasyon.
- Konprann ke yon pwogram dwe prepare oswa tradui an langaj machin anvan òdinatè a ka egzekte li.
- Konprann poukisa li enpòtan pou prepare yon algoritm anvan ou ekri kòd.

---

# Entwodiksyon

Jiska kounye a, nou aprann ke yon algoritm se yon seri etap ki pèmèt rezoud yon pwoblèm.

Men, gen yon kestyon enpòtan.

> **Kijan yon òdinatè rive egzekite yon algoritm?**

Repons lan fèt an plizyè etap.

Premye etap la se reflechi sou pwoblèm nan epi prepare yon algoritm.

Apre sa, algoritm nan ekri nan yon langaj pwogramasyon tankou **Python**, **JavaScript**, **Java** oswa **C++**.

Lè algoritm nan ekri nan yon langaj pwogramasyon, li vin tounen yon **pwogram** (oswa **kòd sous**).

Men, travay la pa fini la.

Yon òdinatè pa konprann langaj pwogramasyon dirèkteman.

Li konprann sèlman **langaj machin**, sa vle di enstriksyon ki ekri an binè (0 ak 1).

Se poutèt sa, anvan processeur a (CPU) ka egzekite yon pwogram, pwogram nan dwe pase atravè yon etap preparasyon.

Tou depan de langaj pwogramasyon an, etap sa a ka fèt pa yon **konpilatè**, yon **entèprèt**, oswa yon lòt sistèm ki prepare pwogram nan pou processeur a.

Nan leson sa a, nou pral sitou aprann diferans ki genyen ant **algoritm** ak **pwogram**.

Nou pral etidye konpilatè, entèprèt ak langaj machin pi an detay nan yon lòt modil.

> **💡 Sa pou sonje**
>
> **Yon algoritm dekri etap pou rezoud yon pwoblèm.**
>
> **Yon pwogram se algoritm sa a ki ekri nan yon langaj pwogramasyon.**
>
> **Anvan òdinatè a egzekite pwogram nan, li dwe prepare oswa tradui an langaj machin.**

---

## 📊 ENFOGRAFI 17 — Depi pwoblèm rive jouk CPU a

### Objektif

Montre tout etap ki pèmèt yon òdinatè egzekite yon solisyon.

```text
🎯 Pwoblèm

        │

        ▼

📝 Algoritm

        │

        ▼

💻 Langaj pwogramasyon

        │

        ▼

📄 Pwogram (Kòd sous)

        │

        ▼

⚙ Konpilatè / Entèprèt

        │

        ▼

010101... (Langaj machin)

        │

        ▼

🖥 CPU egzekite enstriksyon yo
```

---

## 💡 Èske w te konnen?

Processeur yon òdinatè pa konprann Python, JavaScript oswa C++ dirèkteman.

Li konprann sèlman langaj machin.

Se poutèt sa tout pwogram dwe pase atravè yon etap preparasyon anvan òdinatè a ka egzekite yo.

---

# Kisa yon pwogram ye?

Yon **pwogram** se yon seri enstriksyon ki ekri nan yon langaj pwogramasyon.

Pwogram nan se fason nou ekri yon algoritm pou yon òdinatè kapab prepare epi egzekite li.

Nan lòt mo:

- **Algoritm lan** dekri etap pou rezoud yon pwoblèm.
- **Pwogram nan** se algoritm sa a ki ekri nan yon langaj pwogramasyon.

Yon menm algoritm ka ekri nan plizyè langaj diferan.

Se poutèt sa ou ka itilize **Python**, **JavaScript**, **Java**, **C++**, **Go** oswa anpil lòt langaj pou rezoud menm pwoblèm nan.

Sa ki chanje se sentaks langaj la.

Sa ki pa chanje se lojik algoritm nan.

---

# Yon konparezon ki fasil pou konprann

Ann pran yon egzanp tout moun konnen.

Ou vle konstwi yon kay.

Premye bagay ou bezwen se yon **plan**.

Plan an montre:

- ki kote mi yo pral ye;
- ki kote pòt yo pral ye;
- ki kote fenèt yo pral ye;
- ki jan tout kay la ap òganize.

Lè plan an pare, mason yo sèvi avè l pou konstwi kay la.

Nan enfòmatik, se menm prensip la.

- 📝 **Algoritm lan** se plan an.
- 💻 **Pwogram nan** se plan sa a ki ekri nan yon langaj pwogramasyon.
- ⚙️ **Konpilatè oswa entèprèt la** prepare pwogram nan pou òdinatè a ka egzekite li.

San yon plan, li difisil pou konstwi yon bon kay.

Menm jan an tou, san yon algoritm, li difisil pou devlope yon bon pwogram.

---

## 📊 ENFOGRAFI 18 — Plan kay vs Pwogram

```text
🏠 Kay

📐 Plan

        │

        ▼

👷 Konstriksyon

        │

        ▼

🏡 Kay fini

────────────────────────────

💻 Òdinatè

📝 Algoritm

        │

        ▼

📄 Pwogram

        │

        ▼

⚙ Konpilatè / Entèprèt

        │

        ▼

🖥 Egzekisyon
```

---

# Egzanp

Ann sipoze nou vle salye yon itilizatè.

Anvan nou ekri nenpòt kòd, nou reflechi sou etap yo.

## Algoritm

1. Mande itilizatè a non li.
2. Li non an.
3. Afiche mesaj **"Bonjou"** ansanm ak non an.

Algoritm sa a fasil pou yon moun konprann.

Men yon òdinatè pa konprann fraz sa yo dirèkteman.

Nou dwe ekri yo nan yon langaj pwogramasyon.

---

## Pwogram an Python

```python
nom = input("Antre non ou : ")
print("Bonjou", nom)
```

---

## Pwogram an JavaScript

```javascript
const nom = prompt("Antre non ou");
console.log("Bonjou " + nom);
```

---

# Kisa ou remake?

De pwogram sa yo pa ekri menm jan.

Men yo fè egzakteman menm travay la.

Poukisa?

Paske yo baze sou **menm algoritm lan**.

Se sèlman sentaks langaj la ki chanje.

Lojik la rete menm jan.

---

## 📊 ENFOGRAFI 19 — Yon algoritm, plizyè langaj

```text
             📝 Algoritm

      Li non itilizatè a

      Afiche "Bonjou"

               │

───────────────┼────────────────

        ▼              ▼

🐍 Python      💛 JavaScript

        ▼              ▼

      Menm rezilta
```

---

## 💡 Sonje

Lè ou aprann algoritmik, ou pa aprann sèlman yon langaj.

Ou aprann yon fason pou rezoud pwoblèm.

Se poutèt sa yon pwogramè ki byen metrize algoritmik ka aprann yon nouvo langaj pi fasil.

---

# Yon algoritm ka ekri nan plizyè langaj

Yon algoritm pa depann de yon langaj pwogramasyon.

Sa vle di, menm algoritm lan ka ekri nan anpil langaj diferan.

Pa egzanp:

- 🐍 Python
- 💛 JavaScript
- ☕ Java
- ⚙️ C
- ⚙️ C++
- 💜 C#
- 🐘 PHP
- 🐹 Go
- 🦀 Rust

Chak langaj gen pwòp sentaks pa li.

Men lojik algoritm nan rete menm jan.

Se poutèt sa, lè ou byen metrize algoritmik, li vin pi fasil pou aprann nenpòt nouvo langaj pwogramasyon.

---

## 📊 ENFOGRAFI 20 — Menm algoritm, plizyè langaj

```text
                 📝 Algoritm

                       │

      ┌────────────────┼────────────────┐

      ▼                ▼                ▼

🐍 Python      💛 JavaScript       ☕ Java

      ▼                ▼                ▼

⚙️ C++           🦀 Rust           🐹 Go

               │

               ▼

      Menm lojik
      Sentaks diferan
```

---

# Poukisa nou prepare algoritm nan anvan nou ekri kòd?

Ann reprann egzanp kay la.

Si yon mason kòmanse konstwi san plan, li ka:

- mete pòt yo nan move plas;
- bliye kèk fenèt;
- kraze yon pati pou rebati li;
- pèdi tan ak materyèl.

Nan pwogramasyon, se menm bagay la.

Si ou kòmanse ekri kòd san yon algoritm, ou ka:

- bliye kèk etap enpòtan;
- fè erè nan lojik la;
- pase anpil tan ap korije kòd la;
- oblije rekòmanse yon pati nan pwogram nan.

Se poutèt sa pifò pwogramè ki gen eksperyans toujou reflechi sou algoritm nan anvan yo kòmanse ekri kòd.

---

## 📊 ENFOGRAFI 21 — San algoritm vs Avèk algoritm

```text
❌ San algoritm

Kòmanse ekri kòd

        ▼

Erè

        ▼

Koreksyon

        ▼

Nouvo erè

──────────────────────────

✅ Avèk algoritm

Pwoblèm

        ▼

Algoritm

        ▼

Pwogram

        ▼

Preparasyon
(Konpilatè / Entèprèt)

        ▼

Egzekisyon
```

---

# Reflechi tankou yon pwogramè 🧠

Ou vle kreye yon aplikasyon ki kalkile mwayèn twa nòt.

Ki premye bagay ou ta dwe fè?

### A

Kòmanse ekri kòd tousuit.

### B

Reflechi sou etap ki nesesè pou kalkile mwayèn nan.

✅ Bon repons lan se **B**.

Anvan ou chwazi yon langaj pwogramasyon, ou dwe konprann pwoblèm nan epi prepare algoritm lan.

Lè algoritm lan pare, ekri pwogram nan vin pi fasil.

---

## 💡 Sonje

Yon bon pwogramè pa kòmanse pa tape kòd.

Li kòmanse pa konprann pwoblèm nan.

Apre sa, li prepare algoritm lan.

Se sèlman lè sa a li ekri pwogram nan.


---

# Kijan yon pwoblèm vin tounen yon pwogram?

Ann reprann tout pwosesis la depi nan kòmansman.

Lè yon moun vle kreye yon aplikasyon, li pa kòmanse dirèkteman ekri kòd.

Li suiv plizyè etap.

1. Idantifye pwoblèm nan.
2. Reflechi sou solisyon an.
3. Prepare algoritm lan.
4. Ekri algoritm lan nan yon langaj pwogramasyon.
5. Prepare pwogram nan pou òdinatè a (konpilatè, entèprèt oswa yon lòt mekanis).
6. CPU a egzekite enstriksyon yo.
7. Pwogram nan bay rezilta a.

Sa a se menm pwosesis tout pwogram suiv, kit se yon jwèt videyo, yon aplikasyon bankè oswa yon rezo sosyal.

---

## 📊 ENFOGRAFI 22 — Depi lide rive nan rezilta

```text
💡 Lide

        ▼

🎯 Pwoblèm

        ▼

📝 Algoritm

        ▼

💻 Pwogram
(Kòd sous)

        ▼

⚙️ Preparasyon pwogram nan

        ▼

🖥 CPU

        ▼

✅ Rezilta
```

---

# Egzèsis refleksyon

## Egzèsis 1

Mete etap sa yo nan bon lòd.

- Pwogram
- CPU egzekite enstriksyon yo
- Algoritm
- Pwoblèm
- Rezilta

<details>
<summary>Repons</summary>

1. Pwoblèm
2. Algoritm
3. Pwogram
4. CPU egzekite enstriksyon yo
5. Rezilta

</details>

---

## Egzèsis 2

Vrè oswa Fo?

- Yon pwogram se menm bagay ak yon algoritm.
- Menm algoritm lan ka ekri nan plizyè langaj pwogramasyon.
- Yon òdinatè konprann Python dirèkteman.
- Yon algoritm dwe prepare kòm yon pwogram anvan òdinatè a ka egzekite li.

<details>
<summary>Repons</summary>

- ❌ Fo
- ✅ Vrè
- ❌ Fo
- ✅ Vrè

</details>

---

## Egzèsis 3

Ou vle kreye yon aplikasyon kalkilatris.

Ekri algoritm lan anvan ou panse ak langaj pwogramasyon ou pral itilize.

---

## Egzèsis 4

Gade lis sa a.

- Algoritm
- Python
- JavaScript
- Java
- C++

Kiyès ki reprezante yon solisyon?

Kiyès ki reprezante langaj pwogramasyon?

<details>
<summary>Repons</summary>

**Solisyon an:** Algoritm.

**Langaj pwogramasyon yo:** Python, JavaScript, Java ak C++.

</details>

---

## ⚠️ Erè debutan fè souvan

Lè moun kòmanse aprann pwogramasyon, yo konn fè konfizyon ant **algoritm**, **pwogram** ak **langaj pwogramasyon**.

Sonje byen:

- Algoritm lan se lide oswa etap pou rezoud yon pwoblèm.
- Pwogram nan se algoritm sa a ki ekri nan yon langaj pwogramasyon.
- Langaj pwogramasyon an se zouti ki pèmèt ekri pwogram nan.

Yo pa menm bagay.

---

# Sa pou sonje

- Yon algoritm se yon seri etap pou rezoud yon pwoblèm.
- Yon pwogram se algoritm lan ki ekri nan yon langaj pwogramasyon.
- Menm algoritm lan ka ekri nan plizyè langaj diferan.
- Yon pwogram dwe prepare anvan processeur a ka egzekite li.
- Lojik algoritm lan pa chanje; se sèlman sentaks langaj la ki diferan.
- Yon bon pwogramè toujou prepare algoritm li anvan li kòmanse ekri kòd.

---

# Vokabilè

| Mo | Definisyon |
|-----|------------|
| **Pwogram** | Yon seri enstriksyon ki ekri nan yon langaj pwogramasyon. |
| **Langaj pwogramasyon** | Yon lang ki pèmèt ekri pwogram pou òdinatè. |
| **Sentaks** | Règ ki defini fason pou ekri yon langaj pwogramasyon. |
| **Konpilatè** | Yon zouti ki prepare oswa tradui yon pwogram pou òdinatè a ka egzekte li. |
| **Entèprèt** | Yon zouti ki prepare oswa egzekite yon pwogram etap pa etap, selon langaj la. |
| **Langaj machin** | Sèl lang processeur a konprann dirèkteman. |

---

# Tranzisyon pou pwochen leson an

Kounye a ou konprann diferans ki genyen ant yon algoritm ak yon pwogram.

Nan pwochen leson an, ou pral aprann **kijan pou ekri algoritm yo an pseudo-kòd**, yon notasyon ki senp epi endepandan de nenpòt langaj pwogramasyon.

