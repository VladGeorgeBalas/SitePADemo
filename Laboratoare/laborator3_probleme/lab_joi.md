---
weight: 3
title: "Laborator 3 - Joi"
---


## Probleme:
![figura1](/images/lab3/lab3_nested2.png "Transmiterea parametrilor prin referință și prin valoare")

**1. (4p) Funcțiile albastre din figura {{< addlink name="figura1" text="de mai sus" >}} primesc parametrii prin referință, cele verzi prin valoare.**  {#task1}

  🎯 **Scop:** Observați cum se schimbă **valorile** și **adresele** variabilelor când sunt transmise prin referință sau valoare.  

  **Ce trebuie să faceți?**  
   -  Afișați **valorile și adresele** variabilelor:
     -  **Înainte de intrarea în funcție**
     -  **În interiorul funcției**
     -  **La ieșirea din funcție** 


   - **Implementați structura de funcții imbricate** (*nested functions*) conform figurii {{< addlink name="figura1" text="de mai sus" >}}.  Toate funcțiile `f` sunt de tip `void` și primesc un singur parametru, inițializat în `main` cu `0`.


   -  Fiecare funcție (inclusiv `main`) trebuie să conțină:  
     -  Incrementarea valorii variabilei  
     -  Afișarea **numelui funcției**, a **valorii variabilei** și a **adresei accesteia**  
     -  Apelarea altei funcții conform **structurii din figura {{< addlink name="figura1" text="de mai sus" >}}**  
     -  Afișarea **valorii variabilei la ieșire**  

---



##### **2. 🎲 (3p) Inițializarea și scalarea unei matrice 5 × 5**  {#task2}

   -  Inițializați o **matrice 5 × 5** cu **numere aleatoare**.  


   -  Scalați valorile astfel încât **fiecare coloană** să fie în intervalul `[0,1]` folosind **minimul și maximul** acelei coloane. 


   -  Afișați conținutul matricii **înainte și după scalare**.  

---



##### **3. 🔢 (3p) Vector dinamic și pointeri**  {#task3}

   -  Declarați un **vector de întregi alocat dinamic**, cu **dimensiune impară**. 

   -  **populați vectorul cu date** de la tastatură până la întâlnirea lui `0` (neinclus in vector).  

   -  Implementați două funcții care:
     - Primesc vectorul **printr-un poiner**.
     -  Returnează un **pointer către elementul median**.  
     -  **Șterge elementul median** și **realocă spațiul** vectorului. (Folosiți prima funcție pentru a determina medianul).  

   -  **Testați programul**, afișând vectorul **înainte și după ștergere**.  

---

🚀 **Spor la lucru!** 🔥💡
