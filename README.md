# MetaAds Controlled Stream

## Introduction

This document is an instruction on how to work with **OBS Studio** and create a *controlled stream* in detail.

## 1. Opening the [**MetaAds**](https://metaads.team/main/) website

* Connect
* Click on Advertiser
* Click on My Creatives

## 2. Creating a *Controlled Stream*

![Image](./media/1.png)

* Click on Add Stream

![Image](./media/2.png)

* Click on Select Metaverse
* Click on Decentraland
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

* Open MetaAds on My Creatives page

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