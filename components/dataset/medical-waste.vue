<template>
  <div id="main_MedicalWaste">
    <br>
    <b-card
      title="Dataset / Medical Waste Dataset"
      tag="article"
      class="mb-2"
    >
      <h3>Medical Waste Dataset</h3>

      <b-card-text />
      <b-card-text>Our team built the Medical Dataset 41 Classes from real captured images/video motion in different environments</b-card-text>
      <b-card-text />
      <br>
    </b-card>
    <h3>To Download</h3>
    <p>Please read and accept the Agreement and Disclaimer below before download. <b>If you download this dataset, we count you already accepted the agreement and disclaimer.</b></p>
    <p>1. The dataset must be only used for non-commercial or educational purposes.</p>
    <p>2. No responsibility or any guarantee for any incidents, or damages caused by the direct or indirect usage of this dataset.</p>
    <p>3. This dataset is copyright of <a href="https://www.rmutsv.ac.th" target="_blank">Rajamangala University of Technology Srivijaya</a>,for commercial usage please contact <a href="http://tlo.rmutsv.ac.th/tlo/">Technology Licensing Office</a>.</p>
    <p>4. If you used the dataset, please consider to referencing paper [ xxxx  wating publication... ].</p>
    <table>
      <tr>
        <th>Item</th>
        <th>DirectLink</th>
        <th>GoogleDrive</th>
      </tr>
      <tr>
        <td>DatasetMedicalWaste - Controlled Environment (for training)</td>
        <td>
          <b-button href="https://dataset.gezdev.com/MedicalWaste/DatasetMedicalWasteControlledEnvironment.tar.gz" variant="success">
            Download
          </b-button>
        </td>
        <td>
          <b-button href="https://drive.google.com/drive/folders/1E6yaC_vANBaAsbD6oZVkf7p-rqowQQ_G?usp=sharing" target="_blank" variant="success">
            Download
          </b-button>
        </td>
      </tr>
      <tr>
        <td>DatasetMedicalWaste - 3 Environments (for testing)</td>
        <td>
          <b-button href="https://dataset.gezdev.com/MedicalWaste/DatasetMedicalWasteTestLabeled.tar.gz" variant="success">
            Download
          </b-button>
        </td>
        <td>
          <b-button href="https://drive.google.com/drive/folders/1E6yaC_vANBaAsbD6oZVkf7p-rqowQQ_G?usp=sharing" target="_blank" variant="success">
            Download
          </b-button>
        </td>
      </tr>
    </table>
    <br></br>
    <h3>Gallery</h3><!--
    <img
      class="coe_logo"
      src="~/assets/img/dataset/collectBanana01.png"
      alt="Collection Cavendish Banana"
    >
    <img
      class="coe_logo"
      src="~/assets/img/dataset/levelingBanana01.png"
      alt="Leveling Cavendish Banana"
    >-->
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
