<!-- prevent jekyll yaml parsing -->

  **Vysoké učení technické v Brně, Fakulta elektrotechniky a komunikačních technologií, Ústav radioelektroniky**  

---

# Bakalářská práce: Laboratorní úloha pro hodnocení vizuální kvality komprimovaných obrazů pomocí objektivních a subjektivních metrik


Tento repozitář obsahuje veškeré zdrojové kódy, instalační balíčky, materiály a naměřená data z praktické části bakalářské práce zaměřené na hodnocení kvality obrazu pomocí objektivních a subjektivních metrik. Cílem repozitáře je zajistit plnou reprodukovatelnost dosažených výsledků a usnadnit případný další vývoj.

Autor: Daniel Kroužil  
Akademický rok: 2025/2026  
Licence: MIT  

## Obsah repozitáře
- **Zdrojové kódy:** MATLAB skripty pro obě vytvořené aplikace (vyvinuto v prostředí MATLAB R2023b).
- ***[Instalační balíčky:](https://github.com/256-514/Bc-Image-Quality-Analyzer/releases)*** Zkompilované verze aplikací připravené pro běžné uživatele (dostupné v sekci *[Releases](https://github.com/256-514/Bc-Image-Quality-Analyzer/releases)*).
- **Výsledky subjektivních testů:** Tabulka s odpověďmi všech respondentů (dostupné v *[repozitáři](https://github.com/256-514/Bc-Image-Quality-Analyzer/releases)*).

## Popis aplikací
- **Objektivní metriky** – aplikace zaměřená na automatizovanou komprimaci obrazu vybranými kodeky a následný výpočet objektivních metrik kvality.
- **Subjektivní testy** – aplikace sloužící pro uživatelské hodnocení vizuální kvality komprimovaných obrazů.

## Instalace a první spuštění aplikací
Pro běžné používání aplikací **není vyžadována** instalace plného programu MATLAB.
- Stáhněte si [instalační balíčky](https://github.com/256-514/Bc-Image-Quality-Analyzer/releases/tag/v1.1) *(.exe)*.
- Spusťte instalátor. Pro běh aplikace postačí samostatné prostředí MATLAB Runtime. Toto prostředí je součástí instalačního balíčku a v případě potřeby se nainstaluje automaticky.
> [!IMPORTANT]   
> Při úplně prvním spuštění nainstalované aplikace je vyžadováno připojení k internetu. Aplikace si automaticky stáhne nezbytné [doplňkové knihovny](https://github.com/256-514/Bc-Image-Quality-Analyzer/releases/tag/v1.0) pro práci s multimédii (FFmpeg a heif-enc). Velikost stahovaných dat je přibližně 100 MB.

## Informace pro vývojáře
V případě zájmu o nahlédnutí nebo úpravu aplikací jsou zdrojové kódy dostupné jako samostatné ZIP archivy v sekci *[Releases (v1.1)](https://github.com/256-514/Bc-Image-Quality-Analyzer/releases/tag/v1.1)*.

---
