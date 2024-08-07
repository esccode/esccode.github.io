---
title: EscCode validation
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

- [eBooks](#ebooks)
- [Credly profile](#credly-profile)
- [CompTIA CySA+ CS0-003](#comptia-cysa-cs0-003)
- [CompTIA Security+ SY0-601](#comptia-security-sy0-601)
- [CompTIA Data+ DA0-001](#comptia-data-da0-001)
- [Reference](#reference)

### eBooks

> Purchase My eBooks Exclusively:  
> [ Naffy.io ](https://www.naffy.io/esccode-pl/)  
> [ Amazon.com](https://www.amazon.com/author/esccode)

### Credly profile

> [Credly profile](https://www.credly.com/users/jacek-wieteska)

<!-- <div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="429b7fd2-ead7-40a6-9305-edd2378fe538" data-share-badge-host="https://www.credly.com"></div><script type="text/javascript" async src="//cdn.credly.com/assets/utilities/embed.js"></script> -->

### CompTIA CySA+ CS0-003

> Training status
> [Exam Objectives](https://www.comptia.org/certifications)  

### CompTIA Security+ SY0-601

> Passed: April 3, 2024  
> Exp date: April 3, 2027
> [Exam Objectives](https://www.comptia.org/certifications)

### CompTIA Data+ DA0-001  

> Passed:   February 11, 2024  
> Exp date: February 11, 2027
> [Exam Objectives](https://www.comptia.org/certifications)

### Reference

[CompTIA](https://www.comptia.org/certifications)
[ICS2](https://www.isc2.org/)
[Naffy](https://www.naffy.io)
[Credly](https://www.credly.com/)


# Your Content Here

<!-- Other markdown content -->

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
        consentBanner.innerHTML = `This website uses cookies to ensure you get the best experience on our website. 
            <a href="javascript:void(0);" id="acceptCookies">Got it!</a>`;
        document.body.appendChild(consentBanner);

        document.getElementById("acceptCookies").addEventListener("click", function() {
            setCookie("cookieConsent", "accepted", 365);
            document.getElementById("cookieConsent").style.display = "none";
        });

        checkCookieConsent();
    });
</script>
