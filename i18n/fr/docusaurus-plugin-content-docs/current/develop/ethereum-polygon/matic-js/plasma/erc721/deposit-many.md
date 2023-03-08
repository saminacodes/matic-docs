---
id: deposit-many
title: deplasmaitMany
keywords:
- 'plasma client, erc721, deplasmaitMany, polygon, sdk'
description: 'Déposez plusieurs jetons de l''Ethereum à la chaîne de Polygone.'
---

`deplasmaitMany`La méthode  peut être utilisée pour déposer plusieurs jetons de l'Ethereum à la chaîne de polygone.

```
const erc721RootToken = plasmaClient.erc721(<root token address>, true);

const result = await erc721RootToken.deplasmaitMany([<token id1>,<token id2>], <user address>);

const txHash = await result.getTransactionHash();

const txReceipt = await result.getReceipt();

```