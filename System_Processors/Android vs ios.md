## Android vs iOs (A comparison in view of their processor)

There are two main types of smartphone devices available currently in the market. They are the Android and the iOs phones. Even though both do perform similar kind of features, there quite a few important differences in thier working, and the way they are manufactured. 

***One such important difference in between lies in the processor of each kind. Processor is the heart of the smartphone that performs all the required functionality. In this approach let's find out more on what's the difference between the processor in android phones and the processors in the iPhones.***


***Apple's own designed Processors***

Apple has designed System on Chip (SoC) and System in Package (SiP) processors for their mobile consumer devices. They combine a low-power central processing unit (CPU) and other components into a physically compact package to meet the stringent power and space constraints common to mobile devices.

In the earlier stages, Apple first used SoCs in early revisions of the iPhone and iPod touch. These were specified by Apple and manufactured by Samsung, they combine in one package a single ARM-based processing core (CPU), a graphics processing unit (GPU), and other electronics necessary for mobile computing.

***How are iOs procesors made?***

Apple designs processors that use ARM’s 64-bit instruction architecture. That means that Apple’s chips use the same underlying RISC architecture as Qualcomm, Samsung, Huawei and others. The difference is that Apple holds an architectural license with ARM, which allows it to design its own chips from scratch. Apple’s first in-house 64-bit ARM processor was the Apple A7 which was used in the iPhone 5S. It had a dual-core CPU, clocked at 1.4 GHz and a quad-core PowerVR G6430 GPU.

***Apple outraged all processors all of a sudden

It is fair to say that Apple caught Qualcomm sleeping when it announced the 64-bit A7 back in 2013. Until that point, Apple and Qualcomm had both been shipping 32-bit ARMv7 processors for use in mobile devices. Qualcomm was leading the field with its 32-bit Snapdragon 800 SoC. It used an in-house Krait 400 core along with the Adreno 330 GPU. Life was good for Qualcomm.

When Apple suddenly announced a 64-bit ARMv8 CP, Qualcomm had nothing. But it didn't much time for qualcomm to design a 64 bit processor. In April 2014, Qualcomm launched the Snapdragon 810 with four Cortex-A57 cores and four Cortex-A53 cores. The “Cortex” range of cores come directly from ARM, the custodians of the ARM architecture. But in that same year, Apple announced the A8, its second generation in-house 64-bit CPU. It wasn’t until March 2015 that Qualcomm was able to announce its first generation in-house 64-bit CPU, the Snapdragon 820, with its custom Kryo CPU core.

***Apple's own Design for the cores***

Apple made the better design decision - because they can. Most existing ARM implementations are very close in design to ARM’s reference designs. They don’t deviate much in terms of performance, etc. By contrast, Apple has designed their own architecture. Their SoCs accommodate larger and more powerful cores. What people fail to recognize is that most workloads are only optimized for single core performance. As an example, web applications that run on Javascript are only leveraging single core. Some algorithms simply cannot be optimized for multiple cores. However, there are some that can. While there is value in having strong multi-core performance, there are few instances outside of benchmarks where this is made evident.

***What is different about Apple’s CPU cores?***

_First_, Apple had a head-start over just about everyone when it comes to 64-bit ARM based CPUs. Although ARM itself announced the Cortex-A57 back in October 2012, the proposed timeline was that ARM’s partners would ship the first processors during 2014. But Apple had a 64-bit ARM CPU in devices during 2013. The company has since managed to capitalize on that early lead and has produced a new CPU core design every year.

_Second_, Apple’s SoC efforts are tightly coupled to its handset releases. Designing a high performance mobile CPU is hard. It is hard for Apple; for ARM; for Qualcomm; for everyone. Because it is hard, it takes a long time. The Cortex-A57 was announced in October 2012, but it didn’t appear in a smartphone until April 2014. That is a long lead time. That lead time is changing.

_Third_, Apple’s CPUs are big and in this game, big means expensive. According to a 2016 report by the Linley Group, the Hurricane cores in the Apple A10  are “about twice the size of other high-end mobile CPUs”. Even the smaller Zephyr cores are much larger than their low-power counterparts, “nearly twice as large as Cortex-A53.” The key here is that Apple sells smartphones, not chips. As a result, it can afford to make the SoCs more expensive and recoup the money in other places, including the final retail price.

ARM and Qualcomm, however, are in the chip selling business. ARM does the CPU core design for Qualcomm (and others like MediaTek) and Qualcomm designs the chips, which it in turn sells to handset makers like Samsung, Sony, LG, etc. ARM needs to make a profit. Qualcomm needs to make a profit. All the OEMs need to make profits. The practical result is that Qualcomm can’t afford to make overly expensive processors or OEMs will start looking elsewhere.

_Fourth_, Apple’s CPUs have big caches. Silicon costs money and for some chip makers their profit margin can be found in just 0.5 mm2 of silicon saved. Like the third point above, Apple is able make bigger chips (in terms of silicon costs) and that includes large caches.

Before the Cortex-A75, none of ARM’s Cortex processors supported L3 caches. But Apple has been using big L3 caches since the A7. The Apple A7 and the A8 had 1 MB L2 caches and 4 MB L3 caches. The A9 and the A10 had a 3 MB L2 cache and 4 MB L3 cache, that is 7 MB of cache altogether. According to Geekbench the A11 has 8 MB of L2 cache and no L3 cache. While the Cortex-A75 now supports L3 caching, also up to 4 MB, and 4 MB of L2 cache (0.5 MB per core), it is up to chip makers like Qualcomm to decide how much cache they want to include. 

_Fifth_, and finally, Apple’s plan of making processors with wide pipelines at (initially) lower clock speeds has come to fruition. In very broad terms, SoC makers can either make a CPU core with a narrow pipe, but run that pipe at high clock frequencies; or use a wider pipe, but at lower clock speeds. Like a real world water pipe, you can either pump water at high pressure through a narrower pipe or at lower pressure through a wider pipe. In both cases you can theoretically achieve the same throughput. ARM falls squarely in the narrow pipeline camp, while Apple is in the wider pipeline camp. 

***Conclusion***

To conclude on the discussion I will summarise the important points from the above discussion. One of the main important thing followed by apple was to make the wider pipeline with a lower clock speed and so as to increse the IPC(Instruction per cycle). All others followed the way of increasing the number of cores. But Apple went on increasing t's IPC with lesser number of cores, but parallely increasing the number of threads per core.

To combat the effect of latency, apple introduced large cache memory and so there is a more efficient way of processing. While coming to the battery performance, it follows the "Race to shutdown" methodology wherein the cores are powered on for small time of time, the task is done faster and as soon as the task is done the performance cores are shutdown.

To finish off we won’t see a SoC from Qualcomm, Samsung or Huawei that can beat Apple’s latest SoC, in terms of raw CPU power unless one of the following happens:

- Apple stumbles and produces a “bad” SoC. This means it will lose its lead against the other OEMs.
- One of the leading chip makers decides to build an expensive CPU with a large surface area and lots of silicon dedicated to things like cache etc.
