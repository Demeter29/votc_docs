# App Setup

There are 2 things you must set up:

* The LLM API connection.
* The ck3 user folder path. 

Both of them are found in the 'Connection' tab of the app, every other tab is optional.

## LLM API Connection

The mod supports Openrouter, Oobabooga's text-gen-webui, OpenAI or any other OpenAI compatible-APIs. The recommended API is Openrouter, because it's the cheapest and the easiest to set up, it even has free options.

### Openrouter

You need to create an account on [openrouter.ai](https://openrouter.ai).

* Create a new API key [here](https://openrouter.ai/settings/keys) and paste it into the app.

* Find a model you like at [openrouter.ai/models](https://openrouter.ai/models) and also paste that into the app.

**Recommended starting models:**
 * **free:** `nousresearch/hermes-3-llama-3.1-405b:free` 
 (**note:** There is a daily limit for free models, after which you won't be able to use them anymore)
 * **paid:** `nousresearch/hermes-3-llama-3.1-70b`



!!!
Make sure to test the API connection with the **Test Connection** button!
!!!

## CK3 user folder path

In order for the app to be able to communicate with ck3, you need to set the user folder's path to CK3. The app will try the default path, so you don't have to do anything if it's already filled in for you. If it's empty, then you need to manually select it. 

You need to select the root of the CK3 user folder, not the exe or any of the subfolder
**example:** *C:\Users\name\Documents\Paradox Interactive\Crusader Kings III*

## That's it

If you set up everything correctly, then you can start talking to characters ingame via the "talk" interaction.

If you need any help, join [our Discord server](https://discord.gg/yYtS2zFdKw).

## Advanced setup

You can also choose to set up dedicated api connections for actions and summarization. This is useful because some models might work better for text-generation, while others work better for summarization or logical thinking which is important for action detection. You can find them in the 'Actions' and 'Summarization' tab of the app.


