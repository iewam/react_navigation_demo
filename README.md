# react_navigation_demo

- 安装矢量图标库

  ```
  yarn add react-native-vector-icons
  或者 
  npm install --save react-native-vector-icons  
  ```
    - iOS 配置
        
        info.plist 中添加
        ```
        <key>UIAppFonts</key>
        <array>
          <string>AntDesign.ttf</string>
          <string>Entypo.ttf</string>
          <string>EvilIcons.ttf</string>
          <string>Feather.ttf</string>
          <string>FontAwesome.ttf</string>
          <string>FontAwesome5_Brands.ttf</string>
          <string>FontAwesome5_Regular.ttf</string>
          <string>FontAwesome5_Solid.ttf</string>
          <string>Foundation.ttf</string>
          <string>Ionicons.ttf</string>
          <string>MaterialIcons.ttf</string>
          <string>MaterialCommunityIcons.ttf</string>
          <string>SimpleLineIcons.ttf</string>
          <string>Octicons.ttf</string>
          <string>Zocial.ttf</string>
        </array>
        ```
        cd ios 目录下执行 pod install
      
     - Android 配置 
        
        Edit android/app/build.gradle ( NOT android/build.gradle ) and add the following:
        
        `apply from: "../../node_modules/react-native-vector-icons/fonts.gradle"
`
        
- 运行Android模拟器
    
    `emulator -avd Nexus_5X_API_29_x86  或 emulator @Nexus_5X_API_29_x86` 
