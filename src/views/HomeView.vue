<template>
  <div id="home">
    <section class="hero is-primary is-bold">
      <div class="hero-body">
        <div class="container">
          <div class="columns is-vcentered">
            <div class="column is-2 has-text-centered">
              <figure class="image is-128x128 is-inline-block">
                <img alt="New Moon logo" src="@/assets/logo.png" />
              </figure>
            </div>
            <div class="column is-10">
              <!-- Left side -->
              <h1 class="title">Welcome to Project New Moon</h1>
              <p class="subtitle">Get ready to experience Shin Megami Tensei IMAGINE Online once again with Project New Moon: A private server focused on community interaction and feedback.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container content">
        <h2>
          Golden Apple Calculator
          <router-link to="/apples"
            ><o-icon
              pack="mdi"
              class="icon has-text-info"
              icon="link"
            />Link</router-link
          >
        </h2>
        <p>
          Calculate the number of Golden Apples needed to reach a level, and how
          many dungeon runs that means.
        </p>
        <h2>
          Expertise Textbook Calculator
          <router-link to="/books"
            ><o-icon
              pack="mdi"
              class="icon has-text-info"
              icon="link"
            />Link</router-link
          >
        </h2>
        <p>
          Find out how many Expertise Textbooks it will take to reach a certain
          Class/Rank.
        </p>
        <h2>
          Expertise Calculator
          <router-link to="/expertise"
            ><o-icon
              pack="mdi"
              class="icon has-text-info"
              icon="link"
            />Link</router-link
          >
        </h2>
        <p>
          Plan out your expertise build, from Chain Expertise down to specific
          skill unlocks. Supports loading data from saved urls.
        </p>
        <h2>
          Moon Phase Simulator
          <router-link to="/moonphase"
            ><o-icon
              pack="mdi"
              class="icon has-text-info"
              icon="link"
            />Link</router-link
          >
        </h2>
        <p>
          Find out the current time in New Moon and upcoming moon phases.
        </p>
        <h2>
          Timed Demon Schedule
          <router-link to="/timed-demons"
            ><o-icon
              pack="mdi"
              class="icon has-text-info"
              icon="link"
            />Link</router-link
          >
        </h2>
        <p>
          Find out what time-sensitive demons are currently available in all fields.
        </p>
        <h2>
          Demon Inheritance Planner
          <router-link to="/demon-planner"
            ><o-icon
              pack="mdi"
              class="icon has-text-info"
              icon="ballot"
            />Link</router-link
          >
        </h2>
        <p>
          Plan out a demon using fusion and inheritance.
        </p>
        <hr />
        <p>
          Find an issue? Have a suggestion for a new feature or tool? <a href="https://github.com/Kuenaimaku/new-moon-tools/issues">Create an issue on GitHub</a> and I'll see what I can do. <br/>
          And for anything else not covered, check out the 
          <a href="https://wiki.project-new-moon.online/Main_Page">Project New Moon Wiki</a>.
        </p>
      </div>
    </section>
  </div>
</template>

<style scoped>
hr {
  background-color: #333;
}
</style>