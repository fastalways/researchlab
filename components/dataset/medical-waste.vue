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
      <b-card-text>Our team built Medical Dataset 41 Classes from real captured wastes/equipments. The images/video motions are keep in different environments e.g. Controlled Environment Box, Controlled Light Indoor, Dark Zone Indoor, Different Background Indoor, Different Background Outdoor, Overlay Items Indoor (Simulate to ConveyorBelt). <b>All 3,868 cropped images are used for deep learning models training and 7,140 cropped images used for testing the model.</b></b-card-text>
      <b-card-text>There are 41 classes for medical waste included : 1 Way Connector for Foley,2 Ways Connector for Foley,2 Ways Foley Catheter,3 Ways Connector for Foley,3 Ways stopcock,Alcohol Bottle,Alcohol Pad, Boot Cover,Cotton Ball,Cotton Swap,Dilator,Disposable Infusion Set,Extension Tube,Face Shield,Front Load Syringe,Gauze Pad,Glove,Guide Wire,Liquid Bottle,Mask,Nasal Cannula,Needle,NG Tube,Oxygen Mask,Pharmaceutical Product,Pill,Pill Bottle,PPE Suit,Prefilled Humidifier,Pressure Connecting Tube,Reusable Humidifier,Sodium Chloride Bag,Sterile Humidifier Adapter,Surgical Blade,Surgical Cap,Surgical Suit,Syringe,Tracheal Tube,Urine Bag,Vaccine Bottle,Winged Infusion Set.</b-card-text>

      <br>
      <h3>To Download</h3>
      <p>Please read and accept the Agreement and Disclaimer below before download. <b>If you download this dataset, we count you already accepted the agreement and disclaimer.</b></p>
      <p>1. The dataset must be only used for non-commercial or educational purposes.</p>
      <p>2. No responsibility or any guarantee for any incidents, or damages caused by the direct or indirect usage of this dataset.</p>
      <p>3. This dataset is copyright of <a href="https://www.rmutsv.ac.th" target="_blank">Rajamangala University of Technology Srivijaya</a>,for commercial usage please contact <a href="http://tlo.rmutsv.ac.th/tlo/">Technology Licensing Office</a>.</p>
      <p>4. If you used the dataset, please consider to referencing paper [พงศกร เจริญเนตรกุล, กิติศักดิ์ วัฒนกุล, ชัยสิทธิ์ ชูสงค์, นงนาฎ ระวังวงศ์, อรรถพล คงหวาน, ณัฐพล หนูฤทธิ "การแยกประเภทภาพขยะทางการแพทย์ด้วยการเรียนรู้เชิงลึก Medical Waste Image Classification Using Deep Learning",THE 46TH ELECTRICAL ENGINEERING CONFERENCE (EECON-46), pp. 312 - 315, 2566.].</p>
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
        <tr>
          <td>DatasetMedicalWaste <b>(Cropped)</b> - Controlled Environment (for training)</td>
          <td>
            <b-button href="https://dataset.gezdev.com/MedicalWaste/DatasetMedicalWasteControlledEnvironmentCropped.tar.gz" variant="success">
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
          <td>DatasetMedicalWaste <b>(Cropped)</b> - 3 Environments (for testing)</td>
          <td>
            <b-button href="https://dataset.gezdev.com/MedicalWaste/DatasetMedicalWasteTestLabeledCropped.tar.gz" variant="success">
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
      <br>
      <h3>Prediction Demo</h3>
      <br>
      <b-button href="https://medwaste-ai.gezdev.com/" target="_blank" variant="warning">
        LiveDemoClickHere
      </b-button>
      <img
        class="coe_logo"
        width="40%"
        src="~/assets/img/dataset/DemoMedWaste.png"
        alt="DemoMedWaste.png"
      >
      <br>
      <br>
      <h3>Gallery</h3>
      <h5>41 Classes of Medical Waste in the dataset</h5>
      <img
        class="coe_logo"
        width="100%"
        src="~/assets/img/dataset/41medwasteclass.png"
        alt="41medwasteclasses"
      >
      <h5>Sample Images</h5>
      <img
        class="coe_logo"
        width="40%"
        src="~/assets/img/dataset/belt_72.jpg"
        alt="belt_72.jpg"
      >
      <img
        class="coe_logo"
        width="40%"
        src="~/assets/img/dataset/belt_113.jpg"
        alt="belt_113.jpg"
      >
      <img
        class="coe_logo"
        width="40%"
        src="~/assets/img/dataset/Glove_9.JPG"
        alt="Glove_9.JPG"
      >
      <img
        class="coe_logo"
        width="40%"
        src="~/assets/img/dataset/Mask_14.JPG"
        alt="belt_72.jpg"
      >
      <img
        class="coe_logo"
        width="40%"
        src="~/assets/img/dataset/Pill_3.jpg"
        alt="Pill_3.jpg"
      >
      <img
        class="coe_logo"
        width="40%"
        src="~/assets/img/dataset/Syringe_15.jpg"
        alt="Syringe_15.jpg"
      >
      <img
        class="coe_logo"
        width="40%"
        src="~/assets/img/dataset/Vaccinebottle_4.jpg"
        alt="Vaccinebottle_4.jpg"
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
