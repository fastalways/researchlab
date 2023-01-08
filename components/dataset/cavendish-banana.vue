<template>
  <div id="main_Cavendish">
    <br>
    <b-card
      title="Dataset / Cavendish Banana"
      tag="article"
      class="mb-2"
    >
      <h3>Cavendish Banana Ripening Dataset</h3>

      <b-card-text>Bananas are rich in minerals and various nutrients. that the body should receive and provide up to 100 kcal of energy per unit. Because in bananas there are 3 types of sugar: sucrose, fructose, glucose, and dietary fiber. Thus our body will get energy immediately.  Two bananas can provide energy for up to 80-100 minutes (160-200Kcal) and also have other benefits such as stress relief, brain power, reduce the occurrence of ulcers in the stomach, reduce anemia reduction of the occurrence of cramps, nourishing the nervous system, etc.</b-card-text>
      <b-card-text>Our team built the Cavendish banana dataset while ripening. The dataset aim to (1) Banana Segmentation from background using DIP (2) DeepSemeticInstanceSegmentation (3) Ripeness Level Prediction for both DIP method and CNN Classification. We already labeled (annotation) for the data. The ripeness prediction level divied into 8 level.</b-card-text>
      <b-card-text />
      <br>
    </b-card>
    <h3>To Download</h3>
    <p>Please read and accept the Agreement and Disclaimer below before download. <b>If you download this dataset, we count you already accepted the agreement and disclaimer.</b></p>
    <p>1. The dataset must be only used for non-commercial or educational purposes.</p>
    <p>2. No responsibility or any guarantee for any incidents, or damages caused by the direct or indirect usage of this dataset.</p>
    <p>3. This dataset is copyright of <a href="https://www.rmutsv.ac.th" target="_blank">Rajamangala University of Technology Srivijaya</a>,for commercial usage please contact <a href="http://tlo.rmutsv.ac.th/tlo/">Technology Licensing Office</a>.</p>
    <p>4. If you used the dataset, please consider to referencing paper [การจำแนกระดับความสุกของกล้วยหอมอัตโนมัติด้วยการประมวลผลภาพดิจิทัลและการเรียนรู้เชิงลึก - Ripeness Level Classification of Cavendish Banana Using Digital Image Processing and Deep Learning].</p>
    <table>
      <tr>
        <th>Item</th>
        <th>DirectLink</th>
        <th>GoogleDrive</th>
      </tr>
      <tr>
        <td>8 Levels of FullImage</td>
        <td>
          <b-button href="https://dataset.gezdev.com/CavendishBanana/BananaDatasetDiscreteFullImage.tar.gz" variant="success">
            Download
          </b-button>
        </td>
        <td>
          <b-button href="https://drive.google.com/drive/folders/1lKkcf7iSfVh2fgPrJ4iBEYIMybTGo5f4?usp=sharing" target="_blank" variant="success">
            Download
          </b-button>
        </td>
      </tr>
      <tr>
        <td>8 Levels of TextureImage</td>
        <td>
          <b-button href="https://dataset.gezdev.com/CavendishBanana/BananaDatasetDiscreteTextureImage.tar.gz" variant="success">
            Download
          </b-button>
        </td>
        <td>
          <b-button href="https://drive.google.com/drive/folders/1lKkcf7iSfVh2fgPrJ4iBEYIMybTGo5f4?usp=sharing" target="_blank" variant="success">
            Download
          </b-button>
        </td>
      </tr>
      <tr>
        <td>Image and Annotation for DeepInstanceSegmentation</td>
        <td>
          <b-button href="https://dataset.gezdev.com/CavendishBanana/BananaForDeepInstanceSegment.tar.gz" variant="success">
            Download
          </b-button>
        </td>
        <td>
          <b-button href="https://drive.google.com/drive/folders/1lKkcf7iSfVh2fgPrJ4iBEYIMybTGo5f4?usp=sharing" target="_blank" variant="success">
            Download
          </b-button>
        </td>
      </tr>
      <tr>
        <td>Set of Images while Rippening</td>
        <td>
          <b-button href="https://dataset.gezdev.com/CavendishBanana/WhileRipening_CompletedSet.zip" variant="success">
            Download
          </b-button>
        </td>
        <td>
          <b-button href="https://drive.google.com/drive/folders/1lKkcf7iSfVh2fgPrJ4iBEYIMybTGo5f4?usp=sharing" target="_blank" variant="success">
            Download
          </b-button>
        </td>
      </tr>
    </table>
    <br></br>
    <h3>Gallery</h3>
    <img
      class="coe_logo"
      src="~/assets/img/dataset/collectBanana01.png"
      alt="Collection Cavendish Banana"
    >
    <img
      class="coe_logo"
      src="~/assets/img/dataset/levelingBanana01.png"
      alt="Leveling Cavendish Banana"
    >
    </b-card>
  </div>
</template>

<style>
table {
          border-collapse: collapse;
          width: 100%;
          }

          th, td {
          text-align: left;
          padding: 8px;
          }

          tr:nth-child(even){background-color: #f2f2f2}

          th {
          background-color: #4CAF50;
          color: white;
          }
          p{
            padding-left: 35px;
            padding-right: 10px;
          }
</style>
