---
Date: 2023-07-16
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---
![[An affine space with a fixed point is isomorphic to its underlying vector space.svg]]

up:: [[Affine Space]]

Given an affine space $(A, V, +)$, [[Fixing a point in an affine space induces a vector space]]. Fix a point $O \in A$, and call its induced [[Vector Space]] $A_O$.

Then one can easily construct a [[Vector Space Isomorphism]] $T: A_O \leftrightarrow V$, since all points have a unique vector associated to their translation from $O$ (since there is a [[Regular Group Action]]), and since all vectors have an associated point in $A$ which comes from $O$, since the Group Action's domain is defined over the entirety of the additive group $(V, +)$ and is, per hypothesis, [[Free Group Action|Free]] and [[Transitive Group Action|Transitive]] ─ which ensures that there are no "lazy" vectors: all vectors "induce movement" upon the set $A$.

---
### References
- [Affine transformation - Wikipedia](https://en.wikipedia.org/wiki/Affine_transformation)

%%
# Text Elements
# Embedded files
958a5cc24671ee27c6ec933e97f55a59756b5fa8: $$0$$
9e93466d9d4e0c53d84c7e6e90dbe3f5b46626e9: $$T: A_O \leftrightarrow V$$
394c938b63136fc5ddb4db6e8951391ae062b2ed: $$O$$
fd21748f27fb927bf86dc4e8f27586470863691a: $$O + v$$
c6881c8d0826fe31162b0f57f082665da95c384d: $$v$$
39b8ee90328fdee4d6030c74d67b0fc587b8df4e: $$v$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "freedraw",
			"version": 47,
			"versionNonce": 1674351164,
			"isDeleted": false,
			"id": "E5txJ1rDu5hknK7QKsv4m",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -133.6631622314453,
			"y": 74.1579818725586,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 1995899708,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689529560808,
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
			"version": 47,
			"versionNonce": 2057944964,
			"isDeleted": false,
			"id": "-ZRXXkJfgR3xF7ndgSVz3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -74.77427673339844,
			"y": -92.50867462158203,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 875248572,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689529560808,
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
			"version": 139,
			"versionNonce": 762768060,
			"isDeleted": false,
			"id": "hz470VhVmBXacu-Oe1MXf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -134.21873474121094,
			"y": 73.60240936279297,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.888946533203125,
			"height": 165.5555419921875,
			"seed": 524575804,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689529560808,
			"link": null,
			"locked": false,
			"startBinding": {
				"focus": 1.008172423895581,
				"gap": 5,
				"elementId": "ZXbUjzNvcVnWpu-EbQzwt"
			},
			"endBinding": {
				"focus": -0.2441886127830286,
				"gap": 10.722198486328125,
				"elementId": "687K6WOD0wzPdD6NDXolN"
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
					58.888946533203125,
					-165.5555419921875
				]
			]
		},
		{
			"type": "image",
			"version": 66,
			"versionNonce": 969879300,
			"isDeleted": false,
			"id": "ZXbUjzNvcVnWpu-EbQzwt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -159.21873474121094,
			"y": 75.38021087646484,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 12,
			"seed": 237272252,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "Wg0imf7jwR70ni28Do9uj",
					"type": "arrow"
				}
			],
			"updated": 1689529560808,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "394c938b63136fc5ddb4db6e8951391ae062b2ed",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 84,
			"versionNonce": 1900163900,
			"isDeleted": false,
			"id": "687K6WOD0wzPdD6NDXolN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -95.02267242955878,
			"y": -115.75607955340055,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 40.496913462633174,
			"height": 13.161496875355782,
			"seed": 1248691516,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "aZXDPXdjIWYzldyo0GULg",
					"type": "arrow"
				}
			],
			"updated": 1689529560808,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "fd21748f27fb927bf86dc4e8f27586470863691a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 105,
			"versionNonce": 1637527172,
			"isDeleted": false,
			"id": "dsywDbusE8yQAEas8aLW7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -133.34768650053678,
			"y": -17.916988502496597,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.035674514745462,
			"height": 7.483314773547883,
			"seed": 427916732,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689529560808,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "39b8ee90328fdee4d6030c74d67b0fc587b8df4e",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 299,
			"versionNonce": 496004028,
			"isDeleted": false,
			"id": "o5EAFIyn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -20.80312668206404,
			"y": -114.50989391829957,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 89.01243893812979,
			"height": 14.660872295691966,
			"seed": 9743,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689529560808,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "9e93466d9d4e0c53d84c7e6e90dbe3f5b46626e9",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 867,
			"versionNonce": 315244036,
			"isDeleted": false,
			"id": "WJdEO2Or0QtGi8I6IwlyH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 92.361657198505,
			"y": 64.75439971880616,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 49.30901075904778,
			"height": 154.13551199410625,
			"seed": 1763119548,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689529560808,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "o1sV11ui",
				"focus": 0.05677300609613954,
				"gap": 3.3213372807055066
			},
			"endBinding": {
				"elementId": "9DbE0Ljl",
				"focus": -0.2632035683322324,
				"gap": 4.5596737331815405
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
					49.30901075904778,
					-154.13551199410625
				]
			]
		},
		{
			"type": "image",
			"version": 268,
			"versionNonce": 75732028,
			"isDeleted": false,
			"id": "o1sV11ui",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 79.6576575060916,
			"y": 67.44248741880087,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.090680674665816,
			"height": 13.2664991614216,
			"seed": 88160,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "WJdEO2Or0QtGi8I6IwlyH",
					"type": "arrow"
				},
				{
					"id": "Wg0imf7jwR70ni28Do9uj",
					"type": "arrow"
				}
			],
			"updated": 1689529560808,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "958a5cc24671ee27c6ec933e97f55a59756b5fa8",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 240,
			"versionNonce": 643554692,
			"isDeleted": false,
			"id": "9DbE0Ljl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 134.0802999270531,
			"y": -101.68244339525556,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.035674514745462,
			"height": 7.483314773547883,
			"seed": 21253,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "WJdEO2Or0QtGi8I6IwlyH",
					"type": "arrow"
				},
				{
					"id": "aZXDPXdjIWYzldyo0GULg",
					"type": "arrow"
				}
			],
			"updated": 1689529560808,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "c6881c8d0826fe31162b0f57f082665da95c384d",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 246,
			"versionNonce": 1677569212,
			"isDeleted": false,
			"id": "Wg0imf7jwR70ni28Do9uj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -133.98917869285296,
			"y": 74.27338211624709,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 211.93411367910866,
			"height": 0.4114899811921191,
			"seed": 1398426628,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689529560808,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ZXbUjzNvcVnWpu-EbQzwt",
				"focus": -1.1855632582367353,
				"gap": 5.229556048357978
			},
			"endBinding": {
				"elementId": "o1sV11ui",
				"focus": -0.10466511925403994,
				"gap": 1
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
					211.93411367910866,
					0.4114899811921191
				]
			]
		},
		{
			"type": "arrow",
			"version": 614,
			"versionNonce": 630033668,
			"isDeleted": false,
			"id": "aZXDPXdjIWYzldyo0GULg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -69.57109342712289,
			"y": -91.54859727613157,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 201.42557883293898,
			"height": 3.9672284664131183,
			"seed": 1235369732,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689529560808,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "687K6WOD0wzPdD6NDXolN",
				"focus": 2.568050700689143,
				"gap": 11.126733839591083
			},
			"endBinding": {
				"elementId": "9DbE0Ljl",
				"focus": -0.5360064860637404,
				"gap": 2.743651778609717
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
					201.42557883293898,
					-3.9672284664131183
				]
			]
		},
		{
			"type": "image",
			"version": 2,
			"versionNonce": 1644236522,
			"isDeleted": true,
			"id": "pljLk5I6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 16.405788429395386,
			"y": -25.99619620980576,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17,
			"height": 7,
			"seed": 4085,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1714504167341,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "65bb070c43a7a92e13a06f7dad2824e3b73bf6c7",
			"scale": [
				1,
				1
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
		"scrollX": 321.8299446028312,
		"scrollY": 219.7105478638585,
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