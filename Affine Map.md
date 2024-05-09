---
Date: " 2024-04-30"
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---

up:: [[Affine Space]]
![[Affine Map.svg]]

An affine transformation is a map which preserves affine structures ─ i.e. it preserves, in particular, "distances" between points in the set (with respect to the associated group action).

A map between affine spaces $f: (A_M, V_M, +_M) \to (A_N, V_N, +_N)$ is said to be an affine transformation if there is a [[Linear Transformation]] between their respective vector spaces $L: V_M \to V_N$ (which is called the **underlying linear map of $f$**) such that
$$
\forall A \in A_M, \forall v \in V_M: f(A + v) = f(A) + L(v)
$$
Equivalently, one can say that, for any pair of points $A, B \in V_M$, we have that
$$
\overrightarrow{f(A)f(B)} = L\left(\overrightarrow{AB}\right)
$$

## Properties
- [[The underlying linear map of an affine map is unique]]
- An affine map which is bijective is an [[Affine Isomorphism]]

---
### References
- [Affine transformation - Wikipedia](https://en.wikipedia.org/wiki/Affine_transformation)

%%
# Text Elements
# Embedded files
2797a63948653facdebe06c5d1d424f62ec1465b: $$P$$
462832ba76f305369bc72b6f28f1951b51659158: $$P + v$$
a8947431433e0f539b7bc1f093817a893ba562f0: $$A(P)$$
618ceabe15b773d860864554952296282b59ccb8: $$L(v)$$
1b09f2c897b4623e976b3f2561fe2c2a3af811b4: $$v$$
61f49bc9e6d420226dd046c9403e670cc4a123e2: $$A: (E, V) \to (E', V')$$
6072ba07af638ec22dfa7024ab6b52e1ee7733c7: $$L: V \to V'$$
43de7ba3298c6049b0a4eaff52d0e1b3d4b56f93: $$A(P + v) = A(P) + L(v)$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "freedraw",
			"version": 5,
			"versionNonce": 1113785532,
			"isDeleted": false,
			"id": "7DzuBCtgcOG-sRKjaacAv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -98.66313171386719,
			"y": 67.49129486083984,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 1302801596,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689519446292,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.0001,
					0.0001
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 5,
			"versionNonce": 1288287492,
			"isDeleted": false,
			"id": "Sj4Q5oI0Pssbmxaey2vnx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -51.99650573730469,
			"y": -100.84200286865234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 1203489924,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689519446292,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.0001,
					0.0001
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "arrow",
			"version": 160,
			"versionNonce": 968395476,
			"isDeleted": false,
			"id": "ZpQWs7X3yUyuxPM56abTS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -51.44093322753906,
			"y": -101.39757537841797,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 201.66659545898438,
			"height": 0.5555419921875,
			"seed": 12785212,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689902047484,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ZE4WgTe7",
				"focus": 2.348712289126317,
				"gap": 9.396740134713234
			},
			"endBinding": {
				"elementId": "PlAfgAEv",
				"focus": -1.241564721357362,
				"gap": 4.00563383102417
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
					201.66659545898438,
					-0.5555419921875
				]
			]
		},
		{
			"type": "arrow",
			"version": 141,
			"versionNonce": 1233653844,
			"isDeleted": false,
			"id": "LetlY4t4XhBUwz7Kq5Gcb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -98.66313171386719,
			"y": 67.49129486083984,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 199.99993896484375,
			"height": 0.555511474609375,
			"seed": 341469700,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689902047484,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "SOhjVDNR",
				"focus": -1.7135678465762463,
				"gap": 3.9444427490234375
			},
			"endBinding": {
				"elementId": "zPE95SRD",
				"focus": 2.333738888933377,
				"gap": 11.50006103515625
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
					199.99993896484375,
					0.555511474609375
				]
			]
		},
		{
			"type": "arrow",
			"version": 109,
			"versionNonce": 273343956,
			"isDeleted": false,
			"id": "WN2SZLqluDzzAgN5iAvIb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -99.21873474121094,
			"y": 66.93575286865234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 46.666656494140625,
			"height": 165.5555419921875,
			"seed": 1908401980,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689902047484,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "SOhjVDNR",
				"focus": 0.5736344911130382,
				"gap": 4.4999847412109375
			},
			"endBinding": {
				"elementId": "ZE4WgTe7",
				"focus": -0.6337718644134818,
				"gap": 12.174526389596046
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
					46.666656494140625,
					-165.5555419921875
				]
			]
		},
		{
			"type": "arrow",
			"version": 193,
			"versionNonce": 1930890068,
			"isDeleted": false,
			"id": "aMniQSkshoAM46CnbAT_c",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 104.67012023925781,
			"y": 68.04686737060547,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 48.888885498046875,
			"height": 167.7777557373047,
			"seed": 2852484,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689902047485,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "zPE95SRD",
				"focus": -0.7887145750363612,
				"gap": 11.5
			},
			"endBinding": {
				"elementId": "PlAfgAEv",
				"focus": 0.9381207461919213,
				"gap": 4.83922266960144
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
					48.888885498046875,
					-167.7777557373047
				]
			]
		},
		{
			"type": "freedraw",
			"version": 4,
			"versionNonce": 669904444,
			"isDeleted": false,
			"id": "X2xaxzbZi4X2YnQ4-5XWz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 104.67012023925781,
			"y": 69.15801239013672,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 997923716,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689519446293,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.0001,
					0.0001
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 4,
			"versionNonce": 148644740,
			"isDeleted": false,
			"id": "rexgJeFa3NMnYF5_R8v4w",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 154.6701202392578,
			"y": -101.95313262939453,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 1876432700,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689519446293,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.0001,
					0.0001
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "image",
			"version": 36,
			"versionNonce": 487376572,
			"isDeleted": false,
			"id": "SOhjVDNR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -118.4099870938324,
			"y": 71.29285667339494,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.493588689617926,
			"height": 11.285761872936694,
			"seed": 30463,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "LetlY4t4XhBUwz7Kq5Gcb",
					"type": "arrow"
				},
				{
					"id": "WN2SZLqluDzzAgN5iAvIb",
					"type": "arrow"
				}
			],
			"updated": 1689519446293,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "2797a63948653facdebe06c5d1d424f62ec1465b",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 40,
			"versionNonce": 471143172,
			"isDeleted": false,
			"id": "ZE4WgTe7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -84.49472135174739,
			"y": -124.37627269415712,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44.646761734008585,
			"height": 13.394028520202577,
			"seed": 9503,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "ZpQWs7X3yUyuxPM56abTS",
					"type": "arrow"
				},
				{
					"id": "WN2SZLqluDzzAgN5iAvIb",
					"type": "arrow"
				}
			],
			"updated": 1689519446293,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "462832ba76f305369bc72b6f28f1951b51659158",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 71,
			"versionNonce": 700223292,
			"isDeleted": false,
			"id": "zPE95SRD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 96.45604774605671,
			"y": 79.68996376712661,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.650679166089695,
			"height": 16.713807206957707,
			"seed": 69651,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "LetlY4t4XhBUwz7Kq5Gcb",
					"type": "arrow"
				},
				{
					"id": "aMniQSkshoAM46CnbAT_c",
					"type": "arrow"
				}
			],
			"updated": 1689519446293,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "a8947431433e0f539b7bc1f093817a893ba562f0",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 236,
			"versionNonce": 1145209044,
			"isDeleted": false,
			"id": "YgMnqUmiAJWXPKrmsWYBN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -73.66313171386719,
			"y": -14.759136663334107,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 197.22210693359375,
			"height": 0.4608033398234763,
			"seed": 1357882940,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689902047485,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hWs9XSNr",
				"focus": 0.8333357492895029,
				"gap": 10.83343505859375
			},
			"endBinding": {
				"elementId": "Z9LPDJpL",
				"focus": 0.13071935317095587,
				"gap": 14.5556640625
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
					197.22210693359375,
					-0.4608033398234763
				]
			]
		},
		{
			"type": "image",
			"version": 78,
			"versionNonce": 892150076,
			"isDeleted": false,
			"id": "Z9LPDJpL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 137.88195620147863,
			"y": -22.55349012514094,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.46536616149585,
			"height": 16.75631801883657,
			"seed": 23295,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "YgMnqUmiAJWXPKrmsWYBN",
					"type": "arrow"
				}
			],
			"updated": 1689519448691,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "618ceabe15b773d860864554952296282b59ccb8",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 69,
			"versionNonce": 2145853956,
			"isDeleted": false,
			"id": "hWs9XSNr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -100.01440402983367,
			"y": -21.805904518121597,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.035674514745462,
			"height": 7.483314773547883,
			"seed": 42376,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "YgMnqUmiAJWXPKrmsWYBN",
					"type": "arrow"
				}
			],
			"updated": 1689519446293,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "1b09f2c897b4623e976b3f2561fe2c2a3af811b4",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 141,
			"versionNonce": 30263484,
			"isDeleted": false,
			"id": "AoJoYBb0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -30.707630595678978,
			"y": -180.814680515134,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 157.42224971674858,
			"height": 17.72303473632269,
			"seed": 10325,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689519486078,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "61f49bc9e6d420226dd046c9403e670cc4a123e2",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 62,
			"versionNonce": 779415940,
			"isDeleted": false,
			"id": "LNep8dgx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 6.14999879648466,
			"y": -152.6770474279607,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 84.05126640696965,
			"height": 13.658330791132569,
			"seed": 90251,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689519489410,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "6072ba07af638ec22dfa7024ab6b52e1ee7733c7",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 35,
			"versionNonce": 1263659196,
			"isDeleted": false,
			"id": "PlAfgAEv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 152.77440380025553,
			"y": -121.43396319834332,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 181.91378452442794,
			"height": 16.727704324085327,
			"seed": 56584,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "ZpQWs7X3yUyuxPM56abTS",
					"type": "arrow"
				},
				{
					"id": "aMniQSkshoAM46CnbAT_c",
					"type": "arrow"
				}
			],
			"updated": 1689519560905,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "43de7ba3298c6049b0a4eaff52d0e1b3d4b56f93",
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
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "dashed",
		"currentItemRoughness": 0,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 223.49451279640198,
		"scrollY": 247.72576141357422,
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