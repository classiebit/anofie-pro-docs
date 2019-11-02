# Settings

Manage Anofie's global settings here.

---

![Admin Panel Settings](https://anofie-pro-docs.classiebit.com/images/admin-settings.jpg "Admin Panel Settings")

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

Change the branding content of your site.


<a name="SEO"></a>
## SEO

Set the meta tags to improve site ranking on search engines e.g Google, these tags will be applied on all pages of the site.


<a name="Social"></a>
## Social

Set your social media pages URL.



<a name="Wildcard-subdomain"></a>
## Wildcard subdomain

Anofie Pro comes with compatibility for both Wildcard enabled and non-enabled websites. So please be careful before enabling these settings.

<br>
- Wildcard Domain

    If checked, the user's profile URL e.g `http://johndoe.anofie.com` will be activated. So before enabling this setting, make sure the Wildcard subdomain is activated on your hosting.

    > {info} You can `search on Google` about `how to enable wildcard subdomain on CPANEL or VPS`


- Wildcard SSL

    If checked, the user's profile URL will become `HTTPS-enabled` e.g `https://johndoe.anofie.com`. So before enabling this setting, make sure you've installed `Wildcard SSL` on your domain.

    > {warning} You can `search on Google` about `how to install wildcard SSL on CPANEL or VPS`


> {danger} MOST IMPORTANT: Subdomain URL `johndoe.anofie.com` will only work if you've installed Anofie as a `Parent site` on the domain. If installed on `subdomain` or as a `Child site`, the above setting will not work. 

---

![Wildcard-subdomain](https://anofie-pro-docs.classiebit.com/images/wildcard-subdomain-1.jpg "Wildcard-subdomain")

---


<a name="Mail"></a>
## Mail

Set your E-mail configurations. Please make sure you add the correct SMTP details provided from your hosting provider, or else email sending won't work.

<br>
**You can choose between two Email libraries, if in case one not work, you can choose another.**

- Codeigniter Email Library (default)
- PHPMailer Email Library (popular) - [https://github.com/PHPMailer/PHPMailer](https://github.com/PHPMailer/PHPMailer)


<a name="Apps"></a>
## Apps

Set third-party Apps credentials.

<br>
- Google - [https://console.developers.google.com/](https://console.developers.google.com/)
- Google Analytics - [https://analytics.google.com/analytics/web/](https://analytics.google.com/analytics/web/)
- Facebook - [https://developers.facebook.com/](https://developers.facebook.com/)
- Twitter - [https://developer.twitter.com/](https://developer.twitter.com/)
- Instagram - [https://www.instagram.com/developer](https://www.instagram.com/developer)


<a name="Regional"></a>
## Regional

Anofie is a multi-lingual and multi-time zone. No matter where you're from, you can set your native Timezone and Language which will be applied as default.


<a name="AdSense"></a>
## Google AdSense

Google AdSense is integrated in Anofie Pro, you need to enter your `Google Ad Verify Code` first, then when your website gets verified for running ads, you can then enter `Google Ad Code` and the ads will show up on the pages on the front-end, except pages - `about, contact, terms, privacy, authentication and admin panel pages`. 


> {warning} Please read the guidelines provided below each setting, and follow exactly mentioned, or else it may break down your site.