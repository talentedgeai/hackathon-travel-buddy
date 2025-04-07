# Problem Statements
1. Tourists (both foreigners and Vietnamese) face challenges in discovering tours of interest and engaging with tour guides or companies.
2. Booking tours and finding nearby accommoedation are often complicated and unclear.
3. Capturing customer preferences through direct interactions is difficult.
4. Leveraging travel history to provide personalized recommendations is under utilized

# Solution:
Travel Buddy application, integrating AI-driven functionalities to address the defined objectives and problem statements. The solution prioritizes WhatsApp as the main platform  as supplementary options for broader engagement. 

Using LLamaIndex framework to incoporate input data such user profiles such as hobbies, location of interests, agency tour packages recommended tours.

Leverage LLM model with internet search to find nearby accomodation/hotels/hostels that is convenient to take the tours

# User Stories

*   As a Tourist, I want to tell the Travel Buddy app the location(s) I'm interested in visiting and the duration(s) I have available, so that it can find relevant tour options for me.
*   As a Tourist, I want to receive tailored tour recommendations directly in WhatsApp based on the locations, durations, and my preferences (like hobbies/past travel), so that I get convenient and personalized suggestions.
*   As a Tourist, I want to use WhatsApp to interact with the travel buddy service so that I can easily ask questions and manage my travel plans on a familiar platform.
*   As a Tourist, I want a simple and clear process to book a tour once I've decided on one so that I don't get frustrated or confused during the booking.
*   As a Tourist, I want to get recommendations for nearby accommodation (hotels, hostels) for a booked tour so that I can conveniently plan where to stay.

# Objectives and Milestones

| Objective                       | Milestone                                                               | Target Completion Date | Status      | Note                                                                       |
| :------------------------------ | :---------------------------------------------------------------------- | :--------------------- | :---------- | :------------------------------------------------------------------------- |
| Personalized Recommendations    | User can input locations & durations                                    | TBD                    | Not Started | Allow multiple locations/durations. Input via app/WhatsApp interface.       |
| Personalized Recommendations    | AI processes input & generates tour recommendations                     | TBD                    | Not Started | Considers locations, durations, user profile (hobbies, history). Use LlamaIndex. |
| Personalized Recommendations    | Send recommendations via WhatsApp                                       | TBD                    | Not Started | Requires WhatsApp API integration.                                         |
| Seamless Tour Booking           | Simple tour booking process                                             | TBD                    | Not Started | Clear flow within app/WhatsApp.                                            |
| Convenient Accommodation        | Recommend nearby accommodation for booked tours                         | TBD                    | Not Started | Leverage LLM with internet search. Triggered after tour booking.           |
| Core WhatsApp Interaction       | Basic WhatsApp interaction for queries/management                       | TBD                    | Not Started | Foundation for other WhatsApp features.                                    |

# AI Model Specific Tasks Progress

| Task                                                   | Current Status | Notes / Adjustments Needed                                  |
| :----------------------------------------------------- | :------------- | :---------------------------------------------------------- |
| Setup LlamaIndex Framework Integration                 | Not Started    | Choose appropriate index structure, configure environment.      |
| Develop Data Ingestion for LlamaIndex (User Profiles)  | Not Started    | Define data format, privacy considerations.                 |
| Develop Data Ingestion for LlamaIndex (Tour Packages) | Not Started    | Define data format, update frequency.                       |
| Develop Recommendation Logic using LlamaIndex          | Not Started    | Querying strategy based on user input & profile.            |
| Setup LLM & Internet Search Integration (Accommodation) | Not Started    | Select LLM provider/model, configure search access.          |
| Develop Accommodation Search & Ranking Logic           | Not Started    | Prompt engineering, result filtering based on tour location. |
| Evaluate Recommendation Model Performance              | Not Started    | Define metrics (e.g., relevance, diversity).                |
| Evaluate Accommodation Search Performance              | Not Started    | Define metrics (e.g., accuracy, proximity).                 |

# Business Model Specific Tasks Progress

| Task                                          | Current Status | Notes / Adjustments Needed                                       |
| :-------------------------------------------- | :------------- | :--------------------------------------------------------------- |
| Define Target Audience & Market Analysis      | Not Started    | Research tourist demographics, competitor analysis.              |
| Develop Partnerships (Tour Agencies/Guides) | Not Started    | Identify potential partners, define collaboration terms.         |
| Finalize Monetization Strategy                | Not Started    | e.g., Commission model, subscription, advertising?             |
| Develop Marketing & User Acquisition Plan   | Not Started    | Channels (social media, ads, travel blogs), launch strategy.   |
| Define Customer Support Process               | Not Started    | How will user inquiries/issues be handled? (e.g., via WhatsApp) |
| Address Legal & Compliance Requirements     | Not Started    | Data privacy (GDPR/local laws), Terms of Service, payment rules. |


