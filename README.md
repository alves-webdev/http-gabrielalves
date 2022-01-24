from world import love

class HumanBeing:

    def __init__(self):
        self.name = "Gabriel Alves"
        self.username = ["HTTPAlves"]
        self.pronouns = ["He", "Him"]
        self.role = ["Student", "Teacher"]
        self.code = ["Python", "Javascript", "CSS", "HTML"]
        self.askMeAbout = ["tech", "linux", "discord", "discord bots", "anime"]
        self.technologies = {
            "frontEnd" : ["HTML","React", "Javascript", "CSS"],
            "databases" : ["mongoDB", "MySql"],
        }
        self.currentFocus = "Learning Web Development"

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")

me = HumanBeing()
me.say_hi()
love.everyone()
