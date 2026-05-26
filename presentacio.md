# Defensa final del projecte — SMX2

**Alumne:** Oscar Fernández (`@17tayyy`)
**Mòdul:** Projecte intermodular SMX 2n
**Curs:** 2025–2026
**Data de defensa:** _a omplir el dia de la defensa_

> Aquest fitxer és el **fil conductor** de la defensa davant del tribunal.
> Cada apartat enllaça directament al repositori i al document que cal mostrar.

---

## 0. Presentació personal

- **Nom:** Oscar Fernández — *Tay* (`@17tayyy` a GitHub)
- **Centre:** SMX2 · FP Informàtica i Comunicacions
- **Perfil tècnic:** Backend (Python · Rust · FastAPI), ciberseguretat ofensiva i administració de sistemes Linux/Windows.
- **Repositori de perfil GitHub:** <https://github.com/17tayyy>
- **README de perfil:** <https://github.com/17tayyy/17tayyy> *(es projecta el primer durant la Part 1)*

---

## 1. Índex de la defensa

| Part | Continguts | Temps aproximat |
|------|------------|-----------------|
| **Part 1** | Perfil GitHub, README personal i organització dels repositoris | 3–4 min |
| **Part 2** | Anàlisi de dos repositoris seleccionats pel tribunal | 5–6 min |
| **Part 3** | Defensa tècnica del projecte/s triat/s pel tribunal | 5–6 min |
| **Part 4** | Metodologia de treball: Kanban, Gantt i GitHub | 3–4 min |
| **Tancament** | Conclusions i aprenentatges | 1–2 min |

---

## 2. Mapa de repositoris del curs

Tots els repositoris són accessibles des de [github.com/17tayyy](https://github.com/17tayyy).

| # | Projecte | Repositori | Estat |
|---|----------|------------|-------|
| 01 | **Arranquem** | _(integrat dins l'organització de classes; evidències a tractar com a context inicial del curs)_ | ℹ️ |
| 02 | **Consultoria EverPia** | <https://github.com/17tayyy/Projecte2> | ✅ |
| 03 | **Consultoria EverPia 2** | <https://github.com/17tayyy/Projecte3> | ✅ |
| 04 | **Consultoria EverPia 3** | <https://github.com/17tayyy/Projecte4> | ✅ |
| 05 | **La Incubadora** *(TransLògic S.A.)* | <https://github.com/17tayyy/projecte5-17tayyy> | ✅ |
| 06 | **Nexus** *(plataforma e-learning)* | <https://github.com/17tayyy/projecte6-17tayyy> | ✅ |
| 07 | **FoodLogístic S.A.** | <https://github.com/17tayyy/projecte-7-17tayyy> | ✅ |
| 08 | **Connecta't al Futur** *(ONG Horitzons Digitals + Coworking Mataró)* | <https://github.com/17tayyy/projecte-8-17tayyy> | ✅ |

> Tots els repositoris segueixen la mateixa estructura: `README.md` arrel + carpetes `TascaXX/` i `ProducteXX/` amb el seu README.

---

## 3. Part 1 — Perfil de GitHub i organització

### 3.1 Què mostraré

1. **Perfil públic** [github.com/17tayyy](https://github.com/17tayyy):
   - README personalitzat amb stack tècnic (Python, Rust, FastAPI, Pentesting, Docker, Linux…).
   - Pinned repos: una barreja de projectes del curs i projectes personals (`shellox`, `ironmap`, `ferrogrep`, `Argus`…) que demostren especialització en backend i seguretat.
2. **Llista de repositoris del curs:** mostraré que els 7 repos numerats (Projecte2 → Projecte8) hi són tots.
3. **Estructura interna comuna:**
   ```
   ProjecteX/
   ├── README.md          ← índex del projecte amb enllaços a tasques
   ├── TascaXX/
   │   ├── README.md      ← enunciat + procediment
   │   ├── solution.md / solucio.md / informe.md  ← resolució
   │   └── img/           ← evidències visuals
   └── ProducteXX/        ← entregables consolidats
   ```
4. **Qualitat dels commits:** missatges descriptius, granularitat raonable, sense commits genèrics tipus "update".

### 3.2 Punts forts a destacar

- **Coherència** d'estructura entre repositoris → fàcil de navegar.
- **Documentació en Markdown** amb taules, diagrames Mermaid, captures i enllaços relatius.
- **Separació clara** entre tasques (procés d'aprenentatge) i productes (entregables finals).

---

## 4. Part 2 i 3 — Resum tècnic de cada projecte

> Aquesta secció és la "fitxa ràpida" que faré servir si el tribunal demana entrar a qualsevol repo.
> Per a cada projecte tinc: **client/context · objectiu · tasques clau · entregable final · decisions tècniques · dificultats**.

---

### 📁 Projecte 02 — Consultoria EverPia *(grup)*

🔗 <https://github.com/17tayyy/Projecte2>

- **Context:** primer encàrrec com a consultor júnior a EverPia.
- **Tasques presents al repo:**
  - **Tasca 2** — Selecció d'un SAI per a un client (anàlisi tècnic + criteris VA, autonomia, topologia).
  - **Tasca 3** — Seguretat lògica: recuperació d'accés a sistemes (Linux/Windows).
  - **Tasca 8** — Proposta de domini i hosting per a dos clients reals assignats.
- **Producte transversal:** README personal a GitHub (compte de perfil) → ja visible al meu perfil.
- **Decisions destacables:** anàlisi cost-prestacions del SAI; justificació de hosting compartit vs VPS segons perfil de client.
- **Aprenentatge clau:** com estructurar una proposta professional en Markdown amb captures, taules i `solution.md` separat del README.

---

### 📁 Projecte 03 — EverPia 2: *Sobreviure en una empresa IT* *(grup)*

🔗 <https://github.com/17tayyy/Projecte3>

- **Context:** continuació d'EverPia, ara amb el focus en **administració de serveis crítics**.
- **Tasques i productes:**
  - **Tasca 01** — Gestor de contrasenyes (selecció + guia + informe post-incident a EverPia).
  - **Tasca 04** — Plec de Condicions Tècniques per a un servei **LDAP** (cas Innovatech).
  - **Tasca 06** — Diagnosi DNS amb CLI (`dig`, `nslookup`) sobre Zorin OS amb dues interfícies.
  - **Producte 04** — Configuració d'un **servidor DNS BIND9** per al client Digicore: `named.conf.options`, `named.conf.local` i zones de directe/inverses pujats al repo per a desplegament reproduïble.
- **Decisions tècniques:** estructurar el repo com una "biblioteca de fitxers desplegables" per a futurs clients (cas P04).
- **Dificultat resolta:** errors a les zones DNS (sintaxi de SOA i delegacions inverses); validats amb `named-checkzone`.

---

### 📁 Projecte 04 — EverPia 3: Repte final IT *(grup)*

🔗 <https://github.com/17tayyy/Projecte4>

- **Context:** consolidació de competències IT (DRP, accés remot, NFS, CUPS, Figma, Green IT).
- **Tasques i productes destacats:**
  - **Tasca 01–02** — DRP / Còpies de seguretat per a *Muntatges i Serveis Tècnics SL* (cooperatiu: individual → parelles → grup; guies tècniques Windows + Linux).
  - **Tasca 05** — Accés remot SSH (gestió segura de servidors al CPD/núvol).
  - **Tasca 07** — Serveis d'assistència remota *(en parelles)*.
  - **Tasca 09** — Servidor de fitxers Linux amb **NFS**.
  - **Producte 03** — **Kanban del projecte**: és la peça de metodologia (vegeu Part 4).
- **Decisions tècniques:** triar Rescuezilla per imatges del sistema; SSH amb claus públiques + `Match` blocks; NFS amb `no_root_squash` només a la xarxa de gestió.
- **Dificultats:** algunes tasques estan menys desenvolupades (T03, T04, T06, T08, T10–T15) → coherència que cal explicar al tribunal: priorització conscient + alguns RA encara per recuperar.

---

### 📁 Projecte 05 — La Incubadora *(TransLògic S.A.)* *(grup B2B)*

🔗 <https://github.com/17tayyy/projecte5-17tayyy>

- **Context:** incubadora d'empreses IT al Maresme; muntem una empresa fictícia i venem una solució B2B real a *TransLògic S.A.*
- **Tasques i productes:**
  - **T01** — Disseny de la solució tècnica integrada (anàlisi negoci → arquitectura).
  - **T02** — Migració del control de versions de la web de GitHub al **Git local** + branches.
  - **T03** — Serveis de transferència de fitxers (SFTP/FTPS/Samba).
  - **T04** — Instal·lació **Windows Server 2025** sobre VM (PoC abans del desplegament real).
  - **T05–T06** — Desplegament i configuració del **domini Active Directory** + Unitats Organitzatives.
  - **T07** — Acadèmia interna feta amb **Moodle** (Escola Júlia) — defensa per parts.
  - **T08–T09** — Seguretat: anàlisi de malware i vulnerabilitats corporatives.
  - **T10** — Green IT *(en parelles)*: sostenibilitat aplicada a l'empresa.
  - **P01** — Migració a GitHub Classroom amb repos privats.
  - **P02** — Model de **llicenciament Windows Server 2025** optimitzat per a TransLògic.
  - **P03** — Defensa final del projecte d'incubadora.
- **Decisions tècniques:** justificació de Win Server 2025 sobre Linux per requisits AD del client; model de llicències per CAL ajustat als 35 usuaris.
- **Dificultat resolta:** errors d'unió al domini per DNS mal configurat al client → fix forçant `nameserver` al DC.

---

### 📁 Projecte 06 — Nexus *(plataforma e-learning)* *(grup)*

🔗 <https://github.com/17tayyy/projecte6-17tayyy>

- **Context:** desplegament integral d'infraestructura segura per a una plataforma e-learning.
- **Tasques i productes destacats:**
  - **T02** — Missió **Apache**: desplegament multidomini i HTTPS.
  - **T03** — Missió **Nginx**: migració d'alt rendiment, arquitectura lleugera.
  - **T04** — Duel **Apache vs Nginx**: criteri d'elecció segons càrrega/SSL/recursos.
  - **T05** — *Top Secret*: confidencialitat, integritat, autenticitat (xifrat + signatura + hash).
  - **T06** — **PKI corporativa** + signatura digital de PDFs (PoC amb CA pròpia).
  - **T07** — TransLògic: administració avançada i seguretat corporativa.
  - **T08** — Vigilància i auditoria de sistemes (logs, alertes).
- **Decisions tècniques:** triar **Nginx** com a frontal per terminació TLS i Apache només per backends PHP legacy; CA arrel offline + CA intermèdia online.
- **Dificultats:** algunes tasques (T01, T09–T13) i productes encara per documentar → els reconec obertament i marco com a punts oberts.

---

### 📁 Projecte 07 — FoodLogístic S.A. *(grup amb Javier García)*

🔗 <https://github.com/17tayyy/projecte-7-17tayyy>

- **Context:** modernització de la logística alimentària via tecnologia (35 empleats, 25 M€ de facturació).
- **Tasques i productes:**
  - **T01** — Coneixent la competència i el sector (anàlisi de mercat).
  - **T02** — Web corporativa desplegada: <https://17tayyy.github.io/web-corporativa-t02> *(repo separat)*.
  - **T03** — Servidor de fitxers (consolidació documental departamental).
  - **T05** — Vídeo formatiu LOPD per a empleats.
  - **T06** — *Operació Escut Digital*: adaptació legal de la web (RGPD, cookies, avisos).
  - **T07** — Migració al núvol: correu corporatiu (Microsoft 365 vs Google Workspace).
  - **T08** — Tria de la web definitiva entre les propostes individuals.
  - **T09** — **Diagrama de Gantt** del projecte → evidència directa per a la Part 4.
  - **T10** — Pressupost detallat del projecte.
  - **Producte 01** — **Memòria Tècnica de la Proposta**: solució integral en 4 eixos (infra HA + M365 + RGPD + web). **Inversió any 1: 20.206,79 € IVA incl.** + **8.687,59 €/any recurrent**.
- **Decisions tècniques destacables:**
  - Microsoft 365 Business Standard sobre Google Workspace per integració amb Windows + AD existent.
  - Infraestructura HA: NAS amb RAID 6 + replicació offsite.
  - Web amb GitHub Pages → cost zero d'hosting + custom domain.
- **Dificultats:** alineació entre la part legal (RGPD/LSSI) i la part tècnica; resolució amb una passada conjunta a la T06.

---

### 📁 Projecte 08 — Connecta't al Futur *(grup amb Javier García)*

🔗 <https://github.com/17tayyy/projecte-8-17tayyy>

- **Context:** consultoria de digitalització **sostenible** per a PIMEs locals.
- **Dos clients atesos:**

#### 🔸 T01 — Aula Digital ONG *Horitzons Digitals*
- **Repte:** subvenció per crear una aula d'alfabetització digital per a gent gran, persones en cerca de feina i joves en risc.
- **Dossier tècnic** ([`T01/dossier.md`](https://github.com/17tayyy/projecte-8-17tayyy/blob/main/T01/dossier.md), v2.0):
  - **Anàlisi de l'espai:** 60 m² → 15 postos d'alumne + 1 professor; 20 preses RJ-45 Cat6.
  - **3 perfils d'usuari** ben definits (bàsic / cerca feina / joves) amb requisits específics.
  - **Decisió clau:** *un sol model d'equip* (CPU N100, 16 GB RAM, SSD 256 GB) + **imatges Clonezilla per perfil**, en comptes de tres maquinaris diferents.
  - **Topologia de xarxa** amb VLANs (alumnes / professor / gestió) + WiFi 6 separada per a visitants. Diagrama Mermaid al dossier.
  - Comparativa programari lliure vs comercial, pressupost realista i pla de manteniment.

#### 🔸 T02 — Pla de Sostenibilitat *Coworking Mataró*
- **Repte:** reducció ≥20% de la factura elèctrica + certificació sostenibilitat ([`T02/pla.md`](https://github.com/17tayyy/projecte-8-17tayyy/blob/main/T02/pla.md)).
- **Fases:** diagnòstic i auditoria → hardware circular → bones pràctiques digitals → pla integral.
- **Indicadors:** KPIs energètics, gestió RAEE, alineament amb **ODS** (7, 12, 13).

---

## 5. Part 4 — Metodologia de treball *(OBLIGATÒRIA)*

### 5.1 Marc metodològic aplicat

| Eina | Ús durant el curs | Evidència al repo |
|------|-------------------|-------------------|
| **Kanban** (GitHub Projects / Planner) | Gestió diària: *Pendent → En curs → En revisió → Fet* | [Projecte4/producte03 — Kanban del projecte](https://github.com/17tayyy/Projecte4/tree/main/producte03) |
| **Diagrama de Gantt** | Planificació temporal amb dependències i terminis | [Projecte7/Tasca09 — Gantt FoodLogistic](https://github.com/17tayyy/projecte-7-17tayyy/tree/main/Tasca09) |
| **GitHub** | Versionat, evidències, històric de canvis, branques i issues | Tots els repositoris numerats |
| **Markdown** | Documentació tècnica navegable amb taules, diagrames i captures | Cada `README.md` i `solucio.md` |

### 5.2 Cicle de treball aplicat (fases)

1. **Anàlisi** — llegir l'enunciat, identificar client, restriccions, criteris d'avaluació.
2. **Planificació** — descomposar en sub-tasques al Kanban; assignar prioritat i estimació.
3. **Desenvolupament** — implementació tècnica + commits incrementals amb missatges descriptius.
4. **Proves** — PoC sobre VM/contenidor abans de la solució "final" (cas T04 P5: Win Server sobre VM).
5. **Documentació** — `README.md` + `solucio.md` + captures + diagrames Mermaid.
6. **Entrega** — push final, revisió del README arrel del projecte, validació amb el company de grup.

### 5.3 Exemple real viscut: *Diagrama de Gantt de FoodLogístic (P7/T09)*

- **Situació inicial:** la T07 (migració de correu al núvol) semblava una tasca lineal de 2 dies.
- **Què va passar:** en arribar al moment del tall del correu vell, vam veure que requeria coordinació amb l'usuari, finestra fora d'horari laboral i una migració de bústies històrica → real ≈ 5 dies.
- **Acció presa:** vam recórrer al Gantt i replanificar:
  - La T07 es va dividir en `T07a — preparació tècnica` (es podia avançar) i `T07b — tall efectiu` (depenia del client).
  - Les T08 i T09 es van paral·lelitzar perquè no depenien de la T07.
  - El Kanban es va actualitzar: T07 va passar de "En curs" → "Bloquejada (client)" → "En revisió" → "Fet".
- **Resultat:** lliurament dins de termini sense allargar el projecte global.
- **Evidència:** commits dels dies posteriors a T07 + Gantt revisat a T09.

### 5.4 Què demostra el meu GitHub sobre la metodologia

- **Granularitat dels commits:** un commit ≈ una acció lògica, missatge en imperatiu.
- **Estructura predictible** entre repos → un nouvingut localitza la solució de qualsevol tasca en <30 s.
- **Documentació viva:** cada README del projecte enllaça a les tasques, i cada tasca enllaça als seus annexos.
- **Branques i issues:** ús puntual (sobretot P07/P08 amb el Javier) per a tasques paral·leles.

---

## 6. Recuperació de RA pendents *(si escau)*

> Si el tribunal m'indica que hi ha RA pendents de recuperar:

- **Ubicació:** carpeta dedicada `recuperacio-RA/` dins del repo del projecte corresponent.
- **Continguts previstos:** evidència específica del RA + informe `recuperacio.md` + captures.
- **Accessibilitat:** enllaç directe des d'aquest fitxer un cop preparat.

_(Aquest apartat queda obert per omplir si finalment se m'assigna una recuperació.)_

---

## 7. Conclusions i aprenentatges

### 7.1 Què m'enduc del curs (tècnic)

- **Administració de servidors** Windows (AD, GPO, llicenciament 2025) i Linux (DNS, NFS, SSH, LDAP).
- **Web** des de prototip Figma fins a desplegament en GitHub Pages amb domini propi.
- **Seguretat:** gestió de contrasenyes, PKI/CA pròpia, signatura digital, RGPD/LSSI a la pràctica.
- **Cloud:** comparativa real Microsoft 365 vs Google Workspace per a una PIME de 35 treballadors.
- **Sostenibilitat IT:** Green IT, economia circular, KPIs energètics, RAEE i ODS.

### 7.2 Què m'enduc del curs (professional)

- **Documentar mentre faig**, no després — m'estalvia hores i evita perdre el "perquè" d'una decisió.
- **Kanban com a brúixola diària**, no com a tràmit administratiu.
- **Comunicació al client** (memòria tècnica, pressupost, defensa oral) val tant com la solució tècnica.
- **Treball en grup amb GitHub**: branques, revisions i convencions de commits eviten conflictes.

### 7.3 Què milloraré

- Tancar al 100% els repositoris amb tasques encara obertes (P4, P6) abans de presentar-los públicament.
- Augmentar l'ús de **issues** i **GitHub Projects** com a Kanban natiu en comptes d'eines externes.
- Afinar la coherència de naming entre repos (`TascaXX` vs `tascaXX` vs `tascaXX`).

---

## 8. Annex — Enllaços ràpids per al tribunal

- **Perfil:** <https://github.com/17tayyy>
- **README de perfil:** <https://github.com/17tayyy/17tayyy>
- **Projecte 02 (EverPia):** <https://github.com/17tayyy/Projecte2>
- **Projecte 03 (EverPia 2):** <https://github.com/17tayyy/Projecte3>
- **Projecte 04 (EverPia 3):** <https://github.com/17tayyy/Projecte4>
- **Projecte 05 (Incubadora):** <https://github.com/17tayyy/projecte5-17tayyy>
- **Projecte 06 (Nexus):** <https://github.com/17tayyy/projecte6-17tayyy>
- **Projecte 07 (FoodLogístic):** <https://github.com/17tayyy/projecte-7-17tayyy>
  - Web desplegada (T02): <https://17tayyy.github.io/web-corporativa-t02>
  - Memòria tècnica (P01): <https://github.com/17tayyy/projecte-7-17tayyy/tree/main/Producte01>
  - Gantt (T09): <https://github.com/17tayyy/projecte-7-17tayyy/tree/main/Tasca09>
- **Projecte 08 (Connecta't al Futur):** <https://github.com/17tayyy/projecte-8-17tayyy>
  - Dossier ONG Horitzons Digitals: <https://github.com/17tayyy/projecte-8-17tayyy/blob/main/T01/dossier.md>
  - Pla Coworking Mataró: <https://github.com/17tayyy/projecte-8-17tayyy/blob/main/T02/pla.md>
