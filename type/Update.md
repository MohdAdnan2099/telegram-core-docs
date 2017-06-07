# Update

Sample Description

<pre>
<a href="../constructor/updateNewMessage">updateNewMessage</a>#1f2b0afd message:<a href="../type/Message.md">Message</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateMessageID">updateMessageID</a>#4e90bfd6 id:<a href="../type/int.md">int</a> random_id:<a href="../type/long.md">long</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateDeleteMessages">updateDeleteMessages</a>#a20db0e5 messages:Vector&lt;<a href="../type/int.md">int</a>&gt; pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateUserTyping">updateUserTyping</a>#5c486927 user_id:<a href="../type/int.md">int</a> action:<a href="../type/SendMessageAction.md">SendMessageAction</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChatUserTyping">updateChatUserTyping</a>#9a65ea1f chat_id:<a href="../type/int.md">int</a> user_id:<a href="../type/int.md">int</a> action:<a href="../type/SendMessageAction.md">SendMessageAction</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChatParticipants">updateChatParticipants</a>#7761198 participants:<a href="../type/ChatParticipants.md">ChatParticipants</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateUserStatus">updateUserStatus</a>#1bfbd823 user_id:<a href="../type/int.md">int</a> status:<a href="../type/UserStatus.md">UserStatus</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateUserName">updateUserName</a>#a7332b73 user_id:<a href="../type/int.md">int</a> first_name:<a href="../type/string.md">string</a> last_name:<a href="../type/string.md">string</a> username:<a href="../type/string.md">string</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateUserPhoto">updateUserPhoto</a>#95313b0c user_id:<a href="../type/int.md">int</a> date:<a href="../type/int.md">int</a> photo:<a href="../type/UserProfilePhoto.md">UserProfilePhoto</a> previous:<a href="../type/Bool.md">Bool</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateContactRegistered">updateContactRegistered</a>#2575bbb9 user_id:<a href="../type/int.md">int</a> date:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateContactLink">updateContactLink</a>#9d2e67c5 user_id:<a href="../type/int.md">int</a> my_link:<a href="../type/ContactLink.md">ContactLink</a> foreign_link:<a href="../type/ContactLink.md">ContactLink</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateNewEncryptedMessage">updateNewEncryptedMessage</a>#12bcbd9a message:<a href="../type/EncryptedMessage.md">EncryptedMessage</a> qts:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateEncryptedChatTyping">updateEncryptedChatTyping</a>#1710f156 chat_id:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateEncryption">updateEncryption</a>#b4a2e88d chat:<a href="../type/EncryptedChat.md">EncryptedChat</a> date:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateEncryptedMessagesRead">updateEncryptedMessagesRead</a>#38fe25b7 chat_id:<a href="../type/int.md">int</a> max_date:<a href="../type/int.md">int</a> date:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChatParticipantAdd">updateChatParticipantAdd</a>#ea4b0e5c chat_id:<a href="../type/int.md">int</a> user_id:<a href="../type/int.md">int</a> inviter_id:<a href="../type/int.md">int</a> date:<a href="../type/int.md">int</a> version:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChatParticipantDelete">updateChatParticipantDelete</a>#6e5f8c22 chat_id:<a href="../type/int.md">int</a> user_id:<a href="../type/int.md">int</a> version:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateDcOptions">updateDcOptions</a>#8e5e9873 dc_options:Vector&lt;<a href="../type/DcOption.md">DcOption</a>&gt; = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateUserBlocked">updateUserBlocked</a>#80ece81a user_id:<a href="../type/int.md">int</a> blocked:<a href="../type/Bool.md">Bool</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateNotifySettings">updateNotifySettings</a>#bec268ef peer:<a href="../type/NotifyPeer.md">NotifyPeer</a> notify_settings:<a href="../type/PeerNotifySettings.md">PeerNotifySettings</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateServiceNotification">updateServiceNotification</a>#ebe46819 flags:<a href="../type/#.md">#</a> popup:<a href="../type/flags.0?true.md">flags.0?true</a> inbox_date:<a href="../type/flags.1?int.md">flags.1?int</a> type:<a href="../type/string.md">string</a> message:<a href="../type/string.md">string</a> media:<a href="../type/MessageMedia.md">MessageMedia</a> entities:Vector&lt;<a href="../type/MessageEntity.md">MessageEntity</a>&gt; = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updatePrivacy">updatePrivacy</a>#ee3b272a key:<a href="../type/PrivacyKey.md">PrivacyKey</a> rules:Vector&lt;<a href="../type/PrivacyRule.md">PrivacyRule</a>&gt; = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateUserPhone">updateUserPhone</a>#12b9417b user_id:<a href="../type/int.md">int</a> phone:<a href="../type/string.md">string</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateReadHistoryInbox">updateReadHistoryInbox</a>#9961fd5c peer:<a href="../type/Peer.md">Peer</a> max_id:<a href="../type/int.md">int</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateReadHistoryOutbox">updateReadHistoryOutbox</a>#2f2f21bf peer:<a href="../type/Peer.md">Peer</a> max_id:<a href="../type/int.md">int</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateWebPage">updateWebPage</a>#7f891213 webpage:<a href="../type/WebPage.md">WebPage</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateReadMessagesContents">updateReadMessagesContents</a>#68c13933 messages:Vector&lt;<a href="../type/int.md">int</a>&gt; pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChannelTooLong">updateChannelTooLong</a>#eb0467fb flags:<a href="../type/#.md">#</a> channel_id:<a href="../type/int.md">int</a> pts:<a href="../type/flags.0?int.md">flags.0?int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChannel">updateChannel</a>#b6d45656 channel_id:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateNewChannelMessage">updateNewChannelMessage</a>#62ba04d9 message:<a href="../type/Message.md">Message</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateReadChannelInbox">updateReadChannelInbox</a>#4214f37f channel_id:<a href="../type/int.md">int</a> max_id:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateDeleteChannelMessages">updateDeleteChannelMessages</a>#c37521c9 channel_id:<a href="../type/int.md">int</a> messages:Vector&lt;<a href="../type/int.md">int</a>&gt; pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChannelMessageViews">updateChannelMessageViews</a>#98a12b4b channel_id:<a href="../type/int.md">int</a> id:<a href="../type/int.md">int</a> views:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChatAdmins">updateChatAdmins</a>#6e947941 chat_id:<a href="../type/int.md">int</a> enabled:<a href="../type/Bool.md">Bool</a> version:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChatParticipantAdmin">updateChatParticipantAdmin</a>#b6901959 chat_id:<a href="../type/int.md">int</a> user_id:<a href="../type/int.md">int</a> is_admin:<a href="../type/Bool.md">Bool</a> version:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateNewStickerSet">updateNewStickerSet</a>#688a30aa stickerset:<a href="../type/messages.StickerSet.md">messages.StickerSet</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateStickerSetsOrder">updateStickerSetsOrder</a>#bb2d201 flags:<a href="../type/#.md">#</a> masks:<a href="../type/flags.0?true.md">flags.0?true</a> order:Vector&lt;<a href="../type/long.md">long</a>&gt; = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateStickerSets">updateStickerSets</a>#43ae3dec = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateSavedGifs">updateSavedGifs</a>#9375341e = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateBotInlineQuery">updateBotInlineQuery</a>#54826690 flags:<a href="../type/#.md">#</a> query_id:<a href="../type/long.md">long</a> user_id:<a href="../type/int.md">int</a> query:<a href="../type/string.md">string</a> geo:<a href="../type/flags.0?GeoPoint.md">flags.0?GeoPoint</a> offset:<a href="../type/string.md">string</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateBotInlineSend">updateBotInlineSend</a>#e48f964 flags:<a href="../type/#.md">#</a> user_id:<a href="../type/int.md">int</a> query:<a href="../type/string.md">string</a> geo:<a href="../type/flags.0?GeoPoint.md">flags.0?GeoPoint</a> id:<a href="../type/string.md">string</a> msg_id:<a href="../type/flags.1?InputBotInlineMessageID.md">flags.1?InputBotInlineMessageID</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateEditChannelMessage">updateEditChannelMessage</a>#1b3f4df7 message:<a href="../type/Message.md">Message</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChannelPinnedMessage">updateChannelPinnedMessage</a>#98592475 channel_id:<a href="../type/int.md">int</a> id:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateBotCallbackQuery">updateBotCallbackQuery</a>#e73547e1 flags:<a href="../type/#.md">#</a> query_id:<a href="../type/long.md">long</a> user_id:<a href="../type/int.md">int</a> peer:<a href="../type/Peer.md">Peer</a> msg_id:<a href="../type/int.md">int</a> chat_instance:<a href="../type/long.md">long</a> data:<a href="../type/flags.0?bytes.md">flags.0?bytes</a> game_short_name:<a href="../type/flags.1?string.md">flags.1?string</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateEditMessage">updateEditMessage</a>#e40370a3 message:<a href="../type/Message.md">Message</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateInlineBotCallbackQuery">updateInlineBotCallbackQuery</a>#f9d27a5a flags:<a href="../type/#.md">#</a> query_id:<a href="../type/long.md">long</a> user_id:<a href="../type/int.md">int</a> msg_id:<a href="../type/InputBotInlineMessageID.md">InputBotInlineMessageID</a> chat_instance:<a href="../type/long.md">long</a> data:<a href="../type/flags.0?bytes.md">flags.0?bytes</a> game_short_name:<a href="../type/flags.1?string.md">flags.1?string</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateReadChannelOutbox">updateReadChannelOutbox</a>#25d6c9c7 channel_id:<a href="../type/int.md">int</a> max_id:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateDraftMessage">updateDraftMessage</a>#ee2bb969 peer:<a href="../type/Peer.md">Peer</a> draft:<a href="../type/DraftMessage.md">DraftMessage</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateReadFeaturedStickers">updateReadFeaturedStickers</a>#571d2742 = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateRecentStickers">updateRecentStickers</a>#9a422c20 = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateConfig">updateConfig</a>#a229dd06 = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updatePtsChanged">updatePtsChanged</a>#3354678f = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateChannelWebPage">updateChannelWebPage</a>#40771900 channel_id:<a href="../type/int.md">int</a> webpage:<a href="../type/WebPage.md">WebPage</a> pts:<a href="../type/int.md">int</a> pts_count:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateDialogPinned">updateDialogPinned</a>#d711a2cc flags:<a href="../type/#.md">#</a> pinned:<a href="../type/flags.0?true.md">flags.0?true</a> peer:<a href="../type/Peer.md">Peer</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updatePinnedDialogs">updatePinnedDialogs</a>#d8caf68d flags:<a href="../type/#.md">#</a> order:Vector&lt;<a href="../type/flags.0?Vector.md">flags.0?Vector</a>&gt; = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateBotWebhookJSON">updateBotWebhookJSON</a>#8317c0c3 data:<a href="../type/DataJSON.md">DataJSON</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateBotWebhookJSONQuery">updateBotWebhookJSONQuery</a>#9b9240a6 query_id:<a href="../type/long.md">long</a> data:<a href="../type/DataJSON.md">DataJSON</a> timeout:<a href="../type/int.md">int</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateBotShippingQuery">updateBotShippingQuery</a>#e0cdc940 query_id:<a href="../type/long.md">long</a> user_id:<a href="../type/int.md">int</a> payload:<a href="../type/bytes.md">bytes</a> shipping_address:<a href="../type/PostAddress.md">PostAddress</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updateBotPrecheckoutQuery">updateBotPrecheckoutQuery</a>#5d2f3aa9 flags:<a href="../type/#.md">#</a> query_id:<a href="../type/long.md">long</a> user_id:<a href="../type/int.md">int</a> payload:<a href="../type/bytes.md">bytes</a> info:<a href="../type/flags.0?PaymentRequestedInfo.md">flags.0?PaymentRequestedInfo</a> shipping_option_id:<a href="../type/flags.1?string.md">flags.1?string</a> currency:<a href="../type/string.md">string</a> total_amount:<a href="../type/long.md">long</a> = <a href="../type/Update.md">Update</a>;
<a href="../constructor/updatePhoneCall">updatePhoneCall</a>#ab0f6b1e phone_call:<a href="../type/PhoneCall.md">PhoneCall</a> = <a href="../type/Update.md">Update</a>;

</pre>

## Constructors

| Name | Description |
|------|-------------|
| [updateNewMessage](../constructor/updateNewMessage.md) | Sample Description |
| [updateMessageID](../constructor/updateMessageID.md) | Sample Description |
| [updateDeleteMessages](../constructor/updateDeleteMessages.md) | Sample Description |
| [updateUserTyping](../constructor/updateUserTyping.md) | Sample Description |
| [updateChatUserTyping](../constructor/updateChatUserTyping.md) | Sample Description |
| [updateChatParticipants](../constructor/updateChatParticipants.md) | Sample Description |
| [updateUserStatus](../constructor/updateUserStatus.md) | Sample Description |
| [updateUserName](../constructor/updateUserName.md) | Sample Description |
| [updateUserPhoto](../constructor/updateUserPhoto.md) | Sample Description |
| [updateContactRegistered](../constructor/updateContactRegistered.md) | Sample Description |
| [updateContactLink](../constructor/updateContactLink.md) | Sample Description |
| [updateNewEncryptedMessage](../constructor/updateNewEncryptedMessage.md) | Sample Description |
| [updateEncryptedChatTyping](../constructor/updateEncryptedChatTyping.md) | Sample Description |
| [updateEncryption](../constructor/updateEncryption.md) | Sample Description |
| [updateEncryptedMessagesRead](../constructor/updateEncryptedMessagesRead.md) | Sample Description |
| [updateChatParticipantAdd](../constructor/updateChatParticipantAdd.md) | Sample Description |
| [updateChatParticipantDelete](../constructor/updateChatParticipantDelete.md) | Sample Description |
| [updateDcOptions](../constructor/updateDcOptions.md) | Sample Description |
| [updateUserBlocked](../constructor/updateUserBlocked.md) | Sample Description |
| [updateNotifySettings](../constructor/updateNotifySettings.md) | Sample Description |
| [updateServiceNotification](../constructor/updateServiceNotification.md) | Sample Description |
| [updatePrivacy](../constructor/updatePrivacy.md) | Sample Description |
| [updateUserPhone](../constructor/updateUserPhone.md) | Sample Description |
| [updateReadHistoryInbox](../constructor/updateReadHistoryInbox.md) | Sample Description |
| [updateReadHistoryOutbox](../constructor/updateReadHistoryOutbox.md) | Sample Description |
| [updateWebPage](../constructor/updateWebPage.md) | Sample Description |
| [updateReadMessagesContents](../constructor/updateReadMessagesContents.md) | Sample Description |
| [updateChannelTooLong](../constructor/updateChannelTooLong.md) | Sample Description |
| [updateChannel](../constructor/updateChannel.md) | Sample Description |
| [updateNewChannelMessage](../constructor/updateNewChannelMessage.md) | Sample Description |
| [updateReadChannelInbox](../constructor/updateReadChannelInbox.md) | Sample Description |
| [updateDeleteChannelMessages](../constructor/updateDeleteChannelMessages.md) | Sample Description |
| [updateChannelMessageViews](../constructor/updateChannelMessageViews.md) | Sample Description |
| [updateChatAdmins](../constructor/updateChatAdmins.md) | Sample Description |
| [updateChatParticipantAdmin](../constructor/updateChatParticipantAdmin.md) | Sample Description |
| [updateNewStickerSet](../constructor/updateNewStickerSet.md) | Sample Description |
| [updateStickerSetsOrder](../constructor/updateStickerSetsOrder.md) | Sample Description |
| [updateStickerSets](../constructor/updateStickerSets.md) | Sample Description |
| [updateSavedGifs](../constructor/updateSavedGifs.md) | Sample Description |
| [updateBotInlineQuery](../constructor/updateBotInlineQuery.md) | Sample Description |
| [updateBotInlineSend](../constructor/updateBotInlineSend.md) | Sample Description |
| [updateEditChannelMessage](../constructor/updateEditChannelMessage.md) | Sample Description |
| [updateChannelPinnedMessage](../constructor/updateChannelPinnedMessage.md) | Sample Description |
| [updateBotCallbackQuery](../constructor/updateBotCallbackQuery.md) | Sample Description |
| [updateEditMessage](../constructor/updateEditMessage.md) | Sample Description |
| [updateInlineBotCallbackQuery](../constructor/updateInlineBotCallbackQuery.md) | Sample Description |
| [updateReadChannelOutbox](../constructor/updateReadChannelOutbox.md) | Sample Description |
| [updateDraftMessage](../constructor/updateDraftMessage.md) | Sample Description |
| [updateReadFeaturedStickers](../constructor/updateReadFeaturedStickers.md) | Sample Description |
| [updateRecentStickers](../constructor/updateRecentStickers.md) | Sample Description |
| [updateConfig](../constructor/updateConfig.md) | Sample Description |
| [updatePtsChanged](../constructor/updatePtsChanged.md) | Sample Description |
| [updateChannelWebPage](../constructor/updateChannelWebPage.md) | Sample Description |
| [updateDialogPinned](../constructor/updateDialogPinned.md) | Sample Description |
| [updatePinnedDialogs](../constructor/updatePinnedDialogs.md) | Sample Description |
| [updateBotWebhookJSON](../constructor/updateBotWebhookJSON.md) | Sample Description |
| [updateBotWebhookJSONQuery](../constructor/updateBotWebhookJSONQuery.md) | Sample Description |
| [updateBotShippingQuery](../constructor/updateBotShippingQuery.md) | Sample Description |
| [updateBotPrecheckoutQuery](../constructor/updateBotPrecheckoutQuery.md) | Sample Description |
| [updatePhoneCall](../constructor/updatePhoneCall.md) | Sample Description |
