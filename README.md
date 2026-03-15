### YouTube search list project
Its simple React project that allows users to search for YouTube videos and display them

#### Steps:
##### 1. Create the Next.js app:
      npx create-next-app@latest youtube-search-app

##### 2. Set up YouTube API key:
- Go to Google cloud console
- Create a new project
- Navigate to APIs and services, then library, then enable YouTube data API
- Go to APIs and services, then credentials and create an API key
- After create API click show key to copy it
- Create a `.env.local` file in the root of your project and add `NEXT_PUBLIC_YOUTUBE_API_KEY = YOUR_API_KEY_HERE`

##### 3. Create the files in this structure:
```
📁 youtube-search-app/
├─ app/
│  ├─ page.tsx            # Main page with search and list
│  ├─ components/
│  │  ├─ search form.tsx  # Search input and button
│  │  ├─ video card.tsx   # Single video card
│  └─ services/
│     ├─ youtube.ts       # API fetch function
├─ .env.local
└─ ...
```

##### 4. Run development server:
      npm run dev
  
##### 5. Open your browser and go to:
      http://localhost:3000

#### Screenshot:
![1](https://raw.githubusercontent.com/HananMurrar/YouTubeSearchListWeb/main/youtube-search-app/result.png)
