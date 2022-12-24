<template>
  <div class="container-fluid">
    <section id="cards">
      <div class="row">
        <div class="col-3 mt-3" v-for="item of 8" :key="item">
          <div class="cardes">
            <div class="card" style="width: 18rem">
              <div class="card-body">
                <h5 class="card-title">Course <span>01</span></h5>
                <div class="cardhr"><h6></h6></div>

                <p class="card-text">
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
                <div class="buttongroup">
                  <!-- <button>Read More</button> -->
                  <!-- Button trigger modal -->
                  <button
                    type="button"
                    class="btn btn-primary"
                    data-bs-toggle="modal"
                    data-bs-target="#staticBackdrop"
                  >
                    Read More
                  </button>

                  <!-- Modal -->
                  <div
                    class="modal fade"
                    id="staticBackdrop"
                    data-bs-backdrop="static"
                    data-bs-keyboard="false"
                    tabindex="-1"
                    aria-labelledby="staticBackdropLabel"
                    aria-hidden="true"
                  >
                    <div class="modal-dialog">
                      <div class="modal-content">
                        <div class="modal-header">
                          <h1 class="modal-title fs-5" id="staticBackdropLabel">
                            Adversing
                          </h1>
                          <button
                            type="button"
                            class="btn-close"
                            data-bs-dismiss="modal"
                            aria-label="Close"
                          ></button>
                        </div>
                        <div class="modal-body">
                          The P&C Committee shall carry out the Board’s responsibilities relating to compensation of the
members of the Board and the Company’s employees, including the Company’s and its affiliates’
executive officers and provide such other guidance with respect to compensation matters as the
P&C Committee deems appropriate. The P&C Committee shall perform its responsibilities in a
manner that it believes supports the Company’s business objectives and incorporates sound
corporate governance principles. The P&C Committee may also have such other duties as may
from time to time be assigned to it by the Board or, as long as the shares of the Company are
listed on the New York Stock Exchange (the “NYSE”), are required by the rules and regulations
of the U.S. Securities and Exchange Commission (the “SEC”) or of the NYSE.
                        </div>
                        <div class="modal-footer">
                          <button
                            type="button"
                            class="btn btn-secondary"
                            data-bs-dismiss="modal"
                          >
                            <strong>Close</strong>
                          </button>
                          <button type="button" class="btn btn-primary"
                          data-bs-dismiss="modal">
                            <strong>Understood</strong>
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Krub:ital,wght@0,200;0,300;1,200&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap");
.card {
  width: 291px;
  height: 375px;
  border: 3px solid #ffffff;
  background-color: #181818;
}
.container-fluid {
  background-color: #181818;
}
.cardes h5 {
  font-size: 33px;
  letter-spacing: 1px;
  line-height: 50px;
  text-transform: uppercase;
  color: #f2f2f2;
  font-weight: 600;
  font-family: "Krub";
  margin-top: 65px;
}
.card span {
  color: #aa84f9;
  margin-left: 8px;
}
.card-title {
  display: flex;
  justify-content: center;
}
.cardhr h6 {
  width: 55px;
  height: 3px;
  background-color: #aa84f9;
  /* border: 1px solid #000000; */
  margin-left: 100px;
}
.card-text {
  font-size: 14px;
  letter-spacing: 0px;
  line-height: 27px;
  color: #f2f2f2;
  font-weight: 600;
  font-family: "Krub";
  text-align: center;
  margin-top: 25px;
}
.buttongroup {
  display: flex;
  justify-items: center;
  justify-content: center;
}
.buttongroup button {
  width: 125px;
  height: 47px;
  background-color: #aa84f9;
  border: none;
  font-size: 14px;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: #f1f1f1;
  font-weight: 700;
  font-family: "Oswald", sans-serif;
  margin-top: 25px;
}
#cards {
  padding-top: 15px;
  padding-bottom: 15px;
}
</style>