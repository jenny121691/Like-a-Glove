## 💡 Like a Glove 

### Introduction of the task

  For this task, I chose an ML-based challenge rather than a web-oriented one. In my other write-ups, I had previously performed web app vulnerabilities, but for this one, I wanted to challenge myself further by understanding how machine learning models could be manipulated or attacked. 
  
  The aim was to go beyond the traditional web exploitation and gain experience on analyzing and attacking an ML model through code-based interactions. I learned to think more as a developer and an analyst than just as a pentester.

### 🛠️ Process of solving Like a Glove

1. We download the file for the traget machine i renamed the file into challenge.txt.

   This is the file that it shows after i download it.

   <pre>
     
     Like non-mainstream is to efl, battery-powered is to?
     Like sycophancy is to بالشهادة, cont is to?
     Like беспощадно is to indépendance, rs is to?
     Like ajaajjajaja is to hahahahahahahahaahah, ２ is to?
     Like bahno is to arbus, duit is to?
     Like 잡히지 is to ਮੈਂ, 年度第 is to?
     Like usaar is to est-ce-que, ７ is to?
     Like وشعب is to nordeste, rêve is to?
     Like teapots is to glow, ４１ is to?
     Like run-ins is to biggy, update is to?

   </pre>

   🔍 What i inferred:
     I guess it represent words as vertors, Like A is to B, C is to ?

     I can solve these analogies using vertor arithmetic:

     " B - A + C = D ".

2. The tools and the enviornment that i used:

   I download the "glove.twitter.27B.25d.txt" model, created a main.py script, and get in to the virtual enviornment.
   
   First , we get into the virtual enviornment by the command:

   ```bash
   
   source venv/bin/activate
   
   ```
   
   To download the "glove.twitter.27b.25d.txt" by the following command:

   ```bash
   
   wget http://nlp.stanford.edu/data/glove.twitter.27B.zip
   
   unzip glove.twitter.27B.zip
   ```
   After download the model and get into the virtual enviornment, we need to create a main.py:

   ```bash

   touch main.py

   ```
   ![Screenshot showing GET flag result](./image/Likeaglove_first.jpg)

   ✅ Why I downloaded the GloVe model:

   
   ✅ Why I created main.py:

   
   ✅ Why I used the virtual enviornment:
   

4. 
   
