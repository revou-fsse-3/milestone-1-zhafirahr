# Project Milestone 1 Installation Guide (Study Case: For Her Society Revamp 2.0)
<p>For Her Society is a non-profit organization engaged in women's empowerment and mental health. For Her Society provides training, support group system and health checks every 1-3 months.</p>
<p>P.S: Actually, this is the latest version of FHS 1.0, it looks simpler than before</p>
<p>If u Curious, click this link
  
  [link](https://fhs-rise-up.placeblog.site/)
  
  </p>

## Development Process
<p>This section will document all the development stages of creating the website: design choices, considerations, development stages, etc. Side note: this website was built using HTML and CSS without any framework or Javascript.</p>

### Content Creation Process

<p>Let's nostalgic a bit about the reason I create this landing page</p>
<p>I came up with this idea because I was reminded of content related to women's empowerment and mental health (started from remembering the "semicolon project" and one part of my life story) and Brainstorming with some friends.</p>

### HTML 
<ol>
  <li>When developing the website, HTML semantic markup was used throughout the header, nav, main, section, article, etc.</li>
  <li>As best as I could, appropriate tags were also used, such as images, links, and other media elements. Hopefully by using this approach, accessibility and maintainability will be improved on the website.</li>
  <li>Actually, I wanna add a carousel, but my RL Stuff is piled up</li>
</ol>

![image](https://github.com/revou-fsse-3/milestone-1-zhafirahr/assets/47013275/23870a87-cd0b-4ea5-8e1e-17d1312ac732)

![image](https://github.com/revou-fsse-3/milestone-1-zhafirahr/assets/47013275/4d772cc8-edab-4095-98c3-4a32c58fd81e)

### CSS
<ol>
  <li>Media queries were utilized to adjust the styling and layout based on the user's device or screen width</li>
  <li>Most of the structures used flexbox were employed to create flexible and responsive designs across mobile, tablet, and desktop.</li>
  <li>For this version, I didn't use dark mode. But in change, I use parallax .</li>
</ol>

![image](https://github.com/revou-fsse-3/milestone-1-zhafirahr/assets/47013275/580f43cf-6d6d-4619-bbf8-d6928f09a5b0)

![image](https://github.com/revou-fsse-3/milestone-1-zhafirahr/assets/47013275/f6199076-676a-4f4e-9735-c7a7397b3fcf)

## Result 

![image](https://github.com/revou-fsse-3/milestone-1-zhafirahr/assets/47013275/87c3eb2d-9442-4967-abde-e66779bb89dc)

### Deployment
<ol>
  <li>The website was deployed using Netlify, with a custom domain from Niagahoster.</li>
  <li>To ensure seamless integration between Github and Netlify, connect your Netlify account with Github, and choose to deploy from your Github repository. This is done to ensure that Netlify will automatically initiate deployments whenever there are any changes in your GitHub repository.</li>
  <li>Cloudflare, a content delivery network (CDN), was employed to optimize the website's performance and provide enhanced security.</li>
  <li>I used a domain that I've already bought and set up for another website last week. Therefore, what's left is only redirecting it to a different website.</li>
  <li>It can be done by changing the target field to a different website and deleting the old one. I also use CNAME type because it is easier for Netlify.</li>

![image](https://github.com/revou-fsse-3/milestone-1-zhafirahr/assets/47013275/7d64f856-fa1c-4637-ac22-e8e92375b9bf)

 <li>Afterwards add another record with CNAME type, fill the name field with www, and target it to the custom domain website.</li>
  <li>Next, in Netlify, delete the used custom domain on the old website, and click "Add Domain" on your new website in the domain settings menu.</li>
  <li>Follow the instructions to add the custom domain. The finished result will look like this.</li>
  
![image](https://github.com/revou-fsse-3/milestone-1-zhafirahr/assets/47013275/ae4f8ad2-368e-4464-8312-a461b8ef5065)

  <li>Wait for a few minutes, and there we go~</li>

</ol>









