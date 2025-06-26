📺 Netflix 2.0 Clone
A full-stack, fully responsive streaming platform inspired by Netflix. Built using Next.js, Tailwind CSS, NextAuth.js, TMDB API, and Recoil, this application supports dynamic movie browsing, secure Google authentication, and profile-based plan selection.

🚀 Features
🔐 Google OAuth Login with NextAuth.js

🎞️ Dynamic Movie Sections powered by TMDB API

🖼️ Hero Movie Banner with description and call-to-action

🧩 Recoil-based modal for movie previews

📱 Fully responsive UI styled with Tailwind CSS

🧾 Subscription Plans UI (Basic, Standard, Premium)

📸 Output Screenshots
![image](https://github.com/user-attachments/assets/fa33e75e-adc2-4ace-8d13-31331e96da65)
![image](https://github.com/user-attachments/assets/2d4bc625-aad9-40ff-94cb-b4519b02b42f)
![image](https://github.com/user-attachments/assets/f3a983ca-7677-44ec-9211-d8d53dbe11ae)
![image](https://github.com/user-attachments/assets/65fee24f-0221-4dda-ae0b-b2f0458b9cc5)


🖥️ Sign In Page

Users can log in securely using Google authentication or choose to sign up with email and password.

🎬 Landing Page with Hero Movie

The homepage features a hero banner showcasing a highlighted movie, along with Netflix-style scrollable rows of categorized content.

👤 Edit Profile & Plan Selection

Users can manage their subscription plan visually from this dashboard, displaying pricing and profile avatar.

📧 Membership Invitation

On visiting the app for the first time, users are prompted to enter their email to create or restart their membership.

🛠 Tech Stack
Frontend: React.js, Tailwind CSS

Authentication: NextAuth.js with Google OAuth

State Management: Recoil

Data Source: TMDB API


📂 Installation
bash
Copy
Edit
# Clone the repo
git clone https://github.com/your-username/netflix-clone.git

# Install dependencies
cd netflix-clone
npm install

# Run development server
npm run dev
🔑 You'll need to set up .env.local for TMDB API key and NextAuth credentials
