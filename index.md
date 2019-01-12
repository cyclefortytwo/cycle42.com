---
layout: default
title: "Home Page"
fulltitle: "Cypherpunk cooperative located in Berlin"
excerpt: Cypherpunk cooperative located in Berlin

---
<!-- fulltitle: This overrides the default page title, which is "{{page.tite}} | {{site.title}}" -->
<!-- excerpt: If this isn't set, it'll pull your {{site.tagline}} for meta description-->


<section class="container mx-auto">
  <div class="flex flex-col sm:flex-row h-screen justify-center">
    <div class="w-full sm:w-1/2 flex justify-center sm:items-center sm:h-full">
      <img id="hero-logo" class="w-48 h-48 mr-0 block sm:mr-4" src="img/Cycle42.svg" />
    </div>
    <div class="w-5/6 sm:w-1/3 h-48 mx-auto flex mt-8 sm:mt-0 sm:justify-center flex-col text-center sm:text-left sm:pl-4 sm:items-center sm:h-full">
      <p class="text-3xl mt-2 leading-normal">{{page.excerpt}}</p>
    </div>
    <a id="landing-chevron" class="fas fa-chevron-down block absolute pin-b pin-x w-8 text-grey-light text-align text-4xl mx-auto mb-4 no-underline" href="#whatwedo"></a>
  </div>
</section>
<div id="whatwedo" class="-mt-24 mb-24"></div>
<section class="container mx-auto px-8 sm:px-8 md:w-2/3" markdown="1">
{:.text-4xl .text-center .mb-6 .pt-6}
## What we do

{:.text-xl .leading-normal}
Our mission is wide adoption of Grin.
What is **[Grin](http://grin-tech.org/)**? Electronic transactions for all. Without censorship or restrictions.

{:.text-xl .leading-normal .mt-8}
To achive our mission we:
* Contribute to core-development of **[Grin](https://github.com/mimblewimble/grin/)**
* Develop iOS/Android wallet for Grin - **[Ironbelly Wallet](/ironbelly)**
* Develop OpenCL miner for Grin - *Coming soon*{:.text-grey-dark}
* Develop Trezor/Ledger wallet integration - *Coming soon*{:.text-grey-dark}
* Run Berlin MimbleWimble/Grin [Meetup group](https://www.meetup.com/MimbleWimble-Grin-Berlin/)
* Organize events:
	* **Grincon0** - first ever conference in the World about MimbleWimble/Grin, happened 9th Nov 2018 in Berlin. See videos [here](https://grincon.info/)

</section>
<div id="contact" class="-mt-24 mb-24"></div>
<section class="container mx-auto px-8 sm:px-8 md:w-2/3" markdown="1">
{:.text-4xl .text-center .mb-6 .pt-6}
## Contact

{:.text-xl .leading-normal .text-center .pb-8}
Please write us [contact@cycle42.com](mailto:contact@cycle42.com)
</section>
