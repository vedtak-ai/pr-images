# Arbeidsoppgaver – visuell gjennomgang

40 skjermbilder av funksjonene i PR #2982, tatt 14. oktober 2026 i den faktiske Kommune-appen med syntetiske testdata. App-kode: `6103c5df655659bb276f4514e6f51dcfac984d57`. Listeoversikt og filterbildet er oppdatert etter kolonnerettingen i `de560397422d5f69ed748fe9601ad9263a6f31ac`. Standardbredde 1440 px; responsive eksempler ved 1600, 1100 og 390 px.

Noen bakgrunnskort viser manglende tilleggsdata fordi testoppsettet ikke simulerer alle eksterne oppslag. Bildene dokumenterer grensesnittet, ikke live-integrasjoner eller produksjonsklarhet. Utsnitt gjengis fra appens innhold uten skjermdeling. Ingen ekte saks- eller persondata er publisert.

## Liste, kalender og saksfrister

### Samlet arbeidsliste

Oppgaver med og uten frist og saksfrister vises sammen. Personkortet lar deg fordele arbeid. Saksfrister åpner saken og fullføres ikke som vanlige oppgaver.

![Samlet arbeidsliste](00-worklist-overview.png)

### Filtre og sortering

Velg oppgavetype, fristsortering og gruppering. Vis avsluttede henter frem ferdige og forkastede oppgaver; visningsknappene avgrenser til eget, ledig eller utsatt arbeid.

![Filtre og sortering](28-list-filters.png)

### Gruppering etter sak

Valgfri gruppering samler arbeidet etter sak. Standardvisningen er én samlet liste.

![Gruppering etter sak](27-filters-grouping.png)

### Kalender med arbeid

De samme oppgavene vises på datoene sine. Visning og filtre hører til samme arbeidsflate.

![Kalender med arbeid](29-calendar-overview.png)

### Oppgaver uten frist i kalenderen

Oppgaver uten dato finnes under kalenderen, slik at de ikke forsvinner fra arbeidsflaten.

![Oppgaver uten frist i kalenderen](30-calendar-undated.png)

### Opprett fra en kalenderdag

Dagen forblir markert mens oppgaven skrives. Datoen fylles inn automatisk. Oppgavevinduet åpnes ved kalenderdagen og bytter automatisk mellom høyre og venstre side etter tilgjengelig plass.

![Opprett fra en kalenderdag](02-calendar-create.png)

### Åpne oppgave i kalenderen

Et eksisterende kalenderpunkt åpner detaljer ved punktet, med samme oppgavehandlinger som ellers.

![Åpne oppgave i kalenderen](03-calendar-task-details.png)

### Saksfrist i listen

Saksfristen beholder sakens ansvarlige og egne handlinger. Åpne sak tar deg til saksbehandlingen.

![Saksfrist i listen](26-case-deadline.png)

## Oppretting, redigering og fullføring

### Ny oppgave på en sak

Skriv oppgaven, velg ansvarlig og eventuell frist. Beskrivelse og tilknyttet sak er tilgjengelige uten å dominere skjemaet.

![Ny oppgave på en sak](31-new-task.png)

### Lagret utkast

Lagre utkast legger oppgaven til side. Den kan fortsettes fra Oppgaver i toppmenyen.

![Lagret utkast](33-saved-draft.png)

### Detaljer under oppgaveraden

Klikk på en oppgave for å utvide den i listen. Markeringer, kommentarer og historikk ligger i detaljene.

![Detaljer under oppgaveraden](04-inline-details.png)

### Handlingsmeny

Rediger, Endre frist og Forkast oppgave ligger under menyen med tre prikker.

![Handlingsmeny](05-actions.png)

### Redigering

Rediger gir tilgang til felter, status og markeringer. Lagre endringer bekrefter oppdateringen.

![Redigering](06-edit.png)

### Kommentar og endring av frist

Kommentarer vises på oppgaven. Endre frist oppdaterer datoen uten å endre oppgavens status.

![Kommentar og endring av frist](07-comment-and-deadline.png)

### Fullføring med angremulighet

Marker fullført viser bekreftelse etter lagring. Angre fullføring gjenoppretter den tidligere statusen.

![Fullføring med angremulighet](08-completed-undo.png)

### Oppgaven ved siden av saken

Oppgaven kan leses mens saken behandles. Gå til oppgaven åpner den i arbeidslisten. Fullføring ligger nederst.

![Oppgaven ved siden av saken](11-case-task-panel.png)

## Personvalg og rettigheter

### Fordeling direkte i listen

Bruk det samme personkortet som i byggesakslisten, uten først å åpne oppgavedetaljene.

![Fordeling direkte i listen](10-assign-from-list.png)

### Personer uten sakstilgang

Søk viser hvem som kan motta oppgaven. Personer uten tilgang til en tilknyttet sak er deaktivert og har en forklaring.

![Personer uten sakstilgang](09-people-access.png)

### Saksbehandler tar en ledig oppgave

Når en saksbehandler tar en ufordelt oppgave, kan vedkommende velge seg selv. Lederens bredere personvalg er ikke tilgjengelig.

![Saksbehandler tar en ledig oppgave](12-self-claim.png)

## Markeringer og navigering

### Tekstmarkering

En tekstmarkering lagres med originalteksten og lenke tilbake til siden.

![Tekstmarkering](32-text-reference.png)

### Markering av en hel seksjon

En stor sjekklisteseksjon beholder rammen mens oppgaven opprettes. Markeringen legges i den samme oppgaven.

![Markering av en hel seksjon](13-section-selection.png)

### Tilbake til markert innhold

Klikk på en lagret markering åpner riktig visning og fremhever målet. Fremhevingen vises kort og fader ut; et nytt klikk gjentar den.

![Tilbake til markert innhold](14-reveal-reference.png)

### Dra for å markere et område

I samme markeringsmodus velger et klikk innhold, mens et drag tegner området som skal lagres som utsnitt. Den separate Bildeutsnitt-knappen og beskjæringsdialogen er fjernet.

![Dra for å markere et område](15-image-crop.png)

### Utsnitt i oppgaven

Utsnittet gjengis direkte fra appens innhold, uten skjermdeling eller tillatelsesdialog. Klikk på lenken for å gå tilbake og fremheve området. Bildet viser faktisk tekst fra det valgte området med syntetiske saksdata.

![Utsnitt i oppgaven](16-image-attached.png)

## Oppgaver og varsler i toppmenyen

### Hurtigvisning av en oppgave

Oppgaver i toppmenyen gir tilgang til aktive oppgaver, eksisterende markeringer, kommentar og fullføring.

![Hurtigvisning av en oppgave](17-header-preview.png)

### Oppgaveoversikt på bred skjerm

Panelet er forankret til høyrekanten. Det har ingen flyttehåndtak.

![Oppgaveoversikt på bred skjerm](19-panel-Oppgaver-1600.png)

### Varsler på bred skjerm

Varsler bruker samme plassering. Bare varsler, oppgaveoversikten eller oppgavevinduet kan være åpent om gangen.

![Varsler på bred skjerm](19-panel-Varsler-1600.png)

### Oppgaveoversikt på smalere skrivebord

Panelet beholder høyreforankringen ved 1100 pikslers bredde.

![Oppgaveoversikt på smalere skrivebord](19-panel-Oppgaver-1100.png)

### Varsler på smalere skrivebord

Varselpanelet tilpasser seg samme bredde og plassering.

![Varsler på smalere skrivebord](19-panel-Varsler-1100.png)

## Matrikkelføring og automatikk

### Matrikkelføring sammen med oppgaver

Matrikkelarbeid vises i arbeidslisten sammen med vanlige oppgaver, med egne rettigheter og handlinger.

![Matrikkelføring sammen med oppgaver](22-mixed-worklist.png)

### Ta en matrikkeloppgave

Matrikkeloppgaver beholder den etablerte flyten for å ta, frigi og fullføre arbeidet.

![Ta en matrikkeloppgave](23-matrikkel-details.png)

### Tabell for matrikkelarbeid

Den eksisterende tabellvisningen og lagrede visninger er fortsatt tilgjengelige under matrikkelføring.

![Tabell for matrikkelarbeid](24-table-view.png)

### Opprett automatisk oppgaveregel

Administrator kan definere oppgave og mottaker for nye byggesaker, eventuelt begrenset til en søknadstype.

![Opprett automatisk oppgaveregel](20-automation-form.png)

### Oversikt over regler

Lagrede regler kan endres eller pauses. Dette er regler for nye saker, ikke en generell regelmotor.

![Oversikt over regler](21-automation-rule.png)

## Mobil og feilsituasjoner

### Oppretting på mobil

Oppgavevinduet tilpasses 390 pikslers bredde.

![Oppretting på mobil](34-mobile-composer.png)

### Oppgavedetaljer på mobil

Detaljene ligger under raden også på smal skjerm, med markeringer og kommentarer.

![Oppgavedetaljer på mobil](18-mobile-details.png)

### Oppgaveoversikt på mobil

Hurtigpanelet holdes innenfor skjermen.

![Oppgaveoversikt på mobil](19-panel-Oppgaver-390.png)

### Varsler på mobil

Varsler følger den samme responsive plasseringen.

![Varsler på mobil](19-panel-Varsler-390.png)

### Samtidig endring av oppgaven

Ved revisjonskonflikt vises feilen, og oppgaven forblir tilgjengelig. Den presenteres ikke som fullført før lagringen lykkes.

![Samtidig endring av oppgaven](35-concurrent-update-error.png)

### Deler av listen kunne ikke lastes

Hvis saksfristene ikke kan hentes, vises en forklaring samtidig som tilgjengelige oppgaver fortsatt kan brukes.

![Deler av listen kunne ikke lastes](25-partial-load-warning.png)

