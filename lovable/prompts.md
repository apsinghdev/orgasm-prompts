### Prompt to tease your ui engineer


Create a luxury feeling high-end website, as if you were a senior website designer working with startups for an AI LLM aggregator named t3Dotgg. Do the website design to match the style of the attached image 'reference'. I want the website to feature the following pages: Homepage, About page, contact us page, and a blog page with 4 blog articles already populated.

For the homepage I want it to include a hero section with a title, copy, and get started button centred, with a large image underneath showing the product UI by embedding this code 
import Spline from '@splinetool/react-spline/next';

export default function Home() {
  return (
    <main>
      <Spline
        scene="loading..." 
      />
    </main>
  );
}
:

featured in section, showing logos of publications this app has been in
testomonials section with a scrolling carousel of testimonials, each testimonial should also have the result that the user got
how it works section with 2 set up your AI assistant, ask anything. Each card should have an image on as well
features section with a grid of 4 cards showing the features of the app, with icons on each card
a mission statement section which communicates the mission of the company and why we built the app
pricing section with plans for free, pro and enterprise level plans, with a description on each as well as benefit bullet points and a recommeded badge on the pro plan
FAQ section with some questions
Footer

The website should also have a top navigation with only anchor links to all the sections on the homepage, and not link to any other page. The top navigation should also be sticky and blur the background behind it when you scroll.

Style wise, I want to use Inter as the font, with a light font weight for all text and tight letter spacing for headings. Any text that isn't headings should have a lower opacity. I want to use phosphor icons for the icon library with the light icon weight for all icons.

When a page loads the content should animate in from 0 opacity to 100 opacity and animate up. Also animate all the sections and components with opacity and blur as the user scrolls down the page.

For button styles I want to use a neumorphism 3d style button that glows when you hover. Any cards on the page should have a glassmorphic style with background blur and low opacity.

From the tablet breakpoint down, the navigation menu should collapse to a burger menu, with an animating full height tray style menu coming in from the right and animating out when it is closed.
