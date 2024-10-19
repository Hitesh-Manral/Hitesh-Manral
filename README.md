

    class AboutMe:
    def __init__(self):
        self.name = {
            'first': "Hitesh",
            'last': "Manral",
            'pronouns': 'he/him/his'
        }
        self.experience = {
            'curr': 'Building Open Source Projects ',
            'prev': 'currentky Intern at DRDO'
        }
        self.workingOn = 'cvrve'
        self.learning = 'How to build large-scale, high-throughput platforms'
        self.socials = {
            'linkedin': 'https://www.linkedin.com/in/hitesh-manral-04753920b',
            'email': 'hiteshmanral3@gmail.com'
        }

    def greet(self):
        emoji_rocket = "🚀"
        emoji_wave = "👋"
        emoji_code = "💻"
        print(f"{emoji_wave} Hi there! I'm Hitesh Manral, currently working on learn new things and technologies.")
        print(f"I'm building awesome open-source projects  {emoji_code}")
        print(f"Previously, I interned at DRDO. Always learning new things  {emoji_rocket}")
        print(f"Feel free to connect with me on LinkedIn: https://www.linkedin.com/in/hitesh-manral-04753920b")

about_me = AboutMe()
about_me.greet()
