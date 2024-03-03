
<p align="center">
  <img src="https://urban-forage.s3.amazonaws.com/logo.png" alt="image"/>
</p>

### Urban Forager: A Culinary Exploration Tool

Urban Forager is not just a restaurant finder app; it's the culmination of a journey in technology and a passion for gastronomy. Conceived initially during my time at General Assembly, the idea was simple yet ambitious: to create a tool that helps food enthusiasts discover and explore restaurants with ease. Back then, as a project concept, it was known as [Chef's Kiss](https://thechefskiss.netlify.app/). However, limited by the skills I had at the time, it remained just a seedling of an idea.

Post-graduation, my commitment to coding daily has not only honed my skills but has also allowed me to revisit my original idea with fresh eyes and advanced capabilities. Over a focused development period of 10 weeks, Urban Forager was meticulously crafted, embodying both my personal growth and the evolution of my initial concept.

### What Sets Urban Forager Apart?

* Elegant and Professional Interface: The design ethos for Urban Forager was clarity and professionalism. The goal was to create an interface that is not only aesthetically pleasing but also intuitive and user-friendly.

* Robust Backend Integration with APIs: At its core, Urban Forager leverages the power of multiple APIs. The integration with Mapbox API provides a seamless and interactive visualization of restaurant locations. Meanwhile, the Yelp Fusion API is instrumental in fetching up-to-date and relevant restaurant information.

* Efficient Caching System: Recognizing the importance of performance and cost-efficiency, Urban Forager implements a caching mechanism. This significantly reduces the frequency and cost of API calls, enhancing the overall user experience.

* Secure User Authentication with Auth0: User experience is further enriched by the implementation of Auth0. This provides a secure and hassle-free way for users to sign up or log in and personalize their experience, like saving their favorite restaurants and leaving personalized comments about their saved restaurants on their "My Collections" page.

* Fallback Images for a Seamless Experience: I have also addressed the common issue of broken image links in search results. By implementing fallback images, Urban Forager ensures that users always have a visually consistent and pleasing experience.

* Docker and Docker-Compose in Development: In the development environment, Urban Forager utilizes Docker and Docker-compose. This ensures a consistent and isolated environment for development and testing, mirroring production settings and reducing the "it works on my machine" syndrome.
  
* Image Hosting on AWS: In the current setup, all images on Urban Forager are hosted on AWS, ensuring fast and reliable access to media resources.
  
* Accessible Contact via Email Form: Understanding the importance of user feedback and open communication channels, an email form is integrated into the contact page. This allows users to effortlessly reach out with their feedback, questions, or concerns, ensuring that Urban Forager continues to evolve in line with user needs and expectations.

* User-Friendly Error Handling: To maintain a consistent and smooth user experience, Urban Forager includes a dedicated error page. This ensures that if users encounter a broken link or navigate to a non-existent page, their experience remains uninterrupted and guided, thereby reducing frustration and enhancing overall usability.

* Dual Search Functionality for Enhanced Discovery: Urban Forager's search capability is thoughtfully designed with two distinct search bars. The first is dedicated to cuisine types or restaurant styles, enabling users to explore based on their culinary preferences. The second search bar focuses on location, allowing for geographically specific searches. This dual approach empowers users to tailor their search with precision and ease.

* Automatic Location Detection: Embracing convenience and intuitive use, Urban Forager also features an automatic location detection feature. By default, the app can find the user's location, streamlining the search process and instantly providing relevant nearby restaurant suggestions. This feature is particularly useful for users who are exploring new areas or are on the move.

* Future Expansion with AWS: While Docker is not currently used in the production environment, there are plans to deploy the containerized application via AWS. This move aims to leverage the scalability and reliability of AWS services.

Urban Forager is more than just an app; it's a testament to continuous learning and a commitment to creating something both useful and delightful. It represents a significant leap from Chef's Kiss, both in terms of technology and user experience. Whether you're a foodie in search of your next culinary adventure or a curious explorer in the city, Urban Forager is your go-to guide.

#### Access the app here: [Urban Forager](https://urban-forager.netlify.app/)
