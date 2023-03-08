<h2 align="center">
🛡️ Facebook Bug Bounty Writeups Collection ✍️
</h2>

<h4 align ="center">
💖 A curated list of Facebook bug bounty writeups by various security researchers.🌙
</h4>

##### `You can contribute to this collection by submitting your own writeup or any others you know of, written in clear and concise English. Your contributions will help others learn from your experiences and improve the security of Facebook's platform.`


## Table of Contents

  - [Account Takeovers](#ATO)
  - [Remove Code Execution](#RCE) 
  - [Two-Factor Authentication Bypass](#2FA)
  - [Cross-Site Scripting](#XSS)
  - [Cross-Site Request Forgery](#CSRF)
  - [Server-Side Request Forgery](#SSRF)
  - [Logic Vulnerabilities](#LOGIC)
  - [Race Conditions](#RC)
  - [Rate Limits](#RL)
  - [Open Redirects](#OR)
  - [Clickjacking](#CLJ)
  - [Insecure Direct Object Reference](#IDOR)
  - [Privacy/spam](#PS)
  - [Page Roles](#PR)
  - [Facebook Ads](#FA)
  - [Facebook Groups](#FG)
  - [Phone Numbers](#PHN)
  - [Email Address](#EA)
  - [BIP Address](#BIPA)
  - [Symlink Attack](#SYMA)
  - [Accellion’s Secure File Transfer](#ASFT)
  - [XXE](#XXE)
  - [LFI](#LFI)
  - [SQL Injection](#SQLI)
  - [Jenkins](#JK)
  - [API](#API)
  - [GraphQL](#GQ)
  - [FQL](#FQL)
  - [Logic Nonces](#LN)
  - [OAuth](#OAUTH)
  - [Instagram](#IG)
  - [Signal](#SIGNAL)
  - [Slingshot](#SLING)
  - [Messenger Android](#MA)
  - [Moments](#MOMENTS)
  - [Moves](#MOVES)
  - [WhatsApp](#WTP)
  - [Workplace](#WOP)
  - [Whitehat Test Accounts](#WTA)
  - [Facebook Events ](#FE)
  - [DoS Attack](#DOS)
  - [Facebook/Instagram Mobile App](#MBL)
  - [Extra resources](#EXTRAS)
  - [Thanks](#THX)

 
![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="ATO"></a>
### Account Takeovers

- [React debugkeystore key was trusted by Facebook and Oculus domains, leading to account takeover.](https://www.vulnano.com/2022/07/react-debugkeystore-key-was-trusted-by.html)
- [Multiple bugs chained to takeover Facebook Accounts which uses Gmail.](https://ysamm.com/?p=763)
- [Account takeover of Facebook/Oculus accounts due to First-Party access_token stealing.](https://ysamm.com/?p=777)
- [Multiple bugs chained to takeover Facebook Accounts which uses Gmail.](https://ysamm.com/?p=763)
- [Multiple bugs allowed malicious Android Applications to takeover Facebook/Workplace accounts.](https://ysamm.com/?p=729)
- [More secure Facebook Canvas : Tale of $126k worth of bugs that lead to Facebook Account Takeovers.](https://ysamm.com/?p=708)
- [Account takeover of Instagram accounts due to unrestricted permissions of third-party application’s generated tokens.](https://ysamm.com/?p=684)
- [Facebook account takeover due to unsafe redirects after the OAuth flow.](https://ysamm.com/?p=667)
- [Facebook account takeover due to a wide platform bug in ajaxpipe responses.](https://ysamm.com/?p=654)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

 
<a name="RCE"></a>
### Remote Code Execution<br>
- [Facebook's imagetragick story.](https://4lemon.ru/2017-01-17_facebook_imagetragick_remote_code_execution.html)
- [Meta's SparkAR RCE Via ZIP Path Traversal .](https://blog.fadyothman.com/metas-sparkar/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


<a name="2FA"></a>
### 2FA Bypass<br>
- [How I could’ve bypassed the 2FA security of Instagram once again.](https://infosecwriteups.com/how-i-couldve-bypassed-the-2fa-security-of-instagram-once-again-43c05cc9b755)
- [Bypassing 2-Factor Authentication for Facebook Business Manager (Bounty: 1000 USD)](https://infosecwriteups.com/bypassing-2-factor-authentication-for-facebook-business-manager-bounty-1000-usd-c78c858459d6)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="XSS"></a>
### XSS
- [XSS in Facebook CDN due to improper filtering of uploaded files extensions](https://ysamm.com/?p=632)
- [One-click reflected XSS in www.instagram.com due to unfiltered URI schemes leads to account takeover](https://ysamm.com/?p=695)
- [Stored XSS on Facebook.](https://opnsec.com/2018/03/stored-xss-on-facebook)
- Stored XSS on Facebook. [`thread`](https://twitter.com/opnsec/status/855076273395204097), [`POC`](https://www.youtube.com/watch?v=Q9bsKjUd1hM&feature=youtu.be)
- [An XSS on Facebook via PNGs & Wonky Content Types](https://whitton.io/articles/xss-on-facebook-via-png-content-types/)
- [Ability to upload HTML via SRT caption files for Facebook Videos](https://philippeharewood.com/ability-to-upload-html-via-srt-caption-files-for-facebook-videos/)
   <!-- DEAD LINKS 
   
   http://breaksec.com/?p=5713
   http://blog.ptsecurity.com/2013/10/a-story-about-xss-on-facebook.html
   https://www.youtube.com/watch?v=NQOK9-OXwsc
   https://dr4cun0.com/blog/ssrf-at-update-subscription-menu/    
   
   -->
- [Another xss in facebook.](http://nirgoldshlager.blogspot.com/2013/01/another-stored-xss-in-facebookcom.html)
- [Xss in facebook translations ](https://nealpoole.com/blog/2011/03/xss-vulnerability-in-facebook-translations/)
- [Lessons from fb security bb program.](https://nealpoole.com/blog/2011/08/lessons-from-facebooks-security-bug-bounty-program/)
- [Facebook Bug Bounty 2014, Reflected XSS and Filter Evasion worth $7500.](http://www.paulosyibelo.com/2014/07/the-unseen-facebook-bug-bounty-2014-x.html)
- [Facebook FriendFeed Stored XSS](https://prakharprasad.com/facebook-friendfeed-stored-xss/)
- [Stored XSS on Atlassolutions (Facebook Acquisition)](https://medu554.blogspot.com/2014/02/stored-xss-on-atlassolutions-facebook.html)

- [Facebooks Boltpeters.com Configuration File Source Code Disclosure Vulnerability
](https://web.archive.org/web/20160119170845/http://www.websecresearch.com/2014/02/facebooks-boltpeterscom-configuration.html)
- [ See The Posts Of A Friend Who Blocked You](http://nbsriharsha.blogspot.in/2014/03/finally-facebook-hunted.html)
- [Content Types and XSS in Facebook Studio](https://whitton.io/articles/content-types-and-xss-facebook-studio/)
- [Facebook Fixes Minor Issues](https://en.internetwache.org/facebook-fixes-minor-issues-02-05-2014/)
- [Facebook XSS Vulnerability](https://silentzzz.blogspot.com/2007/11/facebook-xss-vulnerability.html)
- [Stored XSS in Facebook's Custom OpenGraph Action Type](https://habr.com/company/pt/blog/247709/)
- [XSS Vulnerability in Gill.is website](https://web.archive.org/web/20120416034642/http://gill.is/2012/04/11/new_website)
- [Stored XSS at Parse](https://dr4cun0.com/blog/stored-xss-at-parse/)
- [Reflected XSS in Instagram's Link Shim](https://web.archive.org/web/20160724215405/http://ameeras.me/Instagram-Reflected-XSS-in-Link-Shim/)
- [DOM XSS in Facebook Mobile Site/App Login](https://thesecurityexperts.wordpress.com/2017/12/20/dom-xss-in-facebook-mobile-siteapp-login/)


![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="CSRF"></a>
### CSRF
- [CSRF in Instagram](https://medium.com/@mohamedajimi59/csrf-in-instagram-461cbba286a)
- [Facebook SMS Captcha was Vulnerable to CSRF Attack](https://lokeshdlk77.medium.com/facebook-sms-captcha-was-vulnerable-to-csrf-attack-8db537b1e980)
- [Facebook Bug Bounty: The Most Severe CSRF Vulnerability](http://www.breaksec.com/?p=6192) ([video](https://vimeo.com/65453658))
- [Invisible Arbitrary CSRF Profile Picture Upload in Facebook](http://www.sneaked.net/invisible-arbitrary-csrf-profile-picture-upload-in-facebook)
- [Facebook CSRF Full Account Takeover](https://www.josipfranjkovic.com/blog/facebook-csrf-full-account-takeover)
- [Facebook Bug Bounty: Secondary Damage (CSRF via XSRF token)](https://josipfranjkovic.blogspot.com/2013/11/facebook-bug-bounty-secondary-damage.html)
- [Facebook CSRF Worth USD 5000](https://amolnaik4.blogspot.com/2012/08/facebook-csrf-worth-usd-5000.html)
- [Hacking any Facebook account - Exploit (PoC)](https://web.archive.org/web/20160110053958/http://www.dan-melamed.com/2013/06/hacking-any-facebook-account-exploit-poc.html)
- [Exploiting Facebook's Oculus](http://www.paulosyibelo.com/2015/01/facebooks-oculus-exploiting.html)
- [Multiple CSRF vulnerabilities in Facebook Messenger](http://blog.mazinahmed.net/2015/06/facebook-messenger-multiple-csrf.html)
- [Messenger Site-wide CSRF](https://whitton.io/articles/messenger-site-wide-csrf/)
- [FacebookMarketingDevelopers.com: Proxies, CSRF, quandry and API fun!](https://philippeharewood.com/facebookmarketingdevelopers-com-proxies-csrf-quandry-and-api-fun/)
- [Bypassing Facebook CSRF](https://blog.darabi.me/2015/04/bypass-facebook-csrf.html)
- [How I Bypassed Facebook CSRF in 2016](https://blog.darabi.me/2016/05/how-i-bypassed-facebook-csrf-in-2016.html)
- [Adding Welcome Notes to Facebook Groups using CSRF](https://niyaax9.blogspot.com/2016/04/facebook-csrf-adding-welcome-notes-to.html)
- [Cross-Site Request Forgery in Facebook](https://medium.com/@zahidali_93675/cross-site-request-forgery-in-facebook-86087201d8c)
- [Facebook Security Bug: CSRF in the Signup Form](https://www.facebook.com/groups/bugbountygroup/permalink/444862699243897/)
- [Low Hanging Fruits #4 - Facebook CSRF and more](https://exploitthesecurity.blogspot.com/2018/01/low-hanging-fruits-4.html)


![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="SSRF"></a>
### SSRF
- [$10000 Facebook SSRF (Bug Bounty)](https://amineaboud.medium.com/10000-facebook-ssrf-bug-bounty-402bd21e58e5)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="LOGIC"></a>
### Logic
- [How I Hacked Facebook Employees Secure Files Server](http://nirgoldshlager.blogspot.com/2013/01/how-i-hacked-facebook-employees-secure.html)
- [Breaking Facebook's Text Captcha](http://pwndizzle.blogspot.in/2014/07/breaking-facebooks-text-captcha.html)
- [Business Logic Flaw on Facebook (PoC)](http://bugbountypoc.com/business-logic-flaw-facebook-poc/)
- [Edit the Facebook Album Order of Any User](https://philippeharewood.com/edit-the-facebook-album-order-of-any-user/)
- [Missing Authorization Check in Pages Manager](http://bugbountypoc.com/missing-authorization-check-in-pages-manager/)
- [Facebook: Bypassing prohibit-embedding protection and stealing user data](https://immukul.blogspot.in/2017/04/facebook-bypassing-prohibit-embedding.html)
- [Facebook Vulnerability that allows to add almost anyone to any group](https://www.youtube.com/watch?v=Qu_A_s0LLbs)
- [Facebook bug allows to access other users' blocked friend list](https://www.youtube.com/watch?v=jxH1yyhCe_k)
- [Facebook Unrestricted File Upload to Remote Code Execution](https://www.youtube.com/watch?v=YFmvlInx4IQ)
- [Facebook Graph API Bug - Disclosing Friends List](https://www.youtube.com/watch?v=j_KiiiYpl4w)
- [Facebook Checkpoint Bypass](https://www.aryansinha.com/2017/08/facebook-checkpoint-flaw.html)


<a name="RC"></a>
### Race conditions

- [Race conditions on the web](https://www.josipfranjkovic.com/blog/race-conditions-on-web)
- [Race conditions on Facebook](https://josipfranjkovic.blogspot.com/2015/04/race-conditions-on-facebook.html)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="RL"></a>
### Rate Limits
- [Facebook Bug: PoC ContactPoint Inference](http://www.hackingmonks.net/2022/07/facebook-bug-poc-contactpoint-inference.html)
- [How I Could Have Hacked Your Facebook Account](http://www.anandpraka.sh/2016/03/how-i-could-have-hacked-your-facebook.html)
- [Facebook Account Takeover](http://arunsureshkumar.me/index.php/2016/04/24/facebook-account-take-over/)
- [Instagram Account Takeover](http://xss001.blogspot.in/2016/05/instagram-account-takeover.html)
- [Bug Hunter Discloses Way to Hack Instagram Accounts on Facebook](https://www.kieranclaessens.be/facebook-text-authentication-flaw.html)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="OR"></a>
### Open Redirect ($500+)
- [Multiple Open Redirection](https://thekaitokid.blogspot.com/2014/10/multiple-open-redirection.html)
- [Evading Facebook Linkshim](https://0xsobky.github.io/evading-facebook-linkshim/)
- [Multiple Open URL Redirection Vulnerability in Facebook Worth $1500](https://arulkumar.in/multiple-open-url-redirection-vulnerability-in-facebook-worth-1500/)
- [Cross-Site Scripting in Facebook Ads Manager](https://www.vulnerability-lab.com/get_content.php?id=975)
- [How I Discovered a $1000 Open Redirect in Facebook](https://yassineaboukir.com/blog/how-i-discovered-a-1000-open-redirect-in-facebook/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="CLJ"></a>
### Clickjacking
- [How I Got $5000 from Facebook Bug Bounty](https://www.codegrudge.com/2015/03/how-i-got-5000-from-facebook-bugbounty.html)
- [Facebook Bug Bounty: Clickjacking](http://www.paulosyibelo.com/2015/03/facebook-bug-bounty-clickjacking.html)
- [Bypassing Facebook's Login Protection](http://www.lachisterablanca.com/2014/02/bypass-de-la-proteccion-contra.html)



![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


<a name="IDOR"></a>
### Insecure Direct Object Reference (IDOR)
- [Instagram IDOR Bug - $4300](https://medium.com/@nvmeeet/4300-instagram-idor-bug-2022-5386cf492cad)
- [Disclosing Unconfirmed Email/Phone of a Facebook User](https://ysamm.com/?p=700)
- [Hacking Facebook.com/thanks for Posting on Your Wall](http://www.anandpraka.sh/2014/11/hacking-facebookcomthanks-posting-on.html)
- [Hijacking a Facebook Account with SMS](https://whitton.io/articles/hijacking-a-facebook-account-with-sms/)
- [Delete Any Photo from Facebook by Exploiting Support Dashboard](https://arulkumar.in/delete-any-photo-from-facebook-by-exploiting-support-dashboard/)
- [Removing Covers/Images on Friendship Pages on Facebook](https://whitton.io/articles/removing-covers-images-on-friendship-pages-on-facebook/)
- [How I Hacked Your Facebook Photos](https://zerohacks.com/bug-bounty-hacks/how-i-hacked-your-facebook-photos/)
- [Overwriting/Removing Cover Photos on Facebook Profiles](https://roy-castillo.blogspot.com/2016/02/overwritingremoving-cover-photos-on.html)
- [Facebook Page Takeover Zero-Day Vulnerability](http://arunsureshkumar.me/index.php/2016/09/16/facebook-page-takeover-zero-day-vulnerability/)
- [Insecure Direct Object Reference (IDOR) in Facebook Groups](https://russellaurio.blogspot.com/2016/11/insecure-direct-object-reference-idor.html)
- [Delete anyone's facebook video](https://www.youtube.com/watch?v=DvNHjh0EJNs)
- [Posting GIFs as Anyone on Facebook](https://philippeharewood.com/posting-gifs-as-anyone-on-facebook/)
- [Image Removal Vulnerability in Facebook](https://blog.darabi.me/2017/11/image-removal-vulnerability-in-facebook.html)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="PS"></a>
### Privacy/Spam
- [This is how I was able to see private archived posts/stories of users on Instagram without following them](https://infosecwriteups.com/this-is-how-i-was-able-to-see-private-archived-posts-stories-of-users-on-instagram-without-de70ca39165c)
- [A Facebook Bug That Exposes Email/Phone Number to Your Friends](https://iamsaugat.medium.com/a-facebook-bug-that-exposes-email-phone-number-to-your-friends-a980d24e5ea8)
- [This is how I was able to see and delete your private Facebook Portal photos](https://hiecstasy.medium.com/this-is-how-i-was-able-to-see-and-delete-your-private-facebook-portal-photos-a93ed22f875b)
- [Trim private live videos and access them](https://medium.com/@yaala/trim-private-live-videos-and-access-them-a331447cc82a)
- [Ability to Invite Any User to a Facebook Page (All Non-Friends)](https://philippeharewood.com/ability-to-invite-any-user-to-a-facebook-page-all-non-friends/)
- [How I Made $500 USD by Reporting Logical Vulnerability on Facebook](https://sweethacking.blogspot.com/2014/11/how-i-made-500-usd-by-reporting-logical.html)
- [Facebook User Identification Bug](http://patorjk.com/blog/2013/03/01/facebook-user-identification-bug/)
- [Facebook Privacy Bug: View Photos as a Blocked User](https://web.archive.org/web/20160125122634/http://allanjaydumanhug.ninja/blog/facebook-privacy-bug-view-photos-as-a-blocked-user/)
- [A Bug in Facebook That Violated My Privacy](https://ysamm.com/?p=280)
- [The Easiest Bug Bounties I Have Ever Won](https://josipfranjkovic.blogspot.com/2015/07/the-easiest-bug-bounties-i-have-ever-won.html)
- [Facebook’s Bug: Fooling Graph Search to Bypass Privacy Restrictions](https://pranavhivarekar.in/2016/02/20/facebooks-bug-fooling-graph-search-to-bypass-privacy-restrictions/)
- [Ability to Send Payment Requests Inspite of Being Blocked by the Recipient](https://web.archive.org/web/20160629134045/https://abhartiya.wordpress.com/2016/02/08/ability-to-send-payment-requests-inspite-of-being-blocked-by-the-recipient/)
- [Curiosity and Passion to Your Profession Might Lead to Make Your Dream Come True](https://medium.com/@rajsek/curiosity-and-passion-to-your-profession-might-lead-to-make-your-dream-come-true-7d9be3c6029a)
- [My 2nd Facebook Bounty POC: FB data of birth disclosure](https://medium.com/@rajsek/my-2nd-facebook-bounty-poc-fb-data-of-birth-disclosure-d02e1bec50)
- [Silently Using Facebook XMPP](https://dr4cun0.com/blog/silently-using-facebook-xmpp/) 
- [Find Mingle Suggestions for Any Facebook User](https://philippeharewood.com/find-mingle-suggestions-for-any-facebook-user/)
- [Find Mingle Suggestions for Any Facebook User Revisited](https://philippeharewood.com/find-mingle-suggestions-for-any-facebook-user-revisited/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="PR"></a>
### Page Roles
- [How I Was Able to Reveal Page Admin of Almost Any Page on Facebook](https://medium.com/pentesternepal/how-i-was-able-to-reveal-page-admin-of-almost-any-page-on-facebook-5a8d68253e0c)
- [Page Admin Disclosure When Posting a Reel](https://zerocode-ph.medium.com/page-admin-disclosure-when-posting-a-reel-1bfac9bd7f71)
- [How I Could Have Crashed Page Role](http://whitehatstories.blogspot.in/2017/09/how-i-could-have-crashed-page-role.html)
- [Tag Photos as a Page Analyst](https://philippeharewood.com/tag-photos-as-a-page-analyst/)
- [Using an Analyst Account to Post to Facebook Open Graph Objects](https://philippeharewood.com/using-an-analyst-account-to-post-to-facebook-open-graph-objects/)
- [Like Any Facebook Page as a Page Analyst](https://philippeharewood.com/like-any-facebook-page-as-a-page-analyst/)
- [Viewing Payment Information as an Ad Analyst](https://philippeharewood.com/viewing-payment-information-as-an-ad-analyst/)
- [View the Job Applications of a Page as an Analyst](https://philippeharewood.com/view-the-job-applications-of-a-page-as-an-analyst/)
- [Deactivate Facebook Page Shop as an Analyst](https://philippeharewood.com/deactivate-facebook-page-shop-as-an-analyst/)
- [Create a Product as an Analyst on a Facebook Page Store](https://philippeharewood.com/create-a-product-as-an-analyst-on-a-facebook-page-store/)
- [Disclose Users with Roles on Facebook Pages](https://philippeharewood.com/disclose-users-with-roles-on-facebook-pages/)
- [Change Trust Project Credibility Indicators as an Analyst](https://philippeharewood.com/change-trust-project-credibility-indicators-as-an-analyst/)
- [A Simple Bug on Facebook That Is Worth $8,000](https://medium.com/@ajdumanhug/a-simple-bug-on-facebook-that-is-worth-8000-b77f7e01b064)
- [Using App Ads Helper as an Analytic User](https://medium.com/@joshuaregio/using-app-ads-helper-as-an-analytic-user-e751fcf9c594)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="FA"></a>
### Facebook Ads
- [Instagram Ad Account Disclosure](https://www.yesnaveen.com/2021/12/Instagram-ad-account-disclosure.html)
- [Facebook Bypass Ads Account Roles](https://blog.darabi.me/2015/03/facebook-bypass-ads-account-roles.html)
- [Ads API Error Leads to Ad Account ID Being Leaked from the Legacy Account ID](https://philippeharewood.com/ads-api-error-leads-to-ad-account-id-being-leaked-from-the-legacy-account-id/)
- [View the Ads Retention Curve Completion Rate for Any Ad Account](https://philippeharewood.com/view-the-ads-retention-curve-completion-rate-for-any-ad-account/)
- [De-Anonymizing Facebook Ads](https://philippeharewood.com/de-anonymizing-facebook-ads/)
- [Session Expiration Bypass in Facebook Creator App](https://medium.com/@evilboyajay/session-expiration-bypass-in-facebook-creator-app-b4f65cc64ce4)
- [Whitehat: Test Accounts can act as Hidden Admin with Business Manager Ad Accounts](https://medium.com/@rohitcoder/whitehat-test-accounts-can-act-as-hidden-admin-with-business-manager-ad-accounts-ce75ead5ffff)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="FG"></a>
### Facebook Groups
- [Facebook Vulnerability Expose Group Member 3000+](https://medium.com/@muhammadsholikhin/facebook-vulnerability-expose-group-member-3000-cca809a53f6b)
- [Facebook Group Members Disclosure](https://spongebhav.medium.com/facebook-group-members-disclosure-e53eb83df39e)
- [Group Experts Pending Expertise Request Acceptance Disclosure](https://hopesamples.blogspot.com/2022/09/group-experts-pending-expertise-request.html)
- [How I was able to post in any Facebook group on behalf of its members](https://web.archive.org/web/20171103133104/http://thesecuritynews.com/project/how-i-was-able-to-post-in-any-facebook-group-on-behalf-of-its-members/)
- [POC Disclose Members in Any Closed Facebook Group](https://medium.com/@edmundaa222/poc-disclose-members-in-any-closed-facebook-group-259783fa4bf)
- [$2500 Lakhpati Bug at Facebook: Gaining access to files of a Closed Group](https://www.facebook.com/notes/$2500-lakhpati-bug-at-facebook-gaining-access-to-files-of-a-closed-group/686615161373797)
- [Get Group's DOC without User Permission: Facebook Graph API Bug](https://medium.com/@rahulmfg/get-groups-doc-without-user-permission-facebook-graph-api-bug-5f19367373a2)
- [The group idphotos endpoint isn't obeying the publish_actions and user_groups permission requirement](https://philippeharewood.com/the-group-idphotos-endpoint-isnt-obeying-the-publish_actions-and-user_groups-permission-requirement/)
- [Facebook Group Hack - In 2015 I Reported and Got 10,000$](https://zappstiko.blogspot.com/2017/02/facebook-group-hack-in-2015-i-reported.html)
- [Missing Functional Level Access Control in Secret Groups](https://medium.com/@iamkartiksingh/missing-functional-level-access-control-in-secret-groups-86da6c110775)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="PHN"></a>
### Phone number
- [How I Was Able to Remove Your Instagram Phone Number](https://medium.com/bugbountywriteup/how-i-was-able-to-remove-your-instagram-phone-number-d346515e79c3)
- [Determine a User from a Private Phone Number](https://philippeharewood.com/determine-a-user-from-a-private-phone-number/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="EA"></a>
### Email address
- [How I was able to remove your Instagram phone number](https://medium.com/bugbountywriteup/how-i-was-able-to-remove-your-instagram-phone-number-d346515e79c3)
- [Determine a user from a private phone number](https://philippeharewood.com/determine-a-user-from-a-private-phone-number/)
- [Confirming any new email address bug in Facebook (Part 4)](https://lokeshdlk77.medium.com/confirming-any-new-email-address-bug-in-facebook-part-4-70cfe1b4dca5)
- [Facebook email disclosure and account takeover](https://medium.com/pentesternepal/facebook-email-disclosure-and-account-takeover-ecdb44ee12e9)
- [A Facebook bug that exposes email/phone number to your friends](https://iamsaugat.medium.com/a-facebook-bug-that-exposes-email-phone-number-to-your-friends-a980d24e5ea8)
- [Obtaining the primary email address of any Facebook user](https://stephensclafani.com/2013/07/09/obtaining-the-primary-email-address-of-any-facebook-user/)
- [Disclosing the primary email address for each Facebook user](https://web.archive.org/web/20161223175543/http://www.dawgyg.com/2016/12/21/disclosing-the-primary-email-address-for-each-facebook-user/)
- [Facebook invitees email address disclosure](http://fogmarks.com/2016/04/03/facebook-invitees-email-addresss-disclosure/)
- [Facebook Skype-to-Email leak (3000$ bounty)](https://web.archive.org/web/20170809142917/http://blog.internot.info/2014/05/facebook-skype-to-email-leak-3000-bounty.html)
- [View commerce settings and email for any page shop](https://philippeharewood.com/view-commerce-settings-and-email-for-any-page-shop/)
- [View the assigned roles and emails of an Instagram account](https://philippeharewood.com/view-the-assigned-roles-and-emails-of-an-instagram-account/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="BIPA"></a>
### BIP address
[Facebook Bug:Getting other user's IP address from a Image on Facebook](https://asad0x01.blogspot.com/2017/05/facebook-buggetting-other-users-ip.html)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="SYMA"></a>
### Symlink Attack
- [Reading Local Files from Facebook's Internal Network](https://josipfranjkovic.blogspot.com/2014/12/reading-local-files-from-facebooks.html)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="ASFT"></a>
### Accellion’s Secure File Transfer
[How I hacked Facebook and found someone's backdoor script](http://blog.orange.tw/2016/04/bug-bounty-how-i-hacked-facebook-and-found-someones-backdoor-script.html)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="XXE"></a>
### XXE
- [Facebook Remote Code Execution](https://www.ubercomp.com/posts/2014-01-16_facebook_remote_code_execution)
- [Hacked Facebook Word Document](https://web.archive.org/web/20150316053924/http://attack-secure.com/hacked-facebook-word-document/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="LFI"></a>
### LFI
- [Facebook Web Security Bug Bounty: Directory Traversal Vulnerability / RCE In Parse.com](http://www.websecuritylog.com/2014/10/facebook--bug-bounty.html?spref=tw)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="SQLI"></a>
### SQLI<br>
- [Pupping a shell on the oculus dev portal ](https://bitquark.co.uk/blog/2014/08/31/popping_a_shell_on_the_oculus_developer_portal)
- [Step by step exploiting sql on fb ](https://josipfranjkovic.blogspot.com/2014/09/step-by-step-exploiting-sql-injection.html)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="JK"></a>
### Jenkins
- [How i hacked facebook jenkins vuln ](https://blog.dewhurstsecurity.com/2014/12/09/how-i-hacked-facebook.html)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="API"></a>
### API
- [Facebook Bug:Commenting on non-friends](https://asad0x01.blogspot.com/2017/05/facebook-bugcommentingon-non-friends.html)
- [Hacking Facebook's Legacy API Part 1: Making Calls on Behalf of Any User](https://stephensclafani.com/2014/07/08/hacking-facebooks-legacy-api-part-1-making-calls-on-behalf-of-any--user/)
- [How I Exposed Your Primary Facebook Photos](https://roy-castillo.blogspot.com/2013/07/how-i-exposed-your-primary-facebook.html)
- [Facebook Insights API Bug](https://philippeharewood.com/facebook-insights-api-bug/)
- [Facebook v2.0 API Bug: Inconsistencies with App-Scoped IDs](https://philippeharewood.com/facebook-v2-0-api-bug-inconsistencies-with-app-scoped-ids/)
- [Bounty leftover part 1](http://blog.intothesymmetry.com/2014/09/bounty-leftover-part-1.html)
- [Paging Cursors Leaking Data in Graph API](https://philippeharewood.com/paging-cursors-leaking-data-in-graph-api/)
- [Tagged Places Shouldn't Show Paging Params If No user_tagged_places Granted](https://philippeharewood.com/tagged-places-shouldnt-show-paging-params-if-no-user_tagged_places-granted/)
- [Bypassing appsecret_proof Verification](https://philippeharewood.com/bypassing-appsecret_proof-verification/)
- [Change the Description of a Video Without publish_actions Permission](https://philippeharewood.com/change-the-description-of-a-video-without-publish_actions-permission/)
- [Icon Field in Posts Gets access_token Appended](https://philippeharewood.com/icon-field-in-posts-gets-access_token-appended/)
- [Reply to a Message Without read_page_mailboxes Permission](https://philippeharewood.com/reply-to-a-message-without-read_page_mailboxes-permission/)
- [Bypassing Posting to Friends Timelines API Restriction](https://philippeharewood.com/bypassing-posting-to-friends-timelines-api-restriction/)
- [How I Exposed Your Private Photos](https://zerohacks.com/bug-bounty-hacks/how-i-exposed-your-private-photos/)
- [Facebook Page Profile Picture Update Requires Neither publish_pages Nor publish_actions](https://philippeharewood.com/facebook-page-profile-picture-update-requires-neither-publish_pages-nor-publish_actions/)
- [The Facebook publish_pages Permission is Missing in MeLinks](https://philippeharewood.com/the-facebook-publish_pages-permission-is-missing-in-melinks/)
- [Upload Videos Thumbnails with Just public_profile Permission](https://philippeharewood.com/upload-videos-thumbnails-with-just-public_profile-permission/)
- [Icon Field in Posts Gets access_token Appended](https://philippeharewood.com/icon-field-in-posts-gets-access_token-appended/)
- [Modifying Privacy Settings on Facebook Through Graph API](https://web.archive.org/web/20160202160841/http://www.secinfinity.net/modifying-privacy-settings-on-facebook-through-graph-api/)
- [Show Friends Sharing Precise Locations as a Third-Party Application](https://philippeharewood.com/show-friends-sharing-precise-locations-as-a-third-party-application/)
- [Change Tag Suggestions for Any Facebook User](https://philippeharewood.com/change-tag-suggestions-for-any-facebook-user/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


<a name="GQ"></a>
### GraphQL
- [GraphQL IDOR in Facebook streamer dashboard](https://kailashbohara.com.np/blog/2020/11/18/GraphQL-IDOR-in-Facebook-streamer-dashboard/)
- [View the GraphQL stored queries for any application](https://philippeharewood.com/view-the-graphql-stored-queries-for-any-application/)
- [Path disclosure in Facebook GraphQL API](https://philippeharewood.com/path-disclosure-in-facebook-graphql-api/)
- [Facebook employees commission splits counts are shown](https://philippeharewood.com/facebook-employees-commission-splits-counts-are-shown/)
- [Abusing Facebook Graph Search](https://philippeharewood.com/abusing-facebook-graph-search/)
- [My 3rd Facebook Bounty Hat Trick - Chennai TCS-er Name Listed in Facebook Hall of Fame](https://medium.com/@rajsek/my-3rd-facebook-bounty-hat-trick-chennai-tcs-er-name-listed-in-facebook-hall-of-fame-47f57f2a4f71)
- [Facebook's Bug - Unauthorized Access to Credit Card Details Limited of Any User](https://pranavhivarekar.in/2017/02/11/facebooks-bug-unauthorized-access-to-credit-card-details-limited-of-any-user/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


<a name="FQL"></a>
### FQL
- [A Bug Worth $4200](https://filippo.io/a-bug-worth-4200$/)
- [Facebook Keyword_Insights Bug](https://philippeharewood.com/facebook-keyword_insights-bug/)
- [Getting the Username in FQL in 2.0 Applications](https://philippeharewood.com/getting-the-username-in-fql-in-2-0-applications/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="LN"></a>
### Login Nonces
- [Stealing messengerlogin nonces](https://stephensclafani.com/2017/03/21/stealing-messenger-com-login-nonces/)
![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="OAUTH"></a>
### OAuth (AKA Stealing Access Tokens)
- [Facebook OAuth Bypass](https://medium.com/@yaala/facebook-oauth-bypass-446a073e687d)
- [Hacking Facebook CSRF Device Login Flow](https://www.josipfranjkovic.com/blog/hacking-facebook-csrf-device-login-flow)
- [Hacking Facebook's Legacy API Part 2: Stealing User Sessions](https://stephensclafani.com/2014/07/29/hacking-facebooks-legacy-api-part-2-stealing-user-sessions/)
- [A Story of $9,500 Bug in Facebook OAuth 2.0](https://isciurus.blogspot.ru/2013/04/a-story-of-9500-bug-in-facebook-oauth-20.html)
- [Pwning Facebook Authorization through Chrome extension](https://isciurus.blogspot.ca/2012/09/pwning-facebook-authorization-through.html)
- [Hacking Facebook with OAuth2 and Chrome Extension](http://homakov.blogspot.ca/2013/02/hacking-facebook-with-oauth2-and-chrome.html)
- [Stealing Facebook Access Tokens using the Facebook OAuth Dialog](https://blog.bentkowski.info/2014/09/in-this-post-ill-explain-to-you.html)
- [Facebook MailChimp Application OAuth 2.0 Misconfiguration](https://prakharprasad.com/facebook-mailchimp-application-oauth-2-0-misconfiguration/)
- [Facebook's Parse OAuth Bug](https://medu554.blogspot.com/2013/08/facebooks-parse-oauth-bug.html)
- [Facebook Authentication Bug Bounty](http://breaksec.com/?p=5753)
- [How I hacked Facebook OAuth to get Full Permission Access Tokens](http://nirgoldshlager.blogspot.com/2013/02/how-i-hacked-facebook-oauth-to-get-full.html)
- [OAuth 2: How I Have Hacked Facebook Again](http://blog.intothesymmetry.com/2014/04/oauth-2-how-i-have-hacked-facebook.html)
- [Stealing Facebook Access Tokens with a Double Submit](https://whitton.io/articles/stealing-facebook-access-tokens-with-a-double-submit/)
- [Facebook JS Security Issue](http://prosecco.gforge.inria.fr/CVE/Facebook_JS_2012.html)
- [Swiping Facebook Official Access Tokens](https://philippeharewood.com/swiping-facebook-official-access-tokens/)
- [OAuth Token Validation Bug in Facebook](http://whitehatstories.blogspot.in/2017/05/oauth-token-validation-bug-in-facebook.html)
- [Bypass OAuth Nonce and Steal Oculus Response Code](https://medium.com/@lokeshdlk77/bypass-oauth-nonce-and-steal-oculus-response-code-faa9cc8d0d37)
- [Stealing Facebook MailChimp Application OAuth 2.0 Access Token](https://medium.com/@lokeshdlk77/stealing-facebook-mailchimp-application-oauth-2-0-access-token-3af51f89f5b0)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="IG"></a>
### Instagram
- [One-click reflected XSS in instagram due to unfiltered URI schemes leads to account takeover](https://labs.detectify.com/2021/07/15/one-click-reflected-xss-in-www-instagram-com-due-to-unfiltered-uri-schemes-leads-to-account-takeover/)
- [How I found a critical bug in Instagram and got $49,500 bounty from Facebook](https://infosecwriteups.com/how-i-found-a-critical-bug-in-instagram-and-got-49500-bounty-from-facebook-626ff2c6a853)
- [React debug.keystore key was trusted by Instagram’s APK file, leading to Account takeover](https://www.vulnano.com/2022/07/react-debugkeystore-key-was-trusted-by.html)
- [Instagram photo was present in data backup nearly after two years being deleted](https://medium.com/@the_null_kid/instagram-photo-was-present-in-data-backup-nearly-after-two-years-being-deleted-f0e4d6e108)
- [Email confirmation bypass at Instagram](https://medium.com/@avinash_/email-confirmation-bypass-at-instagram-cc968f9a126)
- [Instagram-haavoittuvuus antaa kuvat ilman lupaa](http://www.iltalehti.fi/digi/2016050221506011_du.shtml)
- [Breaking video calling feature in Instagram app](https://www.facebook.com/notes/kinghackx/breaking-video-calling-feature-in-instagram-app/522128951955609/)
- [Hacked your Instagram account? Here’s how to get it back](https://viaforensics.com/mobile-security/hacked-your-instagram-account.html)
- [How I found my way into Instagram’s servers](https://josipfranjkovic.blogspot.com/2013/07/how-i-found-my-way-into-instagrams.html)
- [Instagram's One-Click Privacy Switch](https://whitton.io/articles/instagrams-one-click-privacy-switch/)
- [Facebook BugBounty - Facebook, Instagram - Get someone's phone number with just a Facebook account](https://samanfatahpour.blogspot.com/2014/10/facebook-bugbounty-facebook-instagram.html)
- [The Tales of a Bug Bounty Hunter: 10 interesting vulnerabilities in Instagram](https://www.arneswinnen.net/2016/02/the-tales-of-a-bug-bounty-hunter-10-interesting-vulnerabilities-in-instagram/)
- [How I could compromise 4 locked Instagram accounts](https://www.arneswinnen.net/2016/03/how-i-could-compromise-4-locked-instagram-accounts/)
- [Instagram Unauthorized Comment Deletion](https://mohankallepalli.blogspot.com/2016/04/instagram-unauthorized-comment-deletion.html)
- [InstaBrute: Two Ways to Brute-force Instagram Account Credentials](https://www.arneswinnen.net/2016/05/instabrute-two-ways-to-brute-force-instagram-account-credentials/)
- [Instagram Email Verification Issue](http://bugdisclose.blogspot.in/2017/04/instagram-email-verification-issue.html)
- [Find Instagram contacts for any user on Facebook](https://philippeharewood.com/find-instagram-contacts-for-any-user-on-facebook/)
- [Taking over Instagram accounts](https://stefanovettorazzi.com/taking_over_instagram_accounts/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="SIGNAL"></a>
### Signal
- [Getting facebook signal app access token](https://philippeharewood.com/getting-facebook-signal-app-access-token/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="SLING"></a>
### Slingshot
- [Add any facebook user non friend to slingshot without knowing the username](https://philippeharewood.com/add-any-facebook-user-non-friend-to-slingshot-without-knowing-the-username/)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="MA"></a>
### Messenger Android
- [Indirect thread deletion vulnerability in Messenger Android](https://servicenger.com/mobile/facebook-messenger-for-android-indirect-thread-deletion "Indirect thread deletion vulnerability in Messenger Android")
- [Session misconfiguration vulnerability in Messenger Android](https://www.aryansinha.com/2017/11/session-misconfiguration-in-messenger.html "Session misconfiguration vulnerability in Messenger Android")
- [Facebook Messenger Server Random Memory Vulnerability](https://www.vulnano.com/2019/03/facebook-messenger-server-random-memory.html "Facebook Messenger Server Random Memory Vulnerability")

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="MOMENTS"></a>
### Moments
- [Rewriting a photo not owned by the session user in Moments app](https://philippeharewood.com/rewriting-a-photo-not-owned-by-the-session-user-in-moments-app/ "Rewriting a photo not owned by the session user in Moments app")
- [Deleting any Moments app photo or folder not owned by the session user](https://philippeharewood.com/delete-any-moments-app-photo-or-folder-not-owned-by-the-session-user/ "Deleting any Moments app photo or folder not owned by the session user")

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="MOVES"></a>
### Moves
- [OAuth Cross-Site Scripting vulnerability in Facebook's Moves app](https://web.archive.org/web/20171112164937/http://www.paulosyibelo.com:80/2015/12/facebooks-moves-oauth-xss.html "OAuth Cross-Site Scripting vulnerability in Facebook's Moves app")

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="WTP"></a>
### Whatsapp
- [Bypassing biometric authentication in WhatsApp using VoIP](https://infosecwriteups.com/whatsapp-bug-bounty-bypassing-biometric-authentication-using-voip-87548ef7a0ba "Bypassing biometric authentication in WhatsApp using VoIP")
- [WhatsApp Hacked - Remote Code Execution Vulnerability in WhatsApp Web](https://immukul.blogspot.in/2016/11/whatsapp-hacked.html "Remote Code Execution Vulnerability in WhatsApp Web")
- [G Suite vulnerability in WhatsApp](http://blog.pentestnepal.tech/post/156707088037/i-got-emails-g-suite-vulnerability "G Suite vulnerability in WhatsApp")
- [DoS vulnerability in WhatsApp for iOS and Android](https://medium.com/bugbountywriteup/whatsapp-dos-vulnerability-in-ios-android-d896f76d3253 "DoS vulnerability in WhatsApp for iOS and Android")
- [Reading WhatsApp contacts list without unlocking the device](https://medium.com/bugbountywriteup/facebook-bug-bounty-reading-whatsapp-contacts-list-without-unlocking-the-device-a40e9c660a42 "Reading WhatsApp contacts list without unlocking the device")

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="WOP"></a>
### Workplace
- [Privilege escalation vulnerability in Workplace](https://philippeharewood.com/a-walk-in-the-workplace/ "Privilege escalation vulnerability in Workplace")
- [Facebook Workplace Admin account takeover vulnerability](https://www.youtube.com/watch?v=H)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)



<a name="WTA"></a>
### Whitehat Test Accounts
- [Whitehat Test Accounts Can Act as Hidden Admin with Business Manager Ad Accounts](https://medium.com/@rohitcoder/whitehat-test-accounts-can-act-as-hidden-admin-with-business-manager-ad-accounts-ce75ead5ffff)
- [Ability to find Facebook employee’s test accounts which lead to the disclosure of internal information](https://ysamm.com/?p=638)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


<a name="FE"></a>
### Facebook Event
- [Irremovable Guest in Facebook Event (Facebook Bug Bounty)](https://infosecwriteups.com/irremovable-guest-in-facebook-event-facebook-bug-bounty-e10e03c98cd5)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


<a name="FBP"></a>
### Facebook Business Page
- [Hacking Facebook Invoice: How I Could've Bought Anything for Free from Facebook Business Pages](https://infosecwriteups.com/hacking-facebook-invoice-how-i-couldve-bought-anything-for-free-from-facebook-business-pages-42bcfaa73ec4)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


<a name="DOS"></a>
### DOS Attack
- [Remotely Permanent Crash Any Instagram](https://www.yesnaveen.com/2022/05/remotely-permanent-crash-any-instagram.html?m=1)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


<a name="MBL"></a>
### Facebook/Instagram Mobile App 
- [Taking over the Call to Action button on Mobile Devices](https://www.ash-king.co.uk/blog/abusing-Facebooks-call-to-action-to-launch-internal-deeplinks)
- [Facebook android webview vulnerability : Execute arbitrary javascript (xss) and load arbitrary website ](https://servicenger.com/mobile/facebook-android-webview-vulnerability/)
- [Instagram vulnerability : Turn off all type of message requests using deeplink (Android)](https://servicenger.com/mobile/instagram-vulnerability-turn-off-message-requests-deeplink/)
- [Facebook Messenger for android indirect thread deletion vulnerability.](https://servicenger.com/mobile/facebook-messenger-for-android-indirect-thread-deletion/)
- [Multiple bugs allowed malicious Android Applications to takeover Facebook/Workplace accounts](https://ysamm.com/?p=729)
- [Location disclosure in Facebook's Nearby Friends feature](https://otmastimi.medium.com/users-location-diclosure-in-the-nearby-friends-feature-fabd24be05cb "Location disclosure in Facebook's Nearby Friends feature")
- [Accessing private videos and photos saved on a device](https://infosecwriteups.com/how-i-could-have-accessed-all-your-private-videos-photos-saved-inside-your)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

<a name="EXTRAS"></a>
### Some of the extra res that you may want to look at !!

- [Facebook Security Page](https://www.facebook.com/security/)
- [Facebook Bug Bounty Program](https://www.facebook.com/whitehat/)
- [Facebook Bug Bounty Write-ups](https://www.facebook.com/notes/facebook-bug-bounty/)
- [Facebook Security Whitepapers](https://www.facebook.com/security/whitepapers)
- [Facebook Engineering Blog](https://engineering.fb.com/)
- [Facebook Open Source Projects](https://opensource.facebook.com/)
- [Facebook CTF Platform](https://www.facebook.com/fbctf/)
- [Facebook Security Tools and Scripts](https://github.com/facebookincubator)
- [Facebook ThreatExchange Platform](https://www.threatexchange.fb.com/)
- [Facebook Security Research Summit](https://www.facebook.com/notes/facebook-bug-bounty/facebook-security-research-summit-2018/1733463213382838/)
- [Facebook Hacking Tricks and Tips on Reddit](https://www.reddit.com/r/facebookhacking/)
- [Facebook Hacking Methods and Tools on GitHub](https://github.com/topics/facebook-hacking)
- [Facebook Pentesting on Medium](https://medium.com/tag/facebook-pentesting)

![---------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


<a name="THX"></a>
### Thanks 
Special Thanks to :-  
 - [@pwnwriter](https://github.com/pwnwriter)
 - [@phwd](https://twitter.com/phwd)
 - Jaiswalakansh 
 - [Facebook BugBounty Group](https://www.facebook.com/groups/bugbountygroup),  
 - and the [contributors](https://github.com/corrupted-brain/Facebook-Bug-Bounty-Writeups/graphs/contributors)
