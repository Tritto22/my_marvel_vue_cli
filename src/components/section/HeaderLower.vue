<template>
  <div class="header-lower">
    <nav>
      <ul class="nav">
        <li v-for="(link, i) in headerLowerLinks" :key="i">
          <a :href="link.link">{{link.name}}</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'HeaderLower',
  data() {
    return {
      headerLowerLinks: [
        {
          name: 'news',
          link: '#'
        },
        {
          name: 'comics',
          link: '#'
        },
        {
          name: 'characters',
          link: '#'
        },
        {
          name: 'movies',
          link: '#'
        },
        {
          name: 'tv shows',
          link: '#'
        },
        {
          name: 'games',
          link: '#'
        },
        {
          name: 'videos',
          link: '#'
        },
        {
          name: 'more',
          link: '#'
        }
      ]
    }
  }
}
  
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';
  .header-lower{
    max-width: 1200px;
    margin: auto;
    padding-bottom: 10px;
    padding-top: 5px;
    .nav{
      display: flex;
      justify-content: center;
      li{
        text-transform: uppercase;
        padding: 0 18px;
        cursor: pointer;
        a{
          color: $primary-txt-color-light;
          font-size: $lower-font-size;
          text-transform: uppercase;
          font-weight: bold;
          text-decoration: none;
        }
      }
      
    }
  }

</style>