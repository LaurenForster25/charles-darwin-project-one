# Charles Darwin: A Journey that Shaped Evolutionary Biology
In this website, there is a rich timeline of Charles Darwin's history. The site centres around how Darwin became one of the greatest scientists to influence the thought of evolution throughout the past 200 years. It is a focus on the man himself and shines a spotlight on the most pinnacle parts of his life that lead to his incredible theory of evolution. 
The site is targeted towards people of all ages, who have taken a particular interest in biology and it's history, whether that be for studying purposes or simply to educate themselves later in life. 
This site will be useful for people looking to find out about the key stages of his life in specific regards to his work as a naturalist. It will also be useful to those wanting to understand the origins of the theory of evolution and the process that Darwin went through to become a successful theorist and publisher.

## Features

Navigation Bar
  - The fully responsive navigation bar provides links for each page of the website and is located on every page. The nav bar is accessible to the user throughout each web page as they scroll down. 
     - This allows users to travel quickly to anywhere on the site and helps them navigate to a particular piece of information quickly instead of having to scroll up and down multiple times.
Footer
   - The footer contains a Copyright note. As this is a historical website and not a wesbite encourgaing the use of a product, I have not included social media links.
      - The footer is included in all of the pages of the website which creates a more uniform design.
     
### First Page

Introduction and Starting Image
  - The introductory paragraph provides a brief overview of what information the website contains.
    It gives the user a quick glance at what they will be reading about and whether they have found a site with the right information for them.
  - There is also an image of Darwin next to a sketch of the finches he encountered in the Galapagos. 
    The image provides a colourful start to the site, enticing the user and helps to break up the large chunks of text.

![Image of Darwin and a sketch of the finches he later became famous for.](assets/css/images/charles-darwin-and-finches.webp)

Historical Overview
  - This paragraph details Darwin's early life, mainly through his varying education and leads right up until his voyage on the HMS Beagle.
     - This information ensures that there is a sufficeint amount of detail regarding his personal life and helps users undertsand how the stages of his life connected.
  
Darwin's Years of Travel
  - This paragraph provides information on the places he visited while on his voyage, as well as higlighting key discoveries on his travels.
     - These are vital pieces of information because they link Charles Darwin as a ordinary man, to the success he had with his theory of evolution. It highlights the two main targets of the website coming together.
  - There is an image of the route the HMS Beagle took during the time it was sailing.
    - This imagine provides a visual aid to users reading about the journey.

![Image of the route the HMS Beagle sailed](assets/css/images/charles-darwin-voyage-route.webp)

### Second Page 

Darwin's life after the HMS Beagle
  - This paragraph focuses on how Darwin used his findings once back in England and also how he advanced in his career.
     - This information is vital to the user as it recognises the start of his career as a biologist and how that impacted his later accomplishments.

Darwin's Finches
  - This sub-section provides a youtube video of Darwin's finches. Descirbing the differences between the specimens Darwin found and the impact that had on his theories.
     - The youtube video is a brillaint additon to the website as it provides another form of learning for the user and breaks up the large chunks of text.

Darwin's First Book
  - This paragraph describes the process Darwin went throught to get his first book published. (The Origin of Species by means of Natural Selection).
     - This is quite possibly the most important part of the site becasue this part of Darwin's life is what changed the historical thought of evolution forever. It provides the user with very relevant information in regards to the purpose of the site.

Links to Other Sites 
  - This section provides a brief description of other information the users might like to pursue as well as providing links. The information is relation to the wesbite's content.
     - This will help the user go further in the research if they so wish, without enforcing all of that extra information on them in this site.

### Third Page

Further Research Suggestions
  - This section provides the names of other important figures in the history of evolutionary thought.
    - This allows the user to explore beyond the life of Charles Darwin and branch off further into the history of biology.
  
Newsletter
  - There is a chance for users to sign up to the 'Everyday Evolution' Newsletter if they so wish.The form allows users to enter data into the fields and submit the form.
    - This adds an extra layer of user intercativity to the website.



## Features to Implement in the Future
  - It would be a good idea to add in a background image on the third page of the website to bring some more vibrance to the design and increase user interactivity. This would also be a great way to encourage more people to sign up to the newsletter and would provide users with a visual aid rather than just the text.
  - More images could be used to increase the complexity of the design as oppose to just having blocks of colour.

## Testing


### Interesting bugs that have been fixed

 - Throughout the website design, I have coded a lot of navigation links. At the start of the project I only had one page for the enitre site and decided to create a nav bar that linked to each paragraph on the page. When I first created these links not all of them would send me to another part of the page, after looking at the code I realised that I had not added the hashtag symbol to all of the link values.
 - Later on in the website design I had created three pages containing different content for the site. Therefore the navigation bars had to be adjusted. Instead of having seven navigation links to each paragraph I created three links, one for each page. At first these links would not take me to the different parts of the site when I opened them up in the browser and I could not figure out the problem  by simply looking at the code. I searched the problem on Google and found that I had kept the hashtag symbols in for the new values, when hashtags are only used for links on the same page as opposed to a different page entirely.

  -The biggest problem I had whilst incorporating images and videos into the site was getting the video to play in the website. At first I used the video element but this was unsuccessful. After a lot of tinkering to the code I realised that the problem wasn't the code itself but that the video link was not compatible with the element that I was using. I then used ChatGPT to figure out the solution by having it directly look at my code and it provided a solution for me using an iframe element. The iframe embedded the video into the document and it played successfully. This was first piece of code that I had not created myself within the website.
  -I also came across an issue when trying to transfer the HMS Beagle Voyage image into the new website layout. It would not fit down to the size of the site and I used extensive elements in CSS to try and fix this issue, including width percentage, margin adjustments and even adding padding. After many attempts I decided to use ChatGPT again as this tool was the most useful to me when I had an issue with the youtube video. It gave me a solution that combined the elements max-width, height, display, margin-left and margin-right. Whilst also suggesting that I use the '#beagle img' instead of just '#beagle' to address the image in my css code.

## Deployment 

 -In order to deploy the website on GitHub, I followed the steps below:
 1. In the GitHub repository, I navigated towards the settings icon on the top right corner of the page.
 2. From there, I selected 'Pages' from the left-hand side bar.
 3. I ensured that the source was set to 'Deploy from Branch', the Main branch was selected and that the folder was set to Root.
 4. I then clicked save and waited for the wesbite to be deployed.
 5. GitHub then provided me with a URL for the newly deployed website.
-Here is my deployed site: https://laurenforster25.github.io/charles-darwin-project-one/







## Credits

### Code that is not my own  
All of the code used in this project is my own apart from the following code snippets:    

This iframe element which was found on ChatGPT and allowed me to embed a video file into the website.
<iframe width="500" height="300" 
    src="https://www.youtube.com/embed/l25MBq8T77w"
    frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
</iframe>

This css code that helped me adjust the size and positioning of the HMS Beagle Voyage image. This was also found on ChatGPT.
#beagle img {
  max-width: 50%;
  height: auto;
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-bottom:20px;}

### Content 
I created all of the content included in the website, but the information I used was taken from the following open source sites:
* https://www.bbc.co.uk/teach/articles/z7rvxyc
* https://www.britannica.com/biography/Charles-Darwin
* https://www.metropolitan-touring.com/blog/culture/darwin-day-5-fascinating-facts/

I also linked the following pages in my website that users can reach for further information:
* https://www.darwinfoundation.org/en/
* https://darwin-online.org.uk/

### Study Support 

-While I have not been overly communicative during this time due to a personal loss. I would like to thank my cohort leader and the student care team for giving me all the guidance I asked for when completing this project. On my next project I will be sure to use all of the resources available to me and improve my coding skills.
   

