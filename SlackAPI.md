# Slack API

## [chat.postMessage method | Slack](https://api.slack.com/methods/chat.postMessage#formatting)

### text
デフォルトだとチャンネル名はリンクにならない。  
`parse: 'full'` にするか text 内で `<#ChannelId|ChannelName>` のように書く。
