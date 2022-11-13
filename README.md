## Index.html

      <!DOCTYPE html>
      <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
        <link rel="stylesheet" href="style.css">
        <title>Tugas  UTS</title>
      </head>
      <body>
        <div class="container">
          <div class="bar">
           <h1 class="head"><strong>TUGAS PEMROGRAMAN WEB</strong></h1>
          </div>
          <div class="cont-tabel">
            <div class="body-tabel row">
              <h3 class="nama-tabel"><b>Tabel Riwayat Pendidikan</b></h3>
              <table class="table bg-light table-bordered table-hover shadow">
                <thead class="text-bg-dark head-tabel text-center">
                  <tr>
                    <th scope="col">No.</th>
                    <th scope="col">Pendidikan</th>
                    <th scope="col">Tahun</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <th scope="row" class="text-center">1</th>
                    <td>SD Negeri Kesamiran 01</td>
                    <td style="text-align:center">2008 - 2014</td>
                  </tr>
                  <tr>
                    <th scope="row" class="text-center">2</th>
                    <td>SMP Negeri 1 Tarub</td>
                    <td style="text-align:center">2014 - 2017</td>
                  </tr>
                  <tr>
                    <th scope="row" class="text-center">3</th>
                    <td>SMK Muhammadiyah Kramat</td>
                    <td style="text-align:center">2017 - 2020</td>
                  </tr>
                </tbody>
              </table>
            </div>
            <div class="body-tabel row">
              <h3 class="nama-tabel"><b>Tabel Riwayat Pekerjaan</b></h3>
              <table class="table bg-light table-bordered table-hover shadow">
                <thead class="text-bg-dark head-tabel text-center">
                  <tr>
                    <th scope="col">No.</th>
                    <th scope="col">Peusahaan</th>
                    <th scope="col">Tahun</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <th scope="row" class="text-center">1</th>
                    <td>PT. Aisin Indonesia</td>
                    <td style="text-align:center">2020 - 2021</td>
                  </tr>
                  <tr>
                    <th scope="row" class="text-center">2</th>
                    <td>PT. Honda Lock Indonesia</td>
                    <td style="text-align:center">2022 - 2022</td>
                  </tr>
                  <tr>
                    <th scope="row" class="text-center">3</th>
                    <td>PT. Sakura Java Indonesia</td>
                    <td style="text-align:center">2022 - Sekarang</td>
                  </tr>
                </tbody>
            </div>
            </table>
          </div>
          <div class="cont-fitur">
            <div class="cont-button">
              <button type="button" id="btn-biodata" class="button-show">Biodata</button>
              <button type="button" id="btn-kalkulator" class="button-show">Kalkulator</button>
            </div>
            <div class="cont-data">
              <div class="biodata-hide card shadow-lg" id="biodata">
                <h3>Informasi Biodata</h3>
                <div class="card-body body-data">
                  <table class="table table-borderless align-content-center">
                    <tbody>
                      <tr>
                        <td>Nama</td>
                        <td>:</td>
                        <td>Adi Setiawan</td>
                      </tr>
                      <tr>
                        <td>Tempat/Tgl lahir</td>
                        <td>:</td>
                        <td>Tegal, 24 Juni 2002</td>
                      </tr>
                      <tr>
                        <td>Jenis Kelamin</td>
                        <td>:</td>
                        <td>Laki - Laki</td>
                      </tr>
                      <tr>
                        <td>Alamat</td>
                        <td>:</td>
                        <td>Kesamiran RT 01/RW 01</td>
                      </tr>
                      <tr>
                        <td>Kecamatan</td>
                        <td>:</td>
                        <td>Tarub</td>
                      </tr>
                      <tr>
                        <td>Kabupaten</td>
                        <td>:</td>
                        <td>Tegal - Jawa Tengah</td>
                      </tr>
                      <tr>
                        <td>Agama</td>
                        <td>:</td>
                        <td>Islam</td>
                      </tr>
                      <tr>
                        <td>Status Perkawinan</td>
                        <td>:</td>
                        <td>Belum Menikah</td>
                      </tr>
                      <tr>
                        <td>Pekerjaan</td>
                        <td>:</td>
                        <td>Mahasiswa</td>
                      </tr>
                      <tr>
                        <td>Kewarganagaraan</td>
                        <td>:</td>
                        <td>WNI</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </div>
              <div class="kalkulator-hide" id="kalkulator">
                <div class="main">
                  <h2>Kalkulator</h2>
                  <form name="form">
                    <input class="textarea" readonly name="textarea">
                  </form>
                    <table>
                      <tr>
                        <td><input class="button btn-white" type="button" value="AC" onclick="clean()"></td>
                        <td><input class="button btn-white" type="button" value="C" onclick="back()"></td>
                        <td><input class="button btn-orange" type="button" value="/" onclick="insert(' / ')"></td>
                        <td><input class="button btn-orange" type="button" value="x" onclick="insert(' * ')"></td>
                      </tr>
                      <tr>
                        <td><input class="button" type="button" value="7" onclick="insert(7)"></td>
                        <td><input class="button" type="button" value="8" onclick="insert(8)"></td>
                        <td><input class="button" type="button" value="9" onclick="insert(9)"></td>
                        <td><input class="button btn-orange" type="button" value="-" onclick="insert(' - ')"></td>
                      </tr>
                      <tr>
                        <td><input class="button" type="button" value="4" onclick="insert(4)"></td>
                        <td><input class="button" type="button" value="5" onclick="insert(5)"></td>
                        <td><input class="button" type="button" value="6" onclick="insert(6)"></td>
                        <td><input class="button btn-orange" type="button" value="+" onclick="insert(' + ')"></td>
                      </tr>
                      <tr>
                        <td><input class="button" type="button" value="1" onclick="insert(1)"></td>
                        <td><input class="button" type="button" value="2" onclick="insert(2)"></td>
                        <td><input class="button" type="button" value="3" onclick="insert(3)"></td>
                        <td rowspan=2><input style="height:106px;" class="button btn-orange" type="button" value="=" onclick="equal()"></td>
                      </tr>
                      <tr>
                        <td><input class="button" type="button" value="0" onclick="insert(0)"></td>
                        <td><input class="button" type="button" value="00" onclick="insert('00')"></td>
                        <td><input class="button" type="button" value="." onclick="insert('.')"></td>
                      </tr>
                    </table>
                  </div>
              </div>
            </div>
          </div>
         </div>
         <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>
         <script src="script.js"></script>
       </body>
        <footer>
         <p style="font-family: cursive">~ Just Make it Simple ~</p>
        </footer>
      </html>

## Style.css

    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      body{
        background: linear-gradient(to bottom, grey, black,grey);
      }

      .container{
        padding: 50px;
      }

      .bar{
        background: linear-gradient(to right, black, grey, black);
      }

      .head{
        display: block;
        text-align: center;
        max-width: 338px;
        height: max-content;
        font-size: 24px;
        padding: 5px 0;
        margin: auto;
        color: #fff;
        padding-top: 20px;
        padding-bottom: 20px;
      }

      .cont-tabel{
        margin-top: 5vh;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
        gap: 50px;
      }

      .body-tabel{
        max-width: 600px;
      }

      .nama-tabel{
        font-size: 22px;
        margin: 0 auto;
        text-align: center;
        padding-bottom: 10px;
        color: #fff;
      }

      .head-tabel{
        background-color: #080808 !important;
      }


      .cont-fitur{
        width: 100%;
      }

      .cont-button{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        gap: 20px;
        justify-content: space-around;
        height: 80px;
      }

      .button-show{
        border: 1.5px solid #fff;
        background-color: transparent;
        color: #fff;
        padding: 8px 20px;
        border-radius: 10px;
        box-shadow: 2px 2px 4px #00000045;
        transition: .3s;
        height: 45px;
      }

      .button-show:hover{
        background-color: #fff;
        color: #0B372F;
        transform: scale(1.05);
        transition: .3s;
        box-shadow: 2px 2px 8px #00000065;
      }

      .cont-data{
        margin-top: 50px;
        width: 100%;
      }

      .biodata-hide{
        display: none;
      }

      .biodata-show {
        display: block;
        color: #0B372F;
        padding: 30px;
        border: 1px solid #0B372F;
        max-width: 600px;
        margin: 0 auto;
        margin-bottom: 100px;
      }

      .biodata-show > h3{
        font-size: 20px;
        display: block;
        text-align: center;
        border-bottom: 1px solid #0B372F;
        padding-bottom: 15px;
      }

      .body-data > div:nth-child(2) > p::before{
        content: ":";
        padding: 0 30px;
        font-weight: bold;
      }

      .kalkulator-hide{
        display: none;
      }
      .kalkulator-show{
        display: block;
      }

      .main {
          max-width: 310px;
          background: #000;
          padding: 15px;
          border-radius: 15px;
          box-shadow: 0 0 15px;
        margin: 0 auto;
      }

      .main h2 {
          text-align: center;
          color: #F69906;
          text-transform: uppercase;
      }

      .button {
          width: 60px;
          height: 60px;
          font-size: 25px;
          margin: 5px;
          cursor: pointer;
          border: none;
          background: #313131;
          color: #fff;
          border-radius: 30px;
      }

      .btn-orange {
          background:#F69906;
          color:#fff;
      }

      .btn-white{
        background:#D9D9D9;
          color:#333;
        font-weight: bold;
      }

      .textarea {
          width: 100%;
        height: 100px;
          margin: 0 auto;
          font-size: 30px;
          padding: 10px;
          border: none;
        outline: none;
          color: #fff;
        background-color: transparent;
          text-align: right;
      }

      footer {
        text-align: center;
        padding-top: 10px;
        padding-bottom: 5px;
        font-size: 28px;
        background-color: #000;
        color: grey;
      }
      
      
##Script.js

      const btnBiodata = document.getElementById('btn-biodata');
      const btnKalkulator = document.getElementById('btn-kalkulator');
      const biodata = document.getElementById('biodata');
      const kalkulator = document.getElementById('kalkulator');

      let bio = false;
      btnBiodata.addEventListener("click", function(){
        if(bio){
          biodata.setAttribute('class','biodata-hide card shadow-lg');
          btnBiodata.innerHTML = "Biodata";
          this.style.backgroundColor = "transparent";
          this.style.color = "#fff";
          bio = false;
        }else{
          biodata.setAttribute('class','biodata-show card shadow-lg');
          btnBiodata.innerHTML = "Hide Biodata";
          this.style.backgroundColor = "#fff";
          this.style.color = "#0B372F";
          bio = true;
        }
      });

      let kal = false;
      btnKalkulator.addEventListener("click", function(){
        if(kal){
          kalkulator.setAttribute('class','kalkulator-hide');
          btnKalkulator.innerHTML = "kalkulator";
          this.style.backgroundColor = "transparent";
          this.style.color = "#fff";
          kal = false;
        }else{
          kalkulator.setAttribute('class','kalkulator-show');
          btnKalkulator.innerHTML = "Hide kalkulator";
          this.style.backgroundColor = "#fff";
          this.style.color = "#0B372F";
          kal = true;
        }
      });



      // Insert angka ke textview
      function insert(num){
        document.form.textarea.value = document.form.textarea.value + num;
      }

      // Fungsi Hitung
      function equal(){
        var hasil = document.form.textarea.value;
        document.form.textarea.value = eval(hasil);
      }

      // Clean
      function clean(){
        document.form.textarea.value = "";
      }

      // Delete
      function back(){
        var hasil = document.form.textarea.value;
        document.form.textarea.value = hasil.substring(0,hasil.length-1);
      }
