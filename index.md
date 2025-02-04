---
title:
categories:
- comptia
feature_text: |
  ## @esccode
  "If you tell the truth, you don't have to remember anything." - Mark Twain

excerpt: |
  # 
#feature_image: "https://picsum.photos/2560/600?image=733"
feature_image: "https://picsum.photos/1300/400?image=989"
image: "https://picsum.photos/2560/600?image=733"
indexing: true
sitemap: true
aside: true
---

- [eBooks Series](#ebooks-series)
- [Credly Profile](#credly-profile)
- [Training Status](#training-status)

#### eBooks Series

[![All Series](image-19.png)](https://www.amazon.com/author/esccode)
<!-- [![Digital Forensic Case Stories](image-16.png)](https://www.amazon.com/dp/B0DKG6W579)
[![Interview Mastery Series](image-14.png)](https://www.amazon.com/dp/B0DM6P4VYX)
[![Data Mastery Series](image-17.png)](https://www.amazon.com/dp/B0DM6CSP2J)
[![Cybersecurity Mastery Series](image-18.png)](https://www.amazon.com/dp/B0DM6K1JMP) -->
<!-- [![Naffy.io "Produkty cyfrowe"](image-8.png)](https://www.naffy.io/esccode-pl) -->
#### Credly Profile

> Credly profile [Badge Portfolio](https://www.credly.com/users/jacek-wieteska)

<!-- <div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="429b7fd2-ead7-40a6-9305-edd2378fe538" data-share-badge-host="https://www.credly.com"></div><script type="text/javascript" async src="//cdn.credly.com/assets/utilities/embed.js"></script> -->

#### Training Status

> UNIC Institute for the future [Free MOOC on Mastering Web3](https://www.unic.ac.cy/iff/education-and-training/free-courses-moocs/mastering-web3-blockchain-cryptocurrencies-nfts-and-the-metaverse/)  
> CompTIA CySA+ CS0-003 [Exam Objectives ](https://www.comptia.org/certifications)  
> ISC2 [ISC2 Certified in Cybersecurity Entry-Level Certification ](https://www.isc2.org/certifications/cc)  

<!-- #### Naffy.io, Amazon.pl, Amazon.com, and EscCode.pl

![QR Codes](image-12.png) -->

---
<!-- 
#### Reference

[CompTIA](https://www.comptia.org/certifications),
[ICS2](https://www.isc2.org/),
[Naffy](https://www.naffy.io),
[Credly](https://www.credly.com/),
[UNIC](https://courses.unic.ac.cy/),
[Amazon](https://www.amazon.com/author/esccode) -->

<!-- markdown content for cookie -->

<script>
    // CSS for the cookies consent banner
    const style = document.createElement('style');
    style.innerHTML = `
        #cookieConsent {
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 15px;
            z-index: 1000;
            display: none;
        }
        #cookieConsent a {
            color: #4CAF50;
        }
    `;
    document.head.appendChild(style);

    // Function to set a cookie
    function setCookie(name, value, days) {
        let expires = "";
        if (days) {
            let date = new Date();
            date.setTime(date.getTime() + (days * 24 * 60 * 60 * 1000));
            expires = "; expires=" + date.toUTCString();
        }
        document.cookie = name + "=" + (value || "") + expires + "; path=/";
    }

    // Function to get a cookie by name
    function getCookie(name) {
        let nameEQ = name + "=";
        let ca = document.cookie.split(';');
        for (let i = 0; i < ca.length; i++) {
            let c = ca[i];
            while (c.charAt(0) == ' ') c = c.substring(1, c.length);
            if (c.indexOf(nameEQ) == 0) return c.substring(nameEQ.length, c.length);
        }
        return null;
    }

    // Function to check if cookies consent has already been given
    function checkCookieConsent() {
        let consent = getCookie("cookieConsent");
        if (!consent) {
            document.getElementById("cookieConsent").style.display = "block";
        }
    }

    // Event listener for the "Got it!" link
    document.addEventListener('DOMContentLoaded', function() {
        const consentBanner = document.createElement('div');
        consentBanner.id = 'cookieConsent';
        consentBanner.innerHTML = `This website uses /cookies/ to ensure you get the best experience on our website. 
            <a href="javascript:void(0);" id="acceptCookies">Got it!</a>`;
        document.body.appendChild(consentBanner);

        document.getElementById("acceptCookies").addEventListener("click", function() {
            setCookie("cookieConsent", "accepted", 365);
            document.getElementById("cookieConsent").style.display = "none";
        });

        checkCookieConsent();
    });
</script>
