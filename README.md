# 💸 Zerks 💸 - Customizable Landing Page

Welcome to **Zerks**! 🎉 This is a fun, customizable landing page that you can easily tweak to your liking. 🎨

Change the text, buttons, and animations, or add your favorite emojis! 😎 It's all up to you! 🌟

## Features:
- ✨ **Cool Text Scramble**: Customize the main text (`💸 Zerks 💸`) to anything you want! 📝
- 🎶 **Social Media Buttons**: Add your links to Spotify 🎧, Instagram 📸, SoundCloud 🎤, Discord 🎮, and more!
- 🔊 **Volume Toggle**: Click the volume icon to mute/unmute the sound! 🔇🔊
- 👻 **Overlay Screen**: Surprise visitors with a "beware..." message before entering. 👀
- 🎨 **Fully Customizable**: Change the layout, colors, fonts, and images to make it yours! 💥

## How to Customize:
### Text Scramble:
- Edit the `phrases` array to change the scrambled text. 💬
  ```javascript
  const phrases = ["💸 Zerks 💸", "Your Custom Text 🌟", "🔥 Cool Stuff 🔥"];

## Social Media Buttons:
  - Update the social media URLs in the handleButtonClick function! 🌍
javascript
Copy code
function handleButtonClick(event, platform) {
  let url;
  if (platform === 'spotify') {
    url = 'https://your-spotify-link.com';
  } else if (platform === 'instagram') {
    url = 'https://your-instagram-link.com';
  }
  window.open(url, '_blank');
}

## Emojis & Icons:
 -Add any emojis to the text or buttons for more fun! 🎉
    You can change the volume icon to any emoji you like. 🔊❌
    
## Overlay Customization:
  Modify the "beware..." button text or remove it completely. 😈
  Remove or Modify Volume Toggle:
  If you don’t want the volume toggle, just remove it. 🛑 Or change it to something else you like! 🤩

## Installation:
  Download or clone this repo! 📥
  Open the index.html in your browser to see it in action. 💻
  Customize the code as you like and make it your own! 🖥️

## License:
  Use it however you want! 🎉 Modify and share it with no restrictions. 🚀

Enjoy customizing your landing page and have fun! 🎉✨
