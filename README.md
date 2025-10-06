# 💻 Laborator 1 – HTML & CSS  
### Programare Web – Facultatea de Automatică și Calculatoare, UPT  
**Asist. univ. drd. Alexandra-Gabriela Laicu-Hausberger**

---

## 📚 Descriere generală
Acest laborator reprezintă prima introducere practică în **dezvoltarea web**.  
Scopul este să înțelegi cum se construiește o pagină web de la zero, cum se structurează conținutul folosind **HTML**, și cum se aplică stiluri și layout-uri folosind **CSS**.

La finalul laboratorului, vei avea o **pagină web pentru CV-ul tău**!

---

## 🎯 Obiectivele primului laborator
- Înțelegerea structurii unui fișier HTML (`<html>`, `<head>`, `<body>`).  
- Utilizarea tagurilor: `<h1>`, `<p>`, `<ul>`.  
- Aplicarea regulilor CSS pentru culori, fonturi, margin, padding, etc..  
- Crearea unui layout simplu și responsive folosind **flexbox**.  

---

## 🧩 Exercițiul: Creează o pagină web pentru CV-ul tău

### 🎯 Scop
Să aplici toate conceptele învățate (HTML, CSS, layout) pentru a crea o pagină web de prezentare personală, adică un mini CV online care să reflecte stilul tău.

---

### 🔧 Cerințe
Creează o pagină web care conține:

#### 🔹 Structură HTML
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

#### 🔹 Stilizare CSS
- un fișier CSS separat (`style.css`);  
- fundal deschis și o culoare principală pentru accente;  
- font modern (ex: *Poppins*, *Roboto*);  
- margini, spațieri și text aliniat clar;  
- listă de abilități stilizată (fără bullet points, poți folosi emoji-uri);
- imaginea de profil să fie rotundă, cu o bordură subțire colorată și efect de shadow;

#### 🔹 Layout
- organizează conținutul principal folosind `flexbox`;  
- imaginea și descrierea să fie afișate una lângă alta pe desktop;  
- pe ecrane mici (mobil), elementele trebuie să se aranjeze vertical.  

💡 *Hint:* 
```css
.main {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
  flex-wrap: wrap; /* pentru responsiveness */
}
