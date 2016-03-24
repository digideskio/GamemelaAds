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

1. Download the package from [GAMEMELA Ads stable][1]
2. Import to your Unity project.

Usage
-----------------------
### Namespace
	using GamemelaAds.Unity;

### Settings
		// Unity
		Settings.instance.unity.androidGameId = "xxxxxxx";
		Settings.instance.unity.androidInterstitialPlacementId = "xxxxxxxx";
		Settings.instance.unity.androidRewardedPlacementId = "xxxxxxxx";

		// InMobi
		Settings.instance.inMobi.accountId = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx";
		Settings.instance.inMobi.bannerPlacementId = 000000000000;
		Settings.instance.inMobi.interstitialPlacementId = 00000000000;

		// Google
		Settings.instance.google.adUnitIdBanner = "ca-app-pub-xxxxxxxxxxxxx/xxxxxxxxxxxx";
		Settings.instance.google.adUnitIdInterstitial = "ca-app-pub-xxxxxxxxxxxxx/xxxxxxxxxxxx";
		Settings.instance.google.adUnitIdReward = "ca-app-pub-xxxxxxxxxxxxx/xxxxxxxxxxxx";
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

[1]: https://github.com/gamemela/GamemelaAds/blob/stable/distribution/GamemelaAds.unitypackage "stable version of GAMEMELA-Ads"
