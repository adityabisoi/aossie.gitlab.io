
## Carbon Assistant

### Idea: Expand and Improve Google Assistant Support

#### Description

Carbon Assistant is a project that aims to bring conversational access to the CarbonFootprint API. Powered by Google Assistant and Amazon's Alexa, Carbon Assistant aims to bring awareness about carbon emissions to billions of people around the world. Learning about the emissions caused by the things around you has never been so seamless and indulging.

The existing Google Assistant Action needs to be improved with new features and optimizations to the existing implementation:

1. Add support for Google Home and similar non-screen device using surface detection APIs. This means that all the responses/answers provided by the Action need to be tailored based on what device it is being used on.

2. The CarbonFootprint API has added new categories last year: Agriculture, Sector, Food  and Land. These new categories need to be supported by the action. The new API is  documented at docs.carbonhub.org

3. The context management and slot filing features are currently available only for Appliances, Vehicles, Trains and Flights categories. Rest of the remaining categories need to be supported which also includes the new categories mentioned in #2.

4. Fix issues with [UX] tag from https://gitlab.com/aossie/CarbonAssistant-Function/issues, These issues describe how the responses given by the Assistant Action do not follow certain UX guidelines given by Google. How those issues can be fixed is also given in the issue description.


#### Requirements

For this project, we are looking for a student:

- The candidate needs to have a good grip with Node.js 

- Experience working on a Google Assistant Action is a plus.

- Knowledge of RESTful web APIs.

#### Prerequisites:

Candidates are required to demonstrate that they are able to deploy the existing Google Assistant Action.

#### Deliverables:

A fully functional and well tested v2 of the CarbonFootprint Action with above 4 requirements completed, well-tested and merged into the master branch of the project.

#### Note:

Additional features & improvements to the project can also be proposed and will serve as an important criterion for selection.

#### Mentors

Varun Chitre






