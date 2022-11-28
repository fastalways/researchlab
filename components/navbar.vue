<template>
  <div>
    <b-navbar toggleable="lg" class="navbar navbar-light" type="dark" style="background-color: #042c5c;">
      <b-navbar-brand href="/">
        <img src="~/assets/img/hydra_research_logo.png" width="200" height="100" alt="">
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse" />

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav toggle-class="text-light">
          <b-nav-item href="/research">
            Research
          </b-nav-item>
          <b-nav-item href="/publications">
            Publications
          </b-nav-item>
          <b-nav-item-dropdown text="Member">
            <b-dropdown-item href="/aj-nongnard">
              Nongnard  Rawangwong
            </b-dropdown-item>
            <b-dropdown-item href="/aj-chaisit">
              Chaisit Choosong
            </b-dropdown-item>
            <b-dropdown-item href="/aj-authapon">
              Authapon Kongwan
            </b-dropdown-item>
            <b-dropdown-item href="/aj-kitisak">
              Kittisak Wattanakul
            </b-dropdown-item>
            <b-dropdown-item href="/aj-pongsagorn">
              Pongsagorn Chalearnnetkul
            </b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown text="Dataset">
            <b-dropdown-item href="/alldataset">
              > All Datasets
            </b-dropdown-item>
            <b-dropdown-item href="/dataset/topview-depth-human-action-dataset">
              Topview Depth Image of Human Actions
            </b-dropdown-item>
            <b-dropdown-item href="/dataset/medical-waste-dataset">
              Medical Waste Dataset
            </b-dropdown-item>
            <b-dropdown-item href="/dataset/recycle-waste-dataset">
              Recycle Waste Dataset
            </b-dropdown-item>
            <b-dropdown-item href="/dataset/cavendish-banana-dataset">
              Cavendish Banana for Ripening Dataset
            </b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item href="/project">
            Project
          </b-nav-item>
          <b-nav-item href="/medium">
            Medium
          </b-nav-item>
          <b-nav-item href="/about">
            AboutUs
          </b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item-dropdown text="Lang" right>
            <b-dropdown-item href="#">
              EN
            </b-dropdown-item>
            <b-dropdown-item href="#">
              TH
            </b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
