# START
```
docker run -it --rm abhaydandgedocker/ctf-linux:lvl4
```


---
# 🔍 CTF Challenge - Level 4

This time you have an **Nginx service** running on the system.  
Your task is to figure out **what’s wrong with it** and **locate the port** it is running on.  

The content it serves might help you to break this level.  

---

### 🎯 Objective  
- Inspect the running services.  
- Identify the misconfiguration or issue with Nginx.  
- Find the port where Nginx is serving.  
- Explore the served content to progress further.  

---
## 🔑 Hint  

- Nginx usually runs on **default ports** (think 80/443 👀).  Start It first 😉
- But in this challenge, it may be running on a **non-standard port**.  
- Use commands like:  
  ```bash
  ss 

### 📌 Reminder  
Don’t forget to **grade yourself** once you finish:  

```bash
level4 
```
