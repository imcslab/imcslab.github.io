---
title: Prof. Seunghyun Park
feature_text: |
  ## Faculty member

feature_image: "/assets/uploads/bg_3.jpg"
excerpt: "A demo of Markdown and HTML includes"
aside: true
---

* * *

### Education
###### Ph.D in Cybersecurity (Feb. 2021)
* School of Cybersecurity, Korea University
* Thesis: Data-driven Anomaly Detection using Hierarchical Multi-labeled Classification for Vehicular Communications (Advisor: Prof. Jin-Young Choi)

###### M.S in Computer Science and Engineering (Feb. 2008)
* College of Informatics, Korea University
* Thesis: Formal Verification of UML State Machines (Advisor: Prof. Jin-Young Choi)

###### B.S in Computer Science and Engineering (Feb. 2006)
* Division of Computer Science and Engineering, Chung-Ang University

### Positions and responsibilities
###### Assistant Professor, Hansung University (Sep. 2021 - _current_)
* **Division of Computer Engineering**
> Web Engineering, Automotive Cybersecurity
* **Industrial-Academic Education Support Center**
> Director (Feb. 2024 - _current_)

###### Senior Manager (Dec. 2014 - Aug. 2021)
* **Hyundai Security Center, Hyundai Motor Company and Kia**
> Cybersecurity crisis management, Risk assessment and incident response, Automotive security for connectivity services, CAN IDS and SoC, Plug and Charge security infrastructures, Cybersecurity governace for vehicle IT environment and security infrastructures, Auto-ISAC council

###### Manager (May 2011 - Nov. 2014)
* **Advanced Institute of Technology, Korea Telecom Corp.**
> Research of data analytic models in social media platform for Adaptive IPTV Service, Developmrnt of intelligent knowledge service for social media and web-based IPTV platform

###### Research Engineer (Feb 2008 - Apr. 2011)
* **Mobile Communications Lab., LG Electronics Inc.**
> Mobile connectivity software, Development in Media Transfer Protocol, OMA SyncML DS, Rich Communication Suite

### Skills and interests
###### Automotive cybersecurity
* Automotive security regulation and compliance (UN Regulation No.155, ISO/SAE 21434)
* Connected vehicles security
* Threat Analysis and Risk Assessment (TARA) methods
* Plug and charge security (ISO 15118)
* In-vehicle network security (CAN IDS, gateway, ethernet firewalls)

###### Security policy and technology
* Secure software development process
* Crisis management and incident responses
* Web and mobile security inspection
* Public cloud security

### Professional activities
* **Executive committee**: The Korean Institute of Communications and Information Sciences (KICS), Korea Institute of Information Security and Cryptology (KIISC), Korean Society Automotive Engineers (KSAE): Electrical and Electronic Systems Division, Converged Software and AI Division
* **Review**: IEEE Transactions on Vehicular Technology (IEEE TVT), Vehicles, Sensors, The Transactions of the Korean Society Automotive Engineers (Trans. KSAE), The Journal of Korean Institute of Communications and Information Sciences (JKICS), KIPS Transactions on Computer and Communication systems (KTCCS)
* **Editorial Board Member**: KIISC (2025)
* **Program committee**: ICISC (International Conference on Information Security and Cryptology), IMIS (International Conference on Innovative Mobile and Internet Services in Ubiquitous Computing), Broadband and Wireless Computing, Communication and Applications (BWCCA), P2P, Parallel, Grid, Cloud and Internet Computing (3PGCIC), KSAE Conference (2024 Spring), KIISC Conference (2025 Summer)
* **Organizing committee**: International Conference on Ubiquitous and Future Networks (ICUFN 2023/2024/2025), Joint Conference on Communications and Information (JCCI 2024/2025), KICS Conference (2024 Summer, 2025 Winter)
* **Advisory**: Auto-ISAC Committee (Acamedic Member), Korea Health Information Service (KHIS), Korea Labor and Employment Service (KLES), Audit and Inspection Research Institute (BAI), Korea Expressway Corporation (KEC), Industrial Bank of Korea (IBK Bank), International Constructors Association of Korea (ICAK), ez Caretech, CIoT
* **Invited Talks**: _Secure Connected and Autonomous Vehicles: Research Trends and Challenges_ in Keynote BWCCA/3PGCIC 2023, Special lecture in Intelligent Mobility at Korea University, WISC 2023, KIISE SWCC 2023, KICS Winter Conference 2023, SCH Mobility Workshop 2023, Special lecture in Mobility Security at Dankook University 2024, Automotive and Unmanned Mobility Security Workshop 2024 at KIISC, Future Communication Technology Workshop 2024 at KICS

### Lectures
* **Information Security**: Cryptographic tools, Symmetric encryption, Web security, IT security management and compliance
* **Web Framework 1**: React.js with Modern JavaScript
* **Web Framework 2**: Node.js & Express.js
* **Web Programming**: HTML5, CSS3, JavaScript
* **Open Source Software**: Opensouce software license, source code control
* **Web Engineering Capstone Design, SW Pre-capstone Design, Capstone Design**

<!--

[A link](https://david.darn.es "A link")

Lorem ipsum dolor sit amet, consectetur adip* isicing elit, sed do eiusmod *tempor incididunt ut labore et dolore magna aliqua.

Duis aute irure dolor in [A link](https://david.darn.es "A link") reprehenderit in voluptate velit esse cillum **bold text** dolore eu fugiat nulla pariatur. Excepteur span element sint occaecat cupidatat non proident, sunt _italicised text_ in culpa qui officia deserunt mollit anim id `some code` est laborum.

* An item
* An item
* An item
* An item
* An item

1. Item one
2. Item two
3. Item three
4. Item four
5. Item five

> A simple blockquote

Some HTML...

``` html
<blockquote cite="http://www.imdb.com/title/tt0284978/quotes/qt1375101">
  <p>You planning a vacation, Mr. Sullivan?</p>
  <footer>
    <a href="http://www.imdb.com/title/tt0284978/quotes/qt1375101">Sunways Security Guard</a>
  </footer>
</blockquote>
```

...CSS...

``` css
blockquote {
  text-align: center;
  font-weight: bold;
}
blockquote footer {
  font-size: .8rem;
}
```

...and JavaScript

``` js
const blockquote = document.querySelector("blockquote")
const bolden = (keyString, string) =>
  string.replace(new RegExp(keyString, 'g'), '<strong>'+keyString+'</strong>')

blockquote.innerHTML = bolden("Mr. Sullivan", blockquote.innerHTML)
```

`Single line of code`

## HTML Includes

### Contact form

{% include site-form.html %}

``` html
{% raw %}{% include site-form.html %}{% endraw %}
```

### Demo map embed

{% include map.html id="1UT-2Z-Vg_MG_TrS5X2p8SthsJhc" title="Coffee shop map" %}

``` html
{% raw %}{% include map.html id="XXXXXX" title="Coffee shop map" %}{% endraw %}
```

### Button include

{% include button.html text="A button" link="https://david.darn.es" %}

{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}

``` html
{% raw %}{% include button.html text="A button" link="https://david.darn.es" %}
{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}{% endraw %}
```

### Icon include

{% include icon.html id="twitter" title="twitter" %} [{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes)

``` html
{% raw %}{% include icon.html id="twitter" title="twitter" %}
[{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes){% endraw %}
```

### Video include

{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}

``` html
{% raw %}{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}{% endraw %}
```


### Image includes

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}

``` html
{% raw %}{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}{% endraw %}
```
-->
