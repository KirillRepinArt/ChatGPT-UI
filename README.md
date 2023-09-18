# ChatGPT-UI

This is a css style for [text-generation-webui][1] that looks like ChatGPT. 

## Getting Started

1. Download `sohne-Regular_this one.otf` font, and install it.
    - Mac: use Font Book for this (File --> Add Fonts to Current User)
2. Download `chat_style-Chat-GPT.css` and `main.css`,
   and place them into [text-generation-webui\css][2] folder.
3. Launch text-generation-webui's web server.
4. Scroll down to see Chat style,
   and select Chat-GPT from the available chat styles.
5. That's it.

This style is meant to be used only in a chat setting, I haven't styled other pages like 'Parameters', 'Model' and so on.

![TextGen_wip_01](https://github.com/KirillRepinArt/ChatGPT-UI/assets/118350327/d3f49a8c-c730-42ce-b269-77d83dfd403f)
![TextGen_wip_02](https://github.com/KirillRepinArt/ChatGPT-UI/assets/118350327/d0ddf141-bd54-46b6-bc99-49e6ebd141a9)
![TextGen_wip_03](https://github.com/KirillRepinArt/ChatGPT-UI/assets/118350327/fb4c430d-ad58-4805-acaa-38a6f03c9ec6)
![TextGen_wip_04](https://github.com/KirillRepinArt/ChatGPT-UI/assets/118350327/685b07df-c04e-400d-bfe6-f5d20fae67f5)
![TextGen_wip_05](https://github.com/KirillRepinArt/ChatGPT-UI/assets/118350327/f38bf7fb-46e3-4108-98b5-304f06f8e889)
![TextGen_wip_06](https://github.com/KirillRepinArt/ChatGPT-UI/assets/118350327/273bc857-5cab-48ca-a015-8383dcb4173b)
![TextGen_wip_07](https://github.com/KirillRepinArt/ChatGPT-UI/assets/118350327/9dd14cce-56ce-47d0-8a77-6aaf0e35f769)

[1]: https://github.com/oobabooga/text-generation-webui
[2]: https://github.com/oobabooga/text-generation-webui/tree/main/css

Couple of notes.
1. For 'Clear history' button, the buttons 'Cancel' and 'Confirm' are now permanently present above 'Clear history' button.
2. If this style works for you and you would like to keep using it, I suggest caution when updating TexGen. The changes in the main repo might affect the names of the groups I've targeted with CSS, which would result in Chat-GPT style not working properly.
3. This style doesn't work properly on mobile.
