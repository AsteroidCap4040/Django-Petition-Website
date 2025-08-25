# VoiceWave-Petition-Website using Django Framework
This was my very first project during my bachelor’s degree. Looking back, I’m glad I completed it and learned a lot along the way, but I’ll admit the project structure and certain aspects are… let’s say a little rough around the edges.

During testing, I ran into several issues like:

🐞 Random bugs popping up

🔑 Open API keys

🌱 No proper environment setup

…and more

blah blah the list goes on (Damn i taught website is just HTML/CSS/JavaScript and magic).But nevermind as long i can see and interact with result i won't tamper with code.

The project took me a long time, with plenty of trial-and-error and outside help. Revamping the entire codebase now feels overwhelming, so instead I’m only pushing the frontend folder (which I’m oddly proud of 😅). Along with that, I’ll be sharing the project timeline and screenshots to capture the journey.

### If there’s one thing this project drilled into me, it’s this:  

### **"FUCK MERN STACK x3"** 🚫

---
## 📖 About the Project  

The project is named **VoiceWave** 🌊 (though I was tempted to brainstorm cooler names along the way 😅).  

It is a **petition and community platform** built with Django, designed to let users raise their voices, share stories, and stay updated with current events.  

### 🔑 Core Features  
1. **User Authentication** – Secure login & signup system for users.  
2. **Petitions** – Create, browse, sign petitions, leave comments, and view infographics.  
3. **Stories / Blogs** – Write and share personal stories or blogs, browse others, and engage through comments and upvotes/downvotes.  
4. **News Integration** – Stay updated with relevant topics via integrated news search and reading (powered by [NewsAPI](https://newsapi.org/)).  

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend & Framework:** Python, Django  
- **API Integration:** [NewsAPI](https://newsapi.org/) – for fetching daily news content (Add your API key in static/news.js)

---

## 📸 Screenshots  

### 1) 🏠 Home Page  
- Admin has a special power to **golden upvote** a petition, making it appear on the home page.  
- Displays **top categories** (once a category crosses a certain threshold of petition counts).  
- A placeholder for **trending news** (i didn't do shit about this feature).  

<img width="1919" height="3073" alt="Home Page" src="https://github.com/user-attachments/assets/fbd5169e-bfbd-4d7c-8e99-0b7635e35919" />  

---

### 2) 🔑 Login & Signup Page  
- Simple authentication system for users.  
- Users can create a profile and add personal info.  

![Login & Signup](https://github.com/user-attachments/assets/1e07b12b-f240-475e-881a-2604f5074842)  

---

### 3) 👤 User Profile Page  
- Displays user details.  
- Shows petitions & stories created by the user.  
- Lists petitions signed by the user.  

![User Profile](https://github.com/user-attachments/assets/bbc54435-cd12-4a14-bfe1-c2166e901668)  

---

### 4) 📑 Browse Petition/Story Page  
- Users can **search, sort, and filter** petitions/stories.  
- Click any petition/story to explore in detail.  

![Browse 1](https://github.com/user-attachments/assets/d4fe019a-872a-4df9-afea-b84dfe5d01b1)  
![Browse 2](https://github.com/user-attachments/assets/89e27600-298d-4abc-a835-9aa74800d12b)  

---

### 5) 📌 Petition Detail Page  
- Displays petition details, images, and insights.  
- Users can **sign the petition** (sign count visible).  
- Comment section included for discussions.  

![Petition Detail](https://github.com/user-attachments/assets/ef640ca0-45ca-470b-bb67-a06e0751c0cd)  

---

### 6) 📊 Petition Infographics  
- Data on who signed the petition.  
- Shows signings in the **last 10 days**.  
- **Pie charts** for demographics (age, gender, city).  

<img width="1919" height="2229" alt="Petition Infographics" src="https://github.com/user-attachments/assets/79bce4b2-e255-42eb-945f-790324ae6fe2" />  

---

### 7) 📝 Petition & Story Forms  
- Forms for creating petitions and stories.  
- Includes validation checks & sharing options.  

<img width="1919" height="2843" alt="Petition Form" src="https://github.com/user-attachments/assets/b5ec9afa-d5b1-46bf-bd73-0042b1e5d1c4" />  
<img width="1919" height="2337" alt="Story Form" src="https://github.com/user-attachments/assets/8dd87117-a8fc-4dac-b56f-886f8308132c" />  

---

### 8) 📰 News Section  
- Integrated with **NewsAPI**.  
- Users can **search for news** and click to read the original articles.  

<img width="1919" height="880" alt="News Section" src="https://github.com/user-attachments/assets/6e90f907-a486-4f9f-a6c3-47c688628113" />  


---

## 🙏 Thank You  
This was my **first ever Django project**, and while it’s far from perfect, it taught me invaluable lessons about **web development, frameworks, debugging, and project structuring**.  
A huge thanks to everyone who helped me along the way — tutorials, documentation, friends, and the countless StackOverflow tabs I had open 😅.  

---

## 🚀 Future Scope  
While I don’t plan to revamp the entire codebase right now, here are some ideas if I (or anyone else) ever revisits the project:  

- ✅ Proper environment setup with `.env` files and secure API key handling  
- ✅ Cleaner project structure following Django best practices  
- ✅ Full backend integration (instead of pushing only the frontend)  
- ✅ Improve **news feature** with filtering and live updates 
- ✅ Add notifications for petition milestones (e.g., “100 people signed your petition 🎉”)  
- ✅ Deploy the project on a hosting platform (Heroku, AWS, or Vercel)  

---


 
