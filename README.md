I uhm like wasting time ⭐

athlete:- i play badminton professionally and skate some times 

 I do enjoy coding and 3d designing ( still getting better ) n have created over 100+ reps on various stuff involving python, ml, c++ , sql, css and matlab 

import requests

username = "sahasra09"
token = "YOUR_GITHUB_TOKEN"
languages = ["Python", "HTML", "CSS", "JavaScript"]
counts = {lang: 0 for lang in languages}

page = 1
while True:
    url = f"https://api.github.com/users/{username}/repos?per_page=100&page={page}"
    resp = requests.get(url, headers={"Authorization": f"token {token}"})
    data = resp.json()
    if not data:
        break
    for repo in data:
        lang = repo.get("language")
        if lang in counts:
            counts[lang] += 1
    page += 1

print(counts)

I also did create a couple of games and websites ( go to repositories section beside overview on the top, pls dont fork any of them for your benefits )

 Some of my repositories require to be unzipped after being downloaded and can be run through VSC 
 
 

--- july 2021

update:- I dont code anymore and if you want access to any of my reps, you can message me
