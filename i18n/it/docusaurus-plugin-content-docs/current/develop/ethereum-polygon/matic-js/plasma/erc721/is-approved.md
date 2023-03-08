---
id: is-aproved
title: isApproved
keywords:
- 'plasma client, erc721, isApproved, polygon, sdk'
description: 'Verifica se un token è approvato per un tokenId specificato.'
---

Il metodo `isApproved` verifica se il token è approvato per il tokenId specificato. Restituisce un valore booleano.

```
const erc721Token = plasmaClient.erc721(<token address>, true);

const result = await erc721Token.isApproved(<tokenId>);

```