# Modul 5

## Dag 1 - TypeScript, commits och felsökning

Bad om:

Copilot: Hjälp att förstå TypeScript-uppgifterna samt ett Git-problem där två commits representerade samma logiska ändring.
Victor: "Resonemang kring TypeScript-observationer, JavaScript-beteenden och commit-historik."

(GPT-6) Luna: Git-scenariot du nämner är ett bra tillfälle att göra en extra noggrann kontroll.

Fick:

Copilot: Förklaringar kring typeof, == vs ===, null vs NULL samt hjälp att analysera commit-historiken.
Victor: "Förklaringar, motargument, verifieringar och en del felslut som sedan verifierades mot faktisk output."

Stämde:

Copilot: typeof, == vs ===, null vs NULL, flyttal och öppettidslogiken efter kontroll i Console.
Victor: (Inget var fel. Det var jag som missade min egna kod. 15 var tiden. Fick en blankning i huvudet och trodde 15=>Faktiskt Klockslag just nu. Japp.)

Fel eller överdrivet:

Copilot: En analys missade först kolumnen "Vad sa TypeScript?" och fick korrigeras efter kontroll mot faktiska resultat.
Victor: "En analys missade kolumnen "Vad sa TypeScript?" och fick korrigeras efter kontroll mot källmaterialet."

Jag gjorde:

Copilot: Körde koden själv, verifierade resultaten i Console, fyllde i förutsägelserna och slog ihop två relaterade commits till en mer korrekt historik.

Victor: "Verifierade alla påståenden mot faktisk output, rättade commit-historiken och fyllde i förutsägelserna."

Lärde mig:

=== jämför både typ och värde.
Copilot: Flyttal lagras inte exakt. TypeScript kan varna men JavaScript avgör vad som händer vid körning.
Victor: Små skillnader i syntax kan ge stora skillnader i resultat. Observation slår antaganden.
(GPT-6) Luna: Git-scenariot du nämner är ett bra tillfälle att göra en extra noggrann kontroll.

## Dag 2 - Loopar, funktioner och scope

Bad om:

Copilot: Ett lugnt bollplank, en sak i taget, som granskar Victors egna lösningar och hjälper till att upptäcka misstag.
Victor: "It's valuable for me to just have someone to discuss and spot mistakes when you see them."

Fick:

Copilot: Förklarade bland annat skillnaden mellan moms som läggs ovanpå ett pris och moms som redan ingår (momsandelen blir `pris * 12 / 112`), granskade funktionerna mot testerna och hjälpte till med scope och felsökning i DevTools.
Victor: Skrev implementationerna själv, provade dem i webbläsaren och använde Luna som bollplank.

Stämde:

Copilot: Alla 16 tester visades gröna. Scope-förutsägelserna stämde med körningen. Victor körde `npm run typecheck`; utdraget visade `tsc --noEmit` utan rapporterade diagnostikfel.
Victor: "Observing carefully is actually harder than it seems."

Fel eller överdrivet:

Inga noterbara fel. Endast mild förvirring av Victor 🫠

- Step with F10 and watch total.

-+ Observe a few iterations: the same breakpoint fires once per list item.

-+ Once you’ve seen `total` accumulate, resume execution.

Jag gjorde:

Copilot: Granskade README, källkod, tester, webbläsarresultat och Git-historik. Jag föreslog beräkningen för inkluderad moms, men ändrade inte källkoden; Victor skrev och testade implementationerna. Git-historiken visade 15 commits före `origin/main`; Victor bekräftade senare att allt var committat och pushat.
