<template>
  <div id="main-container">
    <carosel />
    <navbar />
    <div id="main-content">
      <v-container fluid>
        <v-row no-gutters>
          <v-col>
            <div align="left" style="padding-left: 50px;">
              <img
                class="coe_logo"
                src="~/assets/img/aj-nattapon.jpg"
                width="365"
                height="500"
                alt="Computer Engineering"
              >
            </div>
            <div align="center">
              <span class="white--text" align="center">
                <h4>
                  <div style="padding-top: 10px; text-align: left; padding-left: 30px;">Nattapon Noorit
                  </div>
                </h4>
                <li style="padding-left: 50px;padding-top: 10px;text-align: left;"><b>Present Position:</b> Lecturer
                </li>
                <li style="padding-left: 50px;padding-top: 4px;text-align: left;"><b>Dept.:</b> Computer Engineering
                </li>
                <li style="padding-left: 50px;padding-top: 4px;text-align: left;"><b>Faculty:</b> Engineering</li>
                <li style="padding-left: 50px;padding-top: 4px;text-align: left;"><b>Rajamangala University of
                  Technology Srivijaya</b></li>
                <li style="padding-left: 50px;padding-top: 4px;text-align: left;"><b>E-mail (work) :</b>
                    nattapon.n@rmusv.ac.th</li>
                <h4>
                  <div style="padding-top: 10px; text-align: left; padding-left: 30px;">อ.ณัฐพล หนูฤทธิ</div>
                </h4>
                <li style="padding-left: 50px;padding-top: 4px;text-align: left;text-align: left;">
                  <b>ตำแหน่งปัจจุบัน:</b> อาจารย์</li>
                <li style="padding-left: 50px;padding-top: 4px;text-align: left;text-align: left;"><b>สาขา:</b>
                  วิศวกรรมคอมพิวเตอร์</li>
                <li style="padding-left: 50px;padding-top: 4px;text-align: left;text-align: left;"><b>คณะ:</b>
                  วิศวกรรมศาสตร์</li>
                <li style="padding-left: 50px;padding-top: 4px;text-align: left;text-align: left;">
                  <b>มหาวิทยาลัยเทคโนโลยีราชมงคลศรีวิชัย</b></li>
                <li style="padding-left: 50px;padding-top: 4px;text-align: left;text-align: left;"><b>E-mail (ทำงาน)
                  :</b> nattapon.n@rmusv.ac.th</li>
                <li style="padding-left: 50px;padding-top: 4px;text-align: left;text-align: left;">
                  <b>เบอร์โทรศัพท์สำนักงาน:</b> 0-7431-7168 </li>

                <h4>
                  <div style="padding-top: 15px;padding-left: 30px;text-align: left;">Google Site RMUTSV</div>
                </h4>
                <div style="padding-left: 50px;text-align: left;"><a
                  href="https://nattaponn.sites.rmutsv.ac.th/"
                  target="_blank"
                >https://pongsagornch.sites.rmutsv.ac.th/</a></div>
              </span>
            </div>
          </v-col>
          <v-col>
            <div align="left">
              <span class="white--text" align="left">
                <h4>
                  <div>Pongsagorn Chalearnnetkul</div>
                </h4>
                <div> is presently a lecturer at <a href="http://coe.eng.rmutsv.ac.th" target="_blank">Computer
                  Engineering,</a> <a href="https://eng.rmutsv.ac.th" target="_blank">Faculty of Engineering,</a> <a
                  href="https://www.rmutsv.ac.th"
                  target="_blank"
                >Rajamangala University of Technology Srivijaya,</a></div>
                <h4>
                  <div style="padding-top:30px;padding-left:10px;"> Education:</div>
                </h4>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;"><b>M.Eng. in Computer Engineering</b> -
                  2010 <b>Prince of Songkla University,</b> Thailand</li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;"><b>B.Eng. in Computer Engineering</b> -
                  2010 <b>Prince of Songkla University,</b> Thailand</li>
                <h4>
                  <div style="padding-top:30px;padding-left:10px;"> Field of Interests / Professional Highlights:</div>
                </h4>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Computer Vision</li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Digital Image Processing</li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Pattern Recognition </li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Computer Programming</li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Artificial Intelligence</li>
                <h4>
                  <div style="padding-top:30px;padding-left:10px;"> Teaching Exprience:</div>
                </h4>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Computer Programming</li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Microcontroller</li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Sensor and Transducer</li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Database System</li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Artificial Intelligence</li>
                <h4>
                  <div style="padding-top:30px;padding-left:10px;"> Papers and Publications:</div>
                </h4>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">นราธร สังข์ประเสริฐ และณัฐพล หนูฤทธิ. 2562. การพัฒนาเทคโนโลยีความเป็นจริงเสริม (AR: Augmented Reality) ที่ใช้ร่วมกับหนังสือเรียนการเขียนโปรแกรมคอมพิวเตอร์สำหรับนักศึกษาชั้นปริญญาตรี. การประชุมวิชาการระดับชาติ ครั้งที่ 5 มหาวิทยาลัยราชภัฎอุบลราชธานี, โรงแรมเดอะรีเจนท์ จังหวัดอุบลราชธานี,15-16 กรกฎาคม 2562, หน้า 10-17.
                </li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Nattapon Noorit and Nikom Suvonvorn,  “Human Activity Recognition from Basic Actions Using Graph Similarity Measurement”, In Proceeding of 12th International Joint Conference on Computer Science and Software Engineering (JCSSE), Hatyai, Thailand, 22th-24th July 2015, pp.7-11.
                </li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">Nattapon Noorit and Nikom Suvonvorn, “Human Activity Recognition from Basic Actions Using Finite State Machine,” In Proceeding of Advances Data and Information Engineering, Kuala Lumpur, Malaysia, 16th-18th December 2013.
                </li>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;">N. Noorit, N. Suvonvorn and M. Karnchanadecha, “Model-based Human Action Recognition,” In Proceedings of SPIE the 2nd International Conference on Digital Image Processing, Singapore, 26th-28th February 2010, pp. 7546P-1 - 7546P-6.
                </li>
                <h4>
                  <div style="padding-top:30px;padding-left:10px;"> Work Experience:</div>
                </h4>
                <li style="padding-left: 10px;padding-top: 4px;text-align: left;"><b>Lecturer at Computer Engineering
                  Program RUTS</b> - 2017 to present</li>
              </span>
            </div>
          </v-col>
        </v-row>
      </v-container>
    </div>
    <vfooter />
  </div>
</template>

<script>
import Carosel from '../components/carosel.vue'
import navbar from '../components/navbar.vue'
import vfooter from '../components/vfooter.vue'
export default {
  components: { navbar, Carosel, vfooter }
}
</script>

    <style>
    @import url('https://fonts.googleapis.com/css?family=Prompt');

    html,
    body {
      font-family: 'Prompt', sans-serif;
    }

    #main-container {
      font-family: Prompt, Avenir, Helvetica, Arial, sans-serif;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      color: #2c3e50;
      margin-top: 60px;
      max-width: 1440px;
      margin: auto;
    }

    #main-content {
      min-height: 900px;
      padding-top: 1%;
      padding-left: 2%;
      padding-right: 2%;
    }
    </style>
