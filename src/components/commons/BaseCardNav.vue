<template>
  <nav>
      <ul>
          <li v-for="(link, index) in links" :key="index">
              <img :src="link.icon">
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
                   icon: "../../fable/home.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Pages",
                   icon:"../../fable/document.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Blog",
                   icon:"../../fable/printer.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Shop",
                   icon:"../../fable/cart.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Shortcodes",
                   icon:"../../fable/lab.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Support",
                   icon:"../../fable/chat.png",
                   isActive: false,
                   href:"#",
               },

               {
                   text: "Contact",
                   icon:"../../fable/envelope.png",
                   isActive: false,
                   href:"#",
               },

           ]
        }
    }
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
    }

    

</style>