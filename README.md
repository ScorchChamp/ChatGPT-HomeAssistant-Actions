<div align="center">
    <img src="assets/logo.png" alt="GPT & Home Assistant Integration" width="200">
    <h2>🚀 Set Up Your GPT with Home Assistant Integration! 🤖</h2>
</div>

# Short step-by-step
1. 🛠️ Create a GPT in ChatGPT
2. ⚙️ Go to configure -> Create new action
3. 📝 Copy the [Home Assistant openAPI schema](https://gist.github.com/ScorchChamp/f10d30459eef5b70253a70a14f2dff1c) into the schema field.
   1. Replace 'YOUR BASE URL HERE' with your home assistant base url (without /api/)
4. 🔑 Add your Long-Lived Access Token as Bearer API Key to Authentication


# Visual step-by-step

## 1. 🛠️ Create a GPT in ChatGPT

<div align="center">
    <img src="assets/step1.png" alt="Step 1 - Create a GPT" width="300">
</div>

## 2. ✨ Give it Some Personality

<div align="center">
    <img src="assets/step2.png" alt="Step 2 - Personality" width="300">
</div>

## 3. ⚙️ Configure New Action

<div align="center">
    <img src="assets/step3.png" alt="Step 3 - Configure" width="300">
</div>

## 4. 📝 Copy OpenAPI Schema

<div align="center">
    <img src="assets/step4.png" alt="Step 4 - OpenAPI Schema" width="300">
</div>

Copy the OpenAPI schema from [this Gist](https://gist.github.com/ScorchChamp/f10d30459eef5b70253a70a14f2dff1c). 

🔧 Remember to replace your Home Assistant base URL in servers.url (without /api/).

## 5. 🔑 Add Your API Key

<div align="center">
    <img src="assets/step5.png" alt="Step 5 - API Key" width="300">
</div>

## 🗝️ Retrieving Your API Key

Navigate to Your Home Assistant Profile.

At the bottom, click 'Create Token'.

<div align="center">
    <img src="assets/apikey.png" alt="API Key Retrieval" width="300">
</div>