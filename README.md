# template

This is my personal template, of which I'll try to keep using xD

```json
[
	Units
   {
	"name": "name",
	"replaces": "unit",
	"unitType": "type",
	"movement": 0,
	"strength": 0,
	"range": 0,
	"rangedStrength": 0,
	"cost": 0,
	"hurryCostModifier": number,
	"requiredTech": "Tech",
	"requieredResourse": "Resource",
	"obsoleteTech": "Tech",
	"upgradesTo": "unit",
	"promotions": ["promotion"],
	"uniqueTo": "civ",
	"uniques": ["uniques"],
   },
	Civs
     {
	"name": "Civ",
	"leaderName": "Leader Name",
	"adjective": ["Civilian"],
	"cityStateType": "Type",
	"outerColor": [3,2,1],
	"innerColor": [1,2,3],

	"startBias": ["terrains"],
	"preferredVictoryType": "Victory type",
	"favoredReligion": "religio",

	"startIntroPart1": "intro",
	"startIntroPart2": "close",

	"introduction": "Speech?",
	"declaringWar": "Frase",
	"attacked": "Frase",
	"afterPeace": "Frase",
	"defeated": "Speech",

	"neutralHello": "Greetings",
	"hateHello": "frase",

	"tradeRequest": "Asking for trade",
	"neutralLetsHearIt": "  ",
	"hateLetsHearIt": "  ",
	"neutralNo": "  ",
	"neutralYes": "  ",
	"hateNo": "  ",
	"hateYes": "  ",
		
	"uniqueName": "Unique Name",
	"uniques": ["Nation Unique"],

	"cities": ["Capital","city","cities","city"]
	},
       Buildings
{
		"name": "Name",
		"replaces": "Building",
		"isNationalWonder": true,
    "isWonder": true,
		"cost": 1,
		"hurryCostModifier": 40,
		"requiredNearbyImprovedResources": ["Resourece"],
		"requiredBuilding": "Monument",
		"requiredTech": "Tech",
		"maintenance": 1,
		"gold": 3,
		"food": 2,
		"science": 3,
		"culture": 1,
		"happiness": 1,
		"production": 3,
		"resourceBonusStats": {"food": 1},
		"percentStatBonus": {"food": 15},
		"specialistSlots": {"Artist": 1},
		"greatPersonPoints": {"production": 1},
		"cityStrength": 5,
		"cityHealth": 50,
		"uniqueTo": "civ",
		"uniques": ["Unique"],
		"quote": " ",
	},
       Tile Improvements
     {
		"name": "name",
		"terrainsCanBeBuiltOn": ["Plains","Grassland"],
		"resourceTerrainAllow": ["Forest"],
		"food": 1,
		"gold": 1,
		"science": 8,
		"culture": 6,
		"production": 1,
		"turnsToBuild": 7,
		"techRequired": "Tech",
		"uniqueTo": "civ",
		"uniques": ["uniques"],
		"shortcutKey": "F",
	},

]
