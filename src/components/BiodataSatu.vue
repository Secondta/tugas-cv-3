<template>
  <div class="all">
    <span v-for="BiodataSatu in BiodataSatu" :key="BiodataSatu">
      <div class="box1">
        <div class="box2">
          <div>
            <span style="font-size: 20px"><b>Ringkasan</b></span>
            <hr />
            {{ BiodataSatu.ringkasan }}
          </div> <br>
          <div>
            <span style="font-size: 20px"><b>Skill</b></span>
            <hr />
            <ul>
              <li>{{ BiodataSatu.skill }}</li>
            </ul>
          </div>
          <div>
            <span style="font-size: 20px"><b>Pengalaman</b></span>
            <hr />
            -
          </div><br>
          <div>
            <span style="font-size: 20px"><b>Pendidikan</b></span>
            <hr />
            <b> SD </b>: 2011-2017 <br />
            <b> SMP </b>: 2017-2020 <br />
            <b> SMK </b>: 2020-Sekarang
          </div>
          <div>
            <span style="font-size: 20px"><b>Sertifikat</b></span>
            <hr />
            {{ BiodataSatu.sertifikat }}
          </div>
        </div>
        <div class="padding">
        <h2 style="padding-top: 58px">{{ BiodataSatu.nama }}</h2>
        </div>
        <img
          src="https://asset-a.grid.id/crop/18x11:429x310/700x465/photo/2020/09/28/2585945251.jpg"
        />
        <div class="padding">
        <h3>
          Contact
          <span>
            <hr />
          </span>
        </h3>
        <p>
          <span><b>Alamat:</b></span> <br />Semarang
        </p>
        <p>
          <span><b>Nomor HP:</b></span> <br />+62 812 26386174
        </p>
        <p>
          <span><b>Email:</b></span> <br /><span
            style="text-decoration: underline"
            >idnssquad89@gmail.com</span
          >
        </p>
        <p>
          <span><b>Linkdin:</b></span> <br />-
        </p>
        <div>
          <span style="font-size: 20px"><b>Bahasa </b></span>
          <hr />
          Bahasa Indonesia <br />
          Bahasa Jawa <br />Bahas Inggris
        </div><br>
        <div>
          <span style="font-size: 20px"><b>Hobi </b></span>
          <hr>
          <ul>
            <li>Game</li>
            <li>Programming</li>
          </ul>
          </div>
        </div>
      </div>
    </span>
  </div>
</template>
<script>
/* eslint-disable */
import axios from 'axios'
export default {
data(){
  return{
    BiodataSatu: ''
  }
},
  mounted() {
    this.load()
  },
  methods: {
    load(){
      axios.get('http://localhost:3000/BiodataSatu').then(res => {
      this.BiodataSatu = res.data
      }).catch ((err) => {
        console.log(err);
      })
    }
  }
}
</script>
<style scoped>
.all {
  margin-left: 8cm;
  margin-right: 9cm;
}
img {
  width: 6cm;
}
.box1 {
  background-color: #f1f1f1;
  width: 5cm;
  padding-right: 1cm;
  height: 23cm;
}
.box2 {
  background-color: white;
  position: absolute;
  margin-left: 6cm;
  padding: 1cm;
  width: 10cm;
  height: 21cm;
}
.bordernama {
  background-color: black;
  color: white;
  font-size: 25px;
  height: 100px;
  padding-left: 5cm;
  padding-top: 15px;
}
.border1 {
  margin-right: 13cm;
  padding: 25px;
  text-align: right;
}
.profile {
  font-size: 20px;
}
.katapenting {
  font-size: medium;
}
.padding {
  padding-left: 1cm;
}
</style>