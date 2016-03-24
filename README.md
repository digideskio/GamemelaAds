# Gamemela Ads
_Copyright (c) 2016 Funizen Inc. All rights reserved._

The GAMEMELA Ads is ...

_Unity&reg; is a trademark of Unity Technologies._

_Android is a trademark of Google Inc._

_iOS is a trademark of Apple, Inc._

_InMobi is a trademark of InMobi Inc._

## Overview

The GAMEMELA Ads is integration Ads of UnityAds, InMobi, GoogleAds.
* Banner
* Interstition
* RewardedVideo

All features are available on Android.

Features:

![](docs/images/Gamemela Logo.png "")

GAMEMELA Ads SDK
=========

introduce GAMEMELA Ads
-----------------------

1. Download the package from [GAMEMELA Ads download site][1]
2. Export to your Unity project.

Usage
-----------------------
### Namespace
	using GamemelaAds.Unity;

### Settings
    // Unity
		Settings.unity.androidGameId = "xxxxxxx";
		Settings.unity.androidInterstitialPlacementId = "xxxxxxxx";
		Settings.unity.androidRewardedPlacementId = "xxxxxxxx";

    // InMobi
    Settings.inMobi.accountId = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx";
		Settings.inMobi.bannerPlacementId = 000000000000;
		Settings.inMobi.interstitialPlacementId = 00000000000;
		
    // Google
		Settings.google.adUnitIdBanner = "ca-app-pub-xxxxxxxxxxxxx/xxxxxxxxxxxx";
		Settings.google.adUnitIdInterstitial = "ca-app-pub-xxxxxxxxxxxxx/xxxxxxxxxxxx";
		Settings.google.adUnitIdReward = "ca-app-pub-xxxxxxxxxxxxx/xxxxxxxxxxxx";    

### Initialize
		Ads ads = Xxx.instance;
		
		// Xxx have to replace with <AdsUnity, AdsGoogle, AdsInMobi>

### ShowBanner
		ads.ShowBanner();

### DestroyBanner
		ads.DestroyBanner();

### ShowInterstitial
		ads.ShowInterstitial();

### ShowRewardedVideo
		ads.ShowRewardedVideo();

[1]: https://github.com/gamemela/gamemelaads/archive/latest.zip "latest version of GAMEMELA-Ads"
