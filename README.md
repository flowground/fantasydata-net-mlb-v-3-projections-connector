# ![LOGO](logo.png) MLB v3 Projections **flow**ground Connector

## Description

A generated **flow**ground connector for the MLB v3 Projections API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/mlb-v3-projections/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:32+03:00

## API Description

MLB projections API.

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### DFS Slates by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the slates.
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.

### Projected Player Game Stats by Date (w/ Injuries, Lineups, DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.

### Projected Player Game Stats by Player (w/ Injuries, Lineups, DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>10000507</code>.

### Projected Player Season Stats (with ADP)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2017</code>, <code>2018</code>.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-mlb-v-3-projections-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
