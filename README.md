from world import love

class HumanBeing:

    def __init__(self):
        self.name = "Kaushik Goswami"
        self.username = ["TheKaushikGoswami", "_TheKaushikG_"]
        self.pronouns = ["He", "Him"]
        self.role = "Student"
        self.code = ["Python", "Javascript", "CSS", "HTML"]
        self.askMeAbout = ["tech", "linux", "discord", "discord bots", "anime"]
        self.technologies = {
            "frontEnd" : ["HTML", "CSS"],
            "databases" : ["mongo", "MySql"],
            "misc" : ["heroku", "AWS", "ubuntu"]
        }
        self.currentFocus = "Building Open-Source Discord Bots"
        self.funFact = "नातिक्रान्तानि शोचेत प्रस्तुतान्यनागतानि चित्यानि| 🎴"

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")

me = HumanBeing()
me.say_hi()
love.everyone()
