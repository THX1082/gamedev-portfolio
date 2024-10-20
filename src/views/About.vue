<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Lee Brewington</strong>, a software and game developer with over 20 years of experience.<br/>
        I have a passion for learning, gaming, and problem solving.
      </div>

      <div style="margin-top: 20px;">I've worked on some <router-link to="/game-projects">solo games</router-link>, on some <router-link to="/other-projects">commissions</router-link>, and took part in some <router-link to="/resume">game jams</router-link> as well.</div>

      <div style="margin-top: 40px;">I'm <strong>currently looking</strong> for a full-time position with an established Roblox Game Studio. You can reach me at <a href="mailto:brewington7@hotmail.com">brewington7@hotmail.com</a> or <router-link to="/contact">through here</router-link>.</div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of DJX" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>