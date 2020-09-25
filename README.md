# UsefullDocs
This repository gather up a lot of useful docs that i use in my daily as programer. Include fonts, tutorials, packs, formatter tools, notes about to solve bugs and errors, tips and millions of similar things.

## :memo: LoremIpsum
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## :iphone: React Native Useful Libs 
:zap: [Custom modal above statusbar](https://github.com/dnsgusttavo/UsefullDocs/edit/master/README.md)</br>
:zap: [Linear Gradient](https://github.com/react-native-community/react-native-linear-gradient)</br>
:zap: [Custom loaders](https://github.com/maxs15/react-native-spinkit)</br>
:zap: [Acess to smartphone camera roll](https://github.com/react-native-community/react-native-cameraroll)</br>
:zap: [Get media shared by another apps](https://github.com/meedan/react-native-share-menu)</br>
:zap: [Awesome customizable video player](https://github.com/react-native-community/react-native-video)</br>
:zap: [Text Input Mask](https://github.com/react-native-community/react-native-text-input-mask)</br>
:zap: [Download media for links](https://github.com/joltup/rn-fetch-blob)</br>
:zap: [Vector Icons](https://github.com/oblador/react-native-vector-icons)</br>
:star2: [Material Design Icon List](https://material.io/resources/icons/?style=baseline)</br>
:zap: [See more inline](https://github.com/kashishgrover/react-native-see-more-inline)</br>
:zap: [Responsive UIs with media query](https://github.com/joltup/react-native-responsive-ui)</br>

## :rabbit: React Native Useful tutorials
:zap: [Add unimodules](https://docs.expo.io/bare/installing-unimodules/)</br>
:zap: [Add admob ads](https://docs.expo.io/versions/latest/sdk/admob/)</br>

## :octocat: Github Useful repositories
:zap: [Emojis](https://gist.github.com/rxaviers/7360908)</br>

## :space_invader: C/C++ Tips/Tutorials
:zap: [How to install GCC on Windows (PT-BR)](https://terminaldeinformacao.com/2015/10/08/como-instalar-e-configurar-o-gcc-no-windows-mingw/)</br>

## :diamond_shape_with_a_dot_inside: Figma Plugins
:zap: [Figma Blobs](https://www.figma.com/community/plugin/739208439270091369/Blobs)

## :link: Design Links
:zap: [Free Ilustrations](https://undraw.co/)
## :beetle: How To Solve Errors
  ### :dizzy: CameraRoll bug
  ##### ERROR:
  Error: Permission denied at Object.promiseMethodWrapper [as saveToCameraRoll] (But Permission for 'write external storage' is granted)
  
  ##### SOLUTION:
  Add android: requestLegacyExternalStorage = "true" on  AndroidManifest.xml (Inside application tag)
  ```xml
  <application android:requestLegacyExternalStorage="true" ... >
  ```
