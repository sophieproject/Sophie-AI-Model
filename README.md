# Sophie's AI Model
This is the RASA model for Sophie's AI.
It includes the intent files, the story outlines, and other files needed to train a RASA model.

RASA uses Google's Tensorflow to train AI models, which is the main reason why we chose it.

After installing RASA (`pip3 install rasa` OR `pip install rasa`) run `rasa train` and then `rasa run --enable-api`

The default port should be 5005, after that, running Sophie's main code will result in the bot going online. Without this AI Model, it will fail.

We recommend using Cronjobs to automatically train the AI, and starting the AI **before** starting Sophie.
