# Ohmnic - Python/Web Developer 🐍💻  

```python
class Ohmnic:
    def __init__(self):
        self.name = "Ohmnic"
        self.role = "Python/Web Developer"
        self.os = "Linux User"
        self.skills = ["Python", "HTML", "CSS", "JS", "Bash"]
        self.interests = ["Scripts", "Telegram Bots", "Websites"]
        self.contact = {"Telegram": "@OhmnicDev"}
        self.loves = "Tea 🍵"

    def say_hello(self):
        return "Hello, world! Welcome to my GitHub."

if __name__ == "__main__":
    me = Ohmnic()
    print(me.say_hello())
