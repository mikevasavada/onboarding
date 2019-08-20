# ON-BOARDING

The Onboarding module provides you with all the features you need to create that perfect welcome screen, which means there is no need for you to hard code these yourself! Every application needs intro screens and we have made it easy to integrate apis into you app. 

# Customization parameters available 

| Attribute          |      Type     |
| -------------      | ------------- |
| headline*          | String |
| shortDescription*  | String  |
| imageId            | long  |
| imageURL           | String  |
| videoURL           | String  |
| externalURL        | String  |
| enabled            | boolean  |
| featured           | boolean  |
| backgroundColor    | String  |
| backgroundImageId  | long    |
| backgroundImageURL | String  |
| callToActionText   | String  |
| callToActionURL    | String  |
| listOrder          | integer |
| textColor          | String  |
| buttonColor        | String  |
| buttonTextColor    | String  |

#How to try
To use this sample code you should have already registered with AOtomot platform. Once you register you will have your worksmapce name and apik key available, place then in Url.swift file in "workspaceName" and "apiKey" and run your code.
```
struct Urls {

  static let workspaceName = ""
  static let apiKey = ""
  static let baseUrl = "https://\(workspaceName).aotomot.com/api/"
  
  // Onboarding
  static let onboarding = "\(baseUrl)onboarding?apiKey=\(apiKey)"

}
```
# API documentation
You can checkout our api documentation and try them [here](https://docs.aotomot.com/reference/on-boarding-overview) 
