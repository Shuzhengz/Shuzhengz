### Hi there 👋

<style>

</style>

html {
  width: 100%;
  height: 100%;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #000;
}

.wrap-image {
  position: relative;
  &::before,
  &::after {
    content: "";
    width: 100%;
    height: 100%;
    position: absolute;
    z-index: -1;
    border: 2px solid yellow;
    transition: all .25s ease-out;
  }
  &::before {
    background-color: yellow;
    top: -15px;
    left: -15px;
  }
  &::after {
    bottom: -15px;
    right: -15px;
  }
  &:hover {
    &::before {
      top: 15px;
      left: 15px;
    }
    &::after {
      bottom: 15px;
      right: 15px;
    }
  }
}

</style>

<div class="wrap-image">
  <img src="https://avatars.githubusercontent.com/u/43869232?v=4" alt="Profile Picture">
</div>

<!--
**Shuzhengz/Shuzhengz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
