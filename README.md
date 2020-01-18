# Weather Forecast Application Challenge
Inspired from [this article](https://daveceddia.com/react-practice-projects/#weather-app). Sounded like it would be fun.

## Overview
The challenge is going to be broken into three phases. Each phase should add to the complexity of the project/also hopefully
make you use a different piece of React's built in functionality (props, states, etc.)

***

### Phase 1
The first phase of the project is comprised of setting up the application itself, and creating the basic components that will make up the application itself. 

#### Project Setup
I recommend just using [Create React App](https://github.com/facebook/create-react-app) so you can avoid the potential time sink that is getting build processes and a local environments setup. If you want to configure your own environment and build processes more power to you.

#### Interface
Once you can spin up a local instance of the app, we can move on to the actual development piece of this challenge. For this initial interface we are going to just generate a random weather forecast that is comprised of five weather cards. The dates and
weather forecast can be statically set for this phase.

Each card should contain:

- The date
- An icon to indicate the weather
- The high temperature
- The low temperature.

Outside of those requirements, you can structure the interface and weather cards however you want. I won't judge you on appearances,
I am the furthest thing from a designer.

***

### Phase 2
For the second phase, we are going to replace the static five weather cards with dynamically generated ones that are "scrollable". Initially when you load up the application you should see five weather cards along with an inactive "Previous" arrow and "Next" arrow. You should be able to click the next/previous arrows and go to the next five cards or previous five cards respectively. After you get the Next/Previous arrows functional, you should use Moment to make sure the application is using actual dates when clicking the Next/Previous buttons.

***

### Phase 3
The final phase man, way to go broh. For this last phase we are going to be integrating with an external API of some kind to get actual weather forecast data. The national weather service has an API that I know of [located here](https://www.weather.gov/documentation/services-web-api). If you have a preferred API go ahead and use that, I don't care.

***

### Extra Work
If you want to go above and beyond. Implement some tests for you application. If you chose to use Create-React-App then it includes support for testing out of
the box using Jest.

Potential things to test:
- Snapshot tests for your weather cards.
- Testing the handling of the 3rd party Weather Forecast API that was used.
- Navigating through the scrollable weather cards.

## Icon credits
If you are doing this challenge feel free to use whatever icons/images you want. I found some cool ones on [Flaticon.com](https://www.flaticon.com/authors/freepik).

### Thank you based Freepik for the icons.
The icons I'm using were created by [Freepik on Flaticon.com](https://www.flaticon.com/authors/freepik). They will only be used on local machines and won't be used on any kind of production environment. If you want to use the same ones as me, let me know and I can send you a link/zip of the icons. I don't know if I'll be breaking any copyright laws by hosting them on here so I'm just being safe.

Don't sue me please.
