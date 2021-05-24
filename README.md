<h1 align='center'>Mobile Sandbox Linked Monorepo</h1>
<h3 align='center'>All-In-One repo with top mobile technologies with examples and language sanbox inside!</h3>

#### Technology stack
- Android
    - MVVM
    - MVC
    - Dagger/Hilt/Koin
    - Retrofit
    - Room
    - Jetpack Compose
- iOS
    - Swinject
    - Stripe
    - MVVM
    - MVC
- React Native
    - React Navigation
    - Redux/Redux-Saga/Reselect/Action helpers
    - React Native Reanimated
    - React Native Gesture Handler
    - Android/iOS Native Modules
    - Native API's
- Flutter:
    - Flutter-MobX
    - BLoC
    - Animations API
- Common
    - GrahQL Clients (ex. Apollo)
    - Firebase services
    - ReactiveX libraries
    - Language sandboxes

#### Some useful scripts (yarn-based)

    //Install dependencies
    yarn dependency %technology-name%:%project-name% 
    
    //Start project in debug
    yarn start %technology-name%:%project-name%
    
    //Build release project
    yarn build %technology-name%:%project-name%

    //Code prettier
    yarn prettier %technology-name%:%project-name%

    //Code style
    yarn lint %technology-name%:%project-name%

Workflow example:
    
    yarn dependency ios:remanga-api
    yarn start ios:remanga-api
    yarn lint ios:remanga-api
    yarn prettier ios:remanga-api
    yarn build ios:remanga-api