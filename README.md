## Hi there 👋 yo soy Jozicleia Lopes


<section class="hero">
  <div class="overlay">
      <div class="content">
        <h1>creative <br>solutions.</h1>
        <p>We create custom personal and corporate WordPress websites!!</p>
      </div>
  </div>
</section>

@import url('https://fonts.googleapis.com/css?family=Poppins:200,400,800,900&display=swap');
$body-color: blue;
$poppins: 'Poppins', sans-serif;
body {
  margin: 0;
  padding: 0;
  background: #333;
  justify-content: center;
}
.hero {
 background: #133A53 url(https://ctwebdesignshop.com/wp-content/uploads/2019/01/homepage-hero.jpg);
  position: relative;
  display: flex;
  align-items: center;
  justify-content: left;
  font-family: $poppins;
  height: 100vh;
  width: 100vw;
  .overlay {
    position: absolute;
    top:0;
    left:0;
    right: 0;
   // background: rgb(19,58,83);
   // background: linear-gradient(220deg, rgba(19,58,83,0.85) 0%, rgba(208,97,40,0.85) 100%);
  .content {
      display: flex;
      flex-direction:column;
      justify-content: center;
      height: 100vh;
      width: 70vw;
      margin: auto;
      transform-origin: left;
      animation: reveal 1s ease-in-out forwards;
    h1 {
      font-size: 90px;
      line-height: 0.9;
      margin-bottom: 0px;
      color: white;
    }
    p {
      font-size: 24px;
      color: white;
    }
  }
  &:before {
        content: '';
        position: absolute;
        top:0;
        left:0;
        width: 100%;
        height: 100%;
        background: #ff6700;
        z-index: 3;
        animation: reveal .5s reverse forwards;
        animation-delay: .5s;
        transform-origin: ;
    }
    &:after {
        content: '';
        position: absolute;
        top:0;
        left:0;
        width: 100%;
        height: 100%;
        background: #133A53;
        z-index: 2;
        animation: reveal 0.7s reverse forwards;
        animation-delay: .7s;
        transform-origin: left;
    }
  }
}
@keyframes reveal {
  0% {
    transform: scaleX(0);
  }
  100% {
    transform: scaleX(1);
  }
}

<!--
**cleialopes/cleialopes** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
