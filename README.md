# Encompass Health (NYSE: EHC) – Leveraged Buyout (LBO) Model

## 📌 Project Overview
Questo repository contiene un **modello finanziario LBO (Leveraged Buyout) a 3 prospetti** completo e dinamico sviluppato su **Encompass Health Corporation (NYSE: EHC)**, leader statunitense nei servizi sanitari di riabilitazione post-acuta. 

Il modello valuta la fattibilità finanziaria e i rendimenti per uno Sponsor finanziario su un orizzonte di holding period di **5 anni (Anno 1 - Anno 5)**. Include un meccanismo di *Cash Sweep* integrale e risolve le interdipendenze finanziarie attraverso l'attivazione del **calcolo iterativo** per la gestione degli interessi circolanti.

---

## 📊 Key Financial Metrics & Results

L'operazione dimostra una forte capacità di generazione di cassa e un profilo di rischio/rendimento eccellente, in linea con i target di mercato del Private Equity:

*   **Enterprise Value d'Ingresso (EV):** \$14.875,00M (Multiplo d'ingresso: 14,88x EV/EBITDA)
*   **Sponsor Equity Investito:** \$8.000,00M (54% del totale fonti)
*   **Multiple on Invested Capital (MOIC):** **2,14x**
*   **Internal Rate of Return (IRR):** **16,41%**
*   **Deleveraging (Rimborso Debito Senior):** Riduzione del debito Senior da \$5.000,00M a **\$2.947,69M** in 5 anni.

---

## 🗂️ Model Structure

Il file Excel è organizzato in modo modulare per garantire massima leggibilità e manutenibilità:

1.  **Cover / Readme:** Pagina istituzionale con titolo del Pitch Book e informazioni sul progetto.
2.  **Purchase Assumptions & Valuation:** Calcolo del prezzo di acquisto ad azione incl. un premio del 25% sul prezzo di mercato (\$95,00 → \$118,75).
3.  **Sources & Uses Table:** Struttura del capitale che unisce Debito Senior (5.0x EBITDA), Debito Mezzanino e Sponsor Equity a saldo.
4.  **Operating Model (Forecasting):** Proiezioni a 5 anni basate su una crescita del fatturato del **6,0% annuo** e margini EBITDA stabili al **19,0%**.
5.  **Free Cash Flow Calculation:** Riconciliazione dall'Utile Netto al FCF operativo, considerando CapEx (5% del fatturato) e variazioni di NWC fixed a \$30M.
6.  **Debt Schedule:** Piano di ammortamento dinamico con calcolo degli interessi (tasso al 6,0%) e rimborso opzionale guidato dalla formula `=MIN(Debito Iniziale; FCF)`.
7.  **Returns Analysis:** Sintesi finale delle metriche di rendimento dello Sponsor finanziario basata su un'ipotesi conservativa di *Multiple Neutrality* all'uscita (14,88x).

---

## 📈 Summary of Returns (Year 5 Exit)

| Voce di Bilancio / Metrica | Valore (\$M) | Note / Formule |
| :--- | :--- | :--- |
| **EBITDA Anno 5** | \$1.347,59 | Basato su crescita organica costante del 6% |
| **Multiplo di Uscita EV/EBITDA** | 14,88x | Assunzione conservativa (Multiple Neutrality) |
| **Enterprise Value di Uscita** | **\$20.052,19** | `= EBITDA * Multiplo` |
| **(-) Debito Residuo Anno 5** | -\$2.947,69 | Ridotto grazie al meccanismo di Cash Sweep |
| **Ending Equity Value** | **\$17.104,50** | Quota spettante allo Sponsor dopo il paydown |
| **Sponsor Equity Iniziale** | \$8.000,00 | Capitale proprio investito all'Anno 0 |
| **MOIC** | **2,14x** | `= Equity Finale / Equity Iniziale` |
| **IRR** | **16,41%** | `=(MOIC)^(1/5) - 1` |

---

## 🛠️ Best Practices Applicate & Formattazione

*   **Color Coding Standard:** Celle di Input (Dati fissi) in <span style="color:blue">**BLU**</span>, Formule e Calcoli automatici in **NERO**.
*   **Calcolo Iterativo Sbloccato:** Il modello gestisce nativamente il riferimento circolare nato dal collegamento tra Interessi Passivi (Debt Schedule) → Net Income (Operating Model) → Free Cash Flow → Cash Sweep.
*   **Formattazione Istituzionale:** Layout pulito in stile Investment Banking con linee di separazione contabili (bordo singolo superiore, bordo doppio inferiore per i totali).

---


*   By Marco Avellino 
*   
