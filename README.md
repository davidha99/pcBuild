# pcBuild

## CPU
Important terms 

- [AVX instructions](https://hardzone.es/reportajes/que-es/instrucciones-avx-procesador/)  

###### CPU Reviews
- Not sure of buying a AMD's 3000 series or Intel's 9000s?

Here at min [4:21](https://www.youtube.com/watch?v=stM2CPF9YAY&list=WL&index=5&t=4s&ab_channel=LinusTechTips#t=4m21s) they have a good comparision between them. 
###### AMD's Ryzen architecture
- I this [r/explainmelikeimfive](https://www.reddit.com/r/explainlikeimfive/comments/6iwt75/eli5how_does_the_infinity_fabric_work/) post, redditors explain Ryzen's **Infinity Clock**(_IF_) architecture. You will learn how it is deeply connected to RAM. 
- In this [video](https://www.youtube.com/watch?v=lswfgka1HnQ&ab_channel=HardwarEsfera) you will find a hard explanation about the new 3000 series processor's architecture and how it is deeply connected with RAM, emphasizing that the new series of processors that supports more than 8 cores (3600x not included) despite than linked with a RAM with 3200Mhz of "_Real bandwith_", it will only feature 1600Mhz of _"Efective bandwith"_.


###### Why a new-gen CPU is better than an old-gen CPU?
- In this web [article](https://www.howtogeek.com/215940/why-are-newer-generations-of-processors-faster-at-the-same-clock-speed/) they explain why newer CPUs are better than older ones, even with same clocks.
> I had a 1800X OCd to 4.025Ghz and while is a very capable CPU the 3600 has a similar MT score, a little lower at stock compared to mine but I'm sure you can match it after some mild OC. Single thread wise the 3600 is much better than the 1800X. -redditor

###### CPU possible PROBLEMS
- Problems with mobo actualizations. 

[Here](https://steamcommunity.com/discussions/forum/11/1638669204740559442/) its a solution for the **problem** _"Some AMD B450 chipset motherboards may need a BIOS update prior to using Matisse CPUs. Upgrading the BIOS may require a different CPU that is supported by older BIOS revisions."_

###### CPU Overcl@cking
- If I overclock my CPU how long will it last? In this [forum](https://forums.tomshardware.com/threads/if-i-overclock-my-cpu-how-long-will-it-last.2802893/) you will find numerous advices and experiences form overclocking users, that discuss several factors that determine CPU's lives.

- Does running your CPU at 100% usage decrease its expected lifetime? In this [quora forum](https://www.quora.com/Does-running-your-CPU-at-100-usage-decrease-its-expected-lifetime) you have some explanations into why having 100% is harmfull. Althought, having 100% per se isnt the problem, the problem is that 100% generates more energy and therefore the cpu gets hotter. So, if you are able to maintain the CPU at cool temps, theorically your good to go.


## Memory 

###### Speed (bandwidht)

This is a really really controvertial topic, for simplicity I'll only put the info I've gathered.

- [Does Ram Speed REALLY matter? You might be surprised](https://www.youtube.com/watch?v=vjbNhCHwlBo&t=702s&ab_channel=JayzTwoCents) In this video, JayTwoCents makes couple of benchmarks between a default speed-based RAM at 2400MHz and an overclocked 3600MHz memory. The conclusion of the video is always "it depends" althought in some games we can get a 30+ in fps, in other ones might just be 5+ fps.


###### Timings (AKA "latency")

- What RAM timings mean? [Here](https://www.howtogeek.com/303455/how-does-ram-speed-and-timing-affect-my-pcs-performance/) you have a pretty basic article showing what latency means. But its worth saying that the article does summarize very well the things, here is some sentences that really hit my attention.

> While faster, lower latency RAM will indeed increase the technical performance of your computer, it works at such a fundamental level that it’s almost impossible for us flesh-and-blood humans to actually appreciate the difference. 

> Faster RAM will give your PC better performance in certain specific benchmarks, but in terms of actual benefit to most users, having more RAM available is almost always better than having faster RAM

To prove the preivious point, [here](https://www.youtube.com/watch?v=kUFWalEf31w&ab_channel=LinusTechTips) you have again a solid Linus video, where you can actually see if having more RAM is actually better to each specific tasking. Also, something worth noticing was one guy in the comment section of the video stating:

[![Screen-Shot-2020-10-28-at-12-11-45-AM.png](https://i.postimg.cc/kXpXQ47n/Screen-Shot-2020-10-28-at-12-11-45-AM.png)](https://postimg.cc/2VnDmCqJ)


Does RAM speed REALLY matter? This is the typical [Linus video](https://www.youtube.com/watch?v=D_Yt4vSZKVk&ab_channel=LinusTechTips) trying to solve the answere **Does RAM speed REALLY matter?** enigma. Its a pretty normal video, couple of benchmarks in gaming and in system (just the typical video you will spect from Linus) but his conclution was the thing indeed hit me. Check out what he said...

> "Going back to look at the total possible improvment an a bare-bones JEDEC ~2133MHz to the fastest one we tested, the conclusion becomes crystal clear: 4.7% for 64$ more, without any warranty that it will actually work, means that we wouldn't recomended it. Unless you are out of stuff to spent money on that will give you more meaningfull performance or usability improvements, and you have not only the time and know how to thinker with it, but also the patience to drop everything and deal with it when something isn't working. And this is specially true if you are using the latest and greatest platform with that fastest and shinniest RAM" - Linus Tech Tips



Now, in [this](https://www.reddit.com/r/intel/comments/ax96ie/best_ram_for_i79700k/) reddit post, you'll pretty much the same... Most users state that altought having **faster** RAM will make your existance better and having a RAM with more **bandwidht**, will make nothing to no difference in gameplay...

> 3000-3200mhz is the price to performance king. Anything above that is generally just a giant wall of diminishing returns. - Redditor

> You'll get small gains in FPS up to ~3466, but IMO it wouldn't be worth the cost of upgrading. 


###### Testing RAM.
How to test RAM? Ram is one of those components that is lucky dependent, it all depends from the manufacturer. So, you might wanna make sure your memory is working perfectly, so if you find an error you can probably use the warranty. In this [article](https://www.tomshardware.com/how-to/how-to-test-ram) you'll get a guide into multiple ways you can test your precious memory.   

###### Channels.

- What's better 4x8GB or 2x16GB RAM? There is a common misconception in which people thinks that having 2x16GB is better because that way wou'll take advantage of the dual channel. But, it seems to be that even if you are using 4x8GB you'll still be in dual channel. In this [reddit article](https://www.reddit.com/r/buildapc/comments/5ap2f2/whats_better_4x8gb_or_2x16gb_ram/ people) 

> They'll pretty much be the same, "2 dual channel" isn't how it works. You'll still be on dual channel with 2x16GB DIMMS or 4x8GB DIMMs in a dual channel board/CPU. - redditor.

- Sigle rank or Double rank?

The thing gets more controvertial, although people claim it'll be "pretty much the same", i've found [this](https://www.youtube.com/watch?v=twaNbiYOL9A&ab_channel=hYPERs) youtube video showing comparison benchmarks between 4x8GB and 16x2GB, **I'm not sure** if the aim of the video is to show how there is pretty much no difference between 4x8 double channel or 16x2 double channel rather than aiming to the difference between **single and double rank** maybe its something different, but I still need to dive more into it. 

> a dog running on 4 legs is faster then human running on 2 legs. unless you are Usain Bolt XD - youtube comment 





###### AMD.

###### Intel. 
- In this HardWarSfera's [video](https://www.youtube.com/watch?v=yZ2yKz0G6gA&ab_channel=HardwarEsfera) the guy features a 3200 _MHz_ RAM for the BUILD, **but** if you check **video's comment section**, you will find out that for that generation of intel(10th) RAM speed it's limited at 2933 _MHz_, and some comment recomendations for improving the build as well.

*Edit: Look down below at the subheader "BUILDS" for my "Delta" build. In which you will find a PCaPartPicker built with the actuall _improvements_ that the video's comment section feature.*

- What is Intel's Optane memory? In this [article](https://www.pcworld.com/article/3191706/optane-memory-review-why-you-may-want-intels-futuristic-cache-in-your-pc.html?page=2) I didn't just find a fair explanation, but also a pretty damn good review, with benchmarks and conclusions. If you where wondering if it's worth using it, definetly it is.

###### Post-instalation 
- Want to know if you newer-fancy RAM is actually utilizing all his power? 

In this [article](https://www.pcworld.idg.com.au/article/613203/how-set-up-new-computer-ram-memory-after-ve-installed-it-2017/) you will be guided into activating some options at the BIOS to get your memory working 100% efficient.


## GPU
###### Does ultra graphic settigs actually make a difference over the high or very high ones?
This is probably the most important thing when it comes to picking up a graphics card. Perhaps you should Be thinking "Ohh man I love how RDR2 looks in this video called ULTRA PC RTX 2080Ti ULTRA MAXXX RDR2 ULTRA HIGHHHHHHHHHH settings" Yeah, perhaps it looks really reallly good, but the good news is that also the very high configuration gives it stuning looks. And what is even better, an smart configuration of ultra, high, mid will give it a better boost in performance. A lot of the ultra settings the game features are just **unotisable** againts the high ones. If youre feeling skeptik about this, here I have at least 5 different sources of information that proves what I'm saying

- This [article](https://www.gpucheck.com/article/ultra-vs-high-quality-settings) states the ultra vs high, concluding that going for the ultra is always ULTRA expensive and you'll probably just get a 5-10% overall improvement.

- This [youtube video](https://www.youtube.com/watch?v=A8VrFUi79yo&ab_channel=DigitalFoundry) looks kind of an amateur view because he doesn't show super pro benchmarking, tho as you move on into the video you start to notice that this guy is testing every day life situations, like how ligh affects in ultra or mid, that kind of stuff that to the naked eye is really perceptible.

- This is a more opinion-based [video](https://www.youtube.com/watch?v=d5ZsaavKNR8&ab_channel=2kliksphilip), tho the guy has a point, even consoles can play games at pretty quialities, so whatever you get beyond that is just BETTER. He also states that to really play 4k on stable 60fps, you'll litterary have to buy the BEST, so in most cases its just "Meh"

- In this [reddit post](https://www.reddit.com/r/PCRedDead/comments/dwbzce/4k_mediumhigh_or_1440p_ultra/) people state their opinion on how even in titles like RDR2 a good settings configuration might help into getting a boost in frames. So definetly not worth having everything in ultra and having 20 fps...
> I am thinking companies should start naming the ultra setting as the "sucker setting" as while some settings on ultra in games do show a clear visible difference, most do not and you need to compare in screenshots. - redditor.

- Also, [here](https://www.reddit.com/r/nvidia/comments/7nmdts/is_ultra_really_worth_it_compared_to_high/) you have an nvidia post in reddit. People as well debate how different configurations are meant to serve an specific style of gamplay.
> Depends on the game. Some games consider 8x AF as "Ultra" and 16x as some kind of custom Ultraer.    In the past ultra was meant to be a bleeding edge/future proofing option. Most people weren't expected to be able to run anew game at ultra. As hardware advanced what was considered ultra became high, making the game age better. These days ultra is an arbitrary mix of any kind of shit that isn't always tested very well. - redditor.





## Motherboard

Before anything else, now you should wrap your head down to this, beacause we will start using hardship nomenclature. I suggest giving it a look to this article [PcMag: 20 terms to know about a mobo](https://www.pcmag.com/news/buying-a-motherboard-20-terms-you-need-to-know). That will surely help a lot understand acronyms and nomencalture.

###### The anatomy of a motherboard.
Be carefull here because is hard to understand, tho, here you have a pretty good [article](https://www.gamersnexus.net/guides/1229-anatomy-of-a-motherboard-what-is-a-vrm-mosfet?showall=1) that explains every single part of a motherboard, covering how the VRM desing is the most important, as well as his components (MOSFETs, capacitors, Chokes). If you are a little bit more graphic-based guy, this [video](https://www.youtube.com/watch?v=TfPBRSGQMDE&app=desktop&ab_channel=GamersNexus) its actually an extention to the article (written by GamersNexus). I would recomend first reading the article so you can fully understand the video. 

###### Naming a motherboard 
[Here](https://www.youtube.com/watch?v=lCpH-ryKKhI&ab_channel=Techquickie) Linus gives a rapid break down to both Intel and AMD motherboard naming. It all comes down to the tier level of the mobo. Isn't that confusing. Tho, is kind of basic... In the video isn't explained how the last digits affect the mobo, for example what is the difeerence between a, Z390 and a Z370 or perhaps why some of them are named Z399? Huh???? Well, I found in this [article](https://www.pcworld.com/article/3268063/intel-motherboard-z370-vs-h370-vs-b360-vs-h310-8th-gen-cpu.html) a really good comparison between them, don't worry its only about the amount of features it has, such as WiFi, more USB and perhaps faster PCIe bandwith. It's worth giving it a look, but for a dayli basic mobo pick up, you probably wuould be more than cool with the Linu's one. 

###### BIOS and UEFI 
We know that the BIOS and UEFI are basically the only two firmware interfaces for computers that work as an interpreters between the operating system and the computer firmware. But, which one is better or what are the differences? In this [article](https://www.maketecheasier.com/differences-between-uefi-and-bios/) you can look the basics of both and which one should you use.

###### Temperature  
- What is a heathsink and how does it help in a mobo?
In this [video](https://www.youtube.com/watch?v=tX2VKEesUiE&ab_channel=Techquickie) Linus explains as fast as possible what a heatsink is, where they are located (cpu, near the power supply, gpu, etc) as well as the most common ones, such as heat spreaders, passive pinned/finned, active and vaporchamber/heat pipe being the most expensive and effective type of heatsink.

- What is the thermal paste and how good or bad ones affect the temperature?
In this [PcMag](https://www.pcgamer.com/does-the-kind-of-thermal-paste-you-use-matter/#:~:text=The%20big%20question%20is%2C%20does,Short%20answer%2C%20yes.&text=Yet%20they%20don't%20transfer,computer%20in%20a%20hot%20environment.) article you'll find everything related to thermal pastes, as well stating that in short a short answere they indeed have an impact on your PC temperature, specially if you are an avid overclocker.

###### RAID   
- What the hell is RAID, and for what it is used for?
[This](https://forums.tomshardware.com/threads/what-is-raid-support.3105966/) forum features a really basic explanation. But honestly IMO I don't think you'll need it. 

> RAID is not a backup, it's a hardware redundancy so you can have a physical HDD failure, and still operate. -forum guy

###### Sound 
Probably when picking a motherboard you will see a dedicated slot for the audio chipset, when cheking benchmarks or reviews about audio you'll have a hard time figuring out what every single acronym stands for, here I inclded the explanantion to some of the most common ones:

- [SNR](https://www.signalbooster.com/pages/what-is-signal-to-noise-ratio-snr)


###### Intel
- In this [article](https://levvvel.com/z490-motherboard-list/) you will find anything related to the new intel's 400 series mobos. As well as any characteristic EVERY mobo has, for example the SATA, M.V, PCIe, etc...

###### AMD 






## Power Supply
###### My 5 way method into learnig everything about power supplies.

IMO trying to calculate the wattage you need for your system can be quite tedious, althought PCPartPicker gives you a good stimate into how much you'll need, you'll end up just making desitions based into what a third party recommeds, for this I'll probably say that is worth spending some time into learning abut PSU, its the most important part of your system, is the one that dictaminates wether your system will have a long lifespan or if its disposable.

1. Try fast reading this [PSU's glossary](https://www.gamersnexus.net/dictionary/6-psu?lang=en&limit=15&start=15) to kind of like dive you into what you'll probably be hearing. So the faster you understand what the terms mean the better, but for simplicity just try reading once, in the 2nd step we will reaffirm the basics so you'll be good to go.

2. Watch *carefully* [this](https://www.youtube.com/watch?v=lXku-gsdyok&ab_channel=JayzTwoCents) and [this](https://www.youtube.com/watch?v=HSeIlzVxgJ4&ab_channel=GregSalazar] youtube videos. Both talk abouth the same, and even tho its almost the same info, perhaps changing teacher will help you reaffirm what you've learned. Both videos feature the basics of what to concider into buying a PSU, they both include things like wattage, modularity, efficiency and a couple of math. So, try your best to understand what its being explaned. 

*Notes: If you have a hard time understanding what the video is saying, I wouldn't suggest going back to the glossary, I rather recommend looking for specific videos of the desired topic, lets say you dont get what the PSU efficiency stands for, so go ahead and watch some videos, I'm sure by this point you'll pretty much get everything cool.*

3. Now, by this point you'll probably be good to go to buy a PSU, but if you really really whant to get that level of understanding in which just by looking at the specs you can determine if the desired module will be a good option. You'll have to re-read the first step and really dive into learning those terms. 

4. After really understanding what the heck is going on, you will be able to fully understand this video[Wasting Money on Power Supplies: How Many Watts You Need for a PC PSU (2020)](https://www.youtube.com/watch?v=X_wtoCBahhM&ab_channel=GamersNexus), it's from our PC god: GamersNexus better known as "Tech Jesus", he really knows about what he's talking about. Check the video.. you'll be surprised how much money you can save from picking up a decent but "needs-specific" power supply.

5. You might be wondering: "Is it still more I can find about PSUs" the answere is yes. Each power supply and I mean each specific model of power supply (even tho the wattage is the same and the eficciency is labeled the same) is different from other. So imagine you are hunting some PSU into NewEgg, so you're about to make the purchase, but I say WAIT! It is always better to take a look into the reviews of that particular model. But, how can I achieve that?, can I relly into what people say in the coment section below a video? or even in the "reviews" window in the NewEggs page? My answere is: **JhonnyGuru** yes, nowadays he is still the best when it comes into reviewing PSUs, that guy has been reviewing PSUs form like 20 years (no kidding). If there is someone I'll trust, he is the answere! 



###### Recomendations :)
*In this section you'll find some recomendations for specific needs, as I said before, its better to go into Jhonny's reviews for the best posible way of getting a good performance unit and saving some bucks at the time. But I also have to say that there are people in the internet that had already did that, so the people's recommendations are Jhonny-based" I mean, you can always check the review by yourself, but let's imagine you have to make a desition bc a unit is on sale... I'll say "take a look into this section, there is no way you can make a mistake".

- Looking for a good 850w 80+ gold? In this [reddit](https://www.reddit.com/r/buildapc/comments/avqx5t/whats_a_good_psu_brand_for_850w_80_plus_gold/) article you'll get good recomendations, tho the aim is set to specific 850w, in the post youll find redditors commenting good psu brands and some advices. 

> Brand is rather irrelevant as it is not an indication of quality. It comes down to the exact PSU. Check jonnyguru for PSU reviews. - redditor


## Cooling
###### Fan Cooling
###### Liquid Cooling



## Case
- This is JayTwoCent's MicroATX extreme air-flow case recomendation

[![video](http://img.youtube.com/vi/Lfxuqjt38dA/0.jpg)](http://www.youtube.com/watch?v=Lfxuqjt38dA "video") 



## Monitor 
###### The very basic guidelines for monitor buying.
[![Screen-Shot-2020-10-16-at-1-55-44-PM.png](https://i.postimg.cc/nzbfkd6X/Screen-Shot-2020-10-16-at-1-55-44-PM.png)](https://postimg.cc/06f45C5v)

_Its necessary to remind that the most basic thing in monitors its their panels, above you'll find just related info about panels_

[![Hq0GktS.jpg](https://i.postimg.cc/WzVj29nB/Hq0GktS.jpg)](https://postimg.cc/S2gHdfHd)

_A side-by-side comparisson into monitor's looks_



###### Complete guide of monitor picking.
In [**this reddit post**](https://www.reddit.com/r/buildapc/comments/92mb7r/updated_monitor_buying_guide/), you will find an _updated_ complete guide for picking your monitor. It includes an easy step-by-step process in which firstly you'll have to determine your monitor's purpose (editing, artwork, gaming, etc...), then **of course** you'll be provided by a more detailed information about _**monitor panels**_, and a lot more information relevant about the topic

- You don't trust reddit or maybe you want more info about?
[Here](https://www.tomshardware.com/reviews/monitor-buying-guide,5699.html#:~:text=Determine%20your%20monitor's%20main%20purpose,a%20high%2Dcontrast%20VA%20panel.) you'll find also a pretty solid guide. (Maybe a little bit more complete)

- Want to inquire a little bit more into monitor's panels?
In this [HowToGeek article](https://www.howtogeek.com/658701/tn-vs.-ips-vs.-va-whats-the-best-display-panel-technology/) you'll have a pretty good research dedicated only for monitor's panels.

###### Monitors for Gaming
- Motion blur AKA "Ghosting" effect.
[Here](https://levvvel.com/monitor-ghosting-fix/#:~:text=Simply%20said%20monitor%20ghosting%20is,%E2%80%9Cghosts%E2%80%9D%20behind%20moving%20objects.&text=This%20is%20because%20when%20the,image%20effect%20on%20the%20display.) is pretty detailed guide into ghosting, what exactly it is, causes, etc...

- Motion blur reduction in monitors?
In this [web article](https://blurbusters.com/faq/motion-blur-reduction/) you'll find comparissons and information about blur reduction in monitors.

- Want to test your monitor for ghosting?
[This](https://www.testufo.com/ghosting) site is currently used for testing.


###### Monitors for Editing
- What is the sRGB and why it's crucial in editing monitors?
In this [article](https://techterms.com/definition/srgb#:~:text=Stands%20for%20%22Standard%20RGB%22%20(,programs%2C%20monitors%2C%20and%20printers.) you'll find a fair explanation of what sRGB stands, how its connected to your printer and how it differentiates fron Adobe RGB.

- Does having more that 100% sRGB is actually better?
In this [Reddit](https://www.reddit.com/r/Monitors/comments/c83w47/is_125_srgb_better_than_100_srgb/) post, you'll find some comments of users on why it might be worth it, or maybe not.

- What would you get if you had $400 to spend on a monitor for editing?
In this [Reddit](https://www.reddit.com/r/VideoEditing/comments/j40z19/if_you_had_400_to_spend_on_a_monitor_for_editing/) discussion, people recomend a monitor with a good color spectrum, which is typycally needed for accurrate color grading. (or at least that's what I think)
> I’m a fan of the ProArt series by Asus. Their $300 27” 2k monitor is supposed to be really color accurate for the price range. Obviously it’s not HDR or P3 but I’m pretty sure it’s ~1.5 delta ranges for all of sRGB.
It also has an amazing monitor stand for the price range too. Not something people usually think about for monitors.
Edit: it also has Rec. 709 (but I’m not too familiar with that color profile) and the 24” 1080p one is less than $200 and 16:10 - redditor

###### Helpfull sites.
~ [TFT CENTRAL](https://www.tftcentral.co.uk/reviews.htm) for solid/pro monitor reviews

~ [Hardware Unboxed](https://www.youtube.com/c/Hardwareunboxednow/featured) youtube channel, for the best/pro reviews in the youtube area.

## Softwares, Games, Benchmarking softwares, etc...
###### Games 
- Why Far Cry 5 uses a lot of the CPU? 

In this steam [forum](https://steamcommunity.com/app/552520/discussions/0/3211505894137235415/) you will find out why generally ubisofts games are really CPU bounded.

> This game is really cpu bound man. Pretty much any of the recent ubisoft games are pretty cpu intensive. Doesn't mean the games aren't optimized like most people would tell you. I used to have a 4690k@4.6ghz, and games like Wildlands, Watch Dogs 2, and Division would have all 4 cores pegged at 100% more than half the time creating a bottleneck for my 1080. I upgraded to a 8700k@4.8ghz with DDR4@3200mhz(old ram was ddr3@1600mhz), and my fps went from dropping down to 30's to dropping down to 80's. My 8700k averages around 40% on the same areas the 4690k was getting 100%. My advice is to upgrade your Mobo, CPU, and Ram to handle this game better. - BrainyCabde

###### AfterEffects
Is AfterEffects more CPU or GPU based?
> Right now the majority of calculations for AE are done with CPU. They're working on getting certain effects running on GPU, but for right now it's only for a few things. The main thing inside AE that uses cuda is the very obsolete raytrace renderer, so don't bother getting a beefy GPU for that. So unless you are running a lot of GPU powered effects (like E3D) the main focus should be CPU right now. -redditor
###### Benchmarking softwares
Want to know if your rig is well enough for editing, office working, or simple tasking? 
[Here](https://benchmarks.ul.com/resources/what-is-a-good-pcmark-10-score) you will get the needed benchmark score for your PC for doing editing, simple tasks and office working, also you will get a guide on how self benchmark your PC to get the score and the compare it with standards.

## Maintenance
- In this [article](https://www.makeuseof.com/tag/5-pc-parts-tend-die-extend-lifespans/) you will find the 5 main PC components that tend to die, and how to increase their lifespan.
- Why is it important, to have a good air cooler?
> When overclocking, the VOLTAGE can significantly raise the temperature. If you carefully tweak the CPU settings, a **good air cooler** may give you acceptable cooling below 80degC at maximum overclock speeds. Also, you may have to reduce the clock speed by say 4.4GHz vs 4.6GHz(max Turbo), dont worry, despite the 2MHz decreased, the real-world impact on it will be relatively small. - forum guy

## BUILDS
_Here you will find concrete builds for specific tasks. This also features youtuber builts as well as builts I made by combining reddit/youtubecomment/youtuber ones. I didnt included a description of them, because the PCPartPicker web features an specific section for that, also because at the subheaders above you will find some info that redirectionate to these builds, so I found un-usefull to repeat the info again_
###### alpha
###### beta
###### charlie
###### delta




