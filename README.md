import webbrowser

# Mood to YouTube link mapping
mood_songs = {
    "happy": [
        "https://www.youtube.com/watch?v=ZbZSe6N_BXs",  # Happy - Pharrell Williams
        "https://www.youtube.com/watch?v=Y66j_BUCBMY",  # Good Life - OneRepublic
        "https://www.youtube.com/watch?v=iPUmE-tne5U"   # Walking on Sunshine
    ],
    "sad": [
        "https://www.youtube.com/watch?v=hLQl3WQQoQ0",  # Someone Like You - Adele
        "https://www.youtube.com/watch?v=k4V3Mo61fJM",  # Fix You - Coldplay
        "https://www.youtube.com/watch?v=RBumgq5yVrA"   # Let Her Go - Passenger
    ],
    "energetic": [
        "https://www.youtube.com/watch?v=btPJPFnesV4",  # Eye of the Tiger
        "https://www.youtube.com/watch?v=ru0K8uYEZWw",  # Can't Stop the Feeling
        "https://www.youtube.com/watch?v=OPf0YbXqDm0"   # Uptown Funk
    ],
    "relaxed": [
        "https://www.youtube.com/watch?v=UfcAVejslrU",  # Weightless
        "https://www.youtube.com/watch?v=2Vv-BfVoq4g",  # Perfect - Ed Sheeran
        "https://www.youtube.com/watch?v=QDYfEBY9NM4"   # Let It Be - The Beatles
    ]
}

print("🎵 Welcome to Mood-Based Song Suggester 🎵")
print("Available moods: happy, sad, energetic, relaxed")

mood = input("Enter your mood: ").lower()

if mood in mood_songs:
    print(f"Opening a song for your {mood} mood... 🎶")
    webbrowser.open(mood_songs[mood][0])  # Open first song
else:
    print("Mood not recognized. Try again.")# Repo1
🎵 AI Mood-Based Song Suggester – Suggests songs based on your mood (happy, sad, relaxed, etc.) using simple NLP &amp; rule-based AI.  An AI mini project that recommends songs based on mood keywords in user input.  Smart Song Recommendation Bot 🎶 – Enter your mood, get a perfect playlist!
