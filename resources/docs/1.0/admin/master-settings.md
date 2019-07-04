# Master Settings

Here you can manage Anofie's global settings.

> {warning} Please read the guidelines provided below each setting, and follow exactly mentioned, or else it may break down the your site.

---

- [General](#General)
- [SEO](#SEO)
- [Social](#Social)
- [Wildcard subdomain](#Wildcard-subdomain)
- [Mail](#Mail)
- [Apps](#Apps)
- [Regional](#Regional)
- [AdSense](#AdSense)

<a name="General"></a>
## General

Here you can change the branding content of your site.


<a name="SEO"></a>
## SEO

Here you can change the meta tags, these tags will be applied on all pages of the site.


<a name="Social"></a>
## Social

Here you can set your social media pages URL.


<a name="Wildcard-subdomain"></a>
## Wildcard subdomain

We have added compatibility for both Wildcard enabled and non-enabled hostings. So please be carefull before enabling these settings.

<br>
- Wildcard Domain

    If checked, the user's profile url e.g `http://johndoe.anofie.com` will be activated. So before enabling this setting, make sure the Wildcard subdomain is activated on your hosting.

    > {info} You can `search on Google` about `how to enable wildcard subdomain` on your hosting. 


- Wildcard SSL

    If checked, the user's profile url will become `HTTPS enabled` e.g `https://johndoe.anofie.com`. So before enabling this setting, make sure you've installed `Wildcard SSL` on your domain.

    > {warning} You can `search on Google` about `how to install wildcard SSL` on your hosting. 


> {danger} MOST IMPORTANT: Subdomain URL `johndoe.anofie.com` will only work, if you've installed Anofie as a `Parent site` on the domain. If installed on `subdomain` or as a `Child site`, the above setting will not work. 


<a name="Mail"></a>
## Mail

Here you can set your E-mail configurations. Please make sure you've added correct SMTP details provided from your hosting provider, or else email sending won't work.

<br>
**You can choose between two Email libraries, if in case one not work, you can choose another.**

- Codeigniter Email Library (default)
- PHPMailer Email Library (popular) - [https://github.com/PHPMailer/PHPMailer](https://github.com/PHPMailer/PHPMailer)


<a name="Apps"></a>
## Apps

Here you can set third-party library's app credentials. We've used these libraries for Login purposes.

<br>
- Google - [https://console.developers.google.com/](https://console.developers.google.com/)
- Google Analytics - [https://analytics.google.com/analytics/web/](https://analytics.google.com/analytics/web/)
- Facebook - [https://developers.facebook.com/](https://developers.facebook.com/)
- Twitter - [https://developer.twitter.com/](https://developer.twitter.com/)
- Instagram - [https://www.instagram.com/developer](https://www.instagram.com/developer)


<a name="Regional"></a>
## Regional

Anofie is multi-lingual and multi-timezone website. So no matter where you're from in the world, you can set your specific Timezone and Language

<br>
- **Language:**  You can literally add any language you want, traditional to urban or RTL, Anofie supports every langauge available in the world.


<a name="AdSense"></a>
## Google AdSense

Google AdSense is integrated in Anofie, you need to enter your `Google Ad Verify Code` first, then when your website gets verified for running ads, you can then enter `Google Ad Code` and the ads will shows up on the pages on the front-end, except pages - `about , contact, terms, privacy, authentication pages`. 

