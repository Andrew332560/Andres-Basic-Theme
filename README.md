# Andres-Basic-Theme
Andres Basic Theme For BetterDiscord

How to Download? Download BetterDiscord go to Plugins Open the Folder Now Download The Channel Tabs.js click on the Folder and that's it and the BetterDiscord Theme is missing go on to Themes Open the Folder Download the Andres Basic Theme click on the Folder and that's it!

link below

Download in Releases
https://github.com/AndresStudies51/Andres-Basic-Theme/releases/tag/theme

# Contributors

For information on contributing to this project, please see [CONTRIBUTING.md](/CONTRIBUTING.md).

-> Luisito8596 in Charge of Errors

# Code

```
/**
 * @name Andres Basic Theme
 * @author Andres Studies
 * @version 1.0.1
 * @description Andres Basic Theme. by Andres Studies
 * @source https://github.com/AndresStudies51
*/


@import url("https://luckfire.github.io/amoled-cord/src/amoled-cord.css");
@import url(https://discord-custom-covers.github.io/usrbg/dist/usrbg.css);
@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/_res/SettingsIcons.css);
@import url("https://discordstyles.github.io/HorizontalServerList/dist/HorizontalServerList.css");
@import url('https://adaelynxiv.github.io/RoundedDark/src/roundeddark.css');
@import url("https://discordstyles.github.io/RadialStatus/dist/RadialStatus.css");
@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/EmojiReplace/base/JoyPixels.css);

:root {
  --rs-small-spacing: 2px; /* Gap between avatar and status for members list/dms | MUST end in px */
  --rs-medium-spacing: 3px; /* Gap between avatar and status for User popout | MUST end in px */
  --rs-large-spacing: 4px; /* Gap between avatar and status for User profiles | MUST end in px */

  --rs-small-width: 2px; /* Thickness of status border for members list/dms | MUST end in px */
  --rs-medium-width: 3px; /* Thickness of status border for User popout | MUST end in px */
  --rs-large-width: 4px; /* Thickness of status border for User profile | MUST end in px */

  --rs-avatar-shape: 50%; /* 50% for round - 0% for square */

  --rs-online-color: #43b581; /* Colour for online status */
  --rs-idle-color: #faa61a; /* Colour for idle status */
  --rs-dnd-color: #f04747; /* Colour for dnd status */
  --rs-offline-color: #636b75; /* Colour for offline status */
  --rs-streaming-color: #643da7; /* Colour for streaming status */
  --rs-invisible-color: #747f8d; /* Colour for invisible status - Note: this will only show for your own invisibility */
  --rs-phone-color: var(--rs-online-color); /* Colour of the ring and phone icon when a user is on their phone |  */

  --rs-phone-visible: block; /* Visibility of the phone icon next to a users avatar. | block = visible | none = hidden */
}

/* #  Plugin Fixes/Edits  # */
/* Uncomment a plugin Import URL if you use a plugin that's listed here */

/* Channel Tabs: */
/*@import url('https://adaelynxiv.github.io/RoundedDark/src/plugins/channeltabs.css');*/

/* Customizable Variables */
@import url('https://fonts.googleapis.com/css2?family=Karla:wght@400;500;600;700&display=swap');

/* Coloured Folder Icons by CapnKitten (Gibbu#1211 edit)*/
/* If you wish to remove the Folder Icons; or if it breaks one of your plug-ins, remove everything under here: */
.closedFolderIconWrapper-3tRb2d {
    display: none;
}
.folderIconWrapper-1oRIZr:not([style=""])::before {
    position: absolute;
    content: "";
    width: 18px;
    height: 18px;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    margin: auto;
    background-color: inherit;
    -webkit-mask: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/solid/folder.svg) no-repeat;
    mask: url(https://capnkitten.github.io/BetterDiscord/Themes/Material-Discord/files/icons/solid/folder.svg) no-repeat;
    transform: scale(1.3335);
    filter: brightness(1.5) saturate(1.5);
}

.platform-win .typeWindows-2-g3UY {
    top: 13px;
    left: -11px;
}
#channelTabs-container{padding:7px;}
.chat-2ZfjoI, .sidebar-1tnWFu{margin-top:var(--spacing);}
.wrapper-1_HaEi{margin-top:var(--spacing);}
.app-2CXKsg{background:var(--blurple);}
#channelTabs-container{
    border-radius:var(--radius);
    margin-bottom:calc(var(--spacing) - 2px);
    padding:6px!important;
}
#channelTabs-settingsMenu{
    margin-right:15px!important;
    right: 110px!important;
    top: 6px!important;
}
.platform-win .winButton-3UMjdg {
    border-radius:var(--radius);
    height:40px!important;
}
.platform-win .container-ZMc96U {padding-right:8px;}
.channelTabs-tabContainer{max-width:85vw}

.platform-win .typeWindows-2-g3UY {
	top:0px!important;
	height:25px!important;
	left: calc((var(--spacing) - var(--spacing)) - (var(--spacing) + 11px));
}
.platform-win .winButtonClose-3Q8ZH5, .winButtonMinMax-3RsPUg{
    top: calc(var(--spacing) + 2px)!important;
}

/* Bottom HorizontalServerList. Simply remove the comments surrounding the @import to enable it. */
/* @import url("https://discordstyles.github.io/Addons/bottomhsl.css"); */

:root {
  --HSL-server-icon-size: 40px;  /* Size of the server icons | DEFAULT: 40px */
  --HSL-server-spacing: 10px;  /* Spacing between each server icon | DEFAULT: 10px */
  --HSL-server-direction: column; /* Direct of the server list. | Options: column, column-reverse | DEFAULT: column */
}

:root {
  /* ignore these, unless you wanna mess with them, then go for it. they may be removed at any time, though. */
  --lightness-600-660: 0%;
  --lightness-700-760: 0%;
  --lightness-800-860: 0%;
  --lightness-900: 0%;
  --primary-100: hsl(var(--primary-100-hsl)/1);
  --primary-100-hsl: 0 calc(var(--saturation-factor, 1)*0%) 97.6%;
  --primary-130: hsl(var(--primary-130-hsl)/1);
  --primary-130-hsl: 220 calc(var(--saturation-factor, 1)*13%) 95.5%;
  --primary-160: hsl(var(--primary-160-hsl)/1);
  --primary-160-hsl: 210 calc(var(--saturation-factor, 1)*11.1%) 92.9%;
  --primary-200: hsl(var(--primary-200-hsl)/1);
  --primary-200-hsl: 216 calc(var(--saturation-factor, 1)*9.8%) 90%;
  --primary-230: hsl(var(--primary-230-hsl)/1);
  --primary-230-hsl: 210 calc(var(--saturation-factor, 1)*9.1%) 87.1%;
  --primary-260: hsl(var(--primary-260-hsl)/1);
  --primary-260-hsl: 214 calc(var(--saturation-factor, 1)*8.4%) 83.7%;
  --primary-300: hsl(var(--primary-300-hsl)/1);
  --primary-300-hsl: 210 calc(var(--saturation-factor, 1)*9.3%) 78.8%;
  --primary-330: hsl(var(--primary-330-hsl)/1);
  --primary-330-hsl: 215 calc(var(--saturation-factor, 1)*8.8%) 73.3%;
  --primary-345: hsl(var(--primary-345-hsl)/1);
  --primary-345-hsl: 214 calc(var(--saturation-factor, 1)*8.4%) 67.5%;
  --primary-360: hsl(var(--primary-360-hsl)/1);
  --primary-360-hsl: 214 calc(var(--saturation-factor, 1)*8.1%) 61.2%;
  --primary-400: hsl(var(--primary-400-hsl)/1);
  --primary-400-hsl: 223 calc(var(--saturation-factor, 1)*5.8%) 52.9%;
  --primary-430: hsl(var(--primary-430-hsl)/1);
  --primary-430-hsl: 229 calc(var(--saturation-factor, 1)*4.8%) 44.9%;
  --primary-460: hsl(var(--primary-460-hsl)/1);
  --primary-460-hsl: 228 calc(var(--saturation-factor, 1)*5.2%) 38%;
  --primary-500: hsl(var(--primary-500-hsl)/1);
  --primary-500-hsl: 228 calc(var(--saturation-factor, 1)*6%) 32.5%;
  --primary-530: hsl(var(--primary-530-hsl)/1);
  --primary-530-hsl: 227 calc(var(--saturation-factor, 1)*6.5%) 27.3%;
  --primary-560: hsl(var(--primary-560-hsl)/1);
  --primary-560-hsl: 225 calc(var(--saturation-factor, 1)*6.7%) 23.5%;
  --primary-600: hsl(var(--primary-600-hsl)/1);
  --primary-600-hsl: 223 calc(var(--saturation-factor, 1)*6.7%) calc(var(--lightness-600-660, 0) + 20.6%);
  --primary-630: hsl(var(--primary-630-hsl)/1);
  --primary-630-hsl: 220 calc(var(--saturation-factor, 1)*6.5%) calc(var(--lightness-600-660, 0) + 18%);
  --primary-645: hsl(var(--primary-645-hsl)/1);
  --primary-645-hsl: 220 calc(var(--saturation-factor, 1)*7%) calc(var(--lightness-600-660, 0) + 16.9%);
  --primary-660: hsl(var(--primary-660-hsl)/1);
  --primary-660-hsl: 228 calc(var(--saturation-factor, 1)*6.7%) calc(var(--lightness-600-660, 0) + 14.7%);
  --primary-700: hsl(var(--primary-700-hsl)/1);
  --primary-700-hsl: 225 calc(var(--saturation-factor, 1)*6.3%) calc(var(--lightness-700-760, 0) + 12.5%);
  --primary-730: hsl(var(--primary-730-hsl)/1);
  --primary-730-hsl: 225 calc(var(--saturation-factor, 1)*7.1%) calc(var(--lightness-700-760, 0) + 11%);
  --primary-760: hsl(var(--primary-760-hsl)/1);
  --primary-760-hsl: 220 calc(var(--saturation-factor, 1)*6.4%) calc(var(--lightness-700-760, 0) + 9.2%);
  --primary-800: hsl(var(--primary-800-hsl)/1);
  --primary-800-hsl: 220 calc(var(--saturation-factor, 1)*8.1%) calc(var(--lightness-800-860, 0) + 7.3%);
  --primary-830: hsl(var(--primary-830-hsl)/1);
  --primary-830-hsl: 240 calc(var(--saturation-factor, 1)*4%) calc(var(--lightness-800-860, 0) + 4.9%);
  --primary-860: hsl(var(--primary-860-hsl)/1);
  --primary-860-hsl: 240 calc(var(--saturation-factor, 1)*7.7%) calc(var(--lightness-800-860, 0) + 2.5%);
  --primary-900: hsl(var(--primary-900-hsl)/1);
  --primary-900-hsl: 0 calc(var(--saturation-factor, 1)*0%) calc(var(--lightness-900, 0) + 0.8%);
}

.theme-dark,
html.theme-dark .theme-light .root_a28985,
.theme-light.popout_a6e77f {
  --activity-card-background: var(--primary-830) !important;
  --android-navigation-bar-background: var(--primary-830) !important;
  --android-navigation-scrim-background: hsl(var(--primary-830-hsl)/0.5) !important;
  --android-ripple: hsl(var(--white-500-hsl)/0.07) !important;
  --background-accent: var(--primary-760) !important;
  --background-floating: var(--primary-830) !important;
  --background-message-hover: hsl(var(--primary-900-hsl)/0.06) !important;
  --background-mobile-primary: var(--black-500) !important;
  --background-mobile-secondary: var(--primary-860) !important;
  --background-modifier-accent: hsl(var(--primary-760-hsl)/0.48) !important;
  --background-modifier-active: hsl(var(--primary-760-hsl)/0.48) !important;
  --background-modifier-hover: hsl(var(--primary-760-hsl)/0.4) !important;
  --background-modifier-selected: hsl(var(--primary-760-hsl)/0.6) !important;
  --background-nested-floating: var(--primary-830) !important;
  --background-primary: #000000 !important;
  --background-secondary: var(--primary-830) !important;
  --background-secondary-alt: var(--primary-800) !important;
  --background-tertiary: var(--primary-860) !important;
  --bug-reporter-modal-submitting-background: hsl(var(--primary-800-hsl)/0.6) !important;
  --button-outline-brand-background: hsl(var(--white-500-hsl)/0) !important;
  --button-outline-brand-text: var(--white-500) !important;
  --button-outline-brand-text-active: var(--white-500) !important;
  --button-outline-brand-text-hover: var(--white-500) !important;
  --button-outline-danger-background: hsl(var(--white-500-hsl)/0) !important;
  --button-outline-danger-background-active: var(--red-460) !important;
  --button-outline-danger-background-hover: var(--red-430) !important;
  --button-outline-danger-border: var(--red-400) !important;
  --button-outline-danger-border-active: var(--red-430) !important;
  --button-outline-danger-border-hover: var(--red-430) !important;
  --button-outline-danger-text: var(--white-500) !important;
  --button-outline-danger-text-active: var(--white-500) !important;
  --button-outline-danger-text-hover: var(--white-500) !important;
  --button-outline-positive-background: hsl(var(--white-500-hsl)/0) !important;
  --button-outline-positive-text: var(--white-500) !important;
  --button-outline-positive-text-active: var(--white-500) !important;
  --button-outline-positive-text-hover: var(--white-500) !important;
  --button-outline-primary-background: var(--primary-700) !important;
  --button-outline-primary-background-active: var(--primary-600) !important;
  --button-outline-primary-background-hover: var(--primary-630) !important;
  --button-outline-primary-border: var(--primary-700) !important;
  --button-outline-primary-border-active: var(--primary-600) !important;
  --button-outline-primary-border-hover: var(--primary-630) !important;
  --button-outline-primary-text: var(--white-500) !important;
  --button-outline-primary-text-active: var(--white-500) !important;
  --button-outline-primary-text-hover: var(--white-500) !important;
  --button-secondary-background: var(--primary-700) !important;
  --button-secondary-background-active: var(--primary-600) !important;
  --button-secondary-background-disabled: var(--primary-700) !important;
  --button-secondary-background-hover: var(--primary-630) !important;
  --channel-icon: var(--primary-400) !important;
  --channel-text-area-placeholder: var(--primary-400) !important;
  --channels-default: var(--primary-360) !important;
  --channeltextarea-background: var(--primary-830) !important;
  --chat-background: var(--black-500) !important;
  --chat-border: var(--primary-700) !important;
  --chat-input-container-background: var(--primary-600) !important;
  --deprecated-card-bg: hsl(var(--primary-700-hsl)/0.6) !important;
  --deprecated-card-editable-bg: hsl(var(--primary-700-hsl)/0.3) !important;
  --deprecated-quickswitcher-input-background: var(--primary-400) !important;
  --deprecated-quickswitcher-input-placeholder: hsl(var(--white-500-hsl)/0.3) !important;
  --deprecated-store-bg: var(--primary-600) !important;
  --deprecated-text-input-bg: var(--primary-700) !important;
  --deprecated-text-input-border: hsl(var(--black-500-hsl)/0.3) !important;
  --deprecated-text-input-border-disabled: var(--primary-700) !important;
  --deprecated-text-input-border-hover: var(--primary-900) !important;
  --deprecated-text-input-prefix: var(--primary-200) !important;
  --display-banner-overflow-background: hsl(var(--primary-700-hsl)/0.5) !important;
  --forum-post-extra-media-count-container-background: hsl(var(--primary-660-hsl)/0.8) !important;
  --forum-post-tag-background: hsl(var(--primary-660-hsl)/0.9) !important;
  --header-primary: var(--primary-130) !important;
  --header-secondary: var(--primary-345) !important;
  --home-background: var(--primary-760) !important;
  --home-card-resting-border: hsl(var(--transparent-hsl)/0) !important;
  --info-danger-text: var(--white-500) !important;
  --info-help-text: var(--white-500) !important;
  --info-positive-text: var(--white-500) !important;
  --info-warning-text: var(--white-500) !important;
  --input-background: var(--primary-800) !important;
  --input-placeholder-text: var(--input-placeholder-text-dark) !important;
  --interactive-active: var(--primary-130) !important;
  --interactive-hover: var(--primary-230) !important;
  --interactive-muted: var(--primary-500) !important;
  --interactive-normal: var(--primary-345) !important;
  --live-stage-tile-border: hsl(var(--primary-500-hsl)/0.6) !important;
  --logo-primary: var(--white-500) !important;
  --mention-background: hsl(var(--brand-500-hsl)/0.3) !important;
  --modal-background: var(--primary-860) !important;
  --modal-footer-background: var(--primary-900) !important;
  --profile-gradient-message-input-border: hsl(var(--primary-500-hsl)/0.48) !important;
  --profile-gradient-note-background: hsl(var(--black-500-hsl)/0.3) !important;
  --profile-gradient-overlay: hsl(var(--black-500-hsl)/0.6) !important;
  --profile-gradient-overlay-synced-with-user-theme: hsl(var(--black-500-hsl)/0.8) !important;
  --profile-gradient-profile-body-background-hover: hsl(var(--white-500-hsl)/0.16) !important;
  --profile-gradient-role-pill-background: hsl(var(--primary-660-hsl)/0.5) !important;
  --profile-gradient-role-pill-border: hsl(var(--white-500-hsl)/0.2) !important;
  --profile-gradient-section-box: hsl(var(--black-500-hsl)/0.45) !important;
  --scrollbar-auto-scrollbar-color-thumb: var(--primary-700) !important;
  --scrollbar-auto-scrollbar-color-track: var(--primary-630) !important;
  --scrollbar-auto-thumb: var(--primary-600) !important;
  --scrollbar-auto-track: var(--primary-860) !important;
  --scrollbar-thin-thumb: var(--primary-700) !important;
  --scrollbar-thin-track: hsl(var(--black-500-hsl)/0) !important;
  --spoiler-hidden-background: var(--primary-700) !important;
  --spoiler-revealed-background: var(--primary-660) !important;
  --status-danger-text: var(--white-500) !important;
  --status-positive-text: var(--white-500) !important;
  --status-warning-text: var(--black-500) !important;
  --text-muted: var(--primary-345) !important;
  --text-normal: var(--primary-300) !important;
  --textbox-markdown-syntax: var(--primary-360) !important;
  --user-profile-header-overflow-background: hsl(var(--primary-700-hsl)/0.5) !important;
  --elevation-stroke: 0 0 0 1px hsl(var(--primary-600-hsl)/0.15) !important;
  --elevation-low: 0 1px 0 hsl(var(--primary-630-hsl)/0.2),0 1.5px 0 hsl(var(--primary-600-hsl)/0.05),0 2px 0 hsl(var(--primary-630-hsl)/0.05) !important;
  --elevation-medium: 0 4px 4px hsl(var(--black-500-hsl)/0.16) !important;
  --elevation-high: 0 8px 16px hsl(var(--black-500-hsl)/0.24) !important;
  --profile-gradient-primary-color: var(--background-floating);
  --profile-gradient-secondary-color: var(--background-floating);
  --profile-gradient-overlay-color: transparent;
  --profile-gradient-button-color: var(--button-secondary-background);
  --profile-avatar-border-color: var(--background-floating);
  --profile-message-input-border-color: var(--background-modifier-accent);
  --profile-body-background-color: var(--background-primary);
  --profile-body-background-hover: var(--background-modifier-hover);
  --profile-body-divider-color: var(--background-modifier-accent);
  --profile-role-pill-background-color: var(--background-floating);
  --profile-role-pill-border-color: var(--interactive-normal);
  --search-popout-option-fade: linear-gradient(90deg,hsl(var(--primary-830-hsl)/0),hsl(var(--primary-830-hsl)/1) 80%) !important;
  --search-popout-option-fade-hover: linear-gradient(90deg,hsl(var(--primary-800-hsl)/0),var(--primary-800) 50%) !important;
  --home-background: var(--primary-900) !important;
  --dark-elevation-low: 0 1px 5px 0 hsl(var(--black-500-hsl)/0.3);
  --dark-elevation-high: 0 2px 10px 0 hsl(var(--black-500-hsl)/0.2);
  --dark-elevation-border: 0 0 0 1px hsl(var(--primary-700-hsl)/0.6);
}

:is(.theme-dark, .theme-amoled) #app-mount .container__4bde3 {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) :is(.scroller__1f96e,
.auto_a48086,
.thin_b1c063,
.peopleColumn__51df3,
.contentRegionScroller__86c79,
.scrollerBase_dc3aa9)::-webkit-scrollbar-thumb {
  background-color: var(--background-secondary-alt);
}

:is(.theme-dark, .theme-amoled) #app-mount .bar_e58961 {
  background-color: var(--background-accent);
}
:is(.theme-dark, .theme-amoled) #app-mount .markDash_dc3ae9 {
  background: var(--background-accent);
}

:is(.theme-dark, .theme-amoled) #app-mount .container__11d72.themed_b152d4 {
  background: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .container__11d72 .children__32014::after {
  background: linear-gradient(90deg, var(--background-primary) 0, var(--background-primary)) !important;
}
:is(.theme-dark, .theme-amoled) #app-mount .container__11d72 [class*=searchBar] {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .container__11d72 [class*=searchBar] .searchAnswer_b452e7,
:is(.theme-dark, .theme-amoled) #app-mount .container__11d72 [class*=searchBar] .searchFilter__118cb {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .form__13a2c .optionPill_f86b98, .container_def45c .form__13a2c .optionPill_f86b98 {
  background-color: var(--primary-730);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .form__13a2c .channelAttachmentArea__740bf .upload_c98ecb, .container_def45c .form__13a2c .channelAttachmentArea__740bf .upload_c98ecb {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .wrapper_c727b6 {
  background-color: var(--background-tertiary);
}

:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .mainCard__8a660, :is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container__4abd7, :is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .increasedActivityMainCard__916ed, :is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container__1b27a, :is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container_a4e239 {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .loadingCard_a6aa0a, :is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .card__2c1e2 {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container_c24cbd:hover {
  background-color: var(--background-modifier-hover);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container_c24cbd:active {
  background-color: var(--background-modifier-active);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container_c24cbd.isOpen_d88bb6 {
  background-color: var(--background-modifier-selected);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container_c24cbd .textContentFooter__5a630 {
  background: transparent;
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container__99b06:active, :is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container__15ddf:active {
  background-color: var(--background-modifier-active);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container__99b06.isOpen__8593d, :is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container__99b06.isOpen__036bf, :is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container__15ddf.isOpen__8593d, :is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container_b181b6 .container__15ddf.isOpen__036bf {
  background-color: var(--background-modifier-selected);
}

:is(.theme-dark, .theme-amoled) #app-mount .messageListItem__6a4fb:hover {
  background-color: rgba(255, 255, 255, 0.015);
}
:is(.theme-dark, .theme-amoled) #app-mount .tile_ebc93b {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .tile_ebc93b .invalidPoop__03aa3 {
  background-color: var(--background-secondary-alt);
}

:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container__10dc7,
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container__7590f,
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .header__60bef,
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .scrollerContainer_bf5dbd,
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .emptyPage__3e15d {
  background-color: transparent;
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .prompt__1b100 {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .prompt__1b100 .selected__90dd8 {
  background-color: var(--background-modifier-active);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .profileCard_bd55ee {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .channelRow__96673 {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .channelRow__96673:not(.disabled__583e7):hover {
  background-color: var(--background-modifier-hover);
}

:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .wrapper_bd2abe.minimum_ebf000 {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .iconBackground__61963 {
  background-color: var(--background-secondary-alt);
}
:is(.theme-dark, .theme-amoled) #app-mount .chat__52833 .container__515b3:hover {
  background-color: var(--background-modifier-hover);
}

:is(.theme-dark, .theme-amoled) #app-mount .button__66e8c.buttonColor_a6eb73, :is(.theme-dark, .theme-amoled) #app-mount .button__66e8c .buttonColor_a6eb73 {
  background-color: var(--button-secondary-background);
}
:is(.theme-dark, .theme-amoled) #app-mount .button__66e8c.buttonColor_a6eb73:hover, :is(.theme-dark, .theme-amoled) #app-mount .button__66e8c .buttonColor_a6eb73:hover {
  background-color: var(--button-secondary-background-hover);
}
:is(.theme-dark, .theme-amoled) #app-mount .button__66e8c.buttonColor_a6eb73:active, :is(.theme-dark, .theme-amoled) #app-mount .button__66e8c .buttonColor_a6eb73:active {
  background-color: var(--button-secondary-background-active);
}

:is(.theme-dark, .theme-amoled) #app-mount .key__06fe6 {
  box-shadow: inset 0 -4px 0 var(--primary-760);
  background-color: var(--primary-660);
}

:is(.theme-dark, .theme-amoled) .folder__17546.hover__043de {
  background-color: var(--background-secondary-alt);
}

:is(.theme-dark, .theme-amoled) #app-mount [class=wrapper_d281dd] .childWrapper__01b9c,
:is(.theme-dark, .theme-amoled) #app-mount [class=circleIconButton_d8df29] {
  background-color: var(--background-secondary-alt);
}

:is(.theme-dark, .theme-amoled) .container_b2ce9c {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .member_aa4760,
:is(.theme-dark, .theme-amoled) #app-mount .members__9f47b {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .contentWrapper__85d37 {
  background: var(--modal-background);
}

:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .authBox__7196a {
  background-color: transparent;
}
:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .navRow_bb8efc {
  background-color: var(--modal-footer-background);
}

:is(.theme-dark, .theme-amoled) .theme-light .root_a28985 {
  color: var(--primary-300);
}

:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .message__04d9f {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .root_a28985.rootWithShadow__073a7 {
  box-shadow: var(--dark-elevation-border), var(--dark-elevation-high);
}
:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .footerSeparator__57d95 {
  box-shadow: inset 0 1px 0 var(--modal-footer-background);
}

:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .container__7712a {
  background-color: var(--input-background);
}
:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .footer__13977 {
  background-color: var(--modal-footer-background);
}

:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .keyboardShortcutsModal__74c71 {
  background-color: var(--modal-background);
}

:is(.theme-dark, .theme-amoled) #app-mount .modal_c01034 .verifiedRoleHasRole__86f1d {
  background-color: var(--background-secondary);
  border-color: var(--background-secondary);
}

:is(.theme-dark, .theme-amoled) #app-mount .root_a28985.uploadModal_eae2a0 {
  background-color: var(--modal-background);
}
:is(.theme-dark, .theme-amoled) #app-mount .root_a28985.uploadModal_eae2a0 .footer_ceda43 {
  box-shadow: inset 0 1px 0 hsl(var(--primary-900-hsl)/0.6);
  background-color: var(--modal-footer-background);
}

:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .cardPrimary_cb7a0e {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .default__3e2f5 {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .promptContent__63c03 .optionButtonWrapper__4072c.selected__90dd8 {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .promptContent__63c03 .overlay_ef4f80 {
  background: none !important;
}

:is(.theme-dark, .theme-amoled) #app-mount .root_a28985 .previewDark__016ac {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .nowPlayingColumn_f5023f .separator_c2ecc6 {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .nowPlayingColumn_f5023f .applicationStreamingPreviewWrapper__97a95 {
  background-color: var(--background-secondary-alt);
}

:is(.theme-dark, .theme-amoled) #app-mount .directoryContainer_d3edd9 {
  background-color: var(--background-primary);
}

body {
  background: var(--background-primary) !important;
}
body .colorLight-1o6rnK {
  background-color: var(--background-tertiary);
}
body .borderPrimary-1l1Cvj {
  border-color: var(--background-secondary);
}
body .divider-_0um2u {
  background-color: var(--background-modifier-accent);
}
body .hasBorder-17PTeu {
  border-bottom-color: var(--background-modifier-accent);
}
body .searchContainer-2duiLS:is(:hover) button {
  border-color: var(--background-secondary);
  background-color: var(--input-background);
}
body .h6-3NIpOq {
  background: var(--background-primary);
}
body .scrollbar-1NUwvY .thumb-3r19ww {
  background-color: var(--background-secondary-alt) !important;
}
body [class$=control] {
  border-color: var(--background-secondary);
}
body [class$=control]:hover {
  border-color: var(--background-secondary-alt);
}
body .css-1129voj-menu {
  border-color: var(--background-secondary);
  box-shadow: var(--background-secondary) 0px 1px 5px 0px;
  background-color: var(--background-floating);
}
body .css-lbnt4y-option {
  background-color: var(--background-modifier-selected);
}
body .css-1jrkz9i-option {
  background-color: var(--background-modifier-hover);
}
body .modalContent-31OOYM {
  box-shadow: var(--dark-elevation-border), var(--dark-elevation-high);
  background-color: var(--modal-background);
}
body .modalContent-31OOYM .modalFooter-3193QM {
  border: none;
  box-shadow: inset 0 1px 0 hsl(var(--primary-900-hsl)/0.6);
  background-color: var(--modal-footer-background);
}
body .input-2g-os5, body .inputWrapper-3a4ywb {
  border-color: var(--background-secondary);
  background-color: var(--input-background);
}
body .multiInputBlur-2Gn0-C {
  border-color: var(--background-secondary);
  background-color: var(--input-background);
}
body .grid-2a45cj .header-1JzP0t {
  background-color: var(--background-tertiary);
}
body .grid-2a45cj .rowWrapper-2RxnWO {
  background-color: var(--background-secondary);
}
body .grid-2a45cj .rowWrapper-2RxnWO:hover::before {
  background-color: var(--background-secondary-alt);
}
body .grid-2a45cj .rowWrapper-2RxnWO::after {
  border-color: var(--background-secondary-alt) !important;
}
body .disabled-29cfPA, body .disabled-29cfPA:hover {
  border-color: var(--background-secondary);
  background-color: var(--background-tertiary);
}
body .disabled-29cfPA + .pageButtonNext-2_bbdk,
body .disabled-29cfPA + .pageCount-17vMJm,
body .disabled-29cfPA:hover + .pageButtonNext-2_bbdk,
body .disabled-29cfPA:hover + .pageCount-17vMJm,
body .pageButtonNext-2_bbdk,
body .pageCount-17vMJm,
body .pageButtonNext-2_bbdk,
body .pageButtonPrev-3q9rh8 {
  border-color: var(--background-secondary) !important;
  background-color: var(--background-tertiary);
}
body .pageButtonNext-2_bbdk:hover,
body .pageButtonPrev-3q9rh8:hover {
  border-color: var(--background-secondary-alt) !important;
  background-color: var(--background-secondary);
}
body .wrapper-28jGDw {
  background-color: var(--background-tertiary);
}
body .wrapper-28jGDw .scrollbar-1NUwvY {
  background-color: var(--background-tertiary) !important;
}
body .wrapper-28jGDw .scrollbar-1NUwvY .pad-1eAWXq {
  background-color: var(--background-tertiary) !important;
}
body .contentWrapper-3RqEiS {
  background-color: var(--background-primary);
}
body .contentWrapper-3RqEiS .scrollbar-1NUwvY {
  background-color: var(--background-primary) !important;
}
body .contentWrapper-3RqEiS .pad-1eAWXq {
  background-color: var(--background-primary) !important;
}
body .contentWrapper-3RqEiS .cardOptionTile-30nXFk:hover {
  background-color: var(--background-modifier-hover);
}
body .contentWrapper-3RqEiS .cardOptionTileSelected-wkswQf {
  background-color: var(--background-modifier-active);
}
body .contentWrapper-3RqEiS .cardLink-H6gvNe {
  background-color: var(--background-secondary);
}
body .contentWrapper-3RqEiS .cardLink-H6gvNe:hover {
  background-color: var(--background-secondary-alt);
}
body .contentWrapper-3RqEiS .cardLink-H6gvNe .cardImagePlaceholder-EjWnzT {
  background-color: var(--background-primary);
}
body .contentWrapper-3RqEiS .avatarUploaderInner-yEhTv5 {
  background-color: var(--background-primary);
}
body .contentWrapper-3RqEiS .accordionContainer-vSTU_l {
  background-color: var(--background-tertiary);
}

:is(.theme-dark, .theme-amoled) #app-mount .content__4bf10 .pageWrapper_fef757 {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .content__4bf10 .searchBox_a63854 {
  background-color: var(--input-background);
}
:is(.theme-dark, .theme-amoled) #app-mount .content__4bf10 .searchBox_a63854 input {
  color: var(--primary-260);
}
:is(.theme-dark, .theme-amoled) #app-mount .content__4bf10 .searchBox_a63854 input::placeholder {
  color: var(--primary-400);
}
:is(.theme-dark, .theme-amoled) #app-mount .content__4bf10 .searchBox_a63854 .searchIcon_f30c40, :is(.theme-dark, .theme-amoled) #app-mount .content__4bf10 .searchBox_a63854 .closeIcon__3dfb5 {
  color: var(--interactive-normal);
}

:is(.theme-dark, .theme-amoled) #app-mount .container_df3aa0 .mainTableContainer__5ffe0 {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .container_df3aa0 .container__7712a {
  background-color: var(--background-secondary);
}

:is(.theme-dark, .theme-amoled) #app-mount .row__70f4c {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .row__70f4c:hover {
  background-color: var(--background-modifier-hover);
}
:is(.theme-dark, .theme-amoled) #app-mount .clickableAction_bef9b9:hover .action_c957d9 {
  background-color: var(--background-modifier-hover);
}
:is(.theme-dark, .theme-amoled) #app-mount .action_c957d9 {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .sidebarCardWrapper__2c840 {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .headerIcon__8b099 {
  background-color: var(--background-tertiary);
  border-color: var(--background-tertiary);
}

:is(.theme-dark, .theme-amoled) #app-mount .shop_b31ed2 {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .addGamePopout_e4ca8f {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .container_e84cda .header__02652, :is(.theme-dark, .theme-amoled) #app-mount .container_e84cda .autocompleteArrow__353a5 {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .container_e84cda .sectionTag_b0df68 {
  background-color: var(--background-secondary);
}

:is(.theme-dark, .theme-amoled) #app-mount .autocomplete_df266d {
  background-color: var(--background-tertiary);
}
:is(.theme-dark, .theme-amoled) #app-mount .autocomplete_df266d .categoryHeader_f97a5f {
  background-color: var(--background-tertiary);
}

:is(.theme-dark, .theme-amoled) #app-mount .contentWarningPopout__7d8c2 {
  background-color: var(--background-floating);
}
:is(.theme-dark, .theme-amoled) #app-mount .contentWarningPopout__7d8c2 .footer__36118 {
  background-color: var(--background-tertiary);
}

:is(.theme-dark, .theme-amoled) #app-mount .phoneFieldPopout__3e064 {
  background-color: var(--background-floating);
}

:is(.theme-dark, .theme-amoled) #app-mount .drawerSizingWrapper__30274 .emptyHintCard_f3e81a {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .drawerSizingWrapper__30274 .imageLoading__37d01 {
  border-radius: 35%;
  background-color: var(--background-secondary-alt);
  background-image: none;
}

:is(.theme-dark, .theme-amoled) #app-mount .container_d27846 {
  background-color: var(--background-secondary);
}

:is(.theme-dark, .theme-amoled) #app-mount .customColorPicker__3cb6a {
  border: none;
  box-shadow: var(--dark-elevation-border), var(--dark-elevation-high);
  background-color: var(--background-tertiary);
}

:is(.theme-dark, .theme-amoled) #app-mount .overflowRolesPopout__88ab9 {
  background-color: var(--background-floating);
}
:is(.theme-dark, .theme-amoled) #app-mount .overflowRolesPopout__88ab9 .overflowRolesPopoutArrow_f3db31 {
  background-color: var(--background-floating);
}

:is(.theme-dark, .theme-amoled) #app-mount .quickSelectPopout_c0cf80 {
  background-color: var(--background-floating);
}

:is(.theme-dark, .theme-amoled) #app-mount .streamPreview__1846c {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .streamPreview__1846c .previewContainer_bb1924 {
  background-color: var(--background-secondary-alt);
}

:is(.theme-dark, .theme-amoled) #app-mount .layer_ec16dd .focused_f9cf2c {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layer_ec16dd .calendarPicker__5c474 .react-datepicker {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layer_ec16dd .calendarPicker__5c474 .react-datepicker__header {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layer_ec16dd .calendarPicker__5c474 .react-datepicker__navigation,
:is(.theme-dark, .theme-amoled) #app-mount .layer_ec16dd .calendarPicker__5c474 .react-datepicker__navigation {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layer_ec16dd .calendarPicker__5c474 .react-datepicker__current-month {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layer_ec16dd .calendarPicker__5c474 .react-datepicker__day--outside-month,
:is(.theme-dark, .theme-amoled) #app-mount .layer_ec16dd .calendarPicker__5c474 .react-datepicker__day--disabled {
  background-color: var(--background-tertiary);
}

:is(.theme-dark, .theme-amoled) #app-mount .picker__6dca7 .soundButton__5ad7b {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .picker__6dca7 .keybindHint__70c7e {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .body__4e929 {
  background-color: var(--background-secondary);
}

:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .default__3e2f5 {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .avatarUploaderInnerSquareDisabled__3cfd1 {
  background-color: var(--background-secondary-alt);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .tierHeaderContent__27033 {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .prefixInput__38dcc {
  background-color: var(--input-background);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .backgroundContainer__06189 {
  background-color: var(--background-secondary-alt);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .containerFooter_c8da8a {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .iconWrapper__9caa9 {
  background: var(--button-secondary-background);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .iconWrapper__9caa9 .icon_ae3492:hover {
  background: var(--button-secondary-background-hover);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .iconWrapper__9caa9 .icon_ae3492:hover.disabled_d58a9f {
  background: var(--button-secondary-background-disabled);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .auditLog__6c805 {
  border-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .auditLog__6c805 .header_e08fd2 {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .auditLog__6c805 .headerExpanded__03c29 {
  background-color: var(--background-secondary-alt);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .auditLog__6c805 .divider__1505d {
  background-color: var(--background-modifier-accent);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .auditLog__6c805 .changeDetails_ecd760 {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .tierBody__615a1 {
  background-color: var(--background-secondary-alt);
}

:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .sidebarRegion__60457,
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .sidebarRegionScroller__1fa7e {
  background-color: var(--background-primary);
}

:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .cardPrimary_cb7a0e.outline_cb0aed {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .connectContainer__8050b {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .connectContainer__8050b .wrapper__03d5e:hover {
  background-color: var(--background-modifier-hover);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .integration_d2f026 {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .guildHeader__30707 {
  background-color: var(--background-secondary-alt);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .paymentPane__9cf01 {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .paymentPane__9cf01 .expandedInfo__47bad {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .paymentPane__9cf01 .paginator_e620d3 {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .paymentPane__9cf01 .paginator_e620d3 .payment__7d702 {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .paymentPane__9cf01 .paginator_e620d3 .payment__7d702.hoverablePayment__3ea24:hover {
  background-color: var(--background-modifier-hover);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .paymentPane__9cf01 .bottomDivider_a59d97 {
  border-bottom-color: var(--background-modifier-accent);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .codeRedemptionRedirect_bc7f36 {
  border-color: var(--background-tertiary);
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .preview_f42b5d {
  border-color: var(--background-secondary);
  background-color: var(--background-primary) !important;
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .notches__065e9.gray__4fb3f {
  color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .container__0c807 {
  background-color: var(--input-background);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .game__19f4b {
  box-shadow: none;
  border-bottom: 1px solid var(--background-modifier-accent);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .game__19f4b .gameNameInput_e25dd8:is(:hover, :focus) {
  border-color: var(--background-tertiary);
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .option_a0c054:not(.selected_ea51d6, :hover) {
  background-color: var(--background-accent);
}
:is(.theme-dark, .theme-amoled) #app-mount .layers__1c917 .disabled_ab18dc:not(.selected_ea51d6, :hover) {
  color: var(--background-accent);
}

:is(.theme-dark, .theme-amoled) #app-mount .sidebar_ded4b5 nav {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .sidebar_ded4b5 [class*=scroller] {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .sidebar_ded4b5 [class*=scroller].fade_ba0fa0 {
  background-color: transparent;
}

:is(.theme-dark, .theme-amoled) .sidebar_ded4b5 .searchBar_e4ea2a {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) .sidebar_ded4b5 .searchBar_e4ea2a .searchBarComponent__22760 {
  background-color: var(--background-secondary);
}

:is(.theme-dark, .theme-amoled) #app-mount .sidebar_ded4b5 .container__7c79d:not(.hasBanner_e78601) .header__104ca {
  background-color: var(--background-primary);
}
:is(.theme-dark, .theme-amoled) #app-mount .sidebar_ded4b5 .container__7c79d:not(.hasBanner_e78601) .header__104ca:hover {
  background-color: var(--background-secondary);
}
:is(.theme-dark, .theme-amoled) #app-mount .sidebar_ded4b5 .hasBanner_e78601 [class*=scroller-] {
  background-color: transparent;
}

:is(.theme-dark, .theme-amoled) .sidebar_ded4b5 .panels__58331 .container_ca50b9, :is(.theme-dark, .theme-amoled) .sidebar_ded4b5 .panels__58331 .panel_bd8c76, :is(.theme-dark, .theme-amoled) .sidebar_ded4b5 .panels__58331 .wrapper__0ed4a > div {
  background-color: var(--background-primary);
}

.autocomplete_df266d,
.uploadModal_eae2a0 {
    background-color: var(--background-secondary) !important;
}

.headerChildren__7cd0b > svg,
.addButtonIcon_b776b3 {
    color: var(--channels-default);
}

.wrapper-1VLyxH {
    mask: unset;
}

.content-2a4AW9 [style="height: 16px;"] {
    height: 10px !important;
}

.scrollableContainer__33e06 {
    border-radius: 20px;
    min-height: 70px !important;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: flex-start !important;
}

.container__4f639 {
    display: var(--boost-bar);
}

.header__104ca {
    height: 70px;
    display: flex;
    align-items: center;
}

.name_c08dbc {
    color: var(--channels-default);
    text-transform: uppercase;
    font-size: 9pt;
}

.peopleList__2379e::-webkit-scrollbar {
    display: none;
}

.peopleColumn__51df3 {
    background-color: var(--background-primary);
}

.inner__9fd0b {
    min-width: 96%;
    max-height: 50vh;
}

.codeBlockText__6172e,
code {
    font-family: var(--code-font);
}

```
-----------------------

info By Andrew Studies in Charge of Errors by Luisito8596 
