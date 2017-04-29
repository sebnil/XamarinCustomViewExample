# Xamarin CustomView Example

Example project showing how to create a custom control (UIView) with XIB so that it's available in Xamarin iOS designer.
Custom UIView does not render in storyboard, but can be selected from the toolbox window. If you make rendering in storyboard work, please make a pull request and I will merge it into this repo. 
The reason to this example project simply is that I was looking for an example like this but could not find something that was working out of the box. 


Design custom view in xib using Visual Studio or Xcode (less buggy)
![xib](https://github.com/sebnil/XamarinCustomViewExample/blob/master/Readme Images/xib1.png)


CustomView is visible in Toolbox:
![Toolbox](https://github.com/sebnil/XamarinCustomViewExample/blob/master/Readme Images/customview_toolbox.png)


CustomView can be droped into your storyboard:
![Storyboard](https://github.com/sebnil/XamarinCustomViewExample/blob/master/Readme Images/storyboard.png)

Simulator run. View can also be resized/rotated during runtime:
![Storyboard](https://github.com/sebnil/XamarinCustomViewExample/blob/master/Readme Images/simulator_run.png)


## Getting Started

Clone and run .sln in Visual Studio.

### Prerequisites

Visual Studio (Tested on Visual Studio CE 2017)

## Author

* **Sebastian Nilsson** - [sebastiannilsson.com](http://sebastiannilsson.com)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* **Various forum comments in this thread** - *Initial work* - [forums.xamarin.com](https://forums.xamarin.com/discussion/48628/how-to-create-a-custom-control-uiview-with-xib-so-that-its-available-in-xamarin-ios-designer)
* https://developer.xamarin.com/recipes/ios/general/templates/using_the_ios_view_xib_template/
* https://developer.xamarin.com/guides/ios/user_interface/designer/ios_designable_controls_walkthrough/
* https://app.pluralsight.com/