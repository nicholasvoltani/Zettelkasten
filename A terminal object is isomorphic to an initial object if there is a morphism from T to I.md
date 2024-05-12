---
date: 2023-08-21
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---

up:: [[028 MOC Category Theory]]

![[A terminal object is isomorphic to an initial object if there is a morphism from T to I.svg]]

We have that every [[Initial Object]] $I$ has a unique morphism coming out of it towards any other object in a [[Category]] $C$, and that every [[Terminal Object]] $T$ has a unique object coming into it. Thus, there is only one morphism from $I$ to $T$; call it $I \overset{f}{\to} T$. 

In the case where $\exists \varphi \in Hom(T,I)$[^1], we can see that
$$
\begin{cases}
1_I &= f; \varphi\\
1_T &= \varphi ; f
\end{cases}
$$
Therefore, we have that $\varphi$ is the inverse of $f$ ─ therefore, $f$ is an isomorphism.
# Corollaries
When there is a morphism from a terminal object to an initial object, we have that they are isomorphic. In this case, they will be isomorphic to a [[Zero Object]]. Thus, there can only be one zero object (up to isomorphism) in a category.

---
### References
- KASHIWARA, Masaki; SCHAPIRA, Pierre, **Categories and Sheaves**, Berlin, Heidelberg: Springer Berlin Heidelberg, 2006.

[^1]: Note that this doesn't make $T$ stop being a terminal object; it is an additional property that it possesses, aside from being terminal.

%%
# Text Elements
# Embedded files
059bec3371a84dd1f64780290f0e1bdce7e2bad3: $$I$$
906cb0631b5d9a2159aa6a5a0588422942246fb5: $$T$$
8431cb16a483a285b4e5904c9e02998d60315314: $$\exists ! f$$
4f3c97e67df1549fedf548039399554a219ce9fb: $$\varphi$$
e3dbd16b901a857d578f1a0b9f9b3aa9e84d2970: $$\exists! 1_I$$
3571f162ba49f93d9760f75e00bbf2fd3c34bf23: $$\exists! 1_T$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "image",
			"version": 48,
			"versionNonce": 256642782,
			"isDeleted": false,
			"id": "m5MAWMeh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -122.04495884939726,
			"y": -72.85006093820708,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.491933384829668,
			"height": 11.360751148875089,
			"seed": 31318,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "2DQuH_Ij6aXEPTH7-qgdw",
					"type": "arrow"
				},
				{
					"id": "uYFmqWH-0RtYQZ2liaMvr",
					"type": "arrow"
				}
			],
			"updated": 1692660518531,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "059bec3371a84dd1f64780290f0e1bdce7e2bad3",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 68,
			"versionNonce": 1718048258,
			"isDeleted": false,
			"id": "7WfQ2PT6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 61.64501971022675,
			"y": -75.0921077695958,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20.360389351519153,
			"height": 11.787593835090036,
			"seed": 2335,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "2DQuH_Ij6aXEPTH7-qgdw",
					"type": "arrow"
				}
			],
			"updated": 1692660518531,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "906cb0631b5d9a2159aa6a5a0588422942246fb5",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 107,
			"versionNonce": 383943454,
			"isDeleted": false,
			"id": "s6GV0KmmdaxUMaHtDEUGM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -104.66315841674805,
			"y": -75.28411102294922,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 167.86679077148438,
			"height": 36.51483154296875,
			"seed": 1839822850,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692660518531,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					78.60833740234375,
					-35.50053405761719
				],
				[
					167.86679077148438,
					1.0142974853515625
				]
			]
		},
		{
			"type": "arrow",
			"version": 294,
			"versionNonce": 550585794,
			"isDeleted": false,
			"id": "2DQuH_Ij6aXEPTH7-qgdw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": -110.35326766967773,
			"y": -22.585154818586748,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 175.981201171875,
			"height": 37.529144287109375,
			"seed": 135680926,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692660518531,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "7WfQ2PT6",
				"focus": -0.985812738210952,
				"gap": 7.247435287794012
			},
			"endBinding": {
				"elementId": "m5MAWMeh",
				"focus": 0.8811549067094964,
				"gap": 3.5839964875656136
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					78.60833740234375,
					-35.50053405761719
				],
				[
					175.981201171875,
					2.0286102294921875
				]
			]
		},
		{
			"type": "image",
			"version": 55,
			"versionNonce": 69234526,
			"isDeleted": false,
			"id": "9kYCtb2x",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -37.30210392876254,
			"y": -130.6248363121246,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.494443758403985,
			"height": 15.337120744366354,
			"seed": 81931,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692660518531,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "8431cb16a483a285b4e5904c9e02998d60315314",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 78,
			"versionNonce": 535248258,
			"isDeleted": false,
			"id": "ydPQqAVF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -28.954723358154297,
			"y": -13.811653137207031,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.156468376279893,
			"height": 13.5400640077266,
			"seed": 89548,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692660518531,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "4f3c97e67df1549fedf548039399554a219ce9fb",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 138,
			"versionNonce": 592892830,
			"isDeleted": false,
			"id": "1S5PXhY3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -205.8645133972168,
			"y": -71.63394927978516,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 30.463092423455635,
			"height": 14.706320480288927,
			"seed": 16426,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692660518531,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e3dbd16b901a857d578f1a0b9f9b3aa9e84d2970",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 73,
			"versionNonce": 15220034,
			"isDeleted": false,
			"id": "L2LNVoM9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 122.51390518093146,
			"y": -92.53912350605364,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 31.496031496047245,
			"height": 14.224014224021335,
			"seed": 75379,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692660518531,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "3571f162ba49f93d9760f75e00bbf2fd3c34bf23",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 164,
			"versionNonce": 246853598,
			"isDeleted": false,
			"id": "RTCrraFRlIVgAntbsRQDn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 74.86806106567383,
			"y": -70.09869329326756,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.7293701171875,
			"height": 32.98130444454213,
			"seed": 919885442,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692660518531,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					31.95050048828125,
					-17.864881854666017
				],
				[
					51.7293701171875,
					-1.8322878002655614
				],
				[
					30.93621826171875,
					15.116422589876112
				],
				[
					3.55010986328125,
					6.413048647516806
				]
			]
		},
		{
			"type": "arrow",
			"version": 363,
			"versionNonce": 1630749954,
			"isDeleted": false,
			"id": "uYFmqWH-0RtYQZ2liaMvr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": -170.99867098704428,
			"y": -63.58518426638892,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.7293701171875,
			"height": 35.28335081135457,
			"seed": 502178014,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692660518531,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "m5MAWMeh",
				"focus": 0.21271742485674988,
				"gap": 3.0532206105832813
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					31.95050048828125,
					-19.111824237925
				],
				[
					51.7293701171875,
					-1.960178784100014
				],
				[
					30.93621826171875,
					16.171526573429574
				],
				[
					6.084782037781906,
					6.781423112089563
				]
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 0,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 343.07986068725586,
		"scrollY": 270.8865460601015,
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