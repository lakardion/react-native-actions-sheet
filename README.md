# react-native-actions-sheet
A Cross Platform(Android &amp; iOS) ActionSheet with a flexible api, native performance and zero dependency code for react native. Create anything you want inside the ActionSheet.
## Run the Example
To run the example app clone the project

    git clone https://github.com/ammarahm-ed/react-native-actions-sheet.git

      

   then run ` yarn or npm install` in the example folder and finally to run the example app:
       
   
    react-native run-android

## Installation

    npm install react-native-actions-sheet --save
or if you use yarn:

    yarn add react-native-actions-sheet

## Usage
For complete usage, see the example project.

## ActionSheet Props
|Name|Type|Description|Default Value|
|--|--|--|--|
|children|React.Component|Your custom component to render inside ActionSheet|`<View/>`
|customStyles|object|Any custom styles you want to add to the container|
|animated |boolean| Enable or disable animation of Modal|`true`
|animationType|"fade" or "slide"| Animation type for Modal|`fade`
|gestureEnabled|boolean| Enable gestures to control ActionSheet|`false`
|bounceOnOpen|boolean| Enable gestures to control ActionSheet|`false`
|bounceOffset|number| Enable gestures to control ActionSheet|`20`
|springOffset|number| Enable gestures to control ActionSheet|`50`
|initialOffsetFromBottom|number|Use if you want to show the ActionSheet Partially on Opening. **Requires `gestureEnabled=true`**|`1`
|closeOnPressBack|boolean| Enable gestures to control ActionSheet|`true`
|elevation|number| Elevation of ActionSheet|`0`
|indicatorColor|string| Color of gestureEnabled indicator|`gray`
|overlayColor|rgba string| Color of background Overlay. **Must be a rgba(r,g,b,a)** value|`rgba(0,0,0,0.3)`
|onClose|function| Function Called on Close
|onOpen|function| Function Called on Open

## ActionSheet Methods
ActionSheet can be made visible using its own method only.
```jsx
ActionSheet.setModalVisible();
```
#

### MIT Licensed
