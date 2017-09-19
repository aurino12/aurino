//META{"name":"Witcher3","description":"The Witcher 3 Dark Theme","author":"Jadeonking","version":"3.5.9.1"}*//{}
/* **DISCLAIMER** Switches and Small User List Designed by Beard Design */

/* if you wish to hide blocked messages change display: to display:none */

.message-group-blocked {
display:
}

/*
                     _                _                                   _
  __ _ _ __  _ __   | |__   __ _  ___| | ____ _ _ __ ___  _   _ _ __   __| |
 / _` | '_ \| '_ \  | '_ \ / _` |/ __| |/ / _` | '__/ _ \| | | | '_ \ / _` |
| (_| | |_) | |_) | | |_) | (_| | (__|   < (_| | | | (_) | |_| | | | | (_| |
 \__,_| .__/| .__/  |_.__/ \__,_|\___|_|\_\__, |_|  \___/ \__,_|_| |_|\__,_|
      |_|   |_|                           |___/
*/

/* Main background and settings background */

.app {
background:url(http://i67.tinypic.com/1enx2s.jpg)!important;
background-size:cover!important;
}

.callout-backdrop {
background:url(https://i.imgur.com/mQDJWFb.png)!important;
background-size:cover!important;
opacity:.95!important
}

/* Embed Left Borders and Background */

/* Background */
.theme-dark .message-group .embed {
background-color:rgba(25,25,25,.75);
border:none;
border-radius:0
}

/* Commits */
.theme-dark .message-group .embed-wrapper .embed-color-pill[style*='background-color: rgb(114, 137, 218);'] {
background-color:green!important
}

/* Issues */
.theme-dark .message-group .embed-wrapper .embed-color-pill[style*='background-color: rgb(235, 100, 32);'] {
background-color:yellow!important
}

/* Pull Requests Opened */
.theme-dark .message-group .embed-wrapper .embed-color-pill[style*='background-color: rgb(0, 152, 0);'] {
background-color:yellow!important
}

/* Issues, Pull Requests Closed | Website links etc. */
.theme-dark .message-group .embed-wrapper .embed-color-pill {
background-color:#900;
border-radius:0
}


/* If you want to remove titles, descriptions, etc. change display: to display:none and border: to border:none */

.embed .embed-provider, .embed .embed-author, .embed .embed-title, .embed .embed-description, .embed.embed-link .embed-thumbnail {
display:;
border:
}

/*
                           _                           _
  ___ ___  _ __ ___    ___| | ___ _ __ ___   ___ _ __ | |_ ___
 / __/ _ \| '__/ _ \  / _ \ |/ _ \ '_ ` _ \ / _ \ '_ \| __/ __|
| (_| (_) | | |  __/ |  __/ |  __/ | | | | |  __/ | | | |_\__ \
 \___\___/|_|  \___|  \___|_|\___|_| |_| |_|\___|_| |_|\__|___/

*/

span {
backface-visibility:hidden!important
}

textarea {
background:transparent!important
}

.user-popout .body .roles .member-roles {
overflow-y:scroll;
max-height:90px
}

.user-popout .body .roles .member-roles::-webkit-scrollbar {
background:none
}

.user-popout .body .roles .member-roles::-webkit-scrollbar-thumb {
background:#383838;
border:2px solid transparent;
background-clip:content-box
}

.scroller-wrap .scroller::-webkit-scrollbar-thumb {
border:1px solid transparent!important;
background-color:rgba(35,35,35,.75)!important;
border-radius:0px;
background-clip:content-box!important
}

.scroller-wrap .scroller::-webkit-scrollbar-track-piece {
border:none!important;
background:none!important;
}

.tab-bar.SIDE::-webkit-scrollbar {
background:transparent!important
}

.tab-bar.SIDE::-webkit-scrollbar-thumb {
background:#383838!important;
border:2px solid #232323!important
}

div.scroller.settings-wrapper.settings-panel::-webkit-scrollbar-thumb {
background:#383838!important;
border:1px solid #191919!important
}

.user-settings-modal-games.scroller::-webkit-scrollbar-thumb {
background:#383838!important;
border:1px solid #191919!important
}

.user-settings-modal-connections .user-settings-modal-connections-list::-webkit-scrollbar-thumb {
background:#383838!important;
border:1px solid #191919!important
}

.settings .settings-inner .settings-panel::-webkit-scrollbar-thumb {
background:#383838!important;
border:1px solid #191919!important
}

.settings .settings-inner .settings-panel-with-header::-webkit-scrollbar-thumb {
background:#383838!important;
border:1px solid #383838!important
}

#settings-roles .scroller-wrap .scroller::-webkit-scrollbar-thumb {
background:#383838!important;
border:1px solid #383838!important
}

.Select-menu::-webkit-scrollbar {
background:transparent!important
}

.Select-menu::-webkit-scrollbar-thumb {
background:#383838!important;
border:2px solid transparent!important;
background-clip:content-box!important
}

.Select-menu::-webkit-scrollbar-corner {
background:none
}

.change-log.markdown-modal .scroller-wrap .scroller::-webkit-scrollbar-thumb {
background:#383838!important;
border:1px solid #191919!important
}

div.scroller.settings-wrapper.settings-panel {
overflow-y:scroll
}

/*
 _     _     _
| |__ (_) __| | ___
| '_ \| |/ _` |/ _ \
| | | | | (_| |  __/
|_| |_|_|\__,_|\___|

*/
.links,.help-container {
display:none
}

/*
                 _         _                _                                   _
 _ __ ___   __ _(_)_ __   | |__   __ _  ___| | ____ _ _ __ ___  _   _ _ __   __| |___
| '_ ` _ \ / _` | | '_ \  | '_ \ / _` |/ __| |/ / _` | '__/ _ \| | | | '_ \ / _` / __|
| | | | | | (_| | | | | | | |_) | (_| | (__|   < (_| | | | (_) | |_| | | | | (_| \__ \
|_| |_| |_|\__,_|_|_| |_| |_.__/ \__,_|\___|_|\_\__, |_|  \___/ \__,_|_| |_|\__,_|___/
                                                |___/
*/
.links,.chat,.typing,.content,.guild-channels,.private-channels,.guild-header header,.divider-red span,.messages-wrapper,#rtc-connection {
background:transparent!important
}

/* Server list area */
.guilds-wrapper {
background:rgba(0,0,0,0.65)!important;
width:68px;
min-width:68px!important
}

/* Channels list area */
.channels-wrap {
box-shadow:inset 0 0 0 -6px rgba(0,0,0,1);
background:rgba(0,0,0,0.55)
}

/* Chat area */
.content .flex-spacer {
box-shadow:inset 10px 10px 5px -6px rgba(0,0,0,1);
background:transparent
}

/* User list area */
.channel-members {
box-shadow:inset 0 10px 5px -6px rgba(0,0,0,1);
background:transparent!important
}

/*
                                _ _     _                   _   _
 ___  ___ _ ____   _____ _ __  | (_)___| |_   ___  ___  ___| |_(_) ___  _ __
/ __|/ _ \ '__\ \ / / _ \ '__| | | / __| __| / __|/ _ \/ __| __| |/ _ \| '_ \
\__ \  __/ |   \ V /  __/ |    | | \__ \ |_  \__ \  __/ (__| |_| | (_) | | | |
|___/\___|_|    \_/ \___|_|    |_|_|___/\__| |___/\___|\___|\__|_|\___/|_| |_|

*/
.create-guild-container {
background-color:#191919!important
}

.create-guild-container .action {
background:rgba(25,25,25,0);
box-shadow:0 0 1px rgba(0,0,0,.82),0 1px 4px rgba(0,0,0,.1)!important;
border-radius:0
}

.create-guild-container .create-or-join .actions .or {
-webkit-filter:opacity(0.0) invert();
color:#000
}

.create-guild-container .action.create .action-header {
color:#e5e5e5
}

.create-guild-container .action.create .btn-primary {
background-color:#343434!important
}

.create-guild-container .action.create:hover .btn-primary {
background-color:#900!important
}

.guilds-wrapper {
box-shadow:inset -10px 0 5px -6px rgba(0,0,0,1)
}

.guilds-wrapper .guilds-error {
background-color:#191919;
border-radius:0;
margin-top:-10px;
border:0;
height:45px!important;
width:50px;
right:-2px;
position:relative
}

.guilds-wrapper .guilds-error:hover {
background-color:#900
}

.guild-header ul {
background:#191919!important;
opacity:1!important;
transition:transform .5s cubic-bezier(0.18,0.89,0.32,1.28)!important;
padding-top:100px;
top:-56px
}

.guild-header-open ul {
opacity:1!important
}

.guilds-add {
opacity:0.5
}

.guilds-wrapper {
border-right:none
}

.guild-header header span {
margin-left:-10px
}

.guild-header header {
box-shadow:none!important;
color:#e5e5e5
}

.guild-channels header h2 {
padding:0 18px
}

.guild-channels .channel a {
opacity:1;
color:#b2b2b2
}

.guild-channels .channel-text a {
padding:8px 6px 10px 18px
}

.guild-channels .channel-text .channel-name:before {
content:"#";
color:inherit!important
}
.guild-channels .toggle-muted-text-channels a {
opacity:1;
color:#b2b2b2
}

.guild-channels .toggle-muted-text-channels a:hover {
color:#e5e5e5
}

.guild-channels .channel-text.channel-muted:not(.selected) span {
opacity:1;
color:#7f7f7f
}

.guild-channels .channel-text.channel-muted:not(.selected):hover span {
color:#b2b2b2
}

.guild-channels header h2,.guild-channels ul .channel a {
color:#ccc;
opacity:.8
}

.guilds {
padding:18px 20px 85px
}

div.guild.active {
opacity:1!important
}

.guilds-wrapper .guilds {
padding-left:0px
}

.guilds-wrapper .guilds-add {
font-size:30px;
background:transparent;
border-radius:0px;
width:40px!important;
height:40px!important;
margin-left:2px;
margin-top:3px!important
}

.guilds .guild-inner {
background:transparent!important
}

.guilds .active .guild-inner {
background:transparent!important
}

.guilds .guild-inner:hover {
background:transparent!important
}

.guilds-wrapper .guilds .guild .guild-inner {
border-radius:0px!important;
line-height:40px;
width:50px;
height:50px;
margin-left:-5px;
padding-left:7px;
padding-top:10px;
border:none!important;
position:relative;
top:-20px!important
}

.guilds-wrapper .guilds .guild .guild-inner a {
width:50px!important;
height:50px!important;
background-size:50px 50px!important;
border-radius:0px!important
}

.guilds-wrapper .guilds .friends-icon {
width:40px!important;
height:40px!important;
background-size:30px 25px;
position:relative;
margin-left:5px;
bottom:-10px
}

.guilds-wrapper .guilds .guild+.guild {
width:50px!important;
height:42px!important;
background-size:50px 50px!importan
}

.guilds-wrapper .guilds .guild {
height:42px!important
}

.guilds-wrapper .guilds .guild .badge {
bottom:34px!important;
right:14px
}

.guilds-wrapper .guilds .guild:not(.selected) {
opacity:.5
}

.guilds-wrapper .guilds .guild:not(.selected):hover {
opacity:.75
}

.guilds-wrapper .guilds .guild.audio .guild-inner:after {
background-size:16px;
background-color:transparent;
top:40px!important;
right:-3px
}

.guilds-wrapper .guild-separator:after {
background:#e5e5e5;
display:none
}

.guilds .guild-inner:before {
left:-24px
}

.guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before {
background:#e5e5e5!important;
border-radius:0!important;
width:3px!important;
left:8px!important
}

.guilds-wrapper .guilds .guild.selected:before {
top:30px;
display:none
}

.guilds-wrapper .guilds .guild.unread:before {
left:52px!important;
height:50px;
border-radius:0;
background:#900;
top:-4px;
width:12%
}

.guilds li.active .guild-inner:before {
background:#e5e5e5!important
}

.guilds-wrapper .guilds .friends-online {
color:#e5e5e5;
font-size:9.5px;
margin-left:0px;
line-height:20px;
width:55px;
height:20px;
border-radius:8px;
overflow:hidden;
background:transparent;
}

.guilds-error {
width:40px;
height:40px;
line-height:36px
}

.guild-channels header {
opacity:1;
color:#ccc
}

.guild-channels header:hover {
color:#e5e5e5
}

.guild-channels header h2,.private-channels header {
opacity:1
}

.private-channels .search-bar {
background:rgba(0,0,0,0)!important;
border-radius:0
}

.search-bar input::-webkit-input-placeholder {
color:#e5e5e5
}

.private-channels .search-bar input {
background:#232323!important;
color:#e5e5e5
}

.guild-channels .channel:not(.selected):hover {
background:none!important;
width:90%;
border-radius:8px;
padding-right:10px;
}

.private-channels .channel:not(.selected):hover {
background:none!important;
width:90%;
border-radius:8px;
padding-right:10px
}

.guild-channels .channel-voice:not(.selected) {
width:82%!important;
border-radius:8px!important;
padding-right:18px!important
}

.guild-channels .channel-text:not(.selected):hover {
width:100%!important;
padding-right:10px!important
}

.guild-channels .channel:not(.selected):before,.guild-channels .channel.selected:before,.guild-channels .channel.selected:hover:before,.private-channels .channel:not(.selected):before,.private-channels .channel.selected:before,.private-channels .channel.selected:hover:before,.private-channels .search-result.selected:before,.private-channels .search-result:hover:before {
border-left:none!important;
}

.private-channels .search-result.selected,.private-channels .search-result:hover {
width:80%!important
}

.private-channels .channel .icon-friends {
background-color:transparent!important;
border-radius:0
}

.private-channels .channel.selected .icon-friends {
background-color:transparent!important
}

.guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before {
left:-8px
}

.theme-dark #friends .friends-header {
background-color:rgba(0,0,0,.55)!important;
border-bottom:0!important;
box-shadow:inset 10px 0 5px -6px
}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.selected {
color:#e5e5e5;
background-color:#191919
}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item:not(.selected):hover {
background-color:#232323
}

.theme-dark #friends .friends-table .friends-table-header .friends-column {
color:#e5e5e5
}

.theme-dark #friends .friends-table .friends-row .friends-column {
color:#ccc
}

.theme-dark #friends .friends-table .friends-row+.friends-row {
border-top:none
}

.private-channels .channel.selected .channel-name {
color:#e5e5e5;
opacity:1
}

.private-channels .channel .channel-name {
color:#b2b2b2;
opacity:1
}

.private-channels .channel .avatar-small {
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
border-radius:0
}

.guild-channels .channel-voice-states li {
color:#7f7f7f
}

.guild-channels .channel-voice-states li:hover {
color:#e5e5e5
}

.guild-channels .channel-voice.audio li {
color:#7f7f7f
}

.guild-channels .channel-voice-states li.speaking {
color:#E5AC39!important
}

.guild-channels .channel-voice.audio li:hover {
color:#e5e5e5
}

.guild-channels .channel-voice-states li .avatar-small {
border-radius:0px;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
border:none
}

.guild-channels .channel-voice-states li.speaking .avatar-small {
border:none;
color:#900
}

.guild-channels .channel-user-limit {
position:relative;
left:17px;
background:rgba(35,35,35,1);
display:block!important
}

.guild-channels .channel .channel-name {
padding-right:1px
}

.private-channels .channel:hover .channel-name {
color:#e5e5e5!important
}

/*If you want the channel hover buttons back change none to inline block */

.guild-channels .icon-instant-invite {
display:none!important
}

.guild-channels .icon-settings {
display:none!important
}

/*----------------------------------------------------------------------*/

.guild-channels .channel-voice.drop-target {
background:rgba(35,35,35,.50);
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
padding:8px 6px 10px 20px;
width:82!important
}

.guild-channels .channel.sorting:after {
border:2px solid #900
}

.new-messages-indicator.new-messages-indicator-mention {
background:rgba(35,35,35,.9)
}

.new-messages-indicator.new-messages-indicator-mention:hover {
background:#900
}

/*
      _                            _                     _   _
  ___| |__   __ _ _ __  _ __   ___| |___   ___  ___  ___| |_(_) ___  _ __
 / __| '_ \ / _` | '_ \| '_ \ / _ \ / __| / __|/ _ \/ __| __| |/ _ \| '_ \
| (__| | | | (_| | | | | | | |  __/ \__ \ \__ \  __/ (__| |_| | (_) | | | |
 \___|_| |_|\__,_|_| |_|_| |_|\___|_|___/ |___/\___|\___|\__|_|\___/|_| |_|

*/
.btn-hamburger {
margin-right:-18px
}

.btn-hamburger span {
background:#fff
}

.account {
z-index:9;
border-top:6px solid!important;
width:240px;
margin-left:0;
padding:0!important;
background:rgba(25,25,25,1);
height:100px;
box-sizing:border-box;
color:#900;
position:relative
}

.account .status {
border:0 solid rgba(0,0,0,1)
}

.account .btn {
background:transparent;
box-shadow:none!important
}

.account .btn:active {
background:transparent
}

.account .btn-settings:after {
opacity:.3
}

.account .btn-deafen,.account .btn-mute {
border-right:0 solid #000
}

#rtc-connection {
z-index:9;
border-top:none!important;
padding:5px 10px!important
}

#rtc-connection .btn {
background:transparent;
box-shadow:none!important;
border:none
}

#rtc-connection .btn:active {
background:transparent
}

.account .btn-deafen,.account .btn-settings {
box-shadow:none!important
}

.account .btn-group {
border:none;
position:absolute;
right:72px;
top:60px
}

#rtc-connection .btn-group {
border:none
}

#rtc-connection .rtc-connection-channel {
opacity:1;
color:#ccc;
text-decoration:none!important
}

#rtc-connection .rtc-connection-channel:hover {
color:#e5e5e5
}

.account .avatar-small {
opacity:1;
right:-105px;
top:-25px;
border-radius:0;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000
}

.account .account-details .username {
display:none
}

.account .account-details .discriminator {
font-size:14px;
color:#e5e5e5;
text-indent:57px;
font-style:italic;
padding-top:10px;
opacity:1
}

.account .status {
border:2px solid #191919
}

/*
      _           _                   _   _
  ___| |__   __ _| |_   ___  ___  ___| |_(_) ___  _ __
 / __| '_ \ / _` | __| / __|/ _ \/ __| __| |/ _ \| '_ \
| (__| | | | (_| | |_  \__ \  __/ (__| |_| | (_) | | | |
 \___|_| |_|\__,_|\__| |___/\___|\___|\__|_|\___/|_| |_|

*/
.spinner-wandering-cubes .spinner-item {
background-color:#900;
width:15px;
height:15px;
border-radius:25px
}

.chat .has-more button {
color:#e5e5e5!important;
background:rgba(25,25,25,.75)!important;
border:hidden!important;
box-shadow:none!important
}

.highlight {
color:#e5e5e5
}

.mention {
background:rgba(35,35,35,.75)!important;
color:#ccc!important
}

.mentioned .mention {
background:rgba(35,35,35,.75)!important
}

.emoji-picker {
background:#191919!important;
border:none
}

.emoji-picker .scroller::-webkit-scrollbar-track {
background:none!important
}

.emote-menu-inner {
background:#191919
}

#bda-qem-favourite-container .scroller-wrap,#bda-qem-twitch-container .scroller-wrap {
background:#191919;
margin-top:-.6px
}

#bda-qem {
background:#232323
}

#bda-qem button.active {
background-color:#191919;
color:#e5e5e5;
margin-right:-.8px
}

#bda-qem button {
color:#ccc;
box-shadow:none;
border-left:0;
border-right:0;
margin-bottom:-.6px;
margin-right:-.8px
}

#bda-qem button:hover {
background-color:#191919;
color:#fff;
margin-right:-.8px
}

.emoji-picker .search-bar .search-bar-inner {
border:none!important;
background:none
}

.emoji-picker .search-bar input {
color:#e5e5e5;
background-color:#232323;
border:none
}

.emoji-picker .search-bar input::-webkit-input-placeholder {
color:#e5e5e5
}

.emoji-picker .search-bar {
background:#191919;
border:none
}

.emoji-picker .search-bar-clear {
background:#191919;
border:none
}

.emoji-picker .sticky-header {
background:#191919!important
}

.emoji-picker .categories .item.selected {
border-bottom-color:#e5e5e5;
background-color:#232323
}

.emoji-picker .category {
background:#191919;
color:#e5e5e5
}

.emoji-picker .header {
border-bottom:6px solid #900
}

/* Emoji Reactions */

.theme-dark .reaction.reaction-me {
background:rgba(25,25,25,.35);
border-bottom:2px solid #900!important
}

.theme-dark .reaction.reaction-me .reaction-count {
color:#e5e5e5
}

.theme-dark .reaction {
background:rgba(30,30,30,.35);
border-radius:0;
border-bottom:2px solid #7f7f7f
}

.theme-dark .reaction .reaction-count {
color:#b2b2b2
}

.message-reactions-modal .message-reactions-list-inner .reaction.selected {
background-color:#191919;
border-radius:0
}

.message-reactions-modal .message-reactions-list-inner .reaction:not(.selected):hover {
background-color:#383838!important;
border-radius:0
}

.message-reactions-modal .message-reactions-list .scroller-wrap {
background-color:#232323
}

.message-reactions-modal .message-reactions-list-inner {
background-color:#232323
}

div.message-reactions-list {
background-color:#191919
}

.message-reactions-modal .message-reactions-reactors {
background-color:#191919;
border-left:6px solid #900;
}

.message-reactions-modal .message-reactions-reactors .reactor {
box-shadow:none
}

.message-reactions-modal .message-reactions-reactors .reactor .name {
color:#e5e5e5
}

.message-reactions-modal .message-reactions-list-inner .reaction .count {
color:#ccc
}

.message-reactions-modal .message-reactions-reactors .reactor:hover .remove {
background-image:url(https://i.imgur.com/u6RwzJp.png)!important;
background-repeat:no-repeat;
background-position:bottom;
background-size:22px 22px
}

/**/

.title-wrap {
box-shadow:inset 10px 0 5px -6px #000!important;
border-bottom:0 solid rgba(0,0,0,0.3)!important;
background:rgba(0,0,0,0.55)!important
}

.bot-tag {
color:#fff!important;
background:#900
}

/* Clyde Bot*/

.theme-dark .message-group.is-local-bot-message {
background:#33333;
background-image:none;
box-shadow:none
}

.theme-dark .message-group .local-bot-message {
color:#b2b2b2
}

/*----------*/

.form .form-inner .mentioned .highlight {
background:rgba(35,35,35,.75)!important
}

.form .form-inner .highlight {
background:rgba(35,35,35,.75)
}

.form .form-header {
color:#e5e5e5!important;
background:#191919;
border-bottom:6px solid #900;
border-color:#900!important
}

.form .form-actions {
border-top:6px solid #900
}

.markdown-modal,.form .form header,.form .form-inner,.form .form-actions,.need-help-modal .footer,.markdown-modal .markdown-modal-footer {
background:#191919!important
}

.form header {
color:#e5e5e5
}

.channel-notification-settings .content label,.notification-settings-modal .mute-server .checkbox .label span {
color:#ccc
}

.notification-settings-modal .notification-settings-modal-channel-settings-list {
box-shadow:none!important
}

.channel-notification-settings .content .content-inner {
box-shadow:none
}

.notification-settings-modal .notification-settings-modal-channel-settings-header label.title {
color:#ccc
}

.notification-settings-modal .notification-settings-modal-channel-settings-header label.subtitle {
color:#ccc
}

.channel-notification-settings {
border:hidden
}

.channel-notification-settings .content a {
color:#ccc
}

.markdown-modal .markdown-modal-header {
border-bottom:6px solid #900;
color:#e5e5e5
}

.markdown-modal .scroller-wrap .scroller {
color:#ccc
}

#user-profile-modal footer .btn.add-friend {
background:#232323;
color:#e5e5e5
}

#user-profile-modal footer .btn.add-friend:hover {
background:#900;
color:#e5e5e5
}

#user-profile-modal footer .btn.reject-friend {
background:#232323
}

#user-profile-modal footer .btn.reject-friend:hover {
background:#900
}

#user-profile-modal footer .pending p {
color:#ccc
}

#user-profile-modal footer {
border:hidden
}

#user-profile-modal .header .activity {
visibility:collapse;
font-size:0;
color:#b2b2b2
}

#user-profile-modal .header .activity strong {
visibility:visible;
font-size:14px
}

#user-profile-modal .header .discord-tag .discriminator,#user-profile-modal .header .discord-tag {
color:#e5e5e5
}

#user-profile-modal .empty .empty-text {
color:#ccc
}

#user-profile-modal .guilds .guild .guild-name {
color:#ccc
}

.small-popout-box {
background:#191919;
border:hidden;
color:#e5e5e5
}

.option-popout .btn-item {
color:#ccc
}

.option-popout .btn-item:hover {
color:#e5e5e5
}

.modal-content .user-name {
color:#e5e5e5
}

.modal-content .form-inner p {
color:rgba(255,255,255,0.7)
}

.chat .new-messages-bar {
background-color:rgba(35,35,35,.75)
}

.chat .new-messages-bar:hover {
background-color:rgba(25,25,25,.75)
}

.chat .new-messages-bar button:last-child {
color:#ccc
}

.theme-dark .chat .empty-message {
border:none;
background:none;
position:relative;
top:-15px
}

.chat-empty {
background:rgba(200,200,200,95)
}

.chat .empty-message h1 {
color:#ccc
}

.chat>.title-wrap>.title .channel-name {
color:#e5e5e5
}

.chat>.title-wrap>.topic {
font-size:14px;
margin-top:5px;
color:#e5e5e5!important
}

.chat>.title-wrap>.topic .aka {
background:#232323
}

.theme-dark .header-toolbar button.active {
background:#232323
}

.markdown-modal .highlight,.chat .title-wrap .topic .highlight {
background-color:rgba(35,35,35,.75)!important

}

.markdown-modal .highlight:hover,.chat .title-wrap .topic .highlight:hover {
background-color:rgba(25,25,25,.75)!important;
color:#e5e5e5!important
}

.upload-modal {
background:#191919
}

.upload-modal .footer {
background:#191919
}

.upload-modal .footer .button {
background:#232323;
margin:5px;
color:#ccc
}

.upload-modal .footer .button:hover {
background:#900;
color:#e5e5e5!important
}

.upload-modal .inner {
border:hidden
}

.upload-modal .inner .file .icon.image {
border:hidden
}

.upload-modal .inner .comment .label .optional {
color:#b2b2b2;
opacity:1
}

.upload-drop-modal {
background:#191919
}

.upload-drop-modal .bgScale {
background:#191919
}

.upload-drop-modal .inner .icons {
display:none
}

.chat .divider:not(.divider-red)>div {
background:rgba(255,255,255,0.2)!important
}

.chat .divider>span {
background:rgba(35,35,35,.75)!important;
font-size:12px;
text-transform:uppercase;
margin:10px 0;
border-radius:0;
opacity:1;
padding:5px 15px;
width:100%;
text-align:center
}

.chat .divider.divider-red>span {
background:rgba(35,35,35,.75)!important;
color:#ccc!important;
border-radius:0;
opacity:1!important
}

.chat .divider:not(.divider-red)>span {
color:#e5e5e5!important;
opacity:1!important
}

.chat .divider>div {
display:none
}

.chat .divider {
margin-bottom:30px;
margin-top:30px
}

.chat .divider:before {
display:none
}

.chat form {
border-top:none!important;
box-shadow:none
}

.theme-dark .chat .jump-to-present-bar {
background:rgba(35,35,35,.75);
}

.theme-dark .chat .jump-to-present-bar:hover {
background:rgba(25,25,25,.75)
}

.chat .jump-to-present-bar button:last-child {
background:none;
color:#e5e5e5
}

.chat .jump-to-present-bar button:first-child {
background:none;
color:#e5e5e5
}

.messages .message-group:not(.has-divider) {
border-bottom-color:hsla(0,0%,100%,.04)!important
}

.messages .message-group .markup .highlight {
background-color:rgba(35,35,35,.75)!important;
color:#ccc!important;
padding:0.51px 4px;
border-radius:0
}

.messages .message-group .markup .highlight:hover {
background-color:rgba(35,35,35,1)!important;
color:#e5e5e5!important
}

.form-inner .message-group .comment .markup {
color:#ccc;
background:#191919
}

.form-inner .message-group .comment .markup pre {
background:rgba(35,35,35,.75);
border:none;
border-radius:0;
margin-top:4px;
padding:1px
}

.form-inner .message-group .comment .markup pre code {
background:rgba(35,35,35,.75)
}

.form-inner .message-group .comment .markup code.inline {
padding:0.19em!important
}

.message-group .avatar-large {
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
border-radius:0;
margin-left:6px;
margin-bottom:8px;
background-color:#232323
}

.message-group h2 .timestamp {
color:#ccc
}

.messages .message-group {
border-bottom:none!important
}

.delete-message-modal .form-inner .message-group .comment .markup pre {
background:none;
border:none
}

.delete-message-modal .form-inner .message-group .comment .markup pre code {
background:#232323;
line-height:1.5
}

.delete-message-modal .form-inner .message-group .highlight {
background:#232323
}

.delete-message-modal .form-inner .message-group .comment .markup code.inline {
background:#232323!important;
line-height:2;
border-radius:0
}

.messages .markup {
background:none!important
}

.friends-table .messages .message-group .message-send-failed .markup,.friends-table .messages .message-group .message-send-failed .markup a,.messages .message-group .message-send-failed .markup,.messages .message-group .message-send-failed .markup a {
color:rgba(153,0,0,0.5)!important;
font-style:italic
}

.messages .mentioned .message-text {
border-radius:0!important;
background:rgba(35,35,35,0)!important
}

.messages .mentioned .message-text:after {
border-radius:0!important;
border:none!important;
background:none!important
}

.message-group .mentioned .message-text:after {
border:none;
background:none
}

.message-group .edit-message.edit-first-message {
margin-left:-86px;
margin-top:-6px
}

.message-group .edit-message {
margin-left:-86px
}

.message-group .edit-message .channel-textarea-inner {
margin-left:0px
}

.message-group .edit-message .channel-textarea-inner textarea {
overflow-y:auto!important
}

.message-group .edit-message .channel-textarea-inner textarea::-webkit-scrollbar {
background:none
}

.message-group .edit-message .channel-textarea-inner textarea::-webkit-scrollbar-track-piece {
background:none!important
}

.message-group .edit-message .channel-textarea-inner textarea::-webkit-scrollbar-thumb {
background:rgba(56,56,56,.75)!important;
border:1px solid rgba(35,35,35,0.75)
}

.comment > div[style^="border-radius: 2px;"] {
background-color:transparent!important;
}

.comment > div[style^="border-radius: 2px;"]:not([style$="0);"]) .message {
-webkit-animation:anim 5s;
}

@-webkit-keyframes anim {
0%{background:rgba(135,0,0,.50);}
100%{background:rgba(135,0,0,0);}
}

.messages a {
color:#25ACE8!important
}

.messages .markup {
color:#ccc!important;
line-height:1.6em!important
}

.messages .comment .markup pre {
border-radius:0!important;
border:none
}

.messages h2 .user-name {
color:rgba(255,255,255,0.8)
}

.messages h2 span {
color:#ccc!important
}

.chat .welcome-message h1 {
color:#e5e5e5
}

.chat .welcome-message strong {
color:#ccc
}

.chat .welcome-message p {
color:#b2b2b2
}

.messages .markup pre {
background:transparent!important;
border-color:rgba(255,255,255,0.1)!important
}

.messages .markup pre code.hljs {
background:rgba(35,35,35,0.75)!important;
color:#b2b2b2!important;
padding:0.85em!important;
border-radius:0
}

.messages .markup pre code.hljs::-webkit-scrollbar-track-piece {
background:none!important
}

.messages .markup pre code.hljs::-webkit-scrollbar {
background:none
}

.messages .markup pre code.hljs::-webkit-scrollbar-thumb {
background:rgba(56,56,56,.75);
border:1px solid rgba(35,35,35,0.75)
}

.modal-content .markup code.inline,.messages .markup code.inline {
background:rgba(35,35,35,0.75)!important;
color:#b2b2b2!important;
padding:.2em .6em!important;
border-radius:0!important
}

.channel-textarea-upload {
border:hidden!important
}

.theme-dark .channel-textarea.has-results .channel-textarea-inner {
border:hidden
}

.channel-textarea-inner {
border:hidden!important;
background:rgba(35,35,35,.75)!important;
margin:0px;
margin-left:-20px;
border-radius:0
}

.channel-textarea-inner textarea::-webkit-input-placeholder {
color:#e5e5e5!important
}

.channel-textarea-autocomplete-inner {
border:hidden!important;
background:rgba(25,25,25,1)!important;
color:#e5e5e5;
bottom:0;
width:90%;
margin-left:-20px
}

.channel-textarea-autocomplete-inner:after {
border:none!important
}

.channel-textarea-autocomplete-inner header {
border-bottom:6px solid #900!important;
background:rgba(35,35,35,1)!important;
color:#e5e5e5!important
}

.channel-textarea-autocomplete-inner ul li.active {
background:#232323!important;
color:#e5e5e5;
border:hidden
}

.theme-dark .friends-table .messages .message-group .edit-message .edit-operation,.theme-dark .messages-wrapper .messages .message-group .edit-message .edit-operation {
margin:0;
color:#ccc
}

.channel-textarea {
margin:23px
}

div.chat.flex-vertical.flex-spacer.private .channel-textarea-guard button {
background:rgba(25,25,25,.75)!important
}

div.chat.flex-vertical.flex-spacer.private .channel-textarea-guard button:hover {
background:#900!important
}

.channel-textarea-guard div {
color:#ccc
}

.channel-textarea-guard {
background-image:none!important
}

.theme-dark .chat form .typing {
margin:0 10px -3px 20px
}

.channel-textarea-emoji>.sprite-item {
background-image:url("")
}

.spoiler span {
display:none
}

.spoiler:before {
min-height:18px;
padding-top:2px;
border-radius:5px;
background:rgba(25,25,25,0.7)
}

#twitchcord-button {
background-size:24px;
background-position:20px;
background-color:transparent;
opacity:0.4
}

#twitchcord-button:hover,#twitchcord-button.twitchcord-button-open {
opacity:1
}

#twitchcord-button-container {
right:30px!important
}

/* Instant Invite Button */

.theme-dark .invite-button {
background:#191919;
border:none;
border-radius:0
}

.theme-dark .invite-button .invite-button-header {
color:#e5e5e5;
line-height:1.5
}

.theme-dark .invite-button .invite-button-body {
color:#ccc
}

.invite-button-icon {
border-radius:0;
border:none
}

.invite-button-icon.accepted {
border-radius:0
}

.invite-button-icon.expired {
border-radius:0
}

.form .invite-button {
background:#232323;
border:none;
border-radius:0
}

.form .invite-button .invite-button-header {
color:#e5e5e5;
line-height:1.5
}

.form .invite-button .invite-button-body {
color:#ccc
}

/* Blocked Messages */

.message-group-blocked .message-group-blocked-btn {
background:rgba(25,25,25,.75)!important;
color:#e5e5e5!important;
}

.message-group-blocked:hover {
box-shadow:1px .5px 0px 0 rgba(0,0,0,.3),inset 1px -.8px 0 0 rgba(0,0,0,.3)!important
}

.message-group-blocked {
background:rgba(35,35,35,.75)!important;
border:none!important;
border-radius:0;
box-shadow:none!important
}

.theme-dark .messages-wrapper .messages .message-group-blocked.revealed .message-group-blocked-btn {
border-bottom:6px solid #900!important
}

.theme-dark .messages-wrapper .messages .message-group-blocked.revealed .message-group.hide-overflow:hover {
box-shadow:none!important
}

/* BetterDiscord Emote Tooltip */

.tipsy-inner {
background:rgba(35,35,35,.75);
color:#e5e5e5
}

.tipsy {
opacity:1!important;
}

/*** COMPACT MODE ***/
.message-group.compact .timestamp {
position:relative;
top:-3px
}

.message-group.compact .message .markup .user-name {
margin-right:10px
}

.guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before {
left:-8px;
top:11px
}

/*
  __      _                _       _ _     _
 / _|_ __(_) ___ _ __   __| |___  | (_)___| |_
| |_| '__| |/ _ \ '_ \ / _` / __| | | / __| __|
|  _| |  | |  __/ | | | (_| \__ \ | | \__ \ |_
|_| |_|  |_|\___|_| |_|\__,_|___/ |_|_|___/\__|

*/
#friends .btn {
background-color:#232323!important;
color:#e5e5e5
}

.private-channels .channel:hover:not(.selected) .icon-friends {
background-color:transparent!important
}

.private-channels .channel.btn-friends:not(.selected):hover .badge {
margin-right:10px;
background:#900;
color:#e5e5e5;
border-radius:0
}

.private-channels .channel.btn-friends:not(.selected) .badge {
margin-right:33px;
background:#900;
color:#e5e5e5;
border-radius:0
}

.private-channels .channel.btn-friends.selected .badge {
margin-right:10px;
background:#900;
color:#e5e5e5;
border-radius:0
}

.badge {
background:#900!important;
color:#e5e5e5!important;
border-radius:0!important
}

.private-channels .channel .close {
margin-right:5px
}

#friends {
background:transparent!important
}

.friends-header {
background:rgba(0,0,0,0.65)!important
}

.friends-table {
box-shadow:inset 10px 10px 5px -6px rgba(0,0,0,1);
background:rgba(0,0,0,0.65)!important;
margin-top:0!important
}

.friends-header,.friends-table .friends-table-header {
border-bottom:none!important
}

.friends-header .tab-bar .tab-bar-separator,.friends-table .friends-table-header .friends-column-separator {
background:none!important
}

.friends-table .friends-table-body {
padding-top:20px!important
}

.friends-table .friends-row:hover {
background:#191919!important
}

#friends .friends-table .friends-row .friends-column-actions .friends-action.friends-action-red {
background:#232323;
color:#ccc
}

#friends .friends-table .friends-row .friends-column-actions .friends-action.friends-action-red:hover {
background:#900;
color:#e5e5e5
}

#friends .friends-table .friends-row .friends-column-actions .friends-action.friends-action-green {
background:#232323
}

#friends .friends-table .friends-row .friends-column-actions .friends-action.friends-action-green:hover {
background:#900
}

#friends .friends-table .friends-row .friends-column-actions .friends-action+div {
background:#232323
}

#friends .friends-table .friends-row .friends-column-actions .friends-action+div:hover {
background:#900
}

#friends .friends-table .friends-row .friends-column-name .avatar-small {
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
border-radius:0;
margin-left:6px
}

#friends .friends-table .friends-row .friends-column-guilds .avatar-small {
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
border-radius:0
}

.theme-dark .chat .private-channel-call .ripple {
border-radius:0
}

.theme-dark #friends .friends-empty p {
color:#ccc
}

.search-bar .search-bar-inner {
border:none;
background:none
}

.search-bar-icon {
left:-18px
}

.search-bar-icon .icon.icon-search-bar-eye-glass {
background:url(https://i.imgur.com/9R0mm3N.png)!important;
}

.search-bar-icon .icon.visible {
opacity:.80
}

#friends .friends-table .friends-row .friends-column-actions .friends-action-grey {
background:#232323
}

#friends .friends-table .friends-row .friends-column-actions .friends-action-grey:hover {
background:#900
}

.theme-dark .add-friend-input-wrapper {
background:rgba(102,102,102,.13);
border-radius:0;
border:none
}

.theme-dark .add-friend-input-wrapper .add-friend-input::-webkit-input-placeholder {
color:#e5e5e5
}

#friends .btn:hover {
background:#900!important
}

#friends .friends-table .friend-table-add-wrapper .friend-table-add-header .friends-table-add {
background:rgba(0,0,0,.35);
}

.theme-dark #friends .friends-table .friend-table-add-wrapper .friend-table-suggestions-header {
border:none;
margin-top:-25px
}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary.selected {
background:#191919;
color:#b2b2b2
}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item {
color:#b2b2b2
}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary {
background:transparent;
color:#b2b2b2
}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary:hover {
background:#232323!important
}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary.selected {
color:#e5e5e5
}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary:not(.selected):hover {
color:#b2b2b2!important
}

#friends .friends-table .friends-row .friends-column-actions .friends-action.friends-action-add {
background-color:#232323;
background-size:contain
}

#friends .friends-table .friends-row .friends-column-actions .friends-action.friends-action-add:hover {
background-color:#900!important
}

#friends .friends-table .friends-row .friends-column-actions .friends-action.friends-action-ignore {
background-repeat:no-repeat;
background-size:contain;
background-color:#232323
}

#friends .friends-table .friends-row .friends-column-actions .friends-action.friends-action-ignore:hover {
background-image:url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0wIDBoMTZ2MTZIMCIvPgogICAgPHBhdGggZmlsbD0iI0ZGRiIgZD0iTTEyLjY2NjY2NjcgNC4yNzMzMzMzM2wtLjk0LS45NEw4IDcuMDYgNC4yNzMzMzMzMyAzLjMzMzMzMzMzbC0uOTQuOTRMNy4wNiA4bC0zLjcyNjY2NjY3IDMuNzI2NjY2Ny45NC45NEw4IDguOTRsMy43MjY2NjY3IDMuNzI2NjY2Ny45NC0uOTRMOC45NCA4Ii8+CiAgPC9nPgo8L3N2Zz4=);
background-size:contain;
background-color:#900
}

.theme-dark #friends .friends-table .friends-row .friends-column-actions .friends-action {
background-color:#232323;
background-size:contain
}

.theme-dark #friends .friends-table .friends-row .friends-column-actions .friends-action:hover {
background-color:#900!important
}

#friends .friends-table .friends-row .friends-column-actions .friends-action.friends-action-remove:hover {
background:url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGZpbGw9IiNGRkYiIGQ9Ik0xMCAxMmMyLjIxIDAgNC0xLjc5IDQtNHMtMS43OS00LTQtNC00IDEuNzktNCA0IDEuNzkgNCA0IDR6bTAgMmMtMi42NyAwLTggMS4zNC04IDR2MmgxNnYtMmMwLTIuNjYtNS4zMy00LTgtNHptOS4zMDczOTk5LTMuNTA2NjMzM2wxLjY3MjQzMjYtMS42NzI0MzI1NWMuMTI0NTk2LS4xMjQ1OTYwNi4zOTY3NS0uMzk2NzUwMS0uMDA0MDIwMi0uNzk3NTIwMzctLjQwMDc3MDMtLjQwMDc3MDI4LS42NzY5MDA2LS4xMzI1OTI1LS44MDE0OTY3LS4wMDc5OTY0M2wtMS42NzI0MzI1IDEuNjcyNDMyNTItMS42MzY4MjEtMS42MzY4MjFjLS4xMjM2OTY0LS4xMjM2OTY0Ni0uNDI5NzE5MS0uNDI5NzE5MTctLjgzNDQ2NTctLjAyNDk3MjY1LS40MDQ3NDY1LjQwNDc0NjUzLS4wOTk1MDM5LjcxMTU0OTQuMDI0MTkyNS44MzUyNDU4NWwxLjYzNjgyMSAxLjYzNjgyMTAzLTEuNjI1ODI3MyAxLjYyNTgyNzNjLS4xMjM2OTY1LjEyMzY5NjUtLjQzODU5ODkuNDQ2NTUxNC0uMDM3ODI4Ni44NDczMjE3LjQwMDc3MDMuNDAwNzcwMi42NzkyMjgyLjEyMjMxMjMuODAyOTI0Ny0uMDAxMzg0MmwxLjY2NjI0OC0xLjY2NjI0OCAxLjY1NDAxNzQgMS42NTQwMTczYy4xMjQxNDYyLjEyNDE0NjMuNDE5OTIxNi40MTgzNjE0LjgyNDY2ODIuMDEzNjE0OS40MDQ3NDY1LS40MDQ3NDY2LjEwOTc1MTItLjY5OTc0MTgtLjAxNDM5NS0uODIzODg4MWwtMS42NTQwMTc0LTEuNjU0MDE3M3oiLz4KICAgIDxwYXRoIGQ9Ik0wIDBoMjR2MjRIMCIvPgogIDwvZz4KPC9zdmc+);
background-repeat:no-repeat;
background-size:contain
}

#friends .friends-table .friends-row .friends-suggestion-inner .avatar-large {
border-radius:0;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
margin-left:10px
}

/* GROUP CALLS */

.theme-dark .chat .private-channel-call {
background:rgba(0,0,0,.65);
box-shadow:inset 10px 0 5px -6px rgba(0,0,0,1),
inset 0 10px 5px -6px rgba(0,0,0,1);
background:#191919
}

.incoming-call .incoming-call-inner {
background:#191919;
color:#e5e5e5
}

.incoming-call .title {
color:#e5e5e5!important;
opacity:1
}

.incoming-call .options .accept-call {
box-shadow:0px 2.5px 10px #000;
background:#232323
}

.incoming-call .options .decline-call {
box-shadow:0px 2.5px 10px #000;
background:#232323
}

.incoming-call .options .decline-call:hover {
background:#900
}

.incoming-call .callers .avatar-wrapper {
border-radius:0!important
}

.incoming-call .callers .avatar-popout.out-of-focus {
border-radius:0!important
}

.incoming-call .callers .avatar-popout {
border-radius:0!important;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
}

.incoming-call .callers .avatar-pulse {
border-radius:0
}

.theme-dark .chat .private-channel-call .status {
background:#232323;
border:none;
border-radius:8px
}

.private-channel-call .btn-text.btn-danger {
background:#232323;
border-radius:0px
}

.private-channel-call .btn-text {
border-radius:0;
background:#232323
}

.private-channel-call .btn-text:hover {
background:#900
}

.private-channel-call .btn-text:hover {
opacity:1
}

.private-channel-call .btn-text.btn-danger:hover {
background:#900;
opacity:1
}

.theme-dark .chat .private-channel-call .btn-icon {
border-radius:0;
background-color:transparent!important
}

.theme-dark .chat .private-channel-call .btn-icon:hover {
background-color:#333
}

.theme-dark .chat .quick-region-select .label {
color:#b2b2b2
}

.theme-dark .chat .quick-region-select .region {
color:#e5e5e5
}

.region-select-popout .region-select-name {
color:#b2b2b2
}

.region-select-popout .region-select-name:hover {
color:#e5e5e5
}

.region-select-popout .check {
display:none
}

.region-select-popout .item.selected {
border-left:4px solid #900;
border-radius:0
}

.chat>.title-wrap>.title.channel-group-dm .channel-name {
background:#232323
}

.chat>.title-wrap>.title.channel-group-dm .channel-name:hover {
background:#191919!important
}

.chat>.title-wrap>.title.channel-group-dm .channel-name .input-autosize-inner .input-autosize-input {
color:#e5e5e5!important
}

.theme-dark .chat .title-wrap .title.channel-group-dm .channel-name.focus, .theme-dark .chat .title-wrap .title.channel-group-dm .channel-name:hover {
background:#191919
}

.private-channel-recipients-invite {
border:none!important
}

.private-channel-recipients-invite .friend .avatar-small {
border-radius:0px;
box-shadow:-1px 1px 6px #000,inset -1px 1px 6px #000,
inset 1px -1px 6px #000,1px -1px 6px #000
}

.private-channel-recipients-invite .header {
background:#191919!important;
border-bottom:6px solid #900;
border-radius:0px!important
}
.private-channel-recipients-invite .header .title {
color:#e5e5e5!important
}

.private-channel-recipients-invite .header .search-bar {
background:#232323
}

.private-channel-recipients-invite .header .search-bar .search-bar-inner .search-bar input {
background:#232323;
color:#e5e5e5
}

.search-bar-tag {
background:#232323
}

.private-channel-recipients-invite .body .scroller-wrap {
background:#191919!important
}

.private-channel-recipients-invite .footer {
background:#191919!important;
border-top:6px solid #900
}

.private-channel-recipients-invite .footer button {
background:#232323
}

.private-channel-recipients-invite .footer button:hover {
background:#900
}

.private-channel-recipients-invite .footer button:disabled {
background:#333
}

.private-channel-recipients-invite .footer button:disabled:hover {
background:#900
}

.theme-dark .private-channel-recipients-invite .friend {
background:#191919;
color:#b2b2b2
}

.theme-dark .private-channel-recipients-invite .friend.selected {
background:none;
color:#ccc
}

.theme-dark .private-channel-recipients-invite .friend:not(.selected):hover {
color:#e5e5e5;
background:none
}

.private-channel-recipients-invite .error-state.not-friends .text {
color:#e5e5e5
}

.private-channel-recipients-invite .error-state.not-friends .btn {
background:#232323
}

.private-channel-recipients-invite .error-state.not-friends .btn:hover {
background:#900
}

.private-channel-recipients-invite .error-state {
background:#191919
}

.private-channel-recipients-invite .error-state.search-results .text {
color:#e5e5e5
}

.theme-dark .channel-textarea-inner {
width:90%
}

/*
                       _ _     _                   _   _
 _   _ ___  ___ _ __  | (_)___| |_   ___  ___  ___| |_(_) ___  _ __
| | | / __|/ _ \ '__| | | / __| __| / __|/ _ \/ __| __| |/ _ \| '_ \
| |_| \__ \  __/ |    | | \__ \ |_  \__ \  __/ (__| |_| | (_) | | | |
 \__,_|___/\___|_|    |_|_|___/\__| |___/\___|\___|\__|_|\___/|_| |_|

*/
.channel-members .invite-btn {
display:none
}

.channel-members:hover .invite-btn {
background:#232323!important;
display:block!important
}

.channel-members .invite-btn:hover {
background:#900!important
}

.theme-dark .channel-members .member.popout-open {
background:none;
width:100%;
padding-right:20px;
margin-left:0px;
border-left:4px solid #900!important
}

.theme-dark .channel-members-loading {
display: none;
}

.channel-members .member {
margin-left:4px
}

.channel-members .member .member-activity {
visibility:collapse;
font-size:0
}

.channel-members .member .member-activity strong {
visibility:visible;
font-size:11px;
color:#ccc;
font-style:italic;
font-weight:600
}

.private-channels .channel .channel-activity strong {
visibility:visible;
font-size:11px;
color:#ccc;
font-style:italic;
font-weight:600
}

.private-channels .channel:hover .channel-activity strong {
color:#e5e5e5!important
}

.private-channels .channel .channel-activity {
visibility:collapse;
font-size:0
}

.channel-members .member:hover {
background:none!important;
width:100%;
padding-right:20px;
margin-left:0px;
border-left:4px solid #900
}

.channel-members .bot-tag {
margin-right:15px!important
}

.channel-members .member .member-username {
font-size:14px
}

.channel-members .member .member-game {
font-size:10px
}

.channel-members .avatar-small .status {
border-color:#191919!important
}

.channel-members h2 {
padding-top:8px;
padding-bottom:10px;
color:#ccc!important;
font-weight:bold;
text-align:left;
font-size:13px;
opacity:.90
}

.channel-members h2:first-of-type {
margin-top:-45px!important
}

.avatar-small .status {
border-color:#191919
}

.private-channels :not(.selected):hover .status {
border-color:#191919
}

.avatar-xxlarge {
border-radius:0;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000
}

/*CANNOT REMEMBER WHAT AVATAR THIS CHANGES*/
.avatar-medium {
border-radius:8px
}

/*----------------------------------------*/

.avatar-xsmall {
border-radius:0px;
box-shadow:-1px 1px 3px #000,inset -1px 1px 3px #000,
inset 1px -1px 3px #000,1px -1px 3px #000
}

.channel-members .member.member-status-offline .avatar-small {
-webkit-filter:grayscale(100%) blur(1px);
position:relative;
-webkit-transition:all .8s ease;
-moz-transition:all .8s ease;
-o-transition:all .8s ease;
transition:all .8s ease;
-webkit-transform:translateZ(0px);
transform:translateZ(0px)
}

.channel-members .member.popout-open .avatar-small,.channel-members .member:hover .avatar-small {
-webkit-filter:none!important;
filter:none;
position:relative;
-webkit-transition:all .8s ease-out;
-moz-transition:all .8s ease-out;
-o-transition:all .8s ease-out;
transition:all .8s ease-out;
-webkit-transform:translateZ(0px);
transform:translateZ(0px)
}

/*-------------------made by Beard Design-------------------------*/

.channel-members {
transform:translate(150px)!important;
z-index:2!important;
transition:all 300ms ease!important
}

.channel-members:hover {
animation:member 300ms ease!important;
transform:translate(0px)!important;
background:#191919!important
}

.app {
overflow-x:hidden!important
}

.channel-members .member .member-activity,
.channel-members .member .member-username-inner {
opacity:0!important;
transition:opacity 300ms ease, margin 100ms ease!important
}

.channel-members .member .member-username-inner {
margin-bottom:0px!important
}

.channel-members:hover .member .member-activity, .channel-members:hover .member .member-username-inner {
opacity:1!important
}

.header-toolbar button.active {
display:none!important
}

.channel-members h2 {
transform-origin:right!important;
transform:scale(0)!important;
margin-top:-45px!important;
transition:all 300ms ease!important
}

.channel-members:hover h2 {
transform:scale(1)!important;
margin:inherit!important
}

.channel-members .avatar-small {
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
border-radius:0
}

.chat.flex-vertical.flex-spacer>.content.flex-spacer.flex-horizontal>.flex-spacer.flex-vertical {
margin-right:-150px!important;
z-index:1!important
}

.chat.flex-vertical.flex-spacer.private>.content.flex-spacer.flex-horizontal>.flex-spacer.flex-vertical {
margin-right:0px!important;
z-index:1!important;
box-shadow:inset 10px 10px 5px -6px rgba(0,0,0,1)!important
}

div.chat.flex-vertical.flex-spacer.private .channel-members-wrap {
margin-left:-150px
}

/*-------------------------------------------------------------------*/

/*
                       _        __                                       _
 _   _ ___  ___ _ __  (_)_ __  / _| ___    _ __   ___  _ __   ___  _   _| |_
| | | / __|/ _ \ '__| | | '_ \| |_ / _ \  | '_ \ / _ \| '_ \ / _ \| | | | __|
| |_| \__ \  __/ |    | | | | |  _| (_) | | |_) | (_) | |_) | (_) | |_| | |_
 \__,_|___/\___|_|    |_|_| |_|_|  \___/  | .__/ \___/| .__/ \___/ \__,_|\__|
                                          |_|         |_|
*/
.user-popout {
left:-18px
}

.user-popout .header {
background:#191919!important;
border-top-radius:8px!important;
border-bottom:6px solid #900!important;
box-shadow:none
}

.user-popout .avatar-wrapper .avatar-hint {
border-radius:0
}

.user-popout .avatar-wrapper .avatar-popout {
border:none;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
border-radius:0;
background-color:#232323
}

.user-popout .body {
background:#191919;
border-left:0 solid rgba(153,0,0,1);
border-right:0 solid rgba(153,0,0,1);
}

.user-popout .header.streaming {
border-bottom:none !important;
box-shadow:none!important
}

.user-popout .header.streaming .nickname {
color:#fff!important
}

.user-popout .header.streaming .discord-tag .username {
color:#e5e5e5
}

.user-popout .header.streaming .activity strong {
color:#b2b2b2;
margin-left:-66px
}

.user-popout .header.streaming .live-on-twitch {
border-top:6px solid #900;
border-bottom:none;
background:#191919
}

.user-popout .body .section .label {
color:#e5e5e5
}

.user-popout .body .notes textarea {
color:#ccc
}

.user-popout .footer {
background:#191919;
border-top:0 solid rgba(153,0,0,1);
border-left:0 solid rgba(153,0,0,1);
border-right:0 solid rgba(153,0,0,1);
border-bottom:0 solid rgba(153,0,0,1);
border-bottom-radius:8px
}

.user-popout .footer .quick-message-wrapper .input {
background:#232323;
border:hidden;
color:#e5e5e5
}

.user-popout .footer .update-notice {
color:#ccc
}

.user-popout .footer .update-notice .protip {
color:#e5e5e5
}

.user-popout .username-wrapper .username {
color:#e5e5e5
}

.user-popout .username-wrapper .discord-tag .discriminator {
color:#e5e5e5
}

.user-popout .username-wrapper .activity strong {
visibility:visible;
font-size:15px;
color:#ccc;
font-style:italic;
font-weight:600
}

.user-popout .username-wrapper .activity {
visibility:collapse;
font-size:0
}

.user-popout .username-wrapper.has-nickname .discriminator {
color:#ccc
}

.user-popout .username-wrapper.has-nickname .username {
color:#ccc
}

.bot-tag.bot-tag-invert {
background:#900;
color:#e5e5e5!important
}

.popout header {
background-color:#191919;
border-bottom:6px solid #900
}

.slider-bar {
background:#232323!important;
border-radius:0
}

.slider-bar-fill {
background:#900
}

.sensitivity .slider .slider-bar {
background:#900!important
}

.sensitivity .slider .slider-bar-auto {
background:#232323!important
}

.sensitivity .slider .slider-bar-auto.speaking {
background:#900!important
}

.sensitivity .slider .slider-bar.microphone .grow {
background:#232323
}

.popout.popout-invert.popout-top-right header:before,.popout.popout-invert.popout-top header:before {
border-top-color:#e5e5e5
}

.user-popout .user-popout-options .btn {
background-color:#666;
border:1px solid #900
}

.user-popout .user-popout-options .btn:hover {
background-color:#666;
border:1px solid #900
}

.popout section {
background:#191919!important
}

/* Popout Menu */

.popout-menu {
background:#191919;
border-radius:0
}

div.popout.popout-top {
box-shadow:0 0 2px rgba(0,0,0,.82),0 1px 4px 1px rgba(0,0,0,.3)!important
}

div.popout.popout-bottom {
box-shadow:0 0 0 rgba(0,0,0,.82),0 1px 4px 1px rgba(0,0,0,.3)!important
}

div.popout.popout-invert.popout-bottom {
box-shadow:none!important
}

.popout.popout-invert header {
border-top:none!important;
border-bottom:6px solid #900
}

div.popout.popout-top #autocomplete-popout header {
border-bottom:none;
border-top:6px solid #900!important
}

.popout.popout-right.no-arrow {
box-shadow:none
}

.status-picker .popout-menu-item .helper {
color:#ccc
}

.status-picker .popout-menu-item:last-child .helper {
color:#ccc
}

.popout-menu .popout-menu-item.invite {
color:#ccc
}

.popout-menu .popout-menu-separator {
display:none
}

.popout-menu .popout-menu-item {
color:#ccc
}

.popout-menu .popout-menu-item:hover {
background:#232323;
color:#e5e5e5!important
}

.popout-menu [style*='background-image: url("/assets/9a93097ab591379729c68f15a17b26af.svg");'] {
background-image:url(https://i.imgur.com/rI8942r.png)!important;
background-size:18px 18px
}

.popout-menu [style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0wIDBoMTh2MThIMHoiLz4KICAgIDxwYXRoIGZpbGw9IiM3MzdGOEQiIGQ9Ik05IDloNS4yNWMtLjM5NzUgMy4wODI1LTIuNDYgNS44MzUtNS4yNSA2LjY5VjlIMy43NVY0LjcyNUw5IDIuMzkyNVY5em0wIDBIMy43NWMuMzk3NSAzLjA4MjUgMi40NiA1LjgzNSA1LjI1IDYuNjlWOWg1LjI1VjQuNzI1TDkgMi4zOTI1Vjl6TTkgLjc1bC02Ljc1IDN2NC41YzAgNC4xNjI1IDIuODggOC4wNDc1IDYuNzUgOSAzLjg3LS45NTI1IDYuNzUtNC44Mzc1IDYuNzUtOXYtNC41TDkgLjc1eiIvPgogIDwvZz4KPC9zdmc+");'] {
background-image:url(https://i.imgur.com/PLMb5Jf.png)!important;
background-size:18px 18px
}

.popout-menu [style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPHBhdGggZmlsbD0iIzczN0Y4RCIgZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMyAxNHYtMi41bDcuODgtNy44NWMuMTktLjIuNTEtLjIuNzEgMGwxLjc2IDEuNzZjLjIuMi4yLjUxIDAgLjcxTDUuNDcgMTRIM3ptMTIgMEg3LjVsMi0ySDE1djJ6Ii8+Cjwvc3ZnPg==");'] {
background-image:url(https://i.imgur.com/u1wlBLb.png)!important;
background-size:18px 18px
}

.popout-menu [style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0wIDBoMTh2MThIMHoiLz4KICAgIDxnIGZpbGw9IiM3MzdGOEQiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIuMjUgMS41KSI+CiAgICAgIDxwYXRoIGQ9Ik02Ljc2NzcyMTAzLjc1SDEuNDk2MzE2OTdDLjY2OTQ2NzEuNzUgMCAxLjQxOTkyMzkzIDAgMi4yNDYzMTY5N1YxMi43NTM2ODNDMCAxMy41ODA1MzI5LjY2OTkyMzkzIDE0LjI1IDEuNDk2MzE2OTcgMTQuMjVIMTIuMDAzNjgzYy44MjY4NDk5IDAgMS40OTYzMTctLjY2OTkyMzkgMS40OTYzMTctMS40OTYzMTdWNy40ODIwODM2MmMtLjQ1NDM1NTYuMjkxMjMwODgtLjk1OTk3NTguNTA5MTQ4OS0xLjUuNjM3MDU3NDRWMTIuNzVIMS41VjIuMjVoNC42MzA3Mzk5MmMuMTI3ODkxMzYtLjU0MDI4ODcuMzQ1ODI2Ny0xLjA0NTg0MjQuNjM2OTgxMS0xLjV6Ii8+CiAgICAgIDxyZWN0IHdpZHRoPSI2IiBoZWlnaHQ9IjYiIHg9IjguMjUiIHJ4PSIzIi8+CiAgICA8L2c+CiAgPC9nPgo8L3N2Zz4=");'] {
background-image:url(https://i.imgur.com/3Qk2DA6.png)!important;
background-size:18px 18px
}

.popout-menu [style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0wIDBoMTh2MThIMHoiLz4KICAgIDxwYXRoIGZpbGw9IiM3Mjg5REEiIGQ9Ik03LjU0NTM1MzQgMTEuMjM0Mjg3M2w1Ljc2LTUuMTkwMDAwMDRjLjI1NS0uMjMyNS0uMDUyNS0uMzQ1LS4zOS0uMTQyNWwtNy4xMSA0LjQ5MjUwMDA0LTMuMDc1LS45NzUwMDAwNGMtLjY2LS4xODc1LS42Njc1LS42NDUuMTUtLjk3NWwxMS45Nzc1LTQuNjJjLjU0NzUtLjI0NzUgMS4wNzI1LjEzNS44NjI1Ljk3NWwtMi4wNCA5LjYwNzUwMDA0Yy0uMTQyNS42ODI1LS41NTUuODQ3NS0xLjEyNS41MzI1bC0zLjEwNS0yLjI5NS0xLjQ5MjUgMS40NDc1Yy0uMTcyNS4xNzI1LS4zMTUuMzE1LS42MjI1LjMxNWwuMjEtMy4xNzI1eiIvPgogIDwvZz4KPC9zdmc+");'] {
background-image:url(https://i.imgur.com/UFCZJTQ.png)!important;
background-size:18px 18px
}

.popout-menu [style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0wIDBoMTh2MThIMHoiLz4KICAgIDxwYXRoIGZpbGw9IiM3MzdGOEQiIGQ9Ik0xNC4yNSAyLjI1SDMuNzVjLS44MzI1IDAtMS41LjY2NzUtMS41IDEuNXYzaDEuNXYtM2gxMC41djEwLjVIMy43NXYtM2gtMS41djNjMCAuODI4NDI3MS42NzE1NzI4NyAxLjUgMS41IDEuNWgxMC41Yy44Mjg0MjcxIDAgMS41LS42NzE1NzI5IDEuNS0xLjVWMy43NWMwLS44MzI1LS42NzUtMS41LTEuNS0xLjV6bS02LjY5IDkuNDM1bDEuMDY1IDEuMDY1TDEyLjM3NSA5bC0zLjc1LTMuNzVMNy41NiA2LjMwNzUgOS41MDI1IDguMjVIMi4yNXYxLjVoNy4yNTI1TDcuNTYgMTEuNjg1eiIvPgogIDwvZz4KPC9zdmc+");'] {
background-image:url(https://i.imgur.com/O5RG3dq.png)!important;
background-size:18px 18px
}

/*-------------*/

.popout.popout-bottom header:before {
border-bottom-color:#232323
}

#autocomplete-popout .row.selected {
background:#232323!important;
color:#ccc!important
}

#autocomplete-popout h3 {
color:#e5e5e5
}

#autocomplete-popout .section {
color:#ccc
}

#autocomplete-popout .empty:hover {
background:#232323
}

#autocomplete-popout .empty p {
color:#ccc
}

#autocomplete-popout .row .avatar-small {
border-radius:0;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000
}

#autocomplete-popout .row a {
color:#ccc
}

#autocomplete-popout .row.selected a {
color:#ccc!important
}

#autocomplete-popout .row:hover a {
color:#e5e5e5!important
}

#autocomplete-popout .scroller::-webkit-scrollbar-track {
background:#383838!important;
border:1px solid transparent!important;
border-radius:0;
background-clip:content-box!important
}

.quick-message {
background:#232323;
border:none;
border-radius:0;
color:#e5e5e5
}

.quick-message::-webkit-input-placeholder {
color:#e5e5e5
}

/* Admin buttons */
.user-popout .user-popout-options .btn.btn-server {
color:rgba(255,255,255,0.7);
background:rgba(153,0,0,0.4);
border:none!important
}

.user-popout .user-popout-options .btn.btn-server:hover {
color:rgba(255,255,255,1);
background:rgba(153,0,0,1);
border:none!important
}

/* PINNED MESSAGES */
.theme-dark .messages-popout-wrap {
background:#191919;
border:none
}

.theme-dark .messages-popout-wrap .header {
background:#191919;
border-bottom:6px solid #900
}

.theme-dark .messages-popout-wrap .header .title {
color:#e5e5e5
}

.theme-dark .messages-popout-wrap .messages-popout .message-group {
background:#232323;
border:none;
box-shadow:0 0 1px rgba(0,0,0,.82),0 1px 4px rgba(0,0,0,.1);
border-radius:0
}

.theme-dark .messages-popout-wrap .messages-popout .message-group .comment .markup code.inline {
background:rgba(25,25,25,.50);
border-radius:0
}

.theme-dark .messages-popout-wrap .messages-popout .message-group .comment .markup {
background:#232323
}

.theme-dark .messages-popout-wrap .messages-popout .message-group .comment .markup pre {
background:rgba(25,25,25,.50)!important;
border:none;
border-radius:0;
margin-top:4px
}

.theme-dark .messages-popout-wrap .messages-popout .message-group .comment .markup pre code {
background:rgba(25,25,25,.50)!important;
overflow-y:hidden;
color:#ccc
}

.theme-dark .messages-popout-wrap .messages-popout .message-group .comment .markup .highlight {
background:rgba(25,25,25,.50)!important
}

.messages-popout .message-group .action-buttons {
border:none!important;
background:none!important;
box-shadow:none!important;
right:2px!important
}

.theme-dark .messages-popout-wrap .messages-popout .message-group .action-buttons .jump-button {
background:#333333;
color:#e5e5e5;
}

.theme-dark .messages-popout-wrap .messages-popout .empty-placeholder .body {
color:#e5e5e5
}

.theme-dark .messages-popout-wrap .has-more button {
background-color:#232323;
border:none;
border-radius:0;
color:#ccc
}

.theme-dark .messages-popout-wrap .has-more button:hover {
background-color:#900
}

.theme-dark .messages-popout-wrap .footer {
background:#191919;
border-top:6px solid #900
}

.protip.popout-footer .label {
color:#e5e5e5
}

.protip.popout-footer .tip {
color:#b2b2b2
}

/* RECENT MESSAGES */
.recent-mentions-popout .header .tab-bar-item.selected {
border:none
}

.recent-mentions-popout .header .tab-bar-item:hover {
border:none
}

.context-menu.recent-mentions-filter-popout {
box-shadow:0 0 1px rgba(0,0,0,.82),0 1px 4px rgba(0,0,0,.1);
background:#232323!important;
border-radius:0
}

.context-menu.recent-mentions-filter-popout .item {
color:#ccc
}

.context-menu.recent-mentions-filter-popout .item:hover {
background:none!important
}

.theme-dark .recent-mentions-popout .mention-filter .label {
color:#ccc
}

.theme-dark .recent-mentions-popout .messages-popout .message-group .comment .markup .highlight {
background:rgba(25,25,25,.50)
}

.theme-dark .recent-mentions-popout .messages-popout .message-group .comment .markup pre {
background:rgba(25,25,25,.50)!important;
border:none;
margin-top:5px
}

/*
 _              _ _   _
| |_ ___   ___ | | |_(_)_ __  ___
| __/ _ \ / _ \| | __| | '_ \/ __|
| || (_) | (_) | | |_| | |_) \__ \
 \__\___/ \___/|_|\__|_| .__/|___/
                       |_|
*/
.tooltip {
background:#232323;
color:#fff
}

.tooltip.tooltip-left:after {
border-left-color:#e5e5e5!important
}

.tooltip.tooltip-right:after {
border-right-color:#e5e5e5
}

.tooltip.tooltip-top:after {
border-top-color:#e5e5e5
}

.tooltip.tooltip-bottom:after {
border-bottom-color:#e5e5e5
}

.tooltip.tooltip-error {
background-color:#232323
}

.tooltip.tooltip-error.tooltip-right:after {
border-right-color:#e5e5e5
}

/*
           _       _                 _                       _
 _ __ ___ (_)_ __ (_)_ __ ___   __ _| |  _ __ ___   ___   __| | ___
| '_ ` _ \| | '_ \| | '_ ` _ \ / _` | | | '_ ` _ \ / _ \ / _` |/ _ \
| | | | | | | | | | | | | | | | (_| | | | | | | | | (_) | (_| |  __/
|_| |_| |_|_|_| |_|_|_| |_| |_|\__,_|_| |_| |_| |_|\___/ \__,_|\___|

*/
/* SERVER LIST */
.bd-minimal .guilds {
padding-left:10px!important
}

.bd-minimal .guilds .friends-icon {
background-size:60%
}

.bd-minimal .guilds li .guild-inner:before {
height:25px;
border-radius:5px;
margin-top:-13px
}

.bd-minimal .guilds li.unread .guild-inner:before {
width:10px;
height:10px;
margin-top:-5px;
left:-16px
}

.bd-minimal .guilds li.active .guild-inner:before {
left:-18px;
border-radius:5px;
height:25px;
margin-top:-13px
}

.bd-minimal .guilds li,.bd-minimal .guilds li .avatar-small,.bd-minimal .guilds li .guild-inner,.bd-minimal .guilds li .guild-inner a,.bd-minimal .guilds .friends-icon {
width:25px;
height:25px;
line-height:25px
}

.bd-minimal .guilds li .avatar-small,#bd-pub-button {
font-size:10px!important
}

#bd-pub-button {
margin-top:-12px!important;
}

.bd-minimal .guilds .friends-online {
font-size:10px;
word-spacing:50px;
line-height:20px;
margin-left:0;
width:25px;
height:20px;
border-radius:20px;
overflow:hidden;
background:rgba(0,0,0,0.5)
}

/* CHAT */
.bd-minimal .chat>.title-wrap>.title {
font-size:16px
}

.bd-minimal .theme-dark .comment {
border-left:none!important;
padding-left:10px
}

.bd-minimal .message-group {
padding:10px 5px
}

.bd-minimal .guild-channels ul .channel-text .channel-name {
padding-left:5px
}

.bd-minimal .avatar-large {
border-radius:100%
}

.bd-minimal .message-group .edit-message .edit-container-outer {
margin-left:50px
}

.bd-minimal .message-group .edit-message .edit-container-inner {
margin-left:10px
}

/* MEMBERS */
.bd-minimal .channel-members h2 {
margin-top:20px;
margin-bottom:3px;
padding-left:20px
}

.bd-minimal .channel-members h2:first-of-type {
margin-top:0;
margin-bottom:3px
}

.bd-minimal .channel-members .member {
padding:5px 15px 8px 20px
}

/* CHANNELS */
.bd-minimal .guild-header header span {
margin-left:-13px;
font-size:14px
}

.bd-minimal .guild-channels ul .channel-text.unread:not(.selected):not(.channel-muted):before {
top:9px;
width:10px;
height:10px
}

.bd-minimal .guild-channels h2 {
margin-left:10px
}

/* ACCOUNT BAR */
.bd-minimal #rtc-connection {
width:150px;
margin-left:0
}

.bd-minimal .account {
width:159px;
margin-left:0
}

.bd-minimal .account .avatar-small {
display:block!important
}

.bd-minimal .account .username {
display:none
}

.bd-minimal .account .btn-group {
margin-left:-10px
}

.bd-minimal .account .btn-group .btn {
width:30px
}

/*
          _   _   _
 ___  ___| |_| |_(_)_ __   __ _ ___
/ __|/ _ \ __| __| | '_ \ / _` / __|
\__ \  __/ |_| |_| | | | | (_| \__ \
|___/\___|\__|\__|_|_| |_|\__, |___/
                          |___/
*/
.context-menu {
background:#191919!important
}

.context-menu .item.danger {
color:#ccc!important
}

.context-menu .item.danger:hover {
color:#e5e5e5!important
}

.context-menu .item:hover,.context-menu .item-subMenu {
background-color:#191919!important
}

.context-menu .item {
color:#ccc
}

.context-menu .item:hover {
color:#e5e5e5
}

.change-nickname-warning {
background:#232323
}

.need-help-modal .header {
background:#191919;
border-bottom:6px solid #900
}

.need-help-modal .header input[type=text] {
box-shadow:none
}

.need-help-modal .header input[type=text]::-webkit-input-placeholder {
color:#e5e5e5
}

.need-help-modal a {
color:#b2b2b2
}

.need-help-modal a:hover {
color:#e5e5e5
}

.need-help-modal .footer {
color:#e5e5e5;
border-top:6px solid #900
}

.avatar-uploader .avatar-uploader-inner {
color:#b2b2b2;
border-radius:0px!important;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
border:none!important;
background-color:#232323;
background-repeat:no-repeat
}

.create-guild-container .avatar-uploader .avatar-uploader-inner {
width:64%
}

.avatar-uploader .avatar-uploader-inner:hover {
color:#b2b2b2;
border-radius:0px!important;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
border:none!important;
opacity:.85
}

.avatar-uploader .avatar-uploader-inner .avatar-uploader-hint {
margin-left:4px
}

.markdown-modal,.form
.form-inner,.form .formheader,.form .form-actions,.need-help-modal .footer,.markdown-modal .markdown-modal-footer {
background:#191919!important
}

.form .control-group label a:hover {
color:#e5e5e5
}

.form .control-group input {
background-color:#232323;
border-radius:0;
line-height:34px
}

.clipboard-input-inner button.copy {
background-color:#232323;
border-radius:0;
border:0
}

.clipboard-input-inner {
border:0;
border-radius:0
}

.clipboard-input-inner button.tweet {
background-color:#232323;
border:hidden
}

.clipboard-input-inner input {
color:#ccc;
border-radius:0;
background:#232323
}

.clipboard-input-inner button:first-of-type:before {
width:0
}

.instant-invite-popout a {
color:#ccc
}

.instant-invite-popout a:hover {
color:#e5e5e5
}

.instant-invite-popout hr {
border:3px solid #900
}

.instant-invite-popout .actions .countdown {
color:#e5e5e5
}

/* New Instant Invites Modal */

.instant-invite-modal {
border-radius:8px
}

#instant-invite-modal .copy {
background-image:none!important;
background-color:#383838
}

.clipboard-input-copied .clipboard-input-inner {
border:none!important
}

.clipboard-input-copied button:not(.tweet) {
background-image:url(https://i.imgur.com/vpF5Uw4.png)!important;
background-color:#900!important;
border:none!important
}

#instant-invite-modal .clipboard-input-inner button.copy {
background-image:none!important
}

#instant-invite-modal .clipboard-input-copied button:not(.tweet) {
background-image:url(https://i.imgur.com/vpF5Uw4.png)!important
}

#instant-invite-modal .clipboard-input-inner input {
color:#ccc
}

#instant-invite-modal .form-header header {
color:#e5e5e5
}

#instant-invite-modal .blurb {
color:#ccc
}

#instant-invite-modal .expire-text {
color:#b2b2b2
}

#instant-invite-modal-advanced .form-actions .btn-default {
color:#e5e5e5
}

#instant-invite-modal .form-actions .advanced {
background-image:url(https://i.imgur.com/rI8942r.png)!important;
background-size:18px 18px
}

.channel-notices .channel-notice.invite {
background:#191919
}

.channel-notices .channel-notice .message {
margin-top:-30px;
margin-bottom:-30px
}

.channel-notices .channel-notice .message .btn {
background:#232323
}

.channel-notices .channel-notice .message .btn:hover {
background:#900
}

/*--------------------------*/

.Select-menu-outer {
background:#232323;
border:none;
color:#e5e5e5!important;
border-radius:0!important
}

.Select-option {
color:#ccc!important
}

.Select-option:hover {
background:none!important;
position:relative;
border-radius:0!important
}

.has-value>.Select-control>.Select-value {
background-color:#232323;
padding:8px 52px 10px 10px
}

.form .Select-placeholder {
color:#e5e5e5!important;
border-radius:0;
border:none;
background-color:#232323
}

.form .Select-control * {
color:#e5e5e5
}

.Select-control {
border-radius:0
}

.user-settings-locale .select-item .primary {
color:#e5e5e5!important
}

.user-settings-locale .select-item .localized {
color:#e5e5e5
}

.user-settings-locale .select-item.option-value {
color:#ccc!important
}

.form .voice-settings
.control-groups .control-group .Select-control {
border-radius:0;
background-color:#232323;
color:#e5e5e5
}

.form .voice-settings
.control-groups .control-group .Select(in-focus-has-value) {
border-radius:0;
background-color:#232323;
color:#e5e5e5
}

.avatar-uploader a {
color:#ccc;
margin-left:5px
}

.avatar-uploader a:hover {
color:#e5e5e5
}

.form .control-group label a {
color:#b2b2b2
}

.form .control-group .help-text {
color:#ccc!important
}

.protip .label {
color:#ccc
}

.protip {
color:#b2b2b2
}

.user-settings-appearance .protip .tip,.user-settings-streamer-mode .protip .tip {
color:#b2b2b2
}

.streamer-mode-enabled {
background:#191919
}

.settings .settings-header {
background:#e5e5e5!important
}

.settings .settings-inner .settings-panel-header {
color:#e5e5e5
}

.instant-invites .instant-invites-list .instant-invite {
color:#ccc
}

.instant-invites .instant-invites-list .instant-invite+.instant-invite {
border-top:0
}

.instant-invites .instant-invites-list .instant-invite .countdown {
color:#e5e5e5
}

.instant-invites .instant-invites-list .instant-invite .countdown.countdown-never {
color:#e5e5e5
}

.instant-invites .instant-invites-list .instant-invite .show-channel .member {
color:#ccc
}

.instant-invites .instant-invites-list .instant-invite .show-channel .channel {
color:#ccc
}

.instant-invites .instant-invites-list .instant-invite .show-channel .avatar-small {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000
}

.instant-invites .instant-invites-list .instant-invite .member .avatar-small {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000
}

.instant-invites .instant-invites-list .instant-invite .member {
color:#ccc
}

div.control-group .shortcut-recorder input[type=text] {
color:#e5e5e5;
text-shadow:0 0 0 #000;
font-weight:400
}

.instant-invites .instant-invite-buttons .btn.btn-danger {
background:#232323;
border:hidden;
color:#e5e5e5
}

.instant-invites .instant-invite-buttons .btn.btn-danger:hover {
background:#900;
color:#fff
}

.form .btn.red {
background-color:#232323;
border:0
}

.form .btn.red:hover {
background:#900
}

.guild-settings-modal-members .member-buttons .btn+.btn {
background-color:#232323;
color:#ccc;
border:0;
margin-top:4px
}

.guild-settings-modal-members .guild-settings-modal-members-footer .help-text strong {
color:#ccc
}

.guild-settings-modal-members .guild-settings-modal-members-footer .help-text {
color:#b2b2b2
}

.guild-settings-modal-overview a {
color:#ccc
}

.guild-settings-modal-overview .settings-panel .verification-level-select .radio-group li .criteria {
color:#ccc
}

.guild-settings-modal-overview .settings-panel .explicit-content-filter-select .radio-group li .description {
color:#ccc
}

.guild-settings-modal-members .member-buttons .btn+.btn:hover {
background-color:#900
}

.guild-settings-modal-members .member-buttons .btn {
background-color:#232323;
border:0;
color:#ccc
}

.guild-settings-modal-members .member-buttons .btn.btn-danger {
border:none;
color:#e5e5e5
}

.guild-settings-modal-members .member-buttons .btn.btn-danger:hover {
background:#900
}

.guild-settings-modal-members .member-buttons .btn:hover {
background-color:#900
}

.guild-settings-modal-integrations .guild-settings-modal-integrations-header {
color:#e5e5e5
}

.guild-settings-modal-members .guild-settings-modal-list .member .member-username {
color:#e5e5e5
}

.guild-settings-modal-integrations .guild-settings-modal-integrations-body.no-integrations p {
color:#b2b2b2
}

.guild-settings-modal-integrations .guild-settings-modal-integrations-body.no-integrations p a {
color:#00b0f4
}

.guild-settings-modal-integrations
.guild-settings-modal-integrations-body.no-integrations p a:hover {
color:#e5e5e5
}

.guild-settings-modal-members h6 {
color:#e5e5e5
}

.guild-settings-modal-members
.guild-settings-modal-members-header .form .Select .Select-value {
color:#e5e5e5
}

.guild-settings-modal-members .guild-settings-modal-list .member .avatar-small {
border-radius:0;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000
}

.guild-settings-modal-members
.guild-settings-modal-members-footer .help-text strong {
color:#e5e5e5
}

.guild-settings-modal-members
.guild-settings-modal-members-footer .help-text {
color:#ccc
}

/* Server Emojis */

.guild-settings-modal-emoji .table-header {
color:#ccc
}

.guild-settings-modal-emoji .guild-settings-modal-emoji-header h6 {
color:#e5e5e5;
border-bottom:none!important
}

.guild-settings-modal-emoji .guild-settings-modal-emoji-header {
border-bottom:none!important
}

.guild-settings-modal-emoji .guild-settings-modal-emoji-header p {
color:#ccc
}

.guild-settings-modal-emoji .no-emoji p {
color:#ccc
}

.guild-settings-modal-emoji .emoji-row {
border-bottom:none
}

.guild-settings-modal-emoji .emoji-uploader .emoji-uploader-avatar {
border-radius:0
}

.guild-settings-modal-emoji .emoji-uploader .emoji-uploader-username {
color:#e5e5e5
}

.guild-settings-modal-emoji .emoji-row .emoji-name {
background:#232323;
color:#e5e5e5
}

.guild-settings-modal-emoji .emoji-row:hover .emoji-name {
background:#232323!important;
border:1px solid #232323!important;
}

.guild-settings-modal .emoji-row .btn.btn-danger, .guild-settings-modal .member-buttons .btn.btn-danger {
background:#232323;
border:none;
color:#e5e5e5
}

.guild-settings-modal .emoji-row .btn.btn-danger:hover {
background:#900
}

/*---------------*/
.search-bar.search-bar-light input {
background:#232323;
border-radius:0!important;
height:34px;
color:#e5e5e5
}

.search-bar.search-bar-light input::-webkit-input-placeholder {
color:#e5e5e5!important
}

.search-bar.search-bar-light .search-bar-inner {
border:none!important;
background-color:#232323;
border-radius:0!important;
padding-bottom:0px;
padding-top:0px
}

.search-bar-clear.active {
background:#232323
}

.form .btn-primary {
background-color:#232323
}

.form .btn-primary:hover {
background-color:#900
}

.user-settings-modal a {
color:#b2b2b2
}

.user-settings-modal a:hover {
color:#e5e5e5
}

.channel-notification-settings .content .content-inner {
background:transparent!important
}

.callout-backdrop {
opacity:0.55
}

.tab-bar.SIDE .tab-bar-header {
box-shadow:none
}

.tab-bar.SIDE {
margin-right:0;
background-color:rgba(35,35,35,1);
border-right:6px solid #900;
border-radius:0px
}

.tab-bar.SIDE .tab-bar-item {
color:#ccc
}

.tab-bar.SIDE .tab-bar-item.selected {
background:none!important
}

.tab-bar.SIDE .tab-bar-item:before {
border-left:4px solid #900
}

.tab-bar.SIDE .tab-bar-item:hover:before {
border:none
}

.slider-handle,.Select-control {
border:none!important
}

.settings .settings-header {
background:rgba(35,35,35,1)!important
}

#settings-roles h1 {
color:#e5e5e5
}

.settings .settings-inner,.settings .settings-actions {
background:#191919;
border-left:#900 solid 0
}

.settings .settings-actions {
border-top:none!important
}

.settings .settings-actions .btn-confirm:not(.reverse-slide) .btn:first-of-type:hover {
background-color:#900
}

.settings .settings-actions .btn-confirm:not(.reverse-slide) .btn:first-of-type {
background-color:#232323
}

.settings .settings-actions .btn-confirm:not(.reverse-slide).active .btn:last-of-type:not(:first-of-type) {
background:#232323
}

.settings .settings-actions .btn-confirm:not(.reverse-slide).active .btn:last-of-type:not(:first-of-type):hover {
background:#900
}

#settings-roles .roles header h1 {
color:#e5e5e5
}

#settings-roles-pro-tip .pro-tip {
color:#e5e5e5
}

#settings-roles-pro-tip {
color:#b2b2b2
}

.form .radio-group .radio,.form .checkbox-group .checkbox,.checkbox .checkbox-inner+span {
color:#ccc!important
}

.form .control-group input[type=email],.form .control-group input[type=password],.form .control-group input[type=text] {
padding:5px 10px;
border-radius:0;
box-sizing:border-box;
border:0 solid #232323!important;
background:#232323!important;
color:#e5e5e5;
font-size:18px
}

.form .control-group textarea {
background:#232323!important;
box-sizing:border-box;
border:0 solid #232323!important;
color:#e5e5e5;
border-radius:0;
font-size:18px;
padding:5px 10px
}

.region-select .region-select-inner {
background-color:#232323;
border:0;
border-radius:0
}

.region-select-name {
color:#e5e5e5
}

.region-select button {
color:#e5e5e5;
background-color:#343434;
border:0;
border-radius:0
}

.region-select:hover button {
background-color:#900
}

.region-select-modal {
background-color:#191919
}

.region-select-modal .region-select-modal-option {
background-color:#232323;
border:0
}

.region-select-modal .region-select-modal-footer {
color:#ccc
}

.region-select-modal .region-select-modal-header {
color:#e5e5e5
}

.create-guild-container p {
color:#ccc
}

.create-guild-container h5 {
color:#e5e5e5
}

.create-guild-container .action.join .btn {
background-color:#343434;
color:#e5e5e5
}

.create-guild-container .action.join:hover .btn {
background-color:#900!important
}

.create-guild-container .action .action-body {
color:#b2b2b2
}

.create-guild-container .action.join .action-header {
color:#ccc
}

.create-guild-container .action.create .btn-primary {
background-color:#343434!important
}

.create-guild-container .create-or-join header {
color:#e5e5e5
}

.create-guild-container .join-server h5 {
color:#e5e5e5
}

.create-guild-container .join-server p {
color:#b2b2b2
}

.create-guild-container .join-server .btn-primary:hover {
background-color:#900
}

.create-guild-container .join-server .btn-primary {
background-color:#232323
}

.create-guild-container .join-server .link-container label {
color:#ccc
}

.create-guild-container .form-actions .btn-default {
color:#e5e5e5
}

.avatar-uploader small {
color:#ccc
}

.avatar-uploader small strong {
font-weight:400;
color:#e5e5e5
}

.form .btn:disabled {
background:#232323
}

.form .btn:disabled:hover {
background:#232323
}

.form .btn-default {
padding:10px 0!important;
width:90px;
height:50px;
border-radius:3px;
border-bottom:0;
background-color:#232323;
color:#e5e5e5
}

.form .btn-default:hover {
-webkit-transition:background-color .2s ease;
background-color:#900;
border:none
}

.form hr,.form .control-groups.control-separator,.instant-invites .instant-invites-header,.guild-settings-modal-integrations .guild-settings-modal-integrations-header,.guild-settings-modal-members .guild-settings-modal-members-header,.guild-settings-modal-members .guild-settings-modal-list .member+.member,.guild-settings-modal-members .guild-settings-modal-members-footer,#settings-roles .roles header,#user-profile-modal .tab-bar {
border-color:rgba(255,255,255,0);
box-shadow:none
}

.form .control-group input[type=email]:disabled,.form .control-group input[type=password]:disabled,.form .control-group input[type=text]:disabled,.form .control-group textarea:disabled {
background:#666!important;
opacity:.25
}

.alert.form.has-icon:before {
display:none
}

.alert.form .form-inner h4 {
color:#e5e5e5;
margin-top:-40px;
margin-bottom:20px
}

.alert.form .form-inner p {
color:#ccc;
margin-bottom:10px
}

.alert.form .form-inner .cancel {
background:#232323;
border:none;
color:#e5e5e5
}

.alert.form .form-inner .cancel:hover {
background:#900;
color:#fff
}

.alert.form .form-inner .btn {
border:none;
color:#e5e5e5
}

.alert.form .form-inner .btn-close-forever {
color:#b2b2b2
}

.guild-settings-modal-members {
background:none!important
}

#settings-roles .roles li.draggable {
margin-left:6px
}

#settings-roles .roles li.sorting:after {
border:2px solid #900
}

#settings-roles .roles li {
margin-left:6px;
color:#e5e5e5
}

#settings-roles .roles li .lock {
background-image:url(https://i.imgur.com/CgPGTlg.png);
background-size:15px 15px
}

#settings-roles .roles li .avatar-small {
border-radius:0;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000
}

#settings-roles .roles {
border-right:none
}

#settings-roles .roles li:hover:before {
background:none
}

#settings-roles .roles li:hover:not(.selected) {
background:rgba(35,35,35,.50)!important;
width:105px;
margin-left:6px
}

#settings-roles .roles li.selected {
background:#232323!important;
width:105px;
margin-left:6px
}

#settings-roles .roles li.selected:before {
background:none
}

#settings-roles .selected-role .btn-confirm:not(.reverse-slide) .btn:first-of-type:hover {
background-color:#900!important
}

#settings-roles .selected-role .btn-confirm:not(.reverse-slide) .btn:first-of-type {
background-color:#232323!important
}

#settings-roles .selected-role .btn-confirm:not(.reverse-slide).active .btn:last-of-type:not(:first-of-type) {
background:#232323
}

#settings-roles .selected-role .btn-confirm:not(.reverse-slide).active .btn:last-of-type:not(:first-of-type):hover {
background:#900
}

.btn-help {
font-size:15px;
background:#191919
}

.btn-help:hover,.radio:hover span:after {
background:#232323
}

.btn-confirm .btn:first-of-type {
background-color:#232323
}

.btn-confirm .btn:first-of-type:hover {
background-color:#900
}

.btn-confirm.active .btn:last-of-type:not(:first-of-type) {
background-color:#232323
}

.btn-confirm.active .btn:last-of-type:not(:first-of-type):hover {
background-color:#900
}

.btn-confirm.active .btn {
background-color:#900
}

.form .btn.green {
color:#e5e5e5;
background:#232323
}

.form .btn.green:hover {
background:#900;
color:#e5e5e5
}

.user-settings-modal-security .btn-ghost {
color:#e5e5e5;
background:#232323;
border:none
}

.user-settings-modal-security .btn-ghost:hover {
background-color:#900
}

.user-settings-modal-security .mfa-group .mfa-active {
color:#e5e5e5
}

.user-settings-modal-security .mfa-group .lock-icon {
display:none
}

.user-settings-modal-security p {
color:#ccc
}

.user-settings-modal-security.show-art {
background:none
}

.user-settings-modal-security .backup-codes p {
color:#ccc
}

.user-settings-modal-security .backup-codes p strong {
color:#ccc
}

.user-settings-modal-security .backup-codes .code {
color:#b2b2b2
}

.mfa-modal .mfa-step {
border-bottom:none
}

.mfa-modal .form-inner p {
color:#ccc!important
}

.user-settings-modal .link-button {
color:#b2b2b2
}

.user-settings-modal .link-button:hover {
color:#ccc
}

.radio .radio-inner span:after {
background:#666;
border-radius:5px
}

.radio .radio-inner {
background:#232323;
border-radius:10px;
border:0
}

.radio-theme input[type=radio]:checked~label {
border:4px solid #666;
}

.radio-theme.dark label:not(.selected) {
border:none
}

.radio-theme.light label:not(.selected) {
border:none
}

.user-settings-modal .voice-settings .reset-voice-settings {
color:#b2b2b2
}

.user-settings-modal .voice-settings .reset-voice-settings:hover {
color:#e5e5e5;
opacity:1
}

.user-settings-modal-keybinds .user-settings-modal-keybinds-header {
border-bottom:none
}

.user-settings-modal-keybinds .user-settings-modal-keybinds-header .btn-add-keybind {
background:#232323
}

.user-settings-modal-keybinds .user-settings-modal-keybinds-header .btn-add-keybind:hover {
background:#900
}

.user-settings-modal-keybinds .user-settings-modal-keybinds-list .keybind .btn-confirm:not(.reverse-slide) .btn:first-of-type:hover {
background-color:#900!important
}

.user-settings-modal-connections .user-settings-modal-accounts-list .connect-container .name {
color:#e5e5e5
}

.user-settings-modal-connections .user-settings-modal-accounts-list .connect-container .btn {
border:none;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
border-radius:0
}

.user-settings-modal-connections .user-settings-modal-accounts-list .connect-container.disabled .btn {
background-repeat:no-repeat;
background-position:50%;
background-size:auto
}

.user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-integrations.no-integrations {
color:#ccc!important;
background:#232323;
box-shadow:none
}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-accounts-list .btn {
box-shadow:none
}

.user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-integrations {
border:none!important
}

.user-settings-modal-connections .user-settings-modal-connections-list {
box-shadow:none!important
}

.user-settings-modal-connections .user-settings-modal-connections-header label {
color:#e5e5e5
}

.settings-connections-wrapper .authed-app {
background:#232323;
border:none;
box-shadow:none
}

.settings-connections-wrapper .authed-app .header .header-actions .action-btn {
background:#191919
}

.settings-connections-wrapper .authed-app .header .header-actions .action-btn:hover {
background:#900!important
}

.settings-connections-wrapper .authed-app .header .app-name {
color:#e5e5e5
}

.settings-connections-wrapper .authed-app .details .header {
color:#ccc
}

.settings-connections-wrapper .authed-app .details .body {
color:#b2b2b2
}

.settings-connections-wrapper .authed-app .details .body li {
color:#b2b2b2
}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-divider {
display:none
}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-accounts-list h3 {
color:#e5e5e5
}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-accounts-list .user-settings-modal-accounts-list-description .user-settings-modal-accounts-list-description-inner.warning {
color:#b2b2b2
}

.connect-account-btn .connect-account-btn-inner {
border:none
}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-options .connection-option .checkbox .checkbox-inner.alt input[type=checkbox]+span {
background:#383838
}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-options .connection-option .checkbox .checkbox-inner.alt input[type=checkbox]:checked+span {
background:#900
}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-options .connection-option .checkbox .checkbox-inner.alt input[type=checkbox]:checked+span:after {
background:#e5e5e5
}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-header .btn-delete {
background:#191919;
border:none
}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-header .btn-delete:hover {
background:#900!important
}

.connect-account-btn .connect-account-btn-inner:hover {
background-color:#232323
}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-accounts-list .user-settings-modal-accounts-list-description .user-settings-modal-accounts-list-description-inner {
color:#b2b2b2!important
}

.user-settings-modal-keybinds
.user-settings-modal-keybinds-header {
border-bottom:0 #232323 solid
}

.user-settings-modal .account-warning {
background:#232323!important;
color:#e5e5e5!important;
border:none!important
}

.user-settings-locale p {
color:#b2b2b2
}

.tab-bar.TOP {
border:0 solid #232323
}

.tab-bar.TOP .tab-bar-item {
color:#b2b2b2
}

.tab-bar.TOP .tab-bar-item:hover {
color:#ccc;
border:none
}

.tab-bar.TOP .tab-bar-item.selected {
border:none;
color:#e5e5e5
}

.markdown-modal .markdown-modal-footer {
border-top:6px solid #900;
color:#ccc
}

.markdown-modal ul li {
color:#b2b2b2
}

.markdown-modal strong {
color:#ccc
}

.change-log.markdown-modal code.inline {
background:#232323;
border-radius:0
}

.change-log-button-container:before {
display:none
}

.change-log-button-container .change-log-button {
margin-top:-15px
}

#overlay-explanation {
background:#232323;
color:#e5e5e5;
margin-bottom:21px
}

.user-settings-streamer-mode {
background:none
}

.user-settings-modal-games {
background:#191919!important;
border:solid #900 0!important;
box-shadow:none
}

.user-settings-modal-games .games-table .games-row .item-game,.user-settings-modal-games .games-table .games-row .item-overlay {
border-color:#191919!important
}

.user-settings-modal-games .games-table .games-row .item-game .game-input,.user-settings-modal-games .games-table .games-row .item-game .game-name {
color:#e5e5e5
}

.user-settings-modal-games .games-table .games-row .item-game .icon {
background:url(https://imgur.com/TdP6eOM.png);
background-position:center;
background-size:15px 20px
}

.user-settings-modal-games .games-table .games-row .item-game .game-input:focus,
.user-settings-modal-games .games-table .games-row .item-game .game-input:hover {
border-radius:0;
border-color:#383838;
background-color:#232323
}

.user-settings-modal-games .games-table .games-row .item-game .last-played {
color:#ccc
}

.user-settings-modal-connections .user-settings-modal-accounts-list .connect-container .count {
color:#b2b2b2
}

.user-settings-modal-connections .user-settings-modal-accounts-list .connect-container.disabled .count {
color:#b2b2b2
}

.now-playing.no-detection {
background:#232323
}

.now-playing.no-detection {
border:0
}

.now-playing {
background-color:#232323;
border:1px solid;
animation-name:pulse;
animation-duration:1.5s;
animation-direction:alternate;
border-radius:0
}

@keyframes pulse {
100%{border-color:#e5e5e5}
50%{border-color:#191919}
}

.now-playing-add {
color:#b2b2b2
}

.now-playing-add .link {
color:#ccc
}

div.now-playing-add span.link:hover {
color:#e5e5e5!important
}
/*----------MADE BY BEARD DESIGN----------*/
.checkbox .checkbox-inner input[type=checkbox]:checked+span:after {
background:#e5e5e5;
top:-1px;
border-right:0px;
border-bottom:0px;
transform:translate(10px,0px);
box-shadow:0px 2px 3px rgba(0,0,0,0.4)
}

.checkbox .checkbox-inner input[type=checkbox]:checked+span {
background:#900;
border:0px;
height:14px;
width:30px;
top:0px;
border-radius:0px;
margin-left:0px!important
}

.checkbox .checkbox-inner.alt input[type=checkbox]+span {
background:#191919;
border:none
}

.checkbox .checkbox-inner.alt input[type=checkbox]:checked+span {
background:#900
}

.checkbox .checkbox-inner input[type=checkbox]:disabled+span {
background:#333
}

.now-playing .checkbox .checkbox-inner input[type=checkbox]:disabled+span {
background:#000
}

.checkbox .checkbox-inner input[type=checkbox]:checked:disabled+span {
background:#333
}

.checkbox .checkbox-inner:disabled+span {
background:#333
}

.checkbox .checkbox-inner span {
top:0px;
height:14px;
width:30px;
border-radius:0px;
border:0px;
background:#232323;
margin-left:0px!important
}

.checkbox .checkbox-inner+span {
margin-left:18px!important
}

.checkbox .checkbox-inner span:after {
content:"";
position:absolute;
background:#666;
transform:rotate(0deg)translate(0px,0px);
height:16px!important;
width:16px!important;
top:-1px;
border-radius:0px;
border-right:0px;
border-bottom:0px;
transition:all 200ms ease;
box-shadow:0px 2px 3px rgba(0,0,0,0.3)
}

/*-------------------------------------------*/

.bd-g-table tbody tr,.bd-g-table thead th,.bd-g-table tbody tr:nth-child(odd) {
background:#232323!important
}

.bd-g-table textarea {
color:#e5e5e5!important;
background:#e5e5e5!important;
padding:10px!important;
box-sizing:border-box
}

#bd-pane .scroller-wrap div[style*="background:#2E3136; color:#ADADAD; height:30px; position:absolute; bottom:0; left:0; right:0;"] {
background:#191919!important
}

.CodeMirror {
background:#232323!important;
border-radius:0;
color:#b2b2b2!important
}

.CodeMirror-gutters {
background:#191919!important;
border:none!important
}

.CodeMirror-linenumber {
color:#b2b2b2!important
}

.CodeMirror > ::-webkit-scrollbar-thumb {
background-color:#232323;
background-clip:padding-box;
border:1px solid #191919;
border-radius:0px
}

.CodeMirror > ::-webkit-scrollbar,
.CodeMirror > ::-webkit-scrollbar-track {
background:#191919;
width:14px
}

.CodeMirror > ::-webkit-scrollbar-track-piece {
background-color:#191919;
background-clip:padding-box;
border:2px solid #191919;
border-radius:0px
}

.CodeMirror-scrollbar-filler {
background:#191919
}

.cm-s-neat span.cm-builtin {
color:#ff6666
}

.cm-s-neat span.cm-atom,.cm-s-neat span.cm-number {
color:green
}

.cm-s-neat span.cm-keyword {
color:#ff6666
}

.cm-s-neat span.cm-meta {
color:#0080ff
}

.cm-s-neat span.cm-variable {
color:#0080ff
}

.cm-s-neat span.cm-string {
color:#0080ff
}

.member-roles .member-role {
background-color:#232323;
border:0 solid #000;
padding:2px 4px;
color:#fff;
margin:2.5px
}

#permissions .permission-actions span {
color:#ccc!important
}

#permissions .permission-actions {
color:#ccc
}

#autocomplete-popout .empty h4 {
color:#e5e5e5
}

#permissions .permissions-helpdesk,.guild-settings-modal-members .guild-settings-modal-members-footer a {
color:#999
}

#permissions .permissions-helpdesk:hover,.guild-settings-modal-members .guild-settings-modal-members-footer a:hover {
color:#e5e5e5
}

#user-profile-modal .header {
background:#191919;
border-bottom:6px solid #900
}

#user-profile-modal .btn {
background:#232323
}

#user-profile-modal .btn:hover {
background:#900
}

#user-profile-modal .sub-header,#user-profile-modal .tab-bar,#user-profile-modal .scroller,#user-profile-modal .empty,#user-profile-modal footer {
background:#191919!important
}

#user-profile-modal .guilds .guild:hover {
background:#232323!important;
color:#e5e5e5
}

#user-profile-modal .avatar-profile {
border:hidden;
background-color:rgba(0,0,0,0);
border-radius:0px;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000
}

#user-profile-modal .guilds .avatar-large {
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
border-radius:0px
}

#user-profile-modal .guilds .guild .guild-nick {
color:#b2b2b2
}

#user-profile-modal .avatar-profile .status {
box-shadow:none;
border:4px solid #191919
}

#user-profile-modal .guilds .guild .status {
border-color:#191919
}

#user-profile-modal .guilds .guild:hover .status {
border-color:#191919
}

#user-profile-modal .tab-bar-container {
background:#191919;
border:none
}

#user-profile-modal .guilds .section .section-header {
color:#e5e5e5
}

#user-profile-modal .guilds .section+.section {
border:none
}

#user-profile-modal .guilds .section .connected-account .connected-account-name {
color:#ccc
}

/* New User Profile Modal */

#user-profile-modal .guilds .section .connected-accounts .connected-account {
border:none;
background:#232323
}

#user-profile-modal .guilds .section .connected-accounts .connected-account .connected-account-name-inner .connected-account-name {
color:#e5e5e5
}

#user-profile-modal .guilds .section .connected-accounts .connected-account a .connected-account-open-icon {
background:url(https://imgur.com/Mgd1QEP.png);
background-size:18px 18px
}

#user-profile-modal .guilds .section .connected-accounts .connected-account .connected-account-name-inner .connected-account-verified-icon {
background:url(https://imgur.com/TdP6eOM.png);
background-position:center;
background-size:16px 21px
}

#user-profile-modal .header .header-info .badge-premium {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.75
}

#user-profile-modal .header .header-info .header-info-inner .discord-tag .username {
color:#e5e5e5
}

#user-profile-modal .header .header-info .header-info-inner .discord-tag .discriminator {
color:#e5e5e5
}

#user-profile-modal .actions .btn {
background:#232323!important
}

#user-profile-modal .actions .btn:hover {
background:#900!important
}

#user-profile-modal .header .header-info .header-info-inner .activity {
color:#b2b2b2;
text-indent:-42px
}

#user-profile-modal .tab-bar .tab-bar-item.selected {
color:#e5e5e5
}

#user-profile-modal .tab-bar .tab-bar-item {
color:#b2b2b2
}

#user-profile-modal .header:after {
display:none
}

/* --- */

.theme-dark .header-toolbar .separator {
background:none;
margin-left:0
}

#bd-customcss-attach-controls {
background:#191919;
border:none;
box-shadow:none;
padding:5px 10px 10px
}

#bd-customcss-attach-controls .checkbox > span {
font-size:14px;
margin-right:8px;
margin-left:7px
}

#bd-customcss-detach-container #bd-customcss-detach-controls-buttons button {
background:#232323
}

#bd-customcss-detach-container #bd-customcss-detach-controls-buttons button:hover {
background:#900
}

#bd-customcss-detach-container {
background:#191919
}

.bda-slist li {
background:#191919;
border:none;
margin-bottom:35px!important
}

.bda-slist li:nth-child(odd) {
background:#191919;
border:none
}

.bda-slist .bda-description {
border:none;
color:#b2b2b2
}

.bda-slist .bda-name {
color:#e5e5e5
}

.bda-slist .checkbox:before {
color:#b2b2b2
}

.bda-slist .bda-right {
margin-top:-100px
}

.bda-slist .bda-right .bda-plugin-reload {
background:#232323
}

#bd-themes-pane .bda-plugin-reload {
margin-top:35px
}

.bda-slist .bda-right .bda-plugin-settings {
background:#232323
}

.bda-slist .bda-right .bda-plugin-settings:hover {
background:#900
}

.bda-slist .bda-right .bda-plugin-reload:hover {
background:#900
}

/* Even Better Repo Plugin CSS */

#theme-search, #plugin-search {
background:#232323!important;
border:1px solid #191919!important;
color:#e5e5e5
}

.ebr-plugin-item, .ebr-theme-item {
background:#232323!important;
border:none!important;
border-radius:0!important
}

#theme-search:focus, #plugin-search:focus {
border:1px solid #191919!important;
box-shadow:none!important;
outline:none!important
}

.install-button {
background:#555!important
}

.update-button {
background:#900!important
}

.view-source-button {
background:#383838!important
}

.ebr-themes p.description, .ebr-plugins p.description {
color:#ccc!important
}

/* Detected Connections */

.detected-platform-accounts-modal {
background:#191919;
height:375px;
border-radius:6px
}

.detected-platform-accounts-modal .privacy {
bottom:0;
width:450px;
left:0;
position:relative;
margin-top:3px
}

.detected-platform-accounts-modal .divider {
border-top:6px solid #900;
width:450px;
opacity:1;
height:0
}

.input-switch input:checked+.input-switch-slider:before {
border-radius:0;
border:none;
height:20px;
width:20px;
position:absolute;
left:0px;
top:-3px
}

.input-switch .input-switch-slider:before {
border-radius:0;
border:none;
height:20px;
width:20px;
position:absolute;
left:0px;
top:-3px
}

.input-switch input:checked+.input-switch-slider {
border-radius:0;
border:2px solid #191919;
background:#900;
height:15px;
width:20px
}

.input-switch .input-switch-slider {
border-radius:0;
border:2px solid #191919;
background:#232323;
height:15px;
width:40px
}

.detected-platform-accounts-modal .btn-group .btn-primary {
background:#232323
}

.detected-platform-accounts-modal .btn-group .btn-primary:hover {
background:#900!important
}

/* KEYBOARD SHORTCUTS */

.keyboard-shortcuts-modal {
background:#191919
}

.keyboard-shortcuts-modal .modal-subtitle {
border-bottom:6px solid #900;
color:#ccc
}

.keybind-shortcut span {
box-shadow:inset 0 -4px 0 #666;
border:1px solid #666;
color:#ccc
}

.keybind-shortcut span:active {
background-color:#191919!important;
border:solid 1px #666!important;
box-shadow:inset 0 -4px 0 #666!important;
color:#ccc
}

.keyboard-shortcuts-modal .modal-title .content {
color:#e5e5e5
}

.keyboard-shortcuts-modal .modal-title .keybind-shortcut span {
background:#191919!important;
border:solid 1px #666!important;
box-shadow:inset 0 -4px 0 #666!important
}

.keyboard-shortcuts-modal .keyboard-shortcut-list .keybind-group .keybind-description {
color:#b2b2b2
}

.keyboard-shortcuts-modal .keyboard-shortcut-list .keybind-group .bind-arrow {
content:url(https://i.imgur.com/IRzpP3m.png)
}

.keyboard-shortcuts-modal .scroller-wrap .scroller::-webkit-scrollbar-thumb {
background:#383838!important;
border:1px solid transparent!important;
background-clip:content-box!important
}
/* Webhooks */

.webhooks .webhooks-header {
border-bottom:none
}

.webhooks .webhook {
background:#232323
}

.webhooks .webhook .webhook-header .avatar-large {
border-radius:0!important;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000
}

.webhooks .webhook .webhook-header .webhook-details .webhook-name {
color:#e5e5e5
}

.webhooks .webhook .webhook-header .webhook-details .webhook-created-on {
color:#ccc;
position:absolute
}

.webhooks .webhook .webhook-header .webhook-actions .btn-clear {
background:#191919!important;
color:#ccc
}

.webhooks .webhook .webhook-header .webhook-actions .btn-clear:hover {
background:#900!important;
color:#e5e5e5
}

.webhooks .webhooks-header button.btn.btn-primary.green {
positio:relative!important;
botto:-530px!important;
z-index:1
}

.webhooks .webhook .webhook-config input#webhook-name {
background:#191919!important;
margin-top:11px
}

.webhooks .webhook .webhook-config div.Select-placeholder {
background:#191919!important
}

.webhooks .webhook .webhook-config .Select-menu-outer {
background:#191919;
overflow-y:auto;
max-height:125px
}

.webhooks .webhook .webhook-config .Select-menu-outer::-webkit-scrollbar {
background:none
}

.webhooks .webhook .webhook-config .Select-menu-outer::-webkit-scrollbar-thumb {
background:#383838;
border:2px solid transparent;
background-clip:content-box
}

.webhooks .webhook .webhook-config .Select-menu {
overflow-y:hidden
}

.webhooks .webhook .webhook-config input {
background:#191919!important
}

.webhooks .webhook .webhook-config button.copy.flash.icon {
background-color:#191919
}

.webhooks .webhook .webhook-config button.copy.flash.icon:hover {
background-color:#383838
}

.webhooks .webhook .webhook-header .webhook-actions .btn-confirm {
background:#191919!important
}

.webhooks .webhook .webhook-header .webhook-actions .btn-default {
background:#191919;
}

.webhooks .webhook .webhook-header .webhook-actions .btn-default:hover {
background:#900!important
}

.webhooks .webhook .webhook-header .webhook-actions .btn.green {
background:#191919;
position:relative;
top:-2px
}

.webhooks .webhook .webhook-header .webhook-actions .btn.green:hover {
background:#900!important
}

.webhooks .webhook .webhook-header .webhook-actions .btn-confirm.reverse-slide .btn:last-of-type:not(:first-of-type):hover {
background-color:#900!important
}

.webhooks .webhook .webhook-header .webhook-actions .btn-confirm.reverse-slide.active .btn:first-of-type {
background:#191919
}

.webhooks .webhook .webhook-header .webhook-actions .btn-confirm.reverse-slide.active .btn:first-of-type:hover {
background:#900!important
}

.webhooks .webhook .webhook-header .webhook-actions .btn-confirm.active .btn:last-of-type:not(:first-of-type) {
background-color:#191919
}

.webhooks .webhook .webhook-header .webhook-actions .btn-confirm.active .btn:last-of-type:not(:first-of-type):hover {
background-color:#900!important
}

/* Notices and Streamer mode */

.notice.notice-info {
background:#232323
}

.notice .btn {
background:#191919;
border:none;
color:#ccc
}

.notice .btn:hover {
background:#900;
color:#e5e5e5!important
}

.notice.notice-streamer-mode {
background:#232323
}

.streamer-mode-enabled .streamer-mode-enabled-btn,.streamer-mode-enabled .streamer-mode-enabled-btn.disabled {
background:#232323
}

.streamer-mode-enabled .streamer-mode-enabled-btn:hover,.streamer-mode-enabled .streamer-mode-enabled-btn.disabled:hover {
background:#900
}

.streamer-mode-enabled .streamer-mode-enabled-image {
opacity:.1
}

/*

 __   __     _            ___        _
 \ \ / /___ (_) __  ___  |   \  ___ | |__  _  _  __ _
  \ V // _ \| |/ _|/ -_) | |) |/ -_)| '_ \| || |/ _` |
   \_/ \___/|_|\__|\___| |___/ \___||_.__/ \_,_|\__, |
                                                |___/
*/
.form .control-groups .control-group {
color:#b2b2b2
}

.form .control-group label {
color:#ccc
}

.form .control-group .help-text {
color:#999
}

.form .control-groups label {
color:#ccc
}

.settings .settings-inner .settings-panel {
color:#e5e5e5
}

#rtc-debug-modal #users-section .user-list {
border-right:none
}

#rtc-debug-modal #users-section .selected-user {
color:#e5e5e5;
border-left:none!important
}

#rtc-debug-modal #users-section .user-list li.selected {
background:#232323;
color:#e5e5e5;
margin-left:6px
}

#rtc-debug-modal #users-section .user-list li {
background:#191919;
color:#b2b2b2;
margin-left:6px
}

#rtc-debug-modal #users-section .user-list .avatar-small {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000
}

#rtc-debug-modal #users-section .user-list li:not(.selected):hover {
background:rgba(35,35,35,.50);
color:#e5e5e5;
margin-left:6px
}

#rtc-debug-modal #users-section .user-list li.selected:before {
background:none
}

#rtc-debug-modal #users-section .user-list li:hover:not(.selected):before {
background:none
}

#rtc-debug-modal #users-section .user-list li:not(.selected):before {
background:#191919
}

#rtc-connection-popout .debug-button {
color:#e5e5e5
}

#rtc-connection-popout .secured {
color:#e5e5e5
}

#rtc-connection-popout section p {
color:#b2b2b2
}

#rtc-connection-popout hr {
border:hidden
}

/*
             _     _ _        _     _     _
 _ __  _   _| |__ | (_) ___  | |   (_)___| |_
| '_ \| | | | '_ \| | |/ __| | |   | / __| __|
| |_) | |_| | |_) | | | (__  | |___| \__ \ |_
| .__/ \__,_|_.__/|_|_|\___| |_____|_|___/\__|
|_|

*/
#slist,#pubs-container {
background-color:#191919!important;
border-radius:5px 5px 0 0;
border:hidden
}

#pubs-header {
padding:10px;
background-color:#232323!important;
border-radius:5px 5px 0 0;
border:none
}

#pubs-header input {
padding-left:10px;
background:#191919
}

#pubs-header button {
background:#191919;
border-right:3px solid #232323
}

#pubs-searchbtn {
background:#191919!important;
border-left:3px solid #232323;
font-size:14px
}

#pubs-searchbtn:hover {
background:#900!important;
color:#ccc
}

.bd-dropdown-list ul li {
background:#232323!important;
color:#e5e5e5
}

#pubs-footer {
padding:10px;
font-size:12px;
background:#232323!important;
border-radius:0 0 5px 5px
}

.server-name span {
color:#ccc
}

.server-tags {
color:#b2b2b2!important
}

.server-icon {
width:50px;
height:50px;
border-radius:100%
}

.server-row {
padding:10px 10px 8px
}

.server-info {
line-height:50px
}

.server-info span {
color:#ccc
}

.server-info button {
background-color:#232323!important;
width:70px;
height:40px;
margin-top:4px;
margin-right:4px
}

.server-info button:hover {
background-color:#900!important
}

#slist span {
color:#ccc!important
}

.server-row:nth-child(2n+1) {
background-color:#191919!important;
border:none
}

.server-row:nth-child(2n+2) {
background-color:#191919!important
}

/*
  _____
 |_   _|
   | |  ___ ___  _ __  ___
   | | / __/ _ \| '_ \/ __|
  _| || (_| (_) | | | \__ \
 |_____\___\___/|_| |_|___/

*/

.account .btn-settings:after {
background-image:url(https://i.imgur.com/rI8942r.png)!important;
opacity:.5!important
}

.account .btn-settings:hover:after {
opacity:1!important
}

.account .btn-mute:after {
background-image:url(https://i.imgur.com/ovju27H.png)!important;
opacity:.5
}

.account .btn-mute:hover:after {
background-image:url(https://i.imgur.com/66RcXXp.png)!important;
opacity:1!important;
-moz-transform:scaleX(-1);
-o-transform:scaleX(-1);
-webkit-transform:scaleX(-1);
transform:scaleX(-1);
filter:FlipV;
-ms-filter:"FlipV"
}

.account .btn-mute.disabled:after {
background-image:url(https://i.imgur.com/66RcXXp.png)!important;
opacity:1!important;
-moz-transform:scaleX(-1);
-o-transform:scaleX(-1);
-webkit-transform:scaleX(-1);
transform:scaleX(-1);
filter:FlipV;
-ms-filter:"FlipV"
}

.account .btn-deafen:after {
background-image:url(https://i.imgur.com/m1B6ZX1.png)!important;
opacity:.5
}

.account .btn-deafen:hover:after {
background-image:url(https://i.imgur.com/quqY44n.png)!important;
opacity:1
}

.account .btn-deafen.disabled:after {
background-image:url(https://i.imgur.com/quqY44n.png)!important;
opacity:1
}

#rtc-connection .btn-info:after {
background-image:url(https://i.imgur.com/XrnhT3o.png);
background-size:22px 22px
}

#rtc-connection .btn-disconnect:after {
background-image:url(https://i.imgur.com/Q0yl9MW.png);
background-size:25px 25px
}

#rtc-connection-popout .secured:before {
background-image:url(https://i.imgur.com/CgPGTlg.png);
background-size:11px 11px
}

.message-group .btn-option.popout-open, .message-group .comment>div:hover .btn-option {
background-image:url(https://i.imgur.com/rI8942r.png)!important;
background-size:16px 16px!important;
opacity:.5!important;
}

.header-toolbar button span[style*='background-image: url("/assets/093cd423e728025709a8fc032bb43df0.svg");'] {
background-image:url(https://i.imgur.com/Q0yl9MW.png)!important;
transform:rotate(225deg)!important
}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPgogIDxkZWZzPgogICAgPHBhdGggaWQ9ImEiIGQ9Ik04IDJWMEgxLjc3Nzc3Nzc4Qy43OTU5MzgyMiAwIDAgLjc5NTkzODIyIDAgMS43Nzc3Nzc3OFYxNC4yMjIyMjIyQzAgMTUuMjA0MDYxOC43OTU5MzgyMiAxNiAxLjc3Nzc3Nzc4IDE2SDE0LjIyMjIyMjJDMTUuMiAxNiAxNiAxNS4yMDg4ODg5IDE2IDE0LjIyMjIyMjJWOGgtMnY2SDJWMmg2eiIvPgogICAgPG1hc2sgaWQ9ImIiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgeD0iMCIgeT0iMCIgZmlsbD0iI2ZmZiI+CiAgICAgIDx1c2UgeGxpbms6aHJlZj0iI2EiLz4KICAgIDwvbWFzaz4KICA8L2RlZnM+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0wIDBoMjR2MjRIMHoiLz4KICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQgNCkiPgogICAgICA8dXNlIHN0cm9rZT0iI0ZGRiIgc3Ryb2tlLXdpZHRoPSIyIiBtYXNrPSJ1cmwoI2IpIiB4bGluazpocmVmPSIjYSIvPgogICAgICA8cGF0aCBmaWxsPSIjRkZGIiBkPSJNNiA4LjE1NDk0ODVsNS40Mjc2NzU4LTUuNDI3Njc1NzcgMS44NDUwNTE1IDEuODQ1MDUxNUw3Ljg0NTA1MTUgMTBINlY4LjE1NDk0ODV6bTkuODYwMDMxMS02LjI3NTk3MjFsLS44NDgyOTYzLjg0ODI5NjMzLTEuNzM5MDA3NS0xLjczOTAwNzUuODQ4Mjk2My0uODQ4Mjk2MzNjLjE3ODE0MjItLjE4NjYyNTIuNDc1MDQ2LS4xODY2MjUyLjY1MzE4ODIgMGwxLjA4NTgxOTMgMS4wODU4MTkzYy4xODY2MjUyLjE3ODE0MjI0LjE4NjYyNTIuNDc1MDQ1OTYgMCAuNjUzMTg4MnoiLz4KICAgIDwvZz4KICA8L2c+Cjwvc3ZnPg==");']{
background-image:url(https://i.imgur.com/nHzSR9W.png)!important
}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIyNiI+CiAgPHBhdGggZmlsbD0iI0ZGRiIgZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMTMuMDA2Mjg2NjIgMjJjMSAwIDEuNzE0Mjg1NzItLjQwMTk1MzEgMS45OTk5OTk5OC0xLjAwNDg4MjhoLTMuOTk5OTk5OThjLjI4NTcxNDMuNjAyOTI5NyAxIDEuMDA0ODgyOCAyIDEuMDA0ODgyOHptNi45ODA1Mjk3OC0zLjk2MzQzOTlWMTBjMC0yLjY0LTIuMzAyODY2OC00Ljk3NTAzNjYyLTUuMDEwNTU5MDgtNC45NzUwMzY2MiAwLS43Mi0uMzQ0MDU1MTctMS4wMjk4NDYyLTEuOTczMTE0LTEuMDI5ODQ2Mi0xLjYyOTA1ODg1IDAtMS45NjU4NTA4NC4zMDk4NDYyLTEuOTY1ODUwODQgMS4wMjk4NDYyQzguMzI5NjAwMTggNS4wMjQ5NjMzOCA1Ljk5NTQ4MzQgNy4zNiA1Ljk5NTQ4MzQgMTB2OC4wMzY1NjAxaC0uOTg5MTk2Nzh2MS45NTE0MTZIMjF2LTEuOTUxNDE2aC0xLjAxMzE4MzZ6TTE4IDE4SDh2LTcuN0M4IDguNDMgOS40NDQ0NDQ0NCA3IDExLjMzMzMzMzMzIDdoMy4zMzMzMzMzNEMxNi41NTU1NTU2IDcgMTggOC40MyAxOCAxMC4zVjE4eiIvPgo8L3N2Zz4=");'] {
background-image:url(https://i.imgur.com/rYtrTeW.png)!important
}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIyNiI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGZpbGw9IiNGRkYiIGQ9Ik0xMy4wMDYyODY2MiAyMmMuOTk5OTk5OTggMCAxLjcxNDI4NTY4LS40MDE5NTMxIDEuOTk5OTk5OTgtMS4wMDQ4ODI4aC0zLjk5OTk5OTk4Yy4yODU3MTQzLjYwMjkyOTcgMSAxLjAwNDg4MjggMiAxLjAwNDg4Mjh6bTYuOTgwNTI5NzgtMy45NjM0Mzk5VjEwYzAtMi42NC0yLjMwMjg2NjgtNC45NzUwMzY2Mi01LjAxMDU1OTEtNC45NzUwMzY2MiAwLS43Mi0uMzQ0MDU1Mi0xLjAyOTg0NjItMS45NzMxMTQtMS4wMjk4NDYyLTEuNjI5MDU4ODMgMC0xLjk2NTg1MDgyLjMwOTg0NjItMS45NjU4NTA4MiAxLjAyOTg0NjJDOC4zMjk2MDAxOCA1LjAyNDk2MzM4IDUuOTk1NDgzNCA3LjM2IDUuOTk1NDgzNCAxMHY4LjAzNjU2MDFoLS45ODkxOTY3OHYxLjk1MTQxNkgyMXYtMS45NTE0MTZoLTEuMDEzMTgzNnpNMTMuMDgzODk2MTYgMThsLTIuMDc4OTMwODIgMi4wMjcyMDQ1SDQuOTQxNjIwMzhWMThINnYtM2wyLTIuMDgyOTQyOTJWMTAuM0M4IDguNDMgOS40NDQ0NDQ0NCA3IDExLjMzMzMzMzMzIDdoMy4zMzMzMzMzN2MuMjA1ODcyMSAwIDEuMzU3OTgyNS0xLjkwOTA0NTggMS4zNTc5ODI1LTEuOTA5MDQ1OHMxLjMxODM5MDguMjc5MTU2OTIgMi41NTU1MzQzIDEuNTk4ODMzNjdjMS4yMzcxNDM2IDEuMzE5Njc2NzYgMS4zMjUzODg5IDMuMjUxOTI3NzQgMS4zMjUzODg5IDMuMjUxOTI3NzRMMTggMTIuOTQ1NDcyNTZWMThoLTQuOTE2MTAzODR6Ii8+CiAgICA8cGF0aCBzdHJva2U9IiNGMDQ3NDciIHN0cm9rZS13aWR0aD0iMiIgZD0iTTIxIDVMNSAyMSIgc3Ryb2tlLWxpbmVjYXA9InNxdWFyZSIvPgogIDwvZz4KPC9zdmc+");'] {
background-image:url(https://i.imgur.com/szyUrwt.png)!important
}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIyNiI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0xIDFoMjR2MjRIMSIvPgogICAgPHBhdGggZmlsbD0iI0ZGRiIgZD0iTTE1IDE1VjZoLTR2OWgtLjUwODk5NDgyQzEwLjIyNzg4MDQ4IDE1IDEwIDE1LjIyMzg1NzYgMTAgMTUuNWMwIC4yNjgwNjY0LjIxOTgzMDUuNS40OTEwMDUxOC41aDUuMDE3OTg5NjRDMTUuNzcyMTE5NTIgMTYgMTYgMTUuNzc2MTQyNCAxNiAxNS41YzAtLjI2ODA2NjQtLjIxOTgzMDUtLjUtLjQ5MTAwNTE4LS41SDE1em0yLTloMVY0SDh2MmgxdjhsLTIgMnYyaDUuMnY0aDEuNnYtNEgxOXYtMmwtMi0yVjZ6Ii8+CiAgPC9nPgo8L3N2Zz4=");'] {
background-image:url(https://i.imgur.com/wK8aeTQ.png)!important
}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIyNiI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGZpbGw9IiNGRkYiIGQ9Ik0xMSAxM2MyLjIxIDAgNC0xLjc5IDQtNHMtMS43OS00LTQtNC00IDEuNzktNCA0IDEuNzkgNCA0IDR6bTAgMmMtMi42NyAwLTggMS4zNC04IDR2MmgxNnYtMmMwLTIuNjYtNS4zMy00LTgtNHptOS4wNjgxMTA2LTQuMDczNzMzODhWOC41NjEwODkzNmMwLS4xNzYyMDU0NSAwLS41NjEwODkzNi0uNTY2Nzc0Ny0uNTYxMDg5MzYtLjU2Njc3NDggMC0uNTcyMzk4MS4zODQ4ODM5LS41NzIzOTgxLjU2MTA4OTM2djIuMzY1MTc2NzZoLTIuMzE0ODE0NGMtLjE3NDkzMzIgMC0uNjA3NzE0NyAwLS42MDc3MTQ3LjU3MjM5Nzk4IDAgLjU3MjM5ODEuNDMyNzgxNS41NzM1MDE0LjYwNzcxNDcuNTczNTAxNGgyLjMxNDgxNDR2Mi4yOTkyNjcxYzAgLjE3NDkzMzIuMDA1NjIzMy42MjU4OTU3LjU3MjM5ODEuNjI1ODk1Ny41NjY3NzQ3IDAgLjU2Njc3NDctLjM5Mzc5OS41NjY3NzQ3LS41Njg3MzIydi0yLjM1NjQzMDZoMi4zMzkxMzM4Yy4xNzU1NjkzIDAgLjU5Mjc1NTYtLjAwMTEwMzMuNTkyNzU1Ni0uNTczNTAxNCAwLS41NzIzOTc5OC0uNDE3MTg2My0uNTcyMzk3OTgtLjU5Mjc1NTYtLjU3MjM5Nzk4aC0yLjMzOTEzMzh6Ii8+CiAgICA8cGF0aCBkPSJNMSAxaDI0djI0SDFWMXoiLz4KICA8L2c+Cjwvc3ZnPg==");'] {
background-image:url(https://i.imgur.com/NxDeThh.png)!important
}

.header-toolbar button span[style*='background-image: url("/assets/567632a2702aed0296e15d68d6cae738.svg");'] {
background-image:url(https://i.imgur.com/CJdITDq.png)!important
}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIyNiI+CiAgPHBhdGggZmlsbD0iI0ZGRiIgZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNOCA5LjMyNTg0MjdjMCAuNzQxNTczMDMuNjE2NDM4MzYgMS4zNTk1NTA1NiAxLjM1NjE2NDM4IDEuMzU5NTUwNTYuNzM5NzI2MDMgMCAxLjM1NjE2NDQtLjYxNzk3NzUzIDEuMzU2MTY0NC0xLjM1OTU1MDU2IDAtMS40ODMxNDYwNyAxLjYwMjczOTctMS41NDQ5NDM4MiAxLjc4NzY3MTIyLTEuNTQ0OTQzODIuMTg0OTMxNSAwIDEuNzg3NjcxMjMuMDYxNzk3NzUgMS43ODc2NzEyMyAxLjU0NDk0Mzgydi4zMDg5ODg3NmMwIC42MTc5Nzc1My0uMzA4MjE5MTggMS4xMTIzNTk1NS0uODYzMDEzNyAxLjQyMTM0ODMybC0xLjIzMjg3NjcuNjc5Nzc1MjhjLS42NzgwODIyLjM3MDc4NjUtMS4wNDc5NDUyIDEuMDUwNTYxOC0xLjA0Nzk0NTIgMS43OTIxMzQ4M3YxLjExMjM1OTUyQzExLjE0MzgzNTYzIDE1LjM4MjAyMjUgMTEuNzYwMjczOTYgMTYgMTIuNSAxNmMuNzM5NzI2MDMgMCAxLjM1NjE2NDM4LS42MTc5Nzc1IDEuMzU2MTY0MzgtMS4zNTk1NTA1NnYtLjY3OTc3NTI4bC44NjMwMTM3LS40MzI1ODQyN0MxNi4xMzY5ODYzIDEyLjc4NjUxNjgyIDE3IDExLjMwMzM3MDggMTcgOS42OTY2Mjkydi0uMzcwNzg2NUMxNyA2LjQ4MzE0NjA3IDE0LjcxOTE3ODA4IDUgMTIuNSA1IDEwLjIxOTE3ODA4IDUgOCA2LjQ4MzE0NjA3IDggOS4zMjU4NDI3ek0xMi41IDE3Yy0yIDAtMiAzIDAgM3MyLTMgMC0zeiIvPgo8L3N2Zz4=");'] {
background-image:url(https://i.imgur.com/gVzKx34.png)!important
}

.system-message-icon[style*='background-image: url("/assets/c30220457097b064286a8759a9b6c4af.svg");'] {
background-image:url(https://i.imgur.com/oYUOVp0.png)!important
}

.system-message-icon[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCIgdmVyc2lvbj0iMS4xIj4KICA8ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIHN0cm9rZT0ibm9uZSIgc3Ryb2tlLXdpZHRoPSIxIj4KICAgIDxwYXRoIGQ9Ik0xOCAwSDB2MThoMTh6Ii8+CiAgICA8cGF0aCBmaWxsPSIjRjA0NzQ3IiBkPSJNMy44IDhsMy42LTMuNkw2IDMgMCA5bDYgNiAxLjQtMS40TDMuOCAxMEgxOFY4Ii8+CiAgPC9nPgo8L3N2Zz4=");'] {
background-image:url(https://i.imgur.com/586Z9gu.png)!important
}

.system-message-icon[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGZpbGw9IiM5OUFBQjUiIGQ9Ik0wIDE0LjI1VjE4aDMuNzVMMTQuODEgNi45NGwtMy43NS0zLjc1TDAgMTQuMjV6TTE3LjcxIDQuMDRjLjM5LS4zOS4zOS0xLjAyIDAtMS40MUwxNS4zNy4yOWMtLjM5LS4zOS0xLjAyLS4zOS0xLjQxIDBsLTEuODMgMS44MyAzLjc1IDMuNzUgMS44My0xLjgzeiIvPgogICAgPHBhdGggZD0iTTAgMGgxOHYxOEgwIi8+CiAgPC9nPgo8L3N2Zz4K");']{
background-image:url(https://i.imgur.com/u1wlBLb.png)!important
}

.system-message-icon[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0xOCAwSDB2MThoMTh6Ii8+CiAgICA8cGF0aCBmaWxsPSIjNDNCNTgxIiBkPSJNMCA4aDE0LjJsLTMuNi0zLjZMMTIgM2w2IDYtNiA2LTEuNC0xLjQgMy42LTMuNkgwIi8+CiAgPC9nPgo8L3N2Zz4=");'] {
background-image:url(https://i.imgur.com/IzFVy0h.png)!important
}

.system-message-icon[style*='background-image: url("/assets/d80d1fdc43a3c42134a31a39581160ac.svg");'] {
background-image:url(https://i.imgur.com/GczWQaH.png)!important
}

.system-message-icon[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik03Ljk3MDU2My02Ljk5OTk5OTc1TDI0Ljk0MTEyNTc1IDkuOTcwNTYzIDcuOTcwNTYzIDI2Ljk0MTEyNTc1LTguOTk5OTk5NzUgOS45NzA1NjMiLz4KICAgIDxwYXRoIGZpbGw9IiM5OUFBQjUiIGQ9Ik03Ljk3MDU2MyAxMi43OTg5OTAxMmw2LjM2Mzk2MTAzLTYuMzYzOTYxMDMtMi44Mjg0MjcxMi0yLjgyODQyNzE2TDUuMTQyMTM1OSA5Ljk3MDU2M2wtLjM1OTkxMzctLjM1OTkxMzdjLS4xODYwNTcyNS0uMTg2MDU3MjUtLjUwNTQ4NDMtLjE4ODkwMTg1LS43MDA3NDY0OC4wMDYzNjAzLS4xODk1NTE1Ny4xODk1NTE1OC0uMTk4MTA5NzQuNTA4OTk3MDQtLjAwNjM2MDMuNzAwNzQ2NWwzLjU0ODI1NDUgMy41NDgyNTQ1Yy4xODYwNTcyNy4xODYwNTcyNS41MDU0ODQzMy4xODg5MDE4Ni43MDA3NDY1LS4wMDYzNjAzLjE4OTU1MTU2LS4xODk1NTE1Ny4xOTgxMDk3NC0uNTA4OTk3MDQuMDA2MzYwMy0uNzAwNzQ2NWwtLjM1OTkxMzctLjM1OTkxMzY4em03Ljc3ODE3NDYtNC45NDk3NDc0NmwuNzA3MTA2NzcuNzA3MTA2NzggMS40MTQyMTM1Ny0xLjQxNDIxMzU2TDEwLjc5ODk5MDEyLjA3MTA2ODA2IDkuMzg0Nzc2NTYgMS40ODUyODE2M2wuNzA3MTA2NzguNzA3MTA2NzhMNC40MzUwMjkxIDcuODQ5MjQyN0gxLjYwNjYwMTk2TC4xOTIzODg0IDkuMjYzNDU2MjJsMy42NzY5NTUyNyAzLjY3Njk1NTI2LTIuODI4NDI3MTMgMi44Mjg0MjcxMyAxLjEzMTM3MDg2IDEuMTMxMzcwOSAyLjgyODQyNzEtMi44Mjg0MjcxMyAzLjY3Njk1NTI2IDMuNjc2OTU1MjYgMS40MTQyMTM1Ni0xLjQxNDIxMzU2VjEzLjUwNjA5NjlsNS42NTY4NTQyNS01LjY1Njg1NDI0eiIvPgogIDwvZz4KPC9zdmc+");'] {
background-image:url(https://i.imgur.com/wK8aeTQ.png)!important;
margin-right:6px
}

/* Pinned System message */

.theme-dark .system-message-timestamp {
color:#b2b2b2
}

.theme-dark .system-message {
color:#ccc
}

.theme-dark .system-message-content a {
color:#e5e5e5!important
}

/* --------------------- */

.guild-channels .channel-voice-states li .icon-muted {
background-image:url(https://i.imgur.com/66RcXXp.png);
opacity:.5!important;
-moz-transform:scaleX(-1);
-o-transform:scaleX(-1);
-webkit-transform:scaleX(-1);
transform:scaleX(-1);
filter:FlipV;
-ms-filter:"FlipV"
}

.guild-channels .channel-voice-states li .icon-deafened {
background-image:url(https://i.imgur.com/quqY44n.png);
opacity:.5!important
}

.private-channel-call .status-muted:after {
background-image:url(https://i.imgur.com/66RcXXp.png);
background-size:18px 18px;
-moz-transform:scaleX(-1);
-o-transform:scaleX(-1);
-webkit-transform:scaleX(-1);
transform:scaleX(-1);
filter:FlipV;
-ms-filter:"FlipV"
}

.private-channel-call .status-deafened:after {
background-image:url(https://i.imgur.com/quqY44n.png);
background-size:16px 16px
}

.channel-mute-button {
background-image:url(https://i.imgur.com/rYtrTeW.png)
}

.channel-mute-button.muted {
background-image:url(https://i.imgur.com/szyUrwt.png)
}

.channel-notification-settings .content .reset-container .reset-button {
background-image:url(https://i.imgur.com/y5to0IU.png)
}

.guilds-wrapper .guilds .friends-icon {
background-image:url(https://i.imgur.com/QJ8v9RV.png)
}

.private-channels .channel .icon-friends {
background-image:url(https://i.imgur.com/W5UM0RM.png)
}

.guilds-wrapper .guilds .guild.audio .guild-inner:after {
background-image:url(https://i.imgur.com/FgYwEtE.png);
background-size:18px 18px
}

.messages-popout .empty-placeholder .image[style*='background-image: url("/assets/6793e022dc1b065b21f12d6df02f91bd.svg");'] {
background-image:url(https://i.imgur.com/w0GqxfV.png)!important;
background-size:80%
}

.messages-popout .empty-placeholder .image[style*='background-image: url("/assets/308e587f3a68412f137f7317206e92c2.svg");']{
background-image:url(https://i.imgur.com/cqdtLo5.png)!important;
background-size:60%
}

#settings-roles .roles header .create-role-button {
background-image:url(https://i.imgur.com/ZbEoljM.png);
background-size:18px
}

.member-roles .member-role.member-role-add button {
background-image:url(https://i.imgur.com/ZbEoljM.png);
background-size:13px
}

.member-roles .member-role .member-role-remove {
background-image:url(https://i.imgur.com/u6RwzJp.png);
background-size:12px 12px
}

.user-popout .body .roles .icon-roles {
background-image:url(https://i.imgur.com/PLMb5Jf.png)
}

.user-popout .body .notes .icon-notes {
background-image:url(https://i.imgur.com/mYjKNQo.png)
}

.private-channel-call .btn-icon-mute:after {
background-image:url(https://i.imgur.com/ovju27H.png)
}

.private-channel-call .btn-icon-mute.mute:after {
background-image:url(https://i.imgur.com/66RcXXp.png)!important;
opacity:1!important;
-moz-transform:scaleX(-1);
-o-transform:scaleX(-1);
-webkit-transform:scaleX(-1);
transform:scaleX(-1);
filter:FlipV;
-ms-filter:"FlipV"
}

.private-channel-call .btn-icon-settings:after {
background-image:url(https://i.imgur.com/rI8942r.png)
}

.private-channel-call .btn-icon-mute:hover:after {
background-image:url(https://i.imgur.com/66RcXXp.png);
opacity:1!important;
-moz-transform:scaleX(-1);
-o-transform:scaleX(-1);
-webkit-transform:scaleX(-1);
transform:scaleX(-1);
filter:FlipV;
-ms-filter:"FlipV"
}

.private-channel-call .btn-icon-settings:hover:after {
background-image:url(https://i.imgur.com/rI8942r.png);
opacity:1!important
}

.embed .embed-video-actions .embed-video-play {
background-image:url(https://i.imgur.com/5g2k6mV.png);
background-size:25px 25px;
margin-top:-5px
}

.embed .embed-video-actions .embed-video-popout {
background-image:url(https://i.imgur.com/Mgd1QEP.png);
background-size:20px 20px
}

.guild-channels .icon-lock {
background-image:url(https://i.imgur.com/CgPGTlg.png);
background-size:16x 16px!important
}

.search-bar-tag .close {
background-image:url(https://i.imgur.com/u6RwzJp.png);
background-size:16px 16px
}

.private-channels .channel .close {
background-image:url(https://i.imgur.com/u6RwzJp.png);
background-size:18px 18px
}

.btn-confirm .icon.icon-logout {
background-image:url(https://i.imgur.com/bWF7DDP.png);
background-size:22px 22px
}

.btn-confirm .icon.icon-delete {
background-image:url(https://i.imgur.com/5jfTC53.png);
background-size:20px 20px
}

.settings-connections-wrapper .authed-app .details .permission-checkmark {
background-image:url(https://i.imgur.com/TdP6eOM.png);
background-size:13px 12px
}

.user-settings-modal button.preview-sound:before {
background-image:url(https://i.imgur.com/FgYwEtE.png);
background-size:20px 18px
}

.user-settings-locale .help-translate {
background-image:url(https://i.imgur.com/y2loZPV.png);
background-size:26px 22px
}

.markdown-modal .markdown-modal-header .markdown-modal-close {
background-image:url(https://i.imgur.com/u6RwzJp.png);
background-size:20px 20px;
height:18px;
width:18px
}

.user-settings-modal-games .games-table .games-row .item-alert .icon, .user-settings-modal-games .games-table .games-row .item-delete .icon {
background-image:url(https://i.imgur.com/y5to0IU.png);
background-size:16px 16px
}

.theme-dark .channel-textarea-upload {
background-image:url(https://i.imgur.com/yQPO7Rt.png);
background-size:24px 24px
}

.theme-dark .channel-textarea-upload:hover {
background-image:url(https://i.imgur.com/yQPO7Rt.png);
background-color:#383838!important
}

.create-guild-container .action.create .action-icon {
background-image:url(https://i.imgur.com/XcU6PCi.png);
background-size:75px 75px;
opacity:.5
}

.create-guild-container .action.join .action-icon {
background-image:url(https://i.imgur.com/GqN1Daw.png);
background-size:75px 75px;
opacity:.5
}

.create-guild-container .form-actions .btn-default:before {
background-image:url(https://i.imgur.com/586Z9gu.png)
}

.clipboard-input-inner button.tweet {
background-image:url(https://i.imgur.com/3HQwTtZ.png)!important
}

.clipboard-input-inner button.copy {
background-image:url(https://i.imgur.com/vpF5Uw4.png)!important
}

.clipboard-input-inner button.copy:hover {
background-color:#383838
}

.theme-dark .messages-popout-wrap .messages-popout .message-group .action-buttons .close-button {
background-image:url(https://i.imgur.com/u6RwzJp.png)!important
}

.guild-channels header button:after {
background-image:url(https://i.imgur.com/ZbEoljM.png);
background-size:18px 18px
}

#user-profile-modal .header .additional-actions-icon {
background-image:url(https://i.imgur.com/To9qvQa.png);
background-size:34px 34px!important
}

.guild-channels .toggle-muted-text-channels a:before {
background-image:url(https://i.imgur.com/33UBzEX.png);
background-size:18px 18px
}

.chat .welcome-message .item-container .icon.exclamation {
background-image:url(https://i.imgur.com/s2jYlk6.png)
}

.chat .welcome-message .item-container .icon.share {
background-image:url(https://i.imgur.com/O5RG3dq.png);
transform:rotate(-90deg)
}

.chat .welcome-message .item-container .icon.mobile {
background-image:url(https://i.imgur.com/NdsFNVf.png)
}

.chat .welcome-message .item-container .icon.twitter {
background-image:url(https://i.imgur.com/iBdW6HC.png)
}

/* DEV TAG */

.message-group .avatar-large[style*="128043634678300672"]+.comment .user-name::after {
content:"W3 DEV";
color:#e5e5e5;
background:#900;
border-radius:3px;
margin-left:4px;
font-size:10px;
padding:2px 2px 1px 2px;
font-weight:700
}

.guild-settings-modal-members .avatar-small[style*="128043634678300672"]+.member-inner .member-username::after {
content:"W3 DEV";
background:#900;
color:#e5e5e5;
border-radius:3px;
font-size:10px;
padding:2px 2px 1px 2px;
font-weight:700;
margin-left:4px
}

div.avatar-small[style*="128043634678300672"]+.member-inner .member-username-inner::after {
content:"W3 DEV";
color:#e5e5e5;
background:#900;
border-radius:3px;
margin-left:1px;
font-size:10px;
padding:2px 2px 1px 2px;
font-weight:700
}

.avatar-popout[style*="128043634678300672"]::after {
content:"WITCHER 3 DEV";
color:#e5e5e5;
background:#900;
border-radius:3px;
left:-2.5px;
font-size:10px;
padding:1px 5px 0px 5px;
font-weight:700;
line-height:15px;
position:absolute;
width:95%;
text-align:center;
top:93px
}

.avatar-profile[style*="128043634678300672"]::after {
content:"WITCHER 3 DEV";
color:#e5e5e5;
background:#900;
border-radius:3px;
left:-2px;
font-size:11px;
padding:1px 5px 0px 5px;
font-weight:700;
line-height:15px;
position:absolute;
width:95%;
text-align:center;
top:132px
}

.theme-dark .message-group h2 strong:hover {
text-decoration:none;
text-shadow:2.5px 2px 1.5px #000
}

.user-popout .username-wrapper .discord-tag {
margin-top:5px
}

.user-popout .username-wrapper .nickname {
margin-top:5px
}

/* Discord Nitro */

.premium-settings .premium-header .premium-logo {
opacity:.75;
-webkit-filter:greyscale(100%);
filter:grayscale(100%)
}

.premium-settings .premium-header .premium-splash-wumpus {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.premium-settings .premium-header.splash {
border-bottom:none ;
background-image:none
}

.premium-settings .premium-feature .premium-feature-icon {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.premium-settings .premium-header .intro-subtitle {
color:#b2b2b2
}

.premium-settings .premium-feature .premium-feature-title {
color:#e5e5e5
}

.premium-settings .premium-feature .premium-feature-description {
color:#b2b2b2
}

.premium-settings .premium-header .premium-options button strong {
color:#e5e5e5
}

.premium-settings .premium-header .premium-options button {
background:#232323;
border:none;
color:#ccc
}

.premium-settings .premium-header .premium-options button:hover {
background:#900!important
}

.premium-settings .premium-header .premium-options button.btn-clear strong {
color:#e5e5e5
}

.premium-settings .premium-header .premium-options button.btn-clear {
background:#232323;
color:#ccc;
border:none
}

.premium-settings .premium-header .premium-options button.btn-clear:hover {
background:#900!important
}

.premium-settings .subscription .premium-tools .ui-button {
margin-right:0px!important
}

.premium-settings .premium-header .premium-free-months {
color:#b2b2b2
}

.premium-payment-modal {
background:#191919
}

.premium-payment-modal .premium-animation {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.premium-payment-modal .premium-payment-form .premium-payment-title {
color:#e5e5e5
}

.premium-payment-modal .premium-payment-form .premium-payment-subtitle {
color:#b2b2b2
}

.fancy-credit-input {
background-color:#232323
}

.fancy-credit-input .card-icon-wrapper {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.fancy-credit-input .cc-number-wrapper .cc-number-placeholder {
color:#b2b2b2
}

.fancy-credit-input .cc-number-wrapper .cc-number {
color:#ccc!important
}

.fancy-credit-input .cc-number-wrapper .cc-number-continue {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.fancy-credit-input .cc-info-wrapper .expiration-placeholder {
color:#b2b2b2;
opacity:
}

.fancy-credit-input input {
color:#ccc;
opacity:
}

.fancy-credit-input input::-webkit-input-placeholder {
color:#b2b2b2!important
}

.premium-payment-modal .premium-payment-button.open:disabled,
.premium-payment-modal .premium-payment-button.open:disabled:hover {
border:none;
background:#232323
}

.premium-payment-modal .premium-payment-button {
background:#232323;
color:#ccc;
box-shadow:none
}

.premium-payment-modal .premium-payment-button:hover {
background:#900
}

.premium-settings .premium-header {
border-bottom:none

}

.premium-settings .subscription .premium-details .premium-title {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.75
}

.premium-settings .subscription.active:before {
display:none
}

.premium-settings .subscription.active {
background:#383838
}

.premium-settings .subscription.active .btn-filled {
background:#232323;
color:#ccc
}

.premium-settings .subscription.active .btn-filled:hover {
background:#900
}

.premium-settings .subscription .premium-details .premium-info {
color:#b2b2b2
}

.premium-settings .payment-subhead {
color:#ccc
}

.card-icon:before {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.premium-settings .payment-method .payment-info .card-info .card-description {
color:#b2b2b2
}

.premium-settings .payment-method .payment-info .card-info .card-description strong {
color:#ccc
}

.premium-settings .payment-method .payment-info .card-info .card-details {
color:#b2b2b2
}

.btn-stroked {
background:#232323;
color:#ccc;
border:none
}

.btn-stroked:hover {
background:#900
}

.premium-settings .billing-history-list li.header-row {
color:#b2b2b2
}

.premium-settings .billing-history-list li:last-of-type {
color:#b2b2b2
}

.alert.form.premium-unsubscribe:before, .alert.form.premium-upgrade:before {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.modal-content .form-inner p:first-child {
margin-top:40px
}

.alert.form.premium-upgrade strong {
color:#e5e5e5
}

/* search */

.theme-dark .search-results-wrap .search-header {
background-color:#232323
}

.theme-dark .search-results-wrap {
z-index:1;
background:#191919
}

.theme-dark .search-results-wrap .search-result:after {
background-image:none
}

.theme-dark .search-results-wrap .search-result:before {
background-image:none
}

.search-results-wrap .empty-results-wrap .search-index-animation {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.search-results-wrap .empty-results-wrap .still-indexing {
color:#ccc
}

.theme-dark .search-results-wrap .search-header .spinner .path {
stroke:#e5e5e5
}

.search-results-wrap .search-result .search-result-message.hit {
box-shadow:none;
background-color:#232323;
border:none!important;
border-radius:0
}

.theme-dark .search-results-wrap .search-result.expanded {
border:none;
background:#232323;
border-radius:0
}

.theme-dark .search-results-wrap .search-result.expanded .search-result-message.hit {
background:#383838
}

.theme-dark .search-results-wrap .message-group h2 span {
color:#b2b2b2
}

.theme-dark .message-group .mentioned .message-text {
background:none!important
}

.theme-dark .search-results-wrap .channel-separator .channel-name {
background-color:#191919
}

.theme-dark .search-results-wrap .channel-separator:before {
border-color:#b2b2b2
}

.theme-dark .search-results-wrap .search-header .total-results, .theme-dark .search-results-wrap .search-header a {
opacity:1;
color:#b2b2b2
}

.theme-dark .search-results-wrap .search-header .tab {
opacity:1;
color:#b2b2b2;
border-color:#900!important
}

.theme-dark .search-results-wrap .search-header .tab.selected {
color:#e5e5e5
}

.theme-dark .search-results-wrap .search-header .tab:not(.selected):hover {
color:#ccc;
border-color:#ccc!important
}

.theme-dark .search-results-wrap .scroller-wrap .scroller::-webkit-scrollbar-track-piece {
background:none!important
}

.theme-dark .search-results-wrap .scroller-wrap .scroller::-webkit-scrollbar-thumb {
background-color:#292929!important;
border:1px solid #191919!important
}

.theme-dark .search-results-wrap .empty-results-wrap .no-results-image, .theme-dark .search-results-wrap .error-wrap .no-results-image {
opacity:.25
}

.theme-dark .search-results .message-group .comment .markup .mention {
background-color:#191919!important
}

.theme-dark .search-results .message-group .comment .markup .highlight {
background:none;
text-decoration:underline
}

.theme-dark .search-results .message-group .comment .markup pre code {
background-color:#191919;
color:#b2b2b2
}

.theme-dark .search-results .message-group .comment .markup pre {
border:none
}

.theme-dark .search-results .message-group .comment .markup code.inline {
background-color:#191919;
border-radius:0
}

.search-results-wrap .empty-results-wrap .no-results {
color:#b2b2b2
}

.theme-dark .search .search-bar .search-bar-icon {
left:-2px
}

.theme-dark .search .search-bar {
background-color:rgba(25,25,25,.75);
border-radius:0
}

.search .DraftEditor-root .public-DraftStyleDefault-block span {
background-color:#282828
}

.theme-dark .search .search-bar .public-DraftEditorPlaceholder-root {
color:#ccc
}

.search-popout .search-query {
border-bottom:4px solid #900
}

.search-popout .search-query .keybind-shortcut span {
background:#191919!important;
border:solid 1px #666!important;
box-shadow:inset 0 -4px 0 #666!important
}

.search-popout .search-query .search-for strong {
color:#ccc
}

.theme-dark .search-popout {
background-color:#191919;
background-image:none;
border-radius:0
}

.search-popout .results-group:before {
display:none
}

.search-popout .option {
background-color:#191919!important;
background-image:none!important
}

.search-popout .results-group .header {
color:#e5e5e5
}

.search-popout .results-group .search-learn-more {
background-image:url(https://i.imgur.com/PGNUNis.png);
background-size:18px 18px
}

.search-popout .option:hover {
background-color:#232323!important;
border-radius:0
}

.search-popout .option.selected:after {
background-image:none
}

.search-popout .option .filter {
color:#b2b2b2;
opacity:.80
}

.search-popout .option .answer {
color:#ccc;
font-weight:normal
}

.search-popout .option .non-text {
color:#e5e5e5
}

.search-popout .option strong {
color:#ccc
}

.search-popout .option.user .displayed-nick {
color:#b2b2b2;
font-weight:bold
}

.search-popout .option.user .display-username::before {
content:"(";
color:#ccc
}

.search-popout .option.user .display-username::after {
content:")";
color:#ccc
}

.search-popout .option.user .display-avatar {
box-shadow: -1px 1px 6px #000,
inset -1px 1px 6px #000,inset 1px -1px 6px #000,1px -1px 6px #000;
border-radius:2px
}

.search-popout .option:after {
background-image:none
}

.search-popout .option.selected:before {
background-image:url(https://imgur.com/ZbEoljM.png);
background-size:18px 18px
}

.search-popout .results-group .search-clear-history {
background-image:url(https://i.imgur.com/JW7VcCL.png)
}

.theme-dark .search-results-wrap .pagination .pagination-next {
background-image:url(https://imgur.com/33UBzEX.png);
background-size:20px 20px;
transform:rotate(-90deg)!important;
border:none
}

.theme-dark .search-results-wrap .pagination .pagination-previous {
background-image:url(https://imgur.com/33UBzEX.png);
background-size:20px 20px;
transform:rotate(90deg)!important;
border:none
}

.search-popout .date-picker {
background:#191919;
border-top:none
}

.react-datepicker {
background:#191919
}

.react-datepicker .react-datepicker__navigation.react-datepicker__navigation--next, .react-datepicker .react-datepicker__navigation.react-datepicker__navigation--previous {
border:none
}

.react-datepicker .react-datepicker__navigation.react-datepicker__navigation--next {
background-image:url(https://imgur.com/33UBzEX.png);
background-size:18px 18px;
transform:rotate(-90deg)!important
}

.react-datepicker .react-datepicker__navigation.react-datepicker__navigation--previous {
background-image:url(https://imgur.com/33UBzEX.png);
background-size:18px 18px;
transform:rotate(90deg)!important
}

.react-datepicker .react-datepicker__header {
background:#191919
}

.react-datepicker .react-datepicker__month-container {
background:#191919;
border:none
}

.react-datepicker .react-datepicker__month {
background:#191919;
color:#e5e5e5!important
}

.react-datepicker .react-datepicker__current-month {
background:#191919;
color:#e5e5e5!important;
border-bottom:none
}

.react-datepicker .react-datepicker__day-names {
background:#191919
}

.react-datepicker .react-datepicker__day-name {
color:#ccc
}

.react-datepicker__day {
background:#383838;
color:#e5e5e5!important
}

.react-datepicker__day:hover {
background:#232323!important;
color:#e5e5e5!important
}

.react-datepicker__day--today {
background:#383838
}

.react-datepicker .react-datepicker__day.react-datepicker__day--today:after {
background-color:#900
}

.react-datepicker__day--disabled {
background:#191919;
color:#383838!important
}

.react-datepicker__day--disabled:hover {
background:none!important;
color:#383838!important
}

.react-datepicker .react-datepicker__day--outside-month {
background:#232323!important;
}

.react-datepicker .react-datepicker__day--outside-month:hover {
background:#900!important
}

.search-popout .date-picker .date-picker-hint {
border-top:4px solid #900
}

.search-popout .date-picker .date-picker-hint .hint-value {
background:#383838
}

.search-popout .date-picker .date-picker-hint .hint-value:hover {
background:#232323!important
}

.react-datepicker .react-datepicker__day {
border-radius:0!important;
border-color:#191919!important
}

.react-datepicker .react-datepicker__month .react-datepicker__week>.react-datepicker__day:last-of-type {
border-radius:0!important;
}

.react-datepicker .react-datepicker__month>.react-datepicker__week:last-of-type .react-datepicker__day {
border-radius:0!important;
}

.theme-dark .theme-light .ui-calendar-picker .react-datepicker, .theme-light .ui-calendar-picker .react-datepicker {
background-color:#191919
}

.theme-dark .theme-light .ui-calendar-picker .react-datepicker__header, .theme-light .ui-calendar-picker .react-datepicker__header {
background-color:#191919
}

.theme-dark .ui-calendar-picker .react-datepicker__day-name {
color:#ccc!important
}

.theme-dark .ui-calendar-picker .react-datepicker__day.react-datepicker__day--selected:after {
background-color:#900!important
}

/* Invite Modal */

.invite-modal {
box-shadow:1px -1px 2px rgba(0,0,0,1),-1px 1px 2px rgba(0,0,0,1);
border-radius:0
}

.invite-modal .scroller {
background-color:#191919!important;
background:none
}

.invite-modal .avatar-xxxlarge {
border-radius:0;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000
}

.invite-modal .invite-title {
color:#e5e5e5
}

.invite-modal .invite-body {
color:#b2b2b2
}

.invite-modal .button {
background-color:#232323;
color:#b2b2b2
}

.invite-modal .button:hover {
background-color:#900
}

.invite-modal .invite-cancel {
color:#b2b2b2
}

.invite-modal .invite-body.error {
color:#b2b2b2
}

/* Quick Switcher */

.channel-notices .channel-notice.quickswitcher-notice {
background-color:#191919;
background-position:center 20px!important;
padding-top:110px
}

.quickswitcher {
background:#191919!important
}

.quickswitcher .big-input {
background-color:#232323!important;
color:#ccc!important;
border-radius:0
}

.quickswitcher .big-input::-webkit-input-placeholder {
color:#b2b2b2!important
}

.quickswitcher .scroller-wrap:before {
background-image:none!important
}

.quickswitcher .result .section-title:hover {
background:none!important
}

.quickswitcher .result>div {
background-color:#191919
}

.quickswitcher .result>div:hover {
background-color:#383838!important;
border-radius:0
}

.quickswitcher .result.selected {
background-color:#383838!important;
border-radius:0
}

.quickswitcher .result .result-text-channel {
background-color:#191919
}

.quickswitcher .result .result-text-channel:hover {
background-color:#383838;
border-radius:0
}

.quickswitcher .result.selected:after {
background-color:#191919!important;
box-shadow:none!important;
opacity:1!important;
display:none
}

.quickswitcher.dark .result>div .result-match, .quickswitcher.dark .result>div .result-type-icon {
color:#ccc;
opacity:1
}

.quickswitcher .result .result-username {
color:#b2b2b2;
opacity:1
}

.quickswitcher .result .result-note {
color:#b2b2b2;
opacity:1
}

.quickswitcher .tips {
border-top:none
}

.quickswitcher .tips.results {
color:#ccc!important
}

.quickswitcher-empty-state {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:1
}

.quickswitcher .quickswitcher-empty-state-note {
color:#b2b2b2!important
}

.quickswitcher .keybind-shortcut span {
background-color:#232323;
box-shadow:inset 0 -4px 0 #383838;
border-color:#383838
}

.quickswitcher-container .quickswitcher .scroller-wrap .scroller::-webkit-scrollbar-track-piece {
background:none!important;
margin-top:13px!important
}

.quickswitcher-container .quickswitcher .scroller-wrap .scroller::-webkit-scrollbar-thumb {
background-color:#383838!important;
border:1px solid transparent!important;
background-clip:content-box
}

/*-------------------------*/

.layers {
background:none!important
}

.layer {
background:none!important
}

/* NSFW Settings */

/* Kilanna did some bullshit wizardry to make
majority of this work thank him */

div.chat.flex-vertical.flex-spacer > .content.flex-spacer.flex-horizontal {
background-color:rgba(0,0,0,0.65)!important;
box-shadow:inset 10px 10px 5px -6px rgba(0,0,0,1);
}

.theme-dark .ui-guild-nsfw .image {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.75
}

.theme-dark .ui-guild-nsfw .title {
color:#e5e5e5
}

.theme-dark .ui-guild-nsfw .description {
color:#b2b2b2
}

.ui-guild-nsfw .separator {
display:none
}

.theme-dark .ui-button.primary.outlined {
background-color:#232323;
border:none
}

.theme-dark .ui-button.primary.outlined:hover {
background-color:#900
}

.ui-guild-nsfw .action-button.dark-red {
background-color:#232323
}

.ui-guild-nsfw .action-button.dark-red:hover {
background-color:#900
}

.channel-settings-modal .overview .checkbox-group {
position:relative;
left:-10px;
margin-bottom:35px;
margin-top:35px
}

.channel-settings-modal .overview .control-groups {
display:block
}

.channel-settings-modal .overview .checkbox-group:before {
content:"CHANNEL NSFW SETTING";
color:#ccc;
font-size:11px;
font-weight:bold;
}

.channel-settings-modal .overview .control-group .help-text {
margin-top:5px
}

/* Random Bug Fixes */

div.scroller.settings-wrapper.settings-panel {
background:#191919
}

.user-settings-modal-streamer-mode .user-settings-streamer-mode-image {
opacity:.35
}

.user-settings-modal-locale p {
color:#b2b2b2
}

.user-settings-modal-locale a {
color:#e5e5e5!important
}

.guild-settings-modal-security {
background:none
}

.guild-settings-modal-emoji .no-emoji img {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.75
}

.guild-settings-modal-members .search-bar-icon .icon {
top:8px;
left:12px
}

.private-channels .search-result .search-result-name {
color:#b2b2b2
}

.search-bar-light .search-bar-icon .icon.icon-search-bar-clear {
background-image:url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPgogICAgPHJlY3Qgd2lkdGg9IjE4IiBoZWlnaHQ9IjE4Ii8+CiAgICA8cGF0aCBmaWxsPSIjRkZGRkZGIiBkPSJNOSwyIEMxMi44NzEsMiAxNiw1LjEyOSAxNiw5IEMxNiwxMi44NzEgMTIuODcxLDE2IDksMTYgQzUuMTI5LDE2IDIsMTIuODcxIDIsOSBDMiw1LjEyOSA1LjEyOSwyIDksMiBMOSwyIFogTTExLjY5MjUsNS4yNSBMOSw3Ljk0MjUgTDYuMzA3NSw1LjI1IEw1LjI1LDYuMzA3NSBMNy45NDI1LDkgTDUuMjUsMTEuNjkyNSBMNi4zMDc1LDEyLjc1IEw5LDEwLjA1NzUgTDExLjY5MjUsMTIuNzUgTDEyLjc1LDExLjY5MjUgTDEwLjA1NzUsOSBMMTIuNzUsNi4zMDc1IEwxMS42OTI1LDUuMjUgWiIvPgogIDwvZz4KPC9zdmc+Cg==)
}

.change-log-button-container .change-log-button {
color:#e5e5e5
}

.change-log-button-container .change-log-button:hover {
color:#fff
}

.user-settings-modal-locale .select-item .primary {
color:#ccc!important
}

.user-settings-modal-locale .select-item .localized {
color:#ccc!important
}

.premium-settings .payment-method .payment-info .card-tools .ui-button {
border:none;
background:#232323;
color:#ccc
}

.premium-settings .payment-method .payment-info .card-tools .ui-button:hover {
border:none;
background:#900;
color:#ccc
}

.premium-settings .billing-history-list li .ui-form-text {
color:#b2b2b2
}

.ui-form-title.h2 {
color:#ccc
}

.premium-settings .subscription .premium-tools .ui-button {
background:#232323;
color:#ccc
}

.premium-settings .subscription .premium-tools .ui-button:hover {
background:#900;
color:#ccc
}

.premium-settings.v1 .ui-form-divider {
display:none
}

.theme-dark .channel-members .member:not(.disabled).popout-open {
background:none
}

.user-settings-modal .safety-level-select .radio-group li .criteria {
color:#b2b2b2
}

.theme-dark .ui-quick-select {
color:#e5e5e5
}

.theme-dark .ui-quick-select-label {
display:none
}

.ui-quick-select-popout {
background-color:#383838
}

.ui-quick-select-popout-option:hover {
background-color:#232323;
color:#e5e5e5!important
}

.message-group .btn-reaction {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
}

.deprecated-settings-modal .settings-inner .settings-panel h1 {
color:#e5e5e5
}

.emoji-picker .header .search-bar-icon {
left:0px;
top:4px
}

.theme-dark .ui-search-bar {
background-color:#191919;
border-radius:0
}

.quickswitcher.dark .ui-scroller-wrap:before {
background-image:none
}

/* New Server Setting */

.theme-dark .guild-settings-base-section .avatar-uploader .avatar-uploader-inner {
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
}

.ui-standard-sidebar-view .notice-region .ui-settings-notice.elevation-high {
background-color:#383838!important
}

.ui-standard-sidebar-view .notice-region .ui-button.filled.green.small.grow {
background-color:#232323
}

.ui-standard-sidebar-view .notice-region .ui-button.filled.green.small.grow:hover {
background-color:#900
}

.ui-form-item .ui-text-input .input {
background-color:#282828
}

.ui-form-item .ui-text-input .input:focus {
border-color:#191919;
background-color:#191919
}

.ui-form-item .ui-region-selector.ui-input-button {
background-color:#282828
}

.ui-form-item .ui-region-selector.ui-input-button.hover {
background-color:#191919
}

.ui-form-item .ui-button.ghost.grey.min.grow {
background-color:#191919
}

.ui-form-item .ui-button.ghost.brand.min.grow:hover {
background-color:#900;
color:#e5e5e5
}

.ui-form-item .ui-button.brand.ghost {
background-color:#232323;
color:#e5e5e5
}

.ui-button.white.outlined {
background-color:#191919;
border:none
}

.ui-button.white.outlined:hover {
background-color:#900
}

/* Audit Logs */

.theme-dark .ui-popout-list {
background-color:#383838
}

.ui-selectable-item.selected {
background-color:#191919!important;
border-radius:0
}

.theme-dark .ui-selectable-item:hover {
background-color:#232323;
border-radius:0
}

.ui-popout-list .ui-search-bar {
background-color:#282828;
border-radius:0
}

.ui-popout-list .ui-search-bar .input::-webkit-input-placeholder {
color:#e5e5e5
}

.ui-avatar.small {
border-radius:0
}

.theme-dark .ui-audit-log .header {
background-color:#383838;
color:#ccc
}

.theme-dark .ui-audit-log.ui-audit-log-expanded .header {
background-color:#303030
}

.theme-dark .ui-audit-log-change-details {
background-color:#282828
}

.theme-dark .ui-audit-log strong {
color:#e5e5e5
}

.theme-dark .ui-audit-log .timestamp {
color:#b2b2b2
}

.ui-audit-log-change-details .prefix.ui-flex.type-update {
color:#ccc
}

.ui-audit-log-change-details .prefix.ui-flex.type-create {
color:#ccc
}

.ui-audit-log-change-details .change-str {
color:#b2b2b2
}

.ui-audit-log-change-details .sub-list-item {
color:#b2b2b2;
text-decoration:underline
}

.ui-audit-log .ui-avatar {
border-radius:4px;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
}

/* Roles */

.ui-tab-bar.SIDE .ui-tab-bar-item.selected {
border-radius:0
}

.theme-dark .ui-color-picker-custom {
background-color:#383838
}

.ui-color-picker-custom .ui-text-input .input:focus {
background-color:#191919;
border:none;
}

.ui-color-picker-custom .ui-text-input {
background-color:#282828
}

/* Integrations */

.ui-empty-state-title {
color:#e5e5e5!important
}

.ui-empty-state-text {
color:#b2b2b2!important
}

/* Server Emoji */

.theme-dark .emoji-row {
box-shadow:none
}

.theme-dark .ui-text-input.emoji-alias-input .input {
background-color:#232323;
border-color:#191919;
border-radius:0
}

.theme-dark .ui-text-input.emoji-alias-input .input:focus {
background-color:#191919
}

.ui-avatar.xsmall {
border-radius:0;
box-shadow:-1px 1px 2px #000,inset -1px 1px 2px #000,
inset 1px -1px 2px #000,1px -1px 2px #000;
}

.emoji-row .emoji-remove {
background-color:#282828
}

.emoji-row .emoji-remove:hover {
background-color:#303030
}

/* Webhooks */

.webhook-modal {
background-color:#191919
}

.webhook-modal-footer {
background-color:#191919;
border-top:6px solid #900
}

.webkhook-modal-header.ui-form-title.h5 {
color:#e5e5e5;
border-bottom:6px solid #900
}

.webhook-modal .ui-form-title.h5 {
color:#e5e5e5
}

.webhook-modal .ui-form-divider {
background-color:#191919;
margin-top:10px;
margin-bottom:15px
}

.webhook-modal .ui-select .Select-control {
border-radius:0
}

.webhook-modal .ui-text-input .input {
background-color:#383838;
color:#e5e5e5;
border-color:#191919;
border-radius:0
}

.webhook-modal .ui-text-input .input:focus {
background-color:#303030
}

.webhook-modal .ui-text-input .input:hover {
border-color:#191919
}

.webhook-modal .ui-select .Select-value {
height:39px
}

.webhook-modal .ui-select .Select-value-label {
color:#e5e5e5
}

.webhook-modal .ui-select .Select-menu {
background-color:#232323
}

.webhook-modal .ui-select .Select-option {
background-color:#303030
}

.webhook-modal .ui-select .Select-option.is-selected {
background-color:#191919!important
}

.webhook-modal .ui-select .Select-option.is-focused {
background-color:#232323
}

.webhook-modal .ui-form-text {
color:#ccc!important
}

.webhook-modal .ui-button.medium.grow {
background-color:#232323;
border:none;
color:#e5e5e5
}

.webhook-modal .ui-button.medium.grow:hover {
background-color:#900
}

.webhook-modal .avatar-uploader .size-info {
color:#ccc
}

.webhook-modal .ui-copy-input {
background-color:#303030;
border:1px solid #191919;
color:#e5e5e5
}

.webhook-modal .ui-copy-input .input {
color:#e5e5e5
}

.webhook-modal .ui-copy-input.success {
color:#ccc;
border:1px solid #191919!important
}

.webhook-modal .ui-button.green.ghost {
background-color:#232323;
color:#e5e5e5
}

.webhook-modal .ui-button.ghost.grey.min.grow {
color:#e5e5e5
}

.webhook-modal .ui-button.filled.brand.small.grow {
background-color:#232323
}

.webhook-modal .ui-button.filled.brand.small.grow:hover {
background-color:#900
}

.webhook-modal .ui-button.link.grey.small.grow {
color:#e5e5e5
}

.ui-webhook-row .remove-webhook {
background-color:#282828
}

.ui-webhook-row .remove-webhook:hover {
background-color:#303030
}

.form .form-inner {
color:#ccc
}

/* Widget */

.ui-copy-input.success {
border-color:#191919
}

.theme-dark .ui-input-button {
background-color:#282828
}

.ui-button.green.ghost {
color:#e5e5e5;
background-color:#232323
}

.ui-flex.flex-vertical.flex-justify-start.flex-align-stretch.flex-nowrap img.ui-flex-child {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.75
}

/* Members */

.theme-dark .guild-settings-members-member .tag {
color:#b2b2b2
}

.theme-dark .ui-role-list-add {
border-color:#b2b2b2;
opacity:.75
}

.guild-settings-members-member .ui-avatar {
border-radius:0;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000;
}

.theme-dark .guild-settings-members-member {
box-shadow:none
}

.prune-red-link:link {
color:#e5e5e5
}

.ui-flex.flex-horizontal.flex-justify-start.flex-align-stretch.flex-nowrap.ui-search-bar {
background-color:#303030
}

.theme-dark .ui-search-bar .input::-webkit-input-placeholder {
color:#e5e5e5
}

.ui-bot-tag {
background-color:#900
}

/* Invites */

.invite-settings-invite-row .ui-flex {
margin-left:4px
}

.invite-settings-invite-row .channel-name {
color:#b2b2b2;
opacity:1!important;
margin-left:32px
}

.invite-settings-invite-row .overflow-ellipsis.user-select-text.size-medium.color-primary.font-family-code {
color:#ccc;
opacity:1!important
}

.invite-settings-invite-row .revoke-invite {
background-color:#282828
}

.invite-settings-invite-row .revoke-invite:hover {
background-color:#303030
}

.theme-dark .invite-settings-invite-row {
box-shadow:none
}

/* Bans */

.guild-settings-banned-user .ui-avatar {
border-radius:0;
box-shadow:-1px 1px 8px #000,inset -1px 1px 8px #000,
inset 1px -1px 8px #000,1px -1px 8px #000
}

.theme-dark .guild-settings-banned-user {
box-shadow:none
}

.theme-dark .guild-settings-banned-user .username .discrim {
color:#b2b2b2
}

.theme-dark .guild-settings-banned-user-modal .user-discrim {
color:#b2b2b2
}

.guild-settings-banned-user-modal .content {
background-color:#191919!important
}

.theme-dark .guild-settings-banned-user-modal .reason {
color:#ccc
}

.guild-settings-banned-user-modal .footer {
background-color:#191919;
border-top:6px solid #900
}

.guild-settings-banned-user-modal .footer .ui-button.filled.brand.medium.grow {
background-color:#232323
}

.guild-settings-banned-user-modal .footer .ui-button.filled.brand.medium.grow:hover {
background-color:#900
}

.guild-settings-banned-user-modal .footer .ui-button.link.red.medium.revoke-btn.grow {
color:#ccc
}

.guild-settings-banned-user-modal .footer button.red.link:not(:disabled):hover .ui-button-contents {
background-image:none;
color:#e5e5e5
}

/* Delete Server */

.delete-server-modal .form-header header {
color:#e5e5e5
}

/* Notifications */

.deprecated-settings-modal .settings-inner {
background-color:#191919
}

.deprecated-settings-modal .settings-actions {
background-color:#191919;
border-top:none
}

/* New User Settings */

.ui-standard-sidebar-view .sidebar-region .scroller {
background-color:#191919
}

.ui-standard-sidebar-view .scroller {
background-color:#232323
}

.ui-standard-sidebar-view .btn-close {
border-radius:12px;
border-color:#383838!important
}

.ui-standard-sidebar-view .btn-close:hover {
background-color:#900!important
}

.ui-standard-sidebar-view .esc-text {
color:#ccc!important
}

.ui-tab-bar.SIDE .ui-tab-bar-header {
color:#e5e5e5;
margin-bottom:15px;
margin-top:15px
}

.ui-tab-bar.SIDE .ui-tab-bar-item {
color:#999!important
}

.ui-tab-bar.SIDE .ui-tab-bar-item.selected, .ui-tab-bar.SIDE .ui-tab-bar-item:active {
background-color:#191919;
color:#e5e5e5!important
}

.ui-tab-bar.SIDE .ui-tab-bar-item:hover {
background-color:#191919;
border-radius:0;
color:#ccc!important
}

.ui-tab-bar.SIDE .ui-tab-bar-separator {
display:none
}

.ui-scroller-wrap .scroller::-webkit-scrollbar-thumb {
background:#383838!important;
border:1px solid transparent!important;
border-radius:0;
background-clip:content-box!important
}

.ui-standard-sidebar-view .scroller::-webkit-scrollbar-track {
background:none!important
}

.private-channels .scroller::-webkit-scrollbar-thumb {
background:rgba(35,35,35,.75)!important;
border:1px solid transparent!important;
border-radius:0;
background-clip:content-box!important
}

/* My Account */

.theme-dark .ui-card-primary {
background-color:#383838;
border-radius:0
}

.theme-dark .avatar-uploader-indicator {
display:none
}

.user-settings-account .user-info-viewing .ui-button {
background-color:#232323
}

.user-settings-account .user-info-viewing .ui-button:hover {
background-color:#900
}

.theme-dark .ui-card-primary.editable {
background-color:#303030
}

.user-settings-account .ui-text-input .input {
background-color:#232323;
border-radius:0;
border:none
}

.ui-form-title .is-required {
color:#e5e5e5
}

.theme-dark .ui-form-divider {
visibility:hidden
}

.user-settings-account .ui-button.small.grow {
background-color:#232323
}

.user-settings-account .ui-button.small.grow:hover {
background-color:#900
}

.theme-dark .ui-card-primary .ui-form-title.h5 {
color:#ccc
}

.theme-dark .ui-card-primary:not(.editable):not(.outline) .ui-form-text {
color:#b2b2b2
}

.margin-top-60 .ui-form-title.h5 {
color:#e5e5e5
}

.user-settings-security .h5.is-enabled {
color:#b2b2b2
}

.user-settings-security .lock-icon {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
}

.user-settings-security .ui-button.small.grow {
background-color:#191919;
border:none;
color:#e5e5e5
}

.user-settings-security .ui-button.small.grow:hover {
background-color:#900;
}

.user-settings-security img.ui-flex-child {
-webkit-filter:greyscale(100%);
filter:grayscale(100%)
}

.theme-dark .user-settings-security .ui-form-text {
color:#b2b2b2
}

.user-settings-security .ui-checkbox-wrapper .ui-checkbox {
border:none;
background-color:#383838;
}

polyline.ui-icon-fg {
stroke:#b2b2b2!important
}

.user-settings-security .checkbox-group .code {
color:#b2b2b2
}

.user-settings-security .ui-button.brand.link {
color:#b2b2b2;
text-decoration:none!important
}

.user-settings-security .ui-button.brand.link:hover {
color:#e5e5e5
}

.user-settings-security .ui-button.brand.link:not(:disabled):hover .ui-button-contents {
background-image:none;
}

/* Privacy & Safety */

.theme-dark .ui-form-title.h5 {
color:#e5e5e5
}

.theme-dark .ui-form-text.style-description {
color:#b2b2b2
}

.theme-dark .ui-card-primary.editable {
background-color:#383838
}

.ui-card.ui-card-primary.flex-horizontal.margin-bottom-8.checked.editable {
background-color:#900!important;
border:1px solid #232323!important;
color:#ccc
}

.ui-checkbox-wrapper .ui-checkbox {
background-color:#232323;
border:solid 1px #191919;
border-radius:0
}

.theme-dark .ui-checkbox.checked {
background-color:#232323;
border:solid 2px #191919;
border-radius:0
}

.ui-radiogroup .title {
color:#ccc!important
}

.theme-dark .ui-radiogroup .desc {
color:#b2b2b2
}

.theme-dark .ui-radiogroup .checked .desc {
color:#b2b2b2
}

.ui-switch-checkbox:checked+.ui-switch {
background-color:#900!important;
}

.ui-switch {
border-radius:0;
background-color:#191919!important;
height:16px;
margin-left:6px;
top:4px
}

.ui-switch:before {
border-radius:0;
background-color:#b2b2b2!important;
height:18px;
width:18px;
top:-1px;
left:6px;
margin-left:-6px
}

.ui-switch-wrapper:not(.disabled):not(.clear):hover .ui-switch-checkbox+.ui-switch {
background-color:#191919
}

.ui-switch-wrapper:not(.disabled):not(.clear):hover .ui-switch-checkbox:checked+.ui-switch {
background-color:#900
}

.ui-form-title.h3.margin-reset.margin-reset.ui-flex-child {
color:#ccc
}

/* Authorized Apps */

.ui-card.ui-card-primary.authed-app.margin-bottom-8.outline {
background-color:#303030
}

.ui-form-text.style-label-bold.ui-flex-child {
color:#e5e5e5
}

.ui-form-text.style-default {
color:#b2b2b2
}

.user-settings-authorized-apps .authed-app .ui-button {
background-color:#232323;
border:none;
color:#e5e5e5
}

.user-settings-authorized-apps .authed-app .ui-button:hover {
background-color:#900
}

/* Connections */

.theme-dark .user-settings-connections .connect-account-btn .connect-account-btn-inner {
background-color:#232323
}

.user-settings-connections-list-description .warning {
color:#ccc
}

.theme-dark .user-settings-connections .connect-account-btn .connect-account-btn-inner:hover {
background-color:#191919
}

.user-settings-connections .connection-header {
background-color:#303030;
border-radius:0
}

.connection-delete {
border:none
}

div.connection[style*='border-color: rgb(203, 33, 32); background-color: rgb(203, 33, 32);'] {
background-color:#282828!important
}

div.connection[style*='border-color: rgb(89, 54, 149); background-color: rgb(89, 54, 149);'] {
background-color:#282828!important
}

div.connection[style*='border-color: rgb(0, 154, 229); background-color: rgb(0, 154, 229);'] {
background-color:#282828!important
}

div.connection[style*='border-color: rgb(24, 35, 50); background-color: rgb(24, 35, 50);'] {
background-color:#282828!important
}

div.connection[style*='border-color: rgb(95, 153, 207); background-color: rgb(95, 153, 207);'] {
background-color:#282828!important
}

div.connection[style*='border-color: rgb(29, 161, 242); background-color: rgb(29, 161, 242);'] {
background-color:#282828!important
}

div.connection[style*='border-color: rgb(2, 31, 37); background-color: rgb(2, 31, 37);'] {
background-color:#282828!important
}

.ui-switch-wrapper.clear .ui-switch {
box-shadow:none
}

.ui-switch-wrapper.clear:not(.disabled):hover .ui-switch {
box-shadow:none
}

.theme-dark .elevation-low {
border-radius:0
}

/* Discord Nitro */

.premium-settings .premium-header .premium-logo {
opacity:.75;
-webkit-filter:greyscale(100%);
filter:grayscale(100%)
}

.premium-settings .premium-header .premium-splash-wumpus {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.premium-settings .premium-header.splash {
border-bottom:none;
background-image:none
}

.premium-settings .premium-feature .premium-feature-icon {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.premium-settings .premium-header .intro-subtitle {
color:#b2b2b2
}

.premium-settings .premium-feature .premium-feature-title {
color:#e5e5e5
}

.premium-settings .premium-feature .premium-feature-description {
color:#b2b2b2
}

.premium-settings .premium-header .premium-options button strong {
color:#e5e5e5
}

.premium-settings .premium-header .premium-options button {
background:#232323;
border:none;
color:#ccc
}

.premium-settings .premium-header .premium-options button:hover {
background:#900!important
}

.premium-settings .premium-header .premium-options button.btn-clear strong {
color:#e5e5e5
}

.premium-settings .premium-header .premium-options button.btn-clear {
background:#232323;
color:#ccc;
border:none
}

.premium-settings .premium-header .premium-options button.btn-clear:hover {
background:#900!important
}

.premium-settings .subscription .premium-tools .ui-button {
margin-right:0px!important
}

.premium-settings .premium-header .premium-free-months {
color:#b2b2b2
}

.premium-payment-modal {
background:#191919
}

.premium-payment-modal .premium-animation {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.premium-payment-modal .premium-payment-form .premium-payment-title {
color:#e5e5e5
}

.premium-payment-modal .premium-payment-form .premium-payment-subtitle {
color:#b2b2b2
}

.fancy-credit-input {
background-color:#232323
}

.fancy-credit-input .card-icon-wrapper {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.fancy-credit-input .cc-number-wrapper .cc-number-placeholder {
color:#b2b2b2
}

.fancy-credit-input .cc-number-wrapper .cc-number {
color:#ccc!important
}

.fancy-credit-input .cc-number-wrapper .cc-number-continue {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.fancy-credit-input .cc-info-wrapper .expiration-placeholder {
color:#b2b2b2;
opacity:
}

.fancy-credit-input input {
color:#ccc;
opacity:
}

.fancy-credit-input input::-webkit-input-placeholder {
color:#b2b2b2!important
}

.premium-payment-modal .premium-payment-button.open:disabled,
.premium-payment-modal .premium-payment-button.open:disabled:hover {
border:none;
background:#232323
}

.premium-payment-modal .premium-payment-button {
background:#232323;
color:#ccc;
box-shadow:none
}

.premium-payment-modal .premium-payment-button:hover {
background:#900
}

.premium-settings .premium-header {
border-bottom:none

}

.premium-settings .subscription .premium-details .premium-title {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.75
}

.premium-settings .subscription.active:before {
display:none
}

.premium-settings .subscription.active {
background:#383838
}

.premium-settings .subscription.active .btn-filled {
background:#232323;
color:#ccc
}

.premium-settings .subscription.active .btn-filled:hover {
background:#900
}

.premium-settings .subscription .premium-details .premium-info {
color:#b2b2b2
}

.premium-settings .payment-subhead {
color:#ccc
}

.card-icon:before {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.premium-settings .payment-method .payment-info .card-info .card-description {
color:#b2b2b2
}

.premium-settings .payment-method .payment-info .card-info .card-description strong {
color:#ccc
}

.premium-settings .payment-method .payment-info .card-info .card-details {
color:#b2b2b2
}

.btn-stroked {
background:#232323;
color:#ccc;
border:none
}

.btn-stroked:hover {
background:#900
}

.premium-settings .billing-history-list li.header-row {
color:#b2b2b2
}

.premium-settings .billing-history-list li:last-of-type {
color:#b2b2b2
}

.alert.form.premium-unsubscribe:before, .alert.form.premium-upgrade:before {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.4
}

.modal-content .form-inner p:first-child {
margin-top:40px
}

.alert.form.premium-upgrade strong {
color:#e5e5e5
}

.premium-settings .payment-method .payment-info .card-tools .ui-button {
border:none;
background:#191919;
color:#ccc
}

.premium-settings .payment-method .payment-info .card-tools .ui-button:hover {
border:none;
background:#900;
color:#ccc
}

/* Voice */

.ui-select .Select-menu {
background-color:#282828
}

.ui-select .Select-value {
background-color:#383838
}

.theme-dark .ui-select .Select-option.is-focused, .theme-dark .ui-select .Select-option:hover {
background-color:#191919!important
}

.theme-dark .ui-slider .slider-bar-fill {
background-color:#900!important
}

.theme-dark .ui-slider .slider-bar {
background-color:#383838!important;
border-radius:0
}

.user-settings-voice .input-sensitivity-toggle.manual .microphone .fill {
background-color:#900
}

.ui-slider .slider-grabber {
background-color:#b2b2b2;
border-color:#191919;
border-radius:0
}

.ui-key-recorder {
background-color:#282828!important;
border-radius:0
}

.ui-key-recorder:hover {
border:1px solid #191919!important
}

.theme-dark .ui-key-recorder.recording {
border:1px solid #191919!important;
-webkit-animation:none!important;
box-shadow:none
}

.ui-button.ghost.grey.min.grow{
background-color:#202020
}

.theme-dark .ui-key-recorder.recording .input {
color:#ccc
}

.ui-key-recorder.recording .ui-button.ghost.grey {
background-color:#191919;
color:#e5e5e5
}

.theme-dark .ui-input-button .input {
color:#ccc
}

.theme-dark .ui-input-button .input::-webkit-input-placeholder {
color:#b2b2b2
}

.ui-button.red.outlined {
background-color:#191919;
border:none;
color:#e5e5e5
}

.ui-button.red.outlined:hover {
background-color:#900
}

/* Overlay */

.ui-card-warning {
background-color:#383838;
border:none;
border-radius:0
}

.theme-dark .ui-card a {
color:#e5e5e5
}

/* Notifications */

.theme-dark .user-settings-notifications .notifications-sound {
box-shadow:inset 0 -.8px 0 0 #303030
}

/* Keybinds */

.user-settings-keybinds .ghost-pill {
background-color:#383838;
border-radius:0;
color:#e5e5e5
}

.ui-button.filled.brand.small.grow {
background-color:#191919
}

.ui-button.filled.brand.small.grow:hover {
background-color:#900
}

.ui-empty-state-image.margin-bottom-40 {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.75
}

.user-settings-keybinds .keybind-group {
border-bottom:none
}

.theme-dark .ui-hover-card:before {
background-color:#303030;
border:none;
border-radius:0
}

.user-settings-keybinds .remove-keybind {
background-color:#282828
}

.user-settings-keybinds .remove-keybind:hover {
background-color:#303030
}

.ui-form-section.keybind-list .ui-select .Select-value {
background-color:#383838;
border:1px solid #191919
}

/* Games */

.theme-dark .user-settings-games .not-detected {
background-color:#383838;
border-radius:0
}

.theme-dark .user-settings-games .now-playing {
background-color:#900;
border-radius:0
}

.now-playing-add .link {
color:#ccc!important
}

.ui-button.link-color.link:not(:disabled):hover .ui-button-contents {
background-image:none;
color:#e5e5e5
}

.theme-dark .add-game-popout {
background-color:#303030;
border-radius:0
}

.theme-dark .add-game-popout-new .ui-select .Select-value {
background-color:#383838
}

.ui-button.filled.brand.medium.grow.disabled {
background-color:#191919
}

.ui-button.filled.brand.medium.grow {
background-color:#191919
}

.ui-button.filled.brand.medium.grow:hover {
background-color:#900
}

.theme-dark .user-settings-games .game {
box-shadow:none
}

.theme-dark .user-settings-games .game-name {
color:#ccc
}

.ui-hover-roll {
color:#b2b2b2
}

.theme-dark .user-settings-games .overlay-status-text {
color:#ccc
}

.theme-dark .user-settings-games .game-name-input:focus {
background-color:#191919!important
}

.theme-dark .user-settings-games .game-name-input:hover {
background-color:#232323
}

.overlay-toggle-icon-off {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.65
}

.overlay-toggle-icon-on {
-webkit-filter:greyscale(100%);
filter:grayscale(100%)
}

.user-settings-games .game .remove-game {
background-color:#282828
}

.user-settings-games .game .remove-game:hover {
background-color:#303030
}

/* Appearance */

.ui-card.ui-card-primary.preview.outline {
height:20px;
margin-top:12px
}

.ui-card.ui-card-primary.preview.outline:before {
content:"DO NOT USE LIGHT THEME WITCHER 3 IS A DARK THEME";
color:#e5e5e5;
font-weight:bold;
position:relative;
top:5px
}

.user-settings-appearance .preview-inner {
display:none
}

/* Streamer Mode */

.ui-form-notice-icon.no-user-drag.ui-flex-child {
-webkit-filter:greyscale(100%);
filter:grayscale(100%)
}

/* Language */

.ui-checkbox.round {
border:none!important
}

.ui-checkbox.round.checked.inverted {
background-color:#383838!important
}

.theme-dark .ui-radio-list-item {
box-shadow:none
}

/* BetterDiscord */

div#bd-settingspane-container.content-region .ui-switch-wrapper.ui-flex-child {
margin-top:25px
}

div#bd-settingspane-container.content-region .ui-form-title.h3.margin-reset.margin-reset.ui-flex-child{
margin-top:25px
}

.ui-standard-sidebar-view #editor-detached h3 {
color:#e5e5e5
}

.ui-standard-sidebar-view #editor-detached button {
background-color:#191919
}

.ui-standard-sidebar-view #editor-detached button:hover {
background-color:#900
}

.bda-right .ui-switch-wrapper.ui-flex-child {
top:80px
}

.ui-standard-sidebar-view .bda-slist li:nth-child(odd) {
background-color:#303030
}

.ui-standard-sidebar-view .bda-slist li {
background-color:#303030;
border-bottom:none
}

.ui-standard-sidebar-view .bda-slist .bda-description {
background-color:#303030;
border-top:none;
color:#ccc;
margin-top:0;
padding-top:12px
}

.content-region .CodeMirror-scroll {
background-color:#303030
}

.CodeMirror-gutter {
background-color:#383838
}

.content-region #bd-customcss-attach-controls {
background-color:#383838
}

.ui-standard-sidebar-view #bd-customcss-attach-controls button {
background-color:#232323
}

.ui-standard-sidebar-view #bd-customcss-attach-controls button:hover {
background-color:#900
}

#bd-customcss-detach-editor #bd-customcss-innerpane .CodeMirror-scroll {
background-color:#303030
}

#bd-customcss-detach-container #bd-customcss-attach-controls {
background-color:#191919
}

.bd-detached-css-editor #bd-customcss-attach-controls button {
background-color:#232323;
border:none!important;
margin-right:5px
}

.bd-detached-css-editor #bd-customcss-attach-controls button:hover {
background-color:#900
}

.bd-pfbtn {
background-color:#191919;
border-radius:0
}

.bd-pfbtn:hover {
background-color:#900
}

.content-region .CodeMirror-simplescroll-vertical div, .content-region .CodeMirror-simplescroll-horizontal div, #bd-customcss-detach-container .CodeMirror-simplescroll-vertical div, #bd-customcss-detach-container .CodeMirror-simplescroll-horizontal div {
background-color:#191919!important;
border:5px solid transparent!important;
border-radius:0!important;
background-clip:content-box
}

/* New Channel Setting */

/* Overview */

textarea.input {
background-color:#282828!important
}

textarea.input:focus {
background-color:#191919!important
}

/* Voice Overview */

.theme-dark .ui-slider .slider-mark-dash {
background-color:#666
}

.theme-dark .ui-slider .slider-mark-value {
color:#b2b2b2
}

.theme-dark .ui-slider .slider-grabber .bubble {
background-color:#383838
}

.theme-dark .ui-slider .slider-grabber .bubble:before {
border-top-color:#b2b2b2
}

/* Permissions */

.ui-tab-bar.SIDE .guild-role.ui-tab-bar-item.selected {
background-color:#383838
}

.ui-tab-bar.SIDE .guild-role.ui-tab-bar-item:hover {
background-color:#303030
}

/* Discord rolling their face on the keyboard css*/

.uovsMu6N {
background-color:#191919;
border:none;
color:#e5e5e5
}

.uovsMu6N:hover {
background-color:#900
}

._2_7ZaCzU {
background-color:#191919;
border:none;
color:#e5e5e5
}

._2_7ZaCzU:hover {
background-color:#900
}

._3eCAFJCK:hover {
border:none!important
}

._3eCAFJCK:active ._4L4hQM5p, ._3eCAFJCK:hover ._4L4hQM5p {
background-image:none
}

._3M8HCxCs, ._1g2WiOIQ, ._2ScJ_PR8, .mJF6nQXH {
color:#ccc
}

._3EZi6xez:active ._4L4hQM5p, ._3EZi6xez:hover ._4L4hQM5p {
background-image:none;
text-decoration:underline
}

._3Y4mXQW7 {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.75
}

.user-settings-security-image {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:.75
}

._1bjP4FEW:active ._4L4hQM5p, ._1bjP4FEW:hover ._4L4hQM5p {
background-image:none;
text-decoration:underline
}

.O9_zYpYo {
color:#b2b2b2
}

._38OOBLD8 {
color:#e5e5e5!important
}

._1rLRshXe {
color:#b2b2b2!important
}

._36NOFatQ, ._1I9VjEuZ {

}

._2VxITA_2 {
border-color:#191919
}

._3wAGwkJ3 {
background-color:#900!important;
color:#e5e5e5
}

._2wYlsUjN {
background-color:#191919
}

.guild-settings-audit-logs-action-filter-popout .ui-scroller-wrap .scroller::-webkit-scrollbar-track {
background:#282828!important
}

.guild-settings-audit-logs-action-filter-popout .ui-scroller-wrap .scroller::-webkit-scrollbar-thumb {
background-color:#383838
}

.theme-dark .ui-popout-list {
background-color:#282828
}

.theme-dark .guild-settings-members-filter-popout .ui-scroller-wrap .scroller::-webkit-scrollbar-track {
background:none!important
}

.theme-light .ui-text-input .input.editable:focus:focus, .theme-light .ui-text-input .input.editable:hover:focus, .theme-light .ui-text-input .input:focus {
border-color:#383838
}

.theme-light .ui-text-input .input, .theme-light .ui-text-input .input.editable:focus, .theme-light .ui-text-input .input.editable:hover {
color:#ccc
}

.user-popout-kick-body {
color:#ccc
}

._288-ZL2S {
background-color:#900;
color:#e5e5e5
}

._1-Lmhcmg {
background-color:#900;
color:#e5e5e5
}

.theme-dark .private-channel-recipients-invite .friend.selected {
background-color:#191919
}

.theme-dark .private-channel-recipients-invite .friend:hover {
background-color:#303030!important
}

.private-channel-recipients-invite .ui-scroller-wrap .scroller::-webkit-scrollbar {
background-color:#191919
}

.private-channel-recipients-invite .ui-scroller-wrap .scroller::-webkit-scrollbar-thumb {
border:20px solid #383838!important
}

.private-channel-recipients-invite .friend .checkbox .checkbox-inner span {
left:-25px!important
}

.modal-content {
border-radius:8px
}

.theme-dark .user-settings-games .now-playing .overlay-status-text {
color:#ccc
}

.popout-menu .popout-menu-icon[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCIgdmlld0JveD0iMCAwIDE2IDE2Ij4KICA8cGF0aCBmaWxsPSIjNzI4OURBIiBkPSJNMTAuNSw3IEMxMi4xODM4MDk1LDcgMTQsNS4yODY2NjY2NyAxNCwzLjU0NTQ1NDU1IEMxNCwxLjgwNDI0MjQyIDEyLjE4MzgwOTUsMCAxMC41LDAgQzguODE2MTkwNDgsMCA3LDEuODA0MjQyNDIgNywzLjU0NTQ1NDU1IEM3LDUuMjg2NjY2NjcgOC44MTYxOTA0OCw3IDEwLjUsNyBaIE0zLDYgTDMsNCBMMiw0IEwyLDYgTDAsNiBMMCw3IEwyLDcgTDIsOSBMMyw5IEwzLDcgTDUsNyBMNSw2IEwzLDYgWiBNMTAuNSw4IEM4LjQ2NTcxNDI5LDggNSw5LjMyODQ4NDg1IDUsMTEuNDI0MjQyNCBMNSwxMyBMMTYsMTMgTDE2LDExLjQyNDI0MjQgQzE2LDkuMzI4NDg0ODUgMTIuNTM0Mjg1Nyw4IDEwLjUsOCBaIiB0cmFuc2Zvcm09Im1hdHJpeCgtMSAwIDAgMSAxNiAyKSIvPgo8L3N2Zz4K");'] {
background-image:url(https://i.imgur.com/NxDeThh.png)!important;
background-size:19px 19px
}

/* Video Calls */

.ui-video-background {
background:#232323;
box-shadow: inset 10px 10px 5px -6px rgba(0,0,0,1)!important;
}

.theme-dark .ui-video {
background:transparent
}

.chat>.title-wrap.title-wrap-dark.call {
background-color:#191919!important
}

.ui-call-avatar.voice {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000;
}

.ui-call-avatar-border.voice.speaking {
border-radius:0
}

.theme-dark .private-channel-call.minimum .private-channel-call-actions .center {
background-color:#232323;
border-radius:0;
border:none
}

.private-channel-call .button-exit.voice {
background-color:#232323;
border-radius:0
}

.private-channel-call .button-exit.voice ._3M8HCxCs:hover {
color:#e5e5e5
}

.private-channel-call .toggle-button {
-webkit-filter:greyscale(100%);
filter:grayscale(100%);
opacity:1
}

.theme-dark .ui-call-avatar.voice .ui-call-avatar-status {
background-color:rgba(0,0,0,.45);
height:26px;
width:26px;
border:none;
border-radius:6px;
top:0;
left:0
}

.theme-dark .ui-quick-select-popout {
background-color:#191919;
border-radius:0
}

.theme-dark .ui-quick-select-popout-option:hover {
background-color:#282828;
}

.small-popout-box {
border-radius:0
}

/* Avatars */

.private-channels .channel .avatar-small {
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
border-radius:0
}

.guild-channels .channel-voice-states li .avatar-small {
border-radius:0px;
box-shadow:-1px 1px 2px #000,inset -1px 1px 2px #000,
inset 1px -1px 2px #000,1px -1px 2px #000!important;
border:none
}

.account .avatar-small {
opacity:1;
right:-105px;
top:-25px;
border-radius:0;
box-shadow:-1px 1px 2px #000,inset -1px 1px 2px #000,
inset 1px -1px 2px #000,1px -1px 2px #000!important
}

.message-group .avatar-large {
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
border-radius:0;
margin-left:6px;
margin-bottom:8px;
background-color:#232323
}

#friends .friends-table .friends-row .friends-column-name .avatar-small {
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
border-radius:0;
margin-left:6px
}

#friends .friends-table .friends-row .friends-column-guilds .avatar-small {
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
border-radius:0
}

#friends .friends-table .friends-row .friends-suggestion-inner .avatar-large {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
margin-left:10px
}

.private-channel-recipients-invite .friend .avatar-small {
border-radius:0px;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

.avatar-xxlarge {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

.avatar-xsmall {
border-radius:0px;
box-shadow:-1px 1px 2px #000,inset -1px 1px 2px #000,
inset 1px -1px 2px #000,1px -1px 2px #000!important
}

.channel-members .avatar-small {
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
border-radius:0
}

.user-popout .avatar-wrapper .avatar-popout {
border:none;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
border-radius:0;
background-color:#232323
}

#autocomplete-popout .row .avatar-small {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

.avatar-uploader .avatar-uploader-inner {
color:#b2b2b2;
border-radius:0px!important;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
border:none!important;
background-color:#232323;
background-repeat:no-repeat
}

.avatar-uploader .avatar-uploader-inner:hover {
color:#b2b2b2;
border-radius:0px!important;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
border:none!important;
opacity:.85
}

.instant-invites .instant-invites-list .instant-invite .show-channel .avatar-small {
border-radius:0;
box-shadow:-1px 1px 2px #000,inset -1px 1px 2px #000,
inset 1px -1px 2px #000,1px -1px 2px #000!important
}

.instant-invites .instant-invites-list .instant-invite .member .avatar-small {
border-radius:0;
box-shadow:-1px 1px 2px #000,inset -1px 1px 2px #000,
inset 1px -1px 2px #000,1px -1px 2px #000!important
}

.guild-settings-modal-members .guild-settings-modal-list .member .avatar-small {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

#settings-roles .roles li .avatar-small {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

#user-profile-modal .avatar-profile {
border:hidden;
background-color:rgba(0,0,0,0);
border-radius:0px;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

#user-profile-modal .guilds .avatar-large {
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
border-radius:0px
}

.webhooks .webhook .webhook-header .avatar-large {
border-radius:0!important;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

#rtc-debug-modal #users-section .user-list .avatar-small {
border-radius:0;
box-shadow:-1px 1px 2px #000,inset -1px 1px 2px #000,
inset 1px -1px 2px #000,1px -1px 2px #000!important
}

.search-popout .option.user .display-avatar {
box-shadow: -1px 1px 3px #000,
inset -1px 1px 3px #000,inset 1px -1px 3px #000,1px -1px 3px #000!important;
border-radius:2px
}

.invite-modal .avatar-xxxlarge {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

.theme-dark .guild-settings-base-section .avatar-uploader .avatar-uploader-inner {
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
}

.ui-audit-log .ui-avatar {
border-radius:4px;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
}

.guild-settings-members-member .ui-avatar {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important;
}

.guild-settings-banned-user .ui-avatar {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

.guild-settings-members-member .member-avatar {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

._3yh-62Td {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000!important
}

.create-guild-container .avatar-uploader .avatar-uploader-inner {
box-shadow:none!important;
width:128px!important;
height:128px!important
}

/* Bug Fixes */

.container-RYiLUQ {
background:transparent
}

.container-iksrDt {
background-color:#232323;
height:95px;
border-top:6px solid #900
}

.accountDetails-15i-_e .username {
display:none
}

.accountDetails-15i-_e .discriminator {
font-size:16px;
padding-left:35px;
top:11px;
position:relative;
color:#e5e5e5;
opacity:1
}

.container-iksrDt .avatar-small {
border-radius:0;
box-shadow:-1px 1px 4px #000,inset -1px 1px 4px #000,
inset 1px -1px 4px #000,1px -1px 4px #000;
width:38px;
height:38px;
background-size:38px 38px;
left:90px;
top:-22px
}

.container-iksrDt .horizontal-2VE-Fw {
position:relative;
top:33px;
left:-70px
}

.container-RYiLUQ .contentSelectedText-3j5CXt {
background-color:#232323;
border-radius:0
}

.container-RYiLUQ .contentHoveredText-2HYGIY {
background:none
}

.nameHoveredText-2F
