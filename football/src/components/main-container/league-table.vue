
<script>
export default {
  name: "article",
};
</script>
<template>
  <div class="container">
    <div class="row">
      <div class="colonna col-md-6">
        <div class="container-title d-flex"><strong>League Table</strong></div>
        <table class="tb">
          <tbody class="tbd">
            <tr class="head">
              <th class="club">Team</th>
              <th class="pt text-center">W</th>
              <th class="pt text-center">D</th>
              <th class="pt text-center">L</th>
              <th class="pt text-center">PTS</th>
            </tr>
            <tr class="table-body">
              <th class="club">
                <strong class="position">1</strong
                ><img src="../../assets/club-1.png" alt="club" /> United fs Club
              </th>
              <th class="pt text-center">20</th>
              <th class="pt text-center">0</th>
              <th class="pt text-center">0</th>
              <th class="pt text-center">60</th>
            </tr>
            <tr class="table-body">
              <th class="club">
                <strong class="position">2</strong
                ><img src="../../assets/club-2.png" alt="club" /> Instanbul
                Sport
              </th>
              <th class="pt text-center">19</th>
              <th class="pt text-center">0</th>
              <th class="pt text-center">1</th>
              <th class="pt text-center">57</th>
            </tr>
            <tr class="table-body">
              <th class="club">
                <strong class="position">3</strong
                ><img src="../../assets/club-3.png" alt="club" /> Inter Club
              </th>
              <th class="pt text-center">17</th>
              <th class="pt text-center">2</th>
              <th class="pt text-center">1</th>
              <th class="pt text-center">55</th>
            </tr>
            <tr class="table-body">
              <th class="club">
                <strong class="position">4</strong
                ><img src="../../assets/club-4.png" alt="club" /> Milan FC
              </th>
              <th class="pt text-center">15</th>
              <th class="pt text-center">2</th>
              <th class="pt text-center">3</th>
              <th class="pt text-center">47</th>
            </tr>
            <tr class="table-body">
              <th class="club">
                <strong class="position">5</strong
                ><img src="../../assets/club-6.png" alt="club" /> Spezia Young
              </th>
              <th class="pt text-center">11</th>
              <th class="pt text-center">5</th>
              <th class="pt text-center">4</th>
              <th class="pt text-center">38</th>
            </tr>
            <tr class="table-body">
              <th class="club">
                <strong class="position">6</strong
                ><img src="../../assets/club-1.png" alt="club" />MOnza Sport
              </th>
              <th class="pt text-center">10</th>
              <th class="pt text-center">5</th>
              <th class="pt text-center">5</th>
              <th class="pt text-center">35</th>
            </tr>
            <tr class="table-body">
              <th class="club">
                <strong class="position">7</strong
                ><img src="../../assets/club-7.png" alt="club" /> Geova Football
              </th>
              <th class="pt text-center">09</th>
              <th class="pt text-center">6</th>
              <th class="pt text-center">5</th>
              <th class="pt text-center">33</th>
            </tr>
            <tr class="table-body">
              <th class="club">
                <strong class="position">8</strong
                ><img src="../../assets/club-8.png" alt="club" /> Sampdoria
                Sport
              </th>
              <th class="pt text-center">5</th>
              <th class="pt text-center">7</th>
              <th class="pt text-center">8</th>
              <th class="pt text-center">22</th>
            </tr>
            <tr class="table-body">
              <th class="club">
                <strong class="position">9</strong
                ><img src="../../assets/club-9.png" alt="club" />S.S.Lazio
              </th>
              <th class="pt text-center">1</th>
              <th class="pt text-center">10</th>
              <th class="pt text-center">9</th>
              <th class="pt text-center">13</th>
            </tr>
            <tr class="head"></tr>
          </tbody>
        </table>
        <div class="container-bottom">View Full League Table</div>
      </div>
      <div class="colonna col-md-6">
        <div class="container-title d-flex">
          <strong>Fixtures & Results</strong>
        </div>
        <div class="container-club">
          <div class="row one colonna-2 d-flex">
            <span class="col-5"><img class="image" src="../../assets/club-1.png" alt="club" /><strong>Spezia Young</strong></span>
            <h2 class="col-2 vs">vs</h2>
            <span class="col-5"><strong>Monza Sport</strong><img class="image" src="../../assets/club-6.png" alt="club"/></span>
          </div>
          <div class="row two colonna-2 d-flex">
            <span class="col-5"><img class="image" src="../../assets/club-3.png" alt="club" /><strong>Real Young</strong></span>
            <h2 class="col-2 vs">vs</h2>
            <span class="col-5"><strong>Barca Sport</strong><img class="image" src="../../assets/club-2.png" alt="club"/></span>
          </div>
          <div class="row one colonna-2 d-flex">
            <span class="col-5"><img class="image" src="../../assets/club-7.png" alt="club" /><strong>Young Rieti</strong></span>
            <h2 class="col-2 vs">vs</h2>
            <span class="col-5"><strong>Sport Tivoli</strong><img class="image" src="../../assets/club-8.png" alt="club"/></span>
          </div>
          <div class="row two colonna-2 d-flex">
            <span class="col-5"><img class="image" src="../../assets/club-11.png" alt="club" /><strong>Colleferro</strong></span>
            <h2 class="col-2 vs">vs</h2>
            <span class="col-5"><strong>Giudonia Club</strong><img class="image" src="../../assets/club-2.png" alt="club"/></span>
          </div>
          <div class="row one colonna-2 d-flex">
            <span class="col-5"><img class="image" src="../../assets/club-4.png" alt="club" /><strong>Villanova</strong></span>
            <h2 class="col-2 vs">vs</h2>
            <span class="col-5"><strong>VillaAdriana</strong><img class="image" src="../../assets/club-8.png" alt="club"/></span>
          </div>
          <div class="row two colonna-2 d-flex">
            <span class="col-5"><img class="image" src="../../assets/club-7.png" alt="club" /><strong>Young</strong></span>
            <h2 class="col-2 vs">vs</h2>
            <span class="col-5"><strong> Sport Club</strong><img class="image" src="../../assets/club-4.png" alt="club"/></span>
          </div>
          <div class="row one colonna-2 d-flex">
            <span class="col-5"><img class="image" src="../../assets/club-11.png" alt="club" /><strong>Lazio</strong></span>
            <h2 class="col-2 vs">vs</h2>
            <span class="col-5"><strong>Roma Club</strong><img class="image" src="../../assets/club-6.png" alt="club"/></span>
          </div>
          <div class="row two colonna-2 d-flex">
            <span class="col-5"><img class="image" src="../../assets/club-9.png" alt="club" /><strong>Juve</strong></span>
            <h2 class="col-2 vs">vs</h2>
            <span class="col-5"><strong>Napoli Club</strong><img class="image" src="../../assets/club-3.png" alt="club"/></span>
          </div>
          <div class="row one colonna-2 d-flex">
            <span class="col-5"><img class="image" src="../../assets/club-2.png" alt="club" /><strong>Milan</strong></span>
            <h2 class="col-2 vs">vs</h2>
            <span class="col-5"><strong>Inter Club</strong><img class="image" src="../../assets/club-1.png" alt="club"/></span>
          </div>
        </div>
        <div class="container-bottom">View Full League Table</div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  margin-bottom: 30px;
}
.one{
  background-color: #F3F3F3;
}
.two{
  background-color: #EBEBEB;
}
.colonna {
  padding: 40px;
  .container-title {
    justify-content: center;
    align-items: center;
    font-size: 40px;
    margin-bottom: 20px;
    margin-top: 30px;
  }
}
.head {
  background-color: black;
  color: white;
}
.table-body {
  background-color: #f5f5f5;
}
.club {
  text-align: left;
  border-right: 0;
  padding-left: 15px;
  padding-right: 15px;
  font-size: 20px;
}
.pt {
  width: 10%;
  font-size: 20px;
}
img {
  margin-right: 10px;
  width: 20%;
}
.position {
  margin-right: 10px;
}
.container-bottom {
  background-color: black;
  color: white;
  height: 40px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.colonna-2{
  justify-content: center;
  align-items: center;
}
.vs{
  display: flex;
  justify-content: center;
}
.image{
  width:30% ;
  margin-right:10px ;
  margin-left:  10px; ;
}
</style>