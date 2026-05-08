# Woordenkraker

Gevibecoded tooltje om ludiek wachtwoorden te beoordelen.
 
Geef een wachtwoord in en klik op de knop. Een eekhoorn-hacker gaat aan het werk en kraakt het wachtwoord in 30 seconden tot 5 minuten, afhankelijk van de kwaliteit van het wachtwoord. In de tussentijd heeft een groep deelnemers de tijd om een opdracht uit te voeren. Op het einde krijgen ze een beoordeling van hun wachtwoord in kastanjes. Daarbij verandert ook de achtergrondkleur om een visuele impressie te geven van een goed (rood), middelmatig (geel-oranje), tot slecht (rood) wachtwoord.

In werkelijkheid wordt het wachtwoord niet gekraakt, maar roept de site zxcvbn aan, een javascript library die wachtwoorden een score geeft. De score loopt logaritmisch op met de tijd die het in werkelijkheid zou duren om het wachtwoord te kraken. De tool deelt deze score door vier en geeft dat aantal minuten aan de spelers. De waarde wordt begrensd tot een waarde van minimaal 30 seconden tot maximaal 5 minuten voor de speelbaarheid.

## Gebruik

Download het project en open woordenkraker.html in een browser.

De javascript runt lokaal in de browser en verstuurt niets. Er wordt ook niets opgeslagen. De tool kraakt niet echt wachtwoorden. Toch raad ik aan om geen belangrijke wachtwoorden in te geven, aangezien ik de veiligheid niet kan garanderen. Ik neem geen verantwoordelijkheid op voor eventuele wachtwoordlekken.
