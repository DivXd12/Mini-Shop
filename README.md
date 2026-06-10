# MiniMagazin

Proiect web simplu pentru facultate: un magazin online mic, făcut cu **Svelte**, **FastAPI** și **SQLite**.

Aplicația are două părți: client și admin. Clientul poate vedea produse, le poate adăuga în coș și poate plasa o comandă. Adminul poate adăuga, edita și șterge produse, dar și schimba statusul comenzilor.

 Cum se rulează

Ai nevoie de:

- Python 3.11+
- Node.js 20+

Apoi pornești aplicația așa:

1. Dublu click pe `start_backend.bat`
2. Dublu click pe `start_frontend.bat`
3. Deschizi în browser: `http://localhost:5173`

API-ul poate fi văzut aici: `http://localhost:8000/docs`

 Conturi demo

Admin:

- email: `admin@magazin.ro`
- parolă: `admin123`

Client:

- email: `client@magazin.ro`
- parolă: `client123`

 Ce am folosit

- Svelte pentru interfață
- FastAPI pentru backend
- SQLite pentru baza de date

Baza de date se creează automat la prima pornire, cu câteva produse demo deja introduse.
