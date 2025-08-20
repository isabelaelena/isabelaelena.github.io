<style>
    .banner-container {
        position: relative;
        width: 100vw; /* Full width of the viewport */
        left: 50%; /* Move to the left edge of the viewport */
        right: 50%; /* Counter balance the parent width */
        margin-left: -50vw; /* Pull the banner back to align with viewport edges */
        margin-right: -50vw;
    }
    .banner {
        width: 100vw;
        object-fit: cover;
    }
</style>

<div>

    <div class="banner-container">
        <img class="banner" src="/works_duanyam_banner.png" alt="Duanyam Banner">
    </div>

    <div>
        <h1 class="font-extrabold pt-8">
            Siklus Refill
        </h1>
        <p>
            Some of my works from my time as a product and graphic design intern.
        </p>
        <p>
            2020-2021
        </p>
        
    </div>

    <div class="pt-6">
        <h3>OVERVIEW</h3>
        <p>
            Siklus Refill is an early stage startup that strives to revolutionize how retail is done for the Bottom of the Pyramid. Their vision is to reduce ocean plastic that came from plastic packaging (especially sachets) of FMCG brands that ended up not being managed.
        </p>
        <p>
            They achieve their goals by selling household products without its packaging through mobile refill stations and static refill stations.
        </p>
    </div>

    <div>

    </div>


    <h3>GLIMPSE OF THE TEAM & PROCESS</h3>
    <p>
        I was first part of the Business Operations team under Head of Ops before our Head of Engineering created a tech team, where I then joined. Being part of the Ops team before getting into product development really helped me understand our business models, what we're trying to achieve, and felt existing pain-points in the field.
    </p>

    <p class="font-bold">Initial Product & Tech Team</p>

    <p>
        Our initial team consist of 2 developers (Front-end & Back-end) and a UIUX consultant that worked remotely, as well as Head of Engineering (and myself) that worked full-time at the office for close proximity with the Ops Team.
    </p>

    <p>
        With more people in the team now, this is what our daily tech standup looks like
    </p>

    <p class="font-bold">High-level development process</p>
    <p>
        With a newly developed agile team, a lot of what we do is still getting to know each of our teammates work style and figuring out how much load we can take per cycle; we do most of our sprints in 1 week sprint cycle.
    </p>
    
    <h3>INTO THE DETAILS</h3>

    <p class="font-bold">User Research</p>
    <p>
        As a company that is still trying to find the best business model and piloting, we do user research continuously, dedicating at minimum one day of the week to go into field and see how might we improve our products & services by communicating with our end-users. We have two types of end-users that might benefit from the product that we’re going to build:
    </p>

    <p class="font-bold">Product Roadmap & Timelines</p>
    <p>
        After research and gaining Key Insights, we did Brainstorming Sessions; which leads us in ideating how the product will look like initially and the long-term product vision.
    </p>
    <p>
        Google Sheets for short-term roadmaps and timelining; Trello for long-term roadmaps and idea dumps
    </p>



    <h2 class="font-bold pt-4">Planning with existing technologies</h2>

    <p>
        When our team realized we needed a PoS system, we listed down features of the PoS that are essential that will either make or break, and nice to have features.
    <p>
        "Don't reinvent the wheel, because there are other companies have put in more time and work to develop an ecosystem."
    </p>
    <p>
        So instead, we researched possible alternatives that allowed us to integrate their system with ours. Here I learned about APIs and basic integration.    
    </p>



    <h2 class="font-bold pt-4">Database Structures</h2>

    <p class="pt4">
        Our team used PostgreSQL for our mobile application database and data warehouse. Because of how prone to change our operations are and the quite complicated relationship between entities, our team had to be flexible to cater to any last-minute improvements.
    </p>


    <h2 class="font-bold pt-4">User Flows</h2>
    <p>
        User Flow Diagrams not only help us visualize user's supposed experience when interacting with our app, but also for easier communication between product, ui/ux designers, and engineers.
    </p>

    <h2 class="font-bold pt-4">Data & Analytics</h2>
    <p>
        Most of our Data is used for Customer CRM; and because we do not have a data team, we try to at least do basic data analysis to find out about customer habits and behaviors through transaction data (good ol' .csv) or product analytics (Mixpanel)
    </p>
    <p> Some of the questions we like to ask:
        <ul>
            <li>
                User acquisition (total, or per acquisition channel)
            </li>
            <li>
                Conversion rate of each new initiatives after being implemented
            </li>
            <li>
                Most common quantities of products bought
            </li>
            <li>
                User Retention / Churn
            </li>
            <li>
                How long does it take for customers to convert
            </li>
            <li>
                Drop-off Funnels
            </li>
            
        </ul>

    <h2 class="font-bold pt-6">Sprint Tools</h2>
    <p>
        Each Trello card is a user story with acceptance criterias, requirement documents, or even as a means to update the team on what you have to do/are currently doing.
    </p>


    <h3>PRODUCT RESULT</h3>

    <p class="font-bold">Siklus Customer App</p>
    <p>
        Here is what our current build looks like - this video is to showcase to end-users how to register and use our app to help them buy our refill products. Help make the world a better place! Get it on Google Play
    </p>
    <p>
        Highlights:
        <ul>
            <li>
                Shipped first Siklus Customer App
            </li>
            <li>
                Acquired 140 customers across Jakarta area
            </li>
            <li>
                34% conversion rate in the 2 months after deployment
            </li>
        </ul>


    <p class="font-bold">Siklus Business Partner App</p>
    <p>
        Siklus Business Partner App will be used by Siklus Partners in doing their daily operations, such as delivering orders, taking orders, and daily check-ins. This app also works as a tracking & monitoring platform for the Ops team on our partners on daily sales, location, and working hours.
    </p>

    <h3>LEARNINGS</h3>

    <p>
        Difficulties Encountered
        <ul>
            <li>
                Creating a shift in behavior is not as easy as it seems​. Siklus' user acquisition takes up a lot of time and effort because end-users are comfortable with what they have been doing.
            </li>
            <li>
                Influence from communities play a very important role in decision making
            </li>
        </ul>

    <p>
        Key Takeaways
        <ul>
            <li>
                As this is my first experience on building a digital product, it taught me the end-to-end process.
            </li>
            <li>
                The importance of understanding not only the scope of product, but also how the business operates as a whole.
            </li>
            <li>
                Requirement Planning is a skill, because while thinking about all the possible scenarios that might happen, sometimes users might use our product not as we expected them to.
            </li>
            <li>
                Introduced to agile methodology and basic technical knowledge; such as database structures, APIs, and production environments.
            </li>
            <li>
                Managing and getting data is tedious enough, but the gem lies in analyzing those data to create meaningful insights and creating future actionables.
            </li>
            <li>        
                How to work with and manage a team of remote engineers.
            </li>
        </ul>



</div>