# Wireless Charging ---> Wireless Power transmission
In the recent times, we see a wholelot of smartphones coming up with wireless charging facilities. The first phones/tablets with wireless charging features came around in the year 2010. But it took around 4-5 years for it to gain a bit of popularity. Even today after a decade, this isn't much popular in all the mobile phones. Mostly, it's available in the high-end phones. The reason behind this is it's high cost and low efficiency (performance/cost ratio). In this article we will first look on what exactly is wireless charging, it's types and other features of it. Finally we will also have a look at how this principle can be extended further to charging EV's and operating home appliances.

***But anyways how does this work?***

Inductive charging was first invented by Nikola Tesla, and it was in use during 1990's in the tooth brushes. The main underlying principle of wireless charging is the inductive charging (a.k.a wireless charging/cordless charging) which is purely based on Faraday's law of induction. Energy is transferred through inductive coupling. An electrical charge passes safely from the pad to the phone, across the tiny gap between them. The charging pad still needs to be plugged into the mains electrical supply, but the device we tend to charge sits loosely on top. Also, a note on it is that wireless charging doesn't mean that there aren't wires at all, ther's no cable between the device and the power socket. However, the charging pad must be connected to the power socket so that there is AC current source that is used in the coil for induction.

***Inductive charging***

Here, the principle of energy transfer is inductive coupling. And hence both the charging pad and phone contain induction coils in them. In simple terms, induction coils are simply a core of iron wrapped in copper wire. An alternating current is run through an induction coil in the charging station or source pad (the primary or transmission coil.) Any moving electric charge creates a magnetic field, as stated by Oersted's law. The magnetic field fluctuates in strength as the AC current is continually changing amplitude. A changing magnetic field generates an electromotive force otherwise known as Faraday's law of induction. This makes an alternating electric current in a second induction coil (the receiving, or secondary coil) in the portable device. It is then converted to direct current with a rectifier and used to charge a battery or provide operating power.

To summarize it, when the phone or other portable device is placed on the wireless charging pad, the proximity of the coils allows an electromagnetic field to be created. This electromagnetic field allows electricity to be passed from one coil (in the charging pad) to the other (in the phone). The induction coil in the phone then uses the transferred electricity to charge the device battery.

***Advantges***

* Charge several portable devices in the same time. If we have several portable devices, instead of carrying multiple cables for each individual device separately, a single wireless charger can be used to dharge all such devices. There already exists wireless charger that supports multiple devices at the same time.

* Protected connections – No corrosion when the electronics are enclosed, away from water or oxygen in the atmosphere. Less risk of electrical faults such as short circuit due to insulation failure, especially where connections are made or broken frequently.

* Make your phone truly waterproof. Because one induction coil does not need to be in direct contact with the other to allow a charge to pass between them, it could be sealed inside the body of a device and enable it to be made completely waterproof. 

* Durability – Without the need to constantly plug and unplug the device, there is significantly less wear and tear on the socket of the device and the attaching cable.

* Create safe charging zones almost anywhere. The technology could easily be used to provide safe charging points in public places. As inductive charging is standardized, restaurants and cafés could incorporate charging zones into tabletops and airlines could have charging pads in their armrests.

***Disadvantages***

* Less efficient than wired charging. Current inductive charging systems are not quite as efficient as charging with a cable. This means that, in general, a phone charged on a wireless charging pad will take longer to reach full charge than a phone plugged directly into an electrical socket.

* More expensive – Inductive charging also requires drive electronics and coils in both device and charger, increasing the complexity and cost of manufacturing.

* Inconvenience – When a mobile device is connected to a cable, it can be moved around (though in a limited range) and operated while charging. In most implementations of inductive charging, the mobile device must be left on a pad to charge, and thus can't be moved around or easily operated while charging. With some standards, charging can be maintained at a distance, but only with nothing present between the transmitter and receiver.

* Lack of a universal standard. There is also no wholly standardized inductive charging system, meaning a device capable of being wirelessly charged may not be compatible with the charging pad of another device you own. However, several large electronics manufacturers have started working with a standard called Qi (pronounced "chee"), including LG Electronics, Motorola, Nokia, HTC, Sony, and Samsung, so this will certainly become less of a problem over time.

* There is a risk with foreign metal objects, as with induction stoves, they can become extremely hot when they get into the magnetic field of the charging coil. But “smart” charging stations are already available, that can detect when a foreign object is between the smartphone and the contact surface and stop the charging process.

### Resonant Inductive Coupling

A major disadvantage of the standard inductive coupling is that it can only be used for low power applications (maximum wattage is around 30W), also there is a disance constraint in the standard inductive coupling. The gap between the device and the pad is very minimal. To overcome this advantages we use the Resonant Inductive coupling, that is an extension of the inductive coupling.

Looking at it's working, resonant inductive coupling is a stronger form of inductive coupling that occur when the secondary inductive coil (on the device) resonates. The below image shows what exactly is the process, there is an additional resonator that is placed in the secondary circuit.

![reso](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6c/Magnetic_phase_synchronus_coupling.svg/370px-Magnetic_phase_synchronus_coupling.svg.png)

Using resonance can help improve efficiency dramatically. If resonant coupling is used, the secondary coil is capacitive loaded so as to form a tuned LC circuit. If the primary coil is driven at the secondary side resonant frequency, it turns out that significant power may be transmitted between the coils over a range of a few times the coil diameters at reasonable efficiency. This process occurs in a resonant transformer, an electrical component which transformer consists of high Q coil wound on the same core with a capacitor connected across a coil to make a coupled LC circuit.

The most basic resonant inductive coupling consists of one drive coil on the primary side and one resonance circuit on the secondary side. In this case, when the resonant state on the secondary side is observed from the primary side, two resonances as a pair are observed. One of them is called the antiresonant frequency (parallel resonant frequency 1), and the other is called the resonant frequency (serial resonant frequency 1'). The short-circuit inductance and resonant capacitor of the secondary coil are combined into a resonant circuit. When the primary coil is driven with a resonant frequency (serial resonant frequency) of the secondary side, the phases of the magnetic fields of the primary coil and the secondary coil are synchronized. As a result, the maximum voltage is generated on the secondary coil due to the increase of the mutual flux, and the copper loss of the primary coil is reduced, the heat generation is reduced, and the efficiency is relatively improved. The resonant inductive coupling is the near field wireless transmission of electrical energy between magnetically coupled coils, which is part of a resonant circuit tuned to resonate at the same frequency as the driving frequency.

The term that describes the efficiency of resosnant iductive coupling is the coupling coefficient, defined as the ratio of transformer open-circuit voltage ratio to the ratio that would be obtained if all the flux coupled from one coil to the other. Resonant systems are said to be tightly coupled, loosely coupled, critically coupled or overcoupled. Tight coupling is when the coupling coefficient is around 1 as with conventional iron-core transformers. Overcoupling is when the secondary coil is so close and the formation of mutual flux is hindered by the effect of antiresonance, and critical coupling is when the transfer in the passband is optimal. Loose coupling is when the coils are distant from each other, so that most of the flux misses the secondary. In Tesla coils around 0.2 is used, and at greater distances, for example for inductive wireless power transmission, it may be lower than 0.01.

***Comparison***
Non-resonant coupled inductors, such as typical transformers, work on the principle of a primary coil generating a magnetic field and a secondary coil subtending as much as possible of that field so that the power passing through the secondary is as close as possible to that of the primary. This requirement that the field be covered by the secondary results in very short range and usually requires a magnetic core. Over greater distances the non-resonant induction method is highly inefficient and wastes the vast majority of the energy in resistive losses of the primary coil.

### Qi (Wireless Charging Standard)
Qi is an open interface standard that defines wireless power transfer using inductive charging over distances of up to 4 cm (1.6 inches), developed by the Wireless Power Consortium. The system uses a charging pad and a compatible device, which is placed on top of the pad, charging via resonant inductive coupling. First released in 2008, the Qi standard had by 2019 been incorporated into more than 160 smartphones, tablets and other devices.

*Need for such a standard ?*

There arises a need for a common description of the charger's specification. If every company does has it's wireless charging standard with different specification, then the chargers can be used only for specific devices. In such cases, for each portable device there would multiple chargers with different standards, that wold create troubles in compatiblity. To eradicate this confusion, the Wireless Power Consortium established Qi standard as a common standard for all the devices that has the feature of Wireless charging. Many manufacturers of mobie phones, and other devices are a part of it. The first standard was released in the year 2010, for low powered devices and from then there has been many versions of it coming up. The below table specifies all the versions of the satndard that has been released till date.

|Version number|	Released|	Maximum wattage	|Notes|
|:---:|:---:|:---:|:---:|
|1.0	|2010	|5 W	|Power transmitter can be a single coil, coil array, or moving coil.|
|1.1	|2012	|5 W	|12 different transmitter specifications, foreign object detection to prevent heating of metal objects near transmitter, added powering transmitter over USB|
|1.2|	2015|	Baseline Power Profile (BPP): 5W Extended Power Profile (EPP): 15 W |Increased maximum transmitter power to 15W, improved thermal tests for transmitters, improved timing specs, improved foreign object detection sensitivity, optional receiver ID (WP-ID).Labeled by Samsung as “Fast Wireless Charging” (initially 10W, introduced on the Galaxy Note 5 and S6 edge plus), August 2015) requires charging plate to be connected to Qualcomm Quick Charge 2.0-enabled 15W USB charger (9 Volt, 1.67 Ampère support).|
|1.2.3|	2017|	EPP Power Class 0: 5W - 30W|	Added Power Class 0 which allows the consumer to negotiate up to 30W from the charger.|

***Features and Specification***

The WPC published the Qi low-power specification in August 2009. Under the Qi specification, "low power" inductive transfers deliver power below 5 W using inductive coupling between two planar coils. These coils are typically 5 mm apart but can be up to 40 mm and possibly farther apart. The Qi low-power specification has been renamed to the Qi Baseline Power Profile (BPP).

In 2015, WPC introduced the Qi Extended Power Profile (EPP) specification which supports up to 15 W. EPP is also typically used to charge mobile devices like BPP. WPC also introduced Proprietary Power Delivery Extension (PPDE) to allow phone OEMs to deliver higher than Baseline Power Profile's 5W or the Extended Power Profile's 15W. The companies that use proprietary standards are Apple, Google, Hauwei and Samsung.

Regulation of the output voltage is provided by a digital control loop where the power receiver communicates with the power transmitter and requests more or less power. Communication is unidirectional from the power receiver to the power transmitter via backscatter modulation.In backscatter modulation, the power-receiver coil is loaded, changing the current draw at the power transmitter. These current changes are monitored and demodulated into the information required for the two devices to work together.

In 2011, the Wireless Power Consortium began to extend the Qi specification to medium power. As of 2019, the Medium Power standard currently delivers 30 to 65 W, it is expected to eventually support up to 200 W (typically used for portable power tools, robotic vacuum cleaners, drones and e-bikes).

In 2015, the WPC also demonstrated a high-power specification **"Ki"** that will deliver up to 1 kW, allowing the powering of kitchen appliances among other high-power utilities.

###  Magnetic resonant inductive coupling
There is also another type of charging feature that uses, magnetic resonant inductive coupling which uses resonant coils in the both the ends (i.e) the source end and the reciever end that are paired up with each other(operate at the same frequency). When the two resonating coils are held in resonance then large amount of power can be transmitted. The primary resonator increases the primary driving coil current and increases the generated magnetic flux around the primary resonator. This is equivalent to driving the primary coil at high voltage. So, this is an alternative for powering large appliances and devices wirelessly without using high voltage in the primary coil (as in the case of typical inductive coupling).

![mag res ind cou](https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/Wireless_power_-_resonant_inductive_coupling.svg/370px-Wireless_power_-_resonant_inductive_coupling.svg.png)

Resonant transfer works by making a coil ring with an oscillating current. This generates an oscillating magnetic field. Because the coil is highly resonant, any energy placed in the coil dies away relatively slowly over very many cycles; but if a second coil is brought near it, the coil can pick up most of the energy before it is lost, even if it is some distance away. The fields used are predominantly non-radiative, near fields (sometimes called evanescent waves), as all hardware is kept well within the 1/4 wavelength distance they radiate little energy from the transmitter to infinity.

The energy will transfer back and forth between the magnetic field in the inductor and the electric field across the capacitor at the resonant frequency. This oscillation will die away at a rate determined by the gain-bandwidth (Q factor), mainly due to resistive and radiative losses. However, provided the secondary coil cuts enough of the field that it absorbs more energy than is lost in each cycle of the primary, then most of the energy can still be transferred.

The features and advantages of it include: 
* Large power transmission. The amount of power that can be transmitted using this technology is in the ordeer of hndreds of watt. Due to this reason, it's used in charging electic vehicles and other home appliances.

* Orientation issues are combated. In the case of the standard and resonant inductive coupling the alignment of both the source and the reciever coils should be intact or in some predefined way. But using this method there is no need for proper alignment as they are in resonance with each other.

* Distance between the charging pad's surface and the device can be a bit large. This is also other important advantage since there is no need for contact between the two surfaces. Hence this is more ideal for E-Vehicles and home appliances.

* Automated high power inductive charging of electric vehicles allows for more frequent charging events and consequential driving range extension.

* Automatic operation of inductive charging solves this problem, allowing the vehicle to theoretically run indefinitely.
Inductive charging of electric vehicles at high power levels enables charging of electric vehicles while in motion (also known as dynamic charging).

The following is a best example of a company that serves the need in a wider scale. It basically uses the resonant and magnetic resonant inductive coupling systems

### WiTricity = Wireless + Electricity
WiTricity a company that licensed technology originally developed at the Massachusetts Institute of Technology (MIT). The company aims at providing solutions to charging problems in terms of wireless charging facilities. The first commercial application of this technology was seen in the dell latitude laptops that can be charged wirelessly. At present, it's only available for Electric vehicles, but it also aims at developing it further for all electrical home appliances that are used. Their idea of implementing the same to all the homes is by using Source resonating coils that will be placed in the walls of the home. For charging the EV's they place harging pads underneath the ground and once when car is parked over that space then through magnetic resonance coupling charging takes place.

***WiTricity uses resonant inductive coupling technology principle for power transfer.***

![witricity](https://witricity.com/wp-content/uploads/2016/11/overview-diagram.png)

Features of Wireless EV's charging:
* Power transfer as efficient and as fast as conventional plug-in. An efficiency of 90-93 % was recorded.

* One single design for types of cars - spans sports cars, sedans and SUVs. The height between the pad and the battery can be around 10-25 cm and so every EV, regardless of ride height, will be interoperable with a common ground pad.

* Position allowance corrects (or compensates for) parking misalignment. 

* Powers through materials and elements. So, it can be placed in Surface or in-ground placement, terrains make no issues be it Asphalt, cement, snow, ice.

* Smart and Safe, it includes FOD (Foreign Object Detection), LOD (Live Object Detection) and PD (Position Detection) offer advanced protection and ease of use.

* Bi-Directional Power Transfer (Wireless V2G), Large EV batteries can help utility companies stabilize the grid or even power your home. The same principle but in a reverse manner.

![Witricity EV](https://witricity.com/wp-content/uploads/2019/03/magnetic-resonance-benefits-1024x460.png)

### Dynamic charging
Till now, what we have seen are primarily static charging methods. Where the device can't be in motion while charging. Examples include, the Electic vehicle must be in stationary state rather in motion. But there is yet another technology to overcome this issue, that's dynamic charging wherein the charging of the device occurs while it is in motion.

Researchers at the Korea Advanced Institute of Science and Technology (KAIST) have developed an electric transport system (called Online Electric Vehicle, OLEV) where the vehicles draw power from cables underneath the surface of the road via non-contact magnetic charging (where a power source is placed underneath the road surface and power is wirelessly picked up on the vehicle itself). As a possible solution to traffic congestion and to improve overall efficiency by minimizing air resistance and so reduce energy consumption, the test vehicles followed the power track in a convoy formation. In July 2009 the researchers successfully supplied up to 60% power to a bus over a gap of 12 centimetres (4.7 in). Commercialization efforts of the technology have not been successful because of high costs.

### Future of wireless charging

The number of devices that can be charged wirelessly is increasing continuously. According to IHS Markit, the market for wireless electricity supply continued to gather momentum in 2018. In 2018, worldwide sales of wireless power receivers and transmitters across all applications and product segments rose to 600 million units – a 37 percent increase compared to the previous year. IHS Markit forecasts that approximately 2.1 billion units will be shipped worldwide by 2023.

With the increase in fast charging options, acceptance among users will also continue to grow. Beginning with smartphones, wireless charging will also be possible for many other devices. Headphones, smartwatches, and fitness trackers, but also medical devices with low power consumption, such as pacemakers, will benefit from this. Depending on the stage of development in the technology, higher charging power may also be possible in the future.

### References:
1. https://www.lifewire.com/what-is-inductive-charging-575296
2. https://en.wikipedia.org/wiki/Inductive_charging
3. https://www.infineon.com/cms/en/discoveries/wireless-inductive-charging/
4. https://en.wikipedia.org/wiki/Resonant_inductive_coupling
5. https://witricity.com/products/why-magnetic-resonance/wireless-smart-cities/
6. https://www.computerworld.com/article/3235176/wireless-charging-explained-what-is-it-and-how-does-it-work.html
