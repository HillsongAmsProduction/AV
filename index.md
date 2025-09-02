# AV guide

## Introduction 

This guide provides an overview of the set-up, pack-down, troubleshooting, and system overviews of the AV setup in Hillsong Amsterdam 


### set-up
1. **7am - 8am**: Arrive at the venue and begin setting up the AV equipment. Ensure all cables are properly connected and secured.

* 1.1 Av exist of multiple cases, we have:

    * 1 server rack case -> can be found in the hallway between subroom 1 and the auditorium it looks like ![serverRack](/av_guide_images/ServerReckFrontClosed.jpeg)
    * 1 playout case -> can be found in the hallway between subroom 1 and the auditorium it looks like ![playoutCase](/av_guide_images/Playout.jpeg)
    * 3 pc cases -> found in the storage looks like the playout case but less deep called: admin, overlay, songwords in the songwords case is a white speaker
    * 1 av tower case -> found in the storage
    * 1 greengo tower case -> found in the storage
    * 2 multiview cases -> found in the storage looks like ![multiviewCase](/av_guide_images/MultiViewsSetup.jpeg)
* 1.2 Unpack all the cases and set up the equipment in their designated locations. the layout is as follows (everything is with your back to the glass and looking to the tv already present in the room): 
* 1.2.1 on both sides of the tv in front the multiview cases
* 1.2.2 on the left side next to the multiview case and with the left side against the wall the server rack
* 1.2.3 on the left side on 1/3 of the wall the admin case
* 1.2.4 in line with the admin case we have a row with from left to right the overlay case, the playout case and the songwords case
* 1.2.5 on the right side we have the av tower adn teh greengo tower

* 1.3 the playout, overlay, songwords and admin cases have build in tables:
![CaseTabelClosedOnBack](/av_guide_images/TableClosedLegs.jpeg)
![CaseTabelOpenOnBack](/av_guide_images/TableOpenLegsDownSide.jpeg)
![CaseTabelOpenOnFront](/av_guide_images/TableOpenLegsUpSide.jpeg)
two are placed in frond of the tv for the film team one is placed left between the server rack and the admin case and one is placed right next to the greengo tower.

* 1.4 Connect all the equipment using the cables provided in the cases. Ensure that all connections are secure.
  * 1.4.1 all the pc cases have a cable bundle on the right side in the back of the case: ![CableBundle](/av_guide_images/AvPlayoutBack.jpeg) all these cables need to be connected to the server rack.
  * 1.4.2 connecting the cables to the server rack: ![ServerRackBack](/av_guide_images/ServerRackStationsConnections.jpeg) all cables are labeled
  * 1.4.3 in the wall under the tv there is a whole in the wall these leads to the server room on the otherwise were also the sound racks are. through this whole goes one high-voltage power cable and a bundle of cables. 1 sdi for translations, 2 fiber cables and two network cables labeled 6.1 and 6.2, and 4 hdmi cables 
  * 1.4.4 the high-voltage power cable need to be connected on teh back side of the server rack ![PowerConnection](/av_guide_images/ServerReckBackOpen.jpeg)
  * 1.4.5 the hdmi cable labeled hdmi 3 needs to be connected to the red decimeter in the back of the server rack in the input hdmi 2.0 output ![DecimeterConnection](/av_guide_images/AvDecimeterConnection.jpeg)
  * 1.4.6 the translation sdi cable needs to be connected to the black decimeter in the front of the server rack in the input translation 
  * 1.4.7 the fiber cables need to be connected to the black box in the front of the server rack labeled stage and FOH
  * 1.4.8 the network cables need to be connected front of the server rack in the network ports labeled 6.1 and 6.2
  * 1.4.9 when this is all done the server rack can be turned on by switching the 4 power switches on the back of the server rack to the on position from top to bottom
  * 1.4.10 Connect the greengo for the playout and the overlays with a greengo network cable you can take from the greengo tower case. the greengo can be connected from the dedicated station so playout greengo will connect to the playout greengo network point

* 1.5 connecting the multiviews film team desk and white speaker
  * 1.5.1 the multiview cases have a cable in the case with tulp connectors on both sides in the front of the server case on the right bottem you have white tulp power outputs the cable can be connected there and put in the back of the MultiView case in the power input, ![MultiviewPowerConnection](/av_guide_images/Av_MultiviewConnetion.jpeg)
  or you can pick a euro to tulp cable also present in the case and connect it to the power outlet in the wall under the tv do this for both multiview cases
  * 1.5.2 in the multiview cases is a sdi cable (or grap it from the sdi case) this can be connected in the front right of the server rack in output one and connected to the first most left multiview case in the sdi input do the same but as with output two the right multiview case
  * 1.5.3 from the overlay case there are two separate network cables for the film desk. the film desk is in a big black case on the server rack or playout case. open the case take the blackmagic desk and put it on one of two tables in front of the tv. connect the network cables to the back of the desk that say POE the other cable is for the greengo
  * 1.5.4 the white speaker is in the songwords case connect the power cable to the speaker and plug it in the wall outlet under the tv or use the tulp power output on the server rack. the xlr cable needs to be connected on the right side of the server rack on the left xlr output this cable can be found in the songwords case, multiview cases or server rack, if not found pick one from the sound tower in the auditorium

* 1.6 turning on the LED screen
  * 1.6.1 the LED screen can be turned on with the server rack in the middle behind the LED screen you will find a server rack like this ![ledScreenRack](/av_guide_images/AV_ServerRackOff.jpeg) switch all the red switches upstarting with the one labeled hooftschakelaar then do the other two red switches, what can happen is that one or more of the gray switches will flip to a middel position, if so flick them first down and then up again so everything looks like this: ![ledScreenRackOn](/av_guide_images/AV_ServerRackON.jpeg)
  * 1.6.2 on the bottem there is a stream deck mini, on there is a hillsong setting and a 35% setting makes sure these are selected

* 1.7 stageScreens 
  * 1.7.1 We have two stage screens in the auditorium, one in front of the auditorium on the left side of the stage before the piano, this screen, stand and power cable can be found in a case called 8x screens. this screen is connected to the fiber-box under the stage on the left side with a sdi cable av uses the last port of the fiber-box ![StageScreenFront](/av_guide_images/AV_StageScreenFront.jpeg) looks like: ![FiberBox](/av_guide_images/FiberboxFront.jpeg)
  * 2.7.2 The second screen is on a truss in the storage. The sdi and power cable is included in the truss. We put the screen in the back in the middle of the auditorium. this screen we conned to the fiber-box that lays in the FOH also for this we use the last output ![StageScreenBack](/av_guide_images/AV_Tv_placement.jpeg) ![StageScreenPower](/av_guide_images/AV_TvPowerCable.jpeg) ![StageScreenSdi](/av_guide_images/AV_TvSdi.jpeg)
  
This was the setup for av

2. **8am - 10am**: Test all AV equipment to ensure everything is functioning properly. Make any necessary adjustments. prepare for the service
* 1 prayer and praise and screens
  * 1.2 go to the gmail and get the prayer and praises for that day place the prayers on the prayers slide in pro-presenter and the praises on the praises slide in pro-presenter if needed copy the slide and split the praises/prayers over multiple slides 
  * 1.3 get the screens from the onedrive and place them in the correct section in pro-presenter
  * 1.4 make sure you scale to fill the photo is selected in pro-presenter videos are normally not scale to fill because the people in the video will be cut off or appear very wide.

### pack-down

Pack down is basically the reverse of the setup process but there are a few things to keep in mind:
* first turn off the pc's in the cases, then turn off the server rack on the back side by switching all 4 power switches to the off position from bottom to top.
* Then turn off the LED screen press the big power button of the LED controller then twist the knop and press power down do this for both led controllers, when they both show a red light you can proceed by switching all red switches down starting with the one labeled hooftschakelaar then do the other two red switches ![ledScreenRackOff](/av_guide_images/AV_ServerRackOff.jpeg)
* Then start disconnecting all cables and pack everything back in the cases.
* Try to roll all cables up in this way this wil ensure the cables last longer: [click here](https://youtu.be/uKlaXb-fLrg?si=7k0wZazKSaeWO31q)
* The server rack and the playout need to go back in the hallway between subroom 1 and the auditorium all other cases go to the storage.
* The cable though the wall needs to be rolled up around the gray hanger on the wall like the photo: ![CableHanger](/av_guide_images/RolledUpCable.jpeg)
* Make sure the greengo case has the correct amount of greengo's in them: ![GreengoCaseheadsets](/av_guide_images/GreengoCaseheadsets.jpeg)

### equipment

In here we describe the equipment present in the av setup how they work what you need to know to operate them and where to find the manuals

* av server rack
 * Allen & heath DT168: [DT168-Getting-Started](/Documents/AV_SERVER_RACK/AP11788_4-DT168-Getting-Started-Guide-Issue-4.pdf) [DT168-Technical-Datasheet](/Documents/AV_SERVER_RACK/DT168-Technical-Datasheet.pdf) 
 * Allen & heath SQ-5: [SQ-5-Introduction](/Documents/AV_SERVER_RACK/SQ5_AP11089_Introduction_issue2.pdf) [SQ-5-Technical-Datasheet](/Documents/AV_SERVER_RACK/SQ-5-Technical-Datasheet_G.pdf)
 * Luminex GigaCore 26i: [GigaCore-26i-Manual](/Documents/AV_SERVER_RACK/User-Manual_GigaCore-26i_rev-2.8.8.pdf)
 * Ubiquiti Security Gateway Professional USG-PRO-4: [USG-PRO-4-Manual](/Documents/AV_SERVER_RACK/UniFi_Security_Gateway_DS.pdf)
 * Blackmagic Design HyperDeck Studio 4K Pro: [HyperDeck-Studio-4K-Pro-techspecs](/Documents/AV_SERVER_RACK/hyperdeck-studio-4k-pro-techspecs.pdf) [Manual](https://documents.blackmagicdesign.com/UserManuals/HyperDeckHDManual.pdf)
 * sonifex DIO10: [info](https://www.sonifex.com/avn/avn-dio10-12g.shtml)
 * Blackmagic Mini Converter SDI to Audio 4k: [Sdi-To-Audio-Tech-Sheet](/Documents/AV_SERVER_RACK/mini-converter-sdi-to-audio-techspecs.pdf)  [Manual](https://documents.blackmagicdesign.com/UserManuals/BlackmagicConvertersManual.pdf)
 * Dante avio: [info](https://www.getdante.com/products/adapters/dante-avio-adapters/)
 * AJA HELO: [aja-helo](/Documents/AV_SERVER_RACK/AJA_HELO_Manual_v4.0.pdf)  [aja-helo-techspecs](/Documents/AV_SERVER_RACK/helo-spec-sheet.pdf)
 * Blackmagic Web Presenter HD: [manual](https://documents.blackmagicdesign.com/UserManuals/BlackmagicConvertersManual.pdf)
 * Art mx225: [Art-mx225-manual](/Documents/AV_SERVER_RACK/om-mx225.pdf)
 * Resi Encoder E2211: Contact Resi for questions [support](https://resi.io/support/)
 * Blackmagic Atem constellation 8k: [Manual](https://www.blackmagicdesign.com/nl/developer/products/atem/resources)
 * Blackmagic videohub 20x20: [Manual](https://documents.blackmagicdesign.com/UserManuals/VideohubInstallation.pdf)
 * Blackmagic Mini Converter Optical Fiber (12K): [manual](https://documents.blackmagicdesign.com/UserManuals/BlackmagicConvertersManual.pdf)
 * Decimator 12G-CROSS: [Decimator-Manual](/Documents/AV_SERVER_RACK/12G-CROSS_HARDWARE_MANUAL_FV1.0.pdf)

* playout case
  * Mac pro 2019
    * ProPresenter: [info](https://www.renewedvision.com/propresenter) [support](https://support.renewedvision.com/hc/en-us/sections/360002412274-ProPresenter)
    * ProVideoPlayer: [info](https://www.renewedvision.com/provideoplayer) [support](https://support.renewedvision.com/hc/en-us/sections/360002436053-ProVideoPlayer)
  * Luminex GigaCore 12: [GigaCore-12-Manual](/Documents/Playout/GigaCore_12_User_Manual-rev-2.8.7.pdf)
  * Blackmagic sdi to hdmi 3g: [manual](https://documents.blackmagicdesign.com/UserManuals/BlackmagicConvertersManual.pdf)

* overlay case
  * Mac mini m1
    * ProPresenter: [info](https://www.renewedvision.com/propresenter) [support](https://support.renewedvision.com/hc/en-us/sections/360002412274-ProPresenter)
  * Echo III Rackmount: [Echo-III-Rackmount-Manual](/Documents/echo_iii_rackmount_ug.pdf)
    * Blackmagic Decklink Duo 2: [manual](https://www.blackmagicdesign.com/nl/welcome/en)
  * Luminex GigaCore 12: [GigaCore-12-Manual](/Documents/Playout/GigaCore_12_User_Manual-rev-2.8.7.pdf)

* admin case
  * Mac mini m1
    * ProPresenter: [info](https://www.renewedvision.com/propresenter) [support](https://support.renewedvision.com/hc/en-us/sections/360002412274-ProPresenter)
  * Echo III Rackmount: [Echo-III-Rackmount-Manual](/Documents/echo_iii_rackmount_ug.pdf)
      * Blackmagic Decklink Duo 2: [manual](https://www.blackmagicdesign.com/nl/welcome/en)
  * Resi Decoder D2010: Contact Resi for questions [support](https://resi.io/support/)
  * Luminex GigaCore 12: [GigaCore-12-Manual](/Documents/Playout/GigaCore_12_User_Manual-rev-2.8.7.pdf)

* Songwords case
  * Mac mini m1
    * ProPresenter: [info](https://www.renewedvision.com/propresenter) [support](https://support.renewedvision.com/hc/en-us/sections/360002412274-ProPresenter)
  * Echo III Rackmount: [Echo-III-Rackmount-Manual](/Documents/echo_iii_rackmount_ug.pdf)
      * Blackmagic Decklink Duo 2: [manual](https://www.blackmagicdesign.com/nl/welcome/en)
  * Art mx225: [Art-mx225-manual](/Documents/AV_SERVER_RACK/om-mx225.pdf)
  * Luminex GigaCore 12: [GigaCore-12-Manual](/Documents/Playout/GigaCore_12_User_Manual-rev-2.8.7.pdf)

* FiberBox
  * Luminex GigaCore 12: [GigaCore-12-Manual](/Documents/Playout/GigaCore_12_User_Manual-rev-2.8.7.pdf)
  * Blackmagic Mini Converter Optical Fiber (12K): [manual](https://documents.blackmagicdesign.com/UserManuals/BlackmagicConvertersManual.pdf)

### Cable types

* SDI: Serial Digital Interface, a standard for transmitting digital signals over coaxial cable. This cable need to be turned while connecting it to the sdi ports. 
![SDI Cable](/av_guide_images/CableConnectors/DSI.jpeg)
* HDMI: High-Definition Multimedia Interface, a standard for transmitting high-definition video and audio signals over a single cable.
  ![HDMI Cable](/av_guide_images/CableConnectors/HDMI-Connector.jpg)
* XLR: A type of connector commonly used for professional audio equipment. It is typically used for microphones and other balanced audio signals. female XLR connectors are used for inputs male XLR connectors are used for outputs.
![XLR Cable](/av_guide_images/CableConnectors/Xlr-connectors.jpg)
* Jack (1/4 inch): A type of connector commonly used for audio equipment. It is typically used for instruments and other unbalanced audio signals.
![Jack Cable](/av_guide_images/CableConnectors/jack.jpg)
* Ethernet (RJ45): A type of connector commonly used for networking equipment. It is typically used for connecting computers and other devices to a local area network (LAN).
![Ethernet Cable](/av_guide_images/CableConnectors/ethernet.jpg) ![Ethernet Cable2](/av_guide_images/CableConnectors/2109-etherCON-NE8MXX-B.png)
* Fiber optic: A type of cable that uses light to transmit data.
![Optical Fiber Cable](/av_guide_images/CableConnectors/fiberoptic.jpeg) ![opticalcon](/av_guide_images/CableConnectors/3868-opticalCONADVANCEDCableConnectorMTP12.png)
* Power (Euro and Tulp): Cables used to provide electrical power to devices. Euro cables are commonly used in Europe, while Tulp cables are commonly used in consumer electronics.
![c13](/av_guide_images/CableConnectors/c13.jpg) ![Power Cable Tulp](/av_guide_images/CableConnectors/tulp.webp) ![twinoppower](/av_guide_images/CableConnectors/twopinPower.jpg)