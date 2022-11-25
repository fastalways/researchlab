<template>
  <v-footer
    local-attrs
    padless
    color="indigo"
  >
    <v-container fluid>
      <v-row no-gutters>
        <v-col>
          <div align="left">
            <img class="hydra_research_logo" src="~/assets/img/hydra_research_logo.png" width="400" height="200" alt="hydra_research_logo">
          </div>
        </v-col>
        <v-col>
          <div align="left">
            <span class="white--text" align="left">
              <h4><div>Hydra Research Lab - Smart Digital Innovation Lab</div></h4>
              <div>Computer Engineering</div>
              <div>Faculty of Engineering</div>
              <div>Rajamangala University of Technology Srivijaya</div>
            </span>
          </div>
        </v-col>
        <v-col cols="12" sm="4" align="right">
          <div align="left">
            <span class="white--text" align="left">
              <h4><div>ทีมวิจัยไฮดร้า - ทีมวิจัยนวัตกรรมดิจิทัลอัฉริยะ</div></h4>
              <div>สาขาวิศวกรรมคอมพิวเตอร์</div>
              <div>คณะวิศวกรรมศาสตร์</div>
              <div>มหาวิทยาลัยเทคโนโลยีราชมงคลศรีวิชัย สงขลา</div>
            </span>
          </div>
        </v-col>
      </v-row>
      <div style="text-align: center; padding-top:20px">
        <span class="white--text">&copy; {{ new Date().getFullYear() }} Hydra Research Lab, Computer Engineering, Rajamangala University of Technology Srivijaya </span>
      </div>
    </v-container>
  </v-footer>
</template>
