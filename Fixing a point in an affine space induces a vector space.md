---
Date: 2023-07-13
tags:
  - mathematics
aliases: 
excalidraw-open-md: true
excalidraw-plugin: parsed
---
![[Fixing a point in an affine space induces a vector space.svg]]

up:: [[Affine Space]]

Let $(A, V, +)$ be an affine space, and let $O \in A$ be a fixed point (which will play the role of the origin). For all $x \in A$, write $\vec{Ox} = O - x \in V$ as the vector separating $O$ and $x$.

Then the function
$$\begin{align*}
m_O: &A \to V\\
&x \to \vec{Ox}
\end{align*}
$$
is a [[Bijective Function|Bijection]][^1], with inverse 
$$\begin{align*}
m_O^{-1}: &V \to A\\
&v \to O + v
\end{align*}
$$

Using these operators, one can create the [[Vector Space]] operations on $A$ as
$$\begin{align*}
x + y &:= m^{-1}_O(\vec{Ox} + \vec{Oy})\\
\lambda x &:= m^{-1}_O(\lambda \vec{Ox})
\end{align*}
$$

Thus, $A$ can be seen as a vector space, with the fixed point $O$ acting as its origin.

When seeing the affine space as a vector space, [[An affine space with a fixed point is isomorphic to its underlying vector space]][^2], since to each point in $A$ there is only one $v \in V$ ─ thus, being trivially isomorphic to the entire vector space $V$.

---
### References
- [Affine transformation - Wikipedia](https://en.wikipedia.org/wiki/Affine_transformation#Structure)

[^1]: It is [[Surjective Function|Surjective]] due to the space's [[Group Action]] being [[Transitive Group Action|Transitive]], and [[Injective Function|Injective]] due to the action being [[Free Group Action|Free]] ─ i.e. due to the group action being [[Regular Group Action|Regular]].
[^2]: This is true if the entire vector space spans the affine space, which we pressupose due to the group action's domain covering the entirety of $V$, as well as the regularity of the action (that is, there are no "lazy vectors" allowed; all vectors "induce movement" upon the space).

%%
# Text Elements
# Embedded files
9e690aeffae11eb9dcd6eee935506314d81e5928: $$O$$
13ef917f1018fefd324e91136048e9d3d0d30f19: $$\vec{Ox}$$
ea2e2779742ed75fb91e7f1425e92d311a5a1e5e: $$\vec{Oy}$$
6308de99782cd713b736240aeabf63d9668ab694: $$\vec{Ox} + \vec{Oy}$$
f6d75087689f9cea17c5ec842649390cb4dab065: $$m^{-1}_O(\vec{Oy}) = y$$
c01ccdbe9f502fe96065a29b49e0a4b0e330baff: $$m^{-1}_O(\vec{Ox}) = x$$
db13775b7f3c504a8b5e697c8abc33eadf6edc89: $$m^{-1}_O(\vec{Ox} + \vec{Oy}) \equiv x + y$$
03b00cd52ce5cda58fba6a705af9e1481178670e: $$m^{-1}_O(\vec{Oz}) = z$$
d475b58ea838e22b5e22b6727c57a8efd7576add: $$m^{-1}_O(\lambda \vec{Oz}) \equiv \lambda z$$
48c26530c85c63b56130745d3e468b64d25921d3: $$\vec{Oz}$$
f2c38bb67e23062fad8871a6287efc2f50a76f32: $$\lambda \vec{Oz}$$

# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.1.6",
	"elements": [
		{
			"type": "arrow",
			"version": 213,
			"versionNonce": 141517625,
			"isDeleted": false,
			"id": "iIMO51gnj9VrJoKvTQaxj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -152.5520782470703,
			"y": 40.26909637451172,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 328.8888854980469,
			"height": 0,
			"seed": 1598239319,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689301476770,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YdMiXDU9uJMbcQG2w7p9P",
				"focus": -2.119780739148458,
				"gap": 6.718684434890747
			},
			"endBinding": {
				"elementId": "mBGW3dX3",
				"focus": -0.27778371175130206,
				"gap": 5.44439697265625
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
					328.8888854980469,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 302,
			"versionNonce": 384865305,
			"isDeleted": false,
			"id": "viZDTr3asMqG6c34d0rMS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -151.47236873187123,
			"y": 39.59569001607597,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 195.4376928847283,
			"seed": 63012281,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689301476770,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YdMiXDU9uJMbcQG2w7p9P",
				"focus": 0.09464468809217408,
				"gap": 7.3920907933264886
			},
			"endBinding": {
				"elementId": "ub9OwDKZ",
				"focus": -0.9467098333380728,
				"gap": 6.333343505859375
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
					-195.4376928847283
				]
			]
		},
		{
			"type": "image",
			"version": 192,
			"versionNonce": 1352080471,
			"isDeleted": false,
			"id": "KcWYMxIA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -12.186786389883228,
			"y": 48.80027688373013,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.60285134421958,
			"height": 18.49324200890693,
			"seed": 13729,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689301440789,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "13ef917f1018fefd324e91136048e9d3d0d30f19",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 163,
			"versionNonce": 2100869273,
			"isDeleted": false,
			"id": "V128lENe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -184.70682322291245,
			"y": -69.07672477834518,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20.97617696340303,
			"height": 22.024985811573185,
			"seed": 50828,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689301440789,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "ea2e2779742ed75fb91e7f1425e92d311a5a1e5e",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "line",
			"version": 57,
			"versionNonce": 440367479,
			"isDeleted": false,
			"id": "f1zGlWFg2-iHFOudYbU-R",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -150.88539123535156,
			"y": -155.28646087646484,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 324.4445495605469,
			"height": 0,
			"seed": 68949431,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689301440789,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					324.4445495605469,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 167,
			"versionNonce": 1185430905,
			"isDeleted": false,
			"id": "oZT7c6APqx1uphupz3c2T",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 173.48988326974214,
			"y": -153.21962038480365,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.2222595214844034,
			"height": 192.77777099609375,
			"seed": 36196249,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689301440789,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.2222595214844034,
					192.77777099609375
				]
			]
		},
		{
			"type": "arrow",
			"version": 85,
			"versionNonce": 601401593,
			"isDeleted": false,
			"id": "HAj0g6HxG__XDygc2vePr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -150.88539123535156,
			"y": 37.491294860839844,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 323.8888854980469,
			"height": 193.33331298828125,
			"seed": 985961977,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689301476770,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YdMiXDU9uJMbcQG2w7p9P",
				"focus": -1.218231596012861,
				"gap": 9.496485948562622
			},
			"endBinding": {
				"elementId": "Hn0rGw20",
				"focus": 0.5294837118550485,
				"gap": 4.66668701171875
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
					323.8888854980469,
					-193.33331298828125
				]
			]
		},
		{
			"type": "image",
			"version": 89,
			"versionNonce": 1167337049,
			"isDeleted": false,
			"id": "LEhvl40v",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 5.756559034907362,
			"x": -26.75870895199364,
			"y": -87.78654867539805,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 63.968742366877905,
			"height": 21.66683209200703,
			"seed": 29730,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689301440789,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "6308de99782cd713b736240aeabf63d9668ab694",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 62,
			"versionNonce": 703252407,
			"isDeleted": false,
			"id": "ub9OwDKZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -244.44923729719008,
			"y": -186.04833007430193,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 96.01630296352077,
			"height": 23.745967399580408,
			"seed": 84859,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "viZDTr3asMqG6c34d0rMS",
					"type": "arrow"
				}
			],
			"updated": 1689301440789,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "f6d75087689f9cea17c5ec842649390cb4dab065",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 52,
			"versionNonce": 1422914361,
			"isDeleted": false,
			"id": "mBGW3dX3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 181.49940583747494,
			"y": 25.004309066321028,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 98.56359677231575,
			"height": 23.862765534350128,
			"seed": 69613,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "iIMO51gnj9VrJoKvTQaxj",
					"type": "arrow"
				}
			],
			"updated": 1689301440789,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "c01ccdbe9f502fe96065a29b49e0a4b0e330baff",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 51,
			"versionNonce": 382122199,
			"isDeleted": false,
			"id": "Hn0rGw20",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 171.51312093283292,
			"y": -184.3993108036116,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 168.53641072222476,
			"height": 23.781211328902877,
			"seed": 12197,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "HAj0g6HxG__XDygc2vePr",
					"type": "arrow"
				}
			],
			"updated": 1689301440789,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "db13775b7f3c504a8b5e697c8abc33eadf6edc89",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 221,
			"versionNonce": 145433049,
			"isDeleted": false,
			"id": "HM78l74zCZIxMAnXTc0GT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -151.86333465576172,
			"y": 39.09889531135559,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 169.44442749023438,
			"height": 101.66668701171875,
			"seed": 2146026007,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1689301476770,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YdMiXDU9uJMbcQG2w7p9P",
				"focus": -1.1851810031461925,
				"gap": 7.888885498046875
			},
			"endBinding": {
				"elementId": "tIWbs3sqlAtNGx734FVg3",
				"focus": -1.1245460016291642,
				"gap": 5.55560302734375
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
					169.44442749023438,
					101.66668701171875
				]
			]
		},
		{
			"type": "arrow",
			"version": 646,
			"versionNonce": 14672077,
			"isDeleted": false,
			"id": "8tdDzCnVT3cIW33QGEgGx",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -153.42629446037114,
			"y": 39.3830483659357,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 223.88888549804688,
			"height": 134.4444580078125,
			"seed": 972475587,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1714502507600,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YdMiXDU9uJMbcQG2w7p9P",
				"focus": -1.0828641920740747,
				"gap": 7.604732443466773
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
					223.88888549804688,
					134.4444580078125
				]
			]
		},
		{
			"type": "image",
			"version": 315,
			"versionNonce": 1142272473,
			"isDeleted": false,
			"id": "Dm43hkRa6X8r7VeOeEOAz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0.011169976717321894,
			"x": 89.44723807624588,
			"y": 159.55564048998949,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 112.48999955551605,
			"height": 23.30873864663846,
			"seed": 94339033,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689301440790,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "d475b58ea838e22b5e22b6727c57a8efd7576add",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 203,
			"versionNonce": 358949847,
			"isDeleted": false,
			"id": "tIWbs3sqlAtNGx734FVg3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 23.639384111565725,
			"y": 116.03013988355855,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 92.99462350050136,
			"height": 23.24865587512534,
			"seed": 1575515257,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "HM78l74zCZIxMAnXTc0GT",
					"type": "arrow"
				}
			],
			"updated": 1689301446350,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "03b00cd52ce5cda58fba6a705af9e1481178670e",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 105,
			"versionNonce": 579822457,
			"isDeleted": false,
			"id": "8fbrPXBT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0.6091666828217566,
			"x": -92.13744954677772,
			"y": 93.74112928737088,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20.548046676563256,
			"height": 18.49324200890693,
			"seed": 21973,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689301456487,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "48c26530c85c63b56130745d3e468b64d25921d3",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 62,
			"versionNonce": 1687310487,
			"isDeleted": false,
			"id": "TO5zX6Eq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0.5404185308878899,
			"x": 3.5402302862479633,
			"y": 156.36082693551785,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 30.304015135511886,
			"height": 18.80938870480048,
			"seed": 81040,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689301469295,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "f2c38bb67e23062fad8871a6287efc2f50a76f32",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 106,
			"versionNonce": 1946920279,
			"isDeleted": false,
			"id": "YdMiXDU9uJMbcQG2w7p9P",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -162.41881561279297,
			"y": 46.987780809402466,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 12,
			"seed": 898666681,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "iIMO51gnj9VrJoKvTQaxj",
					"type": "arrow"
				},
				{
					"id": "viZDTr3asMqG6c34d0rMS",
					"type": "arrow"
				},
				{
					"id": "HAj0g6HxG__XDygc2vePr",
					"type": "arrow"
				},
				{
					"id": "HM78l74zCZIxMAnXTc0GT",
					"type": "arrow"
				},
				{
					"id": "8tdDzCnVT3cIW33QGEgGx",
					"type": "arrow"
				}
			],
			"updated": 1689301476770,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "9e690aeffae11eb9dcd6eee935506314d81e5928",
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
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 0,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 260.9931005889233,
		"scrollY": 294.8819514601205,
		"zoom": {
			"value": 1.4000000000000001
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