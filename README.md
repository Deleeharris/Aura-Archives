# Project Aura: The Aura-Archives
The exciting and sometimes perilous adventures of building and maintaining my self-hosted AI stacks on my PC and MacBook Air. Protecting my digital freedom and privacy at the risk of my limited sanity.

## About Me

### Navy Veteran | Business Grad | Lifetime Learner | AI Enthusiast

I’m a chronically chroniced (iykyk) adventurer with a desperate need for systems. My journey into self-hosted AI started as a productive ADHD procrastination project and turned into a mission to protect digital freedom. 

You may notice that I don’t list computer science or any related fields in my credentials... That wasn’t an accident. I am a Business graduate with an emphasis in Marketing and a background in coaching, teaching, and social media. I’m building this "Second Brain" or "Brain 2.0" to prove that you don't need a CS degree to take control of your digital privacy and do cool things.

### Credentials
* **Education:** B.S. in Business (Marketing) & Graduate Coursework in Communications Management (Public Relations) 
* **Certifications:** Social Media, Coaching, and Teaching
* **Areas of Lack:** What I DON'T have is an extensive background in computer science, machine learning, or programming. 

### Interests
* **Gaming:** Specifically MMORPGs, Open-World RPGs, Simulations, & solo journaling RPGs! 
* **Psychology & Reading:** Anything that helps me understand the "why" behind the "how" or has a deeply entertaining plot (sometimes even if the writing is bad). 
* **Rabbit Holes:** Deep dives that usually end in things like turning my computers into self-hosted servers for my personal AI brain.

## The Mission
I am passionate about making AI accessible and intuitive, focusing on ethical, safe, and **privacy-forward** local solutions. My goal for Aura is to create a second brain to handle my own inability to properly executive function, without giving everything in my brain to companies that don't have my best interests at heart. 

## Quest Log: Aura's Journey
**NOTE** : As mentioned above, I *love/adore/am obsessed with* video games, particularly of the RPG/MMORPG variety. Working toward and accomplishing a goal in those games, whether it's reaching max character level, collecting all of the pieces of a beautiful armor set, unlocking a hard to get mount, or finally defeating a raid boss, releases endorphins, dopamine, and creates a loop that makes you want to keep playing. 
  
Since I've started working on Project Aura (I'm writing this note on 3.13.26, which makes it about 3 weeks), I have played maybe less than a handful of hours of video games. This project has been so fulfilling and so *fun*, that it has almost completely replaced the video game loop for me.  

In describing this project to my friend, who I have played WoW with for years, I mentioned that figuring out how to make things work the way that I want them to, and seeing that happen, before my eyes, on my screen, feels a lot like beating a raid boss. 
 
So, with that in mind, here is my Quest Log:
 
## Realm Status 
Front-End: MacBook Air M4 (OS: Tahoe, Storage: 512GB SSD, RAM: 16GB)
	* Utilizes Obsidian as integrated User Interface for: 
* 🪄 Agent Chat via Copilot Community plugin
* 🪄 Git via Git Community plugin
  
Back-End: MSI Pulse (OS: Windows 11 Pro, Storage: 512GB SSD + 2TB SSD, RAM: 16GB, **GPU:** 8GB VRAM (Dedicated))
* 🪄 Ollama - running as a network-accessible server via Command Prompt
 * * Models: aura:8b (fork of ministral3:8b), ministral3:3b, and nomic-embed-text.
* 🪄 n8n for workflows 
* 🪄 Firecrawl for crawling and scraping 
  
## Loot Obtained So Far
* ✨ Magical Data Processing: I recently obtained a massive cache of 1,439 items from an itch.io bundle that was impossible to sort. I built an n8n workflow that crawled every link, used Aura’s brain to identify the content, and organized it into a structured database. What would have been a 40-hour manual grind became a 1-hour "automated boss fight" of building and debugging.
* ✨ Customized AI Model: A fork of ministral3:8b optimized to run entirely within my MSI's 8GB of VRAM. Responses are super fast, and she has a custom system prompt tuned for specific tasks and personality.
* ✨ The Pastel Portal (UI): All user interactions run through Obsidian. I’ve customized it with dark mode and pastel rainbow accents, it's adorable *and* functional.
* ✨ Privacy, Security, & Portability: My data and apps stay on my hardware. My Ollama server on the MSI handles the heavy lifting via the network, but since Aura’s "brain" lives on my Mac, I can switch to a local instance when traveling without losing capabilities.
 
## Current and Future Quests
* ❗️The self-hosted version of Firecrawl does NOT support Fire Engine features like stealth mode and proxies. I'm thinking about switching to crawl4ai.
* ❗️I originally built Aura completely within n8n with the capability to chat via Signal. I ran into issues giving her the robust memory and "Brain 2.0" I wanted her to have. When I found Obsidian, I realized I could transfer away from a lot of the other tools I had in my workflow at the time, so I want to reintegrate Aura's ability to chat via Signal for when I am away from my computer. 
* ❗️Push n8n workflows to GitHub. 
