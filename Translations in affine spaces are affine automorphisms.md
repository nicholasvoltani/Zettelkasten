---
date: 2023-07-20
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---
![[Translations in affine spaces are affine automorphisms.svg]]

up:: [[Affine Isomorphism]]

Let $(E, V, +_E)$ be an [[Affine Space]], and let $T_w: E \to E$ be the translation of all points in $E$ by $w \in V$ (i.e. $T_w(P) = P + w$). It defines an [[Affine Map]] with underlying linear map[^1]
$$
\begin{align*}
L: V &\to V\\
v &\mapsto v
\end{align*}
$$
such that one can see the map as
$$
T_w(P+v) = T_w(P) + L(v) = T_w(P) + v
$$
Note that this is the case, since the diagram commutes. Let $P, Q$ be points connected by $v$ ─ i.e. $Q = P + v$. Then we have that
$$
T_w(Q) = Q + w = (P + v) + w = \dots = T_w(P) + v = T_w(P) + L(v)
$$
since the [[Group Action]] is "compatible" ─ $(A+v) + w = A + (v + w)$ ─, alongside the additive group $(V, +)$ being [[Abelian Group|Abelian]].

Thus, this is an [[Affine Isomorphism]], since its inverse is
$$
\begin{align*}
T_w^{-1}: E &\to E\\
P &\mapsto P + (-w)
\end{align*}
$$
with underlying linear map 
$$
\begin{align*}
L^{-1}: V &\to V\\
v &\mapsto v
\end{align*}
$$

---
### References
- 

[^1]: Note that this works since, for any group action, $Q = P + v \iff P = Q + (-v)$

%%
# Text Elements
# Embedded files
2797a63948653facdebe06c5d1d424f62ec1465b: $$P$$
a8947431433e0f539b7bc1f093817a893ba562f0: $$P + w$$
618ceabe15b773d860864554952296282b59ccb8: $$\tilde{v} = v$$
1b09f2c897b4623e976b3f2561fe2c2a3af811b4: $$v$$
9c6079ea42c412a7d572a738c179530d7230a3ae: $$Q$$
3ed1a70505485bf179ae6e043c38a344f558b6ac: $$-v$$
1521d006f51c3672b0731273e1d2eb8c2070014e: $$w$$
2f566cd0a448391975180ce24f3632b44f70baef: $$w$$
124390ccd02c892d51c95a730b45b56acb77a891: $$Q+w = (P + v) + w = (P + w) + v$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "freedraw",
			"version": 42,
			"versionNonce": 1940933460,
			"isDeleted": false,
			"id": "tyt6_ly0b-ncNRX5Mt9en",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -187.01454710960388,
			"y": 76.0610580444336,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 925412692,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689901989031,
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
			"version": 42,
			"versionNonce": 382452716,
			"isDeleted": false,
			"id": "WDP3aNhw6xOEcjQYy60pX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -140.34792113304138,
			"y": -92.2722396850586,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 433054420,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689901989031,
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
			"version": 693,
			"versionNonce": 1910400724,
			"isDeleted": false,
			"id": "lWuJVrkzHi-kJ1TRv6r1Y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -132.4404525343776,
			"y": -92.26745464204075,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 194.8466929158863,
			"height": 0.31628286111120474,
			"seed": 1559521364,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689902007550,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "RTbDJYgp",
				"focus": -1.5071561054085016,
				"gap": 4.981596074790133
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
					194.8466929158863,
					-0.31628286111120474
				]
			]
		},
		{
			"type": "arrow",
			"version": 305,
			"versionNonce": 1996777068,
			"isDeleted": false,
			"id": "WJR5zk9tnkY1bqgIWkWJ3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -179.87892967899768,
			"y": 76.08087763728767,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 188.4599303624798,
			"height": 0.359709551425226,
			"seed": 611073492,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689901989031,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Olod_4dBzHR7its_AqCNA",
				"focus": -1.7135678465762472,
				"gap": 7.135678465762453
			},
			"endBinding": {
				"elementId": "UYS2JfwNYuOe8AAOlL47L",
				"focus": 2.59708995216802,
				"gap": 11.067461822517572
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
					188.4599303624798,
					0.359709551425226
				]
			]
		},
		{
			"type": "arrow",
			"version": 189,
			"versionNonce": 917276244,
			"isDeleted": false,
			"id": "bfrYE9ZrQRLb8dYicUzsg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -187.57015013694763,
			"y": 75.5055160522461,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 46.666656494140625,
			"height": 165.5555419921875,
			"seed": 782731116,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689901989031,
			"link": null,
			"locked": false,
			"startBinding": {
				"focus": 0.7877697158759297,
				"gap": 4.4999847412109375,
				"elementId": "Olod_4dBzHR7its_AqCNA"
			},
			"endBinding": {
				"focus": -0.41122640343117994,
				"gap": 8.385787963867188,
				"elementId": "qcfsCwvt"
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
					9.85508131980896,
					-90.15422058105469
				],
				[
					46.666656494140625,
					-165.5555419921875
				]
			]
		},
		{
			"type": "arrow",
			"version": 724,
			"versionNonce": 949120084,
			"isDeleted": false,
			"id": "bWPyYOV2dEZi-qDTqdv9T",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 18.407820652396506,
			"y": 74.14173227945963,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 48.82757241699731,
			"height": 167.1715114791782,
			"seed": 300800212,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689902007550,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "UYS2JfwNYuOe8AAOlL47L",
				"gap": 13.366316731770832,
				"focus": -0.6918878516990682
			},
			"endBinding": {
				"elementId": "RTbDJYgp",
				"focus": 0.9543024078559024,
				"gap": 4.406004186511893
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
					48.82757241699731,
					-167.1715114791782
				]
			]
		},
		{
			"type": "freedraw",
			"version": 41,
			"versionNonce": 225483732,
			"isDeleted": false,
			"id": "0sb5Wlgw24phl9oc0RBLs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 16.318704843521118,
			"y": 77.72777557373047,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 1239653972,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689901989031,
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
			"version": 41,
			"versionNonce": 878099308,
			"isDeleted": false,
			"id": "MPgRBz2zS1kogtJrt2m0l",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 66.31870484352112,
			"y": -93.38336944580078,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 1510257620,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689901989031,
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
			"version": 76,
			"versionNonce": 1846935892,
			"isDeleted": false,
			"id": "Olod_4dBzHR7its_AqCNA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -206.7614024895691,
			"y": 79.86261985698869,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.493588689617926,
			"height": 11.285761872936694,
			"seed": 1080498516,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "WJR5zk9tnkY1bqgIWkWJ3",
					"type": "arrow"
				},
				{
					"id": "bfrYE9ZrQRLb8dYicUzsg",
					"type": "arrow"
				},
				{
					"id": "O8Vg_fQHTiP9Mnk0zhAS7",
					"type": "arrow"
				}
			],
			"updated": 1689901989031,
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
			"version": 129,
			"versionNonce": 658796012,
			"isDeleted": false,
			"id": "UYS2JfwNYuOe8AAOlL47L",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 5.913746641346787,
			"y": 87.7018612618316,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 48.66894971813822,
			"height": 13.273349923128606,
			"seed": 1653068884,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "WJR5zk9tnkY1bqgIWkWJ3",
					"type": "arrow"
				},
				{
					"id": "bWPyYOV2dEZi-qDTqdv9T",
					"type": "arrow"
				}
			],
			"updated": 1689901989031,
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
			"type": "image",
			"version": 178,
			"versionNonce": 804435668,
			"isDeleted": false,
			"id": "PxSXUUtte3fFECPN3Xtpc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 54.77933899810279,
			"y": -13.939642361474874,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 39.34854117127714,
			"height": 13.82516311423251,
			"seed": 1509281620,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689901989031,
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
			"version": 217,
			"versionNonce": 114806892,
			"isDeleted": false,
			"id": "6SJK9sAKZzddKfQqy7S7Y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -196.2773794841641,
			"y": -33.319301734918476,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.035674514745462,
			"height": 7.483314773547883,
			"seed": 1789445332,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689901989031,
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
			"version": 9,
			"versionNonce": 1335671892,
			"isDeleted": false,
			"id": "qcfsCwvt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -148.76591110229492,
			"y": -113.4358139038086,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 15,
			"seed": 65223,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "bfrYE9ZrQRLb8dYicUzsg",
					"type": "arrow"
				},
				{
					"id": "O8Vg_fQHTiP9Mnk0zhAS7",
					"type": "arrow"
				}
			],
			"updated": 1689901989031,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "9c6079ea42c412a7d572a738c179530d7230a3ae",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 445,
			"versionNonce": 316334828,
			"isDeleted": false,
			"id": "O8Vg_fQHTiP9Mnk0zhAS7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.32086157831103,
			"x": -153.7514988878859,
			"y": 75.69222960707874,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 28.01612759808007,
			"height": 165.57146301685168,
			"seed": 692937556,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689901989031,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "qcfsCwvt",
				"focus": -0.01487684713210237,
				"gap": 9.873512856082172
			},
			"endBinding": {
				"elementId": "Olod_4dBzHR7its_AqCNA",
				"focus": 0.47700987460149064,
				"gap": 8.16138255134129
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
					-13.930300924383413,
					-91.31552941871743
				],
				[
					14.085826673696658,
					-165.57146301685168
				]
			]
		},
		{
			"type": "image",
			"version": 37,
			"versionNonce": 1189745108,
			"isDeleted": false,
			"id": "wNAI7bYt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -136.84126152645766,
			"y": -15.415905623914497,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20.493901531919196,
			"height": 11.271645842555557,
			"seed": 93002,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689901989031,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "3ed1a70505485bf179ae6e043c38a344f558b6ac",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 59,
			"versionNonce": 30909804,
			"isDeleted": false,
			"id": "p9Cq4Wz9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -99.01827384184205,
			"y": 86.28548036957372,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20.311854385344255,
			"height": 7.483314773547883,
			"seed": 74951,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689901989031,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "1521d006f51c3672b0731273e1d2eb8c2070014e",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 96,
			"versionNonce": 1693497172,
			"isDeleted": false,
			"id": "Ssaj0odB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -59.460534584029546,
			"y": -107.2431603774966,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20.311854385344255,
			"height": 7.483314773547883,
			"seed": 54193,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689901989032,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "2f566cd0a448391975180ce24f3632b44f70baef",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 48,
			"versionNonce": 559428332,
			"isDeleted": false,
			"id": "RTbDJYgp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 65.17219829771025,
			"y": -114.29441166284779,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 266.43127631717715,
			"height": 16.717256553234645,
			"seed": 60935,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "lWuJVrkzHi-kJ1TRv6r1Y",
					"type": "arrow"
				},
				{
					"id": "bWPyYOV2dEZi-qDTqdv9T",
					"type": "arrow"
				}
			],
			"updated": 1689902007550,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "124390ccd02c892d51c95a730b45b56acb77a891",
			"scale": [
				1,
				1
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#e03131",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 227.02041709423065,
		"scrollY": 280.66353134252205,
		"zoom": {
			"value": 1.5
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