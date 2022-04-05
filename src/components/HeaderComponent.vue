<template>
<header>
    <img class="logo-ditor" src="../assets/img/logo-ditor.svg" alt="">
    <nav>
        <ul>
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Project</a></li>
            <li><a href="">Contact</a></li>
        </ul>
    </nav>
</header>
</template>

<script>
export default {
  name: 'HeaderComponent'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang='scss'>
header{
    display: flex;
    padding: 10px 20px;
    nav{
        padding: 10px 20px;
        margin-left: 30px;
        ul{
            display: flex;
            flex-direction: row;
            list-style-type: none;
            gap: 10px;
            li{
                a{
                    color: white;
                    text-decoration: none;
                    font-family: var(--cabinText);
                }
            }
            
        }

    }
}

</style>