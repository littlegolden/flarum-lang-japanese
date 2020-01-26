## Flarum 日本語言語パック (beta 8+)
Based on original work (c) 2018 [setsunaMC](https://github.com/setsunaMC/flarum-ext-japanese) and (c) 2019 [rikusen0335](https://github.com/rikusen0335/lang-japanese-extended).

[Slicky](https://bbs.csur.fun/u/Slicky0611)と協力して翻訳します。

> [Read the description in English](https://github.com/Littlegolden/flarum-lang-japanese/blob/master/README_en.md)

### 需要条件
  - Flarum v0.1.0-beta.8 or later


### インストールする
```
composer require littlegolden/flarum-lang-japanese
```

### 更新する
```
composer update littlegolden/flarum-lang-japanese
```

### アンインストール
```
composer remove littlegolden/flarum-lang-japanese
```

### あ、あとアップデートしたらこのコマンドも打つのを忘れないでね！
```
php flarum cache:clear
```

### サポートされている拡張機能

<details>
<summary>見に展開</summary>

  - amaurycarrade-syndication（[Syndication extension](https://discuss.flarum.org/d/4395-syndication-extension-rss-atom-feeds)）
  - antoinefr-money（[Money extension](https://discuss.flarum.org/d/4699-money-extension)）
  - antoinefr-online（[Online users extension](https://discuss.flarum.org/d/8302-online-users-extension)）
  - backtowebsite（[Back to Website Button](https://discuss.flarum.org/d/18285-back-to-website-button)）
  - clarkwinkelmann-author-change（[Discussion and post author change](https://discuss.flarum.org/d/21731-discussion-and-post-author-change)）
  - clarkwinkelmann-create-user-modal（[Create User Modal](https://discuss.flarum.org/d/22608-create-user-modal)）
  - clarkwinkelmann-email-as-display-name（[Email as Display Name](https://discuss.flarum.org/d/22603-email-as-display-name)）
  - clarkwinkelmann-emojionearea（[Emoji Picker](https://discuss.flarum.org/d/4787-emoji-picker)）
  - clarkwinkelmann-passwordless（[Passwordless login](https://discuss.flarum.org/d/22606-passwordless-login)）
  - clarkwinkelmann-post-date（[Change post date](https://discuss.flarum.org/d/21247-change-post-date)）
  - clarkwinkelmann-status（[User status](https://discuss.flarum.org/d/21983-user-status)）
  - datitisev-dashboard（[Datitisev Admin Dashboard](https://discuss.flarum.org/d/2958-datitisev-admin-dashboard)）
  - dem13n-nickname-changer（[NickName Changer](https://discuss.flarum.org/d/21238-nickname-changer)）
  - dem13n-quad-theme（[Quad theme](https://discuss.flarum.org/d/22618-quad-theme)）
  - extiverse-bazaar（[Bazaar extension marketplace](https://discuss.flarum.org/d/5151-bazaar-the-extension-marketplace)）
  - fajuu-contactbutton（[Contact Button](https://discuss.flarum.org/d/18228-contact-button)）
  - fajuu-icons（[Icons by Fajuu](https://discuss.flarum.org/d/21401-icons-by-fajuu)）
  - flagrow-ads（[Flagrow Ads](https://discuss.flarum.org/d/4785-flagrow-ads-bombarding-your-users-with-ads-everywhere-if-you-want)）
  - flagrow-analytics（[Flagrow analytics extension](https://discuss.flarum.org/d/1983-flagrow-analytics-extension-tracking-user-visits)）
  - flagrow-fonts（[Flagrow Fonts](https://discuss.flarum.org/d/6207-flagrow-fonts-easily-add-fonts-to-your-forum)）
  - flagrow-html-errors（[Custom HTML Error Pages](https://discuss.flarum.org/d/10784-custom-html-error-pages)）
  - flagrow-impersonate（[Flagrow Impersonate](https://discuss.flarum.org/d/9868-flagrow-impersonate-login-as-other-users)）
  - ~~flagrow-mason（[Flagrow Mason](https://discuss.flarum.org/d/7028-flagrow-mason-the-discussion-custom-fields-builder)）~~ 最新バージョンと互換性がない
  - flagrow-passport（[Flagrow passport](https://discuss.flarum.org/d/5203-flagrow-passport-the-laravel-passport-oauth-extension)）
  - flagrow-upload（[Flagrow upload](https://discuss.flarum.org/d/4154-flagrow-upload-the-intelligent-file-attachment-extension)）
  - flarum-akismet（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-approval（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-auth-facebook（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-auth-github（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-auth-twitter（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-core（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-discussion-views（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-emoji（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-ext-close（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-ext-fancybox（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-flags（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-likes（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-lock（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-markdown（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-mentions（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-notify（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-pusher（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-statistics（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-sticky（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-subscriptions（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-suspend（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - flarum-tags（[Flarum Core](https://github.com/flarum/lang-english/tree/master/locale)）
  - fof-amazon-affiliation（[Amazon Affiliation](https://discuss.flarum.org/d/12389-friendsofflarum-amazon-affiliation)）
  - fof-auth-gitlab（[GitLab Login](https://discuss.flarum.org/d/20371-friendsofflarum-gitlab-login)）
  - fof-ban-ips（[Ban IPs](https://discuss.flarum.org/d/20949-friendsofflarum-ban-ips)）
  - fof-best-answer（[Best Answer](https://discuss.flarum.org/d/21894-friendsofflarum-best-answer)）
  - fof-byobu（[Byōbu](https://discuss.flarum.org/d/4762-friendsofflarum-by-bu-well-integrated-advanced-private-discussions)）
  - fof-custom-footer（[Custom Footer](https://discuss.flarum.org/d/17774-friendsofflarum-custom-footer)）
  - fof-default-group（[Default Group](https://discuss.flarum.org/d/18158-friendsofflarum-default-group)）
  - fof-drafts（[Drafts](https://discuss.flarum.org/d/20957-friendsofflarum-drafts)）
  - fof-email-checker（[Disposable Emails](https://discuss.flarum.org/d/20457-friendsofflarum-disposable-emails)）
  - fof-follow-tags（[Follow Tags](https://discuss.flarum.org/d/20525-friendsofflarum-follow-tags)）
  - fof-formatting（[Formatting](https://discuss.flarum.org/d/17770-friendsofflarum-formatting/111)）
  - fof-forum-statistics-widget（[Statistics Widget](https://discuss.flarum.org/d/22380-friendsofflarum-forum-statistics-widget)）
  - fof-frontpage（[FrontPage](https://discuss.flarum.org/d/19256-friendsofflarum-frontpage)）
  - fof-gamification（[Gamification](https://discuss.flarum.org/d/20671-friendsofflarum-gamification)）
  - fof-geoip（[GeoIP](https://discuss.flarum.org/d/21493-friendsofflarum-geoip)）
  - fof-ignore-users（[Ignore Users](https://discuss.flarum.org/d/20681-friendsofflarum-ignore-users)）
  - fof-linguist（[Linguist](https://discuss.flarum.org/d/7026-linguist-customize-translations-with-ease)）
  - fof-links（[Links](https://discuss.flarum.org/d/18335-friendsofflarum-links)）
  - fof-masquerade（[Masquerade by FriendsOfFlarum](https://discuss.flarum.org/d/5791-masquerade-by-friendsofflarum-the-user-profile-builder)）
  - fof-merge-discussions（[Masquerade](https://discuss.flarum.org/d/5791-masquerade-by-friendsofflarum-the-user-profile-builder)）
  - fof-nightmode（[Night Mode](https://discuss.flarum.org/d/21492-friendsofflarum-night-mode)）
  - fof-open-collective（[Open Collective](https://discuss.flarum.org/d/22256-friendsofflarum-open-collective)）
  - fof-pages（[Pages](https://discuss.flarum.org/d/18301-friendsofflarum-pages)）
  - fof-polls（[Polls](https://discuss.flarum.org/d/20586-friendsofflarum-polls)）
  - fof-pretty-mail（[Pretty Mail](https://discuss.flarum.org/d/11178-friendsofflarum-pretty-mail)）
  - fof-prevent-necrobumping（[Prevent Necrobumping](https://discuss.flarum.org/d/18312-friendsofflarum-prevent-necrobumping)）
  - fof-pwned-passwords（[Pwned Passwords](https://discuss.flarum.org/d/18348-friendsofflarum-pwned-passwords)）
  - fof-reactions（[Reactions](https://discuss.flarum.org/d/20655-friendsofflarum-reactions)）
  - fof-recaptcha（[reCAPTCHA](https://discuss.flarum.org/d/18399-friendsofflarum-recaptcha)）
  - fof-secure-https（[Secure HTTPS](https://discuss.flarum.org/d/17771-friendsofflarum-secure-https)）
  - fof-sentry（[Sentry](https://discuss.flarum.org/d/18089-friendsofflarum-sentry/34)）
  - fof-share-social（[Share Social](https://discuss.flarum.org/d/20401-friendsofflarum-share-social)）
  - fof-socialprofile（[Social Profile](https://discuss.flarum.org/d/18775-friendsofflarum-social-profile)）
  - fof-spamblock（[Spamblock](https://discuss.flarum.org/d/17772-friendsofflarum-spamblock)）
  - fof-stopforumspam（[StopForumSpam](https://discuss.flarum.org/d/17846-friendsofflarum-stopforumspam)）
  - fof-split（[Split](https://discuss.flarum.org/d/1903-friendsofflarum-split-separates-posts-to-a-new-discussion)）
  - fof-subscribed（[Subscribed](https://discuss.flarum.org/d/20917-friendsofflarum-subscribed)）
  - fof-terms（[Terms](https://discuss.flarum.org/d/11714-fof-terms-ask-your-users-to-accept-tos-and-privacy-policy)）
  - fof-transliterator（[URL Transliterator](https://discuss.flarum.org/d/18074-friendsofflarum-url-transliterator)）
  - fof-user-directory（[User directory](https://discuss.flarum.org/d/5682-user-directory-by-friendsofflarum)）
  - fof-userbio（[User Bio](https://discuss.flarum.org/d/17775-friendsofflarum-user-bio)）
  - fof-username-request（[Username Request](https://discuss.flarum.org/d/20956-friendsofflarum-username-request)）
  - imgur-upload（[Imgur Upload](https://discuss.flarum.org/d/18491-imgur-upload-simple-image-upload-from-the-editor)）
  - kilowhat-affiliation-links（[Multi-Purpose Affiliation Links Generator](https://discuss.flarum.org/d/21833-multi-purpose-affiliation-links-generator)）
  - kilowhat-mailing（[Mailing](https://discuss.flarum.org/d/20443-mailing-by-kilowhat)）
  - kvothe-sub（[Sign Up Button](https://discuss.flarum.org/d/18812-sign-up-button)）
  - maicol07-sso（[Single Sign On (SSO)](https://discuss.flarum.org/d/21666-single-sign-on-sso-with-wordpress-integration)）
  - migratetoflarum-canonical（[Canonical url redirect](https://discuss.flarum.org/d/19307-canonical-url-redirect)）
  - michaelBelgium-profile-views（[Profile views](https://discuss.flarum.org/d/7596-profile-views)）
  - migratetoflarum-fake-data（[Fake Data](https://discuss.flarum.org/d/21160-fake-data)）
  - ~~migratetoflarum-vbulletin-redirects（[Redirects](https://github.com/migratetoflarum/vbulletin-redirects)）~~ 最新バージョンと互換性がない
  - mybbtoflarum（[MyBB to flarum](https://discuss.flarum.org/d/5506-mybb-to-flarum)）
  - nikovonlas-webpush（[OneSignal web push notifications](https://discuss.flarum.org/d/20784-onesignal-web-push-notifications)）
  - perspective（[Perspective API](https://discuss.flarum.org/d/21784-perspective-api)）
  - pushedx-chat（[Realtime chat with Pusher (Alpha)](https://discuss.flarum.org/d/5133-wip-extension-realtime-chat-with-pusher/12)）
  - reflar-cookie-consent（[Cookie Consent](https://discuss.flarum.org/d/10395-cookie-consent)）
  - reflar-doorman（[Doorman](https://discuss.flarum.org/d/17845-doorman-by-reflar)）
  - reflar-level-ranks（[Levels Ranks](https://discuss.flarum.org/d/15052-levels-ranks-by-reflar)）
  - reflar-twofactor（[Two Factor](https://discuss.flarum.org/d/11006-twofactor-by-reflar)）
  - reflar-webhooks（[Webhooks](https://discuss.flarum.org/d/17812-webhooks-by-reflar)）
  - saleksin-auth-google（[Google Login](https://discuss.flarum.org/d/18250-google-login)）
  - shriker-pronouns（[Personal Pronouns](https://discuss.flarum.org/d/21188-personal-pronouns)）
  - simonxeko/follow-users（[Follow Users (WIP)](https://discuss.flarum.org/d/22628-follow-users-wip)）
  - tpokorra-post-notification（[Post Notifications per E-Mail](https://discuss.flarum.org/d/20750-post-notifications-per-e-mail)）
  - v17development-flarum-seo（[Flarum SEO](https://discuss.flarum.org/d/18316-flarum-seo)）
  - xmugenx-post-blacklist（[Post Blacklist](https://discuss.flarum.org/d/21750-post-blacklist)）
  - zerosonesfun-announce（[Announce](https://discuss.flarum.org/d/21651-announce)）

</details>

### デモ
  - https://bbs.csur.fun

### 問題を報告する
  - [Github](https://github.com/Littlegolden/flarum-lang-japanese/issues)
  - [bbs.csur.fun](https://bbs.csur.fun/t/chatroom)

### リンク
  - [Flarum](https://discuss.flarum.org/d/17954)
  - [Github](https://github.com/littlegolden/flarum-lang-japanese)
  - [Packagist](https://packagist.org/packages/littlegolden/flarum-lang-japanese)

### 寄付
Buy me a cup of coffee \^_\^

[Donate](https://pay.csur.fun)
