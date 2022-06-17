<template>
  <nav>
      <ul>
          <li v-for="(link, index) in links" :key="index" :class="{active : link.isActive}" @click="active(index)">
              <img :src="'../../fable/' + link.icon">
              <a href="#">{{link.text}}</a>
          </li>
      </ul>
  </nav>
</template>

<script>
export default {
    name:'BaseCardNav',
    data() {
        return {
            links: [
               {
                   text: "Home",
                   icon: "home.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Pages",
                   icon:"document.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Blog",
                   icon:"printer.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Shop",
                   icon:"cart.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Shortcodes",
                   icon:"lab.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Support",
                   icon:"chat.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Contact",
                   icon:"envelope.png",
                   isActive: false,
                   href:"#",
               },
             ]
        }
        
    },

    methods: {
    active(index) {
        this.links.forEach(link => {
            link.isActive = false;
        });
        this.links[index].isActive = !this.links[index].isActive;
        }
    },
    
}
</script>

<style lang="scss" scoped>
    ul {
        display: flex;
        list-style-type: none;
        font-size: 15px;

        li:hover{
        background-color:var(--second-color) ;
        }

        a {
            display: inline-block;
            text-decoration: none;
            padding: 1.875rem 0.9375rem;
            color: var(--first-color);
            border-bottom: 0.3125rem solid transparent;
        } 

        :hover a {
            color: var(--third-color);
        }

        .active a {
        background-color: var(--second-color);
        color: var(--third-color);
        }
    }

    

</style>