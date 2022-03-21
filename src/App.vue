<template>
  <Menu class="relative inline-block text-left ">
<MenuButton class="inline-flex 
justify-center
 border rounded-md border-gray-300
  shadow-sm px-2 py-2 bg-white
   text-sm font medium">
  option
</MenuButton>
 <Menuitems class="origin-top-right
  absolute right-0 mt-2 w-36 rounded-md
   bg-white shadow-lg 
   ring-black ring-opacity-5">
 <Menuitem class="block px-2 py-1 text-sm cursor-pointer">
 habte
 </Menuitem>
 <Menuitem class="block px-2 py-1 text-sm">
 habtu
 </Menuitem>
 <Menuitem class="block px-2 py-1 text-sm">
 andu
 </Menuitem>
 </Menuitems>
  </Menu>
</template>

<script>
import Menu from '@/components/Menu'
import MenuButton from '@/components/menuButton'
import Menuitems from '@/components/menuitems'
import Menuitem from '@/components/Menuitem'
export default {
  name: 'App',
  components: {
    Menu,
    MenuButton,
    Menuitems,
    Menuitem
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
