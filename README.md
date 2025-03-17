## Hi there 👋
[![Vaunt Community](https://api.vaunt.dev/v1/github/entities/Discovered12345/badges/community)](https://community.vaunt.dev/board/Discovered12345)

- 🔭 I’m currently working on Java
- 🌱 I’m currently learning Java
- 😄 Pronouns: He/Him
- ⚡ Fun fact: I play ice hockey
  
## 📊 GitHub Stat
<p>
    <a href="https://vaunt.dev">
        <img src="https://api.vaunt.dev/v1/github/entities/Discovered12345/contributions?format=svg" width="350" title="Includes public contributions"/>
    </a>
</p>

## 🥇 Achievements
<p>
    <a href="https://community.vaunt.dev/board/Discovered12345/achievements">
        <img src="https://api.vaunt.dev/v1/github/entities/Discovered12345/achievements?format=svg&limit=3" width="350" />
    </a>
</p>










version: 0.0.1
achievements:
  - achievement:
      name: Shooting Star
      icon: <image_url>
      description: Awarded for starring our repository, make a wish!
      triggers:
        - trigger:
            actor: author
            action: star
            condition: starred = true
  - achievement:
      name: Every Bit Counts
      icon: <image_url>
      description: No commit is too small!
      triggers:
        - trigger:
            actor: author
            action: commit
            condition: count() >= 1
  - achievement:
      name: Pull Request Hero
      icon: <image_url>
      description: You're a PR hero, rock on!
      triggers:
        - trigger:
            actor: author
            action: pull_request
            condition: merged = true
  - achievement:
      name: Closer
      icon: <image_url>
      description: Only closers get coffee!
      triggers:
        - trigger:
            actor: author
            action: issue
            condition: closed = true
