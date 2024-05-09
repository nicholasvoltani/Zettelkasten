---
Date: 2023-07-29
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---
![[Monomorphism.svg]]

up:: [[Category]]

A monomorphism is a categorical generalization of an [[Injective Function]], since [[An injective function is a monomorphism in the category Set]].

Given a category $C$ and a morphism $f \in Hom(X, Y)$, we say that $f$ is a monomorphism if
$$
\forall g_1, g_2 \in Hom(Z, X): (f \circ g_1 = f \circ g_2) \implies g_1 = g_2
$$
That is, if they are "equal" after "pre-composition" with $f$, then they were equal all along.

# Related
- Monomorphisms in $C$ are [[Epimorphism]]s in the [[Opposite Category]] $C^{op}$.

---
### References
- [monomorphism in nLab](https://ncatlab.org/nlab/show/monomorphism)

%%
# Text Elements
# Embedded files
a4a1a09ad53132f2798913839e3951db27e9a622: $$Y$$
d2421d67552c8a800644d3060d81459d270cd9df: $$Z$$
25721c528c9effbc5c6ef52de1454bd59f05f9cb: $$X$$
3d1643056a84d5401ade47c02b0bab7795b08743: $$f$$
ef10bd31456270193346a57acf241a509ce1e6c8: $$g_1$$
1af02097aac69b05953bdf8ba93a4156ef66cd00: $$g_2$$
906c735b6839df68332488b0eff345ea13394323: $$f \circ g_1$$
76b354dabbcd32d472a79f8de70d8af24c22d09a: $$f \circ g_2$$
03a5cb04dc8e3634cdc54dc7f21f750dc23cf57e: $$(f \circ g_1 = f \circ g_2) \implies g_1 = g_2$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "image",
			"version": 64,
			"versionNonce": 180668350,
			"isDeleted": false,
			"id": "5YG_AISqHRQXdZQVzYn1S",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -175.02122116088867,
			"y": -45.283546447753906,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 47.90757057883523,
			"height": 27.7359619140625,
			"seed": 1043622206,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "4Bilzyx-Q5MRUtSQ57WSG",
					"type": "arrow"
				},
				{
					"id": "tSu9z1UaMEhn2lIxr491q",
					"type": "arrow"
				},
				{
					"id": "LExp0Bs_9jMFlCWuz6rtd",
					"type": "arrow"
				},
				{
					"id": "_mmU53r3C-jA4ATE3m5da",
					"type": "arrow"
				}
			],
			"updated": 1690650289434,
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
			"version": 174,
			"versionNonce": 888636222,
			"isDeleted": false,
			"id": "p4uOKMlp42FxVUa8753ah",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -21.269145193786628,
			"y": -44.57251748741212,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 50.365945937857056,
			"height": 26.382162157925126,
			"seed": 868425378,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "tSu9z1UaMEhn2lIxr491q",
					"type": "arrow"
				}
			],
			"updated": 1690650236624,
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
			"version": 244,
			"versionNonce": 412164094,
			"isDeleted": false,
			"id": "XyrK5myQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 110.68975236379737,
			"y": -45.91258498918124,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 49.15213031487658,
			"height": 27.03367167318212,
			"seed": 85812,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "LExp0Bs_9jMFlCWuz6rtd",
					"type": "arrow"
				},
				{
					"id": "_mmU53r3C-jA4ATE3m5da",
					"type": "arrow"
				}
			],
			"updated": 1690650289434,
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
			"version": 77,
			"versionNonce": 216454462,
			"isDeleted": false,
			"id": "dtqWUPPuOwDuFbuX0NjDu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 16.038654327392578,
			"y": -31.669166564941406,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 103.45867919921875,
			"height": 1.014312744140625,
			"seed": 1539781090,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1690650229659,
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
			"version": 43,
			"versionNonce": 909566562,
			"isDeleted": false,
			"id": "uKjGoE6X",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 52.66786575317383,
			"y": -53.36939239501953,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16,
			"height": 15,
			"seed": 32681,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690650226673,
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
			"version": 193,
			"versionNonce": 309185546,
			"isDeleted": false,
			"id": "4Bilzyx-Q5MRUtSQ57WSG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -122.4134635925293,
			"y": -23.55475616455078,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 103.45867919921875,
			"height": 1.014312744140625,
			"seed": 1780000190,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1690675176291,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "5YG_AISqHRQXdZQVzYn1S",
				"focus": 0.5773122814800132,
				"gap": 4.700186989524141
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
					103.45867919921875,
					-1.014312744140625
				]
			]
		},
		{
			"type": "arrow",
			"version": 277,
			"versionNonce": 128694986,
			"isDeleted": false,
			"id": "tSu9z1UaMEhn2lIxr491q",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -123.93488693237305,
			"y": -46.37653350830078,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 103.45867919921875,
			"height": 1.014312744140625,
			"seed": 1700201086,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1690675176291,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "5YG_AISqHRQXdZQVzYn1S",
				"focus": -1.0419869598575824,
				"gap": 3.1787636496803913
			},
			"endBinding": {
				"elementId": "p4uOKMlp42FxVUa8753ah",
				"focus": 1.2365228080585038,
				"gap": 3.1216125488281232
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
					103.45867919921875,
					-1.014312744140625
				]
			]
		},
		{
			"type": "image",
			"version": 77,
			"versionNonce": 1615701154,
			"isDeleted": false,
			"id": "WSt9OBkk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -88.69322624286794,
			"y": -63.28503697766716,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.732132722552274,
			"height": 10.488088481701515,
			"seed": 34374,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690650262530,
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
			"version": 45,
			"versionNonce": 1636391294,
			"isDeleted": false,
			"id": "1JNxkgG2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -88.18605461200856,
			"y": -16.627200063604665,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.732132722552274,
			"height": 10.488088481701515,
			"seed": 37228,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690650258673,
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
			"type": "arrow",
			"version": 358,
			"versionNonce": 1690161546,
			"isDeleted": false,
			"id": "LExp0Bs_9jMFlCWuz6rtd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -145.74235153198242,
			"y": -51.448020935058594,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 278.42559814453125,
			"height": 40.06489562988281,
			"seed": 1808664254,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1690675176291,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "5YG_AISqHRQXdZQVzYn1S",
				"focus": -0.8863019388349864,
				"gap": 6.1644744873046875
			},
			"endBinding": {
				"elementId": "XyrK5myQ",
				"focus": 1.01176823472412,
				"gap": 7.564061434158599
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
					137.437744140625,
					-40.06489562988281
				],
				[
					278.42559814453125,
					-2.02862548828125
				]
			]
		},
		{
			"type": "arrow",
			"version": 426,
			"versionNonce": 1826558026,
			"isDeleted": false,
			"id": "_mmU53r3C-jA4ATE3m5da",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -148.78525924682617,
			"y": -5.297370910644581,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 278.42559814453125,
			"height": 25.861853596402753,
			"seed": 842317922,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1690675176291,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "5YG_AISqHRQXdZQVzYn1S",
				"focus": 1.4033442586544018,
				"gap": 12.250213623046825
			},
			"endBinding": {
				"elementId": "XyrK5myQ",
				"focus": -1.5297398943005835,
				"gap": 14.819252243538532
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
					139.46640014648438,
					25.861853596402753
				],
				[
					278.42559814453125,
					1.2377098381839886
				]
			]
		},
		{
			"type": "image",
			"version": 63,
			"versionNonce": 2005129442,
			"isDeleted": false,
			"id": "gdjst71q",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -28.05302504948892,
			"y": -111.28007741865484,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 39.496835316262995,
			"height": 15.191090506255,
			"seed": 70842,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690650302420,
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
			"version": 32,
			"versionNonce": 1352424254,
			"isDeleted": false,
			"id": "MtKdr7vr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -29.57444838933267,
			"y": 28.186337986618593,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 39.496835316262995,
			"height": 15.191090506255,
			"seed": 21165,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690650318969,
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
			"version": 65,
			"versionNonce": 1702325054,
			"isDeleted": false,
			"id": "0HwH0u5y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -110.61534775798273,
			"y": -142.4865211767399,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 197.48417658131498,
			"height": 15.191090506255,
			"seed": 15229,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690650396515,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "03a5cb04dc8e3634cdc54dc7f21f750dc23cf57e",
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
		"scrollX": 223.74494267860734,
		"scrollY": 255.19559478759766,
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