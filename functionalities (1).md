# 🎓 Platformă de Tutoriale Video  
## Funcționalități și Specificații Tehnice

---

## 🔹 1. Scopul aplicației
Aplicația are ca scop dezvoltarea unei platforme web care permite utilizatorilor să creeze, să administreze și să vizualizeze tutoriale video educaționale.  
Profesorii pot încărca materiale video organizate sub formă de cursuri, iar studenții pot accesa conținutul pentru a învăța, urmări progresul și oferi feedback.

---

## 🔹 2. Actorii principali

| Actor | Descriere |
|-------|------------|
| **Vizitator** | Poate accesa pagina principală, vizualiza lista de cursuri publice, dar nu poate accesa lecțiile detaliate. |
| **Student** | Poate vizualiza cursurile video, urmări progresul, oferi rating-uri și comentarii. |
| **Profesor** | Poate crea, edita și șterge cursuri și videoclipuri asociate. |
| **Administrator** | Poate gestiona utilizatorii, cursurile și conținutul publicat pe platformă. |

---

## 🔹 3. Funcționalități principale

### 3.1. Autentificare și gestionare utilizatori
- Înregistrare cont nou (rol: student / profesor)  
- Autentificare cu email și parolă  
- Resetare parolă (prin email)  
- Editare profil (nume, imagine, biografie)  
- Setare roluri și permisiuni (profesor / student / admin)

---

### 3.2. Gestionarea conținutului video
- Încărcarea fișierelor video (formate acceptate: `.mp4`, `.avi`, `.mov`)  
- Salvarea metadatelor: titlu, descriere, categorie, durată, miniatură  
- Vizualizarea listei de videoclipuri proprii  
- Editarea sau ștergerea videoclipurilor existente  
- Vizualizare statistică: număr de vizualizări, rating mediu  

---

### 3.3. Gestionarea cursurilor video
- Crearea unui curs nou (titlu, descriere, categorie, imagine de copertă)  
- Adăugarea videoclipurilor într-un curs (playlist logic)  
- Editarea și actualizarea conținutului cursului  
- Publicarea / dezactivarea unui curs  
- Ștergerea unui curs  
- Organizarea lecțiilor pe capitole / module  

---

### 3.4. Vizualizarea și urmărirea cursurilor
- Pagina principală cu listă de cursuri (cu filtru după categorie / profesor / nivel)  
- Pagină detaliată a cursului: descriere, autor, listă lecții, durată totală  
- Player video integrat cu controale (play, pause, fullscreen, volum)  
- Urmărirea progresului studentului (lecții vizionate / total)  
- Salvarea progresului automat  

---

### 3.5. Interacțiune și feedback
- Sistem de rating (1–5 stele) pentru fiecare curs  
- Comentarii la videoclipuri și cursuri  
- Răspunsuri la comentarii (thread-uri simple)  
- Sortarea cursurilor după rating mediu  
- Posibilitatea de a adăuga cursuri la „Favorite”  

---

### 3.6. Panou administrativ (Admin Dashboard)
- Vizualizare utilizatori înregistrați  
- Ștergere / suspendare conturi  
- Moderarea comentariilor și a cursurilor  
- Vizualizare statistici generale:
  - Număr total de utilizatori
  - Număr total de cursuri
  - Număr total de vizualizări  

---

## 🔹 4. Funcționalități opționale
- Integrare API YouTube / Vimeo pentru import video  
- Generare automată de miniaturi (thumbnail)  
- Sistem de notificări pentru cursuri noi  
- Export progres student (raport PDF / CSV)  
- Mod întunecat (Dark Mode)  

---

## 🔹 5. Fluxuri de utilizare (exemple)

### 🔸 Flux: Profesorul adaugă un curs nou
1. Profesorul se autentifică în platformă  
2. Accesează secțiunea „Cursurile mele”  
3. Apasă butonul „Adaugă curs nou”  
4. Completează titlul, descrierea și imaginea cursului  
5. Încarcă videoclipurile aferente cursului  
6. Salvează și publică cursul  

### 🔸 Flux: Studentul vizualizează un curs
1. Studentul se autentifică  
2. Accesează pagina de cursuri disponibile  
3. Selectează un curs  
4. Redă lecțiile video în player  
5. Poate adăuga un comentariu sau rating  
6. Progresul este salvat automat  

---

## 🔹 6. Tehnologii recomandate
- **Frontend:** React / Vue / Angular  
- **Backend:** Node.js / Django / Laravel  
- **Bază de date:** MySQL / PostgreSQL / MongoDB  
- **Stocare video:** AWS S3 / Firebase Storage / local server  
- **Autentificare:** JWT / OAuth 2.0  
- **Design:** TailwindCSS / Bootstrap  

---

## 🔹 7. Concluzie
Platforma de tutoriale video oferă o soluție completă pentru crearea, organizarea și vizualizarea conținutului educațional video.  
Prin separarea clară a rolurilor și gestionarea centralizată a cursurilor, aplicația asigură o experiență intuitivă și eficientă pentru utilizatori.

---

📁 **Fișier:** `functionalities.md`  
📅 **Versiune:** 1.0  
✍️ **Autor:** [Nume autor / echipă proiect]
