# GAMEBOY-FLASHCART-MBC1

This is an untested flash cart for the Gameboy. I've made many other flash carts but thought that these would be more popular being compatible with the InsideGadgets GBxCart RW.
I would reccomend making the MBC5 version flashcart due to it being compatible with more games. The reason to build this is if there is a game that doesn't work on the MBC5 cartridge.
I will build this to make myself a dedicated Zelda - Links Awakening cartridge. That is an MBC1 based game that doesn't work on the MBC5 based cartridge.

You are limited the 512KB game sizes with this cartridge. This shouldn't ever be an issue as I think only 2 games made use of the full 2MB ROM size the MBC1 can handle.

The difficulty of making such a device these days is, when the Gameboy was released, the 8-bit era was already on the way out. So 33 years later, parts are not readily available. I'm not sure how other people manage to aquire a consistant supply of components.

![Gameboy MBC1 Cart + FRAM](https://user-images.githubusercontent.com/65309612/159166206-e805b48b-a37f-4045-ac42-eaf347163782.jpg)

![Gameboy MBC1 Cart + FRAM 2](https://user-images.githubusercontent.com/65309612/159166205-cb88fab6-66ef-4fcd-83d7-5b36aa37ef67.jpg)

**EEPROM 29F040B**

These are readily available today. They are 512KB in size which fits perfectly into what the MBC1 can handle. It might be a bit difficult to solder directly to the PCB as it is a PLCC package chip,
and the chip legs tuck under the chip and solder does not want to flow properly. I'm not actually sure that the GBxCart RW can write these chips or not, but I guess I'll have to find out.

**SRAM FM18W08**

The SRAM isn't SRAM, its the modern FRAM that was made to replace battery backed SRAM in industrial PLC applications (among other things I'm sure). Once more Aliexpress has these in a small supply. 
These are the most expensive part of building this, apart from the donor MBC5 chip, depends on where you get the MBC5. 
The FRAM is available on eBay but the prices are egregious. Definitly do not buy the FRAM from eBay. 
The FM1808 was discontinued in 2008 and replaced by the FM18W08 which should be available from more reputable suppliers like Mouser and Digikey. 
The FM1808 is what I have tested, but there should be no reason the FM18W08 shouldn't work.

**Memory Controller MBC1**

This is the most expensive part of the cartridge. Not as easy to get as an MBC5 as they were in every dam Gameboy Colour game. The MBC1 was early on in the Gameboys life where a lot 
of games were still not even using a memory controller or needed very little SRAM space. So a lot of the cheap or crap games these days have an MBC2 inside. For that reason I'll not be making batches of these for sale.

**Compatability**

Completely untested but the theory is that ever MBC1 based game will work just perfectly.
