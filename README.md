# AR Poster: Interactive Tech Domains with Ship Shooter Game

An Augmented Reality (AR) experience that showcases six major tech domains with interactive audio, text, and visual content. The poster is designed to hover over an actual printed poster image, which serves as an image target for AR content. The application also features a mini rocket shooter game called **Ship Shooter**, along with a score management feature.

## Features

- **Tech Domains Showcase**: 
  - Web2
  - Web3
  - Android
  - AR/VR
  - Machine Learning (ML)
  - Internet of Things (IoT)
  
  Each tech domain is represented by an icon on the AR interface. When clicked, the icon provides detailed information through a combination of audio and text visuals, giving the user an interactive learning experience.

- **Interactive UI**: 
  - The app uses an image target (the actual poster) to trigger AR content. When the user hovers the UI over the poster, the icons and information pop up in 3D, providing a dynamic and immersive learning experience.

- **Ship Shooter Game**: 
  - A mini rocket shooter game where the user can shoot rockets at moving targets. The game includes score tracking to challenge users and improve their gameplay skills.

## Getting Started:

To get the project up and running locally on mobile device, follow these steps:

- Ensure you have an AR supported android device. (for installing .apk file)
- install the .apk file on your android phone (the .apk file can be found in Releases in the repo page).
- bring the photo of Poster(from Prerequisites folder) in front of camera in app while running.

### Setting up Working Environment:

#### Clone the repository

```bash
git clone https://github.com/savia-sark/Ar-Poster.git
cd Ar-Poster
```
#### There are two methods to set up:
###### 1. For directly importing cloned project files from disk:
- Create a new Project(**version 2022.3.27f1 or above**) from disk and select the Ar Poster folder that you have cloned.
- Import the following packages: \
 AR Foundation, 
 Google AR Core XR Plugin (from Package Manager) \
 Vuforia Engine Package (from [Vuforia Engine 10.29](https://developer.vuforia.com/downloads/sdk))in Unity Project.
- Make sure that you have changed the platform to Android in file > build settings.
 And you are all set!

###### 2. For importing unity Package:

- You must have Unity Engine with editor version 2022.3.27f1 or above (if using those for AR/VR components). \
 "Note: it might not work properly on Unity6."
- Create a new project in above version.
- Import the packages: AR Foundation, Google AR Core XR Plugin, Vuforia Engine Package [Vuforia Engine 10.29](https://developer.vuforia.com/downloads/sdk) in Unity Project.
- After all the above steps import .unitypackage from Releases tab: [AR Poster](https://github.com/savia-sark/Ar-Poster/releases/tag/v1.0) from Github Repo.
- Make sure that you have changed the platform to Android in file > build settings.

