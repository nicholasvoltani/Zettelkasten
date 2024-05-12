---
date: 2023-07-20
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---
![[The boundary of the set is the boundary of its complement.svg]]

up:: [[Boundary (Topology)]]

Let $S \subseteq X$ be a set in a [[Topological Space]] $(X, \tau)$. Denote the [[Closure (Topology)|Closure]] by $(\cdot)^-$ and the [[Interior (Topology)|Interior]] as $(\cdot)^\circ$.

Then its [[Boundary (Topology)|Boundary]] is 
$$
\partial S = S^- \setminus S^\circ = S^- \cap {S^\circ}^C
$$
where $\cdot^C$ is the set's [[Set Complement|Complement]].

Using that [[The closure is the complement of the interior of the complement]] and flipping the intersection, we have
$$
\partial S = {S^\circ}^C \cap {{S^C}^\circ}^C = {S^\circ}^C \setminus {(S^C)}^\circ
$$
Using that [[The interior is the complement of the closure of the complement]] yields
$$
\partial S = {S^\circ}^C \cap {{S^C}^\circ}^C = {{{S^C}^-}^C}^C \setminus {(S^C)}^\circ = {(S^C)}^- \setminus (S^C)^\circ = \partial (S^C)
$$

Thus, $\partial S = \partial (S^C)$.

%%
# Text Elements
# Embedded files
fa4f01bf08b75c2b8e22f1a28765df99d12edd85: $$(X, \tau)$$
8488b1612d1e12be841a8e0d89caf09324f4a362: $$\partial X = \overline{X} \setminus \mathring{X}$$
507c4af1caf468abba106fd6058b2c4f1ebc466b: $$\partial (X^C) = \overline{X^C} \setminus \mathring{X^C}$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "rectangle",
			"version": 225,
			"versionNonce": 1464006484,
			"isDeleted": false,
			"id": "KZt6MWcQxIwshd0qGn7s7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -114.88322877883911,
			"y": -165.84200286865234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 384.4444580078125,
			"height": 264.4444122314453,
			"seed": 356008916,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1689898316175,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 59,
			"versionNonce": 896838740,
			"isDeleted": false,
			"id": "P7XiOtlF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 214.88091446174116,
			"y": 72.48089645481461,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 43.80496547196448,
			"height": 16.687605894081706,
			"seed": 84538,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689898325390,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "fa4f01bf08b75c2b8e22f1a28765df99d12edd85",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 103,
			"versionNonce": 266975060,
			"isDeleted": false,
			"id": "aDjK4KrVJqyGIO-uF3eWI",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 25.67225217819214,
			"y": -80.2864761352539,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#b2f2bb",
			"width": 139.44439697265625,
			"height": 87.77777099609375,
			"seed": 205783508,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1689898401728,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 94,
			"versionNonce": 233949292,
			"isDeleted": false,
			"id": "zmijB2tD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 68.0336877559469,
			"y": -72.76071689637628,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 71.13567432123055,
			"height": 17.17068000857289,
			"seed": 35816,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689898462874,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "8488b1612d1e12be841a8e0d89caf09324f4a362",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 87,
			"versionNonce": 1970863060,
			"isDeleted": false,
			"id": "Gj5MVSxu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 50.868405611316014,
			"y": -104.87100287851389,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 104.4224361757445,
			"height": 18.058015278512205,
			"seed": 56464,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689898465692,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "507c4af1caf468abba106fd6058b2c4f1ebc466b",
			"scale": [
				1,
				1
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#2f9e44",
		"currentItemBackgroundColor": "#b2f2bb",
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
		"scrollX": 138.81627321243286,
		"scrollY": 239.1424102783203,
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