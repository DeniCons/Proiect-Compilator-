
# Proiect Compilator – Quick → C

Acest proiect reprezintă un **compilator complet** realizat în limbajul **C**, dezvoltat în cadrul disciplinei **LFTC (Limbaje Formale și Tehnici de Compilare)**.  
Compilatorul realizează traducerea unui limbaj de programare simplificat, denumit **Quick**, în **cod C**, parcurgând toate etapele clasice ale procesului de compilare.

---

##  Funcționalități

Compilatorul este structurat modular și implementează următoarele faze:

###  Analiză lexicală
- Tokenizarea codului sursă Quick  
- Identificarea cuvintelor cheie, operatorilor, identificatorilor și constantelor  
- Gestionarea erorilor lexicale  

###  Analiză sintactică
- Verificarea structurii programului conform gramaticii limbajului Quick  
- Construirea structurii interne a programului  
- Detectarea erorilor de sintaxă  

###  Analiză semantică
- Verificarea declarațiilor și utilizării variabilelor  
- Verificarea compatibilității tipurilor  
- Gestionarea regulilor semantice ale limbajului  

###  Generare de cod
- Traducerea construcțiilor din Quick în cod C echivalent  
- Generarea unui program C valid, compilabil cu un compilator standard  

---

## Cum se folosește
1. Se compilează proiectul folosind un compilator C (ex. `gcc`)  
2. Se rulează compilatorul cu un fișier sursă **Quick** ca input  
3. Se obține un fișier **C** ca output, care poate fi compilat și executat  

---

