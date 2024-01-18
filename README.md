# MetaAds Controlled Stream on OBS Studio
## Introduction

    This document is an instruction on how to work with OBS Studio and create a controlled stream in detail.

## 1. Opening the [**MetaAds**](https://metaads.team/main/) website

* Connect
* Click on *Advertiser*
* Click on *My Creatives*

## 2. Creating a *Controlled Stream*

* Click on *Add Stream*

![Image](./media/1.png)
##
* Click on Select Metaverse (1)
* Click on **Decentraland** (2)
* Click on Next (3)

![Image](./media/2.png)
##
* Click on *MetaAds* icon
* Upload Preview Image (This is the image that will be displayed on the site)
* Click on Next

![Image](./media/3.png)
##
* Enter Name (1)
* Enter Description (2)
* Enter External target link (is optional) (3)
* Click on Save

![Image](./media/4.png)
##
![Image](./media/5.png)

> <u> EXPECTED STATE </u>: The created *Controlled stream* will appear on the My Creatives tab. Now you need to download **OBS Studio** and finish setting up the stream so that you can launch a *stream campaign*.

## 3. Set up **OBS Studio**

* Open **OBS Studio**
* Click on Settings
* Open **MetaAds** on *My Creatives* page

![Image](./media/7.png)
##

* Click on your recently created stream

![Image](./media/8.png)
##
> You need to transfer the settings of the created stream from the MetaAds website to the stream settings in OBS Studio.

* Click on Stream (1)
* Copy link from *Public stream URL* field and paste in *Server* field (2)
* Copy key from *Private key* field and paste in *Stream key* field (3)
* Mark *Use authentication* (4)
* Copy login from *Stream login* field and paste in *Username* field (5)
* Copy password from *Stream password* field and paste in *Password* field (6)
* Click on OK (7)

![Image](./media/6.png)
##
> You can add a few sources, such as:

* Click on **"+"**

![Image](./media/9.png)

> You can choose any source you want to show. Let's add some source for the view (for example: image).
##
In sources click on *Image*

* Enter the Name (1)
* Click on OK (2)
* Click on Review and select Image you want (3)
* Click on OK (4)

![Image](./media/11.png)

> The selected type with the specified name will appear in the list of sources.
## 4. Creating an audience and campaign with Controlled Stream
### **Audience**

Tutorial for [**Audience creation**](https://github.com/MetaAdsTeam/audience-creation).
> When choosing a creative for a rule, select your *Controlled Stream*

![Image](./media/18.png)

> An audience will be created and the message *"The audience has been successfully created"* will pop up.
##

### **Campaign**

Tutorial for [**Campaign creation**](https://github.com/MetaAdsTeam/campaign-creation).

> When selecting an audience, select the one that has your **Controlled stream**

![Image](./media/24.png)

> The campaign will be created with one of the statuses: *On Moderation*, *New*, *Scheduled*. The message *"The audience has been successfully created"* will also pop up. 5 minutes before the start of the campaign in **OBS Studio**, click on *Start broadcast* and it will appear on the selected *Ad Space*.
