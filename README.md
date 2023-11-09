# MetaAds Controlled Stream

## Introduction

This document is an instruction on how to work with **OBS Studio** and create a *controlled stream* in detail.

## 1. Opening the [**MetaAds**](https://metaads.team/main/) website

* Connect
* Click on *Advertiser*
* Click on *My Creatives*

## 2. Creating a *Controlled Stream*

![Image](./media/1.png)

* Click on *Add Stream*

![Image](./media/2.png)

* Click on Select Metaverse
* Click on **Decentraland**
* Click on Next

![Image](./media/3.png)

* Click on *MetaAds* icon
* Upload Preview Image
* Click on Next

![Image](./media/4.png)

* Enter Name
* Enter description
* Enter External target link (is optional)
* Click on Save

![Image](./media/5.png)

> <u> EXPECTED STATE </u>: The created *Controlled stream* will appear on the My Creatives tab. Now you need to download **OBS Studio** and finish setting up the stream so that you can launch a *stream campaign*.

## 3. Set up **OBS Studio**

* Open **OBS Studio**

![Image](./media/7.png)

* Click on Settings

* Open **MetaAds** on *My Creatives* page

![Image](./media/8.png)

* Click on your recently created stream

> You need to transfer the settings of the created stream from the MetaAds website to the stream settings in OBS Studio.

![Image](./media/6.png)

* Click on broadcast
* Copy link from *Public stream URL* field and paste in *Server* field
* Copy key from *Private key* field and paste in *Stream key* field
* Mark *Use authentication* 
* Copy login from *Stream login* field and paste in *User name* field
* Copy password from *Stream password* field and paste in *Password* field
* Click on OK

> For your stream, you can add some sources, such as:

![Image](./media/9.png)

* Click on **"+"**

> You can choose any source you want to add

**Capture the input audio stream** - this is the source that will stream your microphone.

**Capture the output audio stream** - this is the source that will stream audio from your device.

**Capturing app audio** - this is the source that will stream the sound of a separately selected application.

**Window Capture** - this is the source that will stream your selected window (application).

**Screen Capture** - this is the source that will stream the entire screen of your device.

**Image** - this is the source that will stream your selected image.

**Slide show** - this is the source that will stream your selected slideshow.

> Let's add several sources for the view (for example: image, capture of the input audio stream and capture of the output audio stream).

In sources click on *Image*

![Image](./media/11.png)

* Enter the Name
* Click on OK
* Click on Review and select Image you want
* Click on OK

> The selected type with the specified name will appear in the list of sources.

In sources click on *Capture of the input audio stream*

![Image](./media/12.png)

* Enter the Name
* Click on OK
* Click and select your device in *Device* field
* Click on OK

> The selected type with the specified name will appear in the list of sources.

In sources click on *Capture of the output audio stream*

![Image](./media/13.png)

* Enter the Name
* Click on OK
* Click and select your device in *Device* field
* Click on OK

> The selected type with the specified name will appear in the list of sources.

## 4. Creating an audience and campaign with Controlled Stream
### **Audience**
![Image](./media/10.png)

* Click on *Advertiser*
* Click on *Audience*
* Click on *New Template*

![Image](./media/14.png)

* Enter Name   
* Enter Description
* Click on *Next Step*

![Image](./media/15.png)
![Image](./media/16.png)
![Image](./media/17.png)

* Click on **"+"**
* Choose your **Controlled Stream**
* Click on *Save & To Rules List*
* Click on *Save & Quit*

![Image](./media/18.png)

> An audience will be created and the message *"The audience has been successfully created"* will pop up.

### **Campaign**

![Image](./media/19.png)

* Click on *Advertiser*
* Click on *Campaign*
* Click on *New Campaign*

![Image](./media/20.png)

* Enter Name
* Enter Description
* Set the start and end time of the campaign
* Select an audience with Controlled Stream
* Click on *Next Step*

![Image](./media/21.png)

* In the rule type, select Exclusive (to take up all the selected time)
* Click on *Next Step*

![Image](./media/22.png)
![Image](./media/23.png)

* Click on **Metaverse** and select *Decentraland*
* Select the *Ad Space* where your stream will be displayed
* Click on *Next Step*

> Next a review of your stream will appear.

* Click on Start Campaign

![Image](./media/24.png)

> The campaign will be created with one of the statuses: *On Moderation*, *New*, *Scheduled*. The message *"The audience has been successfully created"* will also pop up. 5 minutes before the start of the campaign in **OBS Studio**, click on *Start broadcast* and it will appear on the selected *Ad Space*.