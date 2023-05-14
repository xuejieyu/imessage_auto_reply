# imessage_auto_reply

- This notebook is to use ChatGPT automatially reply text messages. The original intention behind this project was to mess up with scammers, purely for entertainment purposes. While you are free to use this tool for any purpose, it is important to adhere to all relevant laws and policies, and protocols in romantic relationships :-)

- You can specify your persona in the initial prompt. For example : "Elaine is a middle aged woman living in LA, she works in a resturant as cook. She likes gardening. Her favoriate food is shrimp soup ...... ". Be creative !

- The chatbot will have meomeries for all messages exchnaged during one chat session. 

- 95% of the time it works well and sounds like human. But 5% of the time it will mention it is an AI langurage model or chatbot. I'm still figuring out ways to solve this problem outside of hard coding them.

## How to Start

- Set the environment variable before running this notebook.

  In terminal :

  `OPENAI_API_KEY='your key'  TARGET_PHONE_NUM='your target phone number' jupyter notebook imessage_auto_reply.ipynb`
  
 - The phone number should be in this format:  '+16503204567' 
 
 - You can get your openai api key here (it's free): https://platform.openai.com/account/api-keys
