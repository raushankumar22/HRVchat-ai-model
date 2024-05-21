<div align="center">
  <img src="https://www.soulhq.ai/assets/soul-ui-logo.webp" height="60" width="60"/>
  <p>SoulAI - chat with AI</p>
</div>

# 💙The Problem statement is -

- Implement an application where the user can chat with an AI model. 
- Beyond this, the user should be able to give some feedback at each stage of the conversation

## 🎀 Do you want it on local ?🎀 

1. clone this repository
- modelbackend
- modelfrontend

2. **For running the Backend**
```bash
cd to modelbackend
npm install
npm node index.js
```

3. **For running the Frontend** 
```bash
cd to modelfrontend
npm install
npm run start
```
4. Ensure the backend server is running before starting the frontend. 
- View the frontend result by opening [http://localhost:3000](http://localhost:3000) in your browser.
- View the backend result by opening [http://localhost:5000](http://localhost:5000) in your browser.

## 🎊Some Glimpse of the App🎊

https://github.com/abhishekrawe/chat-ai-model/assets/65603830/8c7a715f-6e5c-45b4-ab10-ac9dd0c0a89f

## 🍨Reasoning behind your design choices:

- The reasoning behind our design choices stems from the primary goal of creating a user-friendly and intuitive interface like ChatGPT. 
Our homepage features a straightforward layout with a sidebar and a central chat section.
We opted for a minimalist design approach to prevent overwhelming users with too many options.

- The past conversation section organizes chats into groups, allowing users to easily navigate through saved conversations. 
We incorporated a rating system for filtering conversations, enhancing the user experience without cluttering the interface with unnecessary elements.

- Avoiding a tabular structure was a deliberate choice, as it wouldn't complement the conversational nature of the platform. 
Instead, we focus on capturing feedback at the end of each conversation.

## 🌵Reasoning behind your technical choices:
- I chose React.js for the front end and used Tailwind CSS/Material UI for styling. 
The back-end is built with Express.js and manages data storage using file system operations.
- It handles tasks like fetching default responses, saving conversations, and retrieving past conversations via HTTP requests. 
- The React-based front-end allows users to interact with the chat interface, ask questions, get AI responses, give feedback, and rate responses.
Our goal is to create a user-friendly platform for communicating with AI and storing conversation history.


## 🤖Features:

1.	**User can chat with AI modal**
2.	**user can give some feedback at each stage of the conversation**
3.	**feedback**
      - like / dislike - using thumbsup/thumbsdown button
      - button are hidden and float when the mouse hovers over AI model's
      - user should able to give ratings out of 5 at the end of conversation
      - used 5 stars for ratings
      - user should be able to give subjective feedback
4.	**user is done having that conversation, the chat gets saved.**
5.  **chat can be revisted from the panel on the side/top bar .**
6.  **another view where the user can see all feedback points across**
      - conversations and filter them based on rating

7. **Easy to navigate, well-designed, well-commented**
8. **Use mock the AI model as an API to return a fixed response.**
9. **mock the APIs as nodejs or any other backend API framework.**

## 🔮Tech stack:
[ReactJs](https://react.dev/) 
[Tailwind CSS](https://tailwindcss.com/) 
[Material UI](https://mui.com/) 
