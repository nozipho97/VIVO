<template>
    <header>

        <input type="checkbox" name="" id="toggler">
        <label for="toggler" class="fas fa-bars"></label>
        <img src="https://i.postimg.cc/mDThq09D/vivo-logo_0.png" alt="">

        <nav class="navbar">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact</router-link>
        <router-link to="/register">Register</router-link>
        
        </nav>
        <div class="icons">
        <i class="fa-solid fa-user fa-beat"></i>
        </div>
    </header>
</template>

<style scope>
:root{
 --lightgreen: var(--lightgreen)
}
*{
  margin: 0; padding: 0;
  box-sizing: border-box;
  font-family: Georgia, 'Times New Roman', Times, serif;
  outline: none; border: none;
  text-decoration: none;
  transition: .2s linear;
}



header{
    position:fixed;
    top:0; left:0; right:0;
    background:lightgreen;
    padding: 1rem 9%;
    display:flex;
    align-items:center;
    justify-content: space-between;
    z-index: 1000;
  }
  
  header .logo{
    font-size: 3rem;
    color:#333;
    font-weight: bolder;
  }
  
  header .navbar a{
    font-size: 2rem;
    padding: 0 1.5rem;
    color: #fff;
  }
  
  header .navbar a:hover{
    color: 	#BF40BF;
  }
  
  header .icons i{
    font-size: 2.5rem;
    margin-left: 1.5rem;
  }
  
  header .icons i:hover{
    color: #BF40BF;
  }
  
  header #toggler{
    display: none;
  }
  
  header .fa-bars{
    font-size: 3rem;
    color: #fff;
    border-radius: .5rem 1.5rem;
    cursor: pointer;
    display: none;
  }
  @media (max-width:991px) {
    #App{
      font-size:55%;
    }
    header{
      padding:2rem;
    }
  }
  @media (max-width:768px){
    header .fa-bars{
      display: block;
    }
    header .navbar{
      position: absolute;
      top:10; left:0; right:0;
      
  
    }
  }
  
  </style>