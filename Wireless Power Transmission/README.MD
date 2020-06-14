# Wireless Charging ---> Wireless Power transmission
In the recent times, we see a wholelot of smartphones coming up with wireless charging facilities. The first phones/tablets with wireless charging features came around in the year 2010. But it took around 4-5 years for it to gain a bit of popularity. Even today after a decade, this isn't much popular in all the mobile phones. Mostly, it's available in the high-end phones. The reason behind this is it's high cost and low efficiency (performance/cost ratio). 

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

***Comparison***
Non-resonant coupled inductors, such as typical transformers, work on the principle of a primary coil generating a magnetic field and a secondary coil subtending as much as possible of that field so that the power passing through the secondary is as close as possible to that of the primary. This requirement that the field be covered by the secondary results in very short range and usually requires a magnetic core. Over greater distances the non-resonant induction method is highly inefficient and wastes the vast majority of the energy in resistive losses of the primary coil.

###  Magnetic resonant inductive coupling
There is also another type of charging feature that uses, magnetic resonant inductive coupling which uses resonant coils in the both the ends (i.e) the source end and the reciever end. When the two resonating coils are held in resonance then large amount of power can be transmitted. 

The other advantages of using such features are
* Large power transmission. The amount of power that can be transmitted using this technology is in the ordeer of hndreds of watt. Due to this reason, it's used in charging electic vehicles and other home appliances.

* Orientation issues are combated. In the case of the standard and resonant inductive coupling the alignment of both the source and the reciever coils should be intact or in some predefined way. But using this method there is no need for proper alignment as they are in resonance with each other.

* Distance between the charging pad's surface and the device can be a bit large. This is also other important advantage since there is no need for contact between the two surfaces. Hence this is more ideal for E-Vehicles and home appliances.

Advantages include:
* Automated high power inductive charging of electric vehicles allows for more frequent charging events and consequential driving range extension.

* Automatic operation of inductive charging solves this problem, allowing the vehicle to theoretically run indefinitely.
Inductive charging of electric vehicles at high power levels enables charging of electric vehicles while in motion (also known as dynamic charging).

The following is a best example of a company that serves the need in a wider scale. It basically uses the resonant and magnetic resonant inductive coupling systems

### WiTricity = Wireless + Electricity
WiTricity a Watertown, Mass.-based company that licenses technology originally developed at the Massachusetts Institute of Technology (MIT). The company aims at providing solutions to charging problems in terms of wireless charging facilities. The first commercial application of this technology was seen in the dell latitude laptops that can be charged wirelessly. At present, it's only available for Electric vehicles, but it also aims at developing it further for all electrical home appliances that are used.

***WiTricity uses resonant inductive coupling technology principle for power transfer.***

Their idea of implementing the same to all the homes is by using Source resonating coils that will be placed in the walls of the home.

### Future of wireless charging


### References:
1. https://www.lifewire.com/what-is-inductive-charging-575296
2. https://en.wikipedia.org/wiki/Inductive_charging
3. https://www.infineon.com/cms/en/discoveries/wireless-inductive-charging/
4. https://en.wikipedia.org/wiki/Resonant_inductive_coupling
5. https://witricity.com/products/why-magnetic-resonance/wireless-smart-cities/
6. https://www.computerworld.com/article/3235176/wireless-charging-explained-what-is-it-and-how-does-it-work.html
