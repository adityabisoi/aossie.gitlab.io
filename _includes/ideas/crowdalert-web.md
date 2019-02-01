## CrowdAlert-Web

### Idea: React based Progressive Web App & REST API

#### Description

Crowdalert is a crowdsourced cross-platform progressive web app. Crowdalert lets you view & report incidents around the globe. Crowdalert targets to deliver the right information to nearby people.

The web app needs to be optimized for performance. Check out our [ongoing repository](https://gitlab.com/aossie/CrowdAlert-Web). This year we aim to achieve the following:

1. **Serverside Rendering:** As the web app is served as a single page app, the initial loading time is very high. The delay is very noticeable for slow 2G networks. We want to eliminate the bottleneck using SSR. SSR also leads to better SEO.

2. **Geo-hashing:** In order to serve the relevant users the relevant incidents, we need to linearly search the incidents. With geo-hashing, we can replace the searching with O(1) fetching.

3. **Testing & CI/CD:** We need to test all our frontend using Jest. Tests are also required for the Django components. Also, we need to implement CI/CD.

4. **Replacing Firebase:** Using WebSockets & any NoSQL DBMS we want to eliminate our Firebase dependancy.

#### Requirements

For this project, we are looking for a prospective student who can work on the REST API & A PWA based frontend.

- The student should be able to work with React, Redux & RxJS. Should be able to design UI following the material design conventions. Should have a decent understanding of CRUD concepts. Working experience with firebase is favorable.


#### Frameworks

- React, Redux, RxJS
- Django, Django Rest Framework
- Jest

#### Mentors

Bruno Woltzenlogel Paleo, Joydeep Mukherjee