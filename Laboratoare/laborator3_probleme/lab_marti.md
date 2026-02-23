+++
weight = 1
title = "Laborator 3 - Marți"
+++


## 🧩 Probleme:


1) **Cerințe:**
    1) {{< addlink name="task1" text="Cerința 1" >}}
    1) {{< addlink name="task2" text="Cerința 2" >}}
    1) {{< addlink name="task3" text="Cerința 3" >}}


![figura1](/images/lab3/lab3_nested3.png "Transmiterea parametrilor prin referință și prin valoare")

##### **1. (4p) Funcțiile albastre din figura {{< addlink name="figura1" text="de mai sus" >}} primesc parametrii prin referință, cele verzi prin valoare.**  {#task1}

  🎯 **Scop:** Observați ce se întâmplă cu **valorile** și **adresele** variabilelor când sunt transmise prin referință sau valoare.  

  **Ce trebuie să faceți?**  
   -  Afișați **valorile și adresele** variabilelor:
     - **Înainte de intrarea în funcție**
     - **În interiorul funcției**
     - **La ieșirea din funcție**  

   -  **Implementați structura de funcții imbricate** (*nested functions*) conform figurii {{< addlink name="figura1" text="de mai sus" >}}.  
     Toate funcțiile `f` sunt de tip `void` și primesc un singur parametru, inițializat în `main` cu `0`.  

   -  Fiecare funcție (inclusiv `main`) trebuie să conțină:  
     -  Incrementarea valorii variabilei  
     -  Afișarea **numelui funcției**, a **valorii variabilei** și a **adresei acesteia**  
     -  Apelarea altei funcții conform **structurii din figura {{< addlink name="figura1" text="de mai sus" >}}**  
     -  Afișarea **valorii variabilei la ieșire**  

---

##### **2. 🎲 (3p) Matrice și scalare în intervalul [-1,1]**  {#task2}

   -  Inițializați o **matrice 5 × 5** cu **numere aleatoare**.  

   -  Scalați valorile astfel încât **toate elementele** să fie în intervalul `[-1,1]`.  

   -  Afișați **conținutul matricii** **înainte și după scalare**.  

---

##### **3. 🔢 (3p) Vector dinamic și pointeri**  {#task3}

   -  Declarați un **vector de întregi alocat dinamic**.  

   -  **Introduceți valori** de la tastatură până la întâlnirea lui `0` (neinclus).  

   -  Valorile vectorului sunt **distincte**.  

   -  Implementați două funcții care:
     -  Primesc vectorul **printr-un pointer**.  
     -  Returnează un **pointer către al doilea cel mai mare element**.  
     -  **Șterge al doilea cel mai mare element** și **realocă spațiul** vectorului. (Folosiți prima funcție pentru calcul).  

   -  **Testați programul**, afișând vectorul **înainte și după ștergerea elementului**.  

---

🚀 **Spor la lucru!** 🔥💡
