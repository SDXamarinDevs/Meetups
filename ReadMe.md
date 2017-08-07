# San Diego Xamarin Dev's 

## Meetups

All meetups are suitable for participants who are just learning to program and have participants who several published apps under their belt. We encourage participants to come have fun, meet other local developers and try out different facets of Xamarin App development that can help accelerate your app development. Participants will be split into random teams to collaborate on projects. Meetups will be hosted as a team hackathon.

## Prerequisites

Participants should bring either a Windows or Mac laptop that is setup for Xamarin Development.

- Mac users should install [PowerShell](https://github.com/PowerShell/PowerShell).
- Install the dotnet cli. You may get by with the stable release, however there are a lot of fixes in v2 and we recommend that you have the [preview](https://github.com/dotnet/cli/tree/release/2.0.0) installed.
- Install the Prism QuickStart Templates for the dotnet cli. NOTE: This requires v2.0 preview 3 or later. You can get the latest v2.0 build [here](https://github.com/dotnet/cli/tree/release/2.0.0)

```bash
dotnet new -i Prism.Forms.QuickstartTemplates::*
```

- Visual Studio 2017 or Visual Studio for Mac (any edition will work)
- An Azure Account. If you do not currently have a Visual Studio Subscription, you can get free credit for Azure with [Dev Essentials](https://www.visualstudio.com/dev-essentials/).
- A phone/tablet for testing.

## Test Device

You should be able to create a new Xamarin Forms or Xamarin native application, deploy and run it on your device prior to attending the meetup. It can take you some time to get this setup your first time. While you may be able to get by with a Simulator we strongly encourage testing on real devices.

### iOS

Due to the limitations imposed by Apple, if you plan on using an iOS device, you will need to plan on bringing a MacBook with you to the Meetups.

- Install XCode
- Make sure you have registered your device in the [developer portal](https://developer.apple.com/). 
- Check out the help docs from Xamarin on setting up [FastLane](https://developer.xamarin.com/guides/ios/deployment,_testing,_and_metrics/provisioning/fastlane/) so that you can save some time during development.

### Android

Xamarin Forms has a strict requirement on the Android Support Library version if your SDK Build Target is below 7.0. For this reason it's recommended that you have the newest SDK's installed on your machine, and that you target 7.0 or above. This will allow you to have the newer Android Support Libraries bundled in your project.

You should take a look at the [Android Version distribution](https://developer.android.com/about/dashboards/index.html) to better assist you in making decisions of what API level's to install on your machine. That said based on the current distribution you will reach around 97% of Android users by having an App compatible with API 17 - 25.

Be sure to enable the [Developer Options](https://developer.android.com/studio/debug/dev-options.html) on your Android Device.

## Notes

The Xamarin Live Player is in Preview in the Alpha Channel only. It has several known limitations which prevent it from working with most modern apps which rely on Reflection. For this reason it is strongly recommended that Participants not rely on the Live Player for the Meetups.