**Ohmnic**

```python
class Ohmnic:
    def __init__(self):
        self.name = "Ohmnic"
        self.role = "CyberSec engineer / Python dev"
        self.os = "Linux"
        self.stack = ["Python", "Bash"]
        self.interests = ["CyberSecurity","Linux systems", "DevOps", "Radio engineering",]

    def hello(self):
        return "Welcome to my GitHub"

if __name__ == "__main__":
    me = Ohmnic()
    print(me.hello())


