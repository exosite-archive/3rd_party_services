# Slack

The collaboration hub that moves work forward

## Full Description

The Slack Web API is an interface for querying information from and enacting change in a Slack workspace.

Use it on the fly for ad-hoc queries, or as part of a more complex tapestry of platform features in a Slack app.

## Capabilities

What can you do with the Web API? 

Call 100 different Slack API endpoints [Find out more!](https://api.slack.com/methods)

Examples:

* channelsList (requires channels:read permission)
  return Slack.channelsList()

* chatPostMessage (requires chat.write permission)
  Slack.chatPostMessage{channel="general", text="My _spidey sense_ tells me I'll have to skip lunch today."}

All exposed Slack methods:

apiTest
appsPermissionsInfo
appsPermissionsRequest
appsPermissionsResourcesList
appsPermissionsScopesList
authRevoke
authTest
botsInfo
channelsArchive
channelsCreate
channelsHistory
channelsInfo
channelsInvite
channelsJoin
channelsKick
channelsLeave
channelsList
channelsMark
channelsRename
channelsReplies
channelsSetPurpose
channelsSetTopic
channelsUnarchive
chatDelete
chatGetPermalink
chatMeMessage
chatPostEphemeral
chatPostMessage
chatUnfurl
chatUpdate
conversationsArchive
conversationsClose
conversationsCreate
conversationsHistory
conversationsInfo
conversationsInvite
conversationsJoin
conversationsKick
conversationsLeave
conversationsList
conversationsMembers
conversationsOpen
conversationsRename
conversationsReplies
conversationsSetPurpose
conversationsSetTopic
conversationsUnarchive
dialogOpen
dndEndDnd
dndEndSnooze
dndInfo
dndTeamInfo
emojiList
filesCommentsAdd
filesCommentsDelete
filesCommentsEdit
filesDelete
filesInfo
filesList
filesRevokePublicURL
filesSharedPublicURL
groupsArchive
groupsCreate
groupsHistory
groupsInfo
groupsInvite
groupsKick
groupsLeave
groupsList
groupsMark
groupsOpen
groupsRename
groupsReplies
groupsSetPurpose
groupsSetTopic
groupsUnarchive
imClose
imHistory
imList
imMark
imOpen
imReplies
migrationExchange
mpimClose
mpimHistory
mpimList
mpimMark
mpimOpen
mpimReplies
oauthAccess
oauthToken
pinsAdd
pinsList
pinsRemove
reactionsAdd
reactionsGet
reactionsList
reactionsRemove
remindersAdd
remindersComplete
remindersDelete
remindersInfo
remindersList
rtmConnect
rtmStart
searchAll
searchFiles
searchMessages
starsAdd
starsList
starsRemove
teamAccessLogs
teamBillableInfo
teamInfo
teamIntegrationLogs
teamProfileGet
usergroupsCreate
usergroupsDisable
usergroupsEnable
usergroupsList
usergroupsUpdate
usergroupsUsersList
usergroupsUsersUpdate
usersConversations
usersGetPresence
usersIdentity
usersInfo
usersList
usersLookupByEmail
usersProfileGet
usersProfileSet
usersSetActive
usersSetPresence

## Schema

https://gist.githubusercontent.com/dominicletz/ef3537f1919375ddad744bfe10b5b8e4/raw/cadef08d41f82c599278b32300719e6ad7400c28/slack.yaml

## Contact

https://slack.com/help/contact
