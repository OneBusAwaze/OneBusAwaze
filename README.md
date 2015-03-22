# Hack the Commute Hackathon: OneBusAwaze

The purpose of this app is to provide transit riders and users of OneBusAway (OBA) the ability to crowd source issues encoutered with their bus. These issues could include whether a bus is full and not accepting more riders (MVP example), whether the bus is disabled, affected by a reroute, etc. Users will be able to report issues for a given route or stop that will be then be viewable to other downstream riders. Issues will appear attached to buses or routes when viewed at a stop. The report data will may be maintained to allow for analysis or recurring issues in the network and act as feedback for regional transit agencies.  

This application was developed on March 20-22, 2015 for the [Hack the Commute Hackathon](https://codeforseattle.hackpad.com/Hack-the-Commute-2h8AsgMYcB8).

![Home?!](screenshot.jpg)

## Challenge and Approach

The Hack The Commute challenge aims to make:
  -improvements to existing applications
  -new tools to help commuters in any mode or modes of transportation
  -data analysis and visualizations that clarify the big picture 

Our submission will improve an existing application, OneBusAway, as well as provide a new data set that can be used highlight issues with particular routes around the city over time. 

Our approach for satisfying this challenge was to:
- Add a crowd sourced issue reporting feature to OneBusAway 
- Add user profiles and a gamification aspect to entice users to create reports
- Maintain historical reports and accessible backend to allow for analytics and prediction
- Provide a dashboard to see painpoints and reports on a large scale

## Team Members

Our team is comprised of:

- [@bbodenmiller](https://github.com/bbodenmiller) - Ben Bodenmiller - Backend Development
- [@aaronbrethorst](https://github.com/aaronbrethorst) - Aaron Brethorst - iOS/Backend Development
- [@veeseattle](https://github.com/veeseattle) - Vania Kurniawati - iOS Development
- [@phodiep](https://github.com/phodiep) - Pho Diep -  iOS Development
- [@kpham](https://github.com/kpham) - Kevin Pham - iOS Development
- [@shiraissy](https://twitter.com/shiraissy) - Kasuke Shiraishi - UX and Design
- [tonyip.com](http://www.tonyip.com/)Tony Ip- UX and Design
- [@cjtezak](https://github.com/cjtezak) - Chris Tezak - PM
- [@YasharF](http://github.com/YasharF) - Yashar - PM
- Katie Bosch - Backend Development

## Technologies, APIs, and Datasets Utilized

We made use of:

- Sound Transit GTFS Data feed
- OneBusAway iPhone App
- [Parse](https://www.parse.com)
- Future
  - likely Azure backend
  - Traffic data for prediction (Inrix, WSDot)

## Contributing

In order to build and run our app:

1. Check out the [GitHub Page for our Fork!](https://github.com/OneBusAwaze/onebusaway-iphone)


Our code is licensed under the [Apache license](LICENSE.md). Pull requests will be accepted to this repo, pending review and approval.
