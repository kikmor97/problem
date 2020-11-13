![Logo](https://bend.md/images/5e8730206d541c6309354d3e_image%20(4).png)

# Problem
Convert input data to html template

You must use:
  - `Angular 10`
  - `scss`
  - `css flex` or `css grid`
  - `BehaviorSubject`

## Inputs
#### Areas:
```json
[
	{
		"id": 1892,
		"name": "Zona 2"
	},
	{
		"id": 1901,
		"name": "Zona 5"
	},
	{
		"id": 1893,
		"name": "Zona 0"
	},
	{
		"id": 1791,
		"name": "Zona 1"
	},
	{
		"id": 1900,
		"name": "Zona 4"
	}
]
```
#### Tables:
```json
[
  {
    "id": 2861,
    "areaId": 1791,
    "joinedWith": null,
    "name": "1",
    "defaultSku": "3",
    "status": "open"
  },
  {
    "id": 2967,
    "areaId": 1791,
    "joinedWith": 2861,
    "name": "3",
    "defaultSku": "1",
    "status": "closed"
  },
  {
    "id": 2969,
    "areaId": 1791,
    "joinedWith": 2861,
    "name": "4",
    "defaultSku": "4",
    "status": "open"
  },
  {
    "id": 2970,
    "areaId": 1791,
    "joinedWith": null,
    "name": "5",
    "defaultSku": "5",
    "status": "closed"
  },
  {
    "id": 2971,
    "areaId": 1791,
    "joinedWith": null,
    "name": "6",
    "defaultSku": "6",
    "status": "open"
  },
  {
    "id": 2972,
    "areaId": 1791,
    "joinedWith": 2974,
    "name": "7",
    "defaultSku": "7",
    "status": "open"
  },
  {
    "id": 2973,
    "areaId": 1791,
    "joinedWith": null,
    "name": "8",
    "defaultSku": "8",
    "status": "open"
  },
  {
    "id": 2974,
    "areaId": 1791,
    "joinedWith": null,
    "name": "9",
    "defaultSku": "9",
    "status": "open"
  },
  {
    "id": 2975,
    "areaId": 1791,
    "joinedWith": 2973,
    "name": "10",
    "defaultSku": "10",
    "status": "open"
  },
  {
    "id": 2976,
    "areaId": 1791,
    "joinedWith": 2973,
    "name": "11",
    "defaultSku": "11",
    "status": "open"
  },
  {
    "id": 2977,
    "areaId": 1791,
    "joinedWith": 2861,
    "name": "12",
    "defaultSku": "12",
    "status": "open"
  },
  {
    "id": 2978,
    "areaId": 1791,
    "joinedWith": 2971,
    "name": "13",
    "defaultSku": "13",
    "status": "open"
  },
  {
    "id": 2979,
    "areaId": 1791,
    "joinedWith": null,
    "name": "15",
    "defaultSku": "15",
    "status": "open"
  },
  {
    "id": 2980,
    "areaId": 1791,
    "joinedWith": null,
    "name": "14",
    "defaultSku": "16",
    "status": "open"
  },
  {
    "id": 2966,
    "areaId": 1892,
    "joinedWith": null,
    "name": "2",
    "defaultSku": "2",
    "status": "open"
  },
  {
    "id": 3003,
    "areaId": 1900,
    "joinedWith": null,
    "name": "2",
    "defaultSku": "2",
    "status": "open"
  },
  {
    "id": 3011,
    "areaId": 1900,
    "joinedWith": 3003,
    "name": "22",
    "defaultSku": "22",
    "status": "open"
  },
  {
    "id": 3013,
    "areaId": 1901,
    "joinedWith": 3014,
    "name": "A1",
    "defaultSku": "A1",
    "status": "open"
  },
  {
    "id": 3014,
    "areaId": 1901,
    "joinedWith": null,
    "name": "A2",
    "defaultSku": "A2",
    "status": "open"
  }
]
```

### Outputs
![Dashboard](https://i.imgur.com/hYzU6R4.png)
![Dashboard](https://i.imgur.com/flpPeAh.png)
![Dashboard](https://i.imgur.com/mgAepsa.png)

