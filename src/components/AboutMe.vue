<template>
  <section id="about">
    <h2>About Me</h2>
    <div class="about-cnt">
      <img src="/profile-image.jpeg" alt="A picture of Emmanuel Olubiyi." />
      <div class="briefs">
        <p>
          I am a <strong>Software Engineer</strong> with
          <strong>3 years</strong>
          of experience developing fully responsive and performant
          <strong>websites</strong> and <strong>web-apps</strong>. I have gained
          a strong understanding of
          <strong>software engineering</strong> through my work in
          <strong>Front-end development</strong>,
          <strong>Back-end development</strong> and constant learning.
        </p>

        <div class="SATs">
          <h3>skills &amp; technologies</h3>
          <div>
            <h4>Languages:</h4>
            <ul>
              <li>HTML</li>
              <li>CSS</li>
              <li>JavaScript</li>
              <li>TypeScript</li>
              <li>PHP</li>
              <li>Python</li>
              <li>Markdown</li>
              <li>Rust</li>
            </ul>
          </div>
          <div>
            <h4>Frameworks:</h4>
            <ul>
              <li>SASS</li>
              <li>TailwindCSS</li>
              <li>Reactjs</li>
              <li>Vuejs</li>
              <li>Nextjs</li>
              <li>Nuxtjs</li>
              <li>Nodejs</li>
              <li>Expressjs</li>
              <li>Django</li>
              <li>Django Rest Framework</li>
            </ul>
          </div>
          <div>
            <h4>Databases:</h4>
            <ul>
              <li>MySQL</li>
              <li>MongoDB</li>
              <li>PostgreSQL</li>
              <li>SQLite</li>
              <li>Redis</li>
            </ul>
          </div>
          <div>
            <h4>Tools:</h4>
            <ul>
              <li>Postman</li>
              <li>Figma</li>
              <li>GIT</li>
              <li>GitHub</li>
              <li>AWS</li>
              <li>Azure</li>
              <li>Heroku</li>
              <li>Notion</li>
              <li>Trello</li>
              <li>Jira</li>
              <li>Wordpress</li>
              <li>Wix website builder</li>
              <li>moodle</li>
            </ul>
          </div>
          <div>
            <h4>Development Skills</h4>
            <ul>
              <li>Technical Writing</li>
              <li>Web Development</li>
              <li>Cloud engineering</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.about-cnt {
  width: 100%;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  gap: 20px;
  margin-top: 20px;
}
.briefs {
  width: 100%;
  max-width: 700px;
}
.briefs p {
  line-height: 1.5;
}
.about-cnt > img {
  width: 250px;
  height: 250px;
  border-radius: 50%;
  box-shadow: 1px 1px 20px rgba(2, 81, 89, 0.5);
}
.SATs {
  margin-top: 20px;
  display: flex;
  flex-flow: column nowrap;
  gap: 16px;
}
.SATs ul {
  display: flex;
  flex-flow: row wrap;
  gap: 7px;
}
.SATs li {
  background: transparent;
  display: inline-block;
  color: var(--heavy-blue);
  border: 1px solid var(--gold);
  border-radius: 5px;
  padding: 5px 10px;
  font-family: var(--logo-font);
  font-size: 13px;
  transition: 0.3s ease;
}
h3,
h4 {
  color: var(--heavy-blue);
}
h3 {
  font-size: 20px;
}
h4 {
  font-size: 18px;
  margin-bottom: 5px;
  font-weight: 900;
}

@media screen and (min-width: 800px) {
  .about-cnt > img {
    width: 350px;
    height: 350px;
  }
  @media screen and (min-width: 900px) {
    .about-cnt {
      flex-flow: row nowrap;
      justify-content: space-between;
      gap: 40px;
    }
    .briefs > p {
      order: 1;
    }
    .about-cnt > img {
      order: 2;
      width: 350px;
      height: 350px;
    }
  }
}
</style>
