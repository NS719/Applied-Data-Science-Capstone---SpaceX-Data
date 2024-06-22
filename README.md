# Data Science Capstone Project: SpaceX Launch Data Analysis

## Project Overview
The commercial space age is here, companies are making space travel affordable for everyone. Perhaps the most successful is SpaceX. SpaceX’s accomplishments include:
- Sending spacecraft to the International Space Station.
- Starlink, a satellite internet constellation providing satellite Internet access.
- Sending manned missions to Space.

One reason SpaceX can do this is the rocket launches are relatively inexpensive. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each. Much of the savings is because SpaceX can reuse the first stage. If it can be determined whether the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

These diagrams from Forest Katsch, a 3D artist and software engineer, will help understand the scale and components of the Falcon 9. 
![Components of the SpaceX Falcon 9 in its fairing configuration](https://zlsadesign.com/infographic/vehicle/spacex-falcon9-components-tall.jpg "Falcon 9 Components")
The payload is enclosed in the fairings. Stage two, or the second stage, helps bring the payload to orbit, but most of the work is done by the first stage. The scale of the first stage is shown here, next to a person and several other landmarks.
![SpaceX Falcon 9 Scale](https://zlsadesign.com/infographic/vehicle/spacex-falcon9-scale-tall.jpg "Falcon 9 Scale")
This stage is quite large and expensive. Unlike other rocket providers, SpaceX's Falcon 9 can recover the first stage. Sometimes the first stage does not land or may crash. Other times, Space X will sacrifice the first stage due to the mission parameters like payload, orbit, and customer.

In this capstone project, you will take the role of a data scientist working for a new rocket company, Space Y that would like to compete with SpaceX. Your job is to determine the price of each launch by gathering information about Space X and creating dashboards for your team. Instead of using rocket science to determine if the first stage will land successfully, you will train a machine learning model and use public information to predict if SpaceX will reuse the first stage, thus determining the cost of a launch.
This project is a graded capstone course [Applied Data Science Capstone](https://www.coursera.org/learn/applied-data-science-capstone) by IBM, final course in the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science).
