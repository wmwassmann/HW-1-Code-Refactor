# HW-1-Code-Refactor
Refactoring html code: Horiseon Web Page.

<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">

    <!-- I updated the title of the page to reflect its content to the best of my ability. -->
    
    <title>Horiseon Social Solution Services, Inc</title>
</head>
<body>
    <header class="header">
    
    <!-- This block contains links, so I inserted <nav> tags -->
      
      <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
          <ul>
            <li>    
            <a href="#search-engine-optimization">Search Engine Optimization</a>
            </li> 
            <li>   
            <a href="#online-reputation-management">Online Reputation Management</a>
            </li>
            <li>    
            <a href="#social-media-marketing">Social Media Marketing</a>                     
            </li>
          </ul>  
        </nav>
      </header>
  <main>   
    <div class="hero" alt="Business-Meeting"></div>
    
    <!-- This element was refactored into an article with three separate chapters, thus requiring the use of <article> to encase three <sections> for clarity. -->
    
    <article id="content" class="content">
      <section id="search-engine-optimization" class="search-engine-optimization">
      
      <!-- I also added "alt=" for any of the images and added an "id" because I think that it makes the notation more specific. I'm still researching this point as it's a little confusing.  I seem to not require the "id" in order to make it work, but I keep reading that it can be a good idea to be more specific when it comes to certain images.  Very curious to learn more in class.-->
      
        <img src="./assets/images/search-engine-optimization.jpg" alt= "Search-Engine-Optimization" class="float-left" />
         <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </section>    
      <section id="online-reputation-management" class="online-reputation-management">
        <img src="./assets/images/online-reputation-management.jpg" alt= "Online-Reputation-Management" class="float-right" />
          <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
          </section>
      <section id="social-media-marketing" class="social-media-marketing">
        <img src="./assets/images/social-media-marketing.jpg" alt= "Social-Media-Marketing" class="float-left" />
         <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
      </section>
    </article>    
    
    <!-- This element is less important and more of supplementary material, as well as being specifically a "sidebar, and thus the "aside" tag was needed. -->
     <aside class="benefits">
      <section class ="benefit-cost">
       <img src="./assets/images/lead-generation.png" alt= "Lead-Generation" />
         <h3>Lead Generation</h3>
          <p>
              Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
          </p>
        </section>
      <section class ="benefit-lead" >    
       <img src="./assets/images/brand-awareness.png" alt= "Brand-Awareness" />
         <h3>Brand Awareness</h3>
          <p>
              Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
          </p>
        </section>
      <section class ="benefit-brand">
       <img src="./assets/images/cost-management.png" alt= "Benefit-Brand" />
         <h3>Cost Management</h3>
          <p>
              As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
          </p>
        </section>
    </aside>
  </main>
    <footer class="footer">
      <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
      </footer>
  </body>
</html>


In general, I think this is a better looking script - I'd like to see how my grade turns out, as I don't have a whole lot to reference other 
than what I've absorbed in class and the research I've done during homework time.  I can imagine I'm missing some things here and there
and I'm more curious about those than a good grade. 

I also wasn't sure if you wanted those links in the <"header"> element other than to their corresponding article. They appear to work,
I just got thrown off by seeing the "#" next to the link because that's more of a placeholder if I'm not mistaken?

Anyway, a very fun, very stimulating exercise. 

