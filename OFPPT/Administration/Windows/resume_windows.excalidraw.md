---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
reseau ^6sIKdLwz

Virtualisation ^467TaJGp

DHCP ^Pv49odLq

DNS ^Kbd53zy2

OU ^YupQptsL

stub: serveur assistant le serveur principale DNS
en gerant les enregistrements SOA, NS, A pour reduire
la charge sur serveur principale ^03eh7Bh8

ActiveDirectory ^6jhHT6go

Checkpoint:  ^hn1eFSdO

VHD (max 2To)

VHDX (max 64To) ^9ej6Ndbx

Créer une zone intégrée AD :  ^yMLMN5IP

C:>Add-DnsServerPrimaryZone -Name ofppt.ma -ZoneFile ofppt.ma.dns 
-DynamicUpdate -NonsecureAndSecure  ^xDSItJzm

Installer le rôle DNS :  ^FepL6PfO

C:>Install-WindowsFeature DNS -IncludeManagementTools ^pplbtZ4H

Créer une zone DNS principale :  ^KfyScMDH

C:>Add-DnsServerPrimaryZone -Name ofppt.ma -ZoneFile ofppt.ma.dns 
-DynamicUpdate -NonsecureAndSecure  ^2FkACWVS

unite dorganisation est un conteneur utilise pour
organiser les objets ^7go1Xr9X

FSRM(FileSystemResourceManager) ^7cEq6BKF

strategies de groupes sont des fonctions de gestion
centralise permettant la gestion des ordinateurs et utilisateurs ^AFvrkufH

Active directory est 
un service d'annuaire,
centralise , approuve par
tout les membere des domaines ^i5ZqmSpx

Transfert de zone complet (AXFR) ^5S6l7RrP

Transfert de zone incrémental (IXFR) ^3DkpwGYb


# Embedded files
5bd5da05c8e7854aa88a6c67ed564a0352557355: [[Pasted Image 20240215203429_608.png]]

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.20",
	"elements": [
		{
			"type": "text",
			"version": 97,
			"versionNonce": 831125248,
			"isDeleted": false,
			"id": "6sIKdLwz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -656.6433421543666,
			"y": -191.1140899658203,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 66.0399169921875,
			"height": 25,
			"seed": 1250930406,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "reseau",
			"rawText": "reseau",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "reseau",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 219,
			"versionNonce": 2104817920,
			"isDeleted": false,
			"id": "6jhHT6go",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -318.8531199863978,
			"y": -191.1140899658203,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 150.15985107421875,
			"height": 25,
			"seed": 2020740179,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "ActiveDirectory",
			"rawText": "ActiveDirectory",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ActiveDirectory",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 19,
			"versionNonce": 2066945792,
			"isDeleted": false,
			"id": "Pv49odLq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 340.94754791259766,
			"y": -191.1140899658203,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 52.71995544433594,
			"height": 25,
			"seed": 545499450,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "DHCP",
			"rawText": "DHCP",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "DHCP",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 34,
			"versionNonce": 1450039552,
			"isDeleted": false,
			"id": "Kbd53zy2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 840.6945833478655,
			"y": -191.1140899658203,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 40.63996887207031,
			"height": 25,
			"seed": 1468549306,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "DNS",
			"rawText": "DNS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "DNS",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 244,
			"versionNonce": 1924675328,
			"isDeleted": false,
			"id": "7cEq6BKF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2400.441836765834,
			"y": -185.43633815220426,
			"strokeColor": "#099268",
			"backgroundColor": "transparent",
			"width": 335.21966552734375,
			"height": 25,
			"seed": 1112512256,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "FSRM(FileSystemResourceManager)",
			"rawText": "FSRM(FileSystemResourceManager)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "FSRM(FileSystemResourceManager)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 241,
			"versionNonce": 1565178112,
			"isDeleted": false,
			"id": "03eh7Bh8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 613.9272875104634,
			"y": -100.22753124076775,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 537.239501953125,
			"height": 75,
			"seed": 735277494,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "stub: serveur assistant le serveur principale DNS\nen gerant les enregistrements SOA, NS, A pour reduire\nla charge sur serveur principale",
			"rawText": "stub: serveur assistant le serveur principale DNS\nen gerant les enregistrements SOA, NS, A pour reduire\nla charge sur serveur principale",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "stub: serveur assistant le serveur principale DNS\nen gerant les enregistrements SOA, NS, A pour reduire\nla charge sur serveur principale",
			"lineHeight": 1.25,
			"baseline": 67
		},
		{
			"type": "text",
			"version": 297,
			"versionNonce": 2090424064,
			"isDeleted": false,
			"id": "467TaJGp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 17.174880268809858,
			"y": -191.1140899658203,
			"strokeColor": "#0c8599",
			"backgroundColor": "transparent",
			"width": 129.2598419189453,
			"height": 25,
			"seed": 1396604902,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Virtualisation",
			"rawText": "Virtualisation",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Virtualisation",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 53,
			"versionNonce": 898341120,
			"isDeleted": false,
			"id": "9ej6Ndbx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -5.185112712147173,
			"y": -116.9116419155356,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 173.97982788085938,
			"height": 75,
			"seed": 2052143165,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "VHD (max 2To)\n\nVHDX (max 64To)",
			"rawText": "VHD (max 2To)\n\nVHDX (max 64To)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "VHD (max 2To)\n\nVHDX (max 64To)",
			"lineHeight": 1.25,
			"baseline": 67
		},
		{
			"type": "text",
			"version": 87,
			"versionNonce": 1834383104,
			"isDeleted": false,
			"id": "hn1eFSdO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -5.185112712147173,
			"y": -26.63598099198657,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 114.27987670898438,
			"height": 25,
			"seed": 1051656381,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Checkpoint: ",
			"rawText": "Checkpoint: ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Checkpoint: ",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"id": "FepL6PfO",
			"type": "text",
			"x": 541.8828661016761,
			"y": 78.7208645353166,
			"width": 285.7346460193395,
			"height": 30.6109619140625,
			"angle": 0,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1896724224,
			"version": 49,
			"versionNonce": 158308096,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"text": "Installer le rôle DNS : ",
			"rawText": "Installer le rôle DNS : ",
			"fontSize": 24.488769531249996,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 21,
			"containerId": null,
			"originalText": "Installer le rôle DNS : ",
			"lineHeight": 1.25
		},
		{
			"id": "pplbtZ4H",
			"type": "text",
			"x": 547.4534280791958,
			"y": 150.12384735930553,
			"width": 621.09375,
			"height": 24,
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
			"seed": 1044445440,
			"version": 101,
			"versionNonce": 943282432,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"text": "C:>Install-WindowsFeature DNS -IncludeManagementTools",
			"rawText": "C:>Install-WindowsFeature DNS -IncludeManagementTools",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 19,
			"containerId": null,
			"originalText": "C:>Install-WindowsFeature DNS -IncludeManagementTools",
			"lineHeight": 1.2
		},
		{
			"id": "KfyScMDH",
			"type": "text",
			"x": 534.4018229031467,
			"y": 218.99397890801873,
			"width": 390.59326171875,
			"height": 30.610961914062496,
			"angle": 0,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1635678464,
			"version": 57,
			"versionNonce": 90486528,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"text": "Créer une zone DNS principale : ",
			"rawText": "Créer une zone DNS principale : ",
			"fontSize": 24.488769531249996,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 21,
			"containerId": null,
			"originalText": "Créer une zone DNS principale : ",
			"lineHeight": 1.25
		},
		{
			"id": "2FkACWVS",
			"type": "text",
			"x": 512.852741613203,
			"y": 274.0318925109598,
			"width": 773.4375,
			"height": 48,
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
			"seed": 2101827840,
			"version": 165,
			"versionNonce": 2040936704,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"text": "C:>Add-DnsServerPrimaryZone -Name ofppt.ma -ZoneFile ofppt.ma.dns \n-DynamicUpdate -NonsecureAndSecure ",
			"rawText": "C:>Add-DnsServerPrimaryZone -Name ofppt.ma -ZoneFile ofppt.ma.dns \n-DynamicUpdate -NonsecureAndSecure ",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 43,
			"containerId": null,
			"originalText": "C:>Add-DnsServerPrimaryZone -Name ofppt.ma -ZoneFile ofppt.ma.dns \n-DynamicUpdate -NonsecureAndSecure ",
			"lineHeight": 1.2
		},
		{
			"id": "yMLMN5IP",
			"type": "text",
			"x": 530.6613013038818,
			"y": 389.6595493354083,
			"width": 367.71502685546875,
			"height": 30.610961914062496,
			"angle": 0,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1283774208,
			"version": 90,
			"versionNonce": 95803136,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"text": "Créer une zone intégrée AD : ",
			"rawText": "Créer une zone intégrée AD : ",
			"fontSize": 24.488769531249996,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 21,
			"containerId": null,
			"originalText": "Créer une zone intégrée AD : ",
			"lineHeight": 1.25
		},
		{
			"id": "xDSItJzm",
			"type": "text",
			"x": 512.852741613203,
			"y": 440.02173913320235,
			"width": 773.4375,
			"height": 48,
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
			"seed": 263133440,
			"version": 179,
			"versionNonce": 980883712,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"text": "C:>Add-DnsServerPrimaryZone -Name ofppt.ma -ZoneFile ofppt.ma.dns \n-DynamicUpdate -NonsecureAndSecure ",
			"rawText": "C:>Add-DnsServerPrimaryZone -Name ofppt.ma -ZoneFile ofppt.ma.dns \n-DynamicUpdate -NonsecureAndSecure ",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 43,
			"containerId": null,
			"originalText": "C:>Add-DnsServerPrimaryZone -Name ofppt.ma -ZoneFile ofppt.ma.dns \n-DynamicUpdate -NonsecureAndSecure ",
			"lineHeight": 1.2
		},
		{
			"type": "text",
			"version": 268,
			"versionNonce": 518190848,
			"isDeleted": false,
			"id": "YupQptsL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1702.934207371303,
			"y": -185.43633815220426,
			"strokeColor": "#099268",
			"backgroundColor": "transparent",
			"width": 28.799972534179688,
			"height": 25,
			"seed": 409358714,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "OU",
			"rawText": "OU",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "OU",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"id": "7go1Xr9X",
			"type": "text",
			"x": 1520.6781569621976,
			"y": -31.238224404128914,
			"width": 574.21875,
			"height": 48,
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
			"seed": 1609767168,
			"version": 123,
			"versionNonce": 1433147136,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"text": "unite dorganisation est un conteneur utilise pour\norganiser les objets",
			"rawText": "unite dorganisation est un conteneur utilise pour\norganiser les objets",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 43,
			"containerId": null,
			"originalText": "unite dorganisation est un conteneur utilise pour\norganiser les objets",
			"lineHeight": 1.2
		},
		{
			"id": "AFvrkufH",
			"type": "text",
			"x": 1539.5751048097998,
			"y": 274.8153462635132,
			"width": 750,
			"height": 48,
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
			"seed": 986822400,
			"version": 145,
			"versionNonce": 587192064,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708025825905,
			"link": null,
			"locked": false,
			"text": "strategies de groupes sont des fonctions de gestion\ncentralise permettant la gestion des ordinateurs et utilisateurs",
			"rawText": "strategies de groupes sont des fonctions de gestion\ncentralise permettant la gestion des ordinateurs et utilisateurs",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 43,
			"containerId": null,
			"originalText": "strategies de groupes sont des fonctions de gestion\ncentralise permettant la gestion des ordinateurs et utilisateurs",
			"lineHeight": 1.2
		},
		{
			"id": "x-F29HQIoJJTPs4jTWSLA",
			"type": "image",
			"x": 1522.5799347024142,
			"y": 363.83654822687225,
			"width": 804.7068903996401,
			"height": 64.82361061552656,
			"angle": 0,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 547641600,
			"version": 85,
			"versionNonce": 73488640,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708025672823,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "5bd5da05c8e7854aa88a6c67ed564a0352557355",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "i5ZqmSpx",
			"type": "text",
			"x": -399.76791359971935,
			"y": -126.29816434902932,
			"width": 339.84375,
			"height": 96,
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
			"seed": 1688877312,
			"version": 172,
			"versionNonce": 1720604928,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708028383089,
			"link": null,
			"locked": false,
			"text": "Active directory est \nun service d'annuaire,\ncentralise , approuve par\ntout les membere des domaines",
			"rawText": "Active directory est \nun service d'annuaire,\ncentralise , approuve par\ntout les membere des domaines",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 91,
			"containerId": null,
			"originalText": "Active directory est \nun service d'annuaire,\ncentralise , approuve par\ntout les membere des domaines",
			"lineHeight": 1.2
		},
		{
			"id": "5S6l7RrP",
			"type": "text",
			"x": 466.67151695638677,
			"y": 633.4505300018823,
			"width": 595.8533839671306,
			"height": 38.13461657389636,
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
			"seed": 1398970624,
			"version": 50,
			"versionNonce": 1421580544,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708031819495,
			"link": null,
			"locked": false,
			"text": "Transfert de zone complet (AXFR)",
			"rawText": "Transfert de zone complet (AXFR)",
			"fontSize": 31.778847144913634,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 30,
			"containerId": null,
			"originalText": "Transfert de zone complet (AXFR)",
			"lineHeight": 1.2
		},
		{
			"id": "3DkpwGYb",
			"type": "text",
			"x": 466.67151695638677,
			"y": 747.599052723826,
			"width": 670.3350569630219,
			"height": 38.13461657389636,
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
			"seed": 885922048,
			"version": 59,
			"versionNonce": 1273002240,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1708031819495,
			"link": null,
			"locked": false,
			"text": "Transfert de zone incrémental (IXFR)",
			"rawText": "Transfert de zone incrémental (IXFR)",
			"fontSize": 31.77884714491363,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 30.000000000000007,
			"containerId": null,
			"originalText": "Transfert de zone incrémental (IXFR)",
			"lineHeight": 1.2
		},
		{
			"id": "ndKKbKCx",
			"type": "text",
			"x": 663.3527272519898,
			"y": 45.74802158954458,
			"width": 457.03125,
			"height": 480,
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
			"seed": 295016704,
			"version": 7,
			"versionNonce": 313555200,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"text": "Créer une zone DNS inversée :\n\nC:\\>Add-DnsServerPrimaryZone -NetworkId\nCréer un enregistrement A :\nIncludeManagementTools\n172.18.0.0/16 -ZoneFile 18.172.in-\nC:\\>Add-DnsServerResourceRecordA -\nAutoriser le serveur DHCP dans AD :\nLier un GPO à un OU:\naddr.arpa.dns - DynamicUpdate\nZoneName\nofppt.ma\n-Name\nlon-client1\n-\nC:\\>Add-DhcpServerInDC\n-DnsName\nlon-\nC:\\>New-GPLINK –Name “GPO01” -Target\nNonsecureAndSecure",
			"rawText": "Créer une zone DNS inversée :\n\nC:\\>Add-DnsServerPrimaryZone -NetworkId\nCréer un enregistrement A :\nIncludeManagementTools\n172.18.0.0/16 -ZoneFile 18.172.in-\nC:\\>Add-DnsServerResourceRecordA -\nAutoriser le serveur DHCP dans AD :\nLier un GPO à un OU:\naddr.arpa.dns - DynamicUpdate\nZoneName\nofppt.ma\n-Name\nlon-client1\n-\nC:\\>Add-DhcpServerInDC\n-DnsName\nlon-\nC:\\>New-GPLINK –Name “GPO01” -Target\nNonsecureAndSecure",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 475,
			"containerId": null,
			"originalText": "Créer une zone DNS inversée :\n\nC:\\>Add-DnsServerPrimaryZone -NetworkId\nCréer un enregistrement A :\nIncludeManagementTools\n172.18.0.0/16 -ZoneFile 18.172.in-\nC:\\>Add-DnsServerResourceRecordA -\nAutoriser le serveur DHCP dans AD :\nLier un GPO à un OU:\naddr.arpa.dns - DynamicUpdate\nZoneName\nofppt.ma\n-Name\nlon-client1\n-\nC:\\>Add-DhcpServerInDC\n-DnsName\nlon-\nC:\\>New-GPLINK –Name “GPO01” -Target\nNonsecureAndSecure",
			"lineHeight": 1.2
		},
		{
			"id": "axtg2VOF",
			"type": "text",
			"x": 1723.2231534357218,
			"y": -126.53020980994484,
			"width": 11.71875,
			"height": 24,
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
			"seed": 798652160,
			"version": 3,
			"versionNonce": 1848375552,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 19,
			"containerId": null,
			"originalText": "",
			"lineHeight": 1.2
		},
		{
			"id": "x42aec9Q",
			"type": "text",
			"x": 1847.8663529496805,
			"y": 275.1570171929527,
			"width": 11.71875,
			"height": 24,
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
			"seed": 211597056,
			"version": 3,
			"versionNonce": 500250368,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 19,
			"containerId": null,
			"originalText": "",
			"lineHeight": 1.2
		},
		{
			"id": "fDux4m-UNHDilh4QY6PgT",
			"type": "line",
			"x": 2168.665099694472,
			"y": 267.77128856882075,
			"width": 0,
			"height": 0,
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
			"roundness": {
				"type": 2
			},
			"seed": 1917097728,
			"version": 19,
			"versionNonce": 1279375616,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1708025491041,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": [
				0,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "G3S5Ee1Z",
			"type": "text",
			"x": 1628.9774640607916,
			"y": 376.2681283040638,
			"width": 11.71875,
			"height": 24,
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
			"seed": 620574464,
			"version": 2,
			"versionNonce": 1820031232,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1708025663391,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 19,
			"containerId": null,
			"originalText": "",
			"lineHeight": 1.2
		},
		{
			"id": "3YggLVGB",
			"type": "text",
			"x": -318.0792238501084,
			"y": -121.3740005508912,
			"width": 11.71875,
			"height": 24,
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
			"seed": 1783544064,
			"version": 2,
			"versionNonce": 454194944,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1708028216498,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 19,
			"containerId": null,
			"originalText": "",
			"lineHeight": 1.2
		},
		{
			"id": "3CiH2Fxp",
			"type": "text",
			"x": -73.56014534230076,
			"y": -90.9465181653506,
			"width": 11.71875,
			"height": 24,
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
			"seed": 1929484032,
			"version": 2,
			"versionNonce": 1752447232,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1708028270267,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 19,
			"containerId": null,
			"originalText": "",
			"lineHeight": 1.2
		},
		{
			"id": "8qS2YFFA",
			"type": "text",
			"x": 317.00879242663393,
			"y": 563.0485532337024,
			"width": 1851.5625,
			"height": 384,
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
			"seed": 1702279424,
			"version": 55,
			"versionNonce": 772069632,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1708031789597,
			"link": null,
			"locked": false,
			"text": "1. Transfert de zone complet (AXFR):\n\nCe mode est utilisé pour transférer l'intégralité de la zone DNS du serveur DNS primaire au serveur DNS secondaire.\nIl est utilisé lors de la configuration initiale du serveur DNS secondaire ou après une restauration complète de la zone DNS.\nCe mode peut prendre du temps et utiliser beaucoup de bande passante, en particulier pour les zones DNS volumineuses.\n2. Transfert de zone incrémental (IXFR):\n\nCe mode est utilisé pour transférer uniquement les modifications apportées à la zone DNS depuis la dernière synchronisation.\nIl est utilisé pour réduire la bande passante utilisée et d'accélérer le processus de transfert.\nCe mode nécessite que le serveur DNS primaire et le serveur DNS secondaire utilisent la même version du service DNS et qu'ils aient une relation de confiance.\n3. Transfert de zone notify (AXFR/IXFR):\n\nCe mode est utilisé pour notifier le serveur DNS secondaire qu'une modification a été apportée à la zone DNS.\nLe serveur DNS secondaire peut ensuite demander un transfert de zone complet (AXFR) ou incrémental (IXFR) pour obtenir les modifications.\nCe mode permet de réduire la bande passante utilisée et d'accélérer le processus de transfert.\nCe mode nécessite que le serveur DNS primaire et le serveur DNS secondaire utilisent la même version du service DNS et qu'ils aient une relation de confiance.",
			"rawText": "1. Transfert de zone complet (AXFR):\n\nCe mode est utilisé pour transférer l'intégralité de la zone DNS du serveur DNS primaire au serveur DNS secondaire.\nIl est utilisé lors de la configuration initiale du serveur DNS secondaire ou après une restauration complète de la zone DNS.\nCe mode peut prendre du temps et utiliser beaucoup de bande passante, en particulier pour les zones DNS volumineuses.\n2. Transfert de zone incrémental (IXFR):\n\nCe mode est utilisé pour transférer uniquement les modifications apportées à la zone DNS depuis la dernière synchronisation.\nIl est utilisé pour réduire la bande passante utilisée et d'accélérer le processus de transfert.\nCe mode nécessite que le serveur DNS primaire et le serveur DNS secondaire utilisent la même version du service DNS et qu'ils aient une relation de confiance.\n3. Transfert de zone notify (AXFR/IXFR):\n\nCe mode est utilisé pour notifier le serveur DNS secondaire qu'une modification a été apportée à la zone DNS.\nLe serveur DNS secondaire peut ensuite demander un transfert de zone complet (AXFR) ou incrémental (IXFR) pour obtenir les modifications.\nCe mode permet de réduire la bande passante utilisée et d'accélérer le processus de transfert.\nCe mode nécessite que le serveur DNS primaire et le serveur DNS secondaire utilisent la même version du service DNS et qu'ils aient une relation de confiance.",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 379,
			"containerId": null,
			"originalText": "1. Transfert de zone complet (AXFR):\n\nCe mode est utilisé pour transférer l'intégralité de la zone DNS du serveur DNS primaire au serveur DNS secondaire.\nIl est utilisé lors de la configuration initiale du serveur DNS secondaire ou après une restauration complète de la zone DNS.\nCe mode peut prendre du temps et utiliser beaucoup de bande passante, en particulier pour les zones DNS volumineuses.\n2. Transfert de zone incrémental (IXFR):\n\nCe mode est utilisé pour transférer uniquement les modifications apportées à la zone DNS depuis la dernière synchronisation.\nIl est utilisé pour réduire la bande passante utilisée et d'accélérer le processus de transfert.\nCe mode nécessite que le serveur DNS primaire et le serveur DNS secondaire utilisent la même version du service DNS et qu'ils aient une relation de confiance.\n3. Transfert de zone notify (AXFR/IXFR):\n\nCe mode est utilisé pour notifier le serveur DNS secondaire qu'une modification a été apportée à la zone DNS.\nLe serveur DNS secondaire peut ensuite demander un transfert de zone complet (AXFR) ou incrémental (IXFR) pour obtenir les modifications.\nCe mode permet de réduire la bande passante utilisée et d'accélérer le processus de transfert.\nCe mode nécessite que le serveur DNS primaire et le serveur DNS secondaire utilisent la même version du service DNS et qu'ils aient une relation de confiance.",
			"lineHeight": 1.2
		},
		{
			"id": "8w4fHHOR",
			"type": "text",
			"x": 335.2906192260258,
			"y": 980.8591135835549,
			"width": 1066.40625,
			"height": 720,
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
			"seed": 68327168,
			"version": 42,
			"versionNonce": 1428354816,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1708031788641,
			"link": null,
			"locked": false,
			"text": "1. Transfert de zone complet (AXFR):\n\nUtilisé pour:\nConfiguration initiale du serveur DNS secondaire.\nRestauration complète de la zone DNS.\nAvantages:\nSimple à mettre en place.\nInconvénients:\nLourd et long.\nConsomme beaucoup de bande passante.\n2. Transfert de zone incrémental (IXFR):\n\nUtilisé pour:\nSynchroniser les modifications depuis la dernière synchronisation.\nAvantages:\nRapide et efficace.\nRéduit la bande passante utilisée.\nInconvénients:\nNécessite une configuration plus complexe.\nNécessite une version compatible du service DNS et une relation de confiance.\n3. Transfert de zone notify (AXFR/IXFR):\n\nUtilisé pour:\nNotifier le serveur secondaire d'une modification.\nLe serveur secondaire peut ensuite demander un AXFR ou IXFR pour obtenir les modifications.\nAvantages:\nRéduit la bande passante et le temps de transfert.\nInconvénients:\nNécessite une configuration plus complexe.\nNécessite une version compatible du service DNS et une relation de confiance.",
			"rawText": "1. Transfert de zone complet (AXFR):\n\nUtilisé pour:\nConfiguration initiale du serveur DNS secondaire.\nRestauration complète de la zone DNS.\nAvantages:\nSimple à mettre en place.\nInconvénients:\nLourd et long.\nConsomme beaucoup de bande passante.\n2. Transfert de zone incrémental (IXFR):\n\nUtilisé pour:\nSynchroniser les modifications depuis la dernière synchronisation.\nAvantages:\nRapide et efficace.\nRéduit la bande passante utilisée.\nInconvénients:\nNécessite une configuration plus complexe.\nNécessite une version compatible du service DNS et une relation de confiance.\n3. Transfert de zone notify (AXFR/IXFR):\n\nUtilisé pour:\nNotifier le serveur secondaire d'une modification.\nLe serveur secondaire peut ensuite demander un AXFR ou IXFR pour obtenir les modifications.\nAvantages:\nRéduit la bande passante et le temps de transfert.\nInconvénients:\nNécessite une configuration plus complexe.\nNécessite une version compatible du service DNS et une relation de confiance.",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 715,
			"containerId": null,
			"originalText": "1. Transfert de zone complet (AXFR):\n\nUtilisé pour:\nConfiguration initiale du serveur DNS secondaire.\nRestauration complète de la zone DNS.\nAvantages:\nSimple à mettre en place.\nInconvénients:\nLourd et long.\nConsomme beaucoup de bande passante.\n2. Transfert de zone incrémental (IXFR):\n\nUtilisé pour:\nSynchroniser les modifications depuis la dernière synchronisation.\nAvantages:\nRapide et efficace.\nRéduit la bande passante utilisée.\nInconvénients:\nNécessite une configuration plus complexe.\nNécessite une version compatible du service DNS et une relation de confiance.\n3. Transfert de zone notify (AXFR/IXFR):\n\nUtilisé pour:\nNotifier le serveur secondaire d'une modification.\nLe serveur secondaire peut ensuite demander un AXFR ou IXFR pour obtenir les modifications.\nAvantages:\nRéduit la bande passante et le temps de transfert.\nInconvénients:\nNécessite une configuration plus complexe.\nNécessite une version compatible du service DNS et une relation de confiance.",
			"lineHeight": 1.2
		}
	],
	"appState": {
		"theme": "dark",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 3,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 250.94017807044327,
		"scrollY": -42.03027941745487,
		"zoom": {
			"value": 0.4788107009300619
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
		}
	},
	"files": {}
}
```
%%