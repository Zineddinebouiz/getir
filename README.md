<html data-countly-useragent="Mozilla/5.0 (Linux; Android 7.1.1; SM-J510F Build/NMF26X; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/96.0.4664.45 Mobile Safari/537.36">
 <head> 
  <!--mui-inject-first--> 
  <style data-jss="" data-meta="makeStyles">
body {
  height: 100vh;
  font-size: 14px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", Helvetica, Arial, sans-serif;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
::placeholder, :-ms-input-placeholder {
  color: rgb(170, 170, 170);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", Helvetica, Arial, sans-serif;
  font-weight: 100;
}
.action-buttons {
  float: right;
  display: block;
  margin-top: 30px;
}
input:not([type="checkbox"]):not([type="radio"]), select, textarea {
  border: none;
  padding: 0px 15px;
  font-size: 14px;
  min-height: 45px;
  transition: background-color 100ms ease-in;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", Helvetica, Arial, sans-serif;
  -o-transition: background-color 100ms ease-in;
  border-radius: 8px !important;
  -moz-transition: background-color 100ms ease-in;
  -moz-border-radius: 8px !important;
  -webkit-transition: background-color 100ms ease-in;
  -webkit-border-radius: 8px !important;
}
input:not([type="checkbox"]):not([type="radio"]):focus, select:focus, textarea:focus {
  outline: none;
}
input:not([type="checkbox"]):not([type="radio"]).input-round, select.input-round, textarea.input-round {
  border-radius: 54px !important;
  -moz-border-radius: 54px !important;
  -webkit-border-radius: 54px !important;
}
input[type="checkbox"] {
  top: -1px;
  width: 17px;
  height: 17px;
  position: relative;
  vertical-align: middle;
}
input[type="checkbox"]+ label {
  position: relative;
  margin-left: 7px;
}
textarea {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "PingFang SC", Helvetica, Arial, sans-serif;
}
dl {
  dd: [object Object];
  dt: [object Object];
  width: 100%;
  margin-top: 20px;
  transition: all 100ms ease-in;
  -o-transition: all 100ms ease-in;
  margin-bottom: 20px;
  -moz-transition: all 100ms ease-in;
  -webkit-transition: all 100ms ease-in;
}
section {
  dl: [object Object];
  display: flex;
  flex-direction: row;
}
a {
  color: #000000;
  position: relative;
  font-weight: bold;
  text-decoration: none;
}
svg {
  color: #6e7187;
  font-size: 22px;
}
.icon {
  width: 36px;
  cursor: pointer;
  height: 36px;
  display: flex;
  transition: all 100ms ease-in;
  align-items: center;
  -o-transition: all 100ms ease-in;
  -moz-transition: all 100ms ease-in;
  justify-content: center;
  -webkit-transition: all 100ms ease-in;
}
.icon svg {
  font-size: 22px;
}
.text-link:hover {
  text-decoration: underline;
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.popup-content {
  max-width: 80vw;
  min-width: 600px;
  border-radius: 10px;
}
.popup-content > div > .content > .post-composer {
  border: none;
}
.popup-content .post-box {
  min-height: 180px;
}
.post-composer {
  width: 100%;
  display: flex;
  padding: 18px;
  position: relative;
  border-radius: 10px;
  background-color: #ffffff;
}
.post-composer.is-in-popup {
  padding-left: 0;
  padding-right: 0;
}
.post-composer .post-avatar {
  left: 18px;
  width: 50px;
  cursor: pointer;
  height: 50px;
  overflow: hidden;
  border-radius: 50%;
}
.post-composer .post-box {
  width: 100%;
  display: flex;
  flex-grow: 1;
  flex-direction: column;
}
@media (max-width:599.95px) {
  .post-composer.post-composer .post-box .action-bar, .post-composer.post-composer .post-box .excess-tips {
    margin-left: -62px;
    margin-right: -18px;
    padding-left: 18px;
    padding-right: 18px;
  }
  .post-composer.comment-composer .post-box .action-bar, .post-composer.comment-composer .post-box .excess-tips {
    margin-left: -78px;
    margin-right: -18px;
    padding-left: 18px;
    padding-right: 18px;
  }
}
.post-composer .post-box form {
  display: flex;
  flex-direction: column;
}
.post-composer .post-box textarea {
  width: 100%;
  border: 0;
  margin: 0 10px;
  resize: none;
  padding: 0;
  font-size: 19px;
  box-shadow: none !important;
  -moz-box-shadow: none !important;
  background-color: transparent;
  -webkit-box-shadow: none !important;
}
.post-composer .post-box .post-preview-box {
  padding: 0 18px;
  background: #f7f8f9;
  border-radius: 10px;
}
.post-composer .post-box .preview-content {
  margin-bottom: 12px;
}
.post-composer .post-box .action-bar {
  display: flex;
  padding: 18px 0 0 0;
  align-items: center;
  flex-direction: row;
}
.post-composer .post-box .metadata {
  width: 100%;
  border: 1px solid #e3e9ee;
  position: relative;
  margin-bottom: 20px;
}
.post-composer .post-box .replay-tip {
  color: #3261d8;
  margin: 0 0 10px 10px;
  display: inline-block;
  font-size: 15px;
  font-family: Helvetica Neue;
  font-weight: 400;
  line-height: 19px;
}
.post-composer .post-box .excess-tips {
  color: #bb271a;
  height: 36px;
  display: flex;
  padding: 0 16px;
  z-index: 1;
  position: relative;
  margin-top: 7px;
  line-height: 36px;
  margin-bottom: -16px;
  justify-content: space-between;
  background-color: #fbe8e8;
}
.post-composer .post-box .excess-tips .btn-delete-excess {
  cursor: pointer;
}
.post-composer .post-box .replay-tip img {
  margin-right: 10px;
  vertical-align: top;
}
.post-composer .post-box .metadata .img-container {
  position: relative;
}
.post-composer .post-box .metadata .content {
  padding: 5px 10px;
}
.post-composer .post-box .metadata .remove {
  top: 5px;
  left: 5px;
  position: absolute;
}
.post-composer .post-box .metadata .remove svg {
  position: absolute;
  font-size: 28px;
  --fa-primary-color: white;
  --fa-secondary-color: black;
  --fa-secondary-opacity: 1;
}
.post-composer .post-box .metadata .content .title {
  margin: 5px 0px;
  font-size: 15px;
}
.post-composer .post-box .metadata .content .description {
  color: #070808;
  margin: 5px 0px;
  word-break: break-word;
}
.post-composer .post-box .metadata .content .site-name {
  color: #070808;
  margin: 5px 0px;
}
.post-composer .post-box .metadata .img-container img {
  max-width: 100%;
}
.post-composer .post-box .action-bar .action-buttons {
  margin-top: 0;
  margin-left: 20px;
}
.post-composer .post-box .action-bar .text-length-limit {
  color: #657786;
  width: 80px;
  text-align: right;
  margin-left: auto;
}
.post-composer .post-box .action-bar .text-length-limit.is-exceed {
  color: #f34545;
}
.post-composer .post-box .action-bar .action-buttons button {
  height: 36px;
  min-width: 66px;
  border-radius: 100px;
}
.post-composer .post-box .action-bar .action-buttons.en button .MuiButton-label {
  line-height: 16px;
}
.post-composer .post-box .action-bar .action-buttons.zh button .MuiButton-label, .post-composer .post-box .action-bar .action-buttons.tw button .MuiButton-label {
  font-size: 17px;
  font-weight: 500;
  line-height: 17px;
  letter-spacing: 0.05em;
}
.post-composer .post-box .action-bar .action-buttons button span {
  color: white;
}
.post-composer .post-box .post-preview-box .post {
  margin-bottom: 18px;
}
.post-composer .post-box textarea:focus {
  outline: none;
}
@media (max-width:599.95px) {
  .post-composer .post-avatar {
    width: 36px;
    height: 36px;
  }
}
.post-composer .post-avatar .avatar {
  width: 100%;
  border: 1px solid #e8e9ea;
  height: 100%;
  box-sizing: border-box;
}
.post-composer.is-in-popup .post-avatar {
  left: 0;
  margin-right: 8px;
}
.post-composer.is-in-popup .post-box {
  width: calc(100% - 58px);
}
.post-composer.is-in-popup .post-box .post-preview-box {
  padding: 0;
  background: #ffffff;
}
.comment-composer .post-box .excess-tips {
  z-index: 1;
  position: relative;
  margin-top: 7px;
  margin-bottom: -16px;
}
.post-composer-divider {
  height: 9px;
  background: #f8f9fb;
  border-bottom: 1px solid #dfe1ea;
}
.popup-content .post-composer-divider {
  display: none;
}
.mobile-GBackTitle-with-post {
  height: 44px !important;
  padding-right: 18px !important;
  justify-content: space-between;
}
.mobile-GBackTitle-with-post > div:first-child {
  margin-left: 18px !important;
}
.mobile-GBackTitle-with-post .action-buttons {
  margin-top: 0;
}
.mobile-GBackTitle-with-post .action-buttons.zh, .mobile-GBackTitle-with-post .action-buttons.tw {
  min-width: 80px;
  text-align: right;
}
.mobile-GBackTitle-with-post.backTitle {
  padding-right: 18px !important;
  padding-bottom: 0 !important;
}
.mobile-GBackTitle-with-post .action-buttons button {
  padding: 5px 10px;
  min-width: 48px;
  border-radius: 55px;
}
.mobile-GBackTitle-with-post .action-buttons button .MuiButton-label {
  font-size: 13px;
  line-height: 1.38;
}
.mobile-GBackTitle-with-post .action-buttons button:disabled {
  background-color: #bdbdcc;
}
.empty-space {
  width: 100%;
  min-height: 1px;
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.popup-overlay {
  z-index: 1000 !important;
  background: rgba(27, 27, 27, 0.9);
  overflow-y: auto;
}
.popup-overlay .popup-repost-content {
  cursor: default;
}
.popup-overlay .popup-content {
  width: auto !important;
  border: 1px solid #e3e9ee !important;
  padding: 0px 0px !important;
}
.popup-overlay.popup-reply-overlay .popup-content, .popup-overlay.popup-repost-overlay .popup-content, .popup-overlay.popup-post-overlay .popup-content {
  width: 600px !important;
  cursor: default;
}
.popup-overlay .popup-content > div > .content {
  padding: 0px 18px;
}
@media (max-width:599.95px) {
  .popup-overlay .popup-content {
    height: 100%;
    margin: 0 !important;
    max-width: 100%;
    min-width: 100%;
    border-radius: 0 !important;
  }
  .popup-overlay .popup-content > div > .content {
    margin: 0 -1px;
    padding: 12px 18px 18px 18px;
  }
  .popup-overlay .popup-content > div > .content .action-bar {
    border-top: 1px solid #dfe1ea !important;
  }
}
.popup-overlay .popup-content .header {
  display: flex;
  padding: 18px;
  font-size: 20px;
  border-bottom: 1px solid #e8e9ea;
}
.popup-overlay .popup-content .post-composer .post-box .action-bar {
  border-top: 1px solid #dfe1ea;
  margin-top: 15px;
}
.popup-overlay .popup-content .action-groups {
  padding: 10px 10px;
  border-top: 1px solid #e3e9ee;
}
.popup-overlay .popup-content .header .title {
  color: #111;
  height: 24px;
  font-size: 18px;
  font-weight: 700;
  line-height: 24px;
}
.popup-overlay .popup-content .header .cancel {
  width: 24px;
  height: 24px;
  background: #e4e4e4;
  margin-right: 15px;
  border-radius: 50%;
}
.popup-overlay .popup-content .header .cancel:hover {
  background: #dfe1ea;
}
.popup-overlay .popup-content .header .cancel svg {
  color: #000;
}
</style> 
  <meta charset="utf-8"> 
  <meta name="viewport" content="width=device-width,initial-scale=1,shrink-to-fit=no,user-scalable=0"> 
  <meta name="theme-color" content="#000000"> 
  <link rel="manifest" href="/manifest.json"> 
  <link rel="shortcut icon" href="/favicon.ico"> 
  <link rel="apple-touch-icon" href="/logo.png"> 
  <title>GETTR - The Marketplace of Ideas</title> 
  <meta name="description" content="GETTR is a brand new social media platform founded on the principles of free speech, independent thought and rejecting political censorship and ???cancel culture.??? With best in class technology, our goal is to create a marketplace of ideas in order to share freedom and democracy around the world." data-react-helmet="true"> 
  <meta property="image" content="https://gettr.com/gettr.jpg" data-react-helmet="true"> 
  <meta property="og:title" content="GETTR - The Marketplace of Ideas" data-react-helmet="true"> 
  <meta property="og:description" content="GETTR is a brand new social media platform founded on the principles of free speech, independent thought and rejecting political censorship and ???cancel culture.??? With best in class technology, our goal is to create a marketplace of ideas in order to share freedom and democracy around the world." data-react-helmet="true"> 
  <meta property="og:image" content="https://gettr.com/gettr.jpg" data-react-helmet="true"> 
  <meta name="twitter:card" content="summary" data-react-helmet="true"> 
  <meta property="og:site_name" content="GETTR - The Marketplace of Ideas"> 
  <link href="/static/css/4.84312c3c.chunk.css" rel="stylesheet"> 
  <style data-emotion="css"></style> 
  <style type="text/css">/* add css styles here (optional) */

.styles_react-code-input-container__tpiKG {
  position: relative;
}

.styles_react-code-input__CRulA > input {
  border: solid 1px #a8adb7;
  border-right: none;
  font-family: 'Lato';
  font-size: 20px;
  color: #525461;
  text-align: center;
  box-sizing: border-box;
  border-radius: 0;
  -webkit-appearance: initial;
}

.styles_react-code-input__CRulA > input:last-child {
  border-right: solid 1px #a8adb7;
  border-top-right-radius: 6px;
  border-bottom-right-radius: 6px;
}

.styles_react-code-input__CRulA > input:first-child {
  border-top-left-radius: 6px;
  border-bottom-left-radius: 6px;
}

.styles_react-code-input__CRulA > input:focus {
  outline: none;
  border: 1px solid #006fff;
  caret-color: #006fff;
}

.styles_react-code-input__CRulA > input:focus + input {
  border-left: none;
}

.styles_loading__Z65VQ {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  text-align: center;
}

.styles_blur__19vMK {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #fff;
  opacity: 0.5;
  filter: blur(0.5px);
  transition: opacity 0.3s;
}

.styles_title__1cca0 {
  margin: 0;
  height: 20px;
  padding-bottom: 10px;
}

.styles_spin__6y_8G {
  display: inline-block;
  animation: styles_loadingCircle__293ky 1s infinite linear;
}

@keyframes styles_loadingCircle__293ky {
  100% {
    transform: rotate(360deg);
  }
}
</style> 
  <style data-jss="" data-meta="MuiTypography">
.MuiTypography-root {
  margin: 0;
}
.MuiTypography-body2 {
  font-size: 14px;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 400;
  line-height: 1.43;
}
.MuiTypography-body1 {
  font-size: 16px;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 400;
  line-height: 22.4px;
}
.MuiTypography-caption {
  font-size: 0.75rem;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 400;
  line-height: 1.66;
}
.MuiTypography-button {
  font-size: 0.875rem;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 500;
  line-height: 1.75;
  text-transform: uppercase;
}
.MuiTypography-h1 {
  font-size: 22px;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 900;
  line-height: 26.25px;
}
.MuiTypography-h2 {
  font-size: 18px;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 800;
  line-height: 21.48px;
}
.MuiTypography-h3 {
  font-size: 3rem;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 400;
  line-height: 1.167;
}
.MuiTypography-h4 {
  font-size: 2.125rem;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 400;
  line-height: 1.235;
}
.MuiTypography-h5 {
  font-size: 1.5rem;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 400;
  line-height: 1.334;
}
.MuiTypography-h6 {
  font-size: 1.25rem;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 500;
  line-height: 1.6;
}
.MuiTypography-subtitle1 {
  font-size: 1rem;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 400;
  line-height: 1.75;
}
.MuiTypography-subtitle2 {
  font-size: 0.875rem;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 500;
  line-height: 1.57;
}
.MuiTypography-overline {
  font-size: 0.75rem;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 400;
  line-height: 2.66;
  text-transform: uppercase;
}
.MuiTypography-srOnly {
  width: 1px;
  height: 1px;
  overflow: hidden;
  position: absolute;
}
.MuiTypography-alignLeft {
  text-align: left;
}
.MuiTypography-alignCenter {
  text-align: center;
}
.MuiTypography-alignRight {
  text-align: right;
}
.MuiTypography-alignJustify {
  text-align: justify;
}
.MuiTypography-noWrap {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}
.MuiTypography-gutterBottom {
  margin-bottom: 0.35em;
}
.MuiTypography-paragraph {
  margin-bottom: 16px;
}
.MuiTypography-colorInherit {
  color: inherit;
}
.MuiTypography-colorPrimary {
  color: #232255;
}
.MuiTypography-colorSecondary {
  color: #c00;
}
.MuiTypography-colorTextPrimary {
  color: #000;
}
.MuiTypography-colorTextSecondary {
  color: #5c7192;
}
.MuiTypography-colorError {
  color: #f44336;
}
.MuiTypography-displayInline {
  display: inline;
}
.MuiTypography-displayBlock {
  display: block;
}
</style> 
  <style data-jss="" data-meta="MuiButtonBase">
.MuiButtonBase-root {
  color: inherit;
  border: 0;
  cursor: pointer;
  margin: 0;
  display: inline-flex;
  outline: 0;
  padding: 0;
  position: relative;
  align-items: center;
  user-select: none;
  border-radius: 0;
  vertical-align: middle;
  -moz-appearance: none;
  justify-content: center;
  text-decoration: none;
  background-color: transparent;
  -webkit-appearance: none;
  -webkit-tap-highlight-color: transparent;
}
.MuiButtonBase-root::-moz-focus-inner {
  border-style: none;
}
.MuiButtonBase-root.Mui-disabled {
  cursor: default;
  pointer-events: none;
}
@media print {
  .MuiButtonBase-root {
    -webkit-print-color-adjust: exact;
  }
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss57 {
  width: 100%;
  bottom: 0;
  height: 84px;
  z-index: 10;
  position: fixed;
  border-top: 0.5px solid #dfe1ea;
  padding-bottom: 24px;
}
.jss57 .MuiBottomNavigationAction-label {
  font-size: 11px;
}
.jss57 .MuiBottomNavigationAction-root {
  padding: 12px 12px 8px;
  min-width: 69px;
}
.jss57 .MuiBottomNavigationAction-label:not(.Mui-selected) {
  color: #AFAFB9;
}
.jss57 .MuiBottomNavigationAction-label .Mui-selected {
  font-size: 11px;
}
.jss58 {
  color: #AFAFB9;
}
.jss59 {
  width: 24px;
  height: 24px;
  display: flex;
  position: relative;
  align-items: center;
  border-radius: 50%;
  justify-content: center;
}
.jss60 {
  width: 24px;
  border: none;
  height: 24px;
  font-size: 14px;
}
.jss61 {
  width: 18px;
  height: 18px;
}
.jss62 {
  top: 0;
  left: 0;
  width: 24px;
  border: 1px solid #c00;
  height: 24px;
  position: absolute;
  border-radius: 50%;
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss63 {
  width: auto;
  padding: 0;
  min-width: 266px;
  margin-bottom: 0;
}
@media (max-width:599.95px) {
  .jss63 {
    width: calc(100% - 40px);
    max-width: 360px;
  }
}
.jss63.Toastify__toast-container--top-right {
  top: 40px;
}
.jss63.Toastify__toast-container--top-center {
  top: 40px;
}
.jss63.Toastify__toast-container--top-left {
  top: 40px;
}
.jss63 .Toastify__toast {
  padding: 0;
  box-shadow: 0px 0px 11px 3px rgba(0, 0, 0, 0.04);
  min-height: 54px;
  border-radius: 10px;
  margin-bottom: 24px;
  background-color: #fff;
}
.jss63 .Toastify__toast-body {
  margin: 0;
}
@media (max-width:599.95px) {
  .jss63.Toastify__toast-container--top-center {
    left: 50%;
    transform: translateX(-50%);
  }
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss55 {
  font-weight: bold;
}
.jss56 {
  text-transform: uppercase;
}
</style> 
  <style data-jss="" data-meta="MuiButton">
.MuiButton-root {
  color: #000;
  padding: 6px 16px;
  font-size: 0.875rem;
  min-width: 64px;
  box-sizing: border-box;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms,box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms,border 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,PingFang SC,Helvetica,Arial,sans-serif;
  font-weight: 500;
  line-height: 1.75;
  border-radius: 4px;
  text-transform: uppercase;
}
.MuiButton-root:hover {
  text-decoration: none;
  background-color: rgba(0, 0, 0, 0.04);
}
.MuiButton-root.Mui-disabled {
  color: rgba(0, 0, 0, 0.26);
}
@media (hover: none) {
  .MuiButton-root:hover {
    background-color: transparent;
  }
}
.MuiButton-root:hover.Mui-disabled {
  background-color: transparent;
}
.MuiButton-label {
  width: 100%;
  display: inherit;
  align-items: inherit;
  justify-content: inherit;
}
.MuiButton-text {
  padding: 6px 8px;
}
.MuiButton-textPrimary {
  color: #232255;
}
.MuiButton-textPrimary:hover {
  background-color: rgba(35, 34, 85, 0.04);
}
@media (hover: none) {
  .MuiButton-textPrimary:hover {
    background-color: transparent;
  }
}
.MuiButton-textSecondary {
  color: #c00;
}
.MuiButton-textSecondary:hover {
  background-color: rgba(204, 0, 0, 0.04);
}
@media (hover: none) {
  .MuiButton-textSecondary:hover {
    background-color: transparent;
  }
}
.MuiButton-outlined {
  border: 1px solid rgba(0, 0, 0, 0.23);
  padding: 5px 15px;
}
.MuiButton-outlined.Mui-disabled {
  border: 1px solid rgba(0, 0, 0, 0.12);
}
.MuiButton-outlinedPrimary {
  color: #232255;
  border: 1px solid rgba(35, 34, 85, 0.5);
}
.MuiButton-outlinedPrimary:hover {
  border: 1px solid #232255;
  background-color: rgba(35, 34, 85, 0.04);
}
@media (hover: none) {
  .MuiButton-outlinedPrimary:hover {
    background-color: transparent;
  }
}
.MuiButton-outlinedSecondary {
  color: #c00;
  border: 1px solid rgba(204, 0, 0, 0.5);
}
.MuiButton-outlinedSecondary:hover {
  border: 1px solid #c00;
  background-color: rgba(204, 0, 0, 0.04);
}
.MuiButton-outlinedSecondary.Mui-disabled {
  border: 1px solid rgba(0, 0, 0, 0.26);
}
@media (hover: none) {
  .MuiButton-outlinedSecondary:hover {
    background-color: transparent;
  }
}
.MuiButton-contained {
  color: rgba(0, 0, 0, 0.87);
  box-shadow: 0px 3px 1px -2px rgba(0,0,0,0.2),0px 2px 2px 0px rgba(0,0,0,0.14),0px 1px 5px 0px rgba(0,0,0,0.12);
  background-color: #e0e0e0;
}
.MuiButton-contained:hover {
  box-shadow: 0px 2px 4px -1px rgba(0,0,0,0.2),0px 4px 5px 0px rgba(0,0,0,0.14),0px 1px 10px 0px rgba(0,0,0,0.12);
  background-color: #d5d5d5;
}
.MuiButton-contained.Mui-focusVisible {
  box-shadow: 0px 3px 5px -1px rgba(0,0,0,0.2),0px 6px 10px 0px rgba(0,0,0,0.14),0px 1px 18px 0px rgba(0,0,0,0.12);
}
.MuiButton-contained:active {
  box-shadow: 0px 5px 5px -3px rgba(0,0,0,0.2),0px 8px 10px 1px rgba(0,0,0,0.14),0px 3px 14px 2px rgba(0,0,0,0.12);
}
.MuiButton-contained.Mui-disabled {
  color: rgba(0, 0, 0, 0.26);
  box-shadow: none;
  background-color: rgba(0, 0, 0, 0.12);
}
@media (hover: none) {
  .MuiButton-contained:hover {
    box-shadow: 0px 3px 1px -2px rgba(0,0,0,0.2),0px 2px 2px 0px rgba(0,0,0,0.14),0px 1px 5px 0px rgba(0,0,0,0.12);
    background-color: #e0e0e0;
  }
}
.MuiButton-contained:hover.Mui-disabled {
  background-color: rgba(0, 0, 0, 0.12);
}
.MuiButton-containedPrimary {
  color: #fff;
  background-color: #232255;
}
.MuiButton-containedPrimary:hover {
  background-color: rgb(24, 23, 59);
}
@media (hover: none) {
  .MuiButton-containedPrimary:hover {
    background-color: #232255;
  }
}
.MuiButton-containedSecondary {
  color: #fff;
  background-color: #c00;
}
.MuiButton-containedSecondary:hover {
  background-color: rgb(142, 0, 0);
}
@media (hover: none) {
  .MuiButton-containedSecondary:hover {
    background-color: #c00;
  }
}
.MuiButton-disableElevation {
  box-shadow: none;
}
.MuiButton-disableElevation:hover {
  box-shadow: none;
}
.MuiButton-disableElevation.Mui-focusVisible {
  box-shadow: none;
}
.MuiButton-disableElevation:active {
  box-shadow: none;
}
.MuiButton-disableElevation.Mui-disabled {
  box-shadow: none;
}
.MuiButton-colorInherit {
  color: inherit;
  border-color: currentColor;
}
.MuiButton-textSizeSmall {
  padding: 4px 5px;
  font-size: 0.8125rem;
}
.MuiButton-textSizeLarge {
  padding: 8px 11px;
  font-size: 0.9375rem;
}
.MuiButton-outlinedSizeSmall {
  padding: 3px 9px;
  font-size: 0.8125rem;
}
.MuiButton-outlinedSizeLarge {
  padding: 7px 21px;
  font-size: 0.9375rem;
}
.MuiButton-containedSizeSmall {
  padding: 4px 10px;
  font-size: 0.8125rem;
}
.MuiButton-containedSizeLarge {
  padding: 8px 22px;
  font-size: 0.9375rem;
}
.MuiButton-fullWidth {
  width: 100%;
}
.MuiButton-startIcon {
  display: inherit;
  margin-left: -4px;
  margin-right: 8px;
}
.MuiButton-startIcon.MuiButton-iconSizeSmall {
  margin-left: -2px;
}
.MuiButton-endIcon {
  display: inherit;
  margin-left: 8px;
  margin-right: -4px;
}
.MuiButton-endIcon.MuiButton-iconSizeSmall {
  margin-right: -2px;
}
.MuiButton-iconSizeSmall > *:first-child {
  font-size: 18px;
}
.MuiButton-iconSizeMedium > *:first-child {
  font-size: 20px;
}
.MuiButton-iconSizeLarge > *:first-child {
  font-size: 22px;
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss39 {
  padding: 6px 16px;
  box-shadow: none;
  word-break: normal;
  border-radius: 16px;
}
.jss39.MuiButton-outlined {
  color: #232255;
  border: 1px solid #232255;
}
.jss39:hover {
  box-shadow: none;
}
.jss39 .MuiButton-label {
  font-size: 16px;
  word-break: break-all;
  line-height: 20px;
  text-transform: capitalize;
}
.jss39:disabled {
  color: #fff;
  background: #bdbdcc;
}
.jss39.loading {
  color: #fff;
  opacity: 0.6;
  background: #232255;
}
.jss39.bold {
  font-weight: bold;
}
.jss39.MuiButton-outlined.danger:not(:disabled) {
  color: #c00;
  border: 1px solid #c00;
  background: none;
}
.jss39.MuiButton-outlined.danger:not(:disabled):hover {
  color: #bd0a06;
  border: 1px solid #bd0a06;
  background: none;
}
.jss39.MuiButton-contained.danger:not(:disabled) {
  background: #c00;
}
.jss39.MuiButton-contained.danger:not(:disabled):hover {
  background: #bd0a06;
}
.jss39.MuiButton-contained:not(:disabled) {
  background: #232255;
}
.jss39.MuiButton-contained:not(:disabled):hover {
  background: #3d3c7c;
}
.jss39.MuiButton-outlined:not(:disabled):hover {
  color: rgb(24, 23, 59);
  border: 1px solid rgb(24, 23, 59);
  background: none;
}
</style> 
  <style data-jss="" data-meta="MuiGrid">
.MuiGrid-container {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  box-sizing: border-box;
}
.MuiGrid-item {
  margin: 0;
  box-sizing: border-box;
}
.MuiGrid-zeroMinWidth {
  min-width: 0;
}
.MuiGrid-direction-xs-column {
  flex-direction: column;
}
.MuiGrid-direction-xs-column-reverse {
  flex-direction: column-reverse;
}
.MuiGrid-direction-xs-row-reverse {
  flex-direction: row-reverse;
}
.MuiGrid-wrap-xs-nowrap {
  flex-wrap: nowrap;
}
.MuiGrid-wrap-xs-wrap-reverse {
  flex-wrap: wrap-reverse;
}
.MuiGrid-align-items-xs-center {
  align-items: center;
}
.MuiGrid-align-items-xs-flex-start {
  align-items: flex-start;
}
.MuiGrid-align-items-xs-flex-end {
  align-items: flex-end;
}
.MuiGrid-align-items-xs-baseline {
  align-items: baseline;
}
.MuiGrid-align-content-xs-center {
  align-content: center;
}
.MuiGrid-align-content-xs-flex-start {
  align-content: flex-start;
}
.MuiGrid-align-content-xs-flex-end {
  align-content: flex-end;
}
.MuiGrid-align-content-xs-space-between {
  align-content: space-between;
}
.MuiGrid-align-content-xs-space-around {
  align-content: space-around;
}
.MuiGrid-justify-content-xs-center {
  justify-content: center;
}
.MuiGrid-justify-content-xs-flex-end {
  justify-content: flex-end;
}
.MuiGrid-justify-content-xs-space-between {
  justify-content: space-between;
}
.MuiGrid-justify-content-xs-space-around {
  justify-content: space-around;
}
.MuiGrid-justify-content-xs-space-evenly {
  justify-content: space-evenly;
}
.MuiGrid-spacing-xs-1 {
  width: calc(100% + 8px);
  margin: -4px;
}
.MuiGrid-spacing-xs-1 > .MuiGrid-item {
  padding: 4px;
}
.MuiGrid-spacing-xs-2 {
  width: calc(100% + 16px);
  margin: -8px;
}
.MuiGrid-spacing-xs-2 > .MuiGrid-item {
  padding: 8px;
}
.MuiGrid-spacing-xs-3 {
  width: calc(100% + 24px);
  margin: -12px;
}
.MuiGrid-spacing-xs-3 > .MuiGrid-item {
  padding: 12px;
}
.MuiGrid-spacing-xs-4 {
  width: calc(100% + 32px);
  margin: -16px;
}
.MuiGrid-spacing-xs-4 > .MuiGrid-item {
  padding: 16px;
}
.MuiGrid-spacing-xs-5 {
  width: calc(100% + 40px);
  margin: -20px;
}
.MuiGrid-spacing-xs-5 > .MuiGrid-item {
  padding: 20px;
}
.MuiGrid-spacing-xs-6 {
  width: calc(100% + 48px);
  margin: -24px;
}
.MuiGrid-spacing-xs-6 > .MuiGrid-item {
  padding: 24px;
}
.MuiGrid-spacing-xs-7 {
  width: calc(100% + 56px);
  margin: -28px;
}
.MuiGrid-spacing-xs-7 > .MuiGrid-item {
  padding: 28px;
}
.MuiGrid-spacing-xs-8 {
  width: calc(100% + 64px);
  margin: -32px;
}
.MuiGrid-spacing-xs-8 > .MuiGrid-item {
  padding: 32px;
}
.MuiGrid-spacing-xs-9 {
  width: calc(100% + 72px);
  margin: -36px;
}
.MuiGrid-spacing-xs-9 > .MuiGrid-item {
  padding: 36px;
}
.MuiGrid-spacing-xs-10 {
  width: calc(100% + 80px);
  margin: -40px;
}
.MuiGrid-spacing-xs-10 > .MuiGrid-item {
  padding: 40px;
}
.MuiGrid-grid-xs-auto {
  flex-grow: 0;
  max-width: none;
  flex-basis: auto;
}
.MuiGrid-grid-xs-true {
  flex-grow: 1;
  max-width: 100%;
  flex-basis: 0;
}
.MuiGrid-grid-xs-1 {
  flex-grow: 0;
  max-width: 8.333333%;
  flex-basis: 8.333333%;
}
.MuiGrid-grid-xs-2 {
  flex-grow: 0;
  max-width: 16.666667%;
  flex-basis: 16.666667%;
}
.MuiGrid-grid-xs-3 {
  flex-grow: 0;
  max-width: 25%;
  flex-basis: 25%;
}
.MuiGrid-grid-xs-4 {
  flex-grow: 0;
  max-width: 33.333333%;
  flex-basis: 33.333333%;
}
.MuiGrid-grid-xs-5 {
  flex-grow: 0;
  max-width: 41.666667%;
  flex-basis: 41.666667%;
}
.MuiGrid-grid-xs-6 {
  flex-grow: 0;
  max-width: 50%;
  flex-basis: 50%;
}
.MuiGrid-grid-xs-7 {
  flex-grow: 0;
  max-width: 58.333333%;
  flex-basis: 58.333333%;
}
.MuiGrid-grid-xs-8 {
  flex-grow: 0;
  max-width: 66.666667%;
  flex-basis: 66.666667%;
}
.MuiGrid-grid-xs-9 {
  flex-grow: 0;
  max-width: 75%;
  flex-basis: 75%;
}
.MuiGrid-grid-xs-10 {
  flex-grow: 0;
  max-width: 83.333333%;
  flex-basis: 83.333333%;
}
.MuiGrid-grid-xs-11 {
  flex-grow: 0;
  max-width: 91.666667%;
  flex-basis: 91.666667%;
}
.MuiGrid-grid-xs-12 {
  flex-grow: 0;
  max-width: 100%;
  flex-basis: 100%;
}
@media (min-width:600px) {
  .MuiGrid-grid-sm-auto {
    flex-grow: 0;
    max-width: none;
    flex-basis: auto;
  }
  .MuiGrid-grid-sm-true {
    flex-grow: 1;
    max-width: 100%;
    flex-basis: 0;
  }
  .MuiGrid-grid-sm-1 {
    flex-grow: 0;
    max-width: 8.333333%;
    flex-basis: 8.333333%;
  }
  .MuiGrid-grid-sm-2 {
    flex-grow: 0;
    max-width: 16.666667%;
    flex-basis: 16.666667%;
  }
  .MuiGrid-grid-sm-3 {
    flex-grow: 0;
    max-width: 25%;
    flex-basis: 25%;
  }
  .MuiGrid-grid-sm-4 {
    flex-grow: 0;
    max-width: 33.333333%;
    flex-basis: 33.333333%;
  }
  .MuiGrid-grid-sm-5 {
    flex-grow: 0;
    max-width: 41.666667%;
    flex-basis: 41.666667%;
  }
  .MuiGrid-grid-sm-6 {
    flex-grow: 0;
    max-width: 50%;
    flex-basis: 50%;
  }
  .MuiGrid-grid-sm-7 {
    flex-grow: 0;
    max-width: 58.333333%;
    flex-basis: 58.333333%;
  }
  .MuiGrid-grid-sm-8 {
    flex-grow: 0;
    max-width: 66.666667%;
    flex-basis: 66.666667%;
  }
  .MuiGrid-grid-sm-9 {
    flex-grow: 0;
    max-width: 75%;
    flex-basis: 75%;
  }
  .MuiGrid-grid-sm-10 {
    flex-grow: 0;
    max-width: 83.333333%;
    flex-basis: 83.333333%;
  }
  .MuiGrid-grid-sm-11 {
    flex-grow: 0;
    max-width: 91.666667%;
    flex-basis: 91.666667%;
  }
  .MuiGrid-grid-sm-12 {
    flex-grow: 0;
    max-width: 100%;
    flex-basis: 100%;
  }
}
@media (min-width:1002px) {
  .MuiGrid-grid-md-auto {
    flex-grow: 0;
    max-width: none;
    flex-basis: auto;
  }
  .MuiGrid-grid-md-true {
    flex-grow: 1;
    max-width: 100%;
    flex-basis: 0;
  }
  .MuiGrid-grid-md-1 {
    flex-grow: 0;
    max-width: 8.333333%;
    flex-basis: 8.333333%;
  }
  .MuiGrid-grid-md-2 {
    flex-grow: 0;
    max-width: 16.666667%;
    flex-basis: 16.666667%;
  }
  .MuiGrid-grid-md-3 {
    flex-grow: 0;
    max-width: 25%;
    flex-basis: 25%;
  }
  .MuiGrid-grid-md-4 {
    flex-grow: 0;
    max-width: 33.333333%;
    flex-basis: 33.333333%;
  }
  .MuiGrid-grid-md-5 {
    flex-grow: 0;
    max-width: 41.666667%;
    flex-basis: 41.666667%;
  }
  .MuiGrid-grid-md-6 {
    flex-grow: 0;
    max-width: 50%;
    flex-basis: 50%;
  }
  .MuiGrid-grid-md-7 {
    flex-grow: 0;
    max-width: 58.333333%;
    flex-basis: 58.333333%;
  }
  .MuiGrid-grid-md-8 {
    flex-grow: 0;
    max-width: 66.666667%;
    flex-basis: 66.666667%;
  }
  .MuiGrid-grid-md-9 {
    flex-grow: 0;
    max-width: 75%;
    flex-basis: 75%;
  }
  .MuiGrid-grid-md-10 {
    flex-grow: 0;
    max-width: 83.333333%;
    flex-basis: 83.333333%;
  }
  .MuiGrid-grid-md-11 {
    flex-grow: 0;
    max-width: 91.666667%;
    flex-basis: 91.666667%;
  }
  .MuiGrid-grid-md-12 {
    flex-grow: 0;
    max-width: 100%;
    flex-basis: 100%;
  }
}
@media (min-width:1366px) {
  .MuiGrid-grid-lg-auto {
    flex-grow: 0;
    max-width: none;
    flex-basis: auto;
  }
  .MuiGrid-grid-lg-true {
    flex-grow: 1;
    max-width: 100%;
    flex-basis: 0;
  }
  .MuiGrid-grid-lg-1 {
    flex-grow: 0;
    max-width: 8.333333%;
    flex-basis: 8.333333%;
  }
  .MuiGrid-grid-lg-2 {
    flex-grow: 0;
    max-width: 16.666667%;
    flex-basis: 16.666667%;
  }
  .MuiGrid-grid-lg-3 {
    flex-grow: 0;
    max-width: 25%;
    flex-basis: 25%;
  }
  .MuiGrid-grid-lg-4 {
    flex-grow: 0;
    max-width: 33.333333%;
    flex-basis: 33.333333%;
  }
  .MuiGrid-grid-lg-5 {
    flex-grow: 0;
    max-width: 41.666667%;
    flex-basis: 41.666667%;
  }
  .MuiGrid-grid-lg-6 {
    flex-grow: 0;
    max-width: 50%;
    flex-basis: 50%;
  }
  .MuiGrid-grid-lg-7 {
    flex-grow: 0;
    max-width: 58.333333%;
    flex-basis: 58.333333%;
  }
  .MuiGrid-grid-lg-8 {
    flex-grow: 0;
    max-width: 66.666667%;
    flex-basis: 66.666667%;
  }
  .MuiGrid-grid-lg-9 {
    flex-grow: 0;
    max-width: 75%;
    flex-basis: 75%;
  }
  .MuiGrid-grid-lg-10 {
    flex-grow: 0;
    max-width: 83.333333%;
    flex-basis: 83.333333%;
  }
  .MuiGrid-grid-lg-11 {
    flex-grow: 0;
    max-width: 91.666667%;
    flex-basis: 91.666667%;
  }
  .MuiGrid-grid-lg-12 {
    flex-grow: 0;
    max-width: 100%;
    flex-basis: 100%;
  }
}
@media (min-width:1920px) {
  .MuiGrid-grid-xl-auto {
    flex-grow: 0;
    max-width: none;
    flex-basis: auto;
  }
  .MuiGrid-grid-xl-true {
    flex-grow: 1;
    max-width: 100%;
    flex-basis: 0;
  }
  .MuiGrid-grid-xl-1 {
    flex-grow: 0;
    max-width: 8.333333%;
    flex-basis: 8.333333%;
  }
  .MuiGrid-grid-xl-2 {
    flex-grow: 0;
    max-width: 16.666667%;
    flex-basis: 16.666667%;
  }
  .MuiGrid-grid-xl-3 {
    flex-grow: 0;
    max-width: 25%;
    flex-basis: 25%;
  }
  .MuiGrid-grid-xl-4 {
    flex-grow: 0;
    max-width: 33.333333%;
    flex-basis: 33.333333%;
  }
  .MuiGrid-grid-xl-5 {
    flex-grow: 0;
    max-width: 41.666667%;
    flex-basis: 41.666667%;
  }
  .MuiGrid-grid-xl-6 {
    flex-grow: 0;
    max-width: 50%;
    flex-basis: 50%;
  }
  .MuiGrid-grid-xl-7 {
    flex-grow: 0;
    max-width: 58.333333%;
    flex-basis: 58.333333%;
  }
  .MuiGrid-grid-xl-8 {
    flex-grow: 0;
    max-width: 66.666667%;
    flex-basis: 66.666667%;
  }
  .MuiGrid-grid-xl-9 {
    flex-grow: 0;
    max-width: 75%;
    flex-basis: 75%;
  }
  .MuiGrid-grid-xl-10 {
    flex-grow: 0;
    max-width: 83.333333%;
    flex-basis: 83.333333%;
  }
  .MuiGrid-grid-xl-11 {
    flex-grow: 0;
    max-width: 91.666667%;
    flex-basis: 91.666667%;
  }
  .MuiGrid-grid-xl-12 {
    flex-grow: 0;
    max-width: 100%;
    flex-basis: 100%;
  }
}
</style> 
  <style data-jss="" data-meta="MuiDivider">
.MuiDivider-root {
  border: none;
  height: 1px;
  margin: 0;
  flex-shrink: 0;
  background-color: rgba(0, 0, 0, 0.12);
}
.MuiDivider-absolute {
  left: 0;
  width: 100%;
  bottom: 0;
  position: absolute;
}
.MuiDivider-inset {
  margin-left: 72px;
}
.MuiDivider-light {
  background-color: rgba(0, 0, 0, 0.08);
}
.MuiDivider-middle {
  margin-left: 16px;
  margin-right: 16px;
}
.MuiDivider-vertical {
  width: 1px;
  height: 100%;
}
.MuiDivider-flexItem {
  height: auto;
  align-self: stretch;
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss22 {
  height: 100%;
  min-width: 50%;
}
.jss23 {
  max-width: 60%;
  padding-left: 40px;
}
.jss24 {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.jss25 {
  height: 100%;
  justify-content: center;
}
.jss26 {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.jss27 svg {
  width: 100%;
  height: 100px;
}
.jss28 {
  color: #000;
  font-size: 13px;
  max-width: 382px;
  margin-top: 8px;
  text-align: center;
  font-weight: 400;
  line-height: 16px;
}
@media (min-width:0px) and (max-width:599.95px) {
  .jss28 {
    max-width: 342px;
  }
}
.jss29 {
  width: 100%;
  height: 48px;
  max-width: 416px;
  margin-top: 20px;
  line-height: 48px;
  border-radius: 100px;
}
.jss29.MuiButtonBase-root:hover {
  background-color: #f2f9ff !important;
}
@media (min-width:0px) and (max-width:599.95px) {
  .jss29 {
    max-width: 250px;
  }
}
.jss30 {
  background-color: #c00 !important;
}
.jss30.MuiButtonBase-root:hover {
  background-color: #bd0a06 !important;
}
.jss31 {
  border: 1px solid #232255 !important;
  background-color: #fff !important;
}
.jss31.MuiButtonBase-root:hover {
  color: #3d3c7c !important;
  border: 1px solid #3d3c7c !important;
  background-color: #f2f9ff !important;
}
.jss32 {
  display: flex;
  margin-top: 18px;
  align-items: center;
  justify-content: flex-end;
}
.jss33 {
  padding-left: 30px;
  padding-right: 30px;
}
@media (max-width:599.95px) {
  .jss33 {
    padding-left: 20px;
    padding-right: 20px;
  }
}
.jss34 {
  color: #000;
  cursor: pointer;
  font-size: 14px;
  font-weight: 400;
  line-height: 16.71px;
  text-transform: capitalize;
  text-decoration: none;
}
.jss34:hover {
  text-decoration: underline;
}
.jss35 {
  height: 24px;
  margin: 0px 17px;
  display: inline-block;
  background-color: #dfe1ea;
}
.jss36 {
  z-index: 2;
}
.jss36 .MuiPaper-root {
  top: 25px;
  right: -25px;
  width: 245px;
  overflow: auto;
  position: absolute;
  box-shadow: 0 0 7px 2px rgba(0, 0, 0, 0.08);
  max-height: 80vh;
  border-radius: 8px;
}
.jss36 .MuiPaper-root .MuiList-root {
  padding: 15px 18px;
}
.jss37 {
  width: 100%;
  display: flex;
  margin-top: 20px;
  align-items: center;
  flex-direction: column;
}
.jss38 {
  display: inline-block;
  padding: 12px 20px;
  margin-top: 20px;
  border-radius: 100px;
  text-decoration: none;
}
.jss38 .arrow-icon {
  top: -1px;
  position: relative;
  transition: transform 0.3s ease;
  margin-left: 0.25rem;
  vertical-align: middle;
}
.jss38 .arrow-icon--circle {
  transition: stroke-dashoffset .3s ease;
  stroke-dasharray: 95;
  stroke-dashoffset: 95;
}
.jss38:hover {
  background: rgba(0, 0, 0, 0.08);
}
.jss38:hover .arrow-icon {
  transform: translate3d(5px, 0, 0);
}
.jss38:hover .arrow-icon--circle {
  stroke-dashoffset: 0;
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss40 {
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.jss40 p {
  color: #6e7187;
  font-size: 15px;
  letter-spacing: 0.01em;
}
.jss40:not(:last-child) {
  margin-bottom: 30px;
}
.jss40 p.active {
  color: #000;
  font-weight: 500;
}
.jss41 {
  margin-left: 8px;
}
.jss41 path {
  stroke: #016edc;
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss42 {
  display: flex;
  padding: 82px 0 44px 0;
  background: #fff;
  align-items: center;
  flex-direction: column;
}
.jss42.transparent {
  background: transparent;
}
.jss43 {
  font-size: 13px;
  font-weight: 500;
  line-height: 18px;
  margin-bottom: 20px;
}
.jss44 {
  display: flex;
  margin-bottom: 50px;
}
.jss44 a {
  display: block;
}
.jss44 a:first-child {
  margin-right: 11px;
}
.jss44 a svg {
  display: block;
}
.jss45 a, .jss45 span {
  color: #A3A3AE;
  font-size: 13px;
  font-weight: 500;
  line-height: 18px;
}
.jss45 a {
  margin-right: 24px;
}
@media (min-width:0px) and (max-width:599.95px) {
  .jss45 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
.jss45 a:hover {
  color: #6e7187;
}
@media (min-width:0px) and (max-width:599.95px) {
  .jss46 {
    display: block;
    margin-top: 16px;
    text-align: center;
  }
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss17 {
  height: 100vh;
  display: flex;
  flex-direction: column;
}
.jss18 {
  flex: 1;
  display: flex;
}
.jss19 {
  display: flex;
  max-width: 1129px;
  min-width: 50%;
  align-items: flex-end;
  padding-top: 41px;
  flex-direction: column;
  justify-content: center;
}
@media (min-width:1002px) and (max-width:1365.95px) {
  .jss19 {
    align-items: center;
  }
}
@media (max-width:1001.95px) {
  .jss19 {
    display: none;
  }
}
.jss20 {
  max-width: 60%;
  min-width: 50%;
}
.jss21 {
  padding: 0 0 24px 0;
  background: transparent !important;
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss47 {
  left: 0;
  right: 0;
  bottom: 0;
  height: 80px;
  z-index: 1400;
  position: fixed;
  background-color: #000;
}
@media (min-width:600px) {
  .jss47 {
    height: 58px;
  }
}
.jss48 {
  height: 100%;
  margin: 0 auto;
  display: flex;
  padding: 0px 16px;
  max-width: 1400px;
  justify-content: space-between;
}
@media (max-width:599.95px) {
  .jss48 {
    padding: 0px 32px;
  }
}
.jss49 {
  display: flex;
  padding: 0;
  align-items: center;
}
@media (max-width:599.95px) {
  .jss49 {
    align-items: flex-start;
    flex-direction: column;
    justify-content: center;
  }
}
.jss50 {
  display: flex;
  padding: 0;
  align-items: center;
  justify-content: flex-end;
}
.jss51 {
  color: #fff;
  font-size: 15px;
  font-weight: 400;
  line-height: 19.5px;
  letter-spacing: 0.015em;
}
.jss52 {
  max-height: 38px;
  border-radius: 100px;
}
.jss52 .MuiButton-label {
  font-size: 14px;
  font-weight: 800;
  line-height: 16px;
}
.jss52.zh span, .jss52.tw span {
  font-weight: 500;
  letter-spacing: 0.05em;
}
.jss53 .MuiButton-label {
  color: #fff;
}
.jss53.MuiButton-outlined {
  border: 1px solid rgba(255, 255, 255, 0.5);
}
.jss53.MuiButton-outlined:not(:disabled):hover {
  border: 1px solid rgba(255, 255, 255, 0.5);
}
.jss54 {
  color: #fff;
  cursor: pointer;
  font-size: 14px;
  font-weight: 600;
  line-height: 19px;
  margin-left: 14px;
}
.jss54:hover {
  text-decoration: underline;
}
@media (max-width:599.95px) {
  .jss54 {
    margin-left: 0;
  }
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss10 {
  top: 0;
  width: 100%;
  height: 52px;
  display: flex;
  padding: 0px 18px;
  z-index: 1100;
  position: sticky;
  align-items: center;
  border-bottom: 1px solid #e8e9ef;
  justify-content: space-between;
  background-color: #fff;
}
.jss11 {
  height: 36px;
  margin-left: -14px;
}
.jss12 {
  height: 28px;
  border-radius: 32px;
}
.jss13 {
  font-size: 0.75rem;
  font-weight: 500;
  text-transform: initial;
}
.jss14 {
  padding: 16px 12px;
  font-size: 14px;
  background-color: #fff;
}
.jss15 {
  font-weight: 500;
}
.jss16 {
  color: #A3A3AE;
  font-weight: 500;
}
</style> 
  <style data-jss="" data-meta="makeStyles">
.jss1 {
  width: 100%;
}
.jss2 {
  display: flex;
  padding: 0;
  position: relative;
  margin-left: auto;
  margin-right: auto;
}
.jss2 img.error {
  color: transparent;
  content: '';
  display: block;
  overflow: hidden;
  transform: scale(1);
}
.jss2 img.error::before {
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
  position: absolute;
  background: #EEEFF3 url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzAiIGhlaWdodD0iMzAiIHZpZXdCb3g9IjAgMCAzMCAzMCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4NCiAgICA8cGF0aCBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTUgNi4yNUgyNVYxMi41ODg2QzI1Ljg4MjcgMTIuNzE0OSAyNi43MjI5IDEyLjk3MjggMjcuNSAxMy4zNDJWNC45OTEyNUMyNy41IDQuMzA2MjUgMjYuOTQ1IDMuNzUgMjYuMjYgMy43NUgzLjc0QzMuNDExNzMgMy43NTI2MiAzLjA5NzY2IDMuODg0MjcgMi44NjU2NCA0LjExNjUyQzIuNjMzNjMgNC4zNDg3NyAyLjUwMjI5IDQuNjYyOTcgMi41IDQuOTkxMjVWMjUuMDA4OEMyLjUgMjUuMzM3NyAyLjYzMDYgMjUuNjUzMyAyLjg2MzExIDI1Ljg4NkMzLjA5NTYyIDI2LjExODcgMy40MTEwMiAyNi4yNDk3IDMuNzQgMjYuMjVIMTYuNTY4M0MxNS41Nzk3IDI0LjgzMjcgMTUgMjMuMTA5MSAxNSAyMS4yNUMxNSAxNy44Njg0IDE2LjkxODEgMTQuOTM1IDE5LjcyNTcgMTMuNDc4MkwxOC4zODI1IDEyLjEzMjVDMTguMTQ4MSAxMS44OTgyIDE3LjgzMDIgMTEuNzY2NSAxNy40OTg3IDExLjc2NjVDMTcuMTY3MyAxMS43NjY1IDE2Ljg0OTQgMTEuODk4MiAxNi42MTUgMTIuMTMyNUw1IDIzLjc1VjYuMjVaTTguMjMyMjMgMTMuMDE3OEM4LjcwMTA3IDEzLjQ4NjYgOS4zMzY5NiAxMy43NSAxMCAxMy43NUMxMC42NjMgMTMuNzUgMTEuMjk4OSAxMy40ODY2IDExLjc2NzggMTMuMDE3OEMxMi4yMzY2IDEyLjU0ODkgMTIuNSAxMS45MTMgMTIuNSAxMS4yNUMxMi41IDEwLjU4NyAxMi4yMzY2IDkuOTUxMDcgMTEuNzY3OCA5LjQ4MjIzQzExLjI5ODkgOS4wMTMzOSAxMC42NjMgOC43NSAxMCA4Ljc1QzkuMzM2OTYgOC43NSA4LjcwMTA3IDkuMDEzMzkgOC4yMzIyMyA5LjQ4MjIzQzcuNzYzMzkgOS45NTEwNyA3LjUgMTAuNTg3IDcuNSAxMS4yNUM3LjUgMTEuOTEzIDcuNzYzMzkgMTIuNTQ4OSA4LjIzMjIzIDEzLjAxNzhaIiBmaWxsPSIjQkRCRENDIi8+DQogICAgPHBhdGggZD0iTTIzLjc1IDI3LjVDMjAuMjk4MSAyNy41IDE3LjUgMjQuNzAxOSAxNy41IDIxLjI1QzE3LjUgMTcuNzk4MSAyMC4yOTgxIDE1IDIzLjc1IDE1QzI3LjIwMTkgMTUgMzAgMTcuNzk4MSAzMCAyMS4yNUMzMCAyNC43MDE5IDI3LjIwMTkgMjcuNSAyMy43NSAyNy41WiIgZmlsbD0iI0JEQkRDQyIvPg0KICAgIDxwYXRoIGQ9Ik0yMy43NSAyMy4xMjVDMjMuNDA0OCAyMy4xMjUgMjMuMTI1IDIzLjQwNDggMjMuMTI1IDIzLjc1QzIzLjEyNSAyNC4wOTUyIDIzLjQwNDggMjQuMzc1IDIzLjc1IDI0LjM3NUMyNC4wOTUyIDI0LjM3NSAyNC4zNzUgMjQuMDk1MiAyNC4zNzUgMjMuNzVDMjQuMzc1IDIzLjQwNDggMjQuMDk1MiAyMy4xMjUgMjMuNzUgMjMuMTI1Wk0yMy43NSAxOC4xMjVDMjMuNDA0OCAxOC4xMjUgMjMuMTI1IDE4LjQwNDggMjMuMTI1IDE4Ljc1VjIxLjI1QzIzLjEyNSAyMS41OTUyIDIzLjQwNDggMjEuODc1IDIzLjc1IDIxLjg3NUMyNC4wOTUyIDIxLjg3NSAyNC4zNzUgMjEuNTk1MiAyNC4zNzUgMjEuMjVWMTguNzVDMjQuMzc1IDE4LjQwNDggMjQuMDk1MiAxOC4xMjUgMjMuNzUgMTguMTI1WiIgZmlsbD0id2hpdGUiLz4NCjwvc3ZnPg0K) no-repeat center / 27.5px 23.75px;
}
.jss3 {
  padding-top: 61px;
}
@media (max-width:599.95px) {
  .jss3 {
    padding-top: 0;
  }
}
@media (max-width:599.95px) {
  .jss4 {
    padding-top: 61px;
  }
}
.jss5 {
  width: 100%;
  display: flex;
  position: relative;
  margin-left: auto;
  margin-right: auto;
  justify-content: flex-start;
}
.jss6 {
  position: relative;
  flex-grow: 2;
}
@media (min-width:1002px) and (max-width:1365.95px) {
  .jss6 {
    width: 860px;
  }
}
@media (min-width:600px) and (max-width:1001.95px) {
  .jss6 {
    width: 600px;
    max-width: 100%;
  }
}
@media (min-width:0px) and (max-width:599.95px) {
  .jss6 {
    width: 100%;
  }
}
.jss7 {
  max-width: none !important;
}
</style> 
  <style data-jss="" data-meta="makeStyles">
</style> 
 </head> 
 <body> 
  <noscript>
    Javascript is required to run this app. You need to enable it in your browser. 
  </noscript> 
  <!--[if IE]>
      <style>
        #ieMsg {
          display: block !important;
        }
      </style>
    <![endif]--> 
  <style>@media all and (-ms-high-contrast:none),(-ms-high-contrast:active){#ieMsg{display:block!important}}</style> 
  <h1 id="ieMsg" style="display:none">Internet Explorer is not supported. Our site works best with <a href="https://www.google.com/chrome/">Chrome</a>.</h1> 
  <div id="root"> 
   <div class="jss1 jss8"> 
    <div class="jss2 jss9 jss7"> 
     <div class="jss5"> 
      <div class="jss6 app-content"> 
       <div class="jss17"> 
        <div class="jss18"> 
         <div class="jss19"> 
          <img src="/static/media/mobile_preview.3fcb3302.png" alt="MobilePreview" class="jss20"> 
         </div> 
         <div class="MuiGrid-root jss22 MuiGrid-container"> 
          <div class="MuiGrid-root jss24 MuiGrid-item MuiGrid-grid-xs-12"> 
           <div class="MuiGrid-root jss33 MuiGrid-container"> 
            <div class="MuiGrid-root MuiGrid-item MuiGrid-grid-xs-6"></div> 
            <div class="MuiGrid-root jss32 MuiGrid-item MuiGrid-grid-xs-6"> 
             <a class="jss34 text-link" href="/helpcenter/mobile">Trouver de l'aide</a> 
             <hr class="MuiDivider-root jss35 MuiDivider-vertical"> 
             <span class="jss34">Langues</span> 
            </div> 
           </div> 
           <div class="MuiGrid-root jss25 MuiGrid-container MuiGrid-direction-xs-column MuiGrid-align-items-xs-center"> 
            <div class="MuiGrid-root MuiGrid-item"> 
             <div class="jss27"> 
              <svg width="101" height="47" viewbox="0 0 84 39" fill="none" xmlns="http://www.w3.org/2000/svg"> 
               <path d="M51.4568 3.33264C51.2262 4.63216 50.6184 5.70112 49.6542 6.64432C50.0525 6.72816 50.5136 6.53952 50.807 6.26704C50.7022 6.79104 50.5345 7.29408 50.2621 7.77616C49.8009 8.61456 49.0673 9.30624 48.2709 9.78832C47.1181 10.459 45.8186 10.6477 44.4352 10.8782C43.513 11.025 42.5488 11.1717 41.9619 11.8005C41.6685 12.1149 41.4589 12.555 41.3331 12.9952C40.2013 11.3813 39.3838 9.49488 39.5934 7.90192C39.8869 5.6592 42.1925 3.96144 44.7706 2.9344C47.4325 1.84448 50.4088 1.4672 52.3371 0C52.1066 0.7336 51.8131 1.4672 51.4149 2.11696C51.0166 2.78768 50.5136 3.39552 49.9686 3.94048C50.5765 3.89856 51.0166 3.68896 51.4568 3.33264Z" fill="#FF0000"></path> 
               <path d="M24.083 19.0108H31.8382V15.4895H19.409V32.68H31.8382V28.96H24.083V25.697H30.895V22.1757H24.083V19.0108Z" fill="#010101"></path> 
               <path d="M50.807 15.4895V19.0108H55.2086V32.68H59.9037V19.0108H64.2843V15.4895H50.807Z" fill="#010101"></path> 
               <path d="M48.9206 15.4895H33.7456L35.7787 19.0108H38.9856V32.68H43.6597V19.0108H46.8666L48.9206 15.4895Z" fill="#010101"></path> 
               <path d="M79.669 26.2419C81.9536 25.0053 83.1064 22.3853 82.4986 19.8491C81.8907 17.313 79.648 15.5314 77.049 15.4685C73.8421 15.4685 70.6352 15.4685 67.4283 15.4685C67.4283 21.2115 67.4283 26.9546 67.4283 32.6767C69.0003 32.6767 70.5514 32.6767 72.1024 32.6767C72.1024 30.7693 72.1024 28.841 72.1024 26.9336C72.9408 26.9336 73.7582 26.9336 74.5966 26.9336C75.7914 28.841 76.9861 30.7693 78.1808 32.6767C80.0043 32.6767 81.8488 32.6767 83.6723 32.6767C82.3518 30.5597 81.0104 28.4008 79.669 26.2419ZM75.8123 23.4333C74.5757 23.4333 73.339 23.4333 72.1234 23.4333C72.1234 21.9661 72.1234 20.4779 72.1234 19.0107C73.4019 19.0107 74.6595 19.0107 75.9381 19.0107C77.1118 19.0946 78.0131 20.1007 77.9922 21.2744C77.9502 22.4691 76.9861 23.4123 75.8123 23.4333Z" fill="#010101"></path> 
               <path d="M9.03376 18.7592C7.31504 19.0736 5.8688 20.2264 5.19808 21.8613C4.52736 23.4752 4.716 25.3197 5.70112 26.7659C6.87488 28.4846 9.05472 29.2182 11.025 28.5475C11.025 26.8498 11.025 25.152 11.025 23.4542C12.597 23.4542 14.148 23.4542 15.699 23.4542C15.699 26.1162 15.699 28.799 15.699 31.461C13.1 32.5928 10.2494 32.9701 7.46176 32.5509C5.38672 32.2365 3.50032 31.1675 2.11696 29.5746C0.7336 27.9816 0 25.9485 0 23.8525C0 21.7565 0.75456 19.7234 2.11696 18.1304C3.47936 16.5374 5.38672 15.4894 7.46176 15.1541C10.2494 14.7349 13.1 15.0912 15.6781 16.223C15.0493 17.313 14.3995 18.4238 13.7707 19.5138C12.3245 18.7382 10.6686 18.4658 9.03376 18.7592Z" fill="#010101"></path> 
              </svg> 
             </div> 
             <div class="jss28">
               Une toute nouvelle plate-forme de m??dia sociaux bas??e sur les principes de la libert?? d'expression, de la pens??e ind??pendante, du rejet de la censure politique et de la ?? cancel culture ??. 
             </div> 
            </div> 
            <div class="MuiGrid-root jss37 MuiGrid-item"> 
             <button class="MuiButtonBase-root MuiButton-root MuiButton-contained jss39 jss30 jss29 MuiButton-containedPrimary MuiButton-fullWidth" tabindex="0" type="button"><span class="MuiButton-label">Cr??er un compte</span></button> 
             <button class="MuiButtonBase-root MuiButton-root MuiButton-outlined jss39 jss31 jss29 MuiButton-outlinedPrimary MuiButton-fullWidth" tabindex="0" type="button"><span class="MuiButton-label">S'identifier</span></button> 
             <button class="MuiButtonBase-root MuiButton-root MuiButton-text jss39 jss38 MuiButton-textPrimary" tabindex="0" type="button"><span class="MuiButton-label">Explorer maintenant<span> 
                <svg class="arrow-icon" xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewbox="0 0 32 32"> 
                 <g fill="none" stroke="#232255" stroke-width="1.5" stroke-linejoin="round" stroke-miterlimit="10"> 
                  <circle class="arrow-icon--circle" cx="16" cy="16" r="15.12"></circle> 
                  <path class="arrow-icon--arrow" d="M16.14 9.93L22.21 16l-6.07 6.07M8.23 16h13.98"></path> 
                 </g> 
                </svg></span></span></button> 
            </div> 
           </div> 
          </div> 
         </div> 
        </div> 
        <div> 
         <div class="jss42 jss21"> 
          <p class="jss43">T??l??chargez cette Application</p> 
          <div class="jss44"> 
           <a href="https://zineddineboui.github.io/qurankarim/" target="_blank" rel="noopener noreferrer" download=""> 
            <svg width="151" height="51" fill="none" xmlns="http://www.w3.org/2000/svg"> 
             <path d="M138.555.664H12.452c-.46 0-.914 0-1.372.003-.384.002-.765.01-1.152.016a16.61 16.61 0 0 0-2.512.22c-.83.14-1.633.405-2.383.784a8.07 8.07 0 0 0-3.506 3.5 8.235 8.235 0 0 0-.783 2.379C.604 8.393.529 9.23.519 10.07c-.012.383-.013.767-.019 1.15v28.893c.006.389.007.764.019 1.153.01.838.085 1.675.225 2.502a8.22 8.22 0 0 0 .783 2.38 7.76 7.76 0 0 0 1.477 2.018 7.865 7.865 0 0 0 2.029 1.474c.75.38 1.553.646 2.383.788.83.136 1.67.21 2.512.221.387.009.768.014 1.152.014.458.002.912.002 1.372.002h126.103c.45 0 .908 0 1.359-.002.382 0 .773-.005 1.155-.014.84-.01 1.678-.084 2.507-.22a8.54 8.54 0 0 0 2.392-.79 7.85 7.85 0 0 0 2.027-1.473 8.007 8.007 0 0 0 1.482-2.017 8.26 8.26 0 0 0 .776-2.38c.139-.828.217-1.665.232-2.503.005-.389.005-.764.005-1.153.01-.454.01-.905.01-1.367v-26.16c0-.458 0-.913-.01-1.365 0-.384 0-.768-.005-1.152a16.93 16.93 0 0 0-.232-2.502 8.284 8.284 0 0 0-.776-2.38 8.095 8.095 0 0 0-3.509-3.499 8.492 8.492 0 0 0-2.392-.784 16.388 16.388 0 0 0-2.507-.22c-.382-.007-.773-.014-1.155-.016-.451-.003-.909-.003-1.359-.003z" fill="#A6A6A6"></path> 
             <path d="M11.004 49.662c-.383 0-.756-.005-1.136-.014-.786-.01-1.57-.079-2.346-.205a7.385 7.385 0 0 1-2.079-.687A6.784 6.784 0 0 1 3.69 47.48a6.677 6.677 0 0 1-1.281-1.752 7.18 7.18 0 0 1-.682-2.08 15.575 15.575 0 0 1-.209-2.352C1.51 41.03 1.5 40.15 1.5 40.15V11.162s.011-.867.018-1.122c.01-.787.08-1.573.208-2.35.12-.725.35-1.429.682-2.085a6.743 6.743 0 0 1 1.274-1.754 6.985 6.985 0 0 1 1.76-1.283 7.31 7.31 0 0 1 2.076-.683 15.8 15.8 0 0 1 2.354-.206l1.132-.015H139.99l1.146.016c.781.01 1.561.077 2.332.204.73.124 1.436.356 2.097.687a7.022 7.022 0 0 1 3.032 3.037 7.22 7.22 0 0 1 .671 2.07c.131.782.203 1.574.218 2.367.004.356.004.738.004 1.117.01.47.01.919.01 1.37v26.262c0 .456 0 .901-.01 1.35 0 .408 0 .782-.005 1.166-.014.78-.086 1.557-.214 2.326a7.2 7.2 0 0 1-.678 2.096 6.875 6.875 0 0 1-1.275 1.739 6.79 6.79 0 0 1-1.756 1.283 7.358 7.358 0 0 1-2.094.69c-.775.126-1.56.195-2.346.204-.367.009-.752.014-1.126.014l-1.361.002-127.631-.002z" fill="#000"></path> 
             <path d="M31.549 26.21c.013-1.05.29-2.08.807-2.993a6.218 6.218 0 0 1 2.146-2.231A6.332 6.332 0 0 0 29.5 18.27c-2.104-.222-4.145 1.264-5.218 1.264-1.093 0-2.745-1.242-4.523-1.206a6.644 6.644 0 0 0-3.254.975 6.677 6.677 0 0 0-2.353 2.458c-2.424 4.214-.616 10.406 1.707 13.812 1.161 1.668 2.52 3.531 4.296 3.465 1.739-.072 2.388-1.113 4.487-1.113 2.08 0 2.688 1.113 4.501 1.071 1.866-.03 3.041-1.675 4.162-3.359a13.818 13.818 0 0 0 1.904-3.891 6 6 0 0 1-2.66-2.215 6.034 6.034 0 0 1-1-3.321zM28.124 16.031a6.147 6.147 0 0 0 1.397-4.392 6.206 6.206 0 0 0-4.02 2.088 5.84 5.84 0 0 0-1.434 4.23 5.121 5.121 0 0 0 4.057-1.926zM53.528 34.817h-5.934l-1.425 4.224h-2.513l5.62-15.627h2.611l5.62 15.627h-2.556l-1.423-4.224zm-5.32-1.949h4.704l-2.319-6.855h-.064l-2.32 6.855zM69.644 33.346c0 3.54-1.888 5.815-4.737 5.815a3.835 3.835 0 0 1-2.07-.482 3.856 3.856 0 0 1-1.5-1.511h-.054v5.643h-2.33V27.649h2.255v1.895h.043a4.014 4.014 0 0 1 3.614-2.014c2.88 0 4.779 2.285 4.779 5.816zm-2.395 0c0-2.307-1.187-3.823-2.999-3.823-1.78 0-2.977 1.548-2.977 3.823 0 2.295 1.197 3.833 2.977 3.833 1.812 0 3-1.506 3-3.833zM82.136 33.346c0 3.54-1.888 5.815-4.736 5.815a3.834 3.834 0 0 1-2.071-.482 3.855 3.855 0 0 1-1.5-1.511h-.054v5.643h-2.33V27.649H73.7v1.895h.043a4.014 4.014 0 0 1 3.614-2.014c2.88 0 4.779 2.285 4.779 5.816zm-2.395 0c0-2.307-1.187-3.823-2.999-3.823-1.78 0-2.977 1.548-2.977 3.823 0 2.295 1.197 3.833 2.977 3.833 1.812 0 3-1.506 3-3.833zM90.392 34.688c.173 1.55 1.673 2.567 3.722 2.567 1.963 0 3.376-1.018 3.376-2.415 0-1.213-.852-1.94-2.87-2.437l-2.017-.488c-2.858-.693-4.185-2.035-4.185-4.213 0-2.696 2.34-4.548 5.664-4.548 3.29 0 5.544 1.852 5.62 4.548H97.35c-.14-1.559-1.424-2.5-3.301-2.5-1.877 0-3.16.952-3.16 2.338 0 1.105.82 1.755 2.826 2.253l1.715.422c3.194.759 4.52 2.047 4.52 4.332 0 2.924-2.32 4.755-6.009 4.755-3.452 0-5.783-1.788-5.933-4.615h2.385zM104.975 24.953v2.696h2.158v1.852h-2.158v6.281c0 .976.432 1.43 1.381 1.43.256-.004.512-.022.766-.054V39a6.37 6.37 0 0 1-1.294.108c-2.297 0-3.194-.866-3.194-3.075v-6.53h-1.65v-1.853h1.65v-2.696h2.341zM108.383 33.345c0-3.585 2.103-5.837 5.382-5.837 3.291 0 5.384 2.252 5.384 5.837 0 3.595-2.082 5.837-5.384 5.837-3.3 0-5.382-2.242-5.382-5.837zm8.392 0c0-2.459-1.122-3.91-3.01-3.91-1.887 0-3.009 1.462-3.009 3.91 0 2.469 1.122 3.91 3.009 3.91 1.888 0 3.01-1.441 3.01-3.91zM121.07 27.648h2.222v1.94h.054c.15-.606.504-1.141 1.001-1.516a2.7 2.7 0 0 1 1.729-.543c.268 0 .536.029.798.088v2.187a3.245 3.245 0 0 0-1.047-.141 2.34 2.34 0 0 0-1.814.75 2.357 2.357 0 0 0-.613 1.87v6.759h-2.33V27.648zM137.616 35.695c-.313 2.068-2.319 3.487-4.886 3.487-3.302 0-5.351-2.22-5.351-5.783 0-3.573 2.06-5.891 5.253-5.891 3.14 0 5.114 2.165 5.114 5.62v.8h-8.016v.142a2.98 2.98 0 0 0 .801 2.305 2.954 2.954 0 0 0 2.252.922 2.562 2.562 0 0 0 2.621-1.602h2.212zm-7.875-3.4h5.674a2.752 2.752 0 0 0-.762-2.057 2.734 2.734 0 0 0-2.021-.835 2.863 2.863 0 0 0-2.046.841 2.895 2.895 0 0 0-.845 2.05zM47.916 11.651a3.297 3.297 0 0 1 2.64 1.03 3.324 3.324 0 0 1 .88 2.701c0 2.399-1.292 3.778-3.52 3.778h-2.701V11.65h2.701zm-1.54 6.447h1.41a2.343 2.343 0 0 0 1.874-.761 2.364 2.364 0 0 0 .593-1.94 2.375 2.375 0 0 0-.602-1.926 2.358 2.358 0 0 0-1.864-.759h-1.41v5.386zM52.747 16.325a2.694 2.694 0 0 1 .683-2.061 2.676 2.676 0 0 1 1.979-.88 2.665 2.665 0 0 1 1.979.88 2.685 2.685 0 0 1 .683 2.06 2.695 2.695 0 0 1-.681 2.065 2.675 2.675 0 0 1-1.981.88 2.665 2.665 0 0 1-1.98-.88 2.687 2.687 0 0 1-.682-2.064zm4.178 0c0-1.228-.55-1.947-1.514-1.947-.969 0-1.513.719-1.513 1.947 0 1.238.544 1.95 1.513 1.95.964 0 1.514-.717 1.514-1.95zM65.147 19.16h-1.155l-1.167-4.173h-.088l-1.162 4.174h-1.144l-1.556-5.667h1.13l1.011 4.324h.083l1.16-4.324h1.07l1.16 4.324h.088l1.006-4.324h1.114l-1.55 5.667zM68.008 13.494h1.072v.9h.083a1.695 1.695 0 0 1 1.685-1.01 1.83 1.83 0 0 1 1.481.583 1.844 1.844 0 0 1 .473 1.525v3.668h-1.114v-3.387c0-.91-.395-1.364-1.219-1.364a1.29 1.29 0 0 0-1.287.884c-.06.178-.08.366-.06.552v3.315h-1.114v-5.666zM74.574 11.281h1.114v7.879h-1.114V11.28zM77.24 16.325a2.695 2.695 0 0 1 .682-2.061 2.674 2.674 0 0 1 1.98-.88 2.666 2.666 0 0 1 1.978.88 2.687 2.687 0 0 1 .684 2.06 2.696 2.696 0 0 1-.682 2.065 2.676 2.676 0 0 1-1.98.881 2.666 2.666 0 0 1-1.981-.88 2.687 2.687 0 0 1-.682-2.065zm4.177 0c0-1.228-.55-1.947-1.514-1.947-.969 0-1.513.719-1.513 1.947 0 1.238.545 1.95 1.513 1.95.964 0 1.514-.717 1.514-1.95zM83.734 17.558c0-1.02.757-1.608 2.1-1.691l1.529-.089v-.49c0-.598-.394-.936-1.156-.936-.622 0-1.053.23-1.176.63h-1.079c.114-.973 1.026-1.597 2.306-1.597 1.416 0 2.214.707 2.214 1.904v3.872h-1.073v-.797h-.088a1.902 1.902 0 0 1-1.695.89 1.698 1.698 0 0 1-1.316-.429 1.713 1.713 0 0 1-.566-1.267zm3.629-.484V16.6l-1.379.089c-.777.052-1.13.317-1.13.817 0 .51.441.807 1.047.807a1.324 1.324 0 0 0 1.321-.726c.08-.16.129-.334.14-.513zM89.938 16.324c0-1.79.916-2.925 2.343-2.925a1.855 1.855 0 0 1 1.73.994h.084v-3.112h1.114v7.879H94.14v-.896h-.088a1.963 1.963 0 0 1-1.772.99c-1.436 0-2.344-1.135-2.344-2.93zm1.15 0c0 1.202.565 1.925 1.508 1.925.94 0 1.52-.733 1.52-1.92 0-1.181-.587-1.925-1.52-1.925-.937 0-1.508.728-1.508 1.92zM99.817 16.325a2.693 2.693 0 0 1 1.58-2.71 2.668 2.668 0 0 1 3.619 1.607c.118.355.161.73.125 1.103a2.703 2.703 0 0 1-.681 2.064 2.68 2.68 0 0 1-1.981.88 2.665 2.665 0 0 1-1.981-.88 2.7 2.7 0 0 1-.68-2.064zm4.178 0c0-1.228-.549-1.947-1.514-1.947-.968 0-1.513.719-1.513 1.947 0 1.238.545 1.95 1.513 1.95.965 0 1.514-.717 1.514-1.95zM106.637 13.494h1.072v.9h.083a1.684 1.684 0 0 1 1.685-1.01 1.833 1.833 0 0 1 1.89 1.291c.082.264.104.543.063.817v3.668h-1.114v-3.387c0-.91-.394-1.364-1.218-1.364a1.288 1.288 0 0 0-1.002.407 1.308 1.308 0 0 0-.345 1.03v3.314h-1.114v-5.666zM117.722 12.082v1.437h1.223v.942h-1.223v2.913c0 .594.244.854.798.854.142 0 .284-.01.425-.026v.931c-.2.036-.403.056-.606.058-1.239 0-1.732-.438-1.732-1.53v-3.2h-.896v-.942h.896v-1.437h1.115zM120.469 11.281h1.104v3.123h.088a1.741 1.741 0 0 1 1.721-1.015 1.856 1.856 0 0 1 1.874 1.301c.083.262.106.539.07.811v3.659h-1.115v-3.383c0-.905-.42-1.363-1.207-1.363a1.314 1.314 0 0 0-1.348.87c-.065.18-.09.374-.073.566v3.31h-1.114V11.28zM131.819 17.63a2.298 2.298 0 0 1-.926 1.266c-.447.3-.985.432-1.519.374a2.552 2.552 0 0 1-1.978-.856 2.57 2.57 0 0 1-.63-2.069 2.623 2.623 0 0 1 1.52-2.733c.341-.153.71-.23 1.083-.227 1.57 0 2.518 1.077 2.518 2.856v.39h-3.986v.063a1.495 1.495 0 0 0 1.503 1.623 1.348 1.348 0 0 0 1.343-.686h1.072zm-3.918-1.825h2.851a1.371 1.371 0 0 0-.835-1.364 1.36 1.36 0 0 0-.554-.104 1.444 1.444 0 0 0-1.462 1.468z" fill="#fff"></path> 
            </svg></a> 
           <a href="https://zineddineboui.github.io/qurankarim/" target="_blank" rel="noopener noreferrer" download=""> 
            <svg width="151" height="51" fill="none" xmlns="http://www.w3.org/2000/svg"> 
             <path d="M6.056 1.164h138.888c2.739 0 5.056 2.517 5.056 5.75v37.5c0 3.233-2.317 5.75-5.056 5.75H6.056C3.317 50.164 1 47.647 1 44.414v-37.5c0-3.233 2.317-5.75 5.056-5.75z" fill="#000" stroke="#A6A6A6"></path> 
             <path d="M53.189 14.382a2.966 2.966 0 0 1-.834 2.2 3.25 3.25 0 0 1-2.444.968 3.362 3.362 0 0 1-2.456-.99 3.49 3.49 0 0 1-1.01-2.453 3.49 3.49 0 0 1 1.01-2.453 3.544 3.544 0 0 1 3.822-.715c.401.163.758.415 1.045.737l-.589.583a2.22 2.22 0 0 0-1.822-.792 2.68 2.68 0 0 0-1.886.773 2.627 2.627 0 0 0-.78 1.867c0 .7.28 1.372.78 1.867a2.68 2.68 0 0 0 1.886.773 2.556 2.556 0 0 0 1.855-.737c.347-.365.549-.842.567-1.342h-2.422v-.792h3.233c.025.168.04.337.045.506zM58.277 11.632h-3v2.09h2.733v.792h-2.733v2.09h3v.814H54.41v-6.6h3.867v.814zM61.921 17.418h-.855v-5.786h-1.867v-.814h4.634v.814H61.92v5.786zM67.102 17.418v-6.6h.855v6.6h-.855zM71.754 17.418h-.856v-5.786H69.03v-.814h4.578v.814h-1.855v5.786zM82.289 16.56a3.486 3.486 0 0 1-4.889 0 3.545 3.545 0 0 1-.978-2.442c0-.908.35-1.781.978-2.442a3.284 3.284 0 0 1 2.445-1.001 3.362 3.362 0 0 1 2.444 1 3.373 3.373 0 0 1 .977 2.443 3.27 3.27 0 0 1-.977 2.442zm-4.256-.55a2.546 2.546 0 0 0 1.811.75 2.566 2.566 0 0 0 1.811-.75c.48-.516.746-1.191.746-1.892 0-.701-.266-1.376-.746-1.892a2.547 2.547 0 0 0-1.81-.75 2.566 2.566 0 0 0-1.812.75 2.778 2.778 0 0 0-.746 1.892c0 .7.267 1.376.746 1.892zM84.477 17.418v-6.6h1.033l3.244 5.137V10.82h.856v6.6h-.889l-3.389-5.38v5.379h-.855z" fill="#fff" stroke="#fff" stroke-width="0.218" stroke-miterlimit="10"></path> 
             <path d="M76.21 27.043c-.935.002-1.85.279-2.627.796a4.697 4.697 0 0 0-1.738 2.107 4.643 4.643 0 0 0-.263 2.708 4.672 4.672 0 0 0 1.3 2.396 4.748 4.748 0 0 0 2.427 1.277c.919.178 1.87.083 2.734-.273a4.723 4.723 0 0 0 2.12-1.731 4.652 4.652 0 0 0 .792-2.605 4.568 4.568 0 0 0-.343-1.805 4.606 4.606 0 0 0-1.028-1.529 4.66 4.66 0 0 0-1.549-1.01c-.58-.23-1.2-.343-1.824-.331zm0 7.513a2.89 2.89 0 0 1-1.643-.38 2.85 2.85 0 0 1-1.143-1.228 2.813 2.813 0 0 1 .488-3.156 2.893 2.893 0 0 1 3.145-.71c.535.208.995.57 1.32 1.04.325.47.5 1.026.5 1.596a2.68 2.68 0 0 1-.728 1.976 2.732 2.732 0 0 1-1.938.862zm-10.355-7.513c-.936.002-1.85.279-2.628.796a4.696 4.696 0 0 0-1.738 2.107 4.643 4.643 0 0 0-.263 2.708 4.671 4.671 0 0 0 1.301 2.396 4.749 4.749 0 0 0 2.427 1.277 4.78 4.78 0 0 0 2.734-.273 4.723 4.723 0 0 0 2.12-1.731 4.652 4.652 0 0 0 .792-2.605 4.57 4.57 0 0 0-.343-1.805 4.606 4.606 0 0 0-1.028-1.529 4.66 4.66 0 0 0-1.55-1.01c-.579-.23-1.2-.343-1.824-.331zm0 7.513a2.89 2.89 0 0 1-1.643-.38 2.849 2.849 0 0 1-1.143-1.228 2.813 2.813 0 0 1 .487-3.156 2.894 2.894 0 0 1 3.145-.71c.536.208.996.57 1.32 1.04.325.47.5 1.026.5 1.596a2.682 2.682 0 0 1-.728 1.976 2.734 2.734 0 0 1-1.938.862zm-12.31-6.072v1.98h4.8a4.127 4.127 0 0 1-1.112 2.497 4.916 4.916 0 0 1-1.7 1.116c-.64.25-1.324.364-2.011.336a5.36 5.36 0 0 1-3.771-1.547 5.253 5.253 0 0 1-1.562-3.733c0-1.4.562-2.744 1.562-3.734a5.36 5.36 0 0 1 3.77-1.546 5.183 5.183 0 0 1 3.645 1.419l1.412-1.397a7.007 7.007 0 0 0-2.313-1.504 7.062 7.062 0 0 0-2.72-.498 7.41 7.41 0 0 0-2.898.47 7.353 7.353 0 0 0-2.48 1.555 7.268 7.268 0 0 0-1.666 2.393 7.208 7.208 0 0 0 0 5.695c.387.9.954 1.714 1.666 2.393a7.355 7.355 0 0 0 2.48 1.555c.924.348 1.91.508 2.897.47a6.805 6.805 0 0 0 2.781-.475 6.75 6.75 0 0 0 2.341-1.56 6.562 6.562 0 0 0 1.734-4.653 6.829 6.829 0 0 0-.1-1.232h-6.756zm50.344 1.54a4.406 4.406 0 0 0-1.554-2.114 4.476 4.476 0 0 0-2.49-.867 4.483 4.483 0 0 0-1.768.359 4.443 4.443 0 0 0-1.478 1.025 4.36 4.36 0 0 0-1.2 3.29 4.622 4.622 0 0 0 .91 2.795c.6.81 1.448 1.406 2.418 1.7.97.293 2.01.267 2.964-.073a4.696 4.696 0 0 0 2.331-1.814l-1.611-1.1c-.24.396-.581.723-.988.949a2.702 2.702 0 0 1-1.334.338 2.408 2.408 0 0 1-1.367-.359 2.372 2.372 0 0 1-.922-1.06l6.322-2.585-.233-.484zm-6.445 1.562a2.55 2.55 0 0 1 .658-1.885 2.598 2.598 0 0 1 1.82-.854 1.84 1.84 0 0 1 1.025.24c.31.178.56.442.719.76l-4.222 1.739zm-5.133 4.532h2.078v-13.75H92.31v13.75zm-3.4-8.03h-.078c-.31-.35-.694-.63-1.123-.82a3.296 3.296 0 0 0-1.366-.28 4.755 4.755 0 0 0-3.198 1.448 4.661 4.661 0 0 0-1.306 3.232c0 1.204.468 2.361 1.306 3.232a4.754 4.754 0 0 0 3.198 1.449c.471.009.939-.085 1.369-.275.43-.19.813-.472 1.12-.825h.078v.67c0 1.794-.967 2.75-2.522 2.75a2.64 2.64 0 0 1-1.45-.47 2.6 2.6 0 0 1-.94-1.19l-1.8.737a4.409 4.409 0 0 0 1.66 2.03c.748.495 1.63.754 2.53.742 2.433 0 4.444-1.42 4.444-4.873v-8.327h-1.922v.77zm-2.39 6.468a2.879 2.879 0 0 1-1.91-.89 2.823 2.823 0 0 1-.777-1.943c0-.722.278-1.417.777-1.943a2.879 2.879 0 0 1 1.91-.89 2.677 2.677 0 0 1 1.873.883 2.624 2.624 0 0 1 .661 1.945 2.594 2.594 0 0 1-.653 1.955 2.644 2.644 0 0 1-1.88.883zm27.101-12.188h-4.978v13.75h2.078v-5.214h2.9a4.365 4.365 0 0 0 1.747-.233 4.33 4.33 0 0 0 1.507-.903 4.242 4.242 0 0 0 0-6.265 4.33 4.33 0 0 0-3.254-1.135zm0 6.6h-2.9v-4.686h2.944a2.394 2.394 0 0 1 1.682.69 2.355 2.355 0 0 1 .696 1.664 2.356 2.356 0 0 1-1.468 2.175c-.288.118-.597.179-.91.179l-.044-.022zm12.822-1.97a3.91 3.91 0 0 0-2.168.502 3.86 3.86 0 0 0-1.532 1.6l1.833.759c.186-.331.464-.601.801-.78a1.993 1.993 0 0 1 1.099-.221 2.025 2.025 0 0 1 1.487.424 1.988 1.988 0 0 1 .736 1.347v.132a4.683 4.683 0 0 0-2.167-.528c-1.978 0-4 1.1-4 3.102a3.155 3.155 0 0 0 1.081 2.237 3.215 3.215 0 0 0 2.375.788 2.967 2.967 0 0 0 1.505-.317c.465-.236.858-.59 1.139-1.025h.067v1.1h2v-5.291c0-2.41-1.845-3.806-4.211-3.806l-.045-.022zm-.255 7.536c-.678 0-1.623-.341-1.623-1.166 0-1.1 1.178-1.474 2.223-1.474a3.714 3.714 0 0 1 1.888.462 2.47 2.47 0 0 1-.805 1.554 2.525 2.525 0 0 1-1.639.646l-.044-.022zm11.8-7.216-2.378 5.962h-.067l-2.467-5.962h-2.222l3.7 8.338-2.111 4.63h2.167l5.689-12.968h-2.311zm-18.667 8.8h2.067v-13.75h-2.067v13.75z" fill="#fff"></path> 
             <path d="M12.101 11.413c-.366.428-.553.98-.522 1.54v24.332a2.12 2.12 0 0 0 .522 1.54l.078.088 13.767-13.63v-.33L12.179 11.337l-.078.077z" fill="url(#a)"></path> 
             <path d="m30.5 29.826-4.555-4.543v-.33l4.556-4.543.1.066 5.455 3.058c1.556.87 1.556 2.3 0 3.18l-5.433 3.057-.122.055z" fill="url(#b)"></path> 
             <path d="m30.635 29.76-4.689-4.643-13.844 13.706a1.81 1.81 0 0 0 2.3.077l16.233-9.14" fill="url(#c)"></path> 
             <path d="m30.635 20.475-16.233-9.13a1.801 1.801 0 0 0-2.3.066l13.844 13.706 4.689-4.642z" fill="url(#d)"></path> 
             <path opacity="0.2" d="m30.502 29.66-16.1 9.075a1.857 1.857 0 0 1-2.223 0l-.077.077.077.088a1.857 1.857 0 0 0 2.223 0l16.233-9.14-.133-.1z" fill="#000"></path> 
             <path opacity="0.12" d="M12.1 38.67a2.185 2.185 0 0 1-.488-1.55v.164a2.12 2.12 0 0 0 .522 1.54l.078-.077-.111-.077zM36.056 26.547 30.5 29.66l.1.1 5.456-3.059c.322-.135.6-.353.808-.632.208-.278.335-.607.37-.952a2.065 2.065 0 0 1-1.178 1.43z" fill="#000"></path> 
             <path opacity="0.25" d="m14.4 11.501 21.656 12.188c.296.13.556.328.76.576.205.248.348.541.418.854a1.914 1.914 0 0 0-.37-.952 1.942 1.942 0 0 0-.808-.632L14.4 11.347c-1.544-.88-2.822-.154-2.822 1.606v.165c.034-1.76 1.278-2.486 2.822-1.617z" fill="#fff"></path> 
             <defs> 
              <lineargradient id="a" x1="24.723" y1="12.7" x2="6.266" y2="31.343" gradientunits="userSpaceOnUse"> 
               <stop stop-color="#00A0FF"></stop> 
               <stop offset="0.01" stop-color="#00A1FF"></stop> 
               <stop offset="0.26" stop-color="#00BEFF"></stop> 
               <stop offset="0.51" stop-color="#00D2FF"></stop> 
               <stop offset="0.76" stop-color="#00DFFF"></stop> 
               <stop offset="1" stop-color="#00E3FF"></stop> 
              </lineargradient> 
              <lineargradient id="b" x1="38.09" y1="25.118" x2="11.212" y2="25.118" gradientunits="userSpaceOnUse"> 
               <stop stop-color="#FFE000"></stop> 
               <stop offset="0.41" stop-color="#FFBD00"></stop> 
               <stop offset="0.78" stop-color="orange"></stop> 
               <stop offset="1" stop-color="#FF9C00"></stop> 
              </lineargradient> 
              <lineargradient id="c" x1="28.09" y1="27.647" x2="3.056" y2="52.924" gradientunits="userSpaceOnUse"> 
               <stop stop-color="#FF3A44"></stop> 
               <stop offset="1" stop-color="#C31162"></stop> 
              </lineargradient> 
              <lineargradient id="d" x1="8.613" y1="3.315" x2="19.788" y2="14.604" gradientunits="userSpaceOnUse"> 
               <stop stop-color="#32A071"></stop> 
               <stop offset="0.07" stop-color="#2DA771"></stop> 
               <stop offset="0.48" stop-color="#15CF74"></stop> 
               <stop offset="0.8" stop-color="#06E775"></stop> 
               <stop offset="1" stop-color="#00F076"></stop> 
              </lineargradient> 
             </defs> 
            </svg></a> 
          </div> 
          <div class="jss45"> 
           <a rel="noopener noreferrer" href="/about">About</a> 
           <a rel="noopener noreferrer" href="/press">Press</a> 
           <a rel="noopener noreferrer" href="/terms">Terms of Use</a> 
           <a rel="noopener noreferrer" href="/privacy">Privacy Policy</a> 
           <span class="jss46">?? 2021 GETTR, Inc.</span> 
          </div> 
         </div> 
        </div> 
       </div> 
       <div class="jss47"> 
        <div class="jss48"> 
         <div class="MuiGrid-root MuiGrid-container"> 
          <div class="MuiGrid-root jss49 MuiGrid-item MuiGrid-grid-xs-6"> 
           <p class="MuiTypography-root jss51 MuiTypography-body1">Ce site utilise des cookies.</p> 
           <span class="jss54 fr_fr">Pour en savoir plus</span> 
          </div> 
          <div class="MuiGrid-root jss50 MuiGrid-item MuiGrid-grid-xs-6"> 
           <div> 
            <button class="MuiButtonBase-root MuiButton-root MuiButton-outlined jss39 jss52 jss53 fr_fr bold" tabindex="0" type="button"><span class="MuiButton-label">Accepter les cookies</span></button> 
           </div> 
          </div> 
         </div> 
        </div> 
       </div> 
      </div> 
     </div> 
    </div> 
   </div> 
   <div class="Toastify"></div> 
  </div> 
 </body>
</html>
