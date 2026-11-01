# Zanzibar Buildings & BRN Lookup MCP (Tanzania)

[Kiswahili](#kiswahili)

Connect your AI assistant (Claude, ChatGPT, Cursor) to [BumiAtlas](https://bumiatlas.com) for Zanzibar property research through the Model Context Protocol (MCP).

This listing is a focused entry point for:

- ~492k building footprints on Unguja and Pemba from the Commission for Lands' (COLA) building register, published on ZanSDI
- Building lookup by building registration number (BRN, `120G40004`) or coordinates
- Registered footprint area
- Satellite and street map images of a building and its neighbours, labelled by BRN

Buildings, not land parcels: Zanzibar's parcels aren't published as data, and mainland Tanzania isn't covered. No owners or occupants.

## Connect

```
https://bumiatlas.com/mcp/tanzania
```

Add it as a custom connector in any MCP client and sign in with Google. Tools, examples and data notes: [bumiatlas.com/mcp-docs/tanzania](https://bumiatlas.com/mcp-docs/tanzania).

- **Claude:** Settings → Connectors → Add custom connector, paste the URL, then Connect.
- **ChatGPT:** Settings → Apps & Connectors → Advanced → Developer mode, then Create with the URL and OAuth authentication.

## Tools

| Tool | Description |
|---|---|
| `TZ_building_search` | Find buildings by BRN or `latitude, longitude`; each result is the whole record, the footprint as GeoJSON on request |
| `TZ_building_image` | Satellite or street map image of a building or point, with every footprint in view outlined and labelled with its BRN |

## Example prompts

- *"Which building is at -5.17008, 39.79258?"*
- *"Look up building 92H20040 and show it on satellite imagery."*
- *"Show the buildings around this point."*
- *"How large is this building's footprint?"*

## Data source

Buildings © Commission for Lands, Zanzibar (COLA), via ZanSDI. A copy of public data for research, not a legal record.

## Kiswahili

Unganisha msaidizi wako wa AI (Claude, ChatGPT au Cursor) na [BumiAtlas](https://bumiatlas.com) kupitia Model Context Protocol (MCP) kutafiti majengo ya Zanzibar.

- Takriban majengo 492,000 ya Unguja na Pemba kutoka Kamisheni ya Ardhi (COLA)
- Tafuta kwa namba ya usajili wa jengo (BRN, `120G40004`) au kwa viwianishi (latitudo, longitudo)
- Picha za setilaiti na ramani za jengo na majengo jirani

Hakuna majina ya wamiliki wala wakazi.

**Kuunganisha:** ongeza `https://bumiatlas.com/mcp/tanzania` kama custom connector kwenye MCP client yako na uingie kwa Google. Majina ya zana ni ya Kiingereza, lakini msaidizi anaweza kujibu kwa Kiswahili.
