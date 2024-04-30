---
Date: 2023-07-08
tags:
  - mathematics
aliases:
  - Free
excalidraw-open-md: true
excalidraw-plugin: parsed
---
![[Free Group Action.svg]]

up:: [[Group Action]]

A group action of a [[Group (Mathematics)|Group]] $G$ over a set $X$ is said to be *free* if all non-identity elements of $G$ "push points away" (i.e. only the identity stabilizes points). That is,
$$\forall g \in G: \forall x \in X: g \cdot x = x\implies g = e_G$$

Equivalently, [[A group action is free iff all its stabilizers are trivial]]: only the identity element keeps elements intact, while all others "induce movement" upon $X$.

## Properties
[[Free Group Actions induce a bijection between the group and a point's orbit]], since all group elements map to distinct points in the space. If it weren't the case, i.e. there were $g \neq h \mid g \cdot x = h \cdot x = x$, then there'd be a non-identity element $(g^{-1} h): x \mapsto x$, which has to be the identity if the action is free.

%%
# Text Elements
# Embedded files
509c53b06bc78ac76961cbdceecf372d075a23f5: $$\alpha: SO(2) \times \mathbb{R}^2 \setminus \{0\} \to \mathbb{R}^2 \setminus \{0\}$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "arrow",
			"version": 154,
			"versionNonce": 426532266,
			"isDeleted": false,
			"id": "AhsG3OtEkuSAsUynNAG8v",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 20.602985382080078,
			"y": 531.0115365982056,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.4210854715202004e-14,
			"height": 246.4751434326172,
			"seed": 511488182,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714504059832,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "y5UkEZ4KkrSS1E6HoBimR",
				"focus": -0.029906535829042655,
				"gap": 30.979561705261332
			},
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
					1.4210854715202004e-14,
					-246.4751434326172
				]
			]
		},
		{
			"type": "arrow",
			"version": 207,
			"versionNonce": 2562154,
			"isDeleted": false,
			"id": "HHaNJyxG0oE3SZXz9AOId",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -125.96348190307617,
			"y": 427.5528268814087,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 295.668701171875,
			"height": 0,
			"seed": 1213278710,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714504059832,
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
					295.668701171875,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 307,
			"versionNonce": 490502954,
			"isDeleted": false,
			"id": "FaFVM9ikbA2ry2Y0I2_Et",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -10.840435028076172,
			"y": 394.0809335708618,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 63.393920898437514,
			"height": 64.0447967930176,
			"seed": 1271167798,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714504059832,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 434,
			"versionNonce": 521635306,
			"isDeleted": false,
			"id": "ovmJzJMgNyOHHun8nxNfF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -30.202617645263658,
			"y": 373.50795857904996,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 102.95166015624999,
			"height": 104.00868191721753,
			"seed": 1060873334,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714504059832,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 549,
			"versionNonce": 784545962,
			"isDeleted": false,
			"id": "y5UkEZ4KkrSS1E6HoBimR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -50.488689422607415,
			"y": 351.98370340777956,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 146.566650390625,
			"height": 148.07147448632082,
			"seed": 612083126,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "AhsG3OtEkuSAsUynNAG8v",
					"type": "arrow"
				}
			],
			"updated": 1714504059832,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 396,
			"versionNonce": 468357994,
			"isDeleted": false,
			"id": "bF4zaqxr5R4ZS-W9V8Gbv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 14.009967803955078,
			"y": 419.69882762334316,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.678833007812514,
			"height": 12.809008688054984,
			"seed": 2091482870,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714504059832,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 82,
			"versionNonce": 148411946,
			"isDeleted": false,
			"id": "i9aaagFD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 57.63654961364087,
			"y": 284.8052925070638,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 238.33741255250342,
			"height": 18.733945091463152,
			"seed": 1548365878,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1714504059832,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "509c53b06bc78ac76961cbdceecf372d075a23f5",
			"scale": [
				1,
				1
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#f5faff",
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
		"scrollX": 265.27332432159096,
		"scrollY": -202.25135135650635,
		"zoom": {
			"value": 2
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#8AC4FFFF",
			"Regular": "#D1E8FFFF"
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