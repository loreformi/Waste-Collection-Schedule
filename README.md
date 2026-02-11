# Waste Collection Schedule – UI Enhanced

Fork migliorato di [mampfes/hacs_waste_collection_schedule](https://github.com/mampfes/hacs_waste_collection_schedule) con UI moderna, icone animate e card Lovelace pronte all’uso.

## Funzionalità

- Icone SVG animate per carta, plastica, vetro, organico e indifferenziato
- Sensori template: `Waste Today`, `Waste Tomorrow`, `Next Waste Collection`
- Card Lovelace con colori dinamici (rosso oggi, arancione domani, verde in anticipo)

## Installazione

1. Copia `custom_components/waste_collection_schedule` in `/config/custom_components/`
2. Copia `www/waste_icons` in `/config/www/`
3. Copia `templates/waste_sensors.yaml` in `/config/templates/`
4. Aggiungi la card in Lovelace (es. `lovelace/waste_cards.yaml`)
5. Riavvia Home Assistant

## Personalizzazione

Puoi modificare le icone SVG in `/local/waste_icons/` o cambiare i colori nella card.
