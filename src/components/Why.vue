<template>
  <div class="container-fluid">
    <div>
      <div class="whyus">
        <div class="row">
          <div class="col-6"></div>
          
          <div class="col-6" id="whyus1">
            <div class="whyus-title">
              <h1>Why <span >us.</span></h1>
              <p>
                There are millions of tracks and episodes on Spotify. So whether
                you’re behind the wheel, working out, partying or relaxing, the
                right music or podcast is always at your fingertips. Choose what
                you want to listen to, or let Spotify surprise you.You can
                also browse through the collections of friends, artists, and
                celebrities, or create a radio station and just sit back.Soundtrack
                your life with Spotify. Subscribe or listen for free.
              </p>
            </div>
            <!-- <div class="buttonGroup">
              <button>Read More</button>
              
            </div> -->
            <div class="accordion accordion-flush" id="accordionFlushExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingOne">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
      <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the first item's accordion body.</div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
      <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the second item's accordion body. Let's imagine this being filled with some actual content.</div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="flush-collapseThree" class="accordion-collapse collapse" aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
      <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
    </div>
  </div>
</div>
          </div>
        </div>
      </div>
    </div>
    <!-- <h2>Customer Service and Support</h2>
    <ol>
      <li>
        <a href="#">Help Site.</a>
        Check out our help site for answers to your questions and to learn how
        to get the most out of Spotify and your music.
      </li>
      <li>
        <a href="#">Community.</a>
        Get fast support from expert Spotify users. If there isn’t already an
        answer there to your question, post it and someone will quickly answer.
        You can also suggest and vote on new ideas for Spotify or simply discuss
        music with other fans.
      </li>
      <li>
        <a href="#">Contact Us.</a>
        Contact our Customer Support if you don’t find a solution on our support site or Community.
      </li>
      <li>
        <a href="#">Audiobook refunds.</a>
        Feeling sociable? Simply tweet the team and they’ll do all they can to help.
      </li>
    </ol> -->
  </div>
</template>

<script>
export default {
  data() {},
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Krub:ital,wght@0,200;0,300;1,200&display=swap");
.whyus{
  background-image: url(../assets/img/whyus.png);
  background-position: left;
  background-size:cover;
  background-repeat: no-repeat;
  height: 100vh;
  background-position-y: 5px;
  


  
}

.container-fluid{
  background-color:#181818;
}
.whyus-title h1{
  font-size: 61px;
color: #ffffff;
font-weight: 700;
font-family: "Krub";
}
.whyus-title span{
  font-size: 61px;
letter-spacing: 6px;
color: #aa84f9;
font-weight: 400;
font-family: "Krub";
}
.whyus-title p{
font-size: 14px;
color: #ffffff;
font-weight: 600;
font-family: "Krub";
text-align: left;
line-height: 26px;
margin-top: 50px;
}

.buttonGroup button{
  border: none;
  width: 126px;
height: 50px;
background-color: #aa84f9;
font-size: 14px;
letter-spacing: 1px;
text-transform: uppercase;
color: #ffffff;
font-weight: 700;
font-family: "Oswald";
margin-top: 45px;
margin-bottom: 290px;
}

</style>