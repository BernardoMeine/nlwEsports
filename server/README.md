# Back-end

## Entidades

### Game

id
title
bannerUrl

### Ad

id
gameId
name
yearsPlaying
discord
weekDays
hourStart
hourEnd
useVoiceChannel
createdAt

## UseCases 

- Listagem de games com contagem de anúncios (GET)
- Criação de novo anúncio (POST)
- Listagem de anúncios por game (GET)
- Buscar discord pelo ID do anúncio (GET)