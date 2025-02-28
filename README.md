# Anime Recommender Beta v1  

## About This Release  
This is the **Beta v1** release of the Anime Recommender. The application fetches a user's **completed** and **plan-to-watch** anime lists from MyAnimeList and analyzes their genres to provide recommendations.  

## How It Works  
1. Enter your **MyAnimeList username**.  
2. The app retrieves your last **10 completed** and **10 plan-to-watch** anime.  
3. It analyzes the **most common genres** from both lists.  
4. Based on genre similarities, it ranks and suggests **5 anime** from your plan-to-watch list.  

## Features  
- Uses **MyAnimeList API** to fetch anime lists.  
- Compares **genre trends** in completed and planned anime.  
- Provides **ranked recommendations** based on genre similarity.  

## Installation  
```sh
git clone https://github.com/yourusername/AnimeRecommender.git
cd AnimeRecommender
pip install -r requirements.txt
python app.py
```

## Notes  
- This is an **early beta version**, and improvements may be needed.  
- The code was not written by me.  

Let me know if you want any changes!
