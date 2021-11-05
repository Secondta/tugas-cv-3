<template>
<div class="all">
    <div class="all2">
        <div class="borderatas">a</div>
        <legend>RESUME</legend>
        <img class="img" src="https://t3.ftcdn.net/jpg/03/46/83/96/360_F_346839683_6nAPzbhpSkIpb8pmAwufkC7c5eD7wYws.jpg" style="border-radius: 100%;">
        <div class="bordernama">
        Secondta <br>
        Ardiansyah <br>
        Wicaksono
        </div>
        <div>
            <span style="font-size: 20px; position: absolute; margin-top: 20px; margin-left: 6cm">SISWA SMK BINA NUSANTARA</span>
            <hr style="margin-left: 6cm; width: 15cm; position: absolute; margin-top: 2cm">
        </div>
        <span  v-for="BiodataDua in BiodataDua" :key="BiodataDua">
        <div class="border1">
            <div class="border2">
                <div class="borderkotak">
                    <span class="judul"> <img src="https://e7.pngegg.com/pngimages/552/804/png-clipart-computer-icons-briefcase-luggage-icon-cdr-rectangle.png" style='width: 30px;'> PENGALAMAN KERJA</span><br>
                    <hr class="dotted">
                    <span>{{ BiodataDua.pengalaman }}</span>
                </div>
                <div class="borderkotak">
                    <span class="judul"> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKDZFxNrQCdh0cFqtY5AzyHU99qpYj5RYq2w&usqp=CAU" style='width: 45px;'> PENDIDIKAN</span><br>
                    <hr class="dotted">
                    <span>{{ BiodataDua.pendidikan }} <br> {{ BiodataDua.pendidikan2 }} <br> {{ BiodataDua.pendidikan3 }}</span>
                </div>
                <div class="borderkotak">
                    <span class="judul"> <img src="https://w7.pngwing.com/pngs/638/985/png-transparent-incandescent-light-bulb-electricity-light-cdr-lamp-black.png" style='width: 30px;'> KEMAMPUAN</span><br>
                    <hr class="dotted">
                    <div class="kper">
                    <div class="subkatapenting"><b>KEMAMPUAN PERSONAL</b><br> <br>
                    
                    <span class="subkatapenting">Organisai<span style='margin-left: 90px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br>
                    <span class="subkatapenting">Komunikasi <span style='margin-left: 76px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br>
                    <span class="subkatapenting">Pembagian Wkatu<span style='margin-left: 43px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br>
                    <span class="subkatapenting">Kekompakan Team<span style='margin-left: 39px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br>
                    <span class="subkatapenting">Komitmen<span style='margin-left: 87px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br>
                    <span class="subkatapenting">Multitasking<span style='margin-left: 78px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span>
                    </div>
                    </div>
                    <div class="subkatapenting"><b>KEMAMPUAN PROFESIONAL</b><br> <br>
                    <span class="subkatapenting">Microsoft Windows <span style='margin-left: 30px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br>
                    <span class="subkatapenting">Windows <span style='margin-left: 82px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br>
                    <span class="subkatapenting">Mac OSX<span style='margin-left: 82px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br>
                    <span class="subkatapenting">Data Handling<span style='margin-left: 58px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br>
                    <span class="subkatapenting">Record Keeping<span style='margin-left: 48px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br>
                    <span class="subkatapenting">Web Skills<span style='margin-left: 78px;'>&#9899;&#9899;&#9899;&#9899;&#9899;</span><span style='opacity: 0.5;'>&#9899;&#9899;</span></span><br> <br>
                    </div>
                    
                </div>
            </div>
        <div class="judul">
            PROFILE
            <hr class="dotted">
            <span class="katapenting"><b>NAMA:</b></span><br>
            <span class="subkatapenting">{{ BiodataDua.name }}</span><br> <br>
            <span class="katapenting"><b>HARI ULANG TAHUN:</b></span><br>
            <span class="subkatapenting">{{ BiodataDua.dob }}</span><br> <br>
            <span class="katapenting"><b>ALAMAT:</b></span><br>
            <span class="subkatapenting">{{ BiodataDua.alamat }}</span><br> <br>
            <span class="katapenting"><b>WEBSITE:</b></span><br>
            PENGHARGAAN
            <hr class="dotted">
            - <br> <br>
            KONTAK
            <hr class="dotted">
            <span class="katapenting" style="margin-right: 40px;"><b> <span> <img src="https://e7.pngegg.com/pngimages/265/94/png-clipart-telephone-call-mobile-phones-rotary-dial-handset-round-signs-miscellaneous-black-and-white.png" style='position: absolute; margin-left: 57px; width: 40px; margin-top: 9px;'> </span> Rumah</b></span><br>
            <span class="subkatapenting" style="margin-right: 55px;">{{ BiodataDua.hn }}</span><br> 
            <span class="katapenting" style="margin-right: 45px;"><b><span> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmmRJwpN4WN2J6ofGlZcjvZhyKS3_AkdipNQ&usqp=CAU"  style='position: absolute; margin-left: 80px; width: 45px; margin-top: 9px;'> </span>Nomor HP</b></span><br>
            <span class="subkatapenting" style="margin-right: 50px;">{{ BiodataDua.pn }}</span><br> 
            <span class="katapenting" style="margin-right: 45px;"><b><span> <img src="https://cdn.kibrispdr.org/data/lambang-email-hitam-putih-6.jpg"  style='position: absolute; margin-left: 55px; width: 40px;'> </span>Email:</b></span><br>
            <span class="subkatapenting" style="margin-right: 45px;">{{ BiodataDua.email }}</span><br> <br>
            SOCIAL
            <hr class="dotted">
            <span class="katapenting" style="margin-right: 50px;"><b>Twitter:</b> <img src="https://image.flaticon.com/icons/png/512/49/49517.png"  style='width: 40px; position: absolute; margin-left: 10px;'> </span><br>
            <span class="subkatapenting" style="margin-right: 60px;">{{ BiodataDua.twit }}</span><br> 
            <span class="katapenting" style="margin-right: 50px;"><b>Facebook:</b> <img src="https://cdn.statically.io/img/image.flaticon.com/icons/png/512/37/37409.png" style='width: 40px; position: absolute; margin-left: 10px;'> </span><br>
            <span class="subkatapenting" style="margin-right: 60px;">{{ BiodataDua.facebook }}</span><br> 
        </div>
        </div>
        </span>
    </div>
    </div>
</template>
<script>
/* eslint-disable */
import axios from 'axios'
export default {
data(){
  return{
    BiodataDua: ''
  }
},
mounted() {
    this.load()
  },
  methods: {
    load(){
      axios.get('http://localhost:3000/BiodataDua').then(res => {
      this.BiodataDua = res.data
      }).catch ((err) => {
        console.log(err);
      })
    }
  }
}
</script>
<style scoped>
.all {
    margin-top: 1cm;
    margin-left: 7cm;
    margin-right: 9cm;
}
.img {
    width: 3cm;
    position: absolute;
    margin-left: 1cm;
    margin-top: 2cm;
}
.bordernama {
    background-color: rgb(13, 13, 90);
    color: white;
    font-size: 25px;
    height: 100px;
    padding-left: 5cm;
    padding-top: 15px;
    width: 16cm;
    font-family: 'Courier New', Courier, monospace;
}
.border1 {
    width: 4cm;
    padding: 25px;
    text-align: right;
    margin-top: 2cm;
    padding-left: 1cm;
    padding-right: 1cm;
    height: 25cm;
}
.judul {
    font-size: 25px;
    font-family: 'Courier New', Courier, monospace;
}
.katapenting {
    font-size: 16px;
    font-family: Arial, Helvetica, sans-serif;
}
.subkatapenting {
    font-size: 12px;
    font-family: Arial, Helvetica, sans-serif;
}
.dotted {
    border: 1px dotted;
    border-left: white;
    border-right: white;
    border-left: white;
    border-top: white;
}
.borderkotak {
    border: 1px none;
    background-color: #f1f1f1;
    text-align: left;
    margin-top: 10px;
    padding: 30px;
}
.border2 {
    background-color: white;
    position: absolute;
    margin-left: 5cm;
    width: 15cm;
    height: auto;
}
legend {
    border: 1px solid none;
    background-color: rgb(13, 13, 90);
    margin-left: 2cm;
    width: 2cm;
    font-size: small;
    text-align: center;
    color: white;
}
.borderatas {
    border: 1px solid none;
    background-color: rgb(13, 13, 90);
    color: rgb(13, 13, 90);
    width: 21cm;
}
.kper {
    position: absolute;
    margin-left: 7cm;
}
</style>