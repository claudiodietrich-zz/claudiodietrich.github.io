<template>
  <section class="section skills has-text-centered">
    <div class="container is-narrow">
      <div class="box">
        <div class="content">
          <div class="columns is-centered">
            <div class="column" v-for="skill in skills" v-bind:key="skill.title">
              <i class="is-size-1" v-bind:class="skill.icon"></i>
              <h1 class="title is-size-4 is-spaced">
                {{ skill.title }}
              </h1>
              <p>
                {{ skill.desc }}
              </p>
              <p class="list-title has-text-purple">
                {{ skill.listTitle }}
              </p>
              <p>
                {{ skill.listItens }}
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data () {
    return {
      skills: [
        {
          title: 'Front-end Developer',
          icon: 'fas fa-laptop',
          desc: 'I tend to code things from scratch, and enjoy bringing ideas to life in the browser.',
          listTitle: 'Languages I speak',
          listItens: 'HTML, CSS, JavaScript, Vue.js, Angular, Bootstrap, Bulma, jQuery, Grunt, LESS, SEO'
        },
        {
          title: 'Back-end Developer',
          icon: 'fas fa-server',
          desc: 'I like simplicity by writing fast code which is also easy to read and maintain.',
          listTitle: 'Languages I speak',
          listItens: 'Node.js, Express.js, Groovy, Grails, MySQL, PostgreSQL, MongoDB, Mongoose, PHP, WordPress'
        },
        {
          title: 'Developer',
          icon: 'fas fa-code',
          desc: 'I\'m a passionate programmer, who likes to write well-crafted and valuable software.',
          listTitle: 'Things I enjoy using',
          listItens: 'AWS, Git, Functional Programming, MVC, Agile, Linux, Vagrant'
        }
      ]
    }
  }
}
</script>


<style scoped>
.section.skills {
  margin-top: -14rem;
  padding-bottom: 1rem;
}

.container.is-narrow {
  max-width: 1200px;
}

.section.skills .box {
  padding: 0;
}

.section.skills .box .content .columns {
  margin-left: 0;
  margin-right: 0;
}

.section.skills .box .content .columns .column {
  padding: 50px 30px;
  border-bottom: 1px solid #E6ECF8;
  border-right: 0px solid #E6ECF8;
}

.section.skills .box .content .columns .column:last-child {
    border-right: none;
}

.section.skills .box .content .columns .column p.list-title {
  margin-top: 50px;
  margin-bottom: 8px;
}

@media screen and (min-width: 1280px) {
  .section.skills .box .content .columns .column {
    padding: 70px 45px;
  }
}

@media screen and (min-width: 769px) {
  .section.skills .box .content .columns .column {
    border-bottom: 0px solid #E6ECF8;
    border-right: 1px solid #E6ECF8;
    padding: 60px 35px;
  }
}
</style>

