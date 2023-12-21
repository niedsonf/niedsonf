<style>
  @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;700display=swap');

  * {
    font-family: 'Fira Code', monospace;
  }

  .wrapper {
    width: 100%;
    height: 100%;
  }

  .border-wrapper {
    width: 100%;
    height: 100%;
    display: flex;
    place-items: center;
    background: rgb(0,179,126);
    background: linear-gradient(45deg, rgba(0,179,126,1) 0%, rgba(0,135,95,1) 50%, rgba(1,95,67,1) 100%);
    background-size: 200% 200%;
    animation: animate-gradient 2s infinite ease-out;
    padding: 0.5rem;
    border-radius: 4px;
  }

  .content {
    width: 100%; 
    height: 100%; 
    background: #22272e;
    border-radius: 4px;
    padding: 1rem;
  }

  .section-title {
    font-size: 20px;
    font-weight: 400;
    color: #00b37e;
  }

  .section-subtitle {
    font-size: 16px;
    font-weight: 400;
    color: #00b37e;
  }

  .section-title::before {
    content: '';
    width: 100%;
    height: 100%;
    background-color: red;
  }

  .skills {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 0.5rem;
    row-gap: 32px;
  }

  .hexagon-grid {
    display: grid;
    width: 50%;
    grid-template-areas:
    "a . b . e"
    ". c . d .";
  }

  .hexagon-grid-reverse {
    display: grid;
    width: 50%;
    grid-template-areas:
    ". c . d ."
    "a . b . e";
  }

  .hexagon-grid:has(.hexagon:hover) .hexagon:not(:hover){
    opacity: 0.7;
  }

  .hexagon-grid-reverse:has(.hexagon:hover) .hexagon:not(:hover){
    opacity: 0.7;
  }

  .hexagon {
    width: 60px;
    height: 60px;
    display: grid;
    place-items: center;
    clip-path: polygon(100% 50%, 75% 93.3%, 25% 93.3%, 0% 50%, 25% 6.7%, 75% 6.7%);
    cursor: pointer;
    background: rgb(0,179,126);
    background: linear-gradient(45deg, rgba(0,179,126,1) 0%, rgba(0,135,95,1) 50%, rgba(1,95,67,1) 100%);
    background-size: 200% 200%;
    animation: animate-gradient 2s infinite ease-out;
    transition: all 200ms;
  }

  .hexagon:hover {
    transform: scale(1.05);
  }

  @keyframes animate-gradient {
    0% {background-position: 0% 0%;}
    50% {background-position: 100% 100%;}
    100% {background-position: 0% 0%;}
  }

</style>

<div class="wrapper">
  <div class="border-wrapper">
    <div class="content">
      <div>
        <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=1000&color=00b37e&random=false&width=435&lines=Hey%2C+I'm+Niedson;Front-end+Developer;B.Sc.+in+Science+n+Technology;Mechatronics+Technician" alt="Typing SVG" /></a>
        <span class="section-subtitle">Brazil, Natal/RN</span>
      </div>
      <div class="skills">
        <div>
          <h1 class="section-title">Front-end Tools</h1>
          <div class="hexagon-grid">
            <div class="hexagon top-hexagon" style="grid-area: a;">
              <image width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg"/>
              </div>
            <div class="hexagon top-hexagon" style="grid-area: b;">
              <image width="32" style="margin-left: -8px;" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg"/>
            </div>
            <div class="hexagon" style="grid-area: c; margin: -30px -12px 0 -12px;">
              <image width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original-wordmark.svg"/>
            </div>
            <div class="hexagon" style="grid-area: d; margin: -30px 0 0 -12px;">
              <image width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-plain.svg"/>
            </div>
          </div>
        </div>
        <div>
          <h1 class="section-title">Back-end Tools</h1>
          <div class="hexagon-grid">
            <div class="hexagon top-hexagon" style="grid-area: a;">
              <image width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-plain.svg"/>
              </div>
            <div class="hexagon top-hexagon" style="grid-area: b;">
              <image width="32" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg"/>
            </div>
            <div class="hexagon" style="grid-area: c; margin: -30px -12px 0 -12px;">
              <image width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sequelize/sequelize-original.svg"/>
            </div>
          </div>
        </div>
        <div>
          <div class="hexagon-grid-reverse">
            <div class="hexagon top-hexagon" style="grid-area: a;  margin: -30px -12px 0 0;">
              <image width="32" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg"/>
              </div>
            <div class="hexagon top-hexagon" style="grid-area: b; margin: -30px -12px 0 -12px;">
              <image width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"/>
            </div>
            <div class="hexagon" style="grid-area: c;">
              <image width="32" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"/>
            </div>
            <div class="hexagon" style="grid-area: d;">
              <image width="32" style="margin-left: -2px;" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg"/>
            </div>
            <div class="hexagon" style="grid-area: e; margin: -30px -12px 0 -12px;">
              <image width="32" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/arduino/arduino-plain.svg"/>
            </div>
          </div>
          <h1 class="section-title">Languages</h1>
        </div>
      </div>
      <hr/>
      <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=niedsonf&layout=compact&theme=dracula" />
    </div>
  </div>
</div>
