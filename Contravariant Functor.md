---
Date: 2023-08-05
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---

up:: [[Functor]]

![[Contravariant Functor.svg]]

A contravariant functor is a functor which flips morphisms in the target [[Category]]. It's usually denoted as
$$
F: C^{op} \to D
$$
where $C^{op}$ is the [[Opposite Category]] of $C$. 

Thus, formally, for each $x, y \in C$, we have that
$$
f \in Hom_C(x, y) \iff F(f) \in Hom_D(F(y), F(x))
$$
i.e. morphisms are flipped upon $F$'s influence.

# Examples
- When talking about [[Vector Space]]s and their relation to their [[Vector Space Dual]]s, it can be proven that [[The functor between vector spaces and their duals is contravariant]].

---
### References
- [What is a Functor? Definitions and Examples, Part 2](https://www.math3ma.com/blog/what-is-a-functor-part-2)

%%
# Text Elements
# Embedded files
121c288d20339ba2d8f565390b6c67439e2f4cbf: $$X$$
97e38c71007b12195f5c0a9d5ca7d828e6cacaba: $$Y$$
c9663a22d05fa30f5770b40464e6f5d5d86e7f16: $$F(C) = \tilde{F}(C^{Op})$$
b8a0c389a143d74b699be293c6c40ecc1ee88a27: $$X$$
ea6d9c5744fff5524b01d461bc0cd7656ac8bae5: $$Y$$
871358c3b3dd22bdd5534ca204c2b63ae36cf8bd: $$C$$
5b87aaad966255b76f461ae852beed70c7b16d6e: $$X$$
f6d8756f7e810f458b3d4f4d62bd7f8716f03f8d: $$Y$$
30baf7f435909c66ff8f665c1a5ea84a2149a1d5: $$Op$$
c15d8d6ecadcf8b7835efec32ce82c93723875dd: $$f$$
fbc5889d4a17a10e41813411c0b363f96d3882dc: $$f^{Op}$$
34506f171a695c0902dec7fbd63b17ba012b00ed: $$F(f) = \tilde{F}(f^{Op})$$
d598bf1f72dbb5e6c6845f15286b5bd0c5cd7409: $$C^{Op}$$
2754d6f44876e7103852a2582fc01583ea1769b7: $$\tilde{F}$$
049be755a767d643118fd37ba807040776939248: $$F: C^{Op} \to C'$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "image",
			"version": 267,
			"versionNonce": 1633465922,
			"isDeleted": false,
			"id": "D4jHFF3X",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 0.2199979765871145,
			"y": 140.71121536351504,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.494185260204677,
			"height": 11.258858945821498,
			"seed": 1406,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "tR-QiA-UGgf55aVseVTns",
					"type": "arrow"
				}
			],
			"updated": 1692662047201,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "5b87aaad966255b76f461ae852beed70c7b16d6e",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 280,
			"versionNonce": 2023900894,
			"isDeleted": false,
			"id": "Vsh1l9Hp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2.488636016845703,
			"y": 260.02098846435547,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 11,
			"seed": 2741,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "tR-QiA-UGgf55aVseVTns",
					"type": "arrow"
				}
			],
			"updated": 1692662047201,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "f6d8756f7e810f458b3d4f4d62bd7f8716f03f8d",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 282,
			"versionNonce": 246455810,
			"isDeleted": false,
			"id": "wdvenyx-KR_WQ8Oyheipv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -36.7049674987793,
			"y": 95.1184310913086,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 96.35858154296875,
			"height": 213.00320434570312,
			"seed": 1009354434,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "GDtzwK6p-9cWoIBEZcEZc",
					"type": "arrow"
				},
				{
					"id": "qcZ3hiCYjS4BnYBRi1lCo",
					"type": "arrow"
				}
			],
			"updated": 1692662047201,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 812,
			"versionNonce": 1756478238,
			"isDeleted": false,
			"id": "tR-QiA-UGgf55aVseVTns",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 11.697956042756562,
			"y": 252.33507537841797,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 0.3791930224091197,
			"height": 94.83709716796875,
			"seed": 942023518,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692662047201,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Vsh1l9Hp",
				"focus": -0.07363386419363147,
				"gap": 7.6859130859375
			},
			"endBinding": {
				"elementId": "D4jHFF3X",
				"focus": -0.027858973835070515,
				"gap": 5.6573333740234375
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
					-0.3791930224091197,
					-94.83709716796875
				]
			]
		},
		{
			"type": "image",
			"version": 249,
			"versionNonce": 11636162,
			"isDeleted": false,
			"id": "s8dyWcfK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1.2691943700229036,
			"y": 319.00498958008484,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.022801887018463,
			"height": 14.494552700181965,
			"seed": 84937,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692662047201,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "d598bf1f72dbb5e6c6845f15286b5bd0c5cd7409",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 462,
			"versionNonce": 301501342,
			"isDeleted": false,
			"id": "ufZXXR1rbTHpmmnjSBmGX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 201.6404081328371,
			"y": -96.27039779566465,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.494185260204677,
			"height": 11.258858945821498,
			"seed": 1254105310,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "TJk788AnSDt3qHUZGw0bP",
					"type": "arrow"
				}
			],
			"updated": 1692662084189,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "121c288d20339ba2d8f565390b6c67439e2f4cbf",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 461,
			"versionNonce": 811689950,
			"isDeleted": false,
			"id": "B9fRrCtUPBqhhmVQxcMxg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 202.89470291137695,
			"y": 24.560829162597656,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 11,
			"seed": 772035870,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "TJk788AnSDt3qHUZGw0bP",
					"type": "arrow"
				}
			],
			"updated": 1692662084189,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "97e38c71007b12195f5c0a9d5ca7d828e6cacaba",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 305,
			"versionNonce": 316908098,
			"isDeleted": false,
			"id": "q4er0ufYDJ0fztxQzBQlO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 171.3084602355957,
			"y": -131.7201919555664,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.84484863281253,
			"height": 213.00320434570312,
			"seed": 993526110,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "GDtzwK6p-9cWoIBEZcEZc",
					"type": "arrow"
				},
				{
					"id": "MD3ND9FCK9y2J4JFPY2kF",
					"type": "arrow"
				}
			],
			"updated": 1692662079315,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 1320,
			"versionNonce": 544442462,
			"isDeleted": false,
			"id": "TJk788AnSDt3qHUZGw0bP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 211.34027706045163,
			"y": 16.874916076660156,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 1.6127859514311922,
			"height": 97.37287902832031,
			"seed": 1974216094,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692662084382,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "B9fRrCtUPBqhhmVQxcMxg",
				"focus": -0.17568199832032047,
				"gap": 7.6859130859375
			},
			"endBinding": {
				"elementId": "ufZXXR1rbTHpmmnjSBmGX",
				"focus": -0.06613960504838903,
				"gap": 4.64300537109375
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
					1.6127859514311922,
					-97.37287902832031
				]
			]
		},
		{
			"type": "image",
			"version": 334,
			"versionNonce": 1597040606,
			"isDeleted": false,
			"id": "HpZDgXv0-eTwfnNWMkDNh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 190.12903553452864,
			"y": 92.93457563966524,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 96.18452326695723,
			"height": 17.17580772624236,
			"seed": 1318175198,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692662047201,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "c9663a22d05fa30f5770b40464e6f5d5d86e7f16",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 847,
			"versionNonce": 313796930,
			"isDeleted": false,
			"id": "GDtzwK6p-9cWoIBEZcEZc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 5.812491412777668,
			"x": 63.9110990591778,
			"y": 103.03236154054562,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 113.06001175897842,
			"height": 0.6725741538944163,
			"seed": 55843394,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692662053997,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "wdvenyx-KR_WQ8Oyheipv",
				"focus": -0.33383815016489077,
				"gap": 10.252399490768966
			},
			"endBinding": {
				"elementId": "q4er0ufYDJ0fztxQzBQlO",
				"focus": -0.5045326683183963,
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
					113.06001175897842,
					0.6725741538944163
				]
			]
		},
		{
			"type": "image",
			"version": 194,
			"versionNonce": 650394654,
			"isDeleted": false,
			"id": "Y7jit84b1H7lNkmFskQpR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -192.86670246286602,
			"y": -79.74340499781309,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.494185260204677,
			"height": 11.258858945821498,
			"seed": 387028930,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "w0XNEYyMROI6H9L_0pEDI",
					"type": "arrow"
				}
			],
			"updated": 1692662047201,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "b8a0c389a143d74b699be293c6c40ecc1ee88a27",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 210,
			"versionNonce": 1136893122,
			"isDeleted": false,
			"id": "NveQK36GOaA6px7iZDfG5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -192.62668991088867,
			"y": 40.073524475097656,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 11,
			"seed": 1313689474,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "w0XNEYyMROI6H9L_0pEDI",
					"type": "arrow"
				}
			],
			"updated": 1692662047201,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "ea6d9c5744fff5524b01d461bc0cd7656ac8bae5",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 193,
			"versionNonce": 108595550,
			"isDeleted": false,
			"id": "aLsV7-85GMe_gr1Hf5mYB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -231.82029342651367,
			"y": -124.82903289794922,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 96.35858154296875,
			"height": 213.00320434570312,
			"seed": 1555828546,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "qcZ3hiCYjS4BnYBRi1lCo",
					"type": "arrow"
				},
				{
					"id": "MD3ND9FCK9y2J4JFPY2kF",
					"type": "arrow"
				}
			],
			"updated": 1692662062343,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 487,
			"versionNonce": 7779458,
			"isDeleted": false,
			"id": "w0XNEYyMROI6H9L_0pEDI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -182.74446950296687,
			"y": -63.97095489501953,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.2387315172496756,
			"height": 96.35856628417969,
			"seed": 1992087298,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692662047201,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Y7jit84b1H7lNkmFskQpR",
				"focus": 0.044664428111340665,
				"gap": 4.6430206298828125
			},
			"endBinding": {
				"elementId": "NveQK36GOaA6px7iZDfG5",
				"focus": -0.1515307819969317,
				"gap": 7.6859130859375
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
					-1.2387315172496756,
					96.35856628417969
				]
			]
		},
		{
			"type": "image",
			"version": 175,
			"versionNonce": 1860062366,
			"isDeleted": false,
			"id": "s0IQHA6mX6XeT_nZkrTzK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -195.41639197054138,
			"y": 101.79717096414923,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.493588689617926,
			"height": 12.311740225021849,
			"seed": 1825482434,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692662047201,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "871358c3b3dd22bdd5534ca204c2b63ae36cf8bd",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 686,
			"versionNonce": 419889794,
			"isDeleted": false,
			"id": "qcZ3hiCYjS4BnYBRi1lCo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0.33177497036786896,
			"x": -135.2426991404872,
			"y": 97.61876339028943,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 90.01529630292457,
			"height": 2.4778196783368145,
			"seed": 273827778,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692662130608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "aLsV7-85GMe_gr1Hf5mYB",
				"focus": 0.6589373163172467,
				"gap": 3.0770137605123864
			},
			"endBinding": {
				"elementId": "wdvenyx-KR_WQ8Oyheipv",
				"focus": 0.5181522139551695,
				"gap": 11.380436356237972
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
					90.01529630292457,
					2.4778196783368145
				]
			]
		},
		{
			"type": "image",
			"version": 280,
			"versionNonce": 1695232322,
			"isDeleted": false,
			"id": "W95vf42N",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0.33177497036786896,
			"x": -102.54540914327535,
			"y": 79.03202820399355,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20.493901531919196,
			"height": 15.370426148939398,
			"seed": 97942,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692662131452,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "30baf7f435909c66ff8f665c1a5ea84a2149a1d5",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 67,
			"versionNonce": 529595394,
			"isDeleted": false,
			"id": "7rBILjS7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -203.95023727416992,
			"y": -38.662025451660156,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16,
			"height": 15,
			"seed": 34688,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692662047202,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "c15d8d6ecadcf8b7835efec32ce82c93723875dd",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 209,
			"versionNonce": 453917982,
			"isDeleted": false,
			"id": "yBmynN2D",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -18.617930016279786,
			"y": 192.880568631777,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.71246067953223,
			"height": 18.49324200890693,
			"seed": 35004,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692662047202,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "fbc5889d4a17a10e41813411c0b363f96d3882dc",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 299,
			"versionNonce": 2126005022,
			"isDeleted": false,
			"id": "iFyR9a2M",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 216.0159890845257,
			"y": -43.34792902676387,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 81.98322285459538,
			"height": 15.4685326140746,
			"seed": 77256,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "MD3ND9FCK9y2J4JFPY2kF",
					"type": "arrow"
				}
			],
			"updated": 1692662089055,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "34506f171a695c0902dec7fbd63b17ba012b00ed",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 389,
			"versionNonce": 398502274,
			"isDeleted": false,
			"id": "jFBi9Dpp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 5.812491412777668,
			"x": 102.41276286459936,
			"y": 85.4807371735495,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.493588689617926,
			"height": 16.415653633362464,
			"seed": 3621,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692662053755,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "2754d6f44876e7103852a2582fc01583ea1769b7",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 287,
			"versionNonce": 461704990,
			"isDeleted": false,
			"id": "MD3ND9FCK9y2J4JFPY2kF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -131.54221725463867,
			"y": -32.423154311381744,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 295.6729589634832,
			"height": 1.6303530105838249,
			"seed": 240080926,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1692662079688,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "aLsV7-85GMe_gr1Hf5mYB",
				"focus": -0.1293322325055976,
				"gap": 3.91949462890625
			},
			"endBinding": {
				"elementId": "q4er0ufYDJ0fztxQzBQlO",
				"focus": 0.08642181513572621,
				"gap": 7.177718526751164
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
					295.6729589634832,
					-1.6303530105838249
				]
			]
		},
		{
			"type": "image",
			"version": 103,
			"versionNonce": 270260034,
			"isDeleted": false,
			"id": "J0Fi933E",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -22.79996777539707,
			"y": -53.39673434730236,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 77.67704075505847,
			"height": 12.011913518823475,
			"seed": 5417,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1692662120247,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "049be755a767d643118fd37ba807040776939248",
			"scale": [
				1,
				1
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1971c2",
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
		"scrollX": 349.4135704040527,
		"scrollY": 148.28955008201427,
		"zoom": {
			"value": 1.6500000000000001
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