# Clans: Single Clan

This endpoint retrieves a specific clan.

## HTTP Request

`GET http://api.cr-api.com/clan/<TAG>`

### URL Parameters

Parameter | Description
--- | ---
TAG | The clan tag of the clan to retrieve

### Query Parameters

Parameter | Default | Description
--- | --- | ---
members | 1 | If set to 0, the result will not include members.


## Response

http://api.cr-api.com/clan/2CCCP

The above command returns JSON structured like this:

```json
{
    "name": "Reddit Alpha",
    "badge": 16000167,
    "type": 2,
    "memberCount": 43,
    "score": 52238,
    "requiredScore": 4600,
    "donations": 7070,
    "description": "Minimum 5200 🏆 to join 🚀When full, #50/50 sent to Reddit Bravo 🚀http://discord.gg/racf",
    "currentRank": 0,
    "badge_url": "/badge/A_Char_Rocket_02.png",
    "tag": "2CCCP",
    "typeName": "Invite Only",
    "region": {
        "isCountry": "true",
        "name": "Niue"
    },
    "members": [
        {
            "avatarId": {
                "low": 1519054,
                "high": 20,
                "unsigned": false
            },
            "name": "PowRay",
            "arena": {
                "imageURL": "/arena/league6.png",
                "arena": "League 6",
                "arenaID": 17,
                "name": "Master III",
                "trophyLimit": 5500
            },
            "role": 3,
            "expLevel": 13,
            "score": 5598,
            "donations": 78,
            "currenRank": 1,
            "previousRank": 2,
            "clanChestCrowns": 0,
            "homeID": {
                "low": 1519054,
                "high": 20,
                "unsigned": false
            },
            "tag": "9RR0CPGU",
            "roleName": "Elder"
        },
        {
            "avatarId": {
                "low": 16708,
                "high": 3,
                "unsigned": false
            },
            "name": "SaintBelikin",
            "arena": {
                "imageURL": "/arena/league6.png",
                "arena": "League 6",
                "arenaID": 17,
                "name": "Master III",
                "trophyLimit": 5500
            },
            "role": 4,
            "expLevel": 13,
            "score": 5597,
            "donations": 0,
            "currenRank": 2,
            "previousRank": 0,
            "clanChestCrowns": 0,
            "homeID": {
                "low": 16708,
                "high": 3,
                "unsigned": false
            },
            "tag": "QVPJRV",
            "roleName": "Co-Leader"
        }
    ]
}
```
