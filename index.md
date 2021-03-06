---
layout: landing
title: "Home Page"
fulltitle: "Cypherpunk collective located in Berlin"
excerpt: Cypherpunk collective located in Berlin

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
<section class="container mx-auto px-3 sm:px-8  md:w-2/3" markdown="1">
{:.text-2xl .sm:text-3xl .mb-4 .sm:mb-6 .pt-4 .sm:pt-6}
## What we do

{:.leading-normal}
Our mission is a wide adoption of Grin.
What is **[Grin](http://grin-tech.org/)**? Electronic transactions for all. Without censorship or restrictions.

{:.leading-normal .mt-8}
To achive our mission we:
* Contribute to core-development of **[Grin](https://github.com/mimblewimble/grin/)**
* Develop iOS/Android wallet for Grin - **[Ironbelly](https://ironbelly.app)**
* Develop OpenCL miner for Grin - already a part of grin-miner
* Develop Trezor/Ledger wallet integration - *Coming soon*{:.text-grey-dark}
* Run Berlin MimbleWimble/Grin [Meetup group](https://www.meetup.com/MimbleWimble-Grin-Berlin/)
* Organize events:
	{:.list-reset}
	* **Grincon0** - first ever conference in the World about MimbleWimble/Grin, happened on 9th Nov 2018 in Berlin. See videos [here](https://grincon.info/)

</section>
<div id="supporters" class="-mt-24 mb-24"></div>
<section class="container mx-auto px-3 sm:px-8 md:w-2/3" markdown="1">
{:.text-2xl .sm:text-3xl .mb-4 .sm:mb-6 .pt-4 .sm:pt-6}
## Supporters

* Pavol Rusnak
* Michalis Kargakis
</section>
<div id="donations" class="-mt-24 mb-24"></div>
<section class="container mx-auto px-3 sm:px-8 md:w-2/3" markdown="1">
{:.text-2xl .sm:text-3xl .mb-4 .sm:mb-6 .pt-4 .sm:pt-6}
## Donations

{:.text-sm .sm:text-base .leading-normal .pb-8 .list-reset}
`grin wallet send -d https://donate.cycle42.com:3415`
</section>
<div id="contact" class="-mt-24 mb-24"></div>
<section class="container mx-auto px-3 sm:px-8 md:w-2/3" markdown="1">
{:.text-2xl .sm:text-3xl .mb-4 .sm:mb-6 .pt-4 .sm:pt-6}
## Contact

{:.leading-normal  .pb-8 }
Please write us [contact@cycle42.com](mailto:contact@cycle42.com)
</section>
