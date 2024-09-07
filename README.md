/* FONT (From Google Fonts) */
﻿
@import url('https://fonts.googleapis.com/css2?family=Shadows+Into+Light&display=swap'');
﻿
/* BACKGROUND */
﻿
body {
	background: url('https://ibb.co/1nQkZf0') center center fixed;
	background-size: 100%;
	font-family: "Shadows Into Light", cursive;
	color: #2e2a2b
}
﻿
/* MAIN PANEL */
﻿
/* RIGHT SIDE */
.container.main {
	background: rgba(216, 210, 208, 0.5);
	border: none;
	box-shadow: none;
	border-radius: 0px
}
﻿
/* LEFT SIDE */
.col-md-9 {
	background: none;
        border-right: none
}
﻿
/* TOPBAR ("Welcome back, ___") */
﻿
.topbar {
	background: rgba(68, 72, 120, 0.5);
	border: none;
	border-top: none;
	color: #e7c2ab;
	border-radius: 0px;
}
﻿
/* NAVBAR (Den/Crossroads/Etc.) */
﻿
.navbar {
	background: rgba(216, 210, 208, 0.5);
	border-bottom: none;
	color: #444878;
	border-radius: 0px
}
﻿
/* NAVBAR BUTTON TEXT COLOR */
﻿
.navbar li a {
	color: #444878 !important
}
﻿
/* NAVBAR BUTTON HOVER */
﻿
.navbar li a:hover {
	background: rgba(216, 210, 208, 0.5) !important;
	border-bottom: none;
	color: #444878 !important;
	border-radius: 0px
}
﻿
/* BREADCRUMB (Home / Den) */
﻿
.breadcrumb {
	background: rgba(161, 172, 190, 0.5) !important;
        border: none;
	border-radius: 0px
}
﻿
/* BREADCRUMB TEXT */
﻿
.breadcrumb .active {
	color: #444878
}
﻿
/* BOOKMARK BUTTON */
﻿
input.floatright, input.floatright:hover {
	background: rgba(68, 72, 120, 0.5) !important;
        border: none !important;
	border-radius: 0px;
	color: #e7c2ab !important;    
}
﻿
/* SWITCH ACCOUNT BUTTON */
﻿
button.button, button.button:hover {
	background: rgba(68, 72, 120, 0.5);
        border: none !important;
	border-radius: 0px;
        text-shadow: none !important;
	color: #e7c2ab !important
}
﻿
/* ALERTS (ie. "Your lionesses have returned from hunting!") */
﻿
.alert,
.alert-warning,
.alert-danger {
	background: rgba(192, 143, 148, 0.5) !important;
	border: none;
	color: #553a63;
	border-radius: 0px !important
}
﻿
/* BIGGEST HEADER ("___"'s DEN) */
﻿
h1 {
	color: #444878;
	font-size: 90px;
	text-align: center;
        font-family: "Shadows Into Light", cursive;
}
﻿
﻿
/* MEDIUM HEADER */
﻿
h2 {
	color: #444878;
	font-size: 24px;
	text-align: center
}
﻿
﻿
/* SMALL HEADER */
﻿
h3 {
	color: #444878 !important;
	font-size: 14px !important
}
﻿
/* RIGHT SIDE PANEL HEADER */
﻿
.sidebar h3 {
	color: #444878 !important;
        font-size: 26px !important;
        font-family: "Shadows Into Light", cursive;
}
﻿
/* RIGHT SIDE PANELS */
.panel {
	background: rgba(161, 172, 190, 0.5) !important;
	box-shadow: none !important;
	border: none !important;
	color: #444878 !important;
	border-radius: 0px
}
﻿
/* ENERGY BAR BACKGROUND */
.progress {
	background: rgba(216, 210, 208, 0.5);
	color: #444878 !important;
	border-radius: 0px !important
}
﻿
/* ENERGY BAR COLOR */
.progress-bar {
	background: rgba(161, 172, 190, 0.5);
	color: #444878 !important;
	border-radius: 0px !important
}
﻿
/* ENERGY BAR TEXT */
.progress div {
	color: #444878 !important
}
﻿
/* CHAT */
﻿
.s-chat-message:nth-child(even) /* Even Numbered Messages */ {
	background: rgba(231, 194, 171, 0.5) !important;
        color: #444878 !important;
	border: none !important
}
﻿
.s-chat-message:nth-child(odd) /* Odd Numbered Messages */ {
	background: rgba(216, 210, 208, 0.5) !important;
        color: #444878 !important;
	border: none !important
}
﻿
.s-chat-message__pinned /* Pinned Message */ {
	background: rgba(192, 143, 148, 0.5) !important;
        color: #444878 !important;
	border: none !important
}
﻿
.s-chat-message_timestamp /* Timestamps */ {
	color: #444878 !important;
}
﻿
div#chatMessageContainer {
	border: none !important;
}
﻿
button#label_currentChannel /* Channel Button ie. Main, Sales */ {
	background: rgba(68, 72, 120, 0.5) !important;
        color: #e7c2ab !important;
	border: none !important
}
﻿
/* LION INFO TABLE (Level, Stats, Territory Count, Etc.) */
﻿
﻿
/* PANEL BACKGROUND COLOR */
﻿
.table {
	background: rgba(161, 172, 190, 0.5);
	border: none !important;
	border-collapse: separate;
	border-radius: 0px
}
﻿
﻿
/* HEADERS COLOR (King Name + Title, "There are _ lions with mutations in _'s pride.") */
﻿
.top,
.bottom,
th {
	background: rgba(68, 72, 120, 0.5) !important;
	color: #e7c2ab !important;
	border-radius: 0px
}
﻿
td.bottom a {
        text-decoration: none !important
}
﻿
/* Color behind "Level, Stats, Branch, Territory" etc. */
﻿
.inner-table .left {
	background: rgba(216, 210, 208, 0.5) !important;
        color: #444878;
	border-radius: 0px
}
﻿
﻿
/* Color behind the number of all of the things above */
﻿
.inner-table .right {
	background: none;
	border-radius: 0px !important
}
﻿
td.right {
	border-radius: 0px !important
}
﻿
/* IGNORE */
.right_odd {
	background: none !important
}
﻿
/* Affects the color behind "_ Unsorted", "_ Pregnant Lionesses", "View Pride Overview", and cave/mound names */
﻿
.cave-grid,
.mound-grid {
	background: rgba(231, 194, 171, 0.5);
	border: none !important;
	border-radius: 0px !important
}
﻿
/* FEED ALL, PLAY ALL */
﻿
.feature {
	background: rgba(161, 172, 190, 0.5) !important;
	color: #444878 !important;
	border: 1px solid #000000 !important;
	border-radius: 0px !important
}
﻿
/* "King Dynasty, Pride Dynasty, Achievements, Showcase" Panels */
﻿
.feature,
div.left {
	background: rgba(161, 172, 190, 0.5);
	border: none;
	border-radius: 0px !important
}
﻿
/* Block of color behind "Territory Description, Player Name, Avatar URL" etc. */
﻿
.table .left {
	background: rgba(216, 210, 208, 0.5);
        border-radius: 0px
}
﻿
/* Color behind the content of the elements listed above */
﻿
input,
select,
textarea {
	background: rgba(216, 210, 208, 0.5) !important;
	border: none !important;
	border-radius: 0px !important;
	color: #444878 !important;
	box-shadow: none !important;
	text-shadow: none !important
}
﻿
/* ACCOUNT OPTIONS PANELS  (Friend Requests Toggles, etc.) */
﻿
.item-header {
	background: rgba(231, 194, 171, 0.5) !important;
	color: #444878  !important;
	border-radius: 0px !important;
}
﻿
.item {
	background: rgba(161, 172, 190, 0.5) !important;
	border: none !important;
	border-radius: 0px !important
}
﻿
/* ACCOUNT OPTIONS ON/OFF TOGGLE SWITCH */
﻿
div.slider.round /* Background */ {
	background: #e8b078 !important
}
﻿
div.slider.round::before /* Circle Part */ {
	background: #a1acbe !important
}
﻿
/* Copyright, Terms of Service, CoC, etc. */
﻿
div.container.footer.center.white.visible-lg.visible-md.visible-sm, div.container.footer.center.white.visible-lg.visible-md.visible-sm a {
        color: #d8d2d0 !important;
        text-shadow: none !important
}
﻿
/* LINK COLOR */
﻿
a:link,
a:visited {
	color: #444878 !important
}
﻿
/* LINK HOVER COLOR */
﻿
a:hover {
	color: #553a63 !important
}
﻿
﻿
/* BOX CONTAINER */
﻿
.boxcontainer {
	background: none;
	height: auto;
	padding: 0px;
	justify-content: center;
	display: flex
}
﻿
/* BOXES */
﻿
.smallbox {
	float: left;
	background: rgba(231, 194, 1171, 0.5);
	color: #444878;
	padding: 10px;
	border: none;
	border-radius: 0px;
	margin: 10px;
	height: 150px;
	width: 28.4%;
	overflow: auto
}
﻿
.mediumbox {
	float: left;
	background: rgba(161, 172, 190, 0.5);
	color: #444878;
	padding: 10px;
	border: none;
	border-radius: 0px;
	margin: 10px;
	height: 150px;
	width: 43.8%;
	overflow: auto
}
﻿
.largebox {
	float: left;
	background: rgba(216, 210, 208, 0.5);
	color: #444878;
	padding: 10px;
	border: none;
	border-radius: 0px;
	margin: 10px;
	height: 150px;
	width: 90%;
	overflow: auto
}
﻿
/* HOVER BOXES */
﻿
.smallhoverbox {
	float: left;
	background: rgba(231, 194, 171, 0.5);
	color: #444878;
	padding: 10px;
	border: none;
	border-radius: 0px;
	margin: 10px;
	height: 50px;
	width: 28.4%;
	overflow: auto;
        transition: 3s
}
﻿
.smallhoverbox:hover {
	height: 150px;
	width: 28.4%;
}
﻿
.mediumhoverbox {
	float: left;
	background: rgba(161, 172, 190, 0.5);
	color: #444878;
	padding: 10px;
	border: none;
	border-radius: 0px;
	margin: 10px;
	height: 50px;
	width: 43.8%;
	overflow: auto;
        transition: 3s
}
﻿
.mediumhoverbox:hover {
	height: 150px;
	width: 43.8%;
}
﻿
.largehoverbox {
	float: left;
	background: rgba(216, 210, 208, 0.5);
	color: #444878;
	padding: 10px;
	border: none;
	border-radius: 0px;
	margin: 10px;
	height: 150px;
	width: 90%;
	overflow: auto;
        transition: 3s
}
﻿
.largehoverbox:hover {
	height: 150px;
	width: 90%;
}
﻿
/* SCROLL BAR */
﻿
/* WIDTH */
﻿
::-webkit-scrollbar {
	width: 10px
}
﻿
﻿
/* BACKGROUND */
﻿
::-webkit-scrollbar-track {
	background: #444878
}
﻿
﻿
/* "THUMB" */
﻿
::-webkit-scrollbar-thumb {
	background: #d8d2d0;
	border-radius: 0px
}
﻿
﻿
/* LION AND USER AVATAR OPACITY */
﻿
div#lion_image {
	opacity: 1
}
﻿
table#player img {
	opacity: 1
}
﻿
﻿
/* CIRCULAR LION AND USER AVATAR */
﻿
div#lion_image {
	border-radius: 50% !important;
	overflow: hidden;
	margin-top: 15px; /* May need adjusting */
	margin-left: 12px /* May need adjusting */
}
﻿
table#player img {
	border-radius: 50% !important;
	overflow: hidden
}
﻿
/* CAVE / MOUND IMAGES */
﻿
div.cave-grid>img /* Pregnant Lionesses */ {
	content: url('https://ibb.co/Yj552gK') !important
}

a[href$="lionoverview.php?id=297802 ID"]>div.cave-grid>img /* Pride Overview */ {
	content: url('https://ibb.co/4pkPVkY') !important
}
﻿
a[href$="unsorted.php?id=297802"]>div.cave-grid>img /* Unsorted */ {
	content: url('https://ibb.co/qCWHGzw') !important
}
﻿
.mound-grid img /* Mound(s) */ {
	background: url("https://ibb.co/NFcNDyQ");
	width: 0;
	height: 0;
	padding-top: 80px;
	padding-right: 130px
}
﻿
/* MAKES BOXES/DESCRIPTION SHOW ON MOBILE */
﻿
@media only screen and (max-width: 767px) {
        .container.main .hidden-xs {
            display: block !important;
        }
}
﻿
@media only screen and (max-width: 991px) and (min-width: 768px) {
	display: block !important;
}
﻿
@media only screen and (min-width: 1200px) {
		div.quote {
			width: 790px;
		}
	}
