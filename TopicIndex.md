# Index By Topic

## Login and User

* [POST /v3/profiles/session](UbiServices.md#post-/v3/profiles/session)
* [POST /v2/authentication/token/ubiservices](ProdTrackmania.md#post-/v2/authentication/token/ubiservices)
* [POST /v2/authentication/token/nadeoservices](ProdTrackmania.md#post-/v2/authentication/token/nadeoservices)
* [POST /v2/authentication/token/basic](ProdTrackmania.md#post-/v2/authentication/token/basic)
* [GET v3/profiles](UbiServices.md#get-v3/profiles)

## Leaderboard

### Get Season and Maps

* [GET /api/token/campaign/official](LiveServices.md#get-/api/token/campaign/official)
* [GET /api/token/campaign/month](LiveServices.md#get-/api/token/campaign/month)
* [GET /api/token/club/campaign](LiveServices.md#get-/api/token/club/campaign)
* [GET /seasons/*seasonid*](ProdTrackmania.md#get-/seasons/*seasonid*)

### Get Scores

* [GET /api/token/leaderboard/group/*groupId*/map](LiveServices.md#get-/api/token/leaderboard/group/*groupId*/map)
* [GET /api/token/leaderboard/group/*groupId*/](LiveServices.md#get-/api/token/leaderboard/group/*groupId*/)
* [GET /api/token/leaderboard/group/*groupId*/top](LiveServices.md#get-/api/token/leaderboard/group/*groupId*/top)
* [GET /api/token/leaderboard/group/*groupId*/map/*mapId*/top](LiveServices.md#get-/api/token/leaderboard/group/*groupId*/map/*mapId*/top)
* [GET /api/token/leaderboard/group/Personal_Best/map/*mapId*/top](LiveServices.md#get-/api/token/leaderboard/group/Personal_Best/map/*mapId*/top)
* [GET /api/token/leaderboard/group/Personal_Best/map/*mapId*/surround/1/1](LiveServices.md#get-/api/token/leaderboard/group/Personal_Best/map/*mapId*/surround/1/1)
* [GET /api/token/leaderboard/group/*groupId*/map/*mapId*/level](LiveServices.md#get-/api/token/leaderboard/group/*groupId*/map/*mapId*/level)

### Get Files (Ghosts, Maps, etc.)

* [GET /mapRecords](ProdTrackmania.md#get-/mapRecords)
* [GET /maps](ProdTrackmania.md#get-/maps)
* [GET /encryptedPackages/versions](ProdTrackmania.md#get-/encryptedPackages/versions)


## Clubs

* [GET /api/token/club/room](LiveServices.md#get-/api/token/club/room)
* [GET /api/token/club/mine](LiveServices.md#get-/api/token/club/mine)
* [GET /api/token/club/*clubId*/member/*accountId*](LiveServices.md#get-/api/token/club/*clubId*/member/*accountId*)
* [GET /api/token/club/*clubId*/activity](LiveServices.md#get-/api/token/club/*clubId*/activity)
* [GET /api/token/club/*clubId*/member](LiveServices.md#get-/api/token/club/*clubId*/member)
* [GET /api/token/club/*clubId*/member/request](LiveServices.md#get-/api/token/club/*clubId*/member/request)
* [GET /api/token/club/*clubId*/room/*activityId(?)*](LiveServices.md#get-/api/token/club/*clubId*/room/*activityId(?)*)

## Skins

* [GET /api/token/club/bucket/skin-upload/all](LiveServices.md#get-/api/token/club/bucket/skin-upload/all)

## Live Arcade

* [GET /api/token/channel/officialhard](LiveServices.md#get-/api/token/channel/officialhard)
* [POST /api/token/channel/officialhard/join](LiveServices.md#post-/api/token/channel/officialhard/join)

## Map Review

* [GET /api/token/map-review/waiting-time](LiveServices.md#get-/api/token/map-review/waiting-time)
* [GET /api/token/map-review/connect](LiveServices.md#get-/api/token/map-review/connect)

## Trophies

* [GET /trophies/settings](ProdTrackmania.md#get-/trophies/settings)
* [GET /accounts/*accountId*/trophies/lastYearSummary](ProdTrackmania.md#get-/accounts/*accountId*/trophies/lastYearSummary)
* [POST /api/token/leaderboard/trophy/player](LiveServices.md#post-/api/token/leaderboard/trophy/player)

## Game Configuration

* [GET /client/config](ProdTrackmania.md#get-/client/config)
* [PUT /waitingQueue/*some id*](ProdTrackmania.md#put-/waitingQueue/*some-id*)
* [PUT /accounts/*accountId*/presence](ProdTrackmania.md#put-/accounts/*accountId*/presence)
* [GET /accounts/*accountId*/policies/global/rules](ProdTrackmania.md#get-/accounts/*accountId*/policies/global/rules)
* [GET /accounts/*accountId*/client/config](ProdTrackmania.md#get-/accounts/*accountId*/client/config)
* [GET /accounts/*accountId*/client/signature](ProdTrackmania.md#get-/accounts/*accountId*/client/signature)
* [GET /accounts/*accountId*/encryptedPackage/key](ProdTrackmania.md#get-/accounts/*accountId*/encryptedPackage/key)
* [GET /client/updaters/current](ProdTrackmania.md#get-/client/updaters/current)
* [GET /accounts/*accountId*/client/urls](ProdTrackmania.md#get-/accounts/*accountId*/client/urls)
* [GET /accounts/*accountId*/client/plugins](ProdTrackmania.md#get-/accounts/*accountId*/client/plugins)
* [GET /accounts/*accountId*/zone](ProdTrackmania.md#get-/accounts/*accountId*/zone)

## Zones

* [GET /zones](ProdTrackmania.md#get-/zones)

## Misc

* [GET /encryptedPackages/versions](ProdTrackmania.md#get-/encryptedPackages/versions)
* [POST /mapRecords](ProdTrackmania.md#post-/mapRecords)
* [GET /servers/*someId*](ProdTrackmania.md#get-/servers/*someId*)
* [GET /api/token/club/follower/map/*mapId*](LiveServices.md#get-/api/token/club/follower/map/*mapId*)
* [GET /api/token/club/player-vip/map/*mapId*](LiveServices.md#get-/api/token/club/player-vip/map/*mapId*)
* [GET /v1/applications/86263886-327a-4328-ac69-527f0d20a237/parameters](UbiServices.md#get-/v1/applications/86263886-327a-4328-ac69-527f0d20a237/parameters)
* [PUT /v1/profiles/me/populations/data](UbiServices.md#put-/v1/profiles/me/populations/data)
* [GET /v1/spaces/*profileId*/parameters](UbiServices.md#get-/v1/spaces/*profileId*/parameters)
* [GET /v1/spaces/*profileId*/configs/primarystore](UbiServices.md#get-/v1/spaces/*profileId*/configs/primarystore)
* [GET /v4/spaces/*profileId*/configs/events](MSR-Akamai.md#get-/v4/spaces/*profileId*/configs/events)
* [POST /v3/profiles/me/events](MSR-Akamai.md#post-/v3/profiles/me/events)
* [GET /club/*clubId*/activity/*nameContent*](MSR-Akamai.md#get-/club/*clubId*/activity/*nameContent*-(ex:/club/3118/activity/65804/5f18c059062cf.png?updateTimestamp=1595457628.png))