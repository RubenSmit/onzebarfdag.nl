---
title: Programma en Locatie · Bruiloft Jeanine en Ruben · 27-29 | 08 | 2024
description: Drie dagen? Wat gaan jullie doen dan? Het complete programma vind je hier.
layout: default
---

{% capture card_content %}
## Programma
Ben je uitgenodigd voor de woensdag, woensdag-donderdag of dinsdag-donderdag? Klik het dan hieronder aan zodat je de juiste programma-onderdelen ziet.

<div class="w-full mt-6 text-center">Bekijk het programma voor:</div>
<div class="w-full mt-2 flex justify-center">
    <button class="py-2 px-4 border-t-2 border-b-2 border-l-2 rounded-l hover:bg-secondary hover:text-white hover:border-secondary border-secondary bg-secondary text-white" data-timeline-button="alles" onclick="changeProgram('alles')">Allesgasten (di-do)</button>
    <button class="py-2 px-4 border-t-2 border-b-2 hover:bg-secondary hover:text-white hover:border-secondary border-primary" data-timeline-button="dag" onclick="changeProgram('dag')">Daggasten (wo-do)</button>
    <button class="py-2 px-4 border-t-2 border-b-2 border-r-2 rounded-r hover:bg-secondary hover:text-white hover:border-secondary border-primary" data-timeline-button="kerk" onclick="changeProgram('kerk')">Kerkgasten (wo)</button>
</div>

{% include card_title.html title="Dinsdag 27 augustus" type="alles" %}
{% capture dinsdag_items %}
{% include timeline_item.html time="14:00" content="Inloop alles-gasten" type="alles" %}
{% include timeline_item.html time="15:00" content="Koffie en Thee" type="alles" %}
{% include timeline_item.html time="16:00" content="Burgerlijk huwelijk" type="alles" %}
{% include timeline_item.html time="18:00" content="Diner" type="alles" %}
{% include timeline_item.html time="21:00" content="Borrel en stukjes" last=true type="alles" %}
{% endcapture %}
{% include timeline.html items=dinsdag_items type="alles" %}

{% include card_title.html title="Woensdag 28 augustus" type="kerk" %}
{% capture woensdag_items %}
{% include timeline_item.html time="07:00 - 09:00" content="Ontbijt" type="alles" %}
{% include timeline_item.html time="10:00" content="Klaarmaken locatie" type="alles" %}
{% include timeline_item.html time="11:00" content="Inloop daggasten" type="dag" %}
{% include timeline_item.html time="12:00" content="Lunch" type="dag" %}
{% include timeline_item.html time="12:30" content="Groepsfoto's" type="alles" %}
{% include timeline_item.html time="13:30" content="Inloop kerkgasten" type="kerk" %}
{% include timeline_item.html time="14:00" content="Kerkdienst" type="kerk" %}
{% include timeline_item.html time="16:00" content="Receptie" type="kerk" %}
{% include timeline_item.html time="17:45" content="Uitzwaaien kerkgasten" type="kerk" %}
{% include timeline_item.html time="18:00" content="Diner" type="dag" %}
{% include timeline_item.html time="21:00" content="Feest" type="dag" %}
{% endcapture %}
{% include timeline.html items=woensdag_items type="kerk" %}

{% include card_title.html title="Donderdag 29 augustus" type="dag" %}
{% capture donderdag_items %}
{% include timeline_item.html time="09:00 - 12:00" content="Brunch" type="dag" %}
{% include timeline_item.html time="12:00" content="Opruimen" type="dag" %}
{% endcapture %}
{% include timeline.html items=donderdag_items type="dag" %}

## Locatie
*De Eik, Coevorderweg 39, Slagharen*

Onze hele bruiloft zal plaatsvinden op De Eik in Slagharen, een voormalige kloosterschool dat omgebouwd is naar een schitterende trouwlocatie.

De Eik heeft een keuken, eet-/feestzaal, woonkamer, spelletjesruimte en 20 slaapkamers. Buiten bevinden zich een terras en een prachtige voortuin waar de kerkdienst gehouden zal worden. Bij slecht weer, zal de kerkdienst plaatsvinden in de kerkzaal van het naastgelegen verzorgingshuis.
{% endcapture %}

{% include card.html title="Programma en Locatie" content=card_content %}
