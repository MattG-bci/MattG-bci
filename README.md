``` python

class Matt:
 def __init__(self):
  self.age = 22
  self.occupation = "MSc Applied Machine Learning student"
  self.institution = "Imperial College London"
  self.interests = ["Software Development", "Deep Learning", "Computer Vision", "Neurotechnology"]
  self.linkedin = "https://www.linkedin.com/in/mfgrzybowski/"
  self.github = "https://github.com/MattG-bci/"
  self.email = "mateusz.f.grzybowski@gmaill.com"
  
  
 def greet(self):
  print(f"Hello there! My name is Matt, I am {self.age} years old. I am currently a {self.occupation} at {self.institution} pursuing a career in fields of my intersts: {self.interests}.")

 def get_contacts(self):
  print("Let's keep in touch!")
  return self.linkedin, self.github, email
```



