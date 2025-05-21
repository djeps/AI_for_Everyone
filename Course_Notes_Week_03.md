[Course Notes](README.md)

- Steps when building an AI-powered speaker
    - Trigger/wake word detection e.g. "Hey device!"
        - Simple A to B mapping i.e. trigger word detected!
    - Speech recognition e.g. "Tell me a joke please."
        - a more deliberate A to B mapping involving ML where A (the input) is an audio 
          sample and B (the output) is a text transcript of that audio sample
    - Intent recognition
        - another A to B mapping, where the input A is the text transcript from the 
          previous step and the output B is the intent
        - the intent could be thought of as one of a limited set of commands the smart 
          speaker is able to execute
    - Execute the intent/command
        - e.g. select a random joke and output it as an audio
    - These 4 steps/components for the AI pipeline for the project, and it won't be 
      uncommon that there's a separate team responsible for the development of each 
      component of the pipeline
    - The last component may be just one from a set of predefined commands (one command = 
      one program) the smart speaker is able to perform
- Steps when building a self-driving car
    - Sensory input (vision/radar/LiDAR or a combination) i.e. how the self-driving car 
      will perceive the environment
        - Additional positional input: GPS and/or maps
    - Detect subjects e.g. cars and/or pedestrians (or other subjects participating in 
      traffic)
        - Using ML to map A to B i.e. images as inputs to labels as output (cars and/or 
          pedestrians and/or other) with positional coordinates (relative to our 
          self-driving car)
            - Using Supervised Learning (or SL) and a selection of cameras (front, back, 
              side) and other sensory input
            - Cars and pedestrians might need an additional AI chained component e.g. 
              trajectory prediction i.e. where the subject might be after a certain elapsed 
              time
            - Additional object detection components
                - Lane detection
                - Traffic lights and signaling detection
                - Obstacle detection
    - Motion planning
    - Steering (angle), acceleration, braking
- AI transformation playbook
    - Start executing pilot projects in order to gain momentum
        - The project do not have to be overly complex but enough to 'get your feet wet' or 
          'get the feel about AI'
        - The initial project doesn't need to be something that brings value to the company
        - It's far more important that it's a successful first time AI project
        - Preferably showing traction (e.g. that it's going in the right direction) usually 
          within 6-12 months
        - It could be completely outsourced or in-house, but eventually building a 
          successful in-house AI team will become a must
    - Build an in-house (internal) AI team
        - It only makes sense to have this as a separate (business) unit within an 
          organization
        - This team would prove essential in supporting all other BUs (business units) in 
          their AI enabled/driven projects
        - But it could also be responsible for working on one common AI platform with each 
          individual BU might simply not be able to deal with
    - Provide broad AI training
        - from all levels of the company and not necessarily technical or engineering people
        - at executive level (what benefits AI might bring and create future business 
          value, drafting an AI strategy)
        - at divisional level (technical due diligence, resource allocation)
        - at engineering level (build and ship AI enabled products)
    - Develop an AI strategy
        - Gain business advantage from using and incorporating AI
        - Strategic data acquisition
        - Unified data warehouse
        - Creating network effects with platform advantages (AI here may be an accelerator)
    - Develop internal and external communication
        - Building investor and government relations (e.g. AI is becoming big in healthcare 
          which is a highly regulated sector and building good relations with government 
          officials may be paramount to the success of a project of AI in healthcare)
        - Talent recruitment
        - Education (users and consumers etc.)
- AI use cases
    - Object classification/recognition algorithms
      - Capable of identifying specific classes from a given set of images (e.g. we feed 
        the model a series of images of different animals and the algorithm is able to 
        detect whether a certain image is that of a dog)
    - Object detection algorithms
      - Not merely classifying but also detecting the exact position of a certain class of 
        objects in a photo of a given set of photos
    - Image segmentation algorithms
      - Identifies a precise boundary around a detected object i.e. all the pixels that 
        belong to a certain class (a car for example)
      - Especially useful in healthcare when analyzing a patient's (e.g.) X-rays
    - Tracking algorithms
      - This basically is object detection but repeated with each frame of a given video 
        feed (so the input here is a video feed and not an image or a photo!) so the 
        position of a detected class/object is updated with each video frame
    - Natural Language Processing (NLP)
      - Text classification (given an input text e.g. an email, output whether the given 
        email is spam or not)
          - Sentiment recognition (whether a restaurant review was positive/negative and 
            how many stars if any)
    - Information retrieval (web engines for example)
    - Name entity recognition (given a text as input, identify all personal names in the text sentence)
    - Machine text translation
    - Word or part-of-speech tagging (tag all e.g. nouns, pronouns, verbs, adjectives in a given sentence)
    - Text-to-speech
    - Robotics (perception, motion planning)
    - Unsupervised Learning (learning similar to how humans learning with much fewer data)
    - Transfer Learning (apply an existing model on something very similar so that we do not start completely from scratch - e.g. in the human world, when we learn how to drive a car, we don't learn how to drive a golf cart completely from scratch! It's only slightly different but not completely different.)
    - Reinforcement Learning (introduce a reward signal to the AI agent whenever it does well and the other way around and in time it will learn to maximize its rewards)
    - GANs or Generative Adversarial Networks (e.g. synthesize new images completely from scratch)
    - Knowledge Mapping

[Course Notes](README.md)
