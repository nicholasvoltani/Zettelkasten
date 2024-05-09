---
Date: 2023-07-29
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---
![[Epimorphism.svg]]

up:: [[Category]]

An epimorphism is a generalization of a [[Surjective Function]], since [[A surjective function is an epimorphism in the category Set]].

Given a category $C$ and a morphism $f \in Hom(X, Y)$, we say that $f$ is an epimorphism if
$$
\forall g_1, g_2 \in Hom(Y, Z): (g_1 \circ f = g_2 \circ f) \implies g_1 = g_2
$$
That is, if they are "equal" after composing with $f$, then they were equal all along.

# Related
- Epimorphisms in $C$ are [[Monomorphism]]s in the [[Opposite Category]] $C^{op}$.

---
### References
- [epimorphism in nLab](https://ncatlab.org/nlab/show/epimorphism)

%%
# Text Elements
# Embedded files
d2421d67552c8a800644d3060d81459d270cd9df: $$Z$$
25721c528c9effbc5c6ef52de1454bd59f05f9cb: $$X$$
a4a1a09ad53132f2798913839e3951db27e9a622: $$Y$$
3d1643056a84d5401ade47c02b0bab7795b08743: $$f$$
ef10bd31456270193346a57acf241a509ce1e6c8: $$g_1$$
1af02097aac69b05953bdf8ba93a4156ef66cd00: $$g_2$$
906c735b6839df68332488b0eff345ea13394323: $$g_1 \circ f$$
76b354dabbcd32d472a79f8de70d8af24c22d09a: $$g_2 \circ f$$
03a5cb04dc8e3634cdc54dc7f21f750dc23cf57e: $$(g_1 \circ f = g_2 \circ f) \implies g_1 = g_2$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "image",
			"version": 260,
			"versionNonce": 1932766346,
			"isDeleted": false,
			"id": "BgHbls4pDLiKrZC1hqBzj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 239.29136754433,
			"y": -37.91216278076172,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 47.90757057883523,
			"height": 27.7359619140625,
			"seed": 569068822,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "0I1Y_Aw9yxfmJZY0Fkjbp",
					"type": "arrow"
				},
				{
					"id": "VgyvXgKRpquUMbK-HhLCP",
					"type": "arrow"
				}
			],
			"updated": 1690675131779,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "d2421d67552c8a800644d3060d81459d270cd9df",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 214,
			"versionNonce": 580305802,
			"isDeleted": false,
			"id": "cRoblhtMwkJUnDs9thdS9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -32.455824066692955,
			"y": -30.608177277451183,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 50.365945937857056,
			"height": 26.382162157925126,
			"seed": 812464726,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "VgyvXgKRpquUMbK-HhLCP",
					"type": "arrow"
				},
				{
					"id": "R9pmk4wiWyUVKID-8YPh4",
					"type": "arrow"
				}
			],
			"updated": 1690675134168,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "25721c528c9effbc5c6ef52de1454bd59f05f9cb",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 310,
			"versionNonce": 115951638,
			"isDeleted": false,
			"id": "WaWrkv3za1-DSdG6kSaUL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 99.50307349089104,
			"y": -31.948244779220317,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 49.15213031487658,
			"height": 27.03367167318212,
			"seed": 180322198,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "0I1Y_Aw9yxfmJZY0Fkjbp",
					"type": "arrow"
				},
				{
					"id": "C67-TUPh_bMGP9WiwWuYM",
					"type": "arrow"
				}
			],
			"updated": 1690675082484,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "a4a1a09ad53132f2798913839e3951db27e9a622",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 139,
			"versionNonce": 1316843914,
			"isDeleted": false,
			"id": "Gt1v10mYUPXP6gaIqyHGd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4.851975454486251,
			"y": -17.70482635498047,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 103.45867919921875,
			"height": 1.014312744140625,
			"seed": 85400790,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1690675034397,
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
					103.45867919921875,
					-1.014312744140625
				]
			]
		},
		{
			"type": "image",
			"version": 105,
			"versionNonce": 2004075542,
			"isDeleted": false,
			"id": "08WAH_S98PQnI0TQeo7eB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 41.4811868802675,
			"y": -39.405052185058594,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16,
			"height": 15,
			"seed": 621351446,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690675034397,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "3d1643056a84d5401ade47c02b0bab7795b08743",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 708,
			"versionNonce": 1780651798,
			"isDeleted": false,
			"id": "0I1Y_Aw9yxfmJZY0Fkjbp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 149.38984776893938,
			"y": -9.179107086532708,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 92.30133056640625,
			"height": 0.4113088680571355,
			"seed": 1972002646,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1690675086763,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "WaWrkv3za1-DSdG6kSaUL",
				"focus": 0.6872779487377232,
				"gap": 1
			},
			"endBinding": {
				"elementId": "BgHbls4pDLiKrZC1hqBzj",
				"focus": -1.0274062943392785,
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
					92.30133056640625,
					-0.4113088680571355
				]
			]
		},
		{
			"type": "arrow",
			"version": 631,
			"versionNonce": 1509152086,
			"isDeleted": false,
			"id": "C67-TUPh_bMGP9WiwWuYM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 152.94001866737688,
			"y": -30.38359832763672,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87.22979736328125,
			"height": 0.507171630859375,
			"seed": 1525679254,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1690675082851,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "WaWrkv3za1-DSdG6kSaUL",
				"focus": -0.8627103046537195,
				"gap": 4.284814861609249
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
					87.22979736328125,
					-0.507171630859375
				]
			]
		},
		{
			"type": "image",
			"version": 274,
			"versionNonce": 241075414,
			"isDeleted": false,
			"id": "gR7M1Zv-wes8-OWDStOwB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 182.09568082172575,
			"y": -51.85644811047966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.732132722552274,
			"height": 10.488088481701515,
			"seed": 1726939606,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690675089060,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "ef10bd31456270193346a57acf241a509ce1e6c8",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 232,
			"versionNonce": 159650122,
			"isDeleted": false,
			"id": "_enFdJnOig-ptVleuU3zX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 184.63160001117888,
			"y": 2.4086428319031485,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.732132722552274,
			"height": 10.488088481701515,
			"seed": 748443414,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690675090843,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "1af02097aac69b05953bdf8ba93a4156ef66cd00",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 150,
			"versionNonce": 1247676426,
			"isDeleted": false,
			"id": "n_d9yj1AfO2wWQRUa_wlM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 100.22669622408912,
			"y": -91.73707815107672,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 39.496835316262995,
			"height": 15.191090506255,
			"seed": 254568150,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690675105443,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "906c735b6839df68332488b0eff345ea13394323",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 123,
			"versionNonce": 1697236362,
			"isDeleted": false,
			"id": "QkW3a4Y6IWeZKLUNAeopD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 104.79108831393287,
			"y": 46.20789865556391,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 39.496835316262995,
			"height": 15.191090506255,
			"seed": 300227606,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690675142376,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "76b354dabbcd32d472a79f8de70d8af24c22d09a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 166,
			"versionNonce": 1182405846,
			"isDeleted": false,
			"id": "j3SIyLaw-eYn72pgGjoTw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 22.22873508786094,
			"y": -127.50786822263834,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 197.48417658131498,
			"height": 15.191090506255,
			"seed": 1045768534,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690675161778,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "03a5cb04dc8e3634cdc54dc7f21f750dc23cf57e",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 127,
			"versionNonce": 1745347850,
			"isDeleted": false,
			"id": "VgyvXgKRpquUMbK-HhLCP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -5.859506130218506,
			"y": -37.247840881347656,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 263.2110900878906,
			"height": 34.99334716796875,
			"seed": 865222218,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1690675130465,
			"link": null,
			"locked": false,
			"startBinding": {
				"focus": -0.9791539916471101,
				"gap": 6.942947387695311,
				"elementId": "cRoblhtMwkJUnDs9thdS9"
			},
			"endBinding": {
				"focus": 1.1118150255659354,
				"gap": 7.9572296142578125,
				"elementId": "BgHbls4pDLiKrZC1hqBzj"
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
					129.32339477539062,
					-34.99334716796875
				],
				[
					263.2110900878906,
					-8.621551513671875
				]
			]
		},
		{
			"type": "arrow",
			"version": 233,
			"versionNonce": 432005962,
			"isDeleted": false,
			"id": "R9pmk4wiWyUVKID-8YPh4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4.338021755218506,
			"y": 5.352790832519517,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 263.2110900878906,
			"height": 27.791443278243378,
			"seed": 1530018314,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1690675139462,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "cRoblhtMwkJUnDs9thdS9",
				"focus": 1.1999029942183528,
				"gap": 9.882089735844415
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
					128.81619262695312,
					27.791443278243378
				],
				[
					263.2110900878906,
					5.222824430931418
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
		"scrollX": 190.2033182355883,
		"scrollY": 238.69548797607422,
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