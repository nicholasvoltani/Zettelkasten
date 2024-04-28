---
Date: 2023-08-05
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---

up:: [[Functor]]

![[Contravariant Functor.excalidraw|400]]

A contravariant functor is a functor which flips morphisms in the target [[Category]]. It's usually denoted as
$$F: C^{op} \to D$$
where $C^{op}$ is the [[Opposite Category]] of $C$. 

Thus, formally, for each $x, y \in C$, we have that
$$f \in Hom_C(x, y) \iff F(f) \in Hom_D(F(y), F(x))$$
i.e. morphisms are flipped upon $F$'s influence.

# Examples
- When talking about [[Vector Space]]s and their relation to their [[Vector Space Dual]]s, it can be proven that [[The functor between vector spaces and their duals is contravariant]].

---
### References
- [What is a Functor? Definitions and Examples, Part 2](https://www.math3ma.com/blog/what-is-a-functor-part-2)

![[{{title}}.svg]]

up:: 

---
### References
- 

# Text Elements
# Embedded files
5b87aaad966255b76f461ae852beed70c7b16d6e: $$X$$
f6d8756f7e810f458b3d4f4d62bd7f8716f03f8d: $$Y$$
d598bf1f72dbb5e6c6845f15286b5bd0c5cd7409: $$C^{Op}$$
121c288d20339ba2d8f565390b6c67439e2f4cbf: $$X$$
97e38c71007b12195f5c0a9d5ca7d828e6cacaba: $$Y$$
c9663a22d05fa30f5770b40464e6f5d5d86e7f16: $$F(C) = \tilde{F}(C^{Op})$$
ea6d9c5744fff5524b01d461bc0cd7656ac8bae5: $$Y$$
871358c3b3dd22bdd5534ca204c2b63ae36cf8bd: $$C$$
30baf7f435909c66ff8f665c1a5ea84a2149a1d5: $$Op$$
c15d8d6ecadcf8b7835efec32ce82c93723875dd: $$f$$
fbc5889d4a17a10e41813411c0b363f96d3882dc: $$f^{Op}$$
34506f171a695c0902dec7fbd63b17ba012b00ed: $$F(f) = \tilde{F}(f^{Op})$$
2754d6f44876e7103852a2582fc01583ea1769b7: $$\tilde{F}$$
049be755a767d643118fd37ba807040776939248: $$F: C^{Op} \to C'$$
3da6174b9dd08fcf0e2feffe36864102df2f8f38: $$$X$$$

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.5",
	"elements": [
		{
			"type": "image",
			"version": 313,
			"versionNonce": 1095341345,
			"isDeleted": false,
			"id": "IAM4yMZP1jV8PY4nFqvjo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -63.34938049316406,
			"y": 8.968143804271051,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 11,
			"seed": 997228175,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "9_VMfgN_JDSbg1FiI6O1L",
					"type": "arrow"
				}
			],
			"updated": 1713895411251,
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
			"version": 326,
			"versionNonce": 2062385377,
			"isDeleted": false,
			"id": "23MC0i0B1Vdyr1IhW06fo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -60.82783508300781,
			"y": 128.14848743220074,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 11,
			"seed": 1226822831,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "9_VMfgN_JDSbg1FiI6O1L",
					"type": "arrow"
				}
			],
			"updated": 1713895411251,
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
			"version": 328,
			"versionNonce": 433683617,
			"isDeleted": false,
			"id": "iZYa1PGaDegxgEUTohsqy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -100.02143859863281,
			"y": -36.754069940846136,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 96.35858154296875,
			"height": 213.00320434570312,
			"seed": 784295631,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "XEeZNF_V6Oh_ck8MCbpOT",
					"type": "arrow"
				},
				{
					"id": "UqZXliVPdMm-GZT6rSWFJ",
					"type": "arrow"
				}
			],
			"updated": 1713895411251,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 948,
			"versionNonce": 841533455,
			"isDeleted": false,
			"id": "9_VMfgN_JDSbg1FiI6O1L",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -51.61851505709694,
			"y": 120.46257434626324,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 0.3791930224091197,
			"height": 94.83709716796875,
			"seed": 2062005487,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713895411251,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "23MC0i0B1Vdyr1IhW06fo",
				"focus": -0.0736338641936304,
				"gap": 7.6859130859375
			},
			"endBinding": {
				"elementId": "IAM4yMZP1jV8PY4nFqvjo",
				"focus": -0.02785897383507148,
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
			"version": 295,
			"versionNonce": 1299817505,
			"isDeleted": false,
			"id": "UEnG4alpdt0AZ-_YY1MtZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -64.82519394795489,
			"y": 187.25430018722722,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.501858843175395,
			"height": 14.250929421587697,
			"seed": 1428242191,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713895411251,
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
			"version": 508,
			"versionNonce": 500332545,
			"isDeleted": false,
			"id": "9WRhwA6I25lPPUKyF1jK-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 138.07102966308594,
			"y": -228.01346935490864,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 11,
			"seed": 1608811823,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "eItpPsQfIvhlNe7ygopSu",
					"type": "arrow"
				}
			],
			"updated": 1713895411251,
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
			"version": 507,
			"versionNonce": 285420481,
			"isDeleted": false,
			"id": "lKnlGTbXiNp2YQdy5cvaP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 139.57823181152344,
			"y": -107.31167186955707,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 11,
			"seed": 1520043855,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "eItpPsQfIvhlNe7ygopSu",
					"type": "arrow"
				}
			],
			"updated": 1713895411251,
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
			"version": 351,
			"versionNonce": 1927933825,
			"isDeleted": false,
			"id": "cJQczPc3lr7PvU91tVDGF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 107.99198913574219,
			"y": -263.59269298772114,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.84484863281253,
			"height": 213.00320434570312,
			"seed": 60441967,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "XEeZNF_V6Oh_ck8MCbpOT",
					"type": "arrow"
				},
				{
					"id": "NepdSghH0ZgILjv77m-N-",
					"type": "arrow"
				}
			],
			"updated": 1713895411251,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 1456,
			"versionNonce": 538136655,
			"isDeleted": false,
			"id": "eItpPsQfIvhlNe7ygopSu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 148.0238059605981,
			"y": -114.99758495549457,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 1.6127859514311922,
			"height": 97.37287902832031,
			"seed": 976076687,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713895411251,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "lKnlGTbXiNp2YQdy5cvaP",
				"focus": -0.17568199832032047,
				"gap": 7.6859130859375
			},
			"endBinding": {
				"elementId": "9WRhwA6I25lPPUKyF1jK-",
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
			"version": 380,
			"versionNonce": 449423105,
			"isDeleted": false,
			"id": "cbtNFMqKFQbaB5ZMH3UIA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 127.34716796025458,
			"y": -39.034463444723826,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 95.1153162157983,
			"height": 17.368883830710992,
			"seed": 1619850671,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713895411251,
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
			"version": 983,
			"versionNonce": 1185466511,
			"isDeleted": false,
			"id": "XEeZNF_V6Oh_ck8MCbpOT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 5.812491412777668,
			"x": 0.5946279593242849,
			"y": -28.840139491609108,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 113.06001175897842,
			"height": 0.6725741538944163,
			"seed": 2111858639,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713895411252,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "iZYa1PGaDegxgEUTohsqy",
				"focus": -0.3338381501648908,
				"gap": 10.252399490768958
			},
			"endBinding": {
				"elementId": "cJQczPc3lr7PvU91tVDGF",
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
			"version": 256,
			"versionNonce": 1330749057,
			"isDeleted": false,
			"id": "hXIcM9tESq7ZIT8Ue3IH3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -255.9431610107422,
			"y": -91.79897655705707,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 11,
			"seed": 2125856783,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "3EC7M7pUYS9TVITqi5mNN",
					"type": "arrow"
				}
			],
			"updated": 1713895411251,
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
			"version": 239,
			"versionNonce": 1422570049,
			"isDeleted": false,
			"id": "lxwl_BDB4iOwK8ZZiz9Uz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -295.1367645263672,
			"y": -256.70153393010395,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 96.35858154296875,
			"height": 213.00320434570312,
			"seed": 1530471983,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "UqZXliVPdMm-GZT6rSWFJ",
					"type": "arrow"
				},
				{
					"id": "NepdSghH0ZgILjv77m-N-",
					"type": "arrow"
				}
			],
			"updated": 1713895411251,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 625,
			"versionNonce": 1997647073,
			"isDeleted": false,
			"id": "3EC7M7pUYS9TVITqi5mNN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -246.06094060282038,
			"y": -195.84345592717426,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.2387315172496756,
			"height": 96.35856628417969,
			"seed": 615680079,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713895447511,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "GtdYqm0s",
				"focus": -0.22440907391341386,
				"gap": 5.205823374547208
			},
			"endBinding": {
				"elementId": "hXIcM9tESq7ZIT8Ue3IH3",
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
			"version": 221,
			"versionNonce": 1540557249,
			"isDeleted": false,
			"id": "9LELqA9LNC8_G2Nyhy0-a",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -258.98606872558594,
			"y": -29.919459955494574,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 12,
			"seed": 1492821615,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713895411251,
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
			"version": 822,
			"versionNonce": 618957071,
			"isDeleted": false,
			"id": "UqZXliVPdMm-GZT6rSWFJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0.33177497036786896,
			"x": -198.55917024034068,
			"y": -34.253737641865314,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 90.01529630292457,
			"height": 2.4778196783368145,
			"seed": 651821199,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713895411252,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "lxwl_BDB4iOwK8ZZiz9Uz",
				"focus": 0.6589373163172468,
				"gap": 3.077013760512415
			},
			"endBinding": {
				"elementId": "iZYa1PGaDegxgEUTohsqy",
				"focus": 0.5181522139551699,
				"gap": 11.380436356237936
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
			"version": 326,
			"versionNonce": 366628225,
			"isDeleted": false,
			"id": "N55QdDUe62t9AL7BPDPiV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0.33177497036786896,
			"x": -166.11492947716926,
			"y": -52.655259753691496,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21,
			"height": 15,
			"seed": 1342772911,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713895411251,
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
			"version": 113,
			"versionNonce": 1528231265,
			"isDeleted": false,
			"id": "YXRg5mSJPGhuBIDPDu0zC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -267.26670837402344,
			"y": -170.5345264838149,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16,
			"height": 15,
			"seed": 1261463759,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713895411251,
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
			"version": 255,
			"versionNonce": 1177788737,
			"isDeleted": false,
			"id": "rNSOgzDhZtn4m46ZVgjML",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -81.57817077636719,
			"y": 60.75468860407574,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26,
			"height": 19,
			"seed": 635991791,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713895411251,
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
			"version": 345,
			"versionNonce": 613404961,
			"isDeleted": false,
			"id": "N2778ibeeX_LBnStmDWkv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 153.31178283691406,
			"y": -175.3377033636977,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 80.7586931501116,
			"height": 15.70307922363281,
			"seed": 649707791,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "NepdSghH0ZgILjv77m-N-",
					"type": "arrow"
				}
			],
			"updated": 1713895411251,
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
			"version": 435,
			"versionNonce": 1805321473,
			"isDeleted": false,
			"id": "-AB5VC3SYNNoilure_uYv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 5.812491412777668,
			"x": 38.843086109554804,
			"y": -46.183937041924,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 16,
			"seed": 790415151,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713895411251,
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
			"version": 423,
			"versionNonce": 1435685199,
			"isDeleted": false,
			"id": "NepdSghH0ZgILjv77m-N-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -194.8586883544922,
			"y": -164.29565534353645,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 295.6729589634832,
			"height": 1.6303530105838249,
			"seed": 1568278863,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1713895411252,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "lxwl_BDB4iOwK8ZZiz9Uz",
				"focus": -0.1293322325055974,
				"gap": 3.91949462890625
			},
			"endBinding": {
				"elementId": "cJQczPc3lr7PvU91tVDGF",
				"focus": 0.08642181513572611,
				"gap": 7.17771852675115
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
			"version": 149,
			"versionNonce": 97286337,
			"isDeleted": false,
			"id": "Rk7NDJ9AbOUHdzaS-LL_1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -86.71246122250957,
			"y": -185.1784600287636,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 78.86908544957645,
			"height": 11.830362817436468,
			"seed": 1865025391,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1713895411251,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "049be755a767d643118fd37ba807040776939248",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 84,
			"versionNonce": 283863233,
			"isDeleted": false,
			"id": "GtdYqm0s",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -313.88391242457317,
			"y": -214.04927930172147,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 111,
			"height": 13,
			"seed": 9210,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "3EC7M7pUYS9TVITqi5mNN",
					"type": "arrow"
				}
			],
			"updated": 1713895447511,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "3da6174b9dd08fcf0e2feffe36864102df2f8f38",
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
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 395.5803449147324,
		"scrollY": 333.30077854075853,
		"zoom": {
			"value": 2.4453988628608463
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