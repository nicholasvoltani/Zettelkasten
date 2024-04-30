---
Date: 2023-07-20
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---
![[The boundary of the boundary is a subset of the boundary.svg]]

up:: [[Boundary (Topology)]]

Let $S \subseteq X$ be a subset of a [[Topological Space]] $(X, \tau)$.

Let $\partial S$ be its [[Boundary (Topology)|Boundary]]. Then the boundary of the boundary of $S$ is 
$$\partial \partial S = \overline{\partial S} \setminus \mathring{\partial S}$$
Since [[The boundary is a closed set]], we have that
$$\partial \partial S = \partial S \setminus \mathring{\partial S} \subseteq \partial S$$

For equality, we have that [[The boundary of the boundary is the boundary iff the boundary's interior is empty]].

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 27](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap27.pdf)

%%
# Text Elements
# Embedded files
c98e52a226a1c2337bb33cc606a46d41e5087da4: $$(X, \tau)$$
cb98af622e1516c98248e62a963e5d80039e3aab: $$\partial S$$
990da65909d40324fecbf1464cea8d83c81c9363: $$S$$
e6bf7815d14f961cdbdc32171141bb703bea7dc6: $$\partial \partial S$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "rectangle",
			"version": 143,
			"versionNonce": 1190049876,
			"isDeleted": false,
			"id": "nvyOs7KmwGDhfPWgPS2pC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -126.82560025728674,
			"y": -150.41467461219202,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 352.3982985343571,
			"height": 225.76927185058594,
			"seed": 1075631060,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1689898717778,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 160,
			"versionNonce": 1857464044,
			"isDeleted": false,
			"id": "7w9fQRwC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 181.2189739355522,
			"y": 53.715509647691164,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.53226678232289,
			"height": 13.536101631361102,
			"seed": 53238,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689898717778,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "c98e52a226a1c2337bb33cc606a46d41e5087da4",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "diamond",
			"version": 226,
			"versionNonce": 2057080276,
			"isDeleted": false,
			"id": "pWCVh-MmeDk-ci0zesYvO",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -31.29053817898918,
			"y": -103.54839602524859,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 165.83451090151553,
			"height": 118.51761846559054,
			"seed": 2027562836,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689898717778,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 479,
			"versionNonce": 1973086572,
			"isDeleted": false,
			"id": "peySwg2NC-7qDGnWlgk-G",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -33.09306783764214,
			"y": -105.3509009296593,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 168.88497807939885,
			"height": 122.60798660657805,
			"seed": 406565588,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689898717778,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 180,
			"versionNonce": 1582047060,
			"isDeleted": false,
			"id": "vDBucxZ0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 45.231593952106465,
			"y": -93.2020274850127,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.756508455268046,
			"height": 7.653905073160827,
			"seed": 83114,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689898726290,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "cb98af622e1516c98248e62a963e5d80039e3aab",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 188,
			"versionNonce": 1272110060,
			"isDeleted": false,
			"id": "eGoEjD8A",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 44.252667684403065,
			"y": -50.93524878160724,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.600646186815256,
			"height": 9.733764124543505,
			"seed": 7925,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689898717778,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "990da65909d40324fecbf1464cea8d83c81c9363",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 318,
			"versionNonce": 1655145452,
			"isDeleted": false,
			"id": "ZXoK1x80",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 44.81966540116306,
			"y": -110.59834381898521,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.175996120867273,
			"height": 6.279722532772665,
			"seed": 38982,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689898767797,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e6bf7815d14f961cdbdc32171141bb703bea7dc6",
			"scale": [
				1,
				1
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#f08c00",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 0,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 166.7817244276082,
		"scrollY": 243.05265221228967,
		"zoom": {
			"value": 2
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		},
		"objectsSnapModeEnabled": false
	},
	"files": {}
}
```
%%