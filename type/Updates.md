# Updates

Sample Description

<pre>
<a href="../constructor/updatesTooLong.md">updatesTooLong</a>#e317af7e = <a href="../type/Updates.md">Updates</a>;
<a href="../constructor/updateShortMessage.md">updateShortMessage</a>#914fbf11 flags:# out:flags.1?<a href="../type/true.md">true</a> mentioned:flags.4?<a href="../type/true.md">true</a> media_unread:flags.5?<a href="../type/true.md">true</a> silent:flags.13?<a href="../type/true.md">true</a> id:<a href="../type/int.md">int</a> user_id:<a href="../type/int.md">int</a> message:<a href="../type/string.md">string</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> date:<a href="../type/int.md">int</a> fwd_from:flags.2?<a href="../type/MessageFwdHeader.md">MessageFwdHeader</a> via_bot_id:flags.11?<a href="../type/int.md">int</a> reply_to_msg_id:flags.3?<a href="../type/int.md">int</a> entities:flags.7?Vector&lt;<a href="../type/MessageEntity.md">MessageEntity</a>&gt; = <a href="../type/Updates.md">Updates</a>;
<a href="../constructor/updateShortChatMessage.md">updateShortChatMessage</a>#16812688 flags:# out:flags.1?<a href="../type/true.md">true</a> mentioned:flags.4?<a href="../type/true.md">true</a> media_unread:flags.5?<a href="../type/true.md">true</a> silent:flags.13?<a href="../type/true.md">true</a> id:<a href="../type/int.md">int</a> from_id:<a href="../type/int.md">int</a> chat_id:<a href="../type/int.md">int</a> message:<a href="../type/string.md">string</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> date:<a href="../type/int.md">int</a> fwd_from:flags.2?<a href="../type/MessageFwdHeader.md">MessageFwdHeader</a> via_bot_id:flags.11?<a href="../type/int.md">int</a> reply_to_msg_id:flags.3?<a href="../type/int.md">int</a> entities:flags.7?Vector&lt;<a href="../type/MessageEntity.md">MessageEntity</a>&gt; = <a href="../type/Updates.md">Updates</a>;
<a href="../constructor/updateShort.md">updateShort</a>#78d4dec1 update:<a href="../type/Update.md">Update</a> date:<a href="../type/int.md">int</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../constructor/updatesCombined.md">updatesCombined</a>#725b04c3 updates:Vector&lt;<a href="../type/Update.md">Update</a>&gt; users:Vector&lt;<a href="../type/User.md">User</a>&gt; chats:Vector&lt;<a href="../type/Chat.md">Chat</a>&gt; date:<a href="../type/int.md">int</a> seq_start:<a href="../type/int.md">int</a> seq:<a href="../type/int.md">int</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../constructor/updates.md">updates</a>#74ae4240 updates:Vector&lt;<a href="../type/Update.md">Update</a>&gt; users:Vector&lt;<a href="../type/User.md">User</a>&gt; chats:Vector&lt;<a href="../type/Chat.md">Chat</a>&gt; date:<a href="../type/int.md">int</a> seq:<a href="../type/int.md">int</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../constructor/updateShortSentMessage.md">updateShortSentMessage</a>#11f1331c flags:# out:flags.1?<a href="../type/true.md">true</a> id:<a href="../type/int.md">int</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> date:<a href="../type/int.md">int</a> media:flags.9?<a href="../type/MessageMedia.md">MessageMedia</a> entities:flags.7?Vector&lt;<a href="../type/MessageEntity.md">MessageEntity</a>&gt; = <a href="../type/Updates.md">Updates</a>;

---functions---
<a href="../method/messages.sendMessage.md">messages.sendMessage</a>#fa88427a flags:# no_webpage:flags.1?<a href="../type/true.md">true</a> silent:flags.5?<a href="../type/true.md">true</a> background:flags.6?<a href="../type/true.md">true</a> clear_draft:flags.7?<a href="../type/true.md">true</a> peer:<a href="../type/InputPeer.md">InputPeer</a> reply_to_msg_id:flags.0?<a href="../type/int.md">int</a> message:<a href="../type/string.md">string</a> random_id:<a href="../type/long.md">long</a> reply_markup:flags.2?<a href="../type/ReplyMarkup.md">ReplyMarkup</a> entities:flags.3?Vector&lt;<a href="../type/MessageEntity.md">MessageEntity</a>&gt; = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.sendMedia.md">messages.sendMedia</a>#c8f16791 flags:# silent:flags.5?<a href="../type/true.md">true</a> background:flags.6?<a href="../type/true.md">true</a> clear_draft:flags.7?<a href="../type/true.md">true</a> peer:<a href="../type/InputPeer.md">InputPeer</a> reply_to_msg_id:flags.0?<a href="../type/int.md">int</a> media:<a href="../type/InputMedia.md">InputMedia</a> random_id:<a href="../type/long.md">long</a> reply_markup:flags.2?<a href="../type/ReplyMarkup.md">ReplyMarkup</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.forwardMessages.md">messages.forwardMessages</a>#708e0195 flags:# silent:flags.5?<a href="../type/true.md">true</a> background:flags.6?<a href="../type/true.md">true</a> with_my_score:flags.8?<a href="../type/true.md">true</a> from_peer:<a href="../type/InputPeer.md">InputPeer</a> id:Vector&lt;<a href="../type/int.md">int</a>&gt; random_id:Vector&lt;<a href="../type/long.md">long</a>&gt; to_peer:<a href="../type/InputPeer.md">InputPeer</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.editChatTitle.md">messages.editChatTitle</a>#dc452855 chat_id:<a href="../type/int.md">int</a> title:<a href="../type/string.md">string</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.editChatPhoto.md">messages.editChatPhoto</a>#ca4c79d8 chat_id:<a href="../type/int.md">int</a> photo:<a href="../type/InputChatPhoto.md">InputChatPhoto</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.addChatUser.md">messages.addChatUser</a>#f9a0aa09 chat_id:<a href="../type/int.md">int</a> user_id:<a href="../type/InputUser.md">InputUser</a> fwd_limit:<a href="../type/int.md">int</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.deleteChatUser.md">messages.deleteChatUser</a>#e0611f16 chat_id:<a href="../type/int.md">int</a> user_id:<a href="../type/InputUser.md">InputUser</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.createChat.md">messages.createChat</a>#9cb126e users:Vector&lt;<a href="../type/InputUser.md">InputUser</a>&gt; title:<a href="../type/string.md">string</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.forwardMessage.md">messages.forwardMessage</a>#33963bf9 peer:<a href="../type/InputPeer.md">InputPeer</a> id:<a href="../type/int.md">int</a> random_id:<a href="../type/long.md">long</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.importChatInvite.md">messages.importChatInvite</a>#6c50051c hash:<a href="../type/string.md">string</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.startBot.md">messages.startBot</a>#e6df7378 bot:<a href="../type/InputUser.md">InputUser</a> peer:<a href="../type/InputPeer.md">InputPeer</a> random_id:<a href="../type/long.md">long</a> start_param:<a href="../type/string.md">string</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.toggleChatAdmins.md">messages.toggleChatAdmins</a>#ec8bd9e1 chat_id:<a href="../type/int.md">int</a> enabled:<a href="../type/Bool.md">Bool</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.migrateChat.md">messages.migrateChat</a>#15a3b8e3 chat_id:<a href="../type/int.md">int</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.sendInlineBotResult.md">messages.sendInlineBotResult</a>#b16e06fe flags:# silent:flags.5?<a href="../type/true.md">true</a> background:flags.6?<a href="../type/true.md">true</a> clear_draft:flags.7?<a href="../type/true.md">true</a> peer:<a href="../type/InputPeer.md">InputPeer</a> reply_to_msg_id:flags.0?<a href="../type/int.md">int</a> random_id:<a href="../type/long.md">long</a> query_id:<a href="../type/long.md">long</a> id:<a href="../type/string.md">string</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.editMessage.md">messages.editMessage</a>#ce91e4ca flags:# no_webpage:flags.1?<a href="../type/true.md">true</a> peer:<a href="../type/InputPeer.md">InputPeer</a> id:<a href="../type/int.md">int</a> message:flags.11?<a href="../type/string.md">string</a> reply_markup:flags.2?<a href="../type/ReplyMarkup.md">ReplyMarkup</a> entities:flags.3?Vector&lt;<a href="../type/MessageEntity.md">MessageEntity</a>&gt; = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.getAllDrafts.md">messages.getAllDrafts</a>#6a3f8d65 = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.setGameScore.md">messages.setGameScore</a>#8ef8ecc0 flags:# edit_message:flags.0?<a href="../type/true.md">true</a> force:flags.1?<a href="../type/true.md">true</a> peer:<a href="../type/InputPeer.md">InputPeer</a> id:<a href="../type/int.md">int</a> user_id:<a href="../type/InputUser.md">InputUser</a> score:<a href="../type/int.md">int</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/messages.sendScreenshotNotification.md">messages.sendScreenshotNotification</a>#c97df020 peer:<a href="../type/InputPeer.md">InputPeer</a> reply_to_msg_id:<a href="../type/int.md">int</a> random_id:<a href="../type/long.md">long</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/help.getAppChangelog.md">help.getAppChangelog</a>#9010ef6f prev_app_version:<a href="../type/string.md">string</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.createChannel.md">channels.createChannel</a>#f4893d7f flags:# broadcast:flags.0?<a href="../type/true.md">true</a> megagroup:flags.1?<a href="../type/true.md">true</a> title:<a href="../type/string.md">string</a> about:<a href="../type/string.md">string</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.editAdmin.md">channels.editAdmin</a>#20b88214 channel:<a href="../type/InputChannel.md">InputChannel</a> user_id:<a href="../type/InputUser.md">InputUser</a> admin_rights:<a href="../type/ChannelAdminRights.md">ChannelAdminRights</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.editTitle.md">channels.editTitle</a>#566decd0 channel:<a href="../type/InputChannel.md">InputChannel</a> title:<a href="../type/string.md">string</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.editPhoto.md">channels.editPhoto</a>#f12e57c9 channel:<a href="../type/InputChannel.md">InputChannel</a> photo:<a href="../type/InputChatPhoto.md">InputChatPhoto</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.joinChannel.md">channels.joinChannel</a>#24b524c5 channel:<a href="../type/InputChannel.md">InputChannel</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.leaveChannel.md">channels.leaveChannel</a>#f836aa95 channel:<a href="../type/InputChannel.md">InputChannel</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.inviteToChannel.md">channels.inviteToChannel</a>#199f3a6c channel:<a href="../type/InputChannel.md">InputChannel</a> users:Vector&lt;<a href="../type/InputUser.md">InputUser</a>&gt; = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.deleteChannel.md">channels.deleteChannel</a>#c0111fe3 channel:<a href="../type/InputChannel.md">InputChannel</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.toggleInvites.md">channels.toggleInvites</a>#49609307 channel:<a href="../type/InputChannel.md">InputChannel</a> enabled:<a href="../type/Bool.md">Bool</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.toggleSignatures.md">channels.toggleSignatures</a>#1f69b606 channel:<a href="../type/InputChannel.md">InputChannel</a> enabled:<a href="../type/Bool.md">Bool</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.updatePinnedMessage.md">channels.updatePinnedMessage</a>#a72ded52 flags:# silent:flags.0?<a href="../type/true.md">true</a> channel:<a href="../type/InputChannel.md">InputChannel</a> id:<a href="../type/int.md">int</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/channels.editBanned.md">channels.editBanned</a>#bfd915cd channel:<a href="../type/InputChannel.md">InputChannel</a> user_id:<a href="../type/InputUser.md">InputUser</a> banned_rights:<a href="../type/ChannelBannedRights.md">ChannelBannedRights</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/phone.discardCall.md">phone.discardCall</a>#78d413a6 peer:<a href="../type/InputPhoneCall.md">InputPhoneCall</a> duration:<a href="../type/int.md">int</a> reason:<a href="../type/PhoneCallDiscardReason.md">PhoneCallDiscardReason</a> connection_id:<a href="../type/long.md">long</a> = <a href="../type/Updates.md">Updates</a>;
<a href="../method/phone.setCallRating.md">phone.setCallRating</a>#1c536a34 peer:<a href="../type/InputPhoneCall.md">InputPhoneCall</a> rating:<a href="../type/int.md">int</a> comment:<a href="../type/string.md">string</a> = <a href="../type/Updates.md">Updates</a>;

</pre>

## Constructors

| Name | Description |
|------|-------------|
| [updatesTooLong](../constructor/updatesTooLong.md) | Sample Description |
| [updateShortMessage](../constructor/updateShortMessage.md) | Sample Description |
| [updateShortChatMessage](../constructor/updateShortChatMessage.md) | Sample Description |
| [updateShort](../constructor/updateShort.md) | Sample Description |
| [updatesCombined](../constructor/updatesCombined.md) | Sample Description |
| [updates](../constructor/updates.md) | Sample Description |
| [updateShortSentMessage](../constructor/updateShortSentMessage.md) | Sample Description |

## Methods

| Name | Description |
|------|-------------|
| [messages.sendMessage](../method/messages.sendMessage.md) | Sends a text message. |
| [messages.sendMedia](../method/messages.sendMedia.md) | Sample Description |
| [messages.forwardMessages](../method/messages.forwardMessages.md) | Forwards messages by their IDs. |
| [messages.editChatTitle](../method/messages.editChatTitle.md) | Sample Description |
| [messages.editChatPhoto](../method/messages.editChatPhoto.md) | Sample Description |
| [messages.addChatUser](../method/messages.addChatUser.md) | Sample Description |
| [messages.deleteChatUser](../method/messages.deleteChatUser.md) | Sample Description |
| [messages.createChat](../method/messages.createChat.md) | Sample Description |
| [messages.forwardMessage](../method/messages.forwardMessage.md) | Forwards single messages. |
| [messages.importChatInvite](../method/messages.importChatInvite.md) | Sample Description |
| [messages.startBot](../method/messages.startBot.md) | Sample Description |
| [messages.toggleChatAdmins](../method/messages.toggleChatAdmins.md) | Sample Description |
| [messages.migrateChat](../method/messages.migrateChat.md) | Sample Description |
| [messages.sendInlineBotResult](../method/messages.sendInlineBotResult.md) | Sample Description |
| [messages.editMessage](../method/messages.editMessage.md) | Sample Description |
| [messages.getAllDrafts](../method/messages.getAllDrafts.md) | Sample Description |
| [messages.setGameScore](../method/messages.setGameScore.md) | Sample Description |
| [messages.sendScreenshotNotification](../method/messages.sendScreenshotNotification.md) | Sample Description |
| [help.getAppChangelog](../method/help.getAppChangelog.md) | Sample Description |
| [channels.createChannel](../method/channels.createChannel.md) | Sample Description |
| [channels.editAdmin](../method/channels.editAdmin.md) | Sample Description |
| [channels.editTitle](../method/channels.editTitle.md) | Sample Description |
| [channels.editPhoto](../method/channels.editPhoto.md) | Sample Description |
| [channels.joinChannel](../method/channels.joinChannel.md) | Sample Description |
| [channels.leaveChannel](../method/channels.leaveChannel.md) | Sample Description |
| [channels.inviteToChannel](../method/channels.inviteToChannel.md) | Sample Description |
| [channels.deleteChannel](../method/channels.deleteChannel.md) | Sample Description |
| [channels.toggleInvites](../method/channels.toggleInvites.md) | Sample Description |
| [channels.toggleSignatures](../method/channels.toggleSignatures.md) | Sample Description |
| [channels.updatePinnedMessage](../method/channels.updatePinnedMessage.md) | Sample Description |
| [channels.editBanned](../method/channels.editBanned.md) | Sample Description |
| [phone.discardCall](../method/phone.discardCall.md) | Sample Description |
| [phone.setCallRating](../method/phone.setCallRating.md) | Sample Description |
