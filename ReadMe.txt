https://github.com/RasaHQ/rasa/blob/main/rasa/core/channels/rest.py#L117

Url above is for the rasa rest from where we can see the output channel

Steps:
1) Copy the custom_channel.py file into your rasa directory
2) copy the custom_channel response in domain
3) go to credentials and add the custom_channel there
5)rasa run -m models --enable-api --cors "*" --credentials credentials.yml --debug
4) enjoy :) 