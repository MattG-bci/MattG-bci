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
  self.languages = ["English", "Spanish", "Polish"]
  self.tools = ["Pytorch", "TensorFlow", "Pandas", "Numpy", "Arduino", "Matlab",  "HTML", "CSS", "Linux (Ubuntu)", "MacOS"]
  self.hobbies = ["Chess", "Gym"]
  
  
 def greet(self):
  print(f"Hello there! My name is Matt, I am {self.age} years old. I am currently a {self.occupation} at {self.institution} pursuing a career in fields of my intersts: {self.interests}.")


 def get_contact_details(self):
  print("Let's keep in touch!")
  return self.linkedin, self.github, self.email
  
 
 def get_more_info(self):
  print("I speak the following languages: \n")
  for idx, lang in enumerate(self.languages):
   print(f"{idx}: {lang}")
  
  print("Moreover, I have experiance with the tools listed below: \n")
  for tool in self.tools:
   print(f"* {tool}")
   
   
```



