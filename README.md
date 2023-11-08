# Rapid Check

### Introduction
RapidCheck is an automated assessment checking application that addresses the time-
consuming and error-prone nature of manually grading subjective sections in assessment papers. By leveraging Natural Language Processing (NLP) techniques
such as word embeddings, semantic analysis, and similarity scoring, RapidCheck aims
to streamline the grading process, enhance accuracy, and save valuable time for
teachers. 
The application focuses on automating the assessment checking by
measuring the similarity between student answers and the marking scheme solution,
RapidCheck provides accurate and efficient grading. 
The application also offers
flexibility by allowing the addition of custom modules through the provision of relevant training material. RapidCheck has the potential to revolutionize the assessment
process, benefiting both teachers and students by providing automated, accurate, and
timely feedback.

### An idea for a way to solve the problem
Our application focuses on automating the assessment checking for the Physics O/A
Levels module. To accomplish this, we have trained the system using a vast dataset of
over 25 Physics course books. This training has allowed us to create Physics word
embeddings, which play a crucial role in grading the student's answers.
RapidCheck utilizes the word embeddings to evaluate the student's answers by
measuring the similarity between their responses and the marking scheme solution. By
employing this approach, we can provide accurate and efficient grading for the Physics
module.
Moreover, our application offers the flexibility to expand its functionality by incorporating
additional modules. This can be achieved by providing the necessary training material,
such as course material and course books, allowing teachers to customize and extend
the system to suit their specific requirements.

### Algorithm & Datastructures
We are developing an algorithm to automatically grade students' answers using various Python
NLP libraries. Initially, we generated distinct embeddings for each subject using the Genism
Word2Vec model. Then, we transformed these word embeddings into Spacy's model, allowing us
to compute sentence similarity. Additionally, we will experiment with incorporating our
embeddings with Spacy's pre-trained sci-spacy embedding to potentially improve accuracy. We
will also compare our results with those generated by pre-trained BERT embeddings. Finally, we
will compare the output of our algorithm with that of human graders and refine it using
reinforcement learning technique.
Our application heavily relies on a combination of data structures within classes, including
variables, linked lists, and custom objects. These classes interact with JSON data retrieved from
the database, which contains model classes that are specific to our project. The custom objects
are created to organize data in a manner that's relevant to our objective of comparing student
responses with correct answers. This approach enables our application to efficiently evaluate
student performance and provide appropriate feedback.

### Hardware/Software Requirements & Network Protocol

- Operating System: Android Jellybean, v16, 4.1.x or higher, IOS 8 or higher
- Processor: Clock speed of 1 gigahertz (GHz) or higher
- RAM: 1 GB
- Storage capacity: approximately 20 MB (for installing application)
- Internet: Internet connection required
- Screen Size and Resolution: 320x480 pixels or higher
  
Network Protocol

- Https/Http
- Mongo dB wire protocol
- TCP/IPv6
- SMTP
