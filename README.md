# 💻 Laborator 1 – HTML & CSS  
### Programare Web – Facultatea de Automatică și Calculatoare, UPT  
**Asist. univ. drd. Alexandra-Gabriela Laicu-Hausberger**

---

## Descriere generală
Acest laborator reprezintă prima introducere practică în **dezvoltarea web**.  
Scopul este să înțelegi cum se construiește o pagină web de la zero, cum se structurează conținutul folosind **HTML**, și cum se aplică stiluri și layout-uri folosind **CSS**.

La finalul laboratorului, vei avea o **pagină web pentru CV-ul tău**!

---

## Obiectivele primului laborator
- Înțelegerea structurii unui fișier HTML (`<html>`, `<head>`, `<body>`).  
- Utilizarea tagurilor: `<h1>`, `<p>`, `<ul>`.  
- Aplicarea regulilor CSS pentru culori, fonturi, margin, padding, etc..  
- Crearea unui layout simplu și responsive folosind **flexbox**.  

---

## Exercițiul: Creează o pagină web pentru CV-ul tău

### Scop
Să aplici toate conceptele învățate (HTML, CSS, layout) pentru a crea o pagină web de prezentare personală, adică un mini CV online care să reflecte stilul tău.

---

### 🔧 Cerințe
Creează o pagină web care conține:

#### Structură HTML
- un **header**
  - care să conțină numele, o scurtă descriere și o **imagine de profil**
- o **secțiune principală** cu
  - o **secțiune „Despre mine”** care să conțină:
    - o **listă de abilități**
    - o listă ordonată de **pasiuni și hobby-uri**
- o **secțiune „Contact”** cu link-uri externe:
  - telefon
  - mail
  - pagina de social media
- un **footer** simplu cu numele tău și anul curent.  

#### Stilizare CSS
- un fișier CSS separat (`style.css`);  
- fundal deschis și o culoare principală pentru accente;  
- font modern (ex: *Poppins*, *Roboto*);  
- margini, spațieri și text aliniat clar;  
- listă de abilități stilizată (fără bullet points, poți folosi emoji-uri);
- imaginea de profil să fie rotundă, cu o bordură subțire colorată și efect de shadow;

#### Layout
- organizează conținutul principal folosind `flexbox`;  
- imaginea și descrierea să fie afișate una lângă alta pe desktop;  
- pe ecrane mici (mobil), elementele trebuie să se aranjeze vertical.  

*Hint:* 
```css
.main {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
  flex-wrap: wrap; /* pentru responsiveness */
}
```
---

## Încărcarea temei

1. Acceptă invitația GitHub Classroom:  
   - [https://classroom.github.com/a/3xOgoGOr](https://classroom.github.com/a/3xOgoGOr)

2. După ce accepți invitația, GitHub va crea automat un **repository personal** pentru tine.  

3. Clonează repository-ul pe calculatorul tău:  
   ```bash
   git clone <linkul-tău-de-repo>
    ```

4. Intră în folderul proiectului:

   ```bash
   cd <folderul tău>
   ```
   
5. Adaugă fișierele index.html și style.css in staging, apoi salvează modificările:

```bash
git add .
git commit -m "Laborator 1 – HTML & CSS final"
 ```

6. Încarcă codul pe GitHub:

```bash
git push
```

---

## (Opțional) Publicarea paginii pe GitHub Pages

După ce ai urcat codul pe GitHub, poți să îți publici pagina în doar câțiva pași simpli:

1. Mergi pe pagina repository-ului tău (exemplu: `PW-Lab1-username`).
2. Accesează **Settings → Pages** (din bara laterală stângă).
3. În secțiunea **“Build and deployment”**, setează:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Apasă **Save**.
5. După câteva secunde, GitHub va genera automat un link public pe care îl poți accesa de oriunde și pe care îl poți trimite oricui!

---


