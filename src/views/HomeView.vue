<template>
<div class="container">
  <img class="banner" src="https://i.postimg.cc/W35Smb26/Brown-and-Beige-Minimalist-Fashion-Banner-1.png" alt="Understanding and Leveraging Your Strengths">


    <h3>Knowing your strengths can provide several benefits, both personally and professionally. Here are some of the key advantages of understanding and leveraging your strengths:</h3>
    
    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://i.postimg.cc/43PmBRZ4/improved-self.jpg" class="d-block w-70" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Improved Self-Awareness</h5>
        <p>Identifying and understanding your strengths helps you gain better self-awareness. You become more conscious of your abilities, talents, and natural inclinations, which can lead to a deeper understanding of who you are as an individual.</p>
      </div>
    </div>
    <div class="carousel-item" >
      <img src="https://i.postimg.cc/jSVwjhZT/enhanced-confidance.jpg" class="d-block w-70" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Enhanced Confidence</h5>
        <p>When you know your strengths, you feel more confident in your abilities. This confidence allows you to take on new challenges and tasks with a positive mindset, knowing that you have the skills and competencies to handle them effectively.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://i.postimg.cc/YC14LmsW/better-decision-making.png" class="d-block w-70" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Better Decision Making</h5>
        <p>Understanding your strengths helps you make informed decisions about career choices, projects, and opportunities. You can align your choices with your strengths, increasing the likelihood of success and satisfaction..</p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
  <p>Please click the button below to register so that you will be able to access the course.</p>
    <RouterLink to="/register"><button class="register">Register</button></RouterLink>
</div>
</template>

<style scope>
 .container {
            max-width: 100%;
            margin: 20px auto;
            padding: 20px;
            /* border: 1px solid #CCC;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); */
        }

.banner {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }

.grid-container{
            display: grid;
            grid-template: 150px;
            grid-template-columns: auto auto;
            grid-gap: 2px;
            padding: 50px;
        }
        
h3{
            text-align: center;
            color: black;
            margin-bottom: 5px;
        }

p{
  color: black;
  font-size: 20px;
}


h5{
  color:lightgreen;

}

.register{
  background-color: red;
            color: #FFF;
            border: none;
            padding: 10px 20px;
            border-radius: 4px;
            cursor: pointer;

}



</style>