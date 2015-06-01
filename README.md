# mcc-mnc-json
"mcc-mnc" stands for Mobile Country Code - Mobile Network Code. "mcc-mnc-json" is a json that contains a relation of country codes with their respective network codes and names.

If you have the country and network codes and want to know to which country and network they belong, 
all you need to do is pass these two codes to "MCCMNC" json.

## Install

```
bower install mcc-mnc-json --save
```

## Usage

EXAMPLE: I want to know the country and network names of the following codes, MCC:310 MNC:270.

```javascript
MCCMNC['310']['name'] // will return 'United States'

MCCMNC['310']['270']['name'] // will return 'T-Mobile'
```

EXAMPLE: I want to know all networks codes of United States.

```javascript
MCCMNC['310'] // will return an object of all network codes with their respective names of United States Networks.

```
