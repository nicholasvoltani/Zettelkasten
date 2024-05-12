---
date: 2023-07-09
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---
![[Free Group Actions induce a bijection between the group and a point's orbit.svg]]

up:: [[Free Group Action]]

Let there be a [[Free Group Action]] of a [[Group (Mathematics)|Group]] $G$ over some set $X$.

Let $x \in X$, and $Orb_x$ its [[Orbit of Group Action|Orbit]].

Construct a map
$$
\begin{align*}
\varphi: G& \to Orb_x\\
&g \mapsto g \cdot x
\end{align*}
$$

Note that [[Group actions induce a surjection between the group and a point's orbit]], since all points $g \cdot x \in Orb_x$ have at least some $g \in G$ from which they get from $x$ to $g \cdot x$. 

If the action is free, then $\varphi$ must be injective. Let $g \cdot x = h \cdot x \in Orb_x$. Then $x = (g^{-1} h) \cdot x$, for which $g^{-1} h = e_G \iff g = h$ (due to the action being free).

Thus, free group actions induce a bijection between $G$ and a point's orbit $Orb_x$.

%%
# Text Elements
# Embedded files
4bf8f587eb773c6fbe8e1af79a0a5a3feafb662f: $$G$$
40f1965867b13b7e809549353f1c2039277121c9: $$Orb_x$$
3ff3b0496eb135a211703621ab1054d5a7198d9d: $$g_1$$
2f09885f84ea364af20aa9b758b83d27b3ef8829: $$g_2$$
03fa907bca709f71c69862df08cf13e5b67e490a: $$g_3$$
cbe3dcbbc91cdd8e29ee220a96f02d1324e3e0c4: $$g_4$$
acf011c59cca095271be5d3a787b36d961c78d3a: $$g_1 \cdot x$$
e7acb260c6d054612a7fafab4cb56cfb1ab6d5f4: $$g_3 \cdot x$$
274a0245c053ee9b3948c083ad0a1214051f9128: $$g_2 \cdot x$$
be9ab3d93c0fa0d150055189db38757645250261: $$g_4 \cdot x$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "arrow",
			"version": 68,
			"versionNonce": 1492702307,
			"isDeleted": false,
			"id": "g8sazmOhfefemRBrt8uXj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -151.9773649673676,
			"y": -117.8142318725586,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 305.5555114746094,
			"height": 0.5555572509765625,
			"seed": 2017164525,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "CIblswLqwlLRfJMONnw9I",
				"focus": -3.0468243738612117,
				"gap": 12.33331298828125
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
					305.5555114746094,
					-0.5555572509765625
				]
			]
		},
		{
			"type": "image",
			"version": 82,
			"versionNonce": 1455613822,
			"isDeleted": false,
			"id": "CIblswLqwlLRfJMONnw9I",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 141.9115205306793,
			"y": -142.7031021118164,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 12,
			"seed": 1722713506,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "g8sazmOhfefemRBrt8uXj",
					"type": "arrow"
				}
			],
			"updated": 1688941783263,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "4bf8f587eb773c6fbe8e1af79a0a5a3feafb662f",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 158,
			"versionNonce": 541478915,
			"isDeleted": false,
			"id": "QTQIw6lLoq2b5cCcRbDsJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -151.42188401033636,
			"y": 24.407997131347656,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 312.7777404785156,
			"height": 1.66668701171875,
			"seed": 1861703501,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "o84TjO46IsNkcV9oUG30z",
				"focus": -1.9592633345821415,
				"gap": 8.166687011718722
			},
			"endBinding": {
				"elementId": "_a0hfN_VYcsDAe2K_7i7a",
				"focus": -2.6650307203427492,
				"gap": 11.888931274414062
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
					312.7777404785156,
					1.66668701171875
				]
			]
		},
		{
			"type": "arrow",
			"version": 51,
			"versionNonce": 61036451,
			"isDeleted": false,
			"id": "AhVH18KhTKJB2lGYXKo4o",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -125.31070847322698,
			"y": -118.36978912353516,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 141.11114501953125,
			"seed": 705226157,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "86iQ5FyBZgCHy3RsltK7B",
				"focus": 0,
				"gap": 7.8333282470703125
			},
			"endBinding": {
				"elementId": "o84TjO46IsNkcV9oUG30z",
				"focus": -0.030027647276182432,
				"gap": 7.27783203125
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
					0,
					141.11114501953125
				]
			]
		},
		{
			"type": "arrow",
			"version": 391,
			"versionNonce": 1899916099,
			"isDeleted": false,
			"id": "Y3d5sKCvqKbxfCrQsXbsC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -49.3437588950583,
			"y": -120.944040604576,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.743661571793929,
			"height": 142.86780798091786,
			"seed": 2090444813,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "R_zJHZyxdA5DaKzc-Iq_M",
				"gap": 4.7035500326310276,
				"focus": 0.29630126953125
			},
			"endBinding": {
				"elementId": "GerARHwy",
				"focus": -0.11051269754498029,
				"gap": 9.512016009888612
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
					-1.743661571793929,
					142.86780798091786
				]
			]
		},
		{
			"type": "arrow",
			"version": 426,
			"versionNonce": 225839843,
			"isDeleted": false,
			"id": "RcEvtk-ONaiQ8kgjpT_uy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 21.944414544200438,
			"y": -120.59198760986328,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.47513468119968394,
			"height": 144.44448852539062,
			"seed": 413343341,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "262PzpAuqOxNZfwMZi41e",
				"focus": 0.000004069010416666667,
				"gap": 4.5000457763671875
			},
			"endBinding": {
				"elementId": "JoK8W1p8F2ECCZUtWs_s5",
				"focus": 0,
				"gap": 8.944396972656243
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
					0.47513468119968394,
					144.44448852539062
				]
			]
		},
		{
			"type": "arrow",
			"version": 576,
			"versionNonce": 1826141827,
			"isDeleted": false,
			"id": "MDon5vlR-BhnP4vEQn83w",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 94.2938291274043,
			"y": -115.59197235107422,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.7782940910073677,
			"height": 135.5555877685547,
			"seed": 888064205,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "NKO17TAGR2Dd_kZmU4LnY",
				"focus": 0.06182453054070755,
				"gap": 6.722259521484375
			},
			"endBinding": {
				"elementId": "z3ArBNRf",
				"focus": -0.18342191795120918,
				"gap": 9.805450439453125
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
					0.7782940910073677,
					135.5555877685547
				]
			]
		},
		{
			"type": "image",
			"version": 42,
			"versionNonce": 1194894206,
			"isDeleted": false,
			"id": "_a0hfN_VYcsDAe2K_7i7a",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 146.88550018876893,
			"y": 0.08355768190985113,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 34.49637662132068,
			"height": 14.204390373484985,
			"seed": 372084706,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "QTQIw6lLoq2b5cCcRbDsJ",
					"type": "arrow"
				}
			],
			"updated": 1688941781587,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "40f1965867b13b7e809549353f1c2039277121c9",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 57,
			"versionNonce": 1009500030,
			"isDeleted": false,
			"id": "86iQ5FyBZgCHy3RsltK7B",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -133.1767748345031,
			"y": -136.94716161145624,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.732132722552274,
			"height": 10.488088481701515,
			"seed": 1400193954,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "AhVH18KhTKJB2lGYXKo4o",
					"type": "arrow"
				}
			],
			"updated": 1688941705775,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "3ff3b0496eb135a211703621ab1054d5a7198d9d",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 69,
			"versionNonce": 969088958,
			"isDeleted": false,
			"id": "R_zJHZyxdA5DaKzc-Iq_M",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -54.843431328643746,
			"y": -136.3916348780578,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.732132722552274,
			"height": 10.488088481701515,
			"seed": 1024491362,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "Y3d5sKCvqKbxfCrQsXbsC",
					"type": "arrow"
				}
			],
			"updated": 1688941705775,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "2f09885f84ea364af20aa9b758b83d27b3ef8829",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 117,
			"versionNonce": 237301283,
			"isDeleted": false,
			"id": "262PzpAuqOxNZfwMZi41e",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 14.045484686981258,
			"y": -135.83607762708124,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.732132722552274,
			"height": 10.488088481701515,
			"seed": 1930831661,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "RcEvtk-ONaiQ8kgjpT_uy",
					"type": "arrow"
				}
			],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "03fa907bca709f71c69862df08cf13e5b67e490a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 255,
			"versionNonce": 340341187,
			"isDeleted": false,
			"id": "NKO17TAGR2Dd_kZmU4LnY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 86.82322516549688,
			"y": -133.05827611340936,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.732132722552274,
			"height": 10.488088481701515,
			"seed": 92453261,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "MDon5vlR-BhnP4vEQn83w",
					"type": "arrow"
				}
			],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "cbe3dcbbc91cdd8e29ee220a96f02d1324e3e0c4",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 58,
			"versionNonce": 1080295779,
			"isDeleted": false,
			"id": "o84TjO46IsNkcV9oUG30z",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -143.8941624879015,
			"y": 30.202808624667234,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.277930978567795,
			"height": 10.63275860515772,
			"seed": 359530477,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "QTQIw6lLoq2b5cCcRbDsJ",
					"type": "arrow"
				},
				{
					"id": "AhVH18KhTKJB2lGYXKo4o",
					"type": "arrow"
				}
			],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "acf011c59cca095271be5d3a787b36d961c78d3a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 120,
			"versionNonce": 734256387,
			"isDeleted": false,
			"id": "JoK8W1p8F2ECCZUtWs_s5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3.3280970335828712,
			"y": 32.980518585604734,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.277930978567795,
			"height": 10.63275860515772,
			"seed": 1759607373,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "RcEvtk-ONaiQ8kgjpT_uy",
					"type": "arrow"
				}
			],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e7acb260c6d054612a7fafab4cb56cfb1ab6d5f4",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 38,
			"versionNonce": 1105675427,
			"isDeleted": false,
			"id": "GerARHwy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -68.35770023049483,
			"y": 31.61940408365161,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.277930978567795,
			"height": 10.63275860515772,
			"seed": 1219930285,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "Y3d5sKCvqKbxfCrQsXbsC",
					"type": "arrow"
				}
			],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "274a0245c053ee9b3948c083ad0a1214051f9128",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 55,
			"versionNonce": 2054993987,
			"isDeleted": false,
			"id": "z3ArBNRf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 79.42013180075517,
			"y": 29.952686554354734,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.277930978567795,
			"height": 10.63275860515772,
			"seed": 647432973,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "MDon5vlR-BhnP4vEQn83w",
					"type": "arrow"
				}
			],
			"updated": 1714501709117,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "be9ab3d93c0fa0d150055189db38757645250261",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "TCXQKYCv",
			"type": "text",
			"x": -4.19960923006289,
			"y": -130.59201049804688,
			"width": 10,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 504648237,
			"version": 2,
			"versionNonce": 1895039491,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1714501671035,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "g8sazmOhfefemRBrt8uXj",
			"originalText": "",
			"lineHeight": 1.25
		},
		{
			"id": "8pTB8NMF",
			"type": "text",
			"x": -4.19960923006289,
			"y": -130.59201049804688,
			"width": 10,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1162209261,
			"version": 2,
			"versionNonce": 73289795,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1714501667777,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "g8sazmOhfefemRBrt8uXj",
			"originalText": "",
			"lineHeight": 1.25
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
		"scrollX": 394.99718443982584,
		"scrollY": 255.0675259859176,
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